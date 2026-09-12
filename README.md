# DSA Notes

Structured notes for Data Structures & Algorithms, following the [Striver / TUF](https://takeuforward.org/) sheet.

Every problem note follows the same shape, so patterns stay comparable across topics:

> Problem statement → Explanation → Core intuition → Brute force → Better approach → Optimal approach → Dry run → Complexity → Interview explanation

Each approach carries commented code and its own time/space analysis.

---

## Topics

| # | Topic | Problems | Status |
|---|---|---|---|
| 01 | Array | — | Planned |
| 02 | [Two Pointers](02-two-pointers/) | 5 | Done |
| 03 | Stacks and Queues | — | Planned |
| 04 | Sliding Window | — | Planned |
| 05 | Linked List | — | Planned |
| 06 | Binary Search | — | Planned |
| 07 | Recursion | — | Planned |
| 08 | Trees | — | Planned |
| 09 | Heaps | — | Planned |
| 10 | Greedy | — | Planned |
| 11 | Graphs | — | Planned |
| 12 | Dynamic Programming | — | Planned |
| 13 | Maths and Geometry | — | Planned |
| 14 | Bit Manipulation | — | Planned |
| 15 | Intervals | — | Planned |
| 16 | Databases | — | Planned |

---

## 02. Two Pointers

| # | Problem | Difficulty | Time | Space |
|---|---|---|---|---|
| 1 | [125. Valid Palindrome](02-two-pointers/01-basics/01-125-valid-palindrome.md) | Easy | `O(n)` | `O(1)` |
| 2 | [15. 3Sum](02-two-pointers/02-medium/01-15-3sum.md) | Medium | `O(n^2)` | `O(1)` |
| 3 | [167. Two Sum II - Input Array Is Sorted](02-two-pointers/02-medium/02-167-two-sum-ii-input-array-is-sorted.md) | Medium | `O(n)` | `O(1)` |
| 4 | [11. Container With Most Water](02-two-pointers/02-medium/03-11-container-with-most-water.md) | Medium | `O(n)` | `O(1)` |
| 5 | [42. Trapping Rain Water](02-two-pointers/03-hard/01-42-trapping-rain-water.md) | Hard | `O(n)` | `O(1)` |

---

## Repository Layout

```text
dsa-notes/
└── 02-two-pointers/
    ├── 01-basics/
    │   └── 01-125-valid-palindrome.md
    ├── 02-medium/
    │   ├── 01-15-3sum.md
    │   ├── 02-167-two-sum-ii-input-array-is-sorted.md
    │   └── 03-11-container-with-most-water.md
    └── 03-hard/
        └── 01-42-trapping-rain-water.md
```

Folders and files are numbered so they sort in study order: topic → difficulty tier → problem.

---

## Language

Solutions are written in **Python 3**, with line-by-line comments intended for revision rather than brevity.
