# 42. Trapping Rain Water

| | |
|---|---|
| **Difficulty** | Hard |
| **Pattern** | Two Pointers / Monotonic Stack |
| **LeetCode** | [42. Trapping Rain Water](https://leetcode.com/problems/trapping-rain-water/) |
| **Time** | `O(n)` |
| **Space** | `O(1)` |

---

## 1. Problem Statement

Given `n` non-negative integers representing an elevation map where the width of each bar is `1`, compute how much water it can trap after raining.

### Examples

```text
Input:  height = [0,1,0,2,1,0,1,3,2,1,2,1]
Output: 6
Explanation: The above elevation map (black section) is represented by
array [0,1,0,2,1,0,1,3,2,1,2,1]. In this case, 6 units of rain water
(blue section) are being trapped.
```

```text
Input:  height = [4,2,0,3,2,5]
Output: 9
```

### Constraints

- `n == height.length`
- `1 <= n <= 2 * 10^4`
- `0 <= height[i] <= 10^5`

---

## 2. Problem Explanation

We are given an array `height`.

Each value represents the height of a vertical bar.

We need to calculate how much rain water can be trapped between these bars.

Example:

```text
height = [0,1,0,2,1,0,1,3,2,1,2,1]
```

Output:

```text
6
```

Water trapped = 6 units.

---

## 3. Core Intuition

Water can be trapped at an index only if there is a taller bar on the **left** and a taller bar on the **right**.

For every index `i`, water above that bar depends on:

```text
left_max  = tallest bar from left side up to i
right_max = tallest bar from right side up to i
```

Water trapped at index `i`:

```text
min(left_max, right_max) - height[i]
```

Why minimum?

Because water overflows from the shorter boundary.

Example:

```text
left_max  = 3
right_max = 2
height[i] = 1
```

Water level can only go up to 2, not 3. So:

```text
water = min(3, 2) - 1 = 1
```

---

## 4. Brute Force Approach

### Idea

For every index:

1. Find the maximum height on its left.
2. Find the maximum height on its right.
3. Water at that index is:

```text
min(left_max, right_max) - height[i]
```

### Example

```text
height = [4, 2, 0, 3, 2, 5]
```

For index 2, value 0:

```text
left side max  = max(4, 2, 0) = 4
right side max = max(0, 3, 2, 5) = 5

water = min(4, 5) - 0 = 4
```

For index 3, value 3:

```text
left side max  = max(4, 2, 0, 3) = 4
right side max = max(3, 2, 5) = 5

water = min(4, 5) - 3 = 1
```

### Complexity

For every index, we scan left and right.

| | | |
|---|---|---|
| **Time** | `O(n^2)` | Scanning both sides for every index. |
| **Space** | `O(1)` | Ignoring output variables. |

### Code

```python
# Define the class solution
class Solution:

    # Function to calculate trapped rain water
    def trap(self, height: List[int]) -> int:

        # Store length of height array
        n = len(height)

        # Store total trapped water
        total_water = 0

        # Traverse every index
        for i in range(n):

            # Store maximum height on the left side including current index
            left_max = 0

            # Find left maximum from index 0 to i
            for left in range(i + 1):

                # Update left maximum
                left_max = max(left_max, height[left])

            # Store maximum height on the right side including current index
            right_max = 0

            # Find right maximum from index i to n - 1
            for right in range(i, n):

                # Update right maximum
                right_max = max(right_max, height[right])

            # Water at current index depends on smaller boundary
            water_at_current = min(left_max, right_max) - height[i]

            # Add current trapped water to total
            total_water += water_at_current

        # Return total trapped water
        return total_water
```

---

## 5. Better Solution Using Prefix and Suffix Arrays

### Idea

Instead of calculating `left_max` and `right_max` again and again, precompute them.

Create two arrays:

```text
prefix_max[i] = maximum height from index 0 to i
suffix_max[i] = maximum height from index i to n - 1
```

Then for every index:

```text
water = min(prefix_max[i], suffix_max[i]) - height[i]
```

### Example

```text
height = [4, 2, 0, 3, 2, 5]
```

Prefix max:

```text
[4, 4, 4, 4, 4, 5]
```

Suffix max:

```text
[5, 5, 5, 5, 5, 5]
```

Now water:

```text
i = 0 -> min(4,5)-4 = 0
i = 1 -> min(4,5)-2 = 2
i = 2 -> min(4,5)-0 = 4
i = 3 -> min(4,5)-3 = 1
i = 4 -> min(4,5)-2 = 2
i = 5 -> min(5,5)-5 = 0
```

Total:

```text
0 + 2 + 4 + 1 + 2 + 0 = 9
```

### Complexity

| | | |
|---|---|---|
| **Time** | `O(n)` | Three linear passes. |
| **Space** | `O(n)` | Because we use prefix and suffix arrays. |

### Code

```python
# Define the class solution
class Solution:

    # Function to calculate trapped rain water
    def trap(self, height: List[int]) -> int:

        # Store length of height array
        n = len(height)

        # If there are less than 3 bars, water cannot be trapped
        if n < 3:
            return 0

        # prefix_max[i] stores maximum height from 0 to i
        prefix_max = [0] * n

        # suffix_max[i] stores maximum height from i to n - 1
        suffix_max = [0] * n

        # First prefix max is first height
        prefix_max[0] = height[0]

        # Build prefix maximum array
        for i in range(1, n):

            # Maximum so far from left side
            prefix_max[i] = max(prefix_max[i - 1], height[i])

        # Last suffix max is last height
        suffix_max[n - 1] = height[n - 1]

        # Build suffix maximum array
        for i in range(n - 2, -1, -1):

            # Maximum so far from right side
            suffix_max[i] = max(suffix_max[i + 1], height[i])

        # Store total trapped water
        total_water = 0

        # Traverse every index
        for i in range(n):

            # Water level is decided by smaller of left max and right max
            water_level = min(prefix_max[i], suffix_max[i])

            # Water above current bar
            water_at_current = water_level - height[i]

            # Add current water to total
            total_water += water_at_current

        # Return total trapped water
        return total_water
```

---

## 6. Optimal Solution Using Two Pointers

### Deep Intuition

The prefix/suffix solution uses extra arrays.

Can we avoid them? Yes.

Use two pointers:

```text
left  = 0
right = n - 1
```

Maintain:

```text
left_max  = maximum height seen from left side
right_max = maximum height seen from right side
```

At every step, compare:

```text
height[left] and height[right]
```

If:

```text
height[left] <= height[right]
```

Then the left side is the limiting side. So we can safely calculate water at `left`.

Why?

Because if `height[left] <= height[right]`, then there is at least one right boundary tall enough to support water on the left side. So water at `left` depends on `left_max`.

Similarly, if:

```text
height[right] < height[left]
```

Then right side is the limiting side, and water at `right` depends on `right_max`.

---

## 7. Two Pointer Logic

For left pointer:

```text
If height[left] >= left_max:
    update left_max
Else:
    water += left_max - height[left]
```

For right pointer:

```text
If height[right] >= right_max:
    update right_max
Else:
    water += right_max - height[right]
```

---

## 8. Most Optimal Complexity

| | | |
|---|---|---|
| **Time** | `O(n)` | Each index is visited once. |
| **Space** | `O(1)` | Only variables are used. |

---

## 9. Optimal Code

```python
# Define the class solution
class Solution:

    # Function to calculate trapped rain water
    def trap(self, height: List[int]) -> int:

        # Store length of height array
        n = len(height)

        # If less than 3 bars exist, water cannot be trapped
        if n < 3:
            return 0

        # Left pointer starts from beginning
        left = 0

        # Right pointer starts from end
        right = n - 1

        # Maximum height seen so far from left side
        left_max = 0

        # Maximum height seen so far from right side
        right_max = 0

        # Store total trapped water
        total_water = 0

        # Continue until both pointers meet
        while left < right:

            # If left bar is smaller or equal, process left side
            if height[left] <= height[right]:

                # If current left bar is greater than or equal to left_max
                if height[left] >= left_max:

                    # Update left_max because this becomes new left boundary
                    left_max = height[left]

                # Otherwise water can be trapped above current left bar
                else:

                    # Add trapped water at current left index
                    total_water += left_max - height[left]

                # Move left pointer one step right
                left += 1

            # If right bar is smaller, process right side
            else:

                # If current right bar is greater than or equal to right_max
                if height[right] >= right_max:

                    # Update right_max because this becomes new right boundary
                    right_max = height[right]

                # Otherwise water can be trapped above current right bar
                else:

                    # Add trapped water at current right index
                    total_water += right_max - height[right]

                # Move right pointer one step left
                right -= 1

        # Return total trapped water
        return total_water
```

### Alternate Shorter Version

```python
class Solution:

    # Define the method
    def trap(self, height: List[int]) -> int:

        # Handle the edge case
        if not height: return 0

        # Declare the result for storing the final result
        result = 0

        # Define the 2 pointer's
        left = 0
        right = len(height) - 1

        # Declare the leftmax and rightmax
        left_max = height[left]
        right_max = height[right]

        # Loop till the condition fails
        while left < right:

            # If the left_max is less then the right_max then shift the left pointer
            if left_max < right_max:

                # Increment the left pointer by 1
                left += 1

                # Update the left_max
                left_max = max(left_max, height[left])

                # Update the result
                result += left_max - height[left]

            # Else if the right_max is less then the left_max then shift the right pointer
            else:

                # Increment the right pointer by 1
                right -= 1

                # Update the right_max
                right_max = max(right_max, height[right])

                # Update the result
                result += right_max - height[right]

        # Finally return the result
        return result
```

---

## 10. Working Example

```python
solution = Solution()

height = [4, 2, 0, 3, 2, 5]

answer = solution.trap(height)

print(answer)
```

Output:

```text
9
```

---

## 11. Dry Run of Optimal Solution

Input:

```text
height = [4, 2, 0, 3, 2, 5]
```

Initial:

```text
left = 0
right = 5
left_max = 0
right_max = 0
total_water = 0
```

### Step 1

```text
height[left]  = 4
height[right] = 5
```

Since `4 <= 5`, process left.

```text
height[0] = 4 >= left_max = 0
left_max = 4
left = 1
```

State:

```text
left = 1
right = 5
left_max = 4
right_max = 0
water = 0
```

### Step 2

```text
height[left]  = 2
height[right] = 5
```

Since `2 <= 5`, process left.

```text
height[1] = 2 < left_max = 4
water += 4 - 2 = 2
```

Move left:

```text
left = 2
water = 2
```

### Step 3

```text
height[left]  = 0
height[right] = 5
```

Since `0 <= 5`, process left.

```text
height[2] = 0 < left_max = 4
water += 4 - 0 = 4
```

Move left:

```text
left = 3
water = 6
```

### Step 4

```text
height[left]  = 3
height[right] = 5
```

Since `3 <= 5`, process left.

```text
height[3] = 3 < left_max = 4
water += 4 - 3 = 1
```

Move left:

```text
left = 4
water = 7
```

### Step 5

```text
height[left]  = 2
height[right] = 5
```

Since `2 <= 5`, process left.

```text
height[4] = 2 < left_max = 4
water += 4 - 2 = 2
```

Move left:

```text
left = 5
water = 9
```

Loop ends because:

```text
left == right
```

Final answer:

```text
9
```

---

## 12. Stack-Based Solution

Since this is also a stack topic, we should know the monotonic stack solution.

### Stack Intuition

We keep a stack of indexes with decreasing heights.

When we find a bar taller than the stack top, it means we found a **right boundary**.

Then the popped bar becomes the **bottom** of trapped water.

Formula:

```text
distance = current_index - left_boundary_index - 1
bounded_height = min(height[current_index], height[left_boundary_index]) - height[bottom]
water = distance * bounded_height
```

### Stack Example

```text
height = [4, 2, 0, 3, 2, 5]
```

At height 3, we can trap water over bars 0 and 2 using 4 as left boundary and 3 as right boundary.

At height 5, we trap more water using previous bars as bottom.

### Stack Complexity

| | | |
|---|---|---|
| **Time** | `O(n)` | Each index is pushed and popped at most once. |
| **Space** | `O(n)` | For stack. |

### Code

```python
# Define the class solution
class Solution:

    # Function to calculate trapped rain water using monotonic stack
    def trap(self, height: List[int]) -> int:

        # Store total trapped water
        total_water = 0

        # Stack stores indexes of bars
        stack = []

        # Traverse every bar by index
        for current_index in range(len(height)):

            # While current bar is taller than bar at stack top
            while stack and height[current_index] > height[stack[-1]]:

                # Popped index is the bottom of water container
                bottom_index = stack.pop()

                # If stack becomes empty, no left boundary exists
                if not stack:

                    # Stop processing
                    break

                # Left boundary index is now stack top
                left_boundary_index = stack[-1]

                # Width between left boundary and current right boundary
                distance = current_index - left_boundary_index - 1

                # Height of water is limited by smaller boundary minus bottom height
                bounded_height = min(height[current_index], height[left_boundary_index]) - height[bottom_index]

                # Add trapped water for this bounded region
                total_water += distance * bounded_height

            # Push current index into stack
            stack.append(current_index)

        # Return total trapped water
        return total_water
```

---

## 13. Which Solution Should You Use in Interview?

For LeetCode 42, the best final answer is usually:

```text
Two pointers -> O(n) time, O(1) space
```

But because this is also a stack topic, also mention:

```text
Monotonic stack -> O(n) time, O(n) space
```

Interview strategy:

```text
Start with brute force
Then prefix/suffix DP
Then monotonic stack
Finally two pointers as most space-optimized
```

---

## 14. Final Complexity Summary

| Approach | Time Complexity | Space Complexity | Notes |
|---|---|---|---|
| Brute force | `O(n^2)` | `O(1)` | Finds left/right max every time |
| Prefix/suffix arrays | `O(n)` | `O(n)` | Easy and very clear |
| Monotonic stack | `O(n)` | `O(n)` | Stack-based solution |
| Two pointers | `O(n)` | `O(1)` | Most space optimal |

---

## 15. Interview Key Points

Say this in interview:

> Water at any index depends on the smaller of the maximum height on its left and right. The brute force approach recalculates these maximums for every index. We can optimize using prefix and suffix maximum arrays. Further, we can reduce space using two pointers by processing the side with the smaller height, because that side determines the water level. This gives `O(n)` time and `O(1)` space.

For stack-specific explanation:

> I can also solve it using a monotonic decreasing stack. When a current bar is taller than the stack top, the popped bar becomes the bottom, the current bar becomes the right boundary, and the new stack top becomes the left boundary. Then I calculate trapped water using width and bounded height.
