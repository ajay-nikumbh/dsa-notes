# 02. Two Pointers

Two pointers is the technique that turns `O(n^2)` into `O(n)` by refusing to re-examine what has already been ruled out. Instead of testing every pair, you keep two indices and move them under a rule that guarantees no valid answer is ever skipped.

The pattern is easy to write and easy to get subtly wrong. The hard part is not the code — it is proving that the pointer you move can be discarded safely. This page covers the theory, all four forms with runnable code, the correctness arguments, and how to recognize the pattern.

## Contents

1. [The Core Idea](#1-the-core-idea)
2. [Why It Is Correct](#2-why-it-is-correct)
3. [When You Can Use It](#3-when-you-can-use-it)
4. [Form A: Converging Pointers](#4-form-a-converging-pointers)
5. [Form B: Slow and Fast](#5-form-b-slow-and-fast)
6. [Form C: Fixed Element Plus Scan](#6-form-c-fixed-element-plus-scan)
7. [Form D: Two Arrays](#7-form-d-two-arrays)
8. [Handling Duplicates](#8-handling-duplicates)
9. [Two Pointers vs Sliding Window](#9-two-pointers-vs-sliding-window)
10. [Choosing Which Pointer to Move](#10-choosing-which-pointer-to-move)
11. [Common Traps](#11-common-traps)
12. [Pattern Recognition Cheat Sheet](#12-pattern-recognition-cheat-sheet)
13. [Problems](#13-problems)

## 1. The Core Idea

A brute-force pair search looks at every combination:

```python
for i in range(n):
    for j in range(i + 1, n):
        check(nums[i], nums[j])        # O(n^2) pairs
```

Two pointers replaces that with a single walk. Each step moves one pointer, so the total work is bounded by how far the pointers can travel — `O(n)` steps, not `O(n^2)`.

```text
Converging:                    Slow / fast:

[ a  b  c  d  e  f ]           [ a  b  c  d  e  f ]
  ^              ^               ^  ^
  left        right              slow fast
  →              ←               →  →
  (meet in the middle)           (fast leads, slow follows)
```

The saving comes from a promise: **when you move a pointer, every pair involving the position you left behind has already been eliminated.** If you cannot make that promise, the technique does not apply.

## 2. Why It Is Correct

This is the part worth understanding properly, because it is what interviewers probe.

Take a sorted array and a target sum. Pointers at both ends:

```text
nums = [2, 7, 11, 15],  target = 9
        L          R
        2 + 15 = 17 > 9
```

The sum is too big, so we move `R` left. **Why is dropping index 3 safe?**

`nums[3] = 15` is the largest value. Pairing it with anything still available (`nums[0]`, `nums[1]`, `nums[2]`) gives a sum **at least** `2 + 15 = 17`, because `nums[0]` is the smallest remaining value. Every one of those pairs is ≥ 17 > 9. So no pair using index 3 can work, and discarding it loses nothing.

Generalized:

| Condition | Move | Because |
|:---|:---|:---|
| `sum < target` | `left += 1` | `nums[left]` with the largest remaining partner is still too small; no pair using `left` works |
| `sum > target` | `right -= 1` | `nums[right]` with the smallest remaining partner is still too big; no pair using `right` works |

Each step permanently eliminates one index. With `n` indices, the loop runs at most `n` times.

**The general shape of the argument:** to justify moving a pointer, show that the position being abandoned cannot participate in any remaining answer. If you can prove that, the algorithm is correct. If you cannot, you have a bug.

### A harder case: Container With Most Water

Area is `width * min(height[left], height[right])`. Say `height[left] < height[right]`; we move `left`. Why is that safe?

Any pair still involving `left` must use a partner strictly inside the current window. Such a pair has:

- **smaller width** — the partner is nearer than `right`
- **height still capped by `height[left]`** — since `height[left]` is the shorter wall, `min(...)` cannot exceed it

Both factors are ≤ the current values, so no such pair beats the area we already recorded. Discarding `left` is safe. Moving the *taller* wall instead would be wrong: a taller partner could still raise the minimum.

## 3. When You Can Use It

Two pointers needs a **monotonic property** — moving a pointer must change the result in a predictable direction.

| You have | Two pointers works? | Why |
|:---|:---:|:---|
| Sorted array, pair sum | Yes | Moving `left` only increases the sum |
| Unsorted array, pair sum | No | A move tells you nothing; use a hashmap |
| Unsorted, but you may sort | Yes | Sort first, if you do not need original indices |
| Palindrome check | Yes | Symmetric comparison from both ends |
| In-place filter/partition | Yes | Slow/fast, no ordering needed |
| Two sorted lists to merge | Yes | Smallest unprocessed element is at one of the two heads |
| Need original indices | Careful | Sorting destroys them — use a hashmap instead |

**The diagnostic question:** if I move this pointer, do I know for certain the target quantity goes up (or down)? Yes means the pattern applies.

## 4. Form A: Converging Pointers

Start at both ends, move inward, stop when they meet.

```python
def two_sum_sorted(nums, target):
    left, right = 0, len(nums) - 1
    while left < right:
        total = nums[left] + nums[right]
        if total == target:
            return [left, right]
        elif total < target:
            left += 1            # need a bigger sum
        else:
            right -= 1           # need a smaller sum
    return []
```

### Palindrome: comparison instead of arithmetic

Same skeleton, different test — and skipping logic inside the loop.

```python
def is_palindrome(s):
    left, right = 0, len(s) - 1
    while left < right:
        while left < right and not s[left].isalnum():
            left += 1                       # skip junk from the left
        while left < right and not s[right].isalnum():
            right -= 1                      # skip junk from the right
        if s[left].lower() != s[right].lower():
            return False
        left += 1
        right -= 1
    return True
```

The `left < right` guard inside the inner loops is essential — without it, a string of pure punctuation runs the pointers past each other.

### Maximizing instead of matching

Here you evaluate at every step rather than searching for one answer.

```python
def max_area(height):
    left, right = 0, len(height) - 1
    best = 0
    while left < right:
        best = max(best, (right - left) * min(height[left], height[right]))
        if height[left] < height[right]:
            left += 1               # always discard the shorter wall
        else:
            right -= 1
    return best
```

### Carrying state: Trapping Rain Water

The pointers carry running maxima, which is what removes the need for prefix/suffix arrays.

```python
def trap(height):
    if not height:
        return 0
    left, right = 0, len(height) - 1
    left_max = right_max = 0
    water = 0
    while left < right:
        if height[left] <= height[right]:
            # left is the limiting side, so left_max alone decides the level
            if height[left] >= left_max:
                left_max = height[left]
            else:
                water += left_max - height[left]
            left += 1
        else:
            if height[right] >= right_max:
                right_max = height[right]
            else:
                water += right_max - height[right]
            right -= 1
    return water
```

**Why `height[left] <= height[right]` licenses using `left_max`:** water at `left` is bounded by `min(left_max, right_max)`. We know some wall at or before `right` is at least `height[left]`, so `right_max >= height[left]`. If `left_max` is the smaller of the two bounds, it alone sets the level — and if it is not, then `height[left] >= left_max` and no water sits there anyway.

## 5. Form B: Slow and Fast

Both pointers move the same direction. `fast` reads everything; `slow` marks where the next kept element belongs. This is the in-place filter, and one skeleton covers a whole family of problems.

```python
def move_zeroes(nums):
    slow = 0
    for fast in range(len(nums)):
        if nums[fast] != 0:                       # the predicate
            nums[slow], nums[fast] = nums[fast], nums[slow]
            slow += 1
        # invariant: nums[0..slow-1] are the kept values, in original order
    return nums
```

Change only the `if` to solve a different problem:

```python
def remove_element(nums, val):
    slow = 0
    for fast in range(len(nums)):
        if nums[fast] != val:
            nums[slow] = nums[fast]
            slow += 1
    return slow                       # new logical length


def remove_duplicates_sorted(nums):
    if not nums:
        return 0
    slow = 1
    for fast in range(1, len(nums)):
        if nums[fast] != nums[slow - 1]:     # compare to last kept value
            nums[slow] = nums[fast]
            slow += 1
    return slow
```

### Cycle detection (Floyd's algorithm)

A different use of the same two-speed idea: `fast` moves twice per step. If a cycle exists they must eventually collide, because the gap between them changes by exactly one each step.

```python
def has_cycle(head):
    slow = fast = head
    while fast and fast.next:
        slow = slow.next            # one step
        fast = fast.next.next       # two steps
        if slow is fast:
            return True
    return False
```

## 6. Form C: Fixed Element Plus Scan

For triplets and beyond: sort, fix one element, then two-pointer the remainder. This turns `O(n^3)` into `O(n^2)`.

```python
def three_sum(nums):
    nums.sort()
    result = []
    n = len(nums)
    for i in range(n - 2):
        if nums[i] > 0:                              # sorted: no triplet can reach 0
            break
        if i > 0 and nums[i] == nums[i - 1]:         # skip duplicate anchors
            continue
        left, right = i + 1, n - 1
        while left < right:
            total = nums[i] + nums[left] + nums[right]
            if total == 0:
                result.append([nums[i], nums[left], nums[right]])
                left += 1
                right -= 1
                while left < right and nums[left] == nums[left - 1]:
                    left += 1                        # skip duplicate seconds
                while left < right and nums[right] == nums[right + 1]:
                    right -= 1                       # skip duplicate thirds
            elif total < 0:
                left += 1
            else:
                right -= 1
    return result
```

The nesting generalizes: kSum is `k - 2` nested loops wrapping a two-pointer core, costing `O(n^(k-1))`.

| Problem | Structure | Time |
|:---|:---|:---:|
| 2Sum (sorted) | Two pointers | `O(n)` |
| 3Sum | Fix 1 + two pointers | `O(n^2)` |
| 4Sum | Fix 2 + two pointers | `O(n^3)` |

## 7. Form D: Two Arrays

One pointer per array, advancing whichever head is smaller.

```python
def merge_sorted(a, b):
    i = j = 0
    out = []
    while i < len(a) and j < len(b):
        if a[i] <= b[j]:
            out.append(a[i]); i += 1
        else:
            out.append(b[j]); j += 1
    out.extend(a[i:])         # at most one of these is non-empty
    out.extend(b[j:])
    return out
```

### Merging in place, from the back

When the destination has padding at the end, write backwards so you never clobber unread data.

```python
def merge_in_place(nums1, m, nums2, n):
    p1, p2, write = m - 1, n - 1, m + n - 1
    while p2 >= 0:                              # only nums2 must be drained
        if p1 >= 0 and nums1[p1] > nums2[p2]:
            nums1[write] = nums1[p1]; p1 -= 1
        else:
            nums1[write] = nums2[p2]; p2 -= 1
        write -= 1
    return nums1
```

**Why backwards is safe:** `write` is always ≥ `p1`, so every slot overwritten has already been read or was empty padding. Looping while `p2 >= 0` is enough — if `nums2` drains first, whatever remains in `nums1` is already in place.

## 8. Handling Duplicates

Duplicate handling is where most two-pointer solutions break. Sorting puts equal values next to each other, which makes skipping them a simple adjacency check.

Two distinct skips are needed, and forgetting either produces duplicate answers:

```python
# 1. Skip duplicate anchors (before scanning)
if i > 0 and nums[i] == nums[i - 1]:
    continue

# 2. Skip duplicate partners (AFTER recording a hit)
while left < right and nums[left] == nums[left - 1]:
    left += 1
while left < right and nums[right] == nums[right + 1]:
    right -= 1
```

The order matters: record the answer, advance both pointers once, *then* skip duplicates. Skipping first would step over a legitimate answer.

```text
nums = [-2, 0, 0, 2, 2],  target 0

i=0 (-2), left=1 (0), right=4 (2)   ->  -2+0+2 = 0, record [-2,0,2]
advance: left=2, right=3
skip dups: nums[2]==nums[1] -> left=3 ; nums[3]==nums[4] -> right=2
left >= right, stop.        Result: one triplet, not four.
```

## 9. Two Pointers vs Sliding Window

Sliding window is two pointers where both move forward and the span between them *is* the answer. The distinction is worth being precise about:

| | Two pointers (converging) | Sliding window |
|:---|:---|:---|
| Direction | Toward each other | Both forward |
| What matters | The pair of values | The contents of the span |
| Typical question | "find a pair with..." | "longest/shortest span with..." |
| Needs sorted input | Usually yes | No |
| Breaks on negatives | No | Often yes |

```python
def longest_window_sum_at_most_k(nums, k):
    """All values must be positive for this to be valid."""
    left = total = best = 0
    for right in range(len(nums)):
        total += nums[right]              # grow
        while total > k:
            total -= nums[left]           # shrink from the left
            left += 1
        best = max(best, right - left + 1)
    return best
```

**Why positives are required:** shrinking the window must reduce the sum. With a negative value, removing it *increases* the sum, so the `while` may exit at the wrong place. For arrays with negatives, use prefix sums plus a hashmap instead.

## 10. Choosing Which Pointer to Move

The rule differs per problem, and picking wrong is the classic bug. Each rule below is backed by the correctness argument from section 2.

| Problem | Rule | Justification |
|:---|:---|:---|
| Two Sum II | Sum too small → `left++`; too big → `right--` | Sorted, so each move changes the sum in exactly one direction |
| 3Sum | Same, per fixed anchor | The inner scan is just Two Sum II |
| Valid Palindrome | Skip non-alphanumerics, else move both | Comparison is symmetric |
| Container With Most Water | Always move the **shorter** wall | Width only shrinks; only a taller minimum can improve area |
| Trapping Rain Water | Process the side with the **smaller** height | That side's running max is the true bound |
| Move Zeroes | `fast` always; `slow` only on a keeper | `slow` marks the write position |
| Merge Sorted Array | Move whichever head is larger (writing backwards) | Largest unplaced element goes into the highest free slot |

## 11. Common Traps

| Trap | Broken | Correct |
|:---|:---|:---|
| Wrong loop bound | `while left <= right` on a pair search | `while left < right` — an element cannot pair with itself |
| Missing inner guard | `while not s[left].isalnum(): left += 1` | Add `left < right` or it runs off the end |
| Skipping dups too early | Skip before recording the answer | Record, advance once, then skip |
| Only skipping the anchor | Duplicate triplets in the output | Skip `left` and `right` too |
| Forgetting to sort | Two pointers on unsorted input | Sort first, or use a hashmap |
| Sorting when indices matter | Returns positions from the sorted array | Use a hashmap, or sort `(value, index)` pairs |
| Moving the taller wall | Container With Most Water returns too small | Always move the shorter one |
| `isalpha()` for palindromes | Drops digits, so `"0P"` misbehaves | Use `isalnum()` |
| Forward in-place merge | Overwrites unread values | Fill from the back |
| Sliding window with negatives | Shrink step is not monotonic | Prefix sums + hashmap |

## 12. Pattern Recognition Cheat Sheet

| Signal in the problem | Form | Cost |
|:---|:---|:---:|
| Sorted array, "find a pair summing to X" | Converging | `O(n)` / `O(1)` |
| "Is it a palindrome" | Converging | `O(n)` / `O(1)` |
| "Maximize area/distance between two positions" | Converging | `O(n)` / `O(1)` |
| "Remove/move elements in-place" | Slow / fast | `O(n)` / `O(1)` |
| "Remove duplicates from sorted array" | Slow / fast | `O(n)` / `O(1)` |
| "Find a cycle" | Slow / fast (Floyd) | `O(n)` / `O(1)` |
| "Triplets/quadruplets summing to X" | Sort + fix + scan | `O(n^(k-1))` |
| "Merge two sorted sequences" | Two arrays | `O(m+n)` |
| "Longest/shortest span satisfying X" | Sliding window | `O(n)` |
| Water/height/container between bars | Converging with state | `O(n)` / `O(1)` |

## 13. Problems

| # | Tier | Problem | Difficulty | Form | Key Idea | Time | Space |
|:---:|:---:|:---|:---:|:---|:---|:---:|:---:|
| 1 | Basics | [125. Valid Palindrome](01.%20Basics/01.%20125.%20Valid%20Palindrome.md) | Easy | Converging | Skip non-alphanumerics, compare inward | `O(n)` | `O(1)` |
| 2 | Medium | [15. 3Sum](02.%20Medium/01.%2015.%203Sum.md) | Medium | Fix + scan | Sort, fix one, two-pointer the rest | `O(n^2)` | `O(1)` |
| 3 | Medium | [167. Two Sum II](02.%20Medium/02.%20167.%20Two%20Sum%20II%20-%20Input%20Array%20Is%20Sorted.md) | Medium | Converging | Sortedness makes each move decidable | `O(n)` | `O(1)` |
| 4 | Medium | [11. Container With Most Water](02.%20Medium/03.%2011.%20Container%20With%20Most%20Water.md) | Medium | Converging | Always move the shorter line | `O(n)` | `O(1)` |
| 5 | Hard | [42. Trapping Rain Water](03.%20Hard/01.%2042.%20Trapping%20Rain%20Water.md) | Hard | Converging + state | Process the smaller side; its max bounds it | `O(n)` | `O(1)` |

### How the Optimization Pays Off

| Problem | Brute Force | Optimal | What two pointers buys |
|:---|:---:|:---:|:---|
| Valid Palindrome | `O(n)` time, `O(n)` space | `O(n)` / `O(1)` | No cleaned-string copy |
| Two Sum II | `O(n^2)` | `O(n)` / `O(1)` | No hashmap |
| 3Sum | `O(n^3)` | `O(n^2)` | No set for dedup |
| Container With Most Water | `O(n^2)` | `O(n)` | Skips provably worse pairs |
| Trapping Rain Water | `O(n^2)` | `O(n)` / `O(1)` | No prefix/suffix arrays |

## Where This Leads

| Skill built here | Used later in |
|:---|:---|
| Correctness by elimination | Binary search, greedy proofs |
| Slow/fast pointers | Linked list cycles, middle node, quickselect |
| Sort-then-scan | 4Sum, merge intervals, closest-pair problems |
| Converging with state | Trapping Rain Water 2D, histogram problems |
| Window growth/shrink | The entire sliding window topic |
