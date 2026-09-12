# 11. Container With Most Water

| | |
|---|---|
| **Difficulty** | Medium |
| **Pattern** | Two Pointers |
| **LeetCode** | [11. Container With Most Water](https://leetcode.com/problems/container-with-most-water/) |
| **Time** | `O(n)` |
| **Space** | `O(1)` |

---

## 1. Problem Statement

You are given an integer array `height` of length `n`. There are `n` vertical lines drawn such that the two endpoints of the `i`th line are `(i, 0)` and `(i, height[i])`.

Find two lines that together with the x-axis form a container, such that the container contains the most water.

Return *the maximum amount of water a container can store*.

**Notice** that you may not slant the container.

### Examples

```text
Input:  height = [1,8,6,2,5,4,8,3,7]
Output: 49
Explanation: The above vertical lines are represented by array
[1,8,6,2,5,4,8,3,7]. In this case, the max area of water the
container can contain is 49.
```

```text
Input:  height = [1,1]
Output: 1
```

### Constraints

- `n == height.length`
- `2 <= n <= 10^5`
- `0 <= height[i] <= 10^4`

---

## 2. Problem Explanation

You are given an integer array `height`.

Each element represents a vertical line:

```text
height[i] = height of line at index i
```

You need to choose **two lines** such that together with the x-axis they form a container that can store the **maximum amount of water**.

The water area between two lines is:

```text
area = width * minimum_height
```

Where:

```text
width          = right_index - left_index
minimum_height = min(height[left_index], height[right_index])
```

### Example

```text
Input:
height = [1,8,6,2,5,4,8,3,7]

Output:
49
```

Best pair:

```text
left index  = 1, height = 8
right index = 8, height = 7
```

Area:

```text
width  = 8 - 1 = 7
height = min(8, 7) = 7

area = 7 * 7 = 49
```

---

## 3. Core Intuition

Water stored between two lines depends on two things:

```text
1. Width between the two lines
2. Smaller height among the two lines
```

Important point:

```text
The shorter line decides the water level.
```

For example:

```text
height[left]  = 8
height[right] = 3
```

Even though left is tall, water can only go up to height 3. So:

```text
container height = min(8, 3) = 3
```

---

## 4. Brute Force Approach

### Idea

Try every possible pair of lines.

For each pair:

```text
Calculate width
Calculate minimum height
Calculate area
Update maximum area
```

### Example

```text
height = [1,8,6,2,5,4,8,3,7]
```

Check pairs:

```text
(0,1), (0,2), (0,3), ...
(1,2), (1,3), (1,4), ...
...
```

For pair `(1,8)`:

```text
height[1] = 8
height[8] = 7

width = 8 - 1 = 7
min_height = 7

area = 49
```

This becomes the maximum.

### Complexity

| | | |
|---|---|---|
| **Time** | `O(n^2)` | Because we check every pair. |
| **Space** | `O(1)` | Because we only store the maximum area. |

### Code

```python
# Import the required lib's
from typing import List

# Define the class solution
class Solution:
    def maxArea(self, height: List[int]) -> int:

        # Store the maximum water area found so far
        max_water = 0

        # Store the total number of vertical lines
        n = len(height)

        # Pick the first line using index i
        for i in range(n):

            # Pick the second line using index j after i
            for j in range(i + 1, n):

                # Calculate the width between both selected lines
                width = j - i

                # Calculate the smaller height because water is limited by shorter line
                min_height = min(height[i], height[j])

                # Calculate the water area for this pair
                current_area = width * min_height

                # Update maximum water area if current area is larger
                max_water = max(max_water, current_area)

        # Return the largest area found after checking all pairs
        return max_water
```

---

## 5. Better / Optimal Approach — Two Pointers

There is no separate meaningful "better but not optimal" approach here like hash map.

The main optimized solution is directly the **two pointers approach**.

---

## 6. Most Optimal Approach — Two Pointers

### Intuition

Start with the widest possible container:

```text
left  = 0
right = len(height) - 1
```

This gives the maximum possible width.

Now calculate the area. Then we need to move one pointer inward.

The question is:

```text
Should we move the taller line or the shorter line?
```

Answer:

```text
Move the shorter line.
```

### Why move the shorter line?

Suppose:

```text
height[left]  = 1
height[right] = 7
```

Water level is limited by:

```text
min(1, 7) = 1
```

If we move the taller line `right`, then width decreases and height is still limited by 1.

So area cannot improve.

But if we move the shorter line `left`, we may find a taller line that increases the limiting height.

That can potentially give a better area.

### Rule

```text
If height[left] < height[right]:
    move left pointer forward

Else:
    move right pointer backward
```

Because we always discard the shorter side.

---

## 7. Working Example

```text
height = [1,8,6,2,5,4,8,3,7]
```

Initial:

```text
left  = 0 -> height = 1
right = 8 -> height = 7
```

Area:

```text
width = 8
min_height = min(1, 7) = 1
area = 8 * 1 = 8

max_water = 8
```

Since left height is smaller, move left:

```text
left  = 1 -> height = 8
right = 8 -> height = 7
```

Area:

```text
width = 7
min_height = min(8, 7) = 7
area = 7 * 7 = 49

max_water = 49
```

Now right height is smaller, move right:

```text
left  = 1 -> height = 8
right = 7 -> height = 3
```

Area:

```text
width = 6
min_height = min(8, 3) = 3
area = 18

max_water = 49
```

Continue. No later area becomes bigger than 49.

Final answer:

```text
49
```

---

## 8. Time and Space Complexity of Optimal Solution

| | | |
|---|---|---|
| **Time** | `O(n)` | Because each pointer moves at most n times. |
| **Space** | `O(1)` | Because we only use a few variables. |

---

## 9. Optimal Code

```python
# Import the required lib's
from typing import List

# Define the class solution
class Solution:

    # Define the method
    def maxArea(self, height: List[int]) -> int:

        # Initialize the left pointer at the first line
        left = 0

        # Initialize the right pointer at the last line
        right = len(height) - 1

        # Store the maximum water area found so far
        max_water = 0

        # Continue until both pointers meet
        while left < right:

            # Calculate the width between the current two lines
            width = right - left

            # Calculate the limiting height using the shorter line
            min_height = min(height[left], height[right])

            # Calculate current container area
            current_area = width * min_height

            # Update maximum area if current area is greater
            max_water = max(max_water, current_area)

            # If left line is shorter, move left pointer forward
            if height[left] < height[right]:

                # Move left inward to possibly find a taller line
                left += 1

            # Otherwise, right line is shorter or equal
            else:

                # Move right inward to possibly find a taller line
                right -= 1

        # Return the maximum water area found
        return max_water
```

---

## 10. Dry Run Table

Input:

```text
height = [1,8,6,2,5,4,8,3,7]
```

| left | right | height[left] | height[right] | width | min height | area | max area | Move |
|---|---|---|---|---|---|---|---|---|
| 0 | 8 | 1 | 7 | 8 | 1 | 8 | 8 | left |
| 1 | 8 | 8 | 7 | 7 | 7 | 49 | 49 | right |
| 1 | 7 | 8 | 3 | 6 | 3 | 18 | 49 | right |
| 1 | 6 | 8 | 8 | 5 | 8 | 40 | 49 | right |
| 1 | 5 | 8 | 4 | 4 | 4 | 16 | 49 | right |
| 1 | 4 | 8 | 5 | 3 | 5 | 15 | 49 | right |
| 1 | 3 | 8 | 2 | 2 | 2 | 4 | 49 | right |
| 1 | 2 | 8 | 6 | 1 | 6 | 6 | 49 | right |

Final answer:

```text
49
```

---

## 11. Interview Explanation

> I will start with two pointers at both ends because this gives the maximum possible width. For every pair, I calculate the area using the smaller height because water level is limited by the shorter line. Then I move the pointer at the shorter line inward, because moving the taller line cannot improve the height limitation and only reduces width. This way, every move has a chance to find a better container. The time complexity is `O(n)`, and space complexity is `O(1)`.

### Key Interview Point

The most important logic is:

```text
Always move the shorter line.
```

Because:

```text
Area = width * min(left_height, right_height)
```

When width is decreasing, the only way to improve area is to find a taller minimum height.
