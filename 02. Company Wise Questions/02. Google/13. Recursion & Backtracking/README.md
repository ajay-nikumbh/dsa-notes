# 13. Recursion & Backtracking

[Back to Google](../README.md) · [Back to DSA Notes](../../../README.md)

84 Google problems: 3 Easy, 57 Medium, 24 Hard, in 8 sub-patterns.

## Sub-patterns

| # | Sub-pattern | Questions | Easy | Medium | Hard | Last 3 Months | Solved | Most Asked |
|:---:|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---|
| 01 | [Basic Recursion](#01-basic-recursion) | 8 | 1 | 7 | 0 | 1 | 0 | 779. K-th Symbol in Grammar, 544. Output Contest Matches, 1545. Find Kth Bit in Nth Binary String |
| 02 | [Subsets](#02-subsets) | 11 | 1 | 8 | 2 | 2 | 4 | 78. Subsets, 90. Subsets II, 320. Generalized Abbreviation |
| 03 | [Permutations](#03-permutations) | 8 | 0 | 7 | 1 | 1 | 2 | 46. Permutations, 526. Beautiful Arrangement, 1079. Letter Tile Possibilities |
| 04 | [Combinations & Combination Sum](#04-combinations--combination-sum) | 6 | 0 | 6 | 0 | 3 | 4 | 17. Letter Combinations of a Phone Number, 39. Combination Sum, 40. Combination Sum II |
| 05 | [Partitioning](#05-partitioning) | 11 | 0 | 9 | 2 | 2 | 2 | 131. Palindrome Partitioning, 140. Word Break II, 1593. Split a String Into the Max Number of Unique Substrings |
| 06 | [Board & Grid Search (N-Queens, Sudoku, Word Search)](#06-board--grid-search-n-queens-sudoku-word-search) | 12 | 0 | 4 | 8 | 4 | 4 | 51. N-Queens, 37. Sudoku Solver, 79. Word Search |
| 07 | [Generate Valid Strings](#07-generate-valid-strings) | 16 | 0 | 9 | 7 | 1 | 1 | 22. Generate Parentheses, 3646. Next Special Palindrome Number, 679. 24 Game |
| 08 | [Divide and Conquer](#08-divide-and-conquer) | 12 | 1 | 7 | 4 | 2 | 0 | 2035. Partition Array Into Two Arrays to Minimize Sum Difference, 932. Beautiful Array, 894. All Possible Full Binary Trees |

**Columns**

- **Last Asked**: most recent LeetCode window that lists the problem for Google (30 days, 3 months, 6 months, 6+ months).
- **Frequency**: LeetCode frequency score (0-100) in the Google "All" list.
- **Status**: your LeetCode status on the day this file was generated. 🔒 after a title means LeetCode Premium.
- **Logic / Key Idea, Time, Space**: fill these in as you solve. A rebuild keeps what you typed.
- **Notes**: link to the problem's notes file.

Inside each sub-pattern, rows are sorted by most recent window, then by frequency (highest first).

## 01. Basic Recursion

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [779. K-th Symbol in Grammar](https://leetcode.com/problems/k-th-symbol-in-grammar/) | Medium | 3 months | 38.9 | Todo |  |  |  | [notes](01.%20Basic%20Recursion/0779.%20K-th%20Symbol%20in%20Grammar/0779.%20K-th%20Symbol%20in%20Grammar.md) |
| 2 | [390. Elimination Game](https://leetcode.com/problems/elimination-game/) | Medium | 6 months | 7.9 | Todo |  |  |  | [notes](01.%20Basic%20Recursion/0390.%20Elimination%20Game/0390.%20Elimination%20Game.md) |
| 3 | [1545. Find Kth Bit in Nth Binary String](https://leetcode.com/problems/find-kth-bit-in-nth-binary-string/) | Medium | 6+ months | 9.1 | Todo |  |  |  | [notes](01.%20Basic%20Recursion/1545.%20Find%20Kth%20Bit%20in%20Nth%20Binary%20String/1545.%20Find%20Kth%20Bit%20in%20Nth%20Binary%20String.md) |
| 4 | [3304. Find the K-th Character in String Game I](https://leetcode.com/problems/find-the-k-th-character-in-string-game-i/) | Easy | 6+ months | 8.7 | Todo |  |  |  | [notes](01.%20Basic%20Recursion/3304.%20Find%20the%20K-th%20Character%20in%20String%20Game%20I/3304.%20Find%20the%20K-th%20Character%20in%20String%20Game%20I.md) |
| 5 | [339. Nested List Weight Sum](https://leetcode.com/problems/nested-list-weight-sum/) 🔒 | Medium | 6+ months | 5.3 | Todo |  |  |  | [notes](01.%20Basic%20Recursion/0339.%20Nested%20List%20Weight%20Sum/0339.%20Nested%20List%20Weight%20Sum.md) |
| 6 | [364. Nested List Weight Sum II](https://leetcode.com/problems/nested-list-weight-sum-ii/) 🔒 | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Basic%20Recursion/0364.%20Nested%20List%20Weight%20Sum%20II/0364.%20Nested%20List%20Weight%20Sum%20II.md) |
| 7 | [2625. Flatten Deeply Nested Array](https://leetcode.com/problems/flatten-deeply-nested-array/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Basic%20Recursion/2625.%20Flatten%20Deeply%20Nested%20Array/2625.%20Flatten%20Deeply%20Nested%20Array.md) |
| 8 | [544. Output Contest Matches](https://leetcode.com/problems/output-contest-matches/) 🔒 | Medium | 6+ months | 30.9 | Todo |  |  |  | [notes](01.%20Basic%20Recursion/0544.%20Output%20Contest%20Matches/0544.%20Output%20Contest%20Matches.md) |

## 02. Subsets

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [78. Subsets](https://leetcode.com/problems/subsets/) | Medium | 3 months | 52.4 | ✅ Solved |  |  |  | [notes](02.%20Subsets/0078.%20Subsets/0078.%20Subsets.md) |
| 2 | [90. Subsets II](https://leetcode.com/problems/subsets-ii/) | Medium | 3 months | 41.7 | ✅ Solved |  |  |  | [notes](02.%20Subsets/0090.%20Subsets%20II/0090.%20Subsets%20II.md) |
| 3 | [784. Letter Case Permutation](https://leetcode.com/problems/letter-case-permutation/) | Medium | 6 months | 8.3 | Todo |  |  |  | [notes](02.%20Subsets/0784.%20Letter%20Case%20Permutation/0784.%20Letter%20Case%20Permutation.md) |
| 4 | [1863. Sum of All Subset XOR Totals](https://leetcode.com/problems/sum-of-all-subset-xor-totals/) | Easy | 6+ months | 8.3 | ✅ Solved |  |  |  | [notes](02.%20Subsets/1863.%20Sum%20of%20All%20Subset%20XOR%20Totals/1863.%20Sum%20of%20All%20Subset%20XOR%20Totals.md) |
| 5 | [491. Non-decreasing Subsequences](https://leetcode.com/problems/non-decreasing-subsequences/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Subsets/0491.%20Non-decreasing%20Subsequences/0491.%20Non-decreasing%20Subsequences.md) |
| 6 | [1239. Maximum Length of a Concatenated String with Unique Characters](https://leetcode.com/problems/maximum-length-of-a-concatenated-string-with-unique-characters/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Subsets/1239.%20Maximum%20Length%20of%20a%20Concatenated%20String%20with%20Unique%20Characters/1239.%20Maximum%20Length%20of%20a%20Concatenated%20String%20with%20Unique%20Characters.md) |
| 7 | [1255. Maximum Score Words Formed by Letters](https://leetcode.com/problems/maximum-score-words-formed-by-letters/) | Hard | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](02.%20Subsets/1255.%20Maximum%20Score%20Words%20Formed%20by%20Letters/1255.%20Maximum%20Score%20Words%20Formed%20by%20Letters.md) |
| 8 | [2044. Count Number of Maximum Bitwise-OR Subsets](https://leetcode.com/problems/count-number-of-maximum-bitwise-or-subsets/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Subsets/2044.%20Count%20Number%20of%20Maximum%20Bitwise-OR%20Subsets/2044.%20Count%20Number%20of%20Maximum%20Bitwise-OR%20Subsets.md) |
| 9 | [320. Generalized Abbreviation](https://leetcode.com/problems/generalized-abbreviation/) 🔒 | Medium | 6+ months | 28.8 | Todo |  |  |  | [notes](02.%20Subsets/0320.%20Generalized%20Abbreviation/0320.%20Generalized%20Abbreviation.md) |
| 10 | [411. Minimum Unique Word Abbreviation](https://leetcode.com/problems/minimum-unique-word-abbreviation/) 🔒 | Hard | 6+ months | 28.8 | Todo |  |  |  | [notes](02.%20Subsets/0411.%20Minimum%20Unique%20Word%20Abbreviation/0411.%20Minimum%20Unique%20Word%20Abbreviation.md) |
| 11 | [1774. Closest Dessert Cost](https://leetcode.com/problems/closest-dessert-cost/) | Medium | 6+ months | 28.8 | Todo |  |  |  | [notes](02.%20Subsets/1774.%20Closest%20Dessert%20Cost/1774.%20Closest%20Dessert%20Cost.md) |

## 03. Permutations

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [47. Permutations II](https://leetcode.com/problems/permutations-ii/) | Medium | 3 months | 26.7 | ✅ Solved |  |  |  | [notes](03.%20Permutations/0047.%20Permutations%20II/0047.%20Permutations%20II.md) |
| 2 | [46. Permutations](https://leetcode.com/problems/permutations/) | Medium | 6 months | 47.2 | ✅ Solved |  |  |  | [notes](03.%20Permutations/0046.%20Permutations/0046.%20Permutations.md) |
| 3 | [526. Beautiful Arrangement](https://leetcode.com/problems/beautiful-arrangement/) | Medium | 6+ months | 31.3 | Todo |  |  |  | [notes](03.%20Permutations/0526.%20Beautiful%20Arrangement/0526.%20Beautiful%20Arrangement.md) |
| 4 | [3720. Lexicographically Smallest Permutation Greater Than Target](https://leetcode.com/problems/lexicographically-smallest-permutation-greater-than-target/) | Medium | 6+ months | 11.8 | Todo |  |  |  | [notes](03.%20Permutations/3720.%20Lexicographically%20Smallest%20Permutation%20Greater%20Than%20Target/3720.%20Lexicographically%20Smallest%20Permutation%20Greater%20Than%20Target.md) |
| 5 | [996. Number of Squareful Arrays](https://leetcode.com/problems/number-of-squareful-arrays/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](03.%20Permutations/0996.%20Number%20of%20Squareful%20Arrays/0996.%20Number%20of%20Squareful%20Arrays.md) |
| 6 | [1718. Construct the Lexicographically Largest Valid Sequence](https://leetcode.com/problems/construct-the-lexicographically-largest-valid-sequence/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](03.%20Permutations/1718.%20Construct%20the%20Lexicographically%20Largest%20Valid%20Sequence/1718.%20Construct%20the%20Lexicographically%20Largest%20Valid%20Sequence.md) |
| 7 | [3309. Maximum Possible Number by Binary Concatenation](https://leetcode.com/problems/maximum-possible-number-by-binary-concatenation/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](03.%20Permutations/3309.%20Maximum%20Possible%20Number%20by%20Binary%20Concatenation/3309.%20Maximum%20Possible%20Number%20by%20Binary%20Concatenation.md) |
| 8 | [1079. Letter Tile Possibilities](https://leetcode.com/problems/letter-tile-possibilities/) | Medium | 6+ months | 29.3 | Todo |  |  |  | [notes](03.%20Permutations/1079.%20Letter%20Tile%20Possibilities/1079.%20Letter%20Tile%20Possibilities.md) |

## 04. Combinations & Combination Sum

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [39. Combination Sum](https://leetcode.com/problems/combination-sum/) | Medium | 30 days | 49.5 | ✅ Solved |  |  |  | [notes](04.%20Combinations%20%26%20Combination%20Sum/0039.%20Combination%20Sum/0039.%20Combination%20Sum.md) |
| 2 | [17. Letter Combinations of a Phone Number](https://leetcode.com/problems/letter-combinations-of-a-phone-number/) | Medium | 3 months | 63.9 | ✅ Solved |  |  |  | [notes](04.%20Combinations%20%26%20Combination%20Sum/0017.%20Letter%20Combinations%20of%20a%20Phone%20Number/0017.%20Letter%20Combinations%20of%20a%20Phone%20Number.md) |
| 3 | [40. Combination Sum II](https://leetcode.com/problems/combination-sum-ii/) | Medium | 3 months | 33.1 | ✅ Solved |  |  |  | [notes](04.%20Combinations%20%26%20Combination%20Sum/0040.%20Combination%20Sum%20II/0040.%20Combination%20Sum%20II.md) |
| 4 | [77. Combinations](https://leetcode.com/problems/combinations/) | Medium | 6 months | 30.7 | ✅ Solved |  |  |  | [notes](04.%20Combinations%20%26%20Combination%20Sum/0077.%20Combinations/0077.%20Combinations.md) |
| 5 | [216. Combination Sum III](https://leetcode.com/problems/combination-sum-iii/) | Medium | 6+ months | 11.4 | Todo |  |  |  | [notes](04.%20Combinations%20%26%20Combination%20Sum/0216.%20Combination%20Sum%20III/0216.%20Combination%20Sum%20III.md) |
| 6 | [3669. Balanced K-Factor Decomposition](https://leetcode.com/problems/balanced-k-factor-decomposition/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Combinations%20%26%20Combination%20Sum/3669.%20Balanced%20K-Factor%20Decomposition/3669.%20Balanced%20K-Factor%20Decomposition.md) |

## 05. Partitioning

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [131. Palindrome Partitioning](https://leetcode.com/problems/palindrome-partitioning/) | Medium | 3 months | 37.8 | ✅ Solved |  |  |  | [notes](05.%20Partitioning/0131.%20Palindrome%20Partitioning/0131.%20Palindrome%20Partitioning.md) |
| 2 | [698. Partition to K Equal Sum Subsets](https://leetcode.com/problems/partition-to-k-equal-sum-subsets/) | Medium | 3 months | 15.9 | Todo |  |  |  | [notes](05.%20Partitioning/0698.%20Partition%20to%20K%20Equal%20Sum%20Subsets/0698.%20Partition%20to%20K%20Equal%20Sum%20Subsets.md) |
| 3 | [93. Restore IP Addresses](https://leetcode.com/problems/restore-ip-addresses/) | Medium | 6 months | 15.9 | Todo |  |  |  | [notes](05.%20Partitioning/0093.%20Restore%20IP%20Addresses/0093.%20Restore%20IP%20Addresses.md) |
| 4 | [140. Word Break II](https://leetcode.com/problems/word-break-ii/) | Hard | 6+ months | 34.8 | ✅ Solved |  |  |  | [notes](05.%20Partitioning/0140.%20Word%20Break%20II/0140.%20Word%20Break%20II.md) |
| 5 | [473. Matchsticks to Square](https://leetcode.com/problems/matchsticks-to-square/) | Medium | 6+ months | 9.9 | Todo |  |  |  | [notes](05.%20Partitioning/0473.%20Matchsticks%20to%20Square/0473.%20Matchsticks%20to%20Square.md) |
| 6 | [2698. Find the Punishment Number of an Integer](https://leetcode.com/problems/find-the-punishment-number-of-an-integer/) | Medium | 6+ months | 6.7 | Todo |  |  |  | [notes](05.%20Partitioning/2698.%20Find%20the%20Punishment%20Number%20of%20an%20Integer/2698.%20Find%20the%20Punishment%20Number%20of%20an%20Integer.md) |
| 7 | [306. Additive Number](https://leetcode.com/problems/additive-number/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Partitioning/0306.%20Additive%20Number/0306.%20Additive%20Number.md) |
| 8 | [842. Split Array into Fibonacci Sequence](https://leetcode.com/problems/split-array-into-fibonacci-sequence/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Partitioning/0842.%20Split%20Array%20into%20Fibonacci%20Sequence/0842.%20Split%20Array%20into%20Fibonacci%20Sequence.md) |
| 9 | [1723. Find Minimum Time to Finish All Jobs](https://leetcode.com/problems/find-minimum-time-to-finish-all-jobs/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Partitioning/1723.%20Find%20Minimum%20Time%20to%20Finish%20All%20Jobs/1723.%20Find%20Minimum%20Time%20to%20Finish%20All%20Jobs.md) |
| 10 | [1593. Split a String Into the Max Number of Unique Substrings](https://leetcode.com/problems/split-a-string-into-the-max-number-of-unique-substrings/) | Medium | 6+ months | 29.5 | Todo |  |  |  | [notes](05.%20Partitioning/1593.%20Split%20a%20String%20Into%20the%20Max%20Number%20of%20Unique%20Substrings/1593.%20Split%20a%20String%20Into%20the%20Max%20Number%20of%20Unique%20Substrings.md) |
| 11 | [816. Ambiguous Coordinates](https://leetcode.com/problems/ambiguous-coordinates/) | Medium | 6+ months | 28.8 | Todo |  |  |  | [notes](05.%20Partitioning/0816.%20Ambiguous%20Coordinates/0816.%20Ambiguous%20Coordinates.md) |

## 06. Board & Grid Search (N-Queens, Sudoku, Word Search)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [79. Word Search](https://leetcode.com/problems/word-search/) | Medium | 30 days | 43.4 | ✅ Solved |  |  |  | [notes](06.%20Board%20%26%20Grid%20Search%20%28N-Queens%2C%20Sudoku%2C%20Word%20Search%29/0079.%20Word%20Search/0079.%20Word%20Search.md) |
| 2 | [51. N-Queens](https://leetcode.com/problems/n-queens/) | Hard | 3 months | 59.9 | ✅ Solved |  |  |  | [notes](06.%20Board%20%26%20Grid%20Search%20%28N-Queens%2C%20Sudoku%2C%20Word%20Search%29/0051.%20N-Queens/0051.%20N-Queens.md) |
| 3 | [37. Sudoku Solver](https://leetcode.com/problems/sudoku-solver/) | Hard | 3 months | 45.0 | ✅ Solved |  |  |  | [notes](06.%20Board%20%26%20Grid%20Search%20%28N-Queens%2C%20Sudoku%2C%20Word%20Search%29/0037.%20Sudoku%20Solver/0037.%20Sudoku%20Solver.md) |
| 4 | [1307. Verbal Arithmetic Puzzle](https://leetcode.com/problems/verbal-arithmetic-puzzle/) | Hard | 3 months | 9.3 | Todo |  |  |  | [notes](06.%20Board%20%26%20Grid%20Search%20%28N-Queens%2C%20Sudoku%2C%20Word%20Search%29/1307.%20Verbal%20Arithmetic%20Puzzle/1307.%20Verbal%20Arithmetic%20Puzzle.md) |
| 5 | [52. N-Queens II](https://leetcode.com/problems/n-queens-ii/) | Hard | 6 months | 17.6 | Todo |  |  |  | [notes](06.%20Board%20%26%20Grid%20Search%20%28N-Queens%2C%20Sudoku%2C%20Word%20Search%29/0052.%20N-Queens%20II/0052.%20N-Queens%20II.md) |
| 6 | [351. Android Unlock Patterns](https://leetcode.com/problems/android-unlock-patterns/) 🔒 | Medium | 6+ months | 34.7 | Todo |  |  |  | [notes](06.%20Board%20%26%20Grid%20Search%20%28N-Queens%2C%20Sudoku%2C%20Word%20Search%29/0351.%20Android%20Unlock%20Patterns/0351.%20Android%20Unlock%20Patterns.md) |
| 7 | [1240. Tiling a Rectangle with the Fewest Squares](https://leetcode.com/problems/tiling-a-rectangle-with-the-fewest-squares/) | Hard | 6+ months | 33.2 | Todo |  |  |  | [notes](06.%20Board%20%26%20Grid%20Search%20%28N-Queens%2C%20Sudoku%2C%20Word%20Search%29/1240.%20Tiling%20a%20Rectangle%20with%20the%20Fewest%20Squares/1240.%20Tiling%20a%20Rectangle%20with%20the%20Fewest%20Squares.md) |
| 8 | [489. Robot Room Cleaner](https://leetcode.com/problems/robot-room-cleaner/) 🔒 | Hard | 6+ months | 33.1 | Todo |  |  |  | [notes](06.%20Board%20%26%20Grid%20Search%20%28N-Queens%2C%20Sudoku%2C%20Word%20Search%29/0489.%20Robot%20Room%20Cleaner/0489.%20Robot%20Room%20Cleaner.md) |
| 9 | [1219. Path with Maximum Gold](https://leetcode.com/problems/path-with-maximum-gold/) | Medium | 6+ months | 30.9 | ✅ Solved |  |  |  | [notes](06.%20Board%20%26%20Grid%20Search%20%28N-Queens%2C%20Sudoku%2C%20Word%20Search%29/1219.%20Path%20with%20Maximum%20Gold/1219.%20Path%20with%20Maximum%20Gold.md) |
| 10 | [980. Unique Paths III](https://leetcode.com/problems/unique-paths-iii/) | Hard | 6+ months | 9.8 | Todo |  |  |  | [notes](06.%20Board%20%26%20Grid%20Search%20%28N-Queens%2C%20Sudoku%2C%20Word%20Search%29/0980.%20Unique%20Paths%20III/0980.%20Unique%20Paths%20III.md) |
| 11 | [2056. Number of Valid Move Combinations On Chessboard](https://leetcode.com/problems/number-of-valid-move-combinations-on-chessboard/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20Board%20%26%20Grid%20Search%20%28N-Queens%2C%20Sudoku%2C%20Word%20Search%29/2056.%20Number%20of%20Valid%20Move%20Combinations%20On%20Chessboard/2056.%20Number%20of%20Valid%20Move%20Combinations%20On%20Chessboard.md) |
| 12 | [2174. Remove All Ones With Row and Column Flips II](https://leetcode.com/problems/remove-all-ones-with-row-and-column-flips-ii/) 🔒 | Medium | 6+ months | 28.8 | Todo |  |  |  | [notes](06.%20Board%20%26%20Grid%20Search%20%28N-Queens%2C%20Sudoku%2C%20Word%20Search%29/2174.%20Remove%20All%20Ones%20With%20Row%20and%20Column%20Flips%20II/2174.%20Remove%20All%20Ones%20With%20Row%20and%20Column%20Flips%20II.md) |

## 07. Generate Valid Strings

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [22. Generate Parentheses](https://leetcode.com/problems/generate-parentheses/) | Medium | 3 months | 61.4 | Todo |  |  |  | [notes](07.%20Generate%20Valid%20Strings/0022.%20Generate%20Parentheses/0022.%20Generate%20Parentheses.md) |
| 2 | [3646. Next Special Palindrome Number](https://leetcode.com/problems/next-special-palindrome-number/) | Hard | 6 months | 41.0 | Todo |  |  |  | [notes](07.%20Generate%20Valid%20Strings/3646.%20Next%20Special%20Palindrome%20Number/3646.%20Next%20Special%20Palindrome%20Number.md) |
| 3 | [679. 24 Game](https://leetcode.com/problems/24-game/) | Hard | 6 months | 40.3 | Todo |  |  |  | [notes](07.%20Generate%20Valid%20Strings/0679.%2024%20Game/0679.%2024%20Game.md) |
| 4 | [1096. Brace Expansion II](https://leetcode.com/problems/brace-expansion-ii/) | Hard | 6 months | 34.2 | Todo |  |  |  | [notes](07.%20Generate%20Valid%20Strings/1096.%20Brace%20Expansion%20II/1096.%20Brace%20Expansion%20II.md) |
| 5 | [301. Remove Invalid Parentheses](https://leetcode.com/problems/remove-invalid-parentheses/) | Hard | 6 months | 12.8 | Todo |  |  |  | [notes](07.%20Generate%20Valid%20Strings/0301.%20Remove%20Invalid%20Parentheses/0301.%20Remove%20Invalid%20Parentheses.md) |
| 6 | [282. Expression Add Operators](https://leetcode.com/problems/expression-add-operators/) | Hard | 6+ months | 39.3 | ✅ Solved |  |  |  | [notes](07.%20Generate%20Valid%20Strings/0282.%20Expression%20Add%20Operators/0282.%20Expression%20Add%20Operators.md) |
| 7 | [756. Pyramid Transition Matrix](https://leetcode.com/problems/pyramid-transition-matrix/) | Medium | 6+ months | 33.2 | Todo |  |  |  | [notes](07.%20Generate%20Valid%20Strings/0756.%20Pyramid%20Transition%20Matrix/0756.%20Pyramid%20Transition%20Matrix.md) |
| 8 | [1415. The k-th Lexicographical String of All Happy Strings of Length n](https://leetcode.com/problems/the-k-th-lexicographical-string-of-all-happy-strings-of-length-n/) | Medium | 6+ months | 16.5 | Todo |  |  |  | [notes](07.%20Generate%20Valid%20Strings/1415.%20The%20k-th%20Lexicographical%20String%20of%20All%20Happy%20Strings%20of%20Length%20n/1415.%20The%20k-th%20Lexicographical%20String%20of%20All%20Happy%20Strings%20of%20Length%20n.md) |
| 9 | [2048. Next Greater Numerically Balanced Number](https://leetcode.com/problems/next-greater-numerically-balanced-number/) | Medium | 6+ months | 12.9 | Todo |  |  |  | [notes](07.%20Generate%20Valid%20Strings/2048.%20Next%20Greater%20Numerically%20Balanced%20Number/2048.%20Next%20Greater%20Numerically%20Balanced%20Number.md) |
| 10 | [3211. Generate Binary Strings Without Adjacent Zeros](https://leetcode.com/problems/generate-binary-strings-without-adjacent-zeros/) | Medium | 6+ months | 8.1 | Todo |  |  |  | [notes](07.%20Generate%20Valid%20Strings/3211.%20Generate%20Binary%20Strings%20Without%20Adjacent%20Zeros/3211.%20Generate%20Binary%20Strings%20Without%20Adjacent%20Zeros.md) |
| 11 | [967. Numbers With Same Consecutive Differences](https://leetcode.com/problems/numbers-with-same-consecutive-differences/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](07.%20Generate%20Valid%20Strings/0967.%20Numbers%20With%20Same%20Consecutive%20Differences/0967.%20Numbers%20With%20Same%20Consecutive%20Differences.md) |
| 12 | [2014. Longest Subsequence Repeated k Times](https://leetcode.com/problems/longest-subsequence-repeated-k-times/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](07.%20Generate%20Valid%20Strings/2014.%20Longest%20Subsequence%20Repeated%20k%20Times/2014.%20Longest%20Subsequence%20Repeated%20k%20Times.md) |
| 13 | [247. Strobogrammatic Number II](https://leetcode.com/problems/strobogrammatic-number-ii/) 🔒 | Medium | 6+ months | 28.8 | Todo |  |  |  | [notes](07.%20Generate%20Valid%20Strings/0247.%20Strobogrammatic%20Number%20II/0247.%20Strobogrammatic%20Number%20II.md) |
| 14 | [681. Next Closest Time](https://leetcode.com/problems/next-closest-time/) 🔒 | Medium | 6+ months | 28.8 | Todo |  |  |  | [notes](07.%20Generate%20Valid%20Strings/0681.%20Next%20Closest%20Time/0681.%20Next%20Closest%20Time.md) |
| 15 | [1087. Brace Expansion](https://leetcode.com/problems/brace-expansion/) 🔒 | Medium | 6+ months | 28.8 | Todo |  |  |  | [notes](07.%20Generate%20Valid%20Strings/1087.%20Brace%20Expansion/1087.%20Brace%20Expansion.md) |
| 16 | [1088. Confusing Number II](https://leetcode.com/problems/confusing-number-ii/) 🔒 | Hard | 6+ months | 28.8 | Todo |  |  |  | [notes](07.%20Generate%20Valid%20Strings/1088.%20Confusing%20Number%20II/1088.%20Confusing%20Number%20II.md) |

## 08. Divide and Conquer

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [2035. Partition Array Into Two Arrays to Minimize Sum Difference](https://leetcode.com/problems/partition-array-into-two-arrays-to-minimize-sum-difference/) | Hard | 3 months | 35.3 | 🟡 Attempted |  |  |  | [notes](08.%20Divide%20and%20Conquer/2035.%20Partition%20Array%20Into%20Two%20Arrays%20to%20Minimize%20Sum%20Difference/2035.%20Partition%20Array%20Into%20Two%20Arrays%20to%20Minimize%20Sum%20Difference.md) |
| 2 | [932. Beautiful Array](https://leetcode.com/problems/beautiful-array/) | Medium | 3 months | 33.8 | Todo |  |  |  | [notes](08.%20Divide%20and%20Conquer/0932.%20Beautiful%20Array/0932.%20Beautiful%20Array.md) |
| 3 | [95. Unique Binary Search Trees II](https://leetcode.com/problems/unique-binary-search-trees-ii/) | Medium | 6 months | 18.9 | Todo |  |  |  | [notes](08.%20Divide%20and%20Conquer/0095.%20Unique%20Binary%20Search%20Trees%20II/0095.%20Unique%20Binary%20Search%20Trees%20II.md) |
| 4 | [395. Longest Substring with At Least K Repeating Characters](https://leetcode.com/problems/longest-substring-with-at-least-k-repeating-characters/) | Medium | 6 months | 12.0 | Todo |  |  |  | [notes](08.%20Divide%20and%20Conquer/0395.%20Longest%20Substring%20with%20At%20Least%20K%20Repeating%20Characters/0395.%20Longest%20Substring%20with%20At%20Least%20K%20Repeating%20Characters.md) |
| 5 | [894. All Possible Full Binary Trees](https://leetcode.com/problems/all-possible-full-binary-trees/) | Medium | 6+ months | 30.5 | Todo |  |  |  | [notes](08.%20Divide%20and%20Conquer/0894.%20All%20Possible%20Full%20Binary%20Trees/0894.%20All%20Possible%20Full%20Binary%20Trees.md) |
| 6 | [3537. Fill a Special Grid](https://leetcode.com/problems/fill-a-special-grid/) | Medium | 6+ months | 19.3 | Todo |  |  |  | [notes](08.%20Divide%20and%20Conquer/3537.%20Fill%20a%20Special%20Grid/3537.%20Fill%20a%20Special%20Grid.md) |
| 7 | [761. Special Binary String](https://leetcode.com/problems/special-binary-string/) | Hard | 6+ months | 18.0 | Todo |  |  |  | [notes](08.%20Divide%20and%20Conquer/0761.%20Special%20Binary%20String/0761.%20Special%20Binary%20String.md) |
| 8 | [427. Construct Quad Tree](https://leetcode.com/problems/construct-quad-tree/) | Medium | 6+ months | 15.5 | Todo |  |  |  | [notes](08.%20Divide%20and%20Conquer/0427.%20Construct%20Quad%20Tree/0427.%20Construct%20Quad%20Tree.md) |
| 9 | [241. Different Ways to Add Parentheses](https://leetcode.com/problems/different-ways-to-add-parentheses/) | Medium | 6+ months | 7.0 | Todo |  |  |  | [notes](08.%20Divide%20and%20Conquer/0241.%20Different%20Ways%20to%20Add%20Parentheses/0241.%20Different%20Ways%20to%20Add%20Parentheses.md) |
| 10 | [1755. Closest Subsequence Sum](https://leetcode.com/problems/closest-subsequence-sum/) | Hard | 6+ months | 6.8 | Todo |  |  |  | [notes](08.%20Divide%20and%20Conquer/1755.%20Closest%20Subsequence%20Sum/1755.%20Closest%20Subsequence%20Sum.md) |
| 11 | [1763. Longest Nice Substring](https://leetcode.com/problems/longest-nice-substring/) | Easy | 6+ months | 6.3 | Todo |  |  |  | [notes](08.%20Divide%20and%20Conquer/1763.%20Longest%20Nice%20Substring/1763.%20Longest%20Nice%20Substring.md) |
| 12 | [805. Split Array With Same Average](https://leetcode.com/problems/split-array-with-same-average/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Divide%20and%20Conquer/0805.%20Split%20Array%20With%20Same%20Average/0805.%20Split%20Array%20With%20Same%20Average.md) |
