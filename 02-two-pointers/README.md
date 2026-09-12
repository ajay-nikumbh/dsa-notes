# 02. Two Pointers

The two pointer technique uses two indices moving through a data structure — usually inward from both ends, or forward at different speeds — to replace a nested loop with a single pass.

It applies when the data is **sorted** or has a **monotonic property**, so that moving one pointer reliably moves the answer in a known direction.

---

## Problems

### 01. Basics

| # | Problem | Difficulty | Time | Space |
|---|---|---|---|---|
| 1 | [125. Valid Palindrome](01-basics/01-125-valid-palindrome.md) | Easy | `O(n)` | `O(1)` |

### 02. Medium

| # | Problem | Difficulty | Time | Space |
|---|---|---|---|---|
| 1 | [15. 3Sum](02-medium/01-15-3sum.md) | Medium | `O(n^2)` | `O(1)` |
| 2 | [167. Two Sum II - Input Array Is Sorted](02-medium/02-167-two-sum-ii-input-array-is-sorted.md) | Medium | `O(n)` | `O(1)` |
| 3 | [11. Container With Most Water](02-medium/03-11-container-with-most-water.md) | Medium | `O(n)` | `O(1)` |

### 03. Hard

| # | Problem | Difficulty | Time | Space |
|---|---|---|---|---|
| 1 | [42. Trapping Rain Water](03-hard/01-42-trapping-rain-water.md) | Hard | `O(n)` | `O(1)` |

---

## Core Patterns

### 1. Converging pointers (opposite ends)

Start at both ends and move inward.

```text
left  = 0
right = n - 1

while left < right:
    ...decide which pointer to move
```

Used in: Valid Palindrome, Two Sum II, Container With Most Water, Trapping Rain Water.

### 2. Fixed element + two pointers

Sort, fix one element, then two-pointer the remainder.

```text
for i in range(n):
    left  = i + 1
    right = n - 1
```

Used in: 3Sum.

---

## How to Decide Which Pointer to Move

This is the heart of the pattern. The move must never skip a better answer.

| Problem | Rule | Why |
|---|---|---|
| Two Sum II | Sum too small → move `left`; too large → move `right` | Array is sorted, so each move changes the sum in exactly one direction |
| Container With Most Water | Always move the **shorter** line | Width always shrinks, so only a taller minimum height can improve the area |
| Trapping Rain Water | Process the side with the **smaller** height | That side's `max` is guaranteed to be the limiting boundary |
| 3Sum | Same as Two Sum II, per fixed element | Sorting makes the inner scan monotonic |

---

## Why Sorting Matters

Sorting is what makes pointer movement *decidable*. Without it, a smaller sum gives no information about which side to move.

Sorting also makes duplicate skipping trivial — equal values become adjacent:

```python
if i > 0 and nums[i] == nums[i - 1]:
    continue
```

---

## Complexity Summary

| Problem | Brute Force | Optimal | Space Saved |
|---|---|---|---|
| Valid Palindrome | `O(n)` time, `O(n)` space | `O(n)` time, `O(1)` space | Avoids building a cleaned string |
| Two Sum II | `O(n^2)` | `O(n)` time, `O(1)` space | Avoids a hash map |
| 3Sum | `O(n^3)` | `O(n^2)` | Avoids a set for duplicates |
| Container With Most Water | `O(n^2)` | `O(n)` | — |
| Trapping Rain Water | `O(n^2)` | `O(n)` time, `O(1)` space | Avoids prefix/suffix arrays |
