# 21. Dynamic Programming

[Back to Facebook](../README.md) · [Back to DSA Notes](../../../README.md)

135 Meta (Facebook) problems: 6 Easy, 74 Medium, 55 Hard, in 15 sub-patterns.

## Sub-patterns

| # | Sub-pattern | Questions | Easy | Medium | Hard | Last 3 Months | Solved | Most Asked |
|:---:|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---|
| 01 | [1D DP (Fibonacci Style)](#01-1d-dp-fibonacci-style) | 28 | 6 | 17 | 5 | 3 | 7 | 139. Word Break, 70. Climbing Stairs, 91. Decode Ways |
| 02 | [Take or Skip (House Robber)](#02-take-or-skip-house-robber) | 4 | 0 | 4 | 0 | 1 | 3 | 198. House Robber, 213. House Robber II, 740. Delete and Earn |
| 03 | [0-1 Knapsack](#03-0-1-knapsack) | 6 | 0 | 5 | 1 | 0 | 2 | 494. Target Sum, 416. Partition Equal Subset Sum, 474. Ones and Zeroes |
| 04 | [Unbounded Knapsack (Coin Change)](#04-unbounded-knapsack-coin-change) | 5 | 0 | 5 | 0 | 1 | 2 | 322. Coin Change, 377. Combination Sum IV, 279. Perfect Squares |
| 05 | [Longest Increasing Subsequence](#05-longest-increasing-subsequence) | 7 | 0 | 5 | 2 | 0 | 4 | 300. Longest Increasing Subsequence, 673. Number of Longest Increasing Subsequence, 354. Russian Doll Envelopes |
| 06 | [2D Grid DP](#06-2d-grid-dp) | 15 | 0 | 10 | 5 | 0 | 3 | 62. Unique Paths, 221. Maximal Square, 764. Largest Plus Sign |
| 07 | [String DP (LCS, Edit Distance)](#07-string-dp-lcs-edit-distance) | 12 | 0 | 5 | 7 | 1 | 5 | 10. Regular Expression Matching, 44. Wildcard Matching, 72. Edit Distance |
| 08 | [Palindrome DP](#08-palindrome-dp) | 4 | 0 | 1 | 3 | 0 | 2 | 1216. Valid Palindrome III, 516. Longest Palindromic Subsequence, 132. Palindrome Partitioning II |
| 09 | [Interval DP](#09-interval-dp) | 9 | 0 | 3 | 6 | 0 | 2 | 312. Burst Balloons, 1039. Minimum Score Triangulation of Polygon, 375. Guess Number Higher or Lower II |
| 10 | [DP on Trees](#10-dp-on-trees) | 6 | 0 | 2 | 4 | 0 | 1 | 968. Binary Tree Cameras, 1373. Maximum Sum BST in Binary Tree, 333. Largest BST Subtree |
| 11 | [Bitmask DP](#11-bitmask-dp) | 6 | 0 | 2 | 4 | 0 | 0 | 1947. Maximum Compatibility Score Sum, 847. Shortest Path Visiting All Nodes, 691. Stickers to Spell Word |
| 12 | [State Machine DP (Stocks)](#12-state-machine-dp-stocks) | 12 | 0 | 7 | 5 | 0 | 4 | 123. Best Time to Buy and Sell Stock III, 714. Best Time to Buy and Sell Stock with Transaction Fee, 801. Minimum Swaps To Make Sequences Increasing |
| 13 | [Digit DP](#13-digit-dp) | 3 | 0 | 0 | 3 | 0 | 0 | 233. Number of Digit One, 2999. Count the Number of Powerful Integers, 3490. Count Beautiful Numbers |
| 14 | [Counting DP](#14-counting-dp) | 15 | 0 | 7 | 8 | 1 | 0 | 96. Unique Binary Search Trees, 3336. Find the Number of Subsequences With Equal GCD, 940. Distinct Subsequences II |
| 15 | [Memoized DFS](#15-memoized-dfs) | 3 | 0 | 1 | 2 | 0 | 0 | 329. Longest Increasing Path in a Matrix, 1140. Stone Game II, 1900. The Earliest and Latest Rounds Where Players Compete |

**Columns**

- **Last Asked**: most recent LeetCode window that lists the problem for Meta (30 days, 3 months, 6 months or 6+ months).
- **Frequency**: LeetCode frequency score (0-100) in the Meta "All" list.
- **Status**: your LeetCode status on the day this file was generated. 🔒 after a title means LeetCode Premium.
- **Logic / Key Idea, Time, Space**: fill these in as you solve. A rebuild keeps what you typed.
- **Notes**: link to the problem's notes file.

Inside each sub-pattern, rows are sorted by most recent window, then by frequency (highest first).

## 01. 1D DP (Fibonacci Style)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [3505. Minimum Operations to Make Elements Within K Subarrays Equal](https://leetcode.com/problems/minimum-operations-to-make-elements-within-k-subarrays-equal/) | Hard | 30 days | 9.2 | Todo |  |  |  | [notes](01.%201D%20DP%20%28Fibonacci%20Style%29/3505.%20Minimum%20Operations%20to%20Make%20Elements%20Within%20K%20Subarrays%20Equal/3505.%20Minimum%20Operations%20to%20Make%20Elements%20Within%20K%20Subarrays%20Equal.md) |
| 2 | [70. Climbing Stairs](https://leetcode.com/problems/climbing-stairs/) | Easy | 3 months | 46.5 | ✅ Solved |  |  |  | [notes](01.%201D%20DP%20%28Fibonacci%20Style%29/0070.%20Climbing%20Stairs/0070.%20Climbing%20Stairs.md) |
| 3 | [3186. Maximum Total Damage With Spell Casting](https://leetcode.com/problems/maximum-total-damage-with-spell-casting/) | Medium | 3 months | 7.1 | Todo |  |  |  | [notes](01.%201D%20DP%20%28Fibonacci%20Style%29/3186.%20Maximum%20Total%20Damage%20With%20Spell%20Casting/3186.%20Maximum%20Total%20Damage%20With%20Spell%20Casting.md) |
| 4 | [91. Decode Ways](https://leetcode.com/problems/decode-ways/) | Medium | 6 months | 45.5 | ✅ Solved |  |  |  | [notes](01.%201D%20DP%20%28Fibonacci%20Style%29/0091.%20Decode%20Ways/0091.%20Decode%20Ways.md) |
| 5 | [509. Fibonacci Number](https://leetcode.com/problems/fibonacci-number/) | Easy | 6 months | 39.7 | ✅ Solved |  |  |  | [notes](01.%201D%20DP%20%28Fibonacci%20Style%29/0509.%20Fibonacci%20Number/0509.%20Fibonacci%20Number.md) |
| 6 | [118. Pascal's Triangle](https://leetcode.com/problems/pascals-triangle/) | Easy | 6 months | 39.1 | ✅ Solved |  |  |  | [notes](01.%201D%20DP%20%28Fibonacci%20Style%29/0118.%20Pascal%27s%20Triangle/0118.%20Pascal%27s%20Triangle.md) |
| 7 | [343. Integer Break](https://leetcode.com/problems/integer-break/) | Medium | 6 months | 25.6 | Todo |  |  |  | [notes](01.%201D%20DP%20%28Fibonacci%20Style%29/0343.%20Integer%20Break/0343.%20Integer%20Break.md) |
| 8 | [413. Arithmetic Slices](https://leetcode.com/problems/arithmetic-slices/) | Medium | 6 months | 11.8 | Todo |  |  |  | [notes](01.%201D%20DP%20%28Fibonacci%20Style%29/0413.%20Arithmetic%20Slices/0413.%20Arithmetic%20Slices.md) |
| 9 | [1235. Maximum Profit in Job Scheduling](https://leetcode.com/problems/maximum-profit-in-job-scheduling/) | Hard | 6 months | 5.5 | Todo |  |  |  | [notes](01.%201D%20DP%20%28Fibonacci%20Style%29/1235.%20Maximum%20Profit%20in%20Job%20Scheduling/1235.%20Maximum%20Profit%20in%20Job%20Scheduling.md) |
| 10 | [139. Word Break](https://leetcode.com/problems/word-break/) | Medium | 6+ months | 52.9 | Todo |  |  |  | [notes](01.%201D%20DP%20%28Fibonacci%20Style%29/0139.%20Word%20Break/0139.%20Word%20Break.md) |
| 11 | [639. Decode Ways II](https://leetcode.com/problems/decode-ways-ii/) | Hard | 6+ months | 38.1 | Todo |  |  |  | [notes](01.%201D%20DP%20%28Fibonacci%20Style%29/0639.%20Decode%20Ways%20II/0639.%20Decode%20Ways%20II.md) |
| 12 | [746. Min Cost Climbing Stairs](https://leetcode.com/problems/min-cost-climbing-stairs/) | Easy | 6+ months | 27.2 | ✅ Solved |  |  |  | [notes](01.%201D%20DP%20%28Fibonacci%20Style%29/0746.%20Min%20Cost%20Climbing%20Stairs/0746.%20Min%20Cost%20Climbing%20Stairs.md) |
| 13 | [983. Minimum Cost For Tickets](https://leetcode.com/problems/minimum-cost-for-tickets/) | Medium | 6+ months | 21.2 | Todo |  |  |  | [notes](01.%201D%20DP%20%28Fibonacci%20Style%29/0983.%20Minimum%20Cost%20For%20Tickets/0983.%20Minimum%20Cost%20For%20Tickets.md) |
| 14 | [837. New 21 Game](https://leetcode.com/problems/new-21-game/) | Medium | 6+ months | 10.4 | Todo |  |  |  | [notes](01.%201D%20DP%20%28Fibonacci%20Style%29/0837.%20New%2021%20Game/0837.%20New%2021%20Game.md) |
| 15 | [119. Pascal's Triangle II](https://leetcode.com/problems/pascals-triangle-ii/) | Easy | 6+ months | 9.8 | Todo |  |  |  | [notes](01.%201D%20DP%20%28Fibonacci%20Style%29/0119.%20Pascal%27s%20Triangle%20II/0119.%20Pascal%27s%20Triangle%20II.md) |
| 16 | [1137. N-th Tribonacci Number](https://leetcode.com/problems/n-th-tribonacci-number/) | Easy | 6+ months | 5.6 | ✅ Solved |  |  |  | [notes](01.%201D%20DP%20%28Fibonacci%20Style%29/1137.%20N-th%20Tribonacci%20Number/1137.%20N-th%20Tribonacci%20Number.md) |
| 17 | [2008. Maximum Earnings From Taxi](https://leetcode.com/problems/maximum-earnings-from-taxi/) | Medium | 6+ months | 5.3 | Todo |  |  |  | [notes](01.%201D%20DP%20%28Fibonacci%20Style%29/2008.%20Maximum%20Earnings%20From%20Taxi/2008.%20Maximum%20Earnings%20From%20Taxi.md) |
| 18 | [1406. Stone Game III](https://leetcode.com/problems/stone-game-iii/) | Hard | 6+ months | 5.1 | Todo |  |  |  | [notes](01.%201D%20DP%20%28Fibonacci%20Style%29/1406.%20Stone%20Game%20III/1406.%20Stone%20Game%20III.md) |
| 19 | [264. Ugly Number II](https://leetcode.com/problems/ugly-number-ii/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%201D%20DP%20%28Fibonacci%20Style%29/0264.%20Ugly%20Number%20II/0264.%20Ugly%20Number%20II.md) |
| 20 | [276. Paint Fence](https://leetcode.com/problems/paint-fence/) 🔒 | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%201D%20DP%20%28Fibonacci%20Style%29/0276.%20Paint%20Fence/0276.%20Paint%20Fence.md) |
| 21 | [790. Domino and Tromino Tiling](https://leetcode.com/problems/domino-and-tromino-tiling/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%201D%20DP%20%28Fibonacci%20Style%29/0790.%20Domino%20and%20Tromino%20Tiling/0790.%20Domino%20and%20Tromino%20Tiling.md) |
| 22 | [2466. Count Ways To Build Good Strings](https://leetcode.com/problems/count-ways-to-build-good-strings/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%201D%20DP%20%28Fibonacci%20Style%29/2466.%20Count%20Ways%20To%20Build%20Good%20Strings/2466.%20Count%20Ways%20To%20Build%20Good%20Strings.md) |
| 23 | [2770. Maximum Number of Jumps to Reach the Last Index](https://leetcode.com/problems/maximum-number-of-jumps-to-reach-the-last-index/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%201D%20DP%20%28Fibonacci%20Style%29/2770.%20Maximum%20Number%20of%20Jumps%20to%20Reach%20the%20Last%20Index/2770.%20Maximum%20Number%20of%20Jumps%20to%20Reach%20the%20Last%20Index.md) |
| 24 | [3201. Find the Maximum Length of Valid Subsequence I](https://leetcode.com/problems/find-the-maximum-length-of-valid-subsequence-i/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%201D%20DP%20%28Fibonacci%20Style%29/3201.%20Find%20the%20Maximum%20Length%20of%20Valid%20Subsequence%20I/3201.%20Find%20the%20Maximum%20Length%20of%20Valid%20Subsequence%20I.md) |
| 25 | [3202. Find the Maximum Length of Valid Subsequence II](https://leetcode.com/problems/find-the-maximum-length-of-valid-subsequence-ii/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%201D%20DP%20%28Fibonacci%20Style%29/3202.%20Find%20the%20Maximum%20Length%20of%20Valid%20Subsequence%20II/3202.%20Find%20the%20Maximum%20Length%20of%20Valid%20Subsequence%20II.md) |
| 26 | [1043. Partition Array for Maximum Sum](https://leetcode.com/problems/partition-array-for-maximum-sum/) | Medium | 6+ months | 36.6 | ✅ Solved |  |  |  | [notes](01.%201D%20DP%20%28Fibonacci%20Style%29/1043.%20Partition%20Array%20for%20Maximum%20Sum/1043.%20Partition%20Array%20for%20Maximum%20Sum.md) |
| 27 | [265. Paint House II](https://leetcode.com/problems/paint-house-ii/) 🔒 | Hard | 6+ months | 36.1 | Todo |  |  |  | [notes](01.%201D%20DP%20%28Fibonacci%20Style%29/0265.%20Paint%20House%20II/0265.%20Paint%20House%20II.md) |
| 28 | [3654. Minimum Sum After Divisible Sum Deletions](https://leetcode.com/problems/minimum-sum-after-divisible-sum-deletions/) | Medium | 6+ months | 6.1 | Todo |  |  |  | [notes](01.%201D%20DP%20%28Fibonacci%20Style%29/3654.%20Minimum%20Sum%20After%20Divisible%20Sum%20Deletions/3654.%20Minimum%20Sum%20After%20Divisible%20Sum%20Deletions.md) |

## 02. Take or Skip (House Robber)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [198. House Robber](https://leetcode.com/problems/house-robber/) | Medium | 3 months | 42.0 | ✅ Solved |  |  |  | [notes](02.%20Take%20or%20Skip%20%28House%20Robber%29/0198.%20House%20Robber/0198.%20House%20Robber.md) |
| 2 | [213. House Robber II](https://leetcode.com/problems/house-robber-ii/) | Medium | 6 months | 30.4 | ✅ Solved |  |  |  | [notes](02.%20Take%20or%20Skip%20%28House%20Robber%29/0213.%20House%20Robber%20II/0213.%20House%20Robber%20II.md) |
| 3 | [740. Delete and Earn](https://leetcode.com/problems/delete-and-earn/) | Medium | 6+ months | 6.4 | Todo |  |  |  | [notes](02.%20Take%20or%20Skip%20%28House%20Robber%29/0740.%20Delete%20and%20Earn/0740.%20Delete%20and%20Earn.md) |
| 4 | [2140. Solving Questions With Brainpower](https://leetcode.com/problems/solving-questions-with-brainpower/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](02.%20Take%20or%20Skip%20%28House%20Robber%29/2140.%20Solving%20Questions%20With%20Brainpower/2140.%20Solving%20Questions%20With%20Brainpower.md) |

## 03. 0-1 Knapsack

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [494. Target Sum](https://leetcode.com/problems/target-sum/) | Medium | 6 months | 45.8 | ✅ Solved |  |  |  | [notes](03.%200-1%20Knapsack/0494.%20Target%20Sum/0494.%20Target%20Sum.md) |
| 2 | [416. Partition Equal Subset Sum](https://leetcode.com/problems/partition-equal-subset-sum/) | Medium | 6+ months | 31.3 | ✅ Solved |  |  |  | [notes](03.%200-1%20Knapsack/0416.%20Partition%20Equal%20Subset%20Sum/0416.%20Partition%20Equal%20Subset%20Sum.md) |
| 3 | [474. Ones and Zeroes](https://leetcode.com/problems/ones-and-zeroes/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](03.%200-1%20Knapsack/0474.%20Ones%20and%20Zeroes/0474.%20Ones%20and%20Zeroes.md) |
| 4 | [1049. Last Stone Weight II](https://leetcode.com/problems/last-stone-weight-ii/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](03.%200-1%20Knapsack/1049.%20Last%20Stone%20Weight%20II/1049.%20Last%20Stone%20Weight%20II.md) |
| 5 | [2742. Painting the Walls](https://leetcode.com/problems/painting-the-walls/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](03.%200-1%20Knapsack/2742.%20Painting%20the%20Walls/2742.%20Painting%20the%20Walls.md) |
| 6 | [2915. Length of the Longest Subsequence That Sums to Target](https://leetcode.com/problems/length-of-the-longest-subsequence-that-sums-to-target/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](03.%200-1%20Knapsack/2915.%20Length%20of%20the%20Longest%20Subsequence%20That%20Sums%20to%20Target/2915.%20Length%20of%20the%20Longest%20Subsequence%20That%20Sums%20to%20Target.md) |

## 04. Unbounded Knapsack (Coin Change)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [322. Coin Change](https://leetcode.com/problems/coin-change/) | Medium | 3 months | 50.3 | ✅ Solved |  |  |  | [notes](04.%20Unbounded%20Knapsack%20%28Coin%20Change%29/0322.%20Coin%20Change/0322.%20Coin%20Change.md) |
| 2 | [279. Perfect Squares](https://leetcode.com/problems/perfect-squares/) | Medium | 6 months | 15.5 | Todo |  |  |  | [notes](04.%20Unbounded%20Knapsack%20%28Coin%20Change%29/0279.%20Perfect%20Squares/0279.%20Perfect%20Squares.md) |
| 3 | [377. Combination Sum IV](https://leetcode.com/problems/combination-sum-iv/) | Medium | 6+ months | 38.8 | Todo |  |  |  | [notes](04.%20Unbounded%20Knapsack%20%28Coin%20Change%29/0377.%20Combination%20Sum%20IV/0377.%20Combination%20Sum%20IV.md) |
| 4 | [518. Coin Change II](https://leetcode.com/problems/coin-change-ii/) | Medium | 6+ months | 15.2 | ✅ Solved |  |  |  | [notes](04.%20Unbounded%20Knapsack%20%28Coin%20Change%29/0518.%20Coin%20Change%20II/0518.%20Coin%20Change%20II.md) |
| 5 | [3592. Inverse Coin Change](https://leetcode.com/problems/inverse-coin-change/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Unbounded%20Knapsack%20%28Coin%20Change%29/3592.%20Inverse%20Coin%20Change/3592.%20Inverse%20Coin%20Change.md) |

## 05. Longest Increasing Subsequence

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [300. Longest Increasing Subsequence](https://leetcode.com/problems/longest-increasing-subsequence/) | Medium | 6 months | 39.3 | ✅ Solved |  |  |  | [notes](05.%20Longest%20Increasing%20Subsequence/0300.%20Longest%20Increasing%20Subsequence/0300.%20Longest%20Increasing%20Subsequence.md) |
| 2 | [1218. Longest Arithmetic Subsequence of Given Difference](https://leetcode.com/problems/longest-arithmetic-subsequence-of-given-difference/) | Medium | 6 months | 12.9 | Todo |  |  |  | [notes](05.%20Longest%20Increasing%20Subsequence/1218.%20Longest%20Arithmetic%20Subsequence%20of%20Given%20Difference/1218.%20Longest%20Arithmetic%20Subsequence%20of%20Given%20Difference.md) |
| 3 | [673. Number of Longest Increasing Subsequence](https://leetcode.com/problems/number-of-longest-increasing-subsequence/) | Medium | 6+ months | 37.8 | ✅ Solved |  |  |  | [notes](05.%20Longest%20Increasing%20Subsequence/0673.%20Number%20of%20Longest%20Increasing%20Subsequence/0673.%20Number%20of%20Longest%20Increasing%20Subsequence.md) |
| 4 | [354. Russian Doll Envelopes](https://leetcode.com/problems/russian-doll-envelopes/) | Hard | 6+ months | 25.7 | Todo |  |  |  | [notes](05.%20Longest%20Increasing%20Subsequence/0354.%20Russian%20Doll%20Envelopes/0354.%20Russian%20Doll%20Envelopes.md) |
| 5 | [368. Largest Divisible Subset](https://leetcode.com/problems/largest-divisible-subset/) | Medium | 6+ months | 18.7 | ✅ Solved |  |  |  | [notes](05.%20Longest%20Increasing%20Subsequence/0368.%20Largest%20Divisible%20Subset/0368.%20Largest%20Divisible%20Subset.md) |
| 6 | [1691. Maximum Height by Stacking Cuboids ](https://leetcode.com/problems/maximum-height-by-stacking-cuboids/) | Hard | 6+ months | 6.2 | Todo |  |  |  | [notes](05.%20Longest%20Increasing%20Subsequence/1691.%20Maximum%20Height%20by%20Stacking%20Cuboids%20/1691.%20Maximum%20Height%20by%20Stacking%20Cuboids%20.md) |
| 7 | [1048. Longest String Chain](https://leetcode.com/problems/longest-string-chain/) | Medium | 6+ months | 5.2 | ✅ Solved |  |  |  | [notes](05.%20Longest%20Increasing%20Subsequence/1048.%20Longest%20String%20Chain/1048.%20Longest%20String%20Chain.md) |

## 06. 2D Grid DP

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [62. Unique Paths](https://leetcode.com/problems/unique-paths/) | Medium | 6 months | 48.2 | ✅ Solved |  |  |  | [notes](06.%202D%20Grid%20DP/0062.%20Unique%20Paths/0062.%20Unique%20Paths.md) |
| 2 | [120. Triangle](https://leetcode.com/problems/triangle/) | Medium | 6 months | 24.8 | Todo |  |  |  | [notes](06.%202D%20Grid%20DP/0120.%20Triangle/0120.%20Triangle.md) |
| 3 | [63. Unique Paths II](https://leetcode.com/problems/unique-paths-ii/) | Medium | 6 months | 20.7 | Todo |  |  |  | [notes](06.%202D%20Grid%20DP/0063.%20Unique%20Paths%20II/0063.%20Unique%20Paths%20II.md) |
| 4 | [221. Maximal Square](https://leetcode.com/problems/maximal-square/) | Medium | 6+ months | 38.8 | Todo |  |  |  | [notes](06.%202D%20Grid%20DP/0221.%20Maximal%20Square/0221.%20Maximal%20Square.md) |
| 5 | [764. Largest Plus Sign](https://leetcode.com/problems/largest-plus-sign/) | Medium | 6+ months | 36.1 | Todo |  |  |  | [notes](06.%202D%20Grid%20DP/0764.%20Largest%20Plus%20Sign/0764.%20Largest%20Plus%20Sign.md) |
| 6 | [64. Minimum Path Sum](https://leetcode.com/problems/minimum-path-sum/) | Medium | 6+ months | 28.3 | Todo |  |  |  | [notes](06.%202D%20Grid%20DP/0064.%20Minimum%20Path%20Sum/0064.%20Minimum%20Path%20Sum.md) |
| 7 | [931. Minimum Falling Path Sum](https://leetcode.com/problems/minimum-falling-path-sum/) | Medium | 6+ months | 12.5 | Todo |  |  |  | [notes](06.%202D%20Grid%20DP/0931.%20Minimum%20Falling%20Path%20Sum/0931.%20Minimum%20Falling%20Path%20Sum.md) |
| 8 | [174. Dungeon Game](https://leetcode.com/problems/dungeon-game/) | Hard | 6+ months | 12.0 | Todo |  |  |  | [notes](06.%202D%20Grid%20DP/0174.%20Dungeon%20Game/0174.%20Dungeon%20Game.md) |
| 9 | [1277. Count Square Submatrices with All Ones](https://leetcode.com/problems/count-square-submatrices-with-all-ones/) | Medium | 6+ months | 10.3 | ✅ Solved |  |  |  | [notes](06.%202D%20Grid%20DP/1277.%20Count%20Square%20Submatrices%20with%20All%20Ones/1277.%20Count%20Square%20Submatrices%20with%20All%20Ones.md) |
| 10 | [1463. Cherry Pickup II](https://leetcode.com/problems/cherry-pickup-ii/) | Hard | 6+ months | 9.7 | Todo |  |  |  | [notes](06.%202D%20Grid%20DP/1463.%20Cherry%20Pickup%20II/1463.%20Cherry%20Pickup%20II.md) |
| 11 | [4003. Minimum Cost Path with Alternating Directions III](https://leetcode.com/problems/minimum-cost-path-with-alternating-directions-iii/) | Hard | 6+ months | 6.3 | Todo |  |  |  | [notes](06.%202D%20Grid%20DP/4003.%20Minimum%20Cost%20Path%20with%20Alternating%20Directions%20III/4003.%20Minimum%20Cost%20Path%20with%20Alternating%20Directions%20III.md) |
| 12 | [741. Cherry Pickup](https://leetcode.com/problems/cherry-pickup/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%202D%20Grid%20DP/0741.%20Cherry%20Pickup/0741.%20Cherry%20Pickup.md) |
| 13 | [799. Champagne Tower](https://leetcode.com/problems/champagne-tower/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%202D%20Grid%20DP/0799.%20Champagne%20Tower/0799.%20Champagne%20Tower.md) |
| 14 | [1289. Minimum Falling Path Sum II](https://leetcode.com/problems/minimum-falling-path-sum-ii/) | Hard | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](06.%202D%20Grid%20DP/1289.%20Minimum%20Falling%20Path%20Sum%20II/1289.%20Minimum%20Falling%20Path%20Sum%20II.md) |
| 15 | [1594. Maximum Non Negative Product in a Matrix](https://leetcode.com/problems/maximum-non-negative-product-in-a-matrix/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%202D%20Grid%20DP/1594.%20Maximum%20Non%20Negative%20Product%20in%20a%20Matrix/1594.%20Maximum%20Non%20Negative%20Product%20in%20a%20Matrix.md) |

## 07. String DP (LCS, Edit Distance)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [115. Distinct Subsequences](https://leetcode.com/problems/distinct-subsequences/) | Hard | 3 months | 31.4 | ✅ Solved |  |  |  | [notes](07.%20String%20DP%20%28LCS%2C%20Edit%20Distance%29/0115.%20Distinct%20Subsequences/0115.%20Distinct%20Subsequences.md) |
| 2 | [10. Regular Expression Matching](https://leetcode.com/problems/regular-expression-matching/) | Hard | 6 months | 47.8 | Todo |  |  |  | [notes](07.%20String%20DP%20%28LCS%2C%20Edit%20Distance%29/0010.%20Regular%20Expression%20Matching/0010.%20Regular%20Expression%20Matching.md) |
| 3 | [44. Wildcard Matching](https://leetcode.com/problems/wildcard-matching/) | Hard | 6 months | 40.6 | ✅ Solved |  |  |  | [notes](07.%20String%20DP%20%28LCS%2C%20Edit%20Distance%29/0044.%20Wildcard%20Matching/0044.%20Wildcard%20Matching.md) |
| 4 | [72. Edit Distance](https://leetcode.com/problems/edit-distance/) | Medium | 6 months | 32.1 | 🟡 Attempted |  |  |  | [notes](07.%20String%20DP%20%28LCS%2C%20Edit%20Distance%29/0072.%20Edit%20Distance/0072.%20Edit%20Distance.md) |
| 5 | [1143. Longest Common Subsequence](https://leetcode.com/problems/longest-common-subsequence/) | Medium | 6 months | 24.3 | ✅ Solved |  |  |  | [notes](07.%20String%20DP%20%28LCS%2C%20Edit%20Distance%29/1143.%20Longest%20Common%20Subsequence/1143.%20Longest%20Common%20Subsequence.md) |
| 6 | [97. Interleaving String](https://leetcode.com/problems/interleaving-string/) | Medium | 6+ months | 12.0 | Todo |  |  |  | [notes](07.%20String%20DP%20%28LCS%2C%20Edit%20Distance%29/0097.%20Interleaving%20String/0097.%20Interleaving%20String.md) |
| 7 | [87. Scramble String](https://leetcode.com/problems/scramble-string/) | Hard | 6+ months | 10.1 | Todo |  |  |  | [notes](07.%20String%20DP%20%28LCS%2C%20Edit%20Distance%29/0087.%20Scramble%20String/0087.%20Scramble%20String.md) |
| 8 | [2060. Check if an Original String Exists Given Two Encoded Strings](https://leetcode.com/problems/check-if-an-original-string-exists-given-two-encoded-strings/) | Hard | 6+ months | 8.2 | Todo |  |  |  | [notes](07.%20String%20DP%20%28LCS%2C%20Edit%20Distance%29/2060.%20Check%20if%20an%20Original%20String%20Exists%20Given%20Two%20Encoded%20Strings/2060.%20Check%20if%20an%20Original%20String%20Exists%20Given%20Two%20Encoded%20Strings.md) |
| 9 | [1092. Shortest Common Supersequence ](https://leetcode.com/problems/shortest-common-supersequence/) | Hard | 6+ months | 6.5 | ✅ Solved |  |  |  | [notes](07.%20String%20DP%20%28LCS%2C%20Edit%20Distance%29/1092.%20Shortest%20Common%20Supersequence%20/1092.%20Shortest%20Common%20Supersequence%20.md) |
| 10 | [712. Minimum ASCII Delete Sum for Two Strings](https://leetcode.com/problems/minimum-ascii-delete-sum-for-two-strings/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](07.%20String%20DP%20%28LCS%2C%20Edit%20Distance%29/0712.%20Minimum%20ASCII%20Delete%20Sum%20for%20Two%20Strings/0712.%20Minimum%20ASCII%20Delete%20Sum%20for%20Two%20Strings.md) |
| 11 | [1458. Max Dot Product of Two Subsequences](https://leetcode.com/problems/max-dot-product-of-two-subsequences/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](07.%20String%20DP%20%28LCS%2C%20Edit%20Distance%29/1458.%20Max%20Dot%20Product%20of%20Two%20Subsequences/1458.%20Max%20Dot%20Product%20of%20Two%20Subsequences.md) |
| 12 | [583. Delete Operation for Two Strings](https://leetcode.com/problems/delete-operation-for-two-strings/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](07.%20String%20DP%20%28LCS%2C%20Edit%20Distance%29/0583.%20Delete%20Operation%20for%20Two%20Strings/0583.%20Delete%20Operation%20for%20Two%20Strings.md) |

## 08. Palindrome DP

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [2472. Maximum Number of Non-overlapping Palindrome Substrings](https://leetcode.com/problems/maximum-number-of-non-overlapping-palindrome-substrings/) | Hard | 6 months | 11.9 | Todo |  |  |  | [notes](08.%20Palindrome%20DP/2472.%20Maximum%20Number%20of%20Non-overlapping%20Palindrome%20Substrings/2472.%20Maximum%20Number%20of%20Non-overlapping%20Palindrome%20Substrings.md) |
| 2 | [1216. Valid Palindrome III](https://leetcode.com/problems/valid-palindrome-iii/) 🔒 | Hard | 6+ months | 57.5 | Todo |  |  |  | [notes](08.%20Palindrome%20DP/1216.%20Valid%20Palindrome%20III/1216.%20Valid%20Palindrome%20III.md) |
| 3 | [516. Longest Palindromic Subsequence](https://leetcode.com/problems/longest-palindromic-subsequence/) | Medium | 6+ months | 20.8 | ✅ Solved |  |  |  | [notes](08.%20Palindrome%20DP/0516.%20Longest%20Palindromic%20Subsequence/0516.%20Longest%20Palindromic%20Subsequence.md) |
| 4 | [132. Palindrome Partitioning II](https://leetcode.com/problems/palindrome-partitioning-ii/) | Hard | 6+ months | 17.5 | ✅ Solved |  |  |  | [notes](08.%20Palindrome%20DP/0132.%20Palindrome%20Partitioning%20II/0132.%20Palindrome%20Partitioning%20II.md) |

## 09. Interval DP

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [312. Burst Balloons](https://leetcode.com/problems/burst-balloons/) | Hard | 6 months | 17.8 | ✅ Solved |  |  |  | [notes](09.%20Interval%20DP/0312.%20Burst%20Balloons/0312.%20Burst%20Balloons.md) |
| 2 | [375. Guess Number Higher or Lower II](https://leetcode.com/problems/guess-number-higher-or-lower-ii/) | Medium | 6 months | 9.7 | Todo |  |  |  | [notes](09.%20Interval%20DP/0375.%20Guess%20Number%20Higher%20or%20Lower%20II/0375.%20Guess%20Number%20Higher%20or%20Lower%20II.md) |
| 3 | [486. Predict the Winner](https://leetcode.com/problems/predict-the-winner/) | Medium | 6 months | 8.9 | Todo |  |  |  | [notes](09.%20Interval%20DP/0486.%20Predict%20the%20Winner/0486.%20Predict%20the%20Winner.md) |
| 4 | [1039. Minimum Score Triangulation of Polygon](https://leetcode.com/problems/minimum-score-triangulation-of-polygon/) | Medium | 6+ months | 10.3 | Todo |  |  |  | [notes](09.%20Interval%20DP/1039.%20Minimum%20Score%20Triangulation%20of%20Polygon/1039.%20Minimum%20Score%20Triangulation%20of%20Polygon.md) |
| 5 | [546. Remove Boxes](https://leetcode.com/problems/remove-boxes/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](09.%20Interval%20DP/0546.%20Remove%20Boxes/0546.%20Remove%20Boxes.md) |
| 6 | [664. Strange Printer](https://leetcode.com/problems/strange-printer/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](09.%20Interval%20DP/0664.%20Strange%20Printer/0664.%20Strange%20Printer.md) |
| 7 | [1000. Minimum Cost to Merge Stones](https://leetcode.com/problems/minimum-cost-to-merge-stones/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](09.%20Interval%20DP/1000.%20Minimum%20Cost%20to%20Merge%20Stones/1000.%20Minimum%20Cost%20to%20Merge%20Stones.md) |
| 8 | [1547. Minimum Cost to Cut a Stick](https://leetcode.com/problems/minimum-cost-to-cut-a-stick/) | Hard | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](09.%20Interval%20DP/1547.%20Minimum%20Cost%20to%20Cut%20a%20Stick/1547.%20Minimum%20Cost%20to%20Cut%20a%20Stick.md) |
| 9 | [2019. The Score of Students Solving Math Expression](https://leetcode.com/problems/the-score-of-students-solving-math-expression/) | Hard | 6+ months | 6.8 | Todo |  |  |  | [notes](09.%20Interval%20DP/2019.%20The%20Score%20of%20Students%20Solving%20Math%20Expression/2019.%20The%20Score%20of%20Students%20Solving%20Math%20Expression.md) |

## 10. DP on Trees

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [968. Binary Tree Cameras](https://leetcode.com/problems/binary-tree-cameras/) | Hard | 6+ months | 39.9 | Todo |  |  |  | [notes](10.%20DP%20on%20Trees/0968.%20Binary%20Tree%20Cameras/0968.%20Binary%20Tree%20Cameras.md) |
| 2 | [1373. Maximum Sum BST in Binary Tree](https://leetcode.com/problems/maximum-sum-bst-in-binary-tree/) | Hard | 6+ months | 10.6 | Todo |  |  |  | [notes](10.%20DP%20on%20Trees/1373.%20Maximum%20Sum%20BST%20in%20Binary%20Tree/1373.%20Maximum%20Sum%20BST%20in%20Binary%20Tree.md) |
| 3 | [333. Largest BST Subtree](https://leetcode.com/problems/largest-bst-subtree/) 🔒 | Medium | 6+ months | 5.7 | Todo |  |  |  | [notes](10.%20DP%20on%20Trees/0333.%20Largest%20BST%20Subtree/0333.%20Largest%20BST%20Subtree.md) |
| 4 | [337. House Robber III](https://leetcode.com/problems/house-robber-iii/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](10.%20DP%20on%20Trees/0337.%20House%20Robber%20III/0337.%20House%20Robber%20III.md) |
| 5 | [834. Sum of Distances in Tree](https://leetcode.com/problems/sum-of-distances-in-tree/) | Hard | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](10.%20DP%20on%20Trees/0834.%20Sum%20of%20Distances%20in%20Tree/0834.%20Sum%20of%20Distances%20in%20Tree.md) |
| 6 | [3562. Maximum Profit from Trading Stocks with Discounts](https://leetcode.com/problems/maximum-profit-from-trading-stocks-with-discounts/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](10.%20DP%20on%20Trees/3562.%20Maximum%20Profit%20from%20Trading%20Stocks%20with%20Discounts/3562.%20Maximum%20Profit%20from%20Trading%20Stocks%20with%20Discounts.md) |

## 11. Bitmask DP

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [847. Shortest Path Visiting All Nodes](https://leetcode.com/problems/shortest-path-visiting-all-nodes/) | Hard | 6+ months | 7.4 | Todo |  |  |  | [notes](11.%20Bitmask%20DP/0847.%20Shortest%20Path%20Visiting%20All%20Nodes/0847.%20Shortest%20Path%20Visiting%20All%20Nodes.md) |
| 2 | [691. Stickers to Spell Word](https://leetcode.com/problems/stickers-to-spell-word/) | Hard | 6+ months | 6.4 | Todo |  |  |  | [notes](11.%20Bitmask%20DP/0691.%20Stickers%20to%20Spell%20Word/0691.%20Stickers%20to%20Spell%20Word.md) |
| 3 | [464. Can I Win](https://leetcode.com/problems/can-i-win/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](11.%20Bitmask%20DP/0464.%20Can%20I%20Win/0464.%20Can%20I%20Win.md) |
| 4 | [1931. Painting a Grid With Three Different Colors](https://leetcode.com/problems/painting-a-grid-with-three-different-colors/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](11.%20Bitmask%20DP/1931.%20Painting%20a%20Grid%20With%20Three%20Different%20Colors/1931.%20Painting%20a%20Grid%20With%20Three%20Different%20Colors.md) |
| 5 | [3533. Concatenated Divisibility](https://leetcode.com/problems/concatenated-divisibility/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](11.%20Bitmask%20DP/3533.%20Concatenated%20Divisibility/3533.%20Concatenated%20Divisibility.md) |
| 6 | [1947. Maximum Compatibility Score Sum](https://leetcode.com/problems/maximum-compatibility-score-sum/) | Medium | 6+ months | 36.1 | Todo |  |  |  | [notes](11.%20Bitmask%20DP/1947.%20Maximum%20Compatibility%20Score%20Sum/1947.%20Maximum%20Compatibility%20Score%20Sum.md) |

## 12. State Machine DP (Stocks)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [123. Best Time to Buy and Sell Stock III](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-iii/) | Hard | 6+ months | 39.0 | ✅ Solved |  |  |  | [notes](12.%20State%20Machine%20DP%20%28Stocks%29/0123.%20Best%20Time%20to%20Buy%20and%20Sell%20Stock%20III/0123.%20Best%20Time%20to%20Buy%20and%20Sell%20Stock%20III.md) |
| 2 | [1653. Minimum Deletions to Make String Balanced](https://leetcode.com/problems/minimum-deletions-to-make-string-balanced/) | Medium | 6+ months | 15.1 | Todo |  |  |  | [notes](12.%20State%20Machine%20DP%20%28Stocks%29/1653.%20Minimum%20Deletions%20to%20Make%20String%20Balanced/1653.%20Minimum%20Deletions%20to%20Make%20String%20Balanced.md) |
| 3 | [1262. Greatest Sum Divisible by Three](https://leetcode.com/problems/greatest-sum-divisible-by-three/) | Medium | 6+ months | 11.4 | Todo |  |  |  | [notes](12.%20State%20Machine%20DP%20%28Stocks%29/1262.%20Greatest%20Sum%20Divisible%20by%20Three/1262.%20Greatest%20Sum%20Divisible%20by%20Three.md) |
| 4 | [3640. Trionic Array II](https://leetcode.com/problems/trionic-array-ii/) | Hard | 6+ months | 9.4 | Todo |  |  |  | [notes](12.%20State%20Machine%20DP%20%28Stocks%29/3640.%20Trionic%20Array%20II/3640.%20Trionic%20Array%20II.md) |
| 5 | [3573. Best Time to Buy and Sell Stock V](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-v/) | Medium | 6+ months | 6.1 | Todo |  |  |  | [notes](12.%20State%20Machine%20DP%20%28Stocks%29/3573.%20Best%20Time%20to%20Buy%20and%20Sell%20Stock%20V/3573.%20Best%20Time%20to%20Buy%20and%20Sell%20Stock%20V.md) |
| 6 | [926. Flip String to Monotone Increasing](https://leetcode.com/problems/flip-string-to-monotone-increasing/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](12.%20State%20Machine%20DP%20%28Stocks%29/0926.%20Flip%20String%20to%20Monotone%20Increasing/0926.%20Flip%20String%20to%20Monotone%20Increasing.md) |
| 7 | [1911. Maximum Alternating Subsequence Sum](https://leetcode.com/problems/maximum-alternating-subsequence-sum/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](12.%20State%20Machine%20DP%20%28Stocks%29/1911.%20Maximum%20Alternating%20Subsequence%20Sum/1911.%20Maximum%20Alternating%20Subsequence%20Sum.md) |
| 8 | [3068. Find the Maximum Sum of Node Values](https://leetcode.com/problems/find-the-maximum-sum-of-node-values/) | Hard | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](12.%20State%20Machine%20DP%20%28Stocks%29/3068.%20Find%20the%20Maximum%20Sum%20of%20Node%20Values/3068.%20Find%20the%20Maximum%20Sum%20of%20Node%20Values.md) |
| 9 | [714. Best Time to Buy and Sell Stock with Transaction Fee](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-with-transaction-fee/) | Medium | 6+ months | 36.9 | ✅ Solved |  |  |  | [notes](12.%20State%20Machine%20DP%20%28Stocks%29/0714.%20Best%20Time%20to%20Buy%20and%20Sell%20Stock%20with%20Transaction%20Fee/0714.%20Best%20Time%20to%20Buy%20and%20Sell%20Stock%20with%20Transaction%20Fee.md) |
| 10 | [801. Minimum Swaps To Make Sequences Increasing](https://leetcode.com/problems/minimum-swaps-to-make-sequences-increasing/) | Hard | 6+ months | 36.1 | Todo |  |  |  | [notes](12.%20State%20Machine%20DP%20%28Stocks%29/0801.%20Minimum%20Swaps%20To%20Make%20Sequences%20Increasing/0801.%20Minimum%20Swaps%20To%20Make%20Sequences%20Increasing.md) |
| 11 | [188. Best Time to Buy and Sell Stock IV](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-iv/) | Hard | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](12.%20State%20Machine%20DP%20%28Stocks%29/0188.%20Best%20Time%20to%20Buy%20and%20Sell%20Stock%20IV/0188.%20Best%20Time%20to%20Buy%20and%20Sell%20Stock%20IV.md) |
| 12 | [1186. Maximum Subarray Sum with One Deletion](https://leetcode.com/problems/maximum-subarray-sum-with-one-deletion/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](12.%20State%20Machine%20DP%20%28Stocks%29/1186.%20Maximum%20Subarray%20Sum%20with%20One%20Deletion/1186.%20Maximum%20Subarray%20Sum%20with%20One%20Deletion.md) |

## 13. Digit DP

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [233. Number of Digit One](https://leetcode.com/problems/number-of-digit-one/) | Hard | 6 months | 14.1 | Todo |  |  |  | [notes](13.%20Digit%20DP/0233.%20Number%20of%20Digit%20One/0233.%20Number%20of%20Digit%20One.md) |
| 2 | [2999. Count the Number of Powerful Integers](https://leetcode.com/problems/count-the-number-of-powerful-integers/) | Hard | 6+ months | 6.0 | Todo |  |  |  | [notes](13.%20Digit%20DP/2999.%20Count%20the%20Number%20of%20Powerful%20Integers/2999.%20Count%20the%20Number%20of%20Powerful%20Integers.md) |
| 3 | [3490. Count Beautiful Numbers](https://leetcode.com/problems/count-beautiful-numbers/) | Hard | 6+ months | 5.9 | Todo |  |  |  | [notes](13.%20Digit%20DP/3490.%20Count%20Beautiful%20Numbers/3490.%20Count%20Beautiful%20Numbers.md) |

## 14. Counting DP

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [96. Unique Binary Search Trees](https://leetcode.com/problems/unique-binary-search-trees/) | Medium | 3 months | 33.8 | Todo |  |  |  | [notes](14.%20Counting%20DP/0096.%20Unique%20Binary%20Search%20Trees/0096.%20Unique%20Binary%20Search%20Trees.md) |
| 2 | [3336. Find the Number of Subsequences With Equal GCD](https://leetcode.com/problems/find-the-number-of-subsequences-with-equal-gcd/) | Hard | 6 months | 16.6 | Todo |  |  |  | [notes](14.%20Counting%20DP/3336.%20Find%20the%20Number%20of%20Subsequences%20With%20Equal%20GCD/3336.%20Find%20the%20Number%20of%20Subsequences%20With%20Equal%20GCD.md) |
| 3 | [3699. Number of ZigZag Arrays I](https://leetcode.com/problems/number-of-zigzag-arrays-i/) | Hard | 6 months | 5.0 | Todo |  |  |  | [notes](14.%20Counting%20DP/3699.%20Number%20of%20ZigZag%20Arrays%20I/3699.%20Number%20of%20ZigZag%20Arrays%20I.md) |
| 4 | [940. Distinct Subsequences II](https://leetcode.com/problems/distinct-subsequences-ii/) | Hard | 6+ months | 11.1 | Todo |  |  |  | [notes](14.%20Counting%20DP/0940.%20Distinct%20Subsequences%20II/0940.%20Distinct%20Subsequences%20II.md) |
| 5 | [935. Knight Dialer](https://leetcode.com/problems/knight-dialer/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](14.%20Counting%20DP/0935.%20Knight%20Dialer/0935.%20Knight%20Dialer.md) |
| 6 | [1155. Number of Dice Rolls With Target Sum](https://leetcode.com/problems/number-of-dice-rolls-with-target-sum/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](14.%20Counting%20DP/1155.%20Number%20of%20Dice%20Rolls%20With%20Target%20Sum/1155.%20Number%20of%20Dice%20Rolls%20With%20Target%20Sum.md) |
| 7 | [1411. Number of Ways to Paint N × 3 Grid](https://leetcode.com/problems/number-of-ways-to-paint-n-3-grid/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](14.%20Counting%20DP/1411.%20Number%20of%20Ways%20to%20Paint%20N%20%C3%97%203%20Grid/1411.%20Number%20of%20Ways%20to%20Paint%20N%20%C3%97%203%20Grid.md) |
| 8 | [1621. Number of Sets of K Non-Overlapping Line Segments](https://leetcode.com/problems/number-of-sets-of-k-non-overlapping-line-segments/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](14.%20Counting%20DP/1621.%20Number%20of%20Sets%20of%20K%20Non-Overlapping%20Line%20Segments/1621.%20Number%20of%20Sets%20of%20K%20Non-Overlapping%20Line%20Segments.md) |
| 9 | [1639. Number of Ways to Form a Target String Given a Dictionary](https://leetcode.com/problems/number-of-ways-to-form-a-target-string-given-a-dictionary/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](14.%20Counting%20DP/1639.%20Number%20of%20Ways%20to%20Form%20a%20Target%20String%20Given%20a%20Dictionary/1639.%20Number%20of%20Ways%20to%20Form%20a%20Target%20String%20Given%20a%20Dictionary.md) |
| 10 | [3129. Find All Possible Stable Binary Arrays I](https://leetcode.com/problems/find-all-possible-stable-binary-arrays-i/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](14.%20Counting%20DP/3129.%20Find%20All%20Possible%20Stable%20Binary%20Arrays%20I/3129.%20Find%20All%20Possible%20Stable%20Binary%20Arrays%20I.md) |
| 11 | [3335. Total Characters in String After Transformations I](https://leetcode.com/problems/total-characters-in-string-after-transformations-i/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](14.%20Counting%20DP/3335.%20Total%20Characters%20in%20String%20After%20Transformations%20I/3335.%20Total%20Characters%20in%20String%20After%20Transformations%20I.md) |
| 12 | [3343. Count Number of Balanced Permutations](https://leetcode.com/problems/count-number-of-balanced-permutations/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](14.%20Counting%20DP/3343.%20Count%20Number%20of%20Balanced%20Permutations/3343.%20Count%20Number%20of%20Balanced%20Permutations.md) |
| 13 | [3539. Find Sum of Array Product of Magical Sequences](https://leetcode.com/problems/find-sum-of-array-product-of-magical-sequences/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](14.%20Counting%20DP/3539.%20Find%20Sum%20of%20Array%20Product%20of%20Magical%20Sequences/3539.%20Find%20Sum%20of%20Array%20Product%20of%20Magical%20Sequences.md) |
| 14 | [920. Number of Music Playlists](https://leetcode.com/problems/number-of-music-playlists/) | Hard | 6+ months | 7.6 | Todo |  |  |  | [notes](14.%20Counting%20DP/0920.%20Number%20of%20Music%20Playlists/0920.%20Number%20of%20Music%20Playlists.md) |
| 15 | [1395. Count Number of Teams](https://leetcode.com/problems/count-number-of-teams/) | Medium | 6+ months | 5.8 | Todo |  |  |  | [notes](14.%20Counting%20DP/1395.%20Count%20Number%20of%20Teams/1395.%20Count%20Number%20of%20Teams.md) |

## 15. Memoized DFS

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [1140. Stone Game II](https://leetcode.com/problems/stone-game-ii/) | Medium | 6 months | 7.2 | Todo |  |  |  | [notes](15.%20Memoized%20DFS/1140.%20Stone%20Game%20II/1140.%20Stone%20Game%20II.md) |
| 2 | [329. Longest Increasing Path in a Matrix](https://leetcode.com/problems/longest-increasing-path-in-a-matrix/) | Hard | 6+ months | 40.1 | Todo |  |  |  | [notes](15.%20Memoized%20DFS/0329.%20Longest%20Increasing%20Path%20in%20a%20Matrix/0329.%20Longest%20Increasing%20Path%20in%20a%20Matrix.md) |
| 3 | [1900. The Earliest and Latest Rounds Where Players Compete](https://leetcode.com/problems/the-earliest-and-latest-rounds-where-players-compete/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](15.%20Memoized%20DFS/1900.%20The%20Earliest%20and%20Latest%20Rounds%20Where%20Players%20Compete/1900.%20The%20Earliest%20and%20Latest%20Rounds%20Where%20Players%20Compete.md) |
