# 02. Two Pointers

The two pointer technique uses two indices moving through a data structure — usually inward from both ends, or forward at different speeds — to replace a nested loop with a single pass.

It applies when the data is **sorted** or has a **monotonic property**, so that moving one pointer reliably moves the answer in a known direction.

---

## Problems

| # | Tier | Problem | Difficulty | Key Idea | Time | Space |
|:---:|:---:|:---|:---:|:---|:---:|:---:|
| 1 | Basics | [125. Valid Palindrome](01.%20Basics/01.%20125.%20Valid%20Palindrome.md) | Easy | Skip non-alphanumerics from both ends, compare inward | `O(n)` | `O(1)` |
| 2 | Medium | [15. 3Sum](02.%20Medium/01.%2015.%203Sum.md) | Medium | Sort, fix one element, two-pointer the rest, skip duplicates | `O(n^2)` | `O(1)` |
| 3 | Medium | [167. Two Sum II - Input Array Is Sorted](02.%20Medium/02.%20167.%20Two%20Sum%20II%20-%20Input%20Array%20Is%20Sorted.md) | Medium | Sorted order makes each pointer move decidable | `O(n)` | `O(1)` |
| 4 | Medium | [11. Container With Most Water](02.%20Medium/03.%2011.%20Container%20With%20Most%20Water.md) | Medium | Always move the shorter line; width only shrinks | `O(n)` | `O(1)` |
| 5 | Hard | [42. Trapping Rain Water](03.%20Hard/01.%2042.%20Trapping%20Rain%20Water.md) | Hard | Process the smaller side; its max bounds the water | `O(n)` | `O(1)` |

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

| Problem | Rule | Why It Is Safe |
|:---|:---|:---|
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

| Problem | Brute Force | Optimal | What the Optimization Buys |
|:---|:---:|:---:|:---|
| Valid Palindrome | `O(n)` time, `O(n)` space | `O(n)` time, `O(1)` space | Avoids building a cleaned string |
| Two Sum II | `O(n^2)` | `O(n)` time, `O(1)` space | Avoids a hash map |
| 3Sum | `O(n^3)` | `O(n^2)` | Avoids a set for duplicates |
| Container With Most Water | `O(n^2)` | `O(n)` | — |
| Trapping Rain Water | `O(n^2)` | `O(n)` time, `O(1)` space | Avoids prefix/suffix arrays |
