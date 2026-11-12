# 01. Array

Everything in DSA starts here. An array is the only data structure where you can jump to any element in one step, and that single property is what makes binary search, two pointers, sliding window, and prefix sums possible.

This page teaches the topic from zero: what an array actually is in memory, the operations and their costs, every foundational pattern with runnable code, and the traps that cause most wrong answers. Read it once end to end, then use the problem notes for practice.

## Contents

1. [What an Array Is](#1-what-an-array-is)
2. [Cost of Every Operation](#2-cost-of-every-operation)
3. [Python Lists vs Real Arrays](#3-python-lists-vs-real-arrays)
4. [Traversal: The Foundation](#4-traversal-the-foundation)
5. [Single-Pass Tracking](#5-single-pass-tracking)
6. [Two Pointers on an Array](#6-two-pointers-on-an-array)
7. [Prefix Sums](#7-prefix-sums)
8. [Hashing for Subarrays](#8-hashing-for-subarrays)
9. [Kadane's Algorithm](#9-kadanes-algorithm)
10. [In-Place Reversal and Rotation](#10-in-place-reversal-and-rotation)
11. [Sorting as a Preprocessing Step](#11-sorting-as-a-preprocessing-step)
12. [Bit Tricks on Arrays](#12-bit-tricks-on-arrays)
13. [Partitioning and the Dutch National Flag](#13-partitioning-and-the-dutch-national-flag)
14. [Boyer-Moore Voting](#14-boyer-moore-voting)
15. [Matrix Basics](#15-matrix-basics)
16. [Common Traps](#16-common-traps)
17. [Pattern Recognition Cheat Sheet](#17-pattern-recognition-cheat-sheet)
18. [Problems](#18-problems)

## 1. What an Array Is

An array is a block of memory where every element has the same size and they sit next to each other. That is the whole idea, and every property follows from it.

```text
nums = [10, 20, 30, 40]

index:      0     1     2     3
          ┌─────┬─────┬─────┬─────┐
memory:   │ 10  │ 20  │ 30  │ 40  │
          └─────┴─────┴─────┴─────┘
address:  1000  1004  1008  1012      (4 bytes per int)
```

To find `nums[i]`, the machine computes:

```text
address = base_address + (i * size_of_element)
```

That is one multiplication and one addition — constant time, no matter how big the array is or which index you want. This is called **random access**, and it is the array's superpower.

The cost of that layout is rigidity: because elements must stay adjacent, inserting into the middle forces everything after it to shift.

```text
Insert 99 at index 1 in [10, 20, 30, 40]:

[10, __, 20, 30, 40]     everything after index 1 shifts right
[10, 99, 20, 30, 40]     then write

Cost: O(n)
```

## 2. Cost of Every Operation

| Operation | Time | Why |
|:---|:---:|:---|
| Read `nums[i]` | `O(1)` | Direct address computation |
| Write `nums[i] = x` | `O(1)` | Same |
| Append at end | `O(1)` amortized | Usually free space; occasionally reallocates |
| Insert at front/middle | `O(n)` | Must shift all later elements |
| Delete at front/middle | `O(n)` | Must shift all later elements back |
| Delete at end | `O(1)` | Nothing to shift |
| Search (unsorted) | `O(n)` | Must check every element |
| Search (sorted) | `O(log n)` | Binary search |
| Sort | `O(n log n)` | Comparison-based limit |

**The rule that matters:** reading is free, reordering is expensive. Good array algorithms read a lot and write little.

### Why append is "amortized O(1)"

A dynamic array over-allocates. When it fills, it doubles capacity and copies everything — an `O(n)` operation. But doubling means that copy happens rarely, and spreading its cost across all the cheap appends averages out to `O(1)` per append.

```text
capacity 4, size 4  -> append -> allocate 8, copy 4 elements, then write
next 4 appends are free
```

## 3. Python Lists vs Real Arrays

Python's `list` is a dynamic array of *pointers*, not a block of raw integers. This matters in two ways:

| Thing | C-style array | Python list |
|:---|:---|:---|
| Element type | Fixed, all same | Anything, mixed |
| Memory | One contiguous block of values | Contiguous block of pointers to objects |
| `nums[i]` | One address computation | Address computation, then follow pointer |
| Growth | Fixed size | Auto-resizes |

Some Python operations look `O(1)` but are not:

| Looks cheap | Actually | Why |
|:---|:---:|:---|
| `nums.insert(0, x)` | `O(n)` | Shifts everything right |
| `nums.pop(0)` | `O(n)` | Shifts everything left |
| `nums[1:]` | `O(n)` | Builds a whole new list |
| `x in nums` | `O(n)` | Linear scan |
| `nums.pop()` | `O(1)` | Removes from the end |
| `x in some_set` | `O(1)` | Hashing |

**Interview trap:** writing `nums.pop(0)` inside a loop turns an `O(n)` algorithm into `O(n^2)`. Use `collections.deque` when you need cheap removal from the front.

## 4. Traversal: The Foundation

Every array pattern is a variation on walking the array. Know these four forms.

```python
nums = [10, 20, 30, 40]

# 1. Values only — when the index does not matter
for value in nums:
    print(value)

# 2. Index only — when you need position or will write back
for i in range(len(nums)):
    print(i, nums[i])

# 3. Both — the usual choice
for i, value in enumerate(nums):
    print(i, value)

# 4. Backwards — when writing into the array as you go
for i in range(len(nums) - 1, -1, -1):
    print(i, nums[i])
```

### Comparing neighbours

Many problems ask about adjacent pairs (is it sorted? where does it drop?). Guard the boundary so you never read past the end.

```python
# Compare each element with the next one
for i in range(len(nums) - 1):      # stop one early
    if nums[i] > nums[i + 1]:
        print("drop at", i)
```

### Circular traversal

When the array wraps around (rotations, circular buffers), use the modulo operator.

```python
n = len(nums)
for i in range(n):
    nxt = nums[(i + 1) % n]         # after the last element, wraps to index 0
```

## 5. Single-Pass Tracking

**The idea:** carry the answer in a variable and update it as you walk. No sorting, no nested loops, no extra memory.

This is the most common `O(n)` / `O(1)` pattern in existence.

```python
def largest(nums):
    largest_so_far = nums[0]                 # start with a real element
    for i in range(1, len(nums)):
        if nums[i] > largest_so_far:
            largest_so_far = nums[i]
        # invariant: largest_so_far is the max of nums[0..i]
    return largest_so_far
```

The comment is the important part. A **loop invariant** is a statement that is true at the end of every iteration. If your invariant holds on iteration `i`, and it still holds on `i+1`, then it holds at the end — which means the answer is correct. Get in the habit of naming the invariant; it is how you prove a loop works.

### Tracking two values at once

Here the update **order** is the whole problem.

```python
def second_largest(nums):
    largest = second = float('-inf')
    for x in nums:
        if x > largest:
            second = largest          # demote the old champion FIRST
            largest = x               # then crown the new one
        elif x > second and x != largest:
            second = x
    return second
```

Swap those two lines and `second` becomes a copy of `largest`. Whenever you track two running extremes, write the demotion before the promotion.

### Why `float('-inf')` and not `0`

| Init | `[-5, -2, -9]` | Correct? |
|:---|:---:|:---:|
| `largest = 0` | returns `0` | No — 0 is not in the array |
| `largest = nums[0]` | returns `-2` | Yes |
| `largest = float('-inf')` | returns `-2` | Yes |

Use `-inf`/`+inf` (or the first element) as sentinels. Never `0` — it silently breaks on all-negative input.

### Streak counting

```python
def max_consecutive_ones(nums):
    best = streak = 0
    for x in nums:
        if x == 1:
            streak += 1
            best = max(best, streak)     # record before it can be reset
        else:
            streak = 0                   # break the run
    return best
```

## 6. Two Pointers on an Array

**The idea:** two indices moving under a rule, replacing a nested loop. `O(n^2)` becomes `O(n)`.

### Form A: converging (opposite ends)

Requires the array to be **sorted** or to have a monotonic property, so that moving a pointer changes the result predictably.

```python
def two_sum_sorted(nums, target):
    left, right = 0, len(nums) - 1
    while left < right:
        total = nums[left] + nums[right]
        if total == target:
            return [left, right]
        elif total < target:
            left += 1          # need more: only the left side can grow
        else:
            right -= 1         # need less: only the right side can shrink
    return []
```

**Why it never misses an answer:** if `total < target`, then `nums[left]` paired with *any* remaining element is also too small (everything left of `right` is smaller still). So no valid pair uses `left` — discarding it is safe. Each step eliminates exactly one candidate, and there are `n` of them.

### Form B: slow and fast (same direction)

`fast` reads every element; `slow` marks where the next kept element belongs. This is the in-place filter.

```python
def move_zeroes(nums):
    slow = 0
    for fast in range(len(nums)):
        if nums[fast] != 0:
            nums[slow], nums[fast] = nums[fast], nums[slow]
            slow += 1
        # invariant: nums[0..slow-1] are the non-zeroes, in original order
    return nums
```

The same skeleton removes duplicates, partitions by a predicate, or compacts a list — only the `if` changes.

### Form C: writing from the back

When the destination array has spare room at the end, fill backwards so you never overwrite unread data.

```python
def merge(nums1, m, nums2, n):
    p1, p2, write = m - 1, n - 1, m + n - 1
    while p2 >= 0:                                  # nums2 must be drained
        if p1 >= 0 and nums1[p1] > nums2[p2]:
            nums1[write] = nums1[p1]
            p1 -= 1
        else:
            nums1[write] = nums2[p2]
            p2 -= 1
        write -= 1
    return nums1
```

**Why backwards is safe:** `write` always sits at or to the right of `p1`. Every slot you overwrite has already been read or was empty padding.

## 7. Prefix Sums

**The idea:** precompute running totals so any range sum becomes one subtraction.

```text
nums   = [ 2,  4,  1,  7,  3]
prefix = [ 2,  6,  7, 14, 17]      prefix[i] = nums[0] + ... + nums[i]
```

The identity that makes it useful:

```text
sum(i..j) = prefix[j] - prefix[i-1]
```

Check it: `sum(1..3) = 4 + 1 + 7 = 12`, and `prefix[3] - prefix[0] = 14 - 2 = 12`.

```python
def build_prefix(nums):
    prefix = [0] * len(nums)
    prefix[0] = nums[0]
    for i in range(1, len(nums)):
        prefix[i] = prefix[i - 1] + nums[i]
    return prefix
```

Build once in `O(n)`, then answer unlimited range queries in `O(1)` each.

### The padded version

Adding a leading zero removes the `i == 0` special case:

```python
def build_prefix_padded(nums):
    prefix = [0] * (len(nums) + 1)
    for i, x in enumerate(nums):
        prefix[i + 1] = prefix[i] + x
    return prefix                     # sum(i..j) == prefix[j+1] - prefix[i]
```

Prefer this form. The off-by-one bugs in the unpadded version are relentless.

## 8. Hashing for Subarrays

**The idea:** combine prefix sums with a hashmap to find subarrays in one pass.

The key realization: you do not need to know where a subarray starts. If the running sum is `S` at index `j`, and you want a subarray summing to `k`, you need some earlier index where the running sum was `S - k`.

```text
      i           j
  ....|===========|....
  prefix=S-k    prefix=S

  the marked span sums to S - (S-k) = k
```

```python
def longest_subarray_sum_k(nums, k):
    first_seen = {0: -1}          # sum 0 occurs "before" the array starts
    running = 0
    best = 0
    for i, x in enumerate(nums):
        running += x
        if running - k in first_seen:
            best = max(best, i - first_seen[running - k])
        if running not in first_seen:
            first_seen[running] = i      # keep the EARLIEST index only
    return best
```

Two details carry the whole algorithm:

| Detail | Reason |
|:---|:---|
| Seed `{0: -1}` | Lets a subarray starting at index 0 be found |
| Only store first occurrence | Earliest start gives the **longest** span |

If you were counting subarrays instead of maximizing length, you would store *counts* rather than first indices:

```python
def count_subarrays_sum_k(nums, k):
    from collections import defaultdict
    seen = defaultdict(int)
    seen[0] = 1
    running = count = 0
    for x in nums:
        running += x
        count += seen[running - k]     # every earlier match is a valid subarray
        seen[running] += 1
    return count
```

**Why not sliding window?** A sliding window needs sums to grow when you extend and shrink when you contract. With negative numbers that breaks — extending can *decrease* the sum. Sliding window works only for all-positive arrays; prefix + hashmap works always.

## 9. Kadane's Algorithm

**The idea:** the maximum subarray ending at `i` is either just `nums[i]`, or `nums[i]` glued onto the best subarray ending at `i-1`.

```python
def max_subarray(nums):
    best_here = best_overall = nums[0]
    for x in nums[1:]:
        best_here = max(x, best_here + x)      # extend, or start fresh here
        best_overall = max(best_overall, best_here)
    return best_overall
```

The decision `max(x, best_here + x)` is the whole algorithm: if the running sum has gone negative, it can only hurt, so drop it and restart.

```text
nums      = [-2,  1, -3,  4, -1,  2,  1, -5,  4]
best_here = [-2,  1, -2,  4,  3,  5,  6,  1,  5]
best_ovr  = [-2,  1,  1,  4,  4,  5,  6,  6,  6]   -> answer 6
```

Initialize with `nums[0]`, not `0` — otherwise an all-negative array wrongly returns `0`.

## 10. In-Place Reversal and Rotation

Reversal is the building block. Two pointers swapping inward:

```python
def reverse(nums, start, end):
    while start < end:
        nums[start], nums[end] = nums[end], nums[start]
        start += 1
        end -= 1
```

### The triple-reversal rotation

To rotate right by `k`, reverse the whole array, then reverse each piece.

```text
nums = [1, 2, 3, 4, 5, 6, 7],  k = 3

reverse all:        [7, 6, 5, 4, 3, 2, 1]
reverse first k=3:  [5, 6, 7, 4, 3, 2, 1]
reverse the rest:   [5, 6, 7, 1, 2, 3, 4]   correct
```

```python
def rotate(nums, k):
    n = len(nums)
    k %= n                      # k can exceed n; rotating by n is a no-op
    reverse(nums, 0, n - 1)
    reverse(nums, 0, k - 1)
    reverse(nums, k, n - 1)
    return nums
```

**Why it works:** reversing the whole array puts the last `k` elements at the front but in reverse order. Reversing each block restores their internal order. `O(n)` time, `O(1)` space.

**Never forget `k %= n`.** Without it, `k > n` indexes out of range.

## 11. Sorting as a Preprocessing Step

Sorting costs `O(n log n)` but buys structure that often pays for itself:

| After sorting | You gain |
|:---|:---|
| Equal values sit together | Duplicate detection in one pass |
| Order is monotonic | Two pointers and binary search become valid |
| Extremes are at the ends | `nums[0]` and `nums[-1]` are min and max |

```python
nums.sort()                              # in place, returns None
ordered = sorted(nums)                   # returns a new list

nums.sort(reverse=True)                  # descending
pairs.sort(key=lambda p: p[1])           # by second field
pairs.sort(key=lambda p: (-p[1], p[0]))  # desc by second, then asc by first
```

Ask before sorting: **do I need the original indices?** If yes, sort `(value, index)` pairs, or do not sort at all — the classic Two Sum returns indices, which is exactly why it uses a hashmap instead of sorting.

## 12. Bit Tricks on Arrays

XOR replaces a hash set in some counting problems, dropping space to `O(1)`.

| Property | Meaning |
|:---|:---|
| `a ^ a = 0` | A value cancels itself |
| `a ^ 0 = a` | Zero is the identity |
| `a ^ b == b ^ a` | Order does not matter |

Because order does not matter and pairs cancel, XOR-ing a list where everything appears twice except one leaves exactly the loner:

```python
def single_number(nums):
    result = 0
    for x in nums:
        result ^= x
    return result
```

```text
[4, 1, 2, 1, 2]  ->  4^1^2^1^2  ->  4^(1^1)^(2^2)  ->  4^0^0  ->  4
```

The same idea finds a missing number by XOR-ing indices against values:

```python
def missing_number(nums):
    result = len(nums)                 # n is never an index
    for i, x in enumerate(nums):
        result ^= i ^ x
    return result
```

The sum formula `n*(n+1)//2 - sum(nums)` also works and reads more clearly, but can overflow in languages with fixed-width integers. XOR never overflows.

## 13. Partitioning and the Dutch National Flag

**The idea:** rearrange an array into regions using pointers as region boundaries. The loop invariant *is* the algorithm.

Three-way partition (Sort Colors) keeps four regions while scanning:

```text
[ 0 0 0 | 1 1 1 | ? ? ? ? | 2 2 2 ]
         low     mid      high
  known0   known1  unknown   known2
```

```python
def sort_colors(nums):
    low, mid, high = 0, 0, len(nums) - 1
    while mid <= high:
        if nums[mid] == 0:
            nums[low], nums[mid] = nums[mid], nums[low]
            low += 1
            mid += 1          # swapped-in value came from below mid: already seen
        elif nums[mid] == 1:
            mid += 1          # already in place
        else:
            nums[mid], nums[high] = nums[high], nums[mid]
            high -= 1         # do NOT advance mid: swapped-in value is unexamined
    return nums
```

The asymmetry is the whole trick. Swapping with `low` brings back a value you already classified, so `mid` advances. Swapping with `high` brings back an unknown, so `mid` stays to examine it.

## 14. Boyer-Moore Voting

**The idea:** find an element appearing more than `n/2` times using `O(1)` space, by pairing off different values until only the majority can survive.

```python
def majority_element(nums):
    candidate, count = None, 0
    for x in nums:
        if count == 0:
            candidate = x          # no one is winning; adopt a new candidate
        count += 1 if x == candidate else -1
    return candidate
```

**Why it works:** each decrement cancels one occurrence of the candidate against one of something else. An element occurring more than `n/2` times has more copies than everything else combined, so it cannot be fully cancelled.

`count` is *not* a frequency — it is a lead margin. If a majority is not guaranteed, add a second pass to confirm the candidate really appears more than `n/2` times.

## 15. Matrix Basics

A 2D array is rows of arrays. Two conventions to keep straight:

```text
matrix[row][col]       row first, then column
m = len(matrix)        number of rows
n = len(matrix[0])     number of columns
```

### Transpose

Reflect across the main diagonal. Iterate only the upper triangle, or you swap everything back.

```python
def transpose(matrix):
    n = len(matrix)
    for i in range(n):
        for j in range(i + 1, n):          # j starts at i+1, not 0
            matrix[i][j], matrix[j][i] = matrix[j][i], matrix[i][j]
    return matrix
```

### Rotate 90 degrees clockwise

Transpose, then reverse each row. Two reflections compose into a rotation.

```text
1 2 3      transpose     1 4 7      reverse rows    7 4 1
4 5 6      ─────────>    2 5 8      ───────────>    8 5 2
7 8 9                    3 6 9                      9 6 3
```

```python
def rotate(matrix):
    transpose(matrix)
    for row in matrix:
        row.reverse()
    return matrix
```

Anticlockwise is the same idea: transpose, then reverse each *column* (or reverse the row order first, then transpose).

### Spiral traversal

Keep four boundaries and shrink them inward.

```python
def spiral_order(matrix):
    if not matrix:
        return []
    top, bottom = 0, len(matrix) - 1
    left, right = 0, len(matrix[0]) - 1
    out = []
    while top <= bottom and left <= right:
        for c in range(left, right + 1):
            out.append(matrix[top][c])
        top += 1
        for r in range(top, bottom + 1):
            out.append(matrix[r][right])
        right -= 1
        if top <= bottom:                      # guard: row may already be consumed
            for c in range(right, left - 1, -1):
                out.append(matrix[bottom][c])
            bottom -= 1
        if left <= right:                      # guard: column may already be consumed
            for r in range(bottom, top - 1, -1):
                out.append(matrix[r][left])
            left += 1
    return out
```

The two `if` guards are not optional. On a single-row matrix, `top` passes `bottom` after the first pass; without the guard the bottom row is emitted twice.

### Marking in place

To record "this row must be cleared" without extra space, store the flag inside the matrix itself — typically in row 0 and column 0. The catch is that `matrix[0][0]` belongs to both markers, so column 0 needs its own separate flag variable, and the writing pass must run backwards so markers are read before being overwritten.

## 16. Common Traps

| Trap | Broken | Correct |
|:---|:---|:---|
| Off-by-one at the end | `for i in range(n): nums[i+1]` | `for i in range(n - 1)` |
| Mutating while iterating | `for x in nums: nums.remove(x)` | Build a new list, or iterate backwards |
| `0` as a sentinel | `largest = 0` | `float('-inf')` or `nums[0]` |
| Aliasing, not copying | `b = a` then `b[0] = 9` changes `a` | `b = a[:]` or `list(a)` |
| Shared inner lists | `[[0] * 3] * 3` — rows are the same object | `[[0] * 3 for _ in range(3)]` |
| `pop(0)` in a loop | `O(n^2)` overall | `collections.deque`, or a read pointer |
| Rotation overflow | `k` used raw | `k %= n` first |
| Empty input | `nums[0]` raises | Guard `if not nums: return ...` |

The `[[0] * 3] * 3` trap is worth seeing:

```python
grid = [[0] * 3] * 3       # three references to ONE list
grid[0][0] = 1
# [[1, 0, 0], [1, 0, 0], [1, 0, 0]]   all rows changed

grid = [[0] * 3 for _ in range(3)]    # three independent lists
grid[0][0] = 1
# [[1, 0, 0], [0, 0, 0], [0, 0, 0]]   correct
```

## 17. Pattern Recognition Cheat Sheet

Read the problem, match the signal, reach for the pattern.

| Signal in the problem | Pattern | Cost |
|:---|:---|:---:|
| "max/min/count" over one pass | Single-pass tracking | `O(n)` / `O(1)` |
| Array is **sorted**, find a pair | Two pointers, converging | `O(n)` / `O(1)` |
| "in-place", "without extra space" | Two pointers, slow/fast | `O(n)` / `O(1)` |
| Destination has room at the end | Fill from the back | `O(n)` / `O(1)` |
| "subarray sum equals k" | Prefix sum + hashmap | `O(n)` / `O(n)` |
| "sum of range i..j", many queries | Prefix sum array | `O(n)` build, `O(1)` query |
| "maximum subarray sum" | Kadane | `O(n)` / `O(1)` |
| "rotate by k" | Triple reversal | `O(n)` / `O(1)` |
| "every element twice except one" | XOR | `O(n)` / `O(1)` |
| "find a pair", array unsorted | Hashmap of seen values | `O(n)` / `O(n)` |
| "longest window satisfying X", positives | Sliding window | `O(n)` / `O(1)` |
| Need all pairs/triplets | Sort, then fix one + two pointers | `O(n^2)` |
| "sort 3 distinct values in place" | Dutch National Flag | `O(n)` / `O(1)` |
| "element appearing > n/2 times" | Boyer-Moore voting | `O(n)` / `O(1)` |
| "count subarrays summing to k" | Prefix sum + hashmap of counts | `O(n)` / `O(n)` |
| "longest consecutive sequence" | Hash set, start only at run heads | `O(n)` / `O(n)` |
| "rotate/transpose a matrix" | Transpose then reverse | `O(n^2)` / `O(1)` |
| "spiral / layer-by-layer" | Four shrinking boundaries | `O(m*n)` |
| "next lexicographic arrangement" | Pivot, swap, reverse suffix | `O(n)` / `O(1)` |

### Choosing between the three "find a pair" tools

| Situation | Use | Why |
|:---|:---|:---|
| Sorted, want values | Two pointers | `O(1)` space |
| Unsorted, want original indices | Hashmap | Sorting destroys indices |
| Unsorted, want values, space-constrained | Sort then two pointers | Trades `O(n log n)` time for `O(1)` space |

## 18. Problems

Folders follow the pattern order below. **Written** = full note; **Pending** = question added, note to follow.

### 01. Basic Traversal and Selection

| # | Problem | Difficulty | Key Idea | Status |
|:---:|:---|:---:|:---|:---:|
| 1 | [Largest in Array](01.%20Basic%20Traversal%20and%20Selection/01.%20Largest%20in%20Array.md) | Basic | Track the biggest value seen so far in one pass | Written |
| 2 | [Second Largest](01.%20Basic%20Traversal%20and%20Selection/02.%20Second%20Largest.md) | Easy | Keep two trackers; demote the old max before promoting a new one | Written |
| 3 | [Array Search](01.%20Basic%20Traversal%20and%20Selection/03.%20Array%20Search.md) | Basic | Scan left to right and stop at the first match | Written |
| 4 | [485. Max Consecutive Ones](01.%20Basic%20Traversal%20and%20Selection/04.%20485.%20Max%20Consecutive%20Ones.md) | Easy | Running streak that resets on a zero | Written |
| 5 | [Array Leaders](01.%20Basic%20Traversal%20and%20Selection/05.%20Array%20Leaders.md) | Easy | Scan from the right with a running maximum | Written |
| 6 | [First and Second Smallests](01.%20Basic%20Traversal%20and%20Selection/06.%20First%20and%20Second%20Smallests.md) | Easy | Second-largest trick mirrored for the minimum | Written |
| 7 | [Find Second Smallest and Second Largest](01.%20Basic%20Traversal%20and%20Selection/07.%20Find%20Second%20Smallest%20and%20Second%20Largest%20Element%20in%20an%20Array.md) | Easy | Four trackers updated in one pass | Written |
| 8 | [1295. Find Numbers with Even Number of Digits](01.%20Basic%20Traversal%20and%20Selection/08.%201295.%20Find%20Numbers%20with%20Even%20Number%20of%20Digits.md) | Easy | Count digits of each number and check if the count is even | Written |
| 9 | [1480. Running Sum of 1d Array](01.%20Basic%20Traversal%20and%20Selection/09.%201480.%20Running%20Sum%20of%201d%20Array.md) | Easy | Each answer is the previous answer plus the current number | Written |
| 10 | [1512. Number of Good Pairs](01.%20Basic%20Traversal%20and%20Selection/10.%201512.%20Number%20of%20Good%20Pairs.md) | Easy | A value seen k times before adds k new pairs | Written |
| 11 | [1672. Richest Customer Wealth](01.%20Basic%20Traversal%20and%20Selection/11.%201672.%20Richest%20Customer%20Wealth.md) | Easy | Sum each row and keep the largest sum | Written |
| 12 | [1732. Find the Highest Altitude](01.%20Basic%20Traversal%20and%20Selection/12.%201732.%20Find%20the%20Highest%20Altitude.md) | Easy | Running sum of gains; track its maximum including 0 | Written |
| 13 | [1920. Build Array from Permutation](01.%20Basic%20Traversal%20and%20Selection/13.%201920.%20Build%20Array%20from%20Permutation.md) | Easy | ans[i] = nums[nums[i]]; in-place trick stores two values in one cell | Written |
| 14 | [1929. Concatenation of Array](01.%20Basic%20Traversal%20and%20Selection/14.%201929.%20Concatenation%20of%20Array.md) | Easy | ans[i] and ans[i + n] both get nums[i] | Written |
| 15 | [2011. Final Value of Variable After Performing Operations](01.%20Basic%20Traversal%20and%20Selection/15.%202011.%20Final%20Value%20of%20Variable%20After%20Performing%20Operations.md) | Easy | Add 1 for every '++' operation and subtract 1 for every '--' | Written |
| 16 | [2114. Maximum Number of Words Found in Sentences](01.%20Basic%20Traversal%20and%20Selection/16.%202114.%20Maximum%20Number%20of%20Words%20Found%20in%20Sentences.md) | Easy | Words = spaces + 1; keep the maximum | Written |
| 17 | [2176. Count Equal and Divisible Pairs in an Array](01.%20Basic%20Traversal%20and%20Selection/17.%202176.%20Count%20Equal%20and%20Divisible%20Pairs%20in%20an%20Array.md) | Easy | Check every pair i < j for equal values and (i * j) % k == 0 | Written |
| 18 | [2574. Left and Right Sum Differences](01.%20Basic%20Traversal%20and%20Selection/18.%202574.%20Left%20and%20Right%20Sum%20Differences.md) | Easy | Right sum = total - left sum - current | Written |
| 19 | [2652. Sum Multiples](01.%20Basic%20Traversal%20and%20Selection/19.%202652.%20Sum%20Multiples.md) | Easy | Add every number from 1 to n divisible by 3, 5 or 7 | Written |
| 20 | [2798. Number of Employees Who Met the Target](01.%20Basic%20Traversal%20and%20Selection/20.%202798.%20Number%20of%20Employees%20Who%20Met%20the%20Target.md) | Easy | Count hours that are at least the target | Written |
| 21 | [2824. Count Pairs Whose Sum is Less than Target](01.%20Basic%20Traversal%20and%20Selection/21.%202824.%20Count%20Pairs%20Whose%20Sum%20is%20Less%20than%20Target.md) | Easy | Sort, then two pointers count many pairs at once | Written |
| 22 | [2942. Find Words Containing Character](01.%20Basic%20Traversal%20and%20Selection/22.%202942.%20Find%20Words%20Containing%20Character.md) | Easy | Collect indices of words that contain the character | Written |
| 23 | [2951. Find the Peaks](01.%20Basic%20Traversal%20and%20Selection/23.%202951.%20Find%20the%20Peaks.md) | Easy | An inner index is a peak if it beats both neighbors | Written |
| 24 | [3005. Count Elements With Maximum Frequency](20.%20Frequency%20Array%20%28Counting%20Buckets%29/03.%203005.%20Count%20Elements%20With%20Maximum%20Frequency.md) (see Frequency Array) | Easy | Count frequencies, then add all counts equal to the max | Written |
| 25 | [3065. Minimum Operations to Exceed Threshold Value I](01.%20Basic%20Traversal%20and%20Selection/25.%203065.%20Minimum%20Operations%20to%20Exceed%20Threshold%20Value%20I.md) | Easy | Count numbers smaller than k | Written |
| 26 | [3146. Permutation Difference between Two Strings](01.%20Basic%20Traversal%20and%20Selection/26.%203146.%20Permutation%20Difference%20between%20Two%20Strings.md) | Easy | Store each character's index in s, sum |index in s - index in t| | Written |
| 27 | [414. Third Maximum Number](01.%20Basic%20Traversal%20and%20Selection/27.%20414.%20Third%20Maximum%20Number.md) | Easy | Three distinct trackers shifted down like second largest | Written |
| 28 | [747. Largest Number At Least Twice of Others](01.%20Basic%20Traversal%20and%20Selection/28.%20747.%20Largest%20Number%20At%20Least%20Twice%20of%20Others.md) | Easy | Track largest and second largest; compare largest >= 2 * second | Written |
| 29 | [896. Monotonic Array](01.%20Basic%20Traversal%20and%20Selection/29.%20896.%20Monotonic%20Array.md) | Easy | One pass with two flags: ever went up, ever went down | Written |
| 30 | [941. Valid Mountain Array](01.%20Basic%20Traversal%20and%20Selection/30.%20941.%20Valid%20Mountain%20Array.md) | Easy | Walk up while increasing, then down while decreasing; must end at the last index | Written |
| 31 | [1299. Replace Elements with Greatest Element on Right Side](01.%20Basic%20Traversal%20and%20Selection/31.%201299.%20Replace%20Elements%20with%20Greatest%20Element%20on%20Right%20Side.md) | Easy | Scan from the right with a running maximum | Written |
| 32 | [1431. Kids With the Greatest Number of Candies](01.%20Basic%20Traversal%20and%20Selection/32.%201431.%20Kids%20With%20the%20Greatest%20Number%20of%20Candies.md) | Easy | Compare candies + extra with the current maximum | Written |

### 02. Rotation and Cyclic Arrays

| # | Problem | Difficulty | Key Idea | Status |
|:---:|:---|:---:|:---|:---:|
| 1 | [1752. Check if Array Is Sorted and Rotated](02.%20Rotation%20and%20Cyclic%20Arrays/01.%201752.%20Check%20if%20Array%20Is%20Sorted%20and%20Rotated.md) | Easy | Count drops around the circle; at most one is allowed | Written |
| 2 | [189. Rotate Array](02.%20Rotation%20and%20Cyclic%20Arrays/02.%20189.%20Rotate%20Array.md) | Medium | Reverse all, then reverse each part | Written |

### 03. Two Pointers and In-place Rearrangement

| # | Problem | Difficulty | Key Idea | Status |
|:---:|:---|:---:|:---|:---:|
| 1 | [283. Move Zeroes](03.%20Two%20Pointers%20and%20In-place%20Rearrangement/01.%20283.%20Move%20Zeroes.md) | Easy | Slow pointer marks where the next non-zero goes | Written |
| 2 | [88. Merge Sorted Array](03.%20Two%20Pointers%20and%20In-place%20Rearrangement/02.%2088.%20Merge%20Sorted%20Array.md) | Easy | Fill from the back so nothing is overwritten | Written |
| 3 | [2149. Rearrange Array Elements by Sign](03.%20Two%20Pointers%20and%20In-place%20Rearrangement/03.%202149.%20Rearrange%20Array%20Elements%20by%20Sign.md) | Medium | Two write cursors stepping by two | Written |

### 04. Hashing (Set)

| # | Problem | Difficulty | Key Idea | Status |
|:---:|:---|:---:|:---|:---:|
| 1 | [128. Longest Consecutive Sequence](04.%20Hashing%20%28Set%29/01.%20128.%20Longest%20Consecutive%20Sequence.md) | Medium | Start counting only from the first number of a run | Written |

### 05. XOR and Math Tricks

| # | Problem | Difficulty | Key Idea | Status |
|:---:|:---|:---:|:---|:---:|
| 1 | [136. Single Number](05.%20XOR%20and%20Math%20Tricks/01.%20136.%20Single%20Number.md) | Easy | XOR everything; pairs cancel | Written |
| 2 | [268. Missing Number](05.%20XOR%20and%20Math%20Tricks/02.%20268.%20Missing%20Number.md) | Easy | Expected sum minus actual sum, or XOR of indices and values | Written |
| 3 | [Missing And Repeating](05.%20XOR%20and%20Math%20Tricks/03.%20Missing%20And%20Repeating.md) | Medium | Two equations from sum and sum of squares | Written |

### 06. Sorting + Two Pointers

All three notes have story pictures with icons, full-width tables, and a constraints chart.

| # | Problem | Difficulty | Key Idea | Status |
|:---:|:---|:---:|:---|:---:|
| 1 | [1. Two Sum](06.%20Sorting%20%2B%20Two%20Pointers/01.%201.%20Two%20Sum.md) | Easy | Hash map of complements, or sort + two pointers | Written |
| 2 | [15. 3Sum](06.%20Sorting%20%2B%20Two%20Pointers/02.%2015.%203Sum.md) | Medium | Fix one, two pointers on the rest, skip duplicates | Written |
| 3 | [18. 4Sum](06.%20Sorting%20%2B%20Two%20Pointers/03.%2018.%204Sum.md) | Medium | Fix two, two pointers on the rest | Written |

### 07. Dutch National Flag (Partitioning)

| # | Problem | Difficulty | Key Idea | Status |
|:---:|:---|:---:|:---|:---:|
| 1 | [75. Sort Colors](07.%20Dutch%20National%20Flag%20%28Partitioning%29/01.%2075.%20Sort%20Colors.md) | Medium | Three regions with low, mid, high pointers | Written |

### 08. Prefix Sum + HashMap

| # | Problem | Difficulty | Key Idea | Status |
|:---:|:---|:---:|:---|:---:|
| 1 | [Longest Subarray with Sum K](08.%20Prefix%20Sum%20%2B%20HashMap/01.%20Longest%20Subarray%20with%20Sum%20K.md) | Medium | First index of each prefix sum gives the longest window | Written |
| 2 | [Largest subarray with 0 sum](08.%20Prefix%20Sum%20%2B%20HashMap/02.%20Largest%20subarray%20with%200%20sum.md) | Medium | Two equal prefix sums mean the middle sums to zero | Written |
| 3 | [560. Subarray Sum Equals K](08.%20Prefix%20Sum%20%2B%20HashMap/03.%20560.%20Subarray%20Sum%20Equals%20K.md) | Medium | Count earlier prefixes equal to current - k | Written |

### 09. Prefix XOR + HashMap

| # | Problem | Difficulty | Key Idea | Status |
|:---:|:---|:---:|:---|:---:|
| 1 | [Count Subarrays with given XOR](09.%20Prefix%20XOR%20%2B%20HashMap/01.%20Count%20Subarrays%20with%20given%20XOR.md) | Medium | Count earlier prefix XORs equal to current ^ k | Written |

### 10. Kadane (Running Optimization)

| # | Problem | Difficulty | Key Idea | Status |
|:---:|:---|:---:|:---|:---:|
| 1 | [53. Maximum Subarray](10.%20Kadane%20%28Running%20Optimization%29/01.%2053.%20Maximum%20Subarray.md) | Medium | Extend the running sum or restart here | Written |
| 2 | [121. Best Time to Buy and Sell Stock](10.%20Kadane%20%28Running%20Optimization%29/02.%20121.%20Best%20Time%20to%20Buy%20and%20Sell%20Stock.md) | Easy | Track the lowest price so far | Written |
| 3 | [152. Maximum Product Subarray](10.%20Kadane%20%28Running%20Optimization%29/03.%20152.%20Maximum%20Product%20Subarray.md) | Medium | Track running max and min; a negative swaps them | Written |

### 11. Boyer-Moore Voting

| # | Problem | Difficulty | Key Idea | Status |
|:---:|:---|:---:|:---|:---:|
| 1 | [169. Majority Element](11.%20Boyer-Moore%20Voting/01.%20169.%20Majority%20Element.md) | Easy | Different values cancel; the majority survives | Written |
| 2 | [229. Majority Element II](11.%20Boyer-Moore%20Voting/02.%20229.%20Majority%20Element%20II.md) | Medium | Two candidates, then verify their counts | Written |

### 12. Permutation

| # | Problem | Difficulty | Key Idea | Status |
|:---:|:---|:---:|:---|:---:|
| 1 | [31. Next Permutation](12.%20Permutation/01.%2031.%20Next%20Permutation.md) | Medium | Find pivot, swap with next larger, reverse suffix | Written |

### 13. Matrix Patterns

| # | Problem | Difficulty | Key Idea | Status |
|:---:|:---|:---:|:---|:---:|
| 1 | [118. Pascal's Triangle](13.%20Matrix%20Patterns/01.%20118.%20Pascal%27s%20Triangle.md) | Easy | Each row is built from the row above | Written |
| 2 | [73. Set Matrix Zeroes](13.%20Matrix%20Patterns/02.%2073.%20Set%20Matrix%20Zeroes.md) | Medium | Use row 0 and column 0 as markers | Written |
| 3 | [48. Rotate Image](13.%20Matrix%20Patterns/03.%2048.%20Rotate%20Image.md) | Medium | Transpose, then reverse each row | Written |
| 4 | [54. Spiral Matrix](13.%20Matrix%20Patterns/04.%2054.%20Spiral%20Matrix.md) | Medium | Four shrinking boundaries | Written |

### 14. Intervals

| # | Problem | Difficulty | Key Idea | Status |
|:---:|:---|:---:|:---|:---:|
| 1 | [56. Merge Intervals](14.%20Intervals/01.%2056.%20Merge%20Intervals.md) | Medium | Sort by start, extend or close the current block | Written |

### 15. Merge Sort Counting

| # | Problem | Difficulty | Key Idea | Status |
|:---:|:---|:---:|:---|:---:|
| 1 | [Count Inversions](15.%20Merge%20Sort%20Counting/01.%20Count%20Inversions.md) | Hard | During merge, one comparison counts a whole left block | Written |
| 2 | [493. Reverse Pairs](15.%20Merge%20Sort%20Counting/02.%20493.%20Reverse%20Pairs.md) | Hard | Count pairs in a separate pass before each merge | Written |

### 16. Prefix and Suffix Precomputation

| # | Problem | Difficulty | Key Idea | Status |
|:---:|:---|:---:|:---|:---:|
| 1 | [238. Product of Array Except Self](16.%20Prefix%20and%20Suffix%20Precomputation/01.%20238.%20Product%20of%20Array%20Except%20Self.md) | Medium | Product of everything left times product of everything right | Written |
| 2 | [724. Find Pivot Index](16.%20Prefix%20and%20Suffix%20Precomputation/02.%20724.%20Find%20Pivot%20Index.md) | Easy | Left sum equals total - left sum - current | Written |
| 3 | [1991. Find the Middle Index in Array](16.%20Prefix%20and%20Suffix%20Precomputation/03.%201991.%20Find%20the%20Middle%20Index%20in%20Array.md) | Easy | Same as pivot index: left sum equals right sum | Written |
| 4 | [2012. Sum of Beauty in the Array](16.%20Prefix%20and%20Suffix%20Precomputation/04.%202012.%20Sum%20of%20Beauty%20in%20the%20Array.md) | Medium | Prefix max and suffix min decide beauty 2; neighbors decide beauty 1 | Written |
| 5 | [42. Trapping Rain Water (Prefix and Suffix)](16.%20Prefix%20and%20Suffix%20Precomputation/05.%2042.%20Trapping%20Rain%20Water%20%28Prefix%20and%20Suffix%29.md) | Hard | Water at i = min(max on left, max on right) - height | Written |

### 17. Cyclic Sort (Correct Index Placement)

| # | Problem | Difficulty | Key Idea | Status |
|:---:|:---|:---:|:---|:---:|
| 1 | [268. Missing Number (Cyclic Sort)](17.%20Cyclic%20Sort%20%28Correct%20Index%20Placement%29/01.%20268.%20Missing%20Number%20%28Cyclic%20Sort%29.md) | Easy | Put each value at its own index; the empty spot is missing | Written |
| 2 | [645. Set Mismatch](17.%20Cyclic%20Sort%20%28Correct%20Index%20Placement%29/02.%20645.%20Set%20Mismatch.md) | Easy | After cyclic sort, the wrong spot shows the duplicate and the missing value | Written |
| 3 | [448. Find All Numbers Disappeared in an Array](17.%20Cyclic%20Sort%20%28Correct%20Index%20Placement%29/03.%20448.%20Find%20All%20Numbers%20Disappeared%20in%20an%20Array.md) | Easy | After cyclic sort, every index with the wrong value is missing | Written |
| 4 | [442. Find All Duplicates in an Array](17.%20Cyclic%20Sort%20%28Correct%20Index%20Placement%29/04.%20442.%20Find%20All%20Duplicates%20in%20an%20Array.md) | Medium | After cyclic sort, values in wrong spots are duplicates | Written |
| 5 | [41. First Missing Positive](17.%20Cyclic%20Sort%20%28Correct%20Index%20Placement%29/05.%2041.%20First%20Missing%20Positive.md) | Hard | Place 1..n at index 0..n-1, then find the first wrong spot | Written |

### 18. Difference Array (Range Update)

| # | Problem | Difficulty | Key Idea | Status |
|:---:|:---|:---:|:---|:---:|
| 1 | [370. Range Addition](18.%20Difference%20Array%20%28Range%20Update%29/01.%20370.%20Range%20Addition.md) | Medium | Add at start, subtract after end, then take a running sum | Written |
| 2 | [1109. Corporate Flight Bookings](18.%20Difference%20Array%20%28Range%20Update%29/02.%201109.%20Corporate%20Flight%20Bookings.md) | Medium | Each booking is one range addition on a difference array | Written |
| 3 | [1094. Car Pooling](18.%20Difference%20Array%20%28Range%20Update%29/03.%201094.%20Car%20Pooling.md) | Medium | Add riders at pickup, remove at drop-off, check the running sum | Written |
| 4 | [2381. Shifting Letters II](18.%20Difference%20Array%20%28Range%20Update%29/04.%202381.%20Shifting%20Letters%20II.md) | Medium | Difference array of shifts, then apply each running shift mod 26 | Written |
| 5 | [2772. Apply Operations to Make All Array Elements Equal to Zero](18.%20Difference%20Array%20%28Range%20Update%29/05.%202772.%20Apply%20Operations%20to%20Make%20All%20Array%20Elements%20Equal%20to%20Zero.md) | Medium | Greedy left to right with a difference array of active decrements | Written |

### 19. 2D Prefix Sum

| # | Problem | Difficulty | Key Idea | Status |
|:---:|:---|:---:|:---|:---:|
| 1 | [304. Range Sum Query 2D - Immutable](19.%202D%20Prefix%20Sum/01.%20304.%20Range%20Sum%20Query%202D%20-%20Immutable.md) | Medium | Prefix sum grid; answer with four lookups | Written |
| 2 | [1314. Matrix Block Sum](19.%202D%20Prefix%20Sum/02.%201314.%20Matrix%20Block%20Sum.md) | Medium | Clamp the block and use the 2D prefix sum | Written |
| 3 | [1074. Number of Submatrices That Sum to Target](19.%202D%20Prefix%20Sum/03.%201074.%20Number%20of%20Submatrices%20That%20Sum%20to%20Target.md) | Hard | Fix two rows, then 560 on the column sums | Written |

### 20. Frequency Array (Counting Buckets)

| # | Problem | Difficulty | Key Idea | Status |
|:---:|:---|:---:|:---|:---:|
| 1 | [1207. Unique Number of Occurrences](20.%20Frequency%20Array%20%28Counting%20Buckets%29/01.%201207.%20Unique%20Number%20of%20Occurrences.md) | Easy | Count values, then check the counts are all different | Written |
| 2 | [1748. Sum of Unique Elements](20.%20Frequency%20Array%20%28Counting%20Buckets%29/02.%201748.%20Sum%20of%20Unique%20Elements.md) | Easy | Add values whose count is exactly 1 | Written |
| 3 | [3005. Count Elements With Maximum Frequency](20.%20Frequency%20Array%20%28Counting%20Buckets%29/03.%203005.%20Count%20Elements%20With%20Maximum%20Frequency.md) | Easy | Count frequencies, then add all counts equal to the max | Written |
| 4 | [274. H-Index](20.%20Frequency%20Array%20%28Counting%20Buckets%29/04.%20274.%20H-Index.md) | Medium | Bucket papers by citations, then scan from high to low | Written |
| 5 | [1338. Reduce Array Size to The Half](20.%20Frequency%20Array%20%28Counting%20Buckets%29/05.%201338.%20Reduce%20Array%20Size%20to%20The%20Half.md) | Medium | Remove the most frequent values first until half is gone | Written |

## Where This Leads

| Skill built here | Used later in |
|:---|:---|
| Single-pass tracking | Kadane, sliding window, stock problems |
| Loop invariants | Proving any loop correct |
| Slow/fast pointers | Linked list cycles, partitioning, quickselect |
| Prefix sums | Subarray counts, 2D range queries, difference arrays |
| Sorting as setup | 3Sum, merge intervals, greedy scheduling |
| Fill-from-the-back | In-place merges, DP space optimization |
| XOR identities | Bit manipulation, finding duplicates |
