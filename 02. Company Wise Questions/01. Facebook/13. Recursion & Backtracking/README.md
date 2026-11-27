# 13. Recursion & Backtracking

[Back to Facebook](../README.md) · [Back to DSA Notes](../../../README.md)

45 Meta (Facebook) problems: 1 Easy, 31 Medium, 13 Hard, in 8 sub-patterns.

## Sub-patterns

| # | Sub-pattern | Questions | Easy | Medium | Hard | Last 3 Months | Solved | Most Asked |
|:---:|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---|
| 01 | [Basic Recursion](#01-basic-recursion) | 6 | 1 | 5 | 0 | 0 | 0 | 339. Nested List Weight Sum, 1545. Find Kth Bit in Nth Binary String, 779. K-th Symbol in Grammar |
| 02 | [Subsets](#02-subsets) | 5 | 0 | 5 | 0 | 1 | 2 | 78. Subsets, 90. Subsets II, 784. Letter Case Permutation |
| 03 | [Permutations](#03-permutations) | 4 | 0 | 4 | 0 | 0 | 2 | 46. Permutations, 1718. Construct the Lexicographically Largest Valid Sequence, 47. Permutations II |
| 04 | [Combinations & Combination Sum](#04-combinations--combination-sum) | 4 | 0 | 4 | 0 | 1 | 4 | 17. Letter Combinations of a Phone Number, 39. Combination Sum, 77. Combinations |
| 05 | [Partitioning](#05-partitioning) | 6 | 0 | 4 | 2 | 0 | 2 | 131. Palindrome Partitioning, 140. Word Break II, 93. Restore IP Addresses |
| 06 | [Board & Grid Search (N-Queens, Sudoku, Word Search)](#06-board--grid-search-n-queens-sudoku-word-search) | 6 | 0 | 1 | 5 | 0 | 3 | 489. Robot Room Cleaner, 79. Word Search, 51. N-Queens |
| 07 | [Generate Valid Strings](#07-generate-valid-strings) | 9 | 0 | 4 | 5 | 2 | 1 | 282. Expression Add Operators, 301. Remove Invalid Parentheses, 22. Generate Parentheses |
| 08 | [Divide and Conquer](#08-divide-and-conquer) | 5 | 0 | 4 | 1 | 0 | 0 | 95. Unique Binary Search Trees II, 427. Construct Quad Tree, 2035. Partition Array Into Two Arrays to Minimize Sum Difference |

**Columns**

- **Last Asked**: most recent LeetCode window that lists the problem for Meta (30 days, 3 months, 6 months or 6+ months).
- **Frequency**: LeetCode frequency score (0-100) in the Meta "All" list.
- **Status**: your LeetCode status on the day this file was generated. 🔒 after a title means LeetCode Premium.
- **Logic / Key Idea, Time, Space**: fill these in as you solve. A rebuild keeps what you typed.
- **Notes**: link to the problem's notes file.

Inside each sub-pattern, rows are sorted by most recent window, then by frequency (highest first).

## 01. Basic Recursion

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [339. Nested List Weight Sum](https://leetcode.com/problems/nested-list-weight-sum/) 🔒 | Medium | 6+ months | 85.1 | Todo |  |  |  | [notes](01.%20Basic%20Recursion/0339.%20Nested%20List%20Weight%20Sum/0339.%20Nested%20List%20Weight%20Sum.md) |
| 2 | [1545. Find Kth Bit in Nth Binary String](https://leetcode.com/problems/find-kth-bit-in-nth-binary-string/) | Medium | 6+ months | 18.8 | Todo |  |  |  | [notes](01.%20Basic%20Recursion/1545.%20Find%20Kth%20Bit%20in%20Nth%20Binary%20String/1545.%20Find%20Kth%20Bit%20in%20Nth%20Binary%20String.md) |
| 3 | [779. K-th Symbol in Grammar](https://leetcode.com/problems/k-th-symbol-in-grammar/) | Medium | 6+ months | 16.7 | Todo |  |  |  | [notes](01.%20Basic%20Recursion/0779.%20K-th%20Symbol%20in%20Grammar/0779.%20K-th%20Symbol%20in%20Grammar.md) |
| 4 | [3304. Find the K-th Character in String Game I](https://leetcode.com/problems/find-the-k-th-character-in-string-game-i/) | Easy | 6+ months | 9.9 | Todo |  |  |  | [notes](01.%20Basic%20Recursion/3304.%20Find%20the%20K-th%20Character%20in%20String%20Game%20I/3304.%20Find%20the%20K-th%20Character%20in%20String%20Game%20I.md) |
| 5 | [2625. Flatten Deeply Nested Array](https://leetcode.com/problems/flatten-deeply-nested-array/) | Medium | 6+ months | 8.2 | Todo |  |  |  | [notes](01.%20Basic%20Recursion/2625.%20Flatten%20Deeply%20Nested%20Array/2625.%20Flatten%20Deeply%20Nested%20Array.md) |
| 6 | [364. Nested List Weight Sum II](https://leetcode.com/problems/nested-list-weight-sum-ii/) 🔒 | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Basic%20Recursion/0364.%20Nested%20List%20Weight%20Sum%20II/0364.%20Nested%20List%20Weight%20Sum%20II.md) |

## 02. Subsets

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [78. Subsets](https://leetcode.com/problems/subsets/) | Medium | 3 months | 63.4 | ✅ Solved |  |  |  | [notes](02.%20Subsets/0078.%20Subsets/0078.%20Subsets.md) |
| 2 | [90. Subsets II](https://leetcode.com/problems/subsets-ii/) | Medium | 6 months | 46.6 | ✅ Solved |  |  |  | [notes](02.%20Subsets/0090.%20Subsets%20II/0090.%20Subsets%20II.md) |
| 3 | [784. Letter Case Permutation](https://leetcode.com/problems/letter-case-permutation/) | Medium | 6+ months | 43.4 | Todo |  |  |  | [notes](02.%20Subsets/0784.%20Letter%20Case%20Permutation/0784.%20Letter%20Case%20Permutation.md) |
| 4 | [1239. Maximum Length of a Concatenated String with Unique Characters](https://leetcode.com/problems/maximum-length-of-a-concatenated-string-with-unique-characters/) | Medium | 6+ months | 26.8 | Todo |  |  |  | [notes](02.%20Subsets/1239.%20Maximum%20Length%20of%20a%20Concatenated%20String%20with%20Unique%20Characters/1239.%20Maximum%20Length%20of%20a%20Concatenated%20String%20with%20Unique%20Characters.md) |
| 5 | [3566. Partition Array into Two Equal Product Subsets](https://leetcode.com/problems/partition-array-into-two-equal-product-subsets/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Subsets/3566.%20Partition%20Array%20into%20Two%20Equal%20Product%20Subsets/3566.%20Partition%20Array%20into%20Two%20Equal%20Product%20Subsets.md) |

## 03. Permutations

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [46. Permutations](https://leetcode.com/problems/permutations/) | Medium | 6 months | 40.8 | ✅ Solved |  |  |  | [notes](03.%20Permutations/0046.%20Permutations/0046.%20Permutations.md) |
| 2 | [47. Permutations II](https://leetcode.com/problems/permutations-ii/) | Medium | 6+ months | 13.1 | ✅ Solved |  |  |  | [notes](03.%20Permutations/0047.%20Permutations%20II/0047.%20Permutations%20II.md) |
| 3 | [1079. Letter Tile Possibilities](https://leetcode.com/problems/letter-tile-possibilities/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](03.%20Permutations/1079.%20Letter%20Tile%20Possibilities/1079.%20Letter%20Tile%20Possibilities.md) |
| 4 | [1718. Construct the Lexicographically Largest Valid Sequence](https://leetcode.com/problems/construct-the-lexicographically-largest-valid-sequence/) | Medium | 6+ months | 36.4 | Todo |  |  |  | [notes](03.%20Permutations/1718.%20Construct%20the%20Lexicographically%20Largest%20Valid%20Sequence/1718.%20Construct%20the%20Lexicographically%20Largest%20Valid%20Sequence.md) |

## 04. Combinations & Combination Sum

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [77. Combinations](https://leetcode.com/problems/combinations/) | Medium | 3 months | 32.6 | ✅ Solved |  |  |  | [notes](04.%20Combinations%20%26%20Combination%20Sum/0077.%20Combinations/0077.%20Combinations.md) |
| 2 | [17. Letter Combinations of a Phone Number](https://leetcode.com/problems/letter-combinations-of-a-phone-number/) | Medium | 6 months | 57.2 | ✅ Solved |  |  |  | [notes](04.%20Combinations%20%26%20Combination%20Sum/0017.%20Letter%20Combinations%20of%20a%20Phone%20Number/0017.%20Letter%20Combinations%20of%20a%20Phone%20Number.md) |
| 3 | [39. Combination Sum](https://leetcode.com/problems/combination-sum/) | Medium | 6 months | 47.2 | ✅ Solved |  |  |  | [notes](04.%20Combinations%20%26%20Combination%20Sum/0039.%20Combination%20Sum/0039.%20Combination%20Sum.md) |
| 4 | [40. Combination Sum II](https://leetcode.com/problems/combination-sum-ii/) | Medium | 6+ months | 32.3 | ✅ Solved |  |  |  | [notes](04.%20Combinations%20%26%20Combination%20Sum/0040.%20Combination%20Sum%20II/0040.%20Combination%20Sum%20II.md) |

## 05. Partitioning

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [131. Palindrome Partitioning](https://leetcode.com/problems/palindrome-partitioning/) | Medium | 6 months | 37.6 | ✅ Solved |  |  |  | [notes](05.%20Partitioning/0131.%20Palindrome%20Partitioning/0131.%20Palindrome%20Partitioning.md) |
| 2 | [140. Word Break II](https://leetcode.com/problems/word-break-ii/) | Hard | 6+ months | 28.5 | ✅ Solved |  |  |  | [notes](05.%20Partitioning/0140.%20Word%20Break%20II/0140.%20Word%20Break%20II.md) |
| 3 | [93. Restore IP Addresses](https://leetcode.com/problems/restore-ip-addresses/) | Medium | 6+ months | 19.4 | Todo |  |  |  | [notes](05.%20Partitioning/0093.%20Restore%20IP%20Addresses/0093.%20Restore%20IP%20Addresses.md) |
| 4 | [473. Matchsticks to Square](https://leetcode.com/problems/matchsticks-to-square/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Partitioning/0473.%20Matchsticks%20to%20Square/0473.%20Matchsticks%20to%20Square.md) |
| 5 | [698. Partition to K Equal Sum Subsets](https://leetcode.com/problems/partition-to-k-equal-sum-subsets/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Partitioning/0698.%20Partition%20to%20K%20Equal%20Sum%20Subsets/0698.%20Partition%20to%20K%20Equal%20Sum%20Subsets.md) |
| 6 | [1723. Find Minimum Time to Finish All Jobs](https://leetcode.com/problems/find-minimum-time-to-finish-all-jobs/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Partitioning/1723.%20Find%20Minimum%20Time%20to%20Finish%20All%20Jobs/1723.%20Find%20Minimum%20Time%20to%20Finish%20All%20Jobs.md) |

## 06. Board & Grid Search (N-Queens, Sudoku, Word Search)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [51. N-Queens](https://leetcode.com/problems/n-queens/) | Hard | 6 months | 46.5 | ✅ Solved |  |  |  | [notes](06.%20Board%20%26%20Grid%20Search%20%28N-Queens%2C%20Sudoku%2C%20Word%20Search%29/0051.%20N-Queens/0051.%20N-Queens.md) |
| 2 | [489. Robot Room Cleaner](https://leetcode.com/problems/robot-room-cleaner/) 🔒 | Hard | 6+ months | 66.8 | Todo |  |  |  | [notes](06.%20Board%20%26%20Grid%20Search%20%28N-Queens%2C%20Sudoku%2C%20Word%20Search%29/0489.%20Robot%20Room%20Cleaner/0489.%20Robot%20Room%20Cleaner.md) |
| 3 | [79. Word Search](https://leetcode.com/problems/word-search/) | Medium | 6+ months | 47.5 | ✅ Solved |  |  |  | [notes](06.%20Board%20%26%20Grid%20Search%20%28N-Queens%2C%20Sudoku%2C%20Word%20Search%29/0079.%20Word%20Search/0079.%20Word%20Search.md) |
| 4 | [37. Sudoku Solver](https://leetcode.com/problems/sudoku-solver/) | Hard | 6+ months | 24.1 | ✅ Solved |  |  |  | [notes](06.%20Board%20%26%20Grid%20Search%20%28N-Queens%2C%20Sudoku%2C%20Word%20Search%29/0037.%20Sudoku%20Solver/0037.%20Sudoku%20Solver.md) |
| 5 | [52. N-Queens II](https://leetcode.com/problems/n-queens-ii/) | Hard | 6+ months | 21.5 | Todo |  |  |  | [notes](06.%20Board%20%26%20Grid%20Search%20%28N-Queens%2C%20Sudoku%2C%20Word%20Search%29/0052.%20N-Queens%20II/0052.%20N-Queens%20II.md) |
| 6 | [980. Unique Paths III](https://leetcode.com/problems/unique-paths-iii/) | Hard | 6+ months | 20.4 | Todo |  |  |  | [notes](06.%20Board%20%26%20Grid%20Search%20%28N-Queens%2C%20Sudoku%2C%20Word%20Search%29/0980.%20Unique%20Paths%20III/0980.%20Unique%20Paths%20III.md) |

## 07. Generate Valid Strings

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [301. Remove Invalid Parentheses](https://leetcode.com/problems/remove-invalid-parentheses/) | Hard | 3 months | 55.3 | Todo |  |  |  | [notes](07.%20Generate%20Valid%20Strings/0301.%20Remove%20Invalid%20Parentheses/0301.%20Remove%20Invalid%20Parentheses.md) |
| 2 | [22. Generate Parentheses](https://leetcode.com/problems/generate-parentheses/) | Medium | 3 months | 51.2 | Todo |  |  |  | [notes](07.%20Generate%20Valid%20Strings/0022.%20Generate%20Parentheses/0022.%20Generate%20Parentheses.md) |
| 3 | [282. Expression Add Operators](https://leetcode.com/problems/expression-add-operators/) | Hard | 6+ months | 56.9 | ✅ Solved |  |  |  | [notes](07.%20Generate%20Valid%20Strings/0282.%20Expression%20Add%20Operators/0282.%20Expression%20Add%20Operators.md) |
| 4 | [247. Strobogrammatic Number II](https://leetcode.com/problems/strobogrammatic-number-ii/) 🔒 | Medium | 6+ months | 25.2 | Todo |  |  |  | [notes](07.%20Generate%20Valid%20Strings/0247.%20Strobogrammatic%20Number%20II/0247.%20Strobogrammatic%20Number%20II.md) |
| 5 | [1096. Brace Expansion II](https://leetcode.com/problems/brace-expansion-ii/) | Hard | 6+ months | 12.8 | Todo |  |  |  | [notes](07.%20Generate%20Valid%20Strings/1096.%20Brace%20Expansion%20II/1096.%20Brace%20Expansion%20II.md) |
| 6 | [679. 24 Game](https://leetcode.com/problems/24-game/) | Hard | 6+ months | 5.4 | Todo |  |  |  | [notes](07.%20Generate%20Valid%20Strings/0679.%2024%20Game/0679.%2024%20Game.md) |
| 7 | [1415. The k-th Lexicographical String of All Happy Strings of Length n](https://leetcode.com/problems/the-k-th-lexicographical-string-of-all-happy-strings-of-length-n/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](07.%20Generate%20Valid%20Strings/1415.%20The%20k-th%20Lexicographical%20String%20of%20All%20Happy%20Strings%20of%20Length%20n/1415.%20The%20k-th%20Lexicographical%20String%20of%20All%20Happy%20Strings%20of%20Length%20n.md) |
| 8 | [2048. Next Greater Numerically Balanced Number](https://leetcode.com/problems/next-greater-numerically-balanced-number/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](07.%20Generate%20Valid%20Strings/2048.%20Next%20Greater%20Numerically%20Balanced%20Number/2048.%20Next%20Greater%20Numerically%20Balanced%20Number.md) |
| 9 | [2014. Longest Subsequence Repeated k Times](https://leetcode.com/problems/longest-subsequence-repeated-k-times/) | Hard | 6+ months | 36.1 | Todo |  |  |  | [notes](07.%20Generate%20Valid%20Strings/2014.%20Longest%20Subsequence%20Repeated%20k%20Times/2014.%20Longest%20Subsequence%20Repeated%20k%20Times.md) |

## 08. Divide and Conquer

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [95. Unique Binary Search Trees II](https://leetcode.com/problems/unique-binary-search-trees-ii/) | Medium | 6 months | 26.6 | Todo |  |  |  | [notes](08.%20Divide%20and%20Conquer/0095.%20Unique%20Binary%20Search%20Trees%20II/0095.%20Unique%20Binary%20Search%20Trees%20II.md) |
| 2 | [2035. Partition Array Into Two Arrays to Minimize Sum Difference](https://leetcode.com/problems/partition-array-into-two-arrays-to-minimize-sum-difference/) | Hard | 6 months | 5.3 | 🟡 Attempted |  |  |  | [notes](08.%20Divide%20and%20Conquer/2035.%20Partition%20Array%20Into%20Two%20Arrays%20to%20Minimize%20Sum%20Difference/2035.%20Partition%20Array%20Into%20Two%20Arrays%20to%20Minimize%20Sum%20Difference.md) |
| 3 | [427. Construct Quad Tree](https://leetcode.com/problems/construct-quad-tree/) | Medium | 6+ months | 8.6 | Todo |  |  |  | [notes](08.%20Divide%20and%20Conquer/0427.%20Construct%20Quad%20Tree/0427.%20Construct%20Quad%20Tree.md) |
| 4 | [395. Longest Substring with At Least K Repeating Characters](https://leetcode.com/problems/longest-substring-with-at-least-k-repeating-characters/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Divide%20and%20Conquer/0395.%20Longest%20Substring%20with%20At%20Least%20K%20Repeating%20Characters/0395.%20Longest%20Substring%20with%20At%20Least%20K%20Repeating%20Characters.md) |
| 5 | [894. All Possible Full Binary Trees](https://leetcode.com/problems/all-possible-full-binary-trees/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Divide%20and%20Conquer/0894.%20All%20Possible%20Full%20Binary%20Trees/0894.%20All%20Possible%20Full%20Binary%20Trees.md) |
