# DSA Notes

Structured notes for Data Structures & Algorithms

Every problem note follows the same shape, so patterns stay comparable across topics:

> Problem statement → Explanation → Core intuition → Brute force → Better approach → Optimal approach → Dry run → Complexity → Interview explanation

Each approach carries commented code and its own time/space analysis.

## Topics

| # | Topic | Core Focus | Problems | Status |
|:---:|:---|:---|:---:|:---:|
| 01 | [Array](01.%20Array/) | Prefix sums, Kadane, in-place rearrangement | 27 | **Easy + Medium** |
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

## 01. Array

### Easy

| # | Problem | Difficulty | Key Idea | Time | Space |
|:---:|:---|:---:|:---|:---:|:---:|
| 1 | [Largest in Array](01.%20Array/01.%20Easy/01.%20Largest%20in%20Array.md) | Basic | Track the max seen so far in one scan | `O(n)` | `O(1)` |
| 2 | [Second Largest](01.%20Array/01.%20Easy/02.%20Second%20Largest.md) | Basic | Keep two variables, update in order | `O(n)` | `O(1)` |
| 3 | [Array Search](01.%20Array/01.%20Easy/03.%20Array%20Search.md) | Basic | Linear scan, return index on match | `O(n)` | `O(1)` |
| 4 | [1752. Check if Array Is Sorted and Rotated](01.%20Array/01.%20Easy/04.%201752.%20Check%20if%20Array%20Is%20Sorted%20and%20Rotated.md) | Easy | Count the "drops"; at most one is allowed | `O(n)` | `O(1)` |
| 5 | [136. Single Number](01.%20Array/01.%20Easy/05.%20136.%20Single%20Number.md) | Easy | XOR cancels every pair, leaving the loner | `O(n)` | `O(1)` |
| 6 | [268. Missing Number](01.%20Array/01.%20Easy/06.%20268.%20Missing%20Number.md) | Easy | Expected sum minus actual sum, or XOR | `O(n)` | `O(1)` |
| 7 | [485. Max Consecutive Ones](01.%20Array/01.%20Easy/07.%20485.%20Max%20Consecutive%20Ones.md) | Easy | Running streak counter, reset on zero | `O(n)` | `O(1)` |
| 8 | [189. Rotate Array](01.%20Array/01.%20Easy/08.%20189.%20Rotate%20Array.md) | Medium | Reverse whole, then reverse both parts | `O(n)` | `O(1)` |
| 9 | [283. Move Zeroes](01.%20Array/01.%20Easy/09.%20283.%20Move%20Zeroes.md) | Easy | Slow pointer marks the next non-zero slot | `O(n)` | `O(1)` |
| 10 | [88. Merge Sorted Array](01.%20Array/01.%20Easy/10.%2088.%20Merge%20Sorted%20Array.md) | Easy | Fill from the back to avoid overwriting | `O(m+n)` | `O(1)` |
| 11 | [Longest Subarray with Sum K](01.%20Array/01.%20Easy/11.%20Longest%20Subarray%20with%20Sum%20K.md) | Medium | Prefix sum + first-seen index in a hashmap | `O(n)` | `O(n)` |
| 12 | [Largest subarray with 0 sum](01.%20Array/01.%20Easy/12.%20Largest%20subarray%20with%200%20sum.md) | Medium | Same prefix sum means zero in between | `O(n)` | `O(n)` |
| 13 | [Find Second Smallest and Second Largest Element in an Array](01.%20Array/01.%20Easy/13.%20Find%20Second%20Smallest%20and%20Second%20Largest%20Element%20in%20an%20Array.md) | Basic | Four trackers in a single pass | `O(n)` | `O(1)` |
| 14 | [First and Second Smallests](01.%20Array/01.%20Easy/14.%20First%20and%20Second%20Smallests.md) | Basic | Two trackers, update smallest before second | `O(n)` | `O(1)` |

### Medium

| # | Problem | Difficulty | Key Idea | Time | Space |
|:---:|:---|:---:|:---|:---:|:---:|
| 1 | [1. Two Sum](01.%20Array/02.%20Medium/01.%201.%20Two%20Sum.md) | Medium | Store complements; check before insert | `O(n)` | `O(n)` |
| 2 | [75. Sort Colors](01.%20Array/02.%20Medium/02.%2075.%20Sort%20Colors.md) | Medium | Three regions, one pass | `O(n)` | `O(1)` |
| 3 | [169. Majority Element](01.%20Array/02.%20Medium/03.%20169.%20Majority%20Element.md) | Easy | Pairwise cancellation leaves the majority | `O(n)` | `O(1)` |
| 4 | [53. Maximum Subarray](01.%20Array/02.%20Medium/04.%2053.%20Maximum%20Subarray.md) | Medium | Extend or restart at each element | `O(n)` | `O(1)` |
| 5 | [121. Best Time to Buy and Sell Stock](01.%20Array/02.%20Medium/05.%20121.%20Best%20Time%20to%20Buy%20and%20Sell%20Stock.md) | Easy | Track min price, best profit against it | `O(n)` | `O(1)` |
| 6 | [2149. Rearrange Array Elements by Sign](01.%20Array/02.%20Medium/06.%202149.%20Rearrange%20Array%20Elements%20by%20Sign.md) | Medium | Sign fixes the slot; cursors step by 2 | `O(n)` | `O(n)` |
| 7 | [31. Next Permutation](01.%20Array/02.%20Medium/07.%2031.%20Next%20Permutation.md) | Medium | Find pivot, swap successor, reverse suffix | `O(n)` | `O(1)` |
| 8 | [Array Leaders](01.%20Array/02.%20Medium/08.%20Array%20Leaders.md) | Easy | Running max from the right | `O(n)` | `O(1)` |
| 9 | [128. Longest Consecutive Sequence](01.%20Array/02.%20Medium/09.%20128.%20Longest%20Consecutive%20Sequence.md) | Medium | Only walk runs from their head | `O(n)` | `O(n)` |
| 10 | [73. Set Matrix Zeroes](01.%20Array/02.%20Medium/10.%2073.%20Set%20Matrix%20Zeroes.md) | Medium | Row 0 and col 0 become the markers | `O(m*n)` | `O(1)` |
| 11 | [48. Rotate Image](01.%20Array/02.%20Medium/11.%2048.%20Rotate%20Image.md) | Medium | Two reflections compose to a rotation | `O(n^2)` | `O(1)` |
| 12 | [54. Spiral Matrix](01.%20Array/02.%20Medium/12.%2054.%20Spiral%20Matrix.md) | Medium | Shrink the rectangle layer by layer | `O(m*n)` | `O(1)` |
| 13 | [560. Subarray Sum Equals K](01.%20Array/02.%20Medium/13.%20560.%20Subarray%20Sum%20Equals%20K.md) | Medium | Count earlier sums equal to sum - k | `O(n)` | `O(n)` |

## 02. Two Pointers

| # | Problem | Difficulty | Key Idea | Time | Space |
|:---:|:---|:---:|:---|:---:|:---:|
| 1 | [125. Valid Palindrome](02.%20Two%20pointers/01.%20Basics/01.%20125.%20Valid%20Palindrome.md) | Easy | Skip non-alphanumerics from both ends, compare inward | `O(n)` | `O(1)` |
| 2 | [15. 3Sum](02.%20Two%20pointers/02.%20Medium/01.%2015.%203Sum.md) | Medium | Sort, fix one element, two-pointer the rest, skip duplicates | `O(n^2)` | `O(1)` |
| 3 | [167. Two Sum II - Input Array Is Sorted](02.%20Two%20pointers/02.%20Medium/02.%20167.%20Two%20Sum%20II%20-%20Input%20Array%20Is%20Sorted.md) | Medium | Sorted order makes each pointer move decidable | `O(n)` | `O(1)` |
| 4 | [11. Container With Most Water](02.%20Two%20pointers/02.%20Medium/03.%2011.%20Container%20With%20Most%20Water.md) | Medium | Always move the shorter line; width only shrinks | `O(n)` | `O(1)` |
| 5 | [42. Trapping Rain Water](02.%20Two%20pointers/03.%20Hard/01.%2042.%20Trapping%20Rain%20Water.md) | Hard | Process the smaller side; its max bounds the water | `O(n)` | `O(1)` |

## Repository Layout

```text
dsa-notes/
├── 01. Array/
│   └── 01. Easy/
│       ├── 01. Largest in Array.md
│       ├── ...
│       └── 14. First and Second Smallests.md
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

## Language

Solutions are written in **Python 3**, with line-by-line comments intended for revision rather than brevity.
