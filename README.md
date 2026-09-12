# DSA Notes

Structured notes for Data Structures & Algorithms

Every problem note follows the same shape, so patterns stay comparable across topics:

> Problem statement → Explanation → Core intuition → Brute force → Better approach → Optimal approach → Dry run → Complexity → Interview explanation

Each approach carries commented code and its own time/space analysis.

---

## Topics

| # | Topic | Core Focus | Problems | Status |
|:---:|:---|:---|:---:|:---:|
| 01 | Array | Prefix sums, Kadane, in-place rearrangement | – | Planned |
| 02 | [Two Pointers](02.%20Two%20pointers/) | Converging pointers, fast/slow, fixed element + scan | 5 | **Done** |
| 03 | Stacks and Queues | Monotonic stack, next greater element | – | Planned |
| 04 | Sliding Window | Fixed and variable windows, longest/shortest substring | – | Planned |
| 05 | Linked List | Reversal, cycle detection, merge and reorder | – | Planned |
| 06 | Binary Search | On answer space, rotated arrays, first/last position | – | Planned |
| 07 | Recursion | Subsets, permutations, backtracking | – | Planned |
| 08 | Trees | Traversals, BST properties, lowest common ancestor | – | Planned |
| 09 | Heaps | Top-K, merge K sorted, running median | – | Planned |
| 10 | Greedy | Interval scheduling, exchange argument | – | Planned |
| 11 | Graphs | BFS/DFS, topological sort, Dijkstra, union-find | – | Planned |
| 12 | Dynamic Programming | 1D/2D states, knapsack, LIS, DP on subsequences | – | Planned |
| 13 | Maths and Geometry | Number theory, matrix rotation, GCD | – | Planned |
| 14 | Bit Manipulation | XOR tricks, masks, bit counting | – | Planned |
| 15 | Intervals | Merge, insert, overlap counting | – | Planned |
| 16 | Databases | Joins, window functions, aggregation | – | Planned |

---

## 02. Two Pointers

| # | Problem | Difficulty | Key Idea | Time | Space |
|:---:|:---|:---:|:---|:---:|:---:|
| 1 | [125. Valid Palindrome](02.%20Two%20pointers/01.%20Basics/01.%20125.%20Valid%20Palindrome.md) | Easy | Skip non-alphanumerics from both ends, compare inward | `O(n)` | `O(1)` |
| 2 | [15. 3Sum](02.%20Two%20pointers/02.%20Medium/01.%2015.%203Sum.md) | Medium | Sort, fix one element, two-pointer the rest, skip duplicates | `O(n^2)` | `O(1)` |
| 3 | [167. Two Sum II - Input Array Is Sorted](02.%20Two%20pointers/02.%20Medium/02.%20167.%20Two%20Sum%20II%20-%20Input%20Array%20Is%20Sorted.md) | Medium | Sorted order makes each pointer move decidable | `O(n)` | `O(1)` |
| 4 | [11. Container With Most Water](02.%20Two%20pointers/02.%20Medium/03.%2011.%20Container%20With%20Most%20Water.md) | Medium | Always move the shorter line; width only shrinks | `O(n)` | `O(1)` |
| 5 | [42. Trapping Rain Water](02.%20Two%20pointers/03.%20Hard/01.%2042.%20Trapping%20Rain%20Water.md) | Hard | Process the smaller side; its max bounds the water | `O(n)` | `O(1)` |

---

## Repository Layout

```text
dsa-notes/
└── 02. Two pointers/
    ├── 01. Basics/
    │   └── 01. 125. Valid Palindrome.md
    ├── 02. Medium/
    │   ├── 01. 15. 3Sum.md
    │   ├── 02. 167. Two Sum II - Input Array Is Sorted.md
    │   └── 03. 11. Container With Most Water.md
    └── 03. Hard/
        └── 01. 42. Trapping Rain Water.md
```

Folders and files are numbered so they sort in study order: topic → difficulty tier → problem.

---

## Language

Solutions are written in **Python 3**, with line-by-line comments intended for revision rather than brevity.
