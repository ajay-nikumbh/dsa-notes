# 01. Array

Arrays are the foundation of most DSA patterns. Nearly every later topic — two pointers, sliding window, prefix sums, binary search — is first learned on a flat array.

These notes work through the TUF array sheet, tier by tier.

## Problems

### 01. Easy

| # | Problem | Difficulty | Key Idea | Time | Space |
|:---:|:---|:---:|:---|:---:|:---:|
| 1 | [Largest in Array](01.%20Easy/01.%20Largest%20in%20Array.md) | Basic | Track the max seen so far in one scan | `O(n)` | `O(1)` |
| 2 | [Second Largest](01.%20Easy/02.%20Second%20Largest.md) | Basic | Keep two variables, update in order | `O(n)` | `O(1)` |
| 3 | [Array Search](01.%20Easy/03.%20Array%20Search.md) | Basic | Linear scan, return index on match | `O(n)` | `O(1)` |
| 4 | [1752. Check if Array Is Sorted and Rotated](01.%20Easy/04.%201752.%20Check%20if%20Array%20Is%20Sorted%20and%20Rotated.md) | Easy | Count the "drops"; at most one is allowed | `O(n)` | `O(1)` |
| 5 | [136. Single Number](01.%20Easy/05.%20136.%20Single%20Number.md) | Easy | XOR cancels every pair, leaving the loner | `O(n)` | `O(1)` |
| 6 | [268. Missing Number](01.%20Easy/06.%20268.%20Missing%20Number.md) | Easy | Expected sum minus actual sum, or XOR | `O(n)` | `O(1)` |
| 7 | [485. Max Consecutive Ones](01.%20Easy/07.%20485.%20Max%20Consecutive%20Ones.md) | Easy | Running streak counter, reset on zero | `O(n)` | `O(1)` |
| 8 | [189. Rotate Array](01.%20Easy/08.%20189.%20Rotate%20Array.md) | Medium | Reverse whole, then reverse both parts | `O(n)` | `O(1)` |
| 9 | [283. Move Zeroes](01.%20Easy/09.%20283.%20Move%20Zeroes.md) | Easy | Slow pointer marks the next non-zero slot | `O(n)` | `O(1)` |
| 10 | [88. Merge Sorted Array](01.%20Easy/10.%2088.%20Merge%20Sorted%20Array.md) | Easy | Fill from the back to avoid overwriting | `O(m+n)` | `O(1)` |
| 11 | [Longest Subarray with Sum K](01.%20Easy/11.%20Longest%20Subarray%20with%20Sum%20K.md) | Medium | Prefix sum + first-seen index in a hashmap | `O(n)` | `O(n)` |
| 12 | [Largest subarray with 0 sum](01.%20Easy/12.%20Largest%20subarray%20with%200%20sum.md) | Medium | Same prefix sum means zero in between | `O(n)` | `O(n)` |
| 13 | [Find Second Smallest and Second Largest Element in an Array](01.%20Easy/13.%20Find%20Second%20Smallest%20and%20Second%20Largest%20Element%20in%20an%20Array.md) | Basic | Four trackers in a single pass | `O(n)` | `O(1)` |
| 14 | [First and Second Smallests](01.%20Easy/14.%20First%20and%20Second%20Smallests.md) | Basic | Two trackers, update smallest before second | `O(n)` | `O(1)` |

### 02. Medium

Planned.

### 03. Hard

Planned.

## Core Patterns in This Topic

### 1. Single-pass tracking

Keep one or more running variables instead of sorting or nesting loops.

```text
largest = nums[0]
for each element:
    if element > largest: largest = element
```

Used in: Largest in Array, Second Largest, Max Consecutive Ones, First and Second Smallests.

### 2. Two pointers / slow-fast writing

One pointer reads, another marks where the next valid value should be written.

```text
slow = 0
for fast in range(n):
    if nums[fast] is valid:
        nums[slow] = nums[fast]
        slow += 1
```

Used in: Move Zeroes, Merge Sorted Array.

### 3. Prefix sum + hashmap

Store the first index at which each running sum appears. If the same sum returns, the span between them sums to zero.

```text
if (prefix_sum - k) seen before:
    candidate length = i - first_index[prefix_sum - k]
```

Used in: Longest Subarray with Sum K, Largest subarray with 0 sum.

### 4. Mathematical / bitwise tricks

Replace a data structure with an identity.

| Trick | Identity | Used in |
|:---|:---|:---|
| XOR self-cancel | `a ^ a = 0`, `a ^ 0 = a` | Single Number, Missing Number |
| Sum formula | `n * (n + 1) / 2` | Missing Number |
| Triple reversal | `reverse(all)` then reverse each part | Rotate Array |

## Why Start Here

| Skill learned | Carried into |
|:---|:---|
| Single-pass tracking | Kadane's algorithm, sliding window |
| Slow/fast pointers | Linked list cycle detection, partitioning |
| Prefix sums | Subarray sum problems, 2D range queries |
| Writing from the back | In-place merges, DP space optimization |
