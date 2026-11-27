# 01. Facebook (Meta)

[Back to Company Wise Questions](../README.md) · [Back to DSA Notes](../../README.md)

Source: LeetCode company lists for Meta (Premium), pulled on 2026-11-27. 1379 unique problems: 437 Easy, 737 Medium, 205 Hard. Each problem appears exactly once.

Window sizes: last 30 days = 9, last 3 months = 113, last 6 months = 318, more than 6 months = 1231.

Chapters go from basic to advanced. Each problem sits in the sub-pattern of its standard optimal solution. Folder layout: `NN. Chapter/NN. Sub-pattern/NNNN. Problem/NNNN. Problem.md`.

## Chapters

| # | Chapter | Sub-patterns | Questions | Easy | Medium | Hard | Last 3 Months | Solved | Most Asked |
|:---:|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---|
| 01 | [Arrays & Hashing](#01-arrays--hashing) | 9 | 117 | 75 | 41 | 1 | 14 | 49 | 1. Two Sum, 121. Best Time to Buy and Sell Stock, 31. Next Permutation |
| 02 | [Strings](#02-strings) | 7 | 65 | 41 | 17 | 7 | 9 | 19 | 680. Valid Palindrome II, 125. Valid Palindrome, 647. Palindromic Substrings |
| 03 | [Two Pointers](#03-two-pointers) | 6 | 54 | 23 | 30 | 1 | 11 | 31 | 408. Valid Word Abbreviation, 88. Merge Sorted Array, 15. 3Sum |
| 04 | [Sliding Window](#04-sliding-window) | 5 | 57 | 9 | 41 | 7 | 8 | 19 | 1004. Max Consecutive Ones III, 76. Minimum Window Substring, 3. Longest Substring Without Repeating Characters |
| 05 | [Prefix Sum](#05-prefix-sum) | 5 | 49 | 11 | 34 | 4 | 3 | 14 | 560. Subarray Sum Equals K, 528. Random Pick with Weight, 523. Continuous Subarray Sum |
| 06 | [Sorting](#06-sorting) | 4 | 32 | 15 | 12 | 5 | 0 | 11 | 791. Custom Sort String, 274. H-Index, 451. Sort Characters By Frequency |
| 07 | [Matrix & Simulation](#07-matrix--simulation) | 5 | 42 | 22 | 19 | 1 | 2 | 8 | 498. Diagonal Traverse, 73. Set Matrix Zeroes, 54. Spiral Matrix |
| 08 | [Math & Number Theory](#08-math--number-theory) | 9 | 117 | 55 | 46 | 16 | 7 | 7 | 50. Pow(x, n), 415. Add Strings, 398. Random Pick Index |
| 09 | [Bit Manipulation](#09-bit-manipulation) | 4 | 33 | 19 | 14 | 0 | 3 | 4 | 268. Missing Number, 136. Single Number, 477. Total Hamming Distance |
| 10 | [Stack & Queue](#10-stack--queue) | 7 | 67 | 14 | 40 | 13 | 10 | 22 | 1249. Minimum Remove to Make Valid Parentheses, 227. Basic Calculator II, 1762. Buildings With an Ocean View |
| 11 | [Binary Search](#11-binary-search) | 7 | 54 | 14 | 32 | 8 | 7 | 17 | 162. Find Peak Element, 34. Find First and Last Position of Element in Sorted Array, 1539. Kth Missing Positive Number |
| 12 | [Linked List](#12-linked-list) | 7 | 36 | 9 | 26 | 1 | 4 | 21 | 138. Copy List with Random Pointer, 2. Add Two Numbers, 19. Remove Nth Node From End of List |
| 13 | [Recursion & Backtracking](#13-recursion--backtracking) | 8 | 45 | 1 | 31 | 13 | 4 | 14 | 339. Nested List Weight Sum, 489. Robot Room Cleaner, 78. Subsets |
| 14 | [Trees](#14-trees) | 12 | 103 | 30 | 68 | 5 | 5 | 46 | 314. Binary Tree Vertical Order Traversal, 543. Diameter of Binary Tree, 1650. Lowest Common Ancestor of a Binary Tree III |
| 15 | [Tries](#15-tries) | 4 | 12 | 0 | 8 | 4 | 0 | 0 | 208. Implement Trie (Prefix Tree), 211. Design Add and Search Words Data Structure, 745. Prefix and Suffix Search |
| 16 | [Heap & Priority Queue](#16-heap--priority-queue) | 6 | 35 | 5 | 19 | 11 | 2 | 5 | 215. Kth Largest Element in an Array, 347. Top K Frequent Elements, 973. K Closest Points to Origin |
| 17 | [Intervals](#17-intervals) | 5 | 15 | 1 | 10 | 4 | 1 | 2 | 56. Merge Intervals, 986. Interval List Intersections, 253. Meeting Rooms II |
| 18 | [Greedy](#18-greedy) | 6 | 76 | 20 | 47 | 9 | 6 | 9 | 670. Maximum Swap, 334. Increasing Triplet Subsequence, 122. Best Time to Buy and Sell Stock II |
| 19 | [Graphs](#19-graphs) | 10 | 62 | 4 | 45 | 13 | 2 | 25 | 1091. Shortest Path in Binary Matrix, 827. Making A Large Island, 133. Clone Graph |
| 20 | [Advanced Graphs](#20-advanced-graphs) | 7 | 31 | 0 | 20 | 11 | 0 | 12 | 721. Accounts Merge, 778. Swim in Rising Water, 1928. Minimum Cost to Reach Destination in Time |
| 21 | [Dynamic Programming](#21-dynamic-programming) | 15 | 135 | 6 | 74 | 55 | 7 | 35 | 1216. Valid Palindrome III, 139. Word Break, 322. Coin Change |
| 22 | [Advanced Data Structures](#22-advanced-data-structures) | 3 | 7 | 0 | 3 | 4 | 0 | 0 | 3636. Threshold Majority Queries, 2817. Minimum Absolute Difference Between Elements With Constraint, 1488. Avoid Flood in The City |
| 23 | [Design](#23-design) | 7 | 45 | 13 | 25 | 7 | 1 | 5 | 146. LRU Cache, 1570. Dot Product of Two Sparse Vectors, 346. Moving Average from Data Stream |
| 24 | [SQL & Database](#24-sql--database) | 7 | 85 | 48 | 32 | 5 | 6 | 40 | 1757. Recyclable and Low Fat Products, 602. Friend Requests II: Who Has the Most Friends, 1661. Average Time of Process per Machine |
| 25 | [Shell & Concurrency](#25-shell--concurrency) | 2 | 5 | 2 | 3 | 0 | 1 | 0 | 1242. Web Crawler Multithreaded, 195. Tenth Line, 192. Word Frequency |

**Columns**

- **Last Asked**: most recent LeetCode window that lists the problem for Meta (30 days, 3 months, 6 months or 6+ months).
- **Frequency**: LeetCode frequency score (0-100) in the Meta "All" list.
- **Status**: your LeetCode status on the day this file was generated. 🔒 after a title means LeetCode Premium.
- **Logic / Key Idea, Time, Space**: fill these in as you solve. A rebuild keeps what you typed.
- **Notes**: link to the problem's notes file.

Inside each sub-pattern, rows are sorted by most recent window, then by frequency (highest first).


## 01. Arrays & Hashing

117 problems: 75 Easy, 41 Medium, 1 Hard. [Open chapter README](01.%20Arrays%20%26%20Hashing/README.md) · [Back to top](#chapters)

### 01.01. Array Traversal & Basics

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [3105. Longest Strictly Increasing or Strictly Decreasing Subarray](https://leetcode.com/problems/longest-strictly-increasing-or-strictly-decreasing-subarray/) | Easy | 30 days | 17.0 | ✅ Solved |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/01.%20Array%20Traversal%20%26%20Basics/3105.%20Longest%20Strictly%20Increasing%20or%20Strictly%20Decreasing%20Subarray/3105.%20Longest%20Strictly%20Increasing%20or%20Strictly%20Decreasing%20Subarray.md) |
| 2 | [121. Best Time to Buy and Sell Stock](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/) | Easy | 3 months | 84.6 | ✅ Solved |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/01.%20Array%20Traversal%20%26%20Basics/0121.%20Best%20Time%20to%20Buy%20and%20Sell%20Stock/0121.%20Best%20Time%20to%20Buy%20and%20Sell%20Stock.md) |
| 3 | [1752. Check if Array Is Sorted and Rotated](https://leetcode.com/problems/check-if-array-is-sorted-and-rotated/) | Easy | 3 months | 32.1 | ✅ Solved |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/01.%20Array%20Traversal%20%26%20Basics/1752.%20Check%20if%20Array%20Is%20Sorted%20and%20Rotated/1752.%20Check%20if%20Array%20Is%20Sorted%20and%20Rotated.md) |
| 4 | [1929. Concatenation of Array](https://leetcode.com/problems/concatenation-of-array/) | Easy | 6 months | 33.8 | ✅ Solved |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/01.%20Array%20Traversal%20%26%20Basics/1929.%20Concatenation%20of%20Array/1929.%20Concatenation%20of%20Array.md) |
| 5 | [485. Max Consecutive Ones](https://leetcode.com/problems/max-consecutive-ones/) | Easy | 6 months | 31.2 | ✅ Solved |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/01.%20Array%20Traversal%20%26%20Basics/0485.%20Max%20Consecutive%20Ones/0485.%20Max%20Consecutive%20Ones.md) |
| 6 | [1431. Kids With the Greatest Number of Candies](https://leetcode.com/problems/kids-with-the-greatest-number-of-candies/) | Easy | 6 months | 19.8 | ✅ Solved |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/01.%20Array%20Traversal%20%26%20Basics/1431.%20Kids%20With%20the%20Greatest%20Number%20of%20Candies/1431.%20Kids%20With%20the%20Greatest%20Number%20of%20Candies.md) |
| 7 | [1470. Shuffle the Array](https://leetcode.com/problems/shuffle-the-array/) | Easy | 6 months | 13.5 | ✅ Solved |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/01.%20Array%20Traversal%20%26%20Basics/1470.%20Shuffle%20the%20Array/1470.%20Shuffle%20the%20Array.md) |
| 8 | [163. Missing Ranges](https://leetcode.com/problems/missing-ranges/) 🔒 | Easy | 6+ months | 43.4 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/01.%20Array%20Traversal%20%26%20Basics/0163.%20Missing%20Ranges/0163.%20Missing%20Ranges.md) |
| 9 | [896. Monotonic Array](https://leetcode.com/problems/monotonic-array/) | Easy | 6+ months | 42.0 | ✅ Solved |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/01.%20Array%20Traversal%20%26%20Basics/0896.%20Monotonic%20Array/0896.%20Monotonic%20Array.md) |
| 10 | [674. Longest Continuous Increasing Subsequence](https://leetcode.com/problems/longest-continuous-increasing-subsequence/) | Easy | 6+ months | 38.5 | ✅ Solved |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/01.%20Array%20Traversal%20%26%20Basics/0674.%20Longest%20Continuous%20Increasing%20Subsequence/0674.%20Longest%20Continuous%20Increasing%20Subsequence.md) |
| 11 | [2210. Count Hills and Valleys in an Array](https://leetcode.com/problems/count-hills-and-valleys-in-an-array/) | Easy | 6+ months | 38.4 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/01.%20Array%20Traversal%20%26%20Basics/2210.%20Count%20Hills%20and%20Valleys%20in%20an%20Array/2210.%20Count%20Hills%20and%20Valleys%20in%20an%20Array.md) |
| 12 | [1287. Element Appearing More Than 25% In Sorted Array](https://leetcode.com/problems/element-appearing-more-than-25-in-sorted-array/) | Easy | 6+ months | 17.2 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/01.%20Array%20Traversal%20%26%20Basics/1287.%20Element%20Appearing%20More%20Than%2025%25%20In%20Sorted%20Array/1287.%20Element%20Appearing%20More%20Than%2025%25%20In%20Sorted%20Array.md) |
| 13 | [2016. Maximum Difference Between Increasing Elements](https://leetcode.com/problems/maximum-difference-between-increasing-elements/) | Easy | 6+ months | 12.4 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/01.%20Array%20Traversal%20%26%20Basics/2016.%20Maximum%20Difference%20Between%20Increasing%20Elements/2016.%20Maximum%20Difference%20Between%20Increasing%20Elements.md) |
| 14 | [1464. Maximum Product of Two Elements in an Array](https://leetcode.com/problems/maximum-product-of-two-elements-in-an-array/) | Easy | 6+ months | 9.4 | ✅ Solved |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/01.%20Array%20Traversal%20%26%20Basics/1464.%20Maximum%20Product%20of%20Two%20Elements%20in%20an%20Array/1464.%20Maximum%20Product%20of%20Two%20Elements%20in%20an%20Array.md) |
| 15 | [941. Valid Mountain Array](https://leetcode.com/problems/valid-mountain-array/) | Easy | 6+ months | 8.5 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/01.%20Array%20Traversal%20%26%20Basics/0941.%20Valid%20Mountain%20Array/0941.%20Valid%20Mountain%20Array.md) |
| 16 | [228. Summary Ranges](https://leetcode.com/problems/summary-ranges/) | Easy | 6+ months | 7.6 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/01.%20Array%20Traversal%20%26%20Basics/0228.%20Summary%20Ranges/0228.%20Summary%20Ranges.md) |
| 17 | [414. Third Maximum Number](https://leetcode.com/problems/third-maximum-number/) | Easy | 6+ months | 6.9 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/01.%20Array%20Traversal%20%26%20Basics/0414.%20Third%20Maximum%20Number/0414.%20Third%20Maximum%20Number.md) |
| 18 | [2348. Number of Zero-Filled Subarrays](https://leetcode.com/problems/number-of-zero-filled-subarrays/) | Medium | 6+ months | 6.8 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/01.%20Array%20Traversal%20%26%20Basics/2348.%20Number%20of%20Zero-Filled%20Subarrays/2348.%20Number%20of%20Zero-Filled%20Subarrays.md) |
| 19 | [1014. Best Sightseeing Pair](https://leetcode.com/problems/best-sightseeing-pair/) | Medium | 6+ months | 6.6 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/01.%20Array%20Traversal%20%26%20Basics/1014.%20Best%20Sightseeing%20Pair/1014.%20Best%20Sightseeing%20Pair.md) |
| 20 | [1550. Three Consecutive Odds](https://leetcode.com/problems/three-consecutive-odds/) | Easy | 6+ months | 6.0 | ✅ Solved |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/01.%20Array%20Traversal%20%26%20Basics/1550.%20Three%20Consecutive%20Odds/1550.%20Three%20Consecutive%20Odds.md) |
| 21 | [2672. Number of Adjacent Elements With the Same Color](https://leetcode.com/problems/number-of-adjacent-elements-with-the-same-color/) | Medium | 6+ months | 5.4 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/01.%20Array%20Traversal%20%26%20Basics/2672.%20Number%20of%20Adjacent%20Elements%20With%20the%20Same%20Color/2672.%20Number%20of%20Adjacent%20Elements%20With%20the%20Same%20Color.md) |
| 22 | [1299. Replace Elements with Greatest Element on Right Side](https://leetcode.com/problems/replace-elements-with-greatest-element-on-right-side/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/01.%20Array%20Traversal%20%26%20Basics/1299.%20Replace%20Elements%20with%20Greatest%20Element%20on%20Right%20Side/1299.%20Replace%20Elements%20with%20Greatest%20Element%20on%20Right%20Side.md) |
| 23 | [1437. Check If All 1's Are at Least Length K Places Away](https://leetcode.com/problems/check-if-all-1s-are-at-least-length-k-places-away/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/01.%20Array%20Traversal%20%26%20Basics/1437.%20Check%20If%20All%201%27s%20Are%20at%20Least%20Length%20K%20Places%20Away/1437.%20Check%20If%20All%201%27s%20Are%20at%20Least%20Length%20K%20Places%20Away.md) |
| 24 | [1534. Count Good Triplets](https://leetcode.com/problems/count-good-triplets/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/01.%20Array%20Traversal%20%26%20Basics/1534.%20Count%20Good%20Triplets/1534.%20Count%20Good%20Triplets.md) |
| 25 | [1800. Maximum Ascending Subarray Sum](https://leetcode.com/problems/maximum-ascending-subarray-sum/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/01.%20Array%20Traversal%20%26%20Basics/1800.%20Maximum%20Ascending%20Subarray%20Sum/1800.%20Maximum%20Ascending%20Subarray%20Sum.md) |
| 26 | [2176. Count Equal and Divisible Pairs in an Array](https://leetcode.com/problems/count-equal-and-divisible-pairs-in-an-array/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/01.%20Array%20Traversal%20%26%20Basics/2176.%20Count%20Equal%20and%20Divisible%20Pairs%20in%20an%20Array/2176.%20Count%20Equal%20and%20Divisible%20Pairs%20in%20an%20Array.md) |
| 27 | [2239. Find Closest Number to Zero](https://leetcode.com/problems/find-closest-number-to-zero/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/01.%20Array%20Traversal%20%26%20Basics/2239.%20Find%20Closest%20Number%20to%20Zero/2239.%20Find%20Closest%20Number%20to%20Zero.md) |
| 28 | [2951. Find the Peaks](https://leetcode.com/problems/find-the-peaks/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/01.%20Array%20Traversal%20%26%20Basics/2951.%20Find%20the%20Peaks/2951.%20Find%20the%20Peaks.md) |
| 29 | [3000. Maximum Area of Longest Diagonal Rectangle](https://leetcode.com/problems/maximum-area-of-longest-diagonal-rectangle/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/01.%20Array%20Traversal%20%26%20Basics/3000.%20Maximum%20Area%20of%20Longest%20Diagonal%20Rectangle/3000.%20Maximum%20Area%20of%20Longest%20Diagonal%20Rectangle.md) |
| 30 | [3151. Special Array I](https://leetcode.com/problems/special-array-i/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/01.%20Array%20Traversal%20%26%20Basics/3151.%20Special%20Array%20I/3151.%20Special%20Array%20I.md) |
| 31 | [3423. Maximum Difference Between Adjacent Elements in a Circular Array](https://leetcode.com/problems/maximum-difference-between-adjacent-elements-in-a-circular-array/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/01.%20Array%20Traversal%20%26%20Basics/3423.%20Maximum%20Difference%20Between%20Adjacent%20Elements%20in%20a%20Circular%20Array/3423.%20Maximum%20Difference%20Between%20Adjacent%20Elements%20in%20a%20Circular%20Array.md) |
| 32 | [3637. Trionic Array I](https://leetcode.com/problems/trionic-array-i/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/01.%20Array%20Traversal%20%26%20Basics/3637.%20Trionic%20Array%20I/3637.%20Trionic%20Array%20I.md) |

### 01.02. In-Place Array Manipulation

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [31. Next Permutation](https://leetcode.com/problems/next-permutation/) | Medium | 3 months | 76.4 | ✅ Solved |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/02.%20In-Place%20Array%20Manipulation/0031.%20Next%20Permutation/0031.%20Next%20Permutation.md) |
| 2 | [189. Rotate Array](https://leetcode.com/problems/rotate-array/) | Medium | 6 months | 40.3 | ✅ Solved |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/02.%20In-Place%20Array%20Manipulation/0189.%20Rotate%20Array/0189.%20Rotate%20Array.md) |
| 3 | [1920. Build Array from Permutation](https://leetcode.com/problems/build-array-from-permutation/) | Easy | 6+ months | 36.7 | ✅ Solved |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/02.%20In-Place%20Array%20Manipulation/1920.%20Build%20Array%20from%20Permutation/1920.%20Build%20Array%20from%20Permutation.md) |
| 4 | [556. Next Greater Element III](https://leetcode.com/problems/next-greater-element-iii/) | Medium | 6+ months | 22.1 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/02.%20In-Place%20Array%20Manipulation/0556.%20Next%20Greater%20Element%20III/0556.%20Next%20Greater%20Element%20III.md) |

### 01.03. Hash Map Lookup

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [1. Two Sum](https://leetcode.com/problems/two-sum/) | Easy | 30 days | 84.7 | ✅ Solved |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/03.%20Hash%20Map%20Lookup/0001.%20Two%20Sum/0001.%20Two%20Sum.md) |
| 2 | [205. Isomorphic Strings](https://leetcode.com/problems/isomorphic-strings/) | Easy | 3 months | 32.3 | ✅ Solved |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/03.%20Hash%20Map%20Lookup/0205.%20Isomorphic%20Strings/0205.%20Isomorphic%20Strings.md) |
| 3 | [290. Word Pattern](https://leetcode.com/problems/word-pattern/) | Easy | 6+ months | 19.1 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/03.%20Hash%20Map%20Lookup/0290.%20Word%20Pattern/0290.%20Word%20Pattern.md) |
| 4 | [3761. Minimum Absolute Distance Between Mirror Pairs](https://leetcode.com/problems/minimum-absolute-distance-between-mirror-pairs/) | Medium | 6+ months | 9.3 | ✅ Solved |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/03.%20Hash%20Map%20Lookup/3761.%20Minimum%20Absolute%20Distance%20Between%20Mirror%20Pairs/3761.%20Minimum%20Absolute%20Distance%20Between%20Mirror%20Pairs.md) |
| 5 | [454. 4Sum II](https://leetcode.com/problems/4sum-ii/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/03.%20Hash%20Map%20Lookup/0454.%204Sum%20II/0454.%204Sum%20II.md) |
| 6 | [966. Vowel Spellchecker](https://leetcode.com/problems/vowel-spellchecker/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/03.%20Hash%20Map%20Lookup/0966.%20Vowel%20Spellchecker/0966.%20Vowel%20Spellchecker.md) |
| 7 | [1814. Count Nice Pairs in an Array](https://leetcode.com/problems/count-nice-pairs-in-an-array/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/03.%20Hash%20Map%20Lookup/1814.%20Count%20Nice%20Pairs%20in%20an%20Array/1814.%20Count%20Nice%20Pairs%20in%20an%20Array.md) |
| 8 | [2325. Decode the Message](https://leetcode.com/problems/decode-the-message/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/03.%20Hash%20Map%20Lookup/2325.%20Decode%20the%20Message/2325.%20Decode%20the%20Message.md) |
| 9 | [2342. Max Sum of a Pair With Equal Sum of Digits](https://leetcode.com/problems/max-sum-of-a-pair-with-equal-sum-of-digits/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/03.%20Hash%20Map%20Lookup/2342.%20Max%20Sum%20of%20a%20Pair%20With%20Equal%20Sum%20of%20Digits/2342.%20Max%20Sum%20of%20a%20Pair%20With%20Equal%20Sum%20of%20Digits.md) |
| 10 | [2352. Equal Row and Column Pairs](https://leetcode.com/problems/equal-row-and-column-pairs/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/03.%20Hash%20Map%20Lookup/2352.%20Equal%20Row%20and%20Column%20Pairs/2352.%20Equal%20Row%20and%20Column%20Pairs.md) |
| 11 | [2365. Task Scheduler II](https://leetcode.com/problems/task-scheduler-ii/) | Medium | 6+ months | 36.1 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/03.%20Hash%20Map%20Lookup/2365.%20Task%20Scheduler%20II/2365.%20Task%20Scheduler%20II.md) |
| 12 | [890. Find and Replace Pattern](https://leetcode.com/problems/find-and-replace-pattern/) | Medium | 6+ months | 6.8 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/03.%20Hash%20Map%20Lookup/0890.%20Find%20and%20Replace%20Pattern/0890.%20Find%20and%20Replace%20Pattern.md) |

### 01.04. Hash Set & Duplicates

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [128. Longest Consecutive Sequence](https://leetcode.com/problems/longest-consecutive-sequence/) | Medium | 3 months | 57.0 | ✅ Solved |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/04.%20Hash%20Set%20%26%20Duplicates/0128.%20Longest%20Consecutive%20Sequence/0128.%20Longest%20Consecutive%20Sequence.md) |
| 2 | [217. Contains Duplicate](https://leetcode.com/problems/contains-duplicate/) | Easy | 3 months | 44.4 | ✅ Solved |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/04.%20Hash%20Set%20%26%20Duplicates/0217.%20Contains%20Duplicate/0217.%20Contains%20Duplicate.md) |
| 3 | [349. Intersection of Two Arrays](https://leetcode.com/problems/intersection-of-two-arrays/) | Easy | 3 months | 41.3 | ✅ Solved |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/04.%20Hash%20Set%20%26%20Duplicates/0349.%20Intersection%20of%20Two%20Arrays/0349.%20Intersection%20of%20Two%20Arrays.md) |
| 4 | [36. Valid Sudoku](https://leetcode.com/problems/valid-sudoku/) | Medium | 3 months | 34.5 | ✅ Solved |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/04.%20Hash%20Set%20%26%20Duplicates/0036.%20Valid%20Sudoku/0036.%20Valid%20Sudoku.md) |
| 5 | [1832. Check if the Sentence Is Pangram](https://leetcode.com/problems/check-if-the-sentence-is-pangram/) | Easy | 6+ months | 8.8 | ✅ Solved |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/04.%20Hash%20Set%20%26%20Duplicates/1832.%20Check%20if%20the%20Sentence%20Is%20Pangram/1832.%20Check%20if%20the%20Sentence%20Is%20Pangram.md) |
| 6 | [3731. Find Missing Elements](https://leetcode.com/problems/find-missing-elements/) | Easy | 6+ months | 8.6 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/04.%20Hash%20Set%20%26%20Duplicates/3731.%20Find%20Missing%20Elements/3731.%20Find%20Missing%20Elements.md) |
| 7 | [2657. Find the Prefix Common Array of Two Arrays](https://leetcode.com/problems/find-the-prefix-common-array-of-two-arrays/) | Medium | 6+ months | 8.4 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/04.%20Hash%20Set%20%26%20Duplicates/2657.%20Find%20the%20Prefix%20Common%20Array%20of%20Two%20Arrays/2657.%20Find%20the%20Prefix%20Common%20Array%20of%20Two%20Arrays.md) |
| 8 | [2215. Find the Difference of Two Arrays](https://leetcode.com/problems/find-the-difference-of-two-arrays/) | Easy | 6+ months | 5.9 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/04.%20Hash%20Set%20%26%20Duplicates/2215.%20Find%20the%20Difference%20of%20Two%20Arrays/2215.%20Find%20the%20Difference%20of%20Two%20Arrays.md) |
| 9 | [771. Jewels and Stones](https://leetcode.com/problems/jewels-and-stones/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/04.%20Hash%20Set%20%26%20Duplicates/0771.%20Jewels%20and%20Stones/0771.%20Jewels%20and%20Stones.md) |
| 10 | [888. Fair Candy Swap](https://leetcode.com/problems/fair-candy-swap/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/04.%20Hash%20Set%20%26%20Duplicates/0888.%20Fair%20Candy%20Swap/0888.%20Fair%20Candy%20Swap.md) |
| 11 | [961. N-Repeated Element in Size 2N Array](https://leetcode.com/problems/n-repeated-element-in-size-2n-array/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/04.%20Hash%20Set%20%26%20Duplicates/0961.%20N-Repeated%20Element%20in%20Size%202N%20Array/0961.%20N-Repeated%20Element%20in%20Size%202N%20Array.md) |
| 12 | [1346. Check If N and Its Double Exist](https://leetcode.com/problems/check-if-n-and-its-double-exist/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/04.%20Hash%20Set%20%26%20Duplicates/1346.%20Check%20If%20N%20and%20Its%20Double%20Exist/1346.%20Check%20If%20N%20and%20Its%20Double%20Exist.md) |
| 13 | [1436. Destination City](https://leetcode.com/problems/destination-city/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/04.%20Hash%20Set%20%26%20Duplicates/1436.%20Destination%20City/1436.%20Destination%20City.md) |
| 14 | [2154. Keep Multiplying Found Values by Two](https://leetcode.com/problems/keep-multiplying-found-values-by-two/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/04.%20Hash%20Set%20%26%20Duplicates/2154.%20Keep%20Multiplying%20Found%20Values%20by%20Two/2154.%20Keep%20Multiplying%20Found%20Values%20by%20Two.md) |
| 15 | [2956. Find Common Elements Between Two Arrays](https://leetcode.com/problems/find-common-elements-between-two-arrays/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/04.%20Hash%20Set%20%26%20Duplicates/2956.%20Find%20Common%20Elements%20Between%20Two%20Arrays/2956.%20Find%20Common%20Elements%20Between%20Two%20Arrays.md) |
| 16 | [3120. Count the Number of Special Characters I](https://leetcode.com/problems/count-the-number-of-special-characters-i/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/04.%20Hash%20Set%20%26%20Duplicates/3120.%20Count%20the%20Number%20of%20Special%20Characters%20I/3120.%20Count%20the%20Number%20of%20Special%20Characters%20I.md) |
| 17 | [3289. The Two Sneaky Numbers of Digitville](https://leetcode.com/problems/the-two-sneaky-numbers-of-digitville/) | Easy | 6+ months | 5.0 | 🟡 Attempted |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/04.%20Hash%20Set%20%26%20Duplicates/3289.%20The%20Two%20Sneaky%20Numbers%20of%20Digitville/3289.%20The%20Two%20Sneaky%20Numbers%20of%20Digitville.md) |
| 18 | [3396. Minimum Number of Operations to Make Elements in Array Distinct](https://leetcode.com/problems/minimum-number-of-operations-to-make-elements-in-array-distinct/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/04.%20Hash%20Set%20%26%20Duplicates/3396.%20Minimum%20Number%20of%20Operations%20to%20Make%20Elements%20in%20Array%20Distinct/3396.%20Minimum%20Number%20of%20Operations%20to%20Make%20Elements%20in%20Array%20Distinct.md) |
| 19 | [575. Distribute Candies](https://leetcode.com/problems/distribute-candies/) | Easy | 6+ months | 5.6 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/04.%20Hash%20Set%20%26%20Duplicates/0575.%20Distribute%20Candies/0575.%20Distribute%20Candies.md) |
| 20 | [3483. Unique 3-Digit Even Numbers](https://leetcode.com/problems/unique-3-digit-even-numbers/) | Easy | 6+ months | 5.5 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/04.%20Hash%20Set%20%26%20Duplicates/3483.%20Unique%203-Digit%20Even%20Numbers/3483.%20Unique%203-Digit%20Even%20Numbers.md) |
| 21 | [3668. Restore Finishing Order](https://leetcode.com/problems/restore-finishing-order/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/04.%20Hash%20Set%20%26%20Duplicates/3668.%20Restore%20Finishing%20Order/3668.%20Restore%20Finishing%20Order.md) |

### 01.05. Frequency Counting

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [383. Ransom Note](https://leetcode.com/problems/ransom-note/) | Easy | 3 months | 26.7 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/05.%20Frequency%20Counting/0383.%20Ransom%20Note/0383.%20Ransom%20Note.md) |
| 2 | [2965. Find Missing and Repeated Values](https://leetcode.com/problems/find-missing-and-repeated-values/) | Easy | 3 months | 13.5 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/05.%20Frequency%20Counting/2965.%20Find%20Missing%20and%20Repeated%20Values/2965.%20Find%20Missing%20and%20Repeated%20Values.md) |
| 3 | [387. First Unique Character in a String](https://leetcode.com/problems/first-unique-character-in-a-string/) | Easy | 6 months | 28.7 | ✅ Solved |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/05.%20Frequency%20Counting/0387.%20First%20Unique%20Character%20in%20a%20String/0387.%20First%20Unique%20Character%20in%20a%20String.md) |
| 4 | [3020. Find the Maximum Number of Elements in Subset](https://leetcode.com/problems/find-the-maximum-number-of-elements-in-subset/) | Medium | 6 months | 7.3 | ✅ Solved |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/05.%20Frequency%20Counting/3020.%20Find%20the%20Maximum%20Number%20of%20Elements%20in%20Subset/3020.%20Find%20the%20Maximum%20Number%20of%20Elements%20in%20Subset.md) |
| 5 | [3471. Find the Largest Almost Missing Integer](https://leetcode.com/problems/find-the-largest-almost-missing-integer/) | Easy | 6 months | 5.0 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/05.%20Frequency%20Counting/3471.%20Find%20the%20Largest%20Almost%20Missing%20Integer/3471.%20Find%20the%20Largest%20Almost%20Missing%20Integer.md) |
| 6 | [3960. Frequency Balance Subarray](https://leetcode.com/problems/frequency-balance-subarray/) | Medium | 6 months | 5.0 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/05.%20Frequency%20Counting/3960.%20Frequency%20Balance%20Subarray/3960.%20Frequency%20Balance%20Subarray.md) |
| 7 | [825. Friends Of Appropriate Ages](https://leetcode.com/problems/friends-of-appropriate-ages/) | Medium | 6+ months | 54.4 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/05.%20Frequency%20Counting/0825.%20Friends%20Of%20Appropriate%20Ages/0825.%20Friends%20Of%20Appropriate%20Ages.md) |
| 8 | [1748. Sum of Unique Elements](https://leetcode.com/problems/sum-of-unique-elements/) | Easy | 6+ months | 38.6 | ✅ Solved |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/05.%20Frequency%20Counting/1748.%20Sum%20of%20Unique%20Elements/1748.%20Sum%20of%20Unique%20Elements.md) |
| 9 | [554. Brick Wall](https://leetcode.com/problems/brick-wall/) | Medium | 6+ months | 38.1 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/05.%20Frequency%20Counting/0554.%20Brick%20Wall/0554.%20Brick%20Wall.md) |
| 10 | [1207. Unique Number of Occurrences](https://leetcode.com/problems/unique-number-of-occurrences/) | Easy | 6+ months | 20.7 | ✅ Solved |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/05.%20Frequency%20Counting/1207.%20Unique%20Number%20of%20Occurrences/1207.%20Unique%20Number%20of%20Occurrences.md) |
| 11 | [3527. Find the Most Common Response](https://leetcode.com/problems/find-the-most-common-response/) | Medium | 6+ months | 19.6 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/05.%20Frequency%20Counting/3527.%20Find%20the%20Most%20Common%20Response/3527.%20Find%20the%20Most%20Common%20Response.md) |
| 12 | [3371. Identify the Largest Outlier in an Array](https://leetcode.com/problems/identify-the-largest-outlier-in-an-array/) | Medium | 6+ months | 17.7 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/05.%20Frequency%20Counting/3371.%20Identify%20the%20Largest%20Outlier%20in%20an%20Array/3371.%20Identify%20the%20Largest%20Outlier%20in%20an%20Array.md) |
| 13 | [1394. Find Lucky Integer in an Array](https://leetcode.com/problems/find-lucky-integer-in-an-array/) | Easy | 6+ months | 17.0 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/05.%20Frequency%20Counting/1394.%20Find%20Lucky%20Integer%20in%20an%20Array/1394.%20Find%20Lucky%20Integer%20in%20an%20Array.md) |
| 14 | [350. Intersection of Two Arrays II](https://leetcode.com/problems/intersection-of-two-arrays-ii/) | Easy | 6+ months | 15.6 | ✅ Solved |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/05.%20Frequency%20Counting/0350.%20Intersection%20of%20Two%20Arrays%20II/0350.%20Intersection%20of%20Two%20Arrays%20II.md) |
| 15 | [299. Bulls and Cows](https://leetcode.com/problems/bulls-and-cows/) | Medium | 6+ months | 14.9 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/05.%20Frequency%20Counting/0299.%20Bulls%20and%20Cows/0299.%20Bulls%20and%20Cows.md) |
| 16 | [594. Longest Harmonious Subsequence](https://leetcode.com/problems/longest-harmonious-subsequence/) | Easy | 6+ months | 10.8 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/05.%20Frequency%20Counting/0594.%20Longest%20Harmonious%20Subsequence/0594.%20Longest%20Harmonious%20Subsequence.md) |
| 17 | [1781. Sum of Beauty of All Substrings](https://leetcode.com/problems/sum-of-beauty-of-all-substrings/) | Medium | 6+ months | 10.7 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/05.%20Frequency%20Counting/1781.%20Sum%20of%20Beauty%20of%20All%20Substrings/1781.%20Sum%20of%20Beauty%20of%20All%20Substrings.md) |
| 18 | [2094. Finding 3-Digit Even Numbers](https://leetcode.com/problems/finding-3-digit-even-numbers/) | Easy | 6+ months | 9.8 | ✅ Solved |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/05.%20Frequency%20Counting/2094.%20Finding%203-Digit%20Even%20Numbers/2094.%20Finding%203-Digit%20Even%20Numbers.md) |
| 19 | [3583. Count Special Triplets](https://leetcode.com/problems/count-special-triplets/) | Medium | 6+ months | 9.7 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/05.%20Frequency%20Counting/3583.%20Count%20Special%20Triplets/3583.%20Count%20Special%20Triplets.md) |
| 20 | [3541. Find Most Frequent Vowel and Consonant](https://leetcode.com/problems/find-most-frequent-vowel-and-consonant/) | Easy | 6+ months | 8.0 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/05.%20Frequency%20Counting/3541.%20Find%20Most%20Frequent%20Vowel%20and%20Consonant/3541.%20Find%20Most%20Frequent%20Vowel%20and%20Consonant.md) |
| 21 | [1002. Find Common Characters](https://leetcode.com/problems/find-common-characters/) | Easy | 6+ months | 6.6 | ✅ Solved |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/05.%20Frequency%20Counting/1002.%20Find%20Common%20Characters/1002.%20Find%20Common%20Characters.md) |
| 22 | [819. Most Common Word](https://leetcode.com/problems/most-common-word/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/05.%20Frequency%20Counting/0819.%20Most%20Common%20Word/0819.%20Most%20Common%20Word.md) |
| 23 | [869. Reordered Power of 2](https://leetcode.com/problems/reordered-power-of-2/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/05.%20Frequency%20Counting/0869.%20Reordered%20Power%20of%202/0869.%20Reordered%20Power%20of%202.md) |
| 24 | [916. Word Subsets](https://leetcode.com/problems/word-subsets/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/05.%20Frequency%20Counting/0916.%20Word%20Subsets/0916.%20Word%20Subsets.md) |
| 25 | [1160. Find Words That Can Be Formed by Characters](https://leetcode.com/problems/find-words-that-can-be-formed-by-characters/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/05.%20Frequency%20Counting/1160.%20Find%20Words%20That%20Can%20Be%20Formed%20by%20Characters/1160.%20Find%20Words%20That%20Can%20Be%20Formed%20by%20Characters.md) |
| 26 | [1399. Count Largest Group](https://leetcode.com/problems/count-largest-group/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/05.%20Frequency%20Counting/1399.%20Count%20Largest%20Group/1399.%20Count%20Largest%20Group.md) |
| 27 | [2981. Find Longest Special Substring That Occurs Thrice I](https://leetcode.com/problems/find-longest-special-substring-that-occurs-thrice-i/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/05.%20Frequency%20Counting/2981.%20Find%20Longest%20Special%20Substring%20That%20Occurs%20Thrice%20I/2981.%20Find%20Longest%20Special%20Substring%20That%20Occurs%20Thrice%20I.md) |
| 28 | [3005. Count Elements With Maximum Frequency](https://leetcode.com/problems/count-elements-with-maximum-frequency/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/05.%20Frequency%20Counting/3005.%20Count%20Elements%20With%20Maximum%20Frequency/3005.%20Count%20Elements%20With%20Maximum%20Frequency.md) |
| 29 | [3442. Maximum Difference Between Even and Odd Frequency I](https://leetcode.com/problems/maximum-difference-between-even-and-odd-frequency-i/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/05.%20Frequency%20Counting/3442.%20Maximum%20Difference%20Between%20Even%20and%20Odd%20Frequency%20I/3442.%20Maximum%20Difference%20Between%20Even%20and%20Odd%20Frequency%20I.md) |
| 30 | [3713. Longest Balanced Substring I](https://leetcode.com/problems/longest-balanced-substring-i/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/05.%20Frequency%20Counting/3713.%20Longest%20Balanced%20Substring%20I/3713.%20Longest%20Balanced%20Substring%20I.md) |
| 31 | [1460. Make Two Arrays Equal by Reversing Subarrays](https://leetcode.com/problems/make-two-arrays-equal-by-reversing-subarrays/) | Easy | 6+ months | 36.1 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/05.%20Frequency%20Counting/1460.%20Make%20Two%20Arrays%20Equal%20by%20Reversing%20Subarrays/1460.%20Make%20Two%20Arrays%20Equal%20by%20Reversing%20Subarrays.md) |
| 32 | [1189. Maximum Number of Balloons](https://leetcode.com/problems/maximum-number-of-balloons/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/05.%20Frequency%20Counting/1189.%20Maximum%20Number%20of%20Balloons/1189.%20Maximum%20Number%20of%20Balloons.md) |
| 33 | [1941. Check if All Characters Have Equal Number of Occurrences](https://leetcode.com/problems/check-if-all-characters-have-equal-number-of-occurrences/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/05.%20Frequency%20Counting/1941.%20Check%20if%20All%20Characters%20Have%20Equal%20Number%20of%20Occurrences/1941.%20Check%20if%20All%20Characters%20Have%20Equal%20Number%20of%20Occurrences.md) |

### 01.06. Grouping by Key

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [49. Group Anagrams](https://leetcode.com/problems/group-anagrams/) | Medium | 3 months | 63.1 | ✅ Solved |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/06.%20Grouping%20by%20Key/0049.%20Group%20Anagrams/0049.%20Group%20Anagrams.md) |
| 2 | [249. Group Shifted Strings](https://leetcode.com/problems/group-shifted-strings/) 🔒 | Medium | 3 months | 57.5 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/06.%20Grouping%20by%20Key/0249.%20Group%20Shifted%20Strings/0249.%20Group%20Shifted%20Strings.md) |
| 3 | [609. Find Duplicate File in System](https://leetcode.com/problems/find-duplicate-file-in-system/) | Medium | 6+ months | 5.8 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/06.%20Grouping%20by%20Key/0609.%20Find%20Duplicate%20File%20in%20System/0609.%20Find%20Duplicate%20File%20in%20System.md) |
| 4 | [893. Groups of Special-Equivalent Strings](https://leetcode.com/problems/groups-of-special-equivalent-strings/) | Medium | 6+ months | 36.1 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/06.%20Grouping%20by%20Key/0893.%20Groups%20of%20Special-Equivalent%20Strings/0893.%20Groups%20of%20Special-Equivalent%20Strings.md) |

### 01.07. Kadane's Algorithm

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [53. Maximum Subarray](https://leetcode.com/problems/maximum-subarray/) | Medium | 6 months | 58.9 | ✅ Solved |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/07.%20Kadane%27s%20Algorithm/0053.%20Maximum%20Subarray/0053.%20Maximum%20Subarray.md) |
| 2 | [152. Maximum Product Subarray](https://leetcode.com/problems/maximum-product-subarray/) | Medium | 6 months | 35.5 | ✅ Solved |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/07.%20Kadane%27s%20Algorithm/0152.%20Maximum%20Product%20Subarray/0152.%20Maximum%20Product%20Subarray.md) |
| 3 | [918. Maximum Sum Circular Subarray](https://leetcode.com/problems/maximum-sum-circular-subarray/) | Medium | 6+ months | 12.8 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/07.%20Kadane%27s%20Algorithm/0918.%20Maximum%20Sum%20Circular%20Subarray/0918.%20Maximum%20Sum%20Circular%20Subarray.md) |
| 4 | [1749. Maximum Absolute Sum of Any Subarray](https://leetcode.com/problems/maximum-absolute-sum-of-any-subarray/) | Medium | 6+ months | 10.9 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/07.%20Kadane%27s%20Algorithm/1749.%20Maximum%20Absolute%20Sum%20of%20Any%20Subarray/1749.%20Maximum%20Absolute%20Sum%20of%20Any%20Subarray.md) |

### 01.08. Cyclic Sort & Index Marking

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [645. Set Mismatch](https://leetcode.com/problems/set-mismatch/) | Easy | 6 months | 25.6 | 🟡 Attempted |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/08.%20Cyclic%20Sort%20%26%20Index%20Marking/0645.%20Set%20Mismatch/0645.%20Set%20Mismatch.md) |
| 2 | [41. First Missing Positive](https://leetcode.com/problems/first-missing-positive/) | Hard | 6+ months | 30.5 | ✅ Solved |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/08.%20Cyclic%20Sort%20%26%20Index%20Marking/0041.%20First%20Missing%20Positive/0041.%20First%20Missing%20Positive.md) |
| 3 | [442. Find All Duplicates in an Array](https://leetcode.com/problems/find-all-duplicates-in-an-array/) | Medium | 6+ months | 20.2 | ✅ Solved |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/08.%20Cyclic%20Sort%20%26%20Index%20Marking/0442.%20Find%20All%20Duplicates%20in%20an%20Array/0442.%20Find%20All%20Duplicates%20in%20an%20Array.md) |
| 4 | [448. Find All Numbers Disappeared in an Array](https://leetcode.com/problems/find-all-numbers-disappeared-in-an-array/) | Easy | 6+ months | 5.8 | ✅ Solved |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/08.%20Cyclic%20Sort%20%26%20Index%20Marking/0448.%20Find%20All%20Numbers%20Disappeared%20in%20an%20Array/0448.%20Find%20All%20Numbers%20Disappeared%20in%20an%20Array.md) |
| 5 | [565. Array Nesting](https://leetcode.com/problems/array-nesting/) | Medium | 6+ months | 5.1 | Todo |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/08.%20Cyclic%20Sort%20%26%20Index%20Marking/0565.%20Array%20Nesting/0565.%20Array%20Nesting.md) |

### 01.09. Majority Element (Boyer-Moore)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea&ensp;&#8203; | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [169. Majority Element](https://leetcode.com/problems/majority-element/) | Easy | 6 months | 46.4 | ✅ Solved |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/09.%20Majority%20Element%20%28Boyer-Moore%29/0169.%20Majority%20Element/0169.%20Majority%20Element.md) |
| 2 | [229. Majority Element II](https://leetcode.com/problems/majority-element-ii/) | Medium | 6 months | 24.0 | ✅ Solved |  |  |  | [notes](01.%20Arrays%20%26%20Hashing/09.%20Majority%20Element%20%28Boyer-Moore%29/0229.%20Majority%20Element%20II/0229.%20Majority%20Element%20II.md) |

## 02. Strings

65 problems: 41 Easy, 17 Medium, 7 Hard. [Open chapter README](02.%20Strings/README.md) · [Back to top](#chapters)

### 02.01. String Basics & Manipulation

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [151. Reverse Words in a String](https://leetcode.com/problems/reverse-words-in-a-string/) | Medium | 6 months | 39.3 | Todo |  |  |  | [notes](02.%20Strings/01.%20String%20Basics%20%26%20Manipulation/0151.%20Reverse%20Words%20in%20a%20String/0151.%20Reverse%20Words%20in%20a%20String.md) |
| 2 | [2667. Create Hello World Function](https://leetcode.com/problems/create-hello-world-function/) | Easy | 6 months | 27.2 | Todo |  |  |  | [notes](02.%20Strings/01.%20String%20Basics%20%26%20Manipulation/2667.%20Create%20Hello%20World%20Function/2667.%20Create%20Hello%20World%20Function.md) |
| 3 | [58. Length of Last Word](https://leetcode.com/problems/length-of-last-word/) | Easy | 6 months | 21.1 | ✅ Solved |  |  |  | [notes](02.%20Strings/01.%20String%20Basics%20%26%20Manipulation/0058.%20Length%20of%20Last%20Word/0058.%20Length%20of%20Last%20Word.md) |
| 4 | [1796. Second Largest Digit in a String](https://leetcode.com/problems/second-largest-digit-in-a-string/) | Easy | 6 months | 5.0 | Todo |  |  |  | [notes](02.%20Strings/01.%20String%20Basics%20%26%20Manipulation/1796.%20Second%20Largest%20Digit%20in%20a%20String/1796.%20Second%20Largest%20Digit%20in%20a%20String.md) |
| 5 | [1108. Defanging an IP Address](https://leetcode.com/problems/defanging-an-ip-address/) | Easy | 6+ months | 38.8 | ✅ Solved |  |  |  | [notes](02.%20Strings/01.%20String%20Basics%20%26%20Manipulation/1108.%20Defanging%20an%20IP%20Address/1108.%20Defanging%20an%20IP%20Address.md) |
| 6 | [696. Count Binary Substrings](https://leetcode.com/problems/count-binary-substrings/) | Easy | 6+ months | 12.2 | ✅ Solved |  |  |  | [notes](02.%20Strings/01.%20String%20Basics%20%26%20Manipulation/0696.%20Count%20Binary%20Substrings/0696.%20Count%20Binary%20Substrings.md) |
| 7 | [709. To Lower Case](https://leetcode.com/problems/to-lower-case/) | Easy | 6+ months | 10.2 | Todo |  |  |  | [notes](02.%20Strings/01.%20String%20Basics%20%26%20Manipulation/0709.%20To%20Lower%20Case/0709.%20To%20Lower%20Case.md) |
| 8 | [1446. Consecutive Characters](https://leetcode.com/problems/consecutive-characters/) | Easy | 6+ months | 8.7 | Todo |  |  |  | [notes](02.%20Strings/01.%20String%20Basics%20%26%20Manipulation/1446.%20Consecutive%20Characters/1446.%20Consecutive%20Characters.md) |
| 9 | [2942. Find Words Containing Character](https://leetcode.com/problems/find-words-containing-character/) | Easy | 6+ months | 8.6 | ✅ Solved |  |  |  | [notes](02.%20Strings/01.%20String%20Basics%20%26%20Manipulation/2942.%20Find%20Words%20Containing%20Character/2942.%20Find%20Words%20Containing%20Character.md) |
| 10 | [520. Detect Capital](https://leetcode.com/problems/detect-capital/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Strings/01.%20String%20Basics%20%26%20Manipulation/0520.%20Detect%20Capital/0520.%20Detect%20Capital.md) |
| 11 | [2264. Largest 3-Same-Digit Number in String](https://leetcode.com/problems/largest-3-same-digit-number-in-string/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Strings/01.%20String%20Basics%20%26%20Manipulation/2264.%20Largest%203-Same-Digit%20Number%20in%20String/2264.%20Largest%203-Same-Digit%20Number%20in%20String.md) |
| 12 | [3019. Number of Changing Keys](https://leetcode.com/problems/number-of-changing-keys/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](02.%20Strings/01.%20String%20Basics%20%26%20Manipulation/3019.%20Number%20of%20Changing%20Keys/3019.%20Number%20of%20Changing%20Keys.md) |
| 13 | [3110. Score of a String](https://leetcode.com/problems/score-of-a-string/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](02.%20Strings/01.%20String%20Basics%20%26%20Manipulation/3110.%20Score%20of%20a%20String/3110.%20Score%20of%20a%20String.md) |
| 14 | [3330. Find the Original Typed String I](https://leetcode.com/problems/find-the-original-typed-string-i/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Strings/01.%20String%20Basics%20%26%20Manipulation/3330.%20Find%20the%20Original%20Typed%20String%20I/3330.%20Find%20the%20Original%20Typed%20String%20I.md) |
| 15 | [1773. Count Items Matching a Rule](https://leetcode.com/problems/count-items-matching-a-rule/) | Easy | 6+ months | 37.1 | ✅ Solved |  |  |  | [notes](02.%20Strings/01.%20String%20Basics%20%26%20Manipulation/1773.%20Count%20Items%20Matching%20a%20Rule/1773.%20Count%20Items%20Matching%20a%20Rule.md) |
| 16 | [2124. Check if All A's Appears Before All B's](https://leetcode.com/problems/check-if-all-as-appears-before-all-bs/) | Easy | 6+ months | 7.8 | ✅ Solved |  |  |  | [notes](02.%20Strings/01.%20String%20Basics%20%26%20Manipulation/2124.%20Check%20if%20All%20A%27s%20Appears%20Before%20All%20B%27s/2124.%20Check%20if%20All%20A%27s%20Appears%20Before%20All%20B%27s.md) |
| 17 | [1816. Truncate Sentence](https://leetcode.com/problems/truncate-sentence/) | Easy | 6+ months | 7.2 | Todo |  |  |  | [notes](02.%20Strings/01.%20String%20Basics%20%26%20Manipulation/1816.%20Truncate%20Sentence/1816.%20Truncate%20Sentence.md) |

### 02.02. Palindromes

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [5. Longest Palindromic Substring](https://leetcode.com/problems/longest-palindromic-substring/) | Medium | 30 days | 58.9 | ✅ Solved |  |  |  | [notes](02.%20Strings/02.%20Palindromes/0005.%20Longest%20Palindromic%20Substring/0005.%20Longest%20Palindromic%20Substring.md) |
| 2 | [125. Valid Palindrome](https://leetcode.com/problems/valid-palindrome/) | Easy | 3 months | 83.8 | ✅ Solved |  |  |  | [notes](02.%20Strings/02.%20Palindromes/0125.%20Valid%20Palindrome/0125.%20Valid%20Palindrome.md) |
| 3 | [409. Longest Palindrome](https://leetcode.com/problems/longest-palindrome/) | Easy | 6 months | 24.3 | Todo |  |  |  | [notes](02.%20Strings/02.%20Palindromes/0409.%20Longest%20Palindrome/0409.%20Longest%20Palindrome.md) |
| 4 | [3517. Smallest Palindromic Rearrangement I](https://leetcode.com/problems/smallest-palindromic-rearrangement-i/) | Medium | 6 months | 6.9 | Todo |  |  |  | [notes](02.%20Strings/02.%20Palindromes/3517.%20Smallest%20Palindromic%20Rearrangement%20I/3517.%20Smallest%20Palindromic%20Rearrangement%20I.md) |
| 5 | [680. Valid Palindrome II](https://leetcode.com/problems/valid-palindrome-ii/) | Easy | 6+ months | 95.7 | ✅ Solved |  |  |  | [notes](02.%20Strings/02.%20Palindromes/0680.%20Valid%20Palindrome%20II/0680.%20Valid%20Palindrome%20II.md) |
| 6 | [647. Palindromic Substrings](https://leetcode.com/problems/palindromic-substrings/) | Medium | 6+ months | 66.3 | ✅ Solved |  |  |  | [notes](02.%20Strings/02.%20Palindromes/0647.%20Palindromic%20Substrings/0647.%20Palindromic%20Substrings.md) |
| 7 | [246. Strobogrammatic Number](https://leetcode.com/problems/strobogrammatic-number/) 🔒 | Easy | 6+ months | 45.2 | Todo |  |  |  | [notes](02.%20Strings/02.%20Palindromes/0246.%20Strobogrammatic%20Number/0246.%20Strobogrammatic%20Number.md) |
| 8 | [266. Palindrome Permutation](https://leetcode.com/problems/palindrome-permutation/) 🔒 | Easy | 6+ months | 5.9 | Todo |  |  |  | [notes](02.%20Strings/02.%20Palindromes/0266.%20Palindrome%20Permutation/0266.%20Palindrome%20Permutation.md) |
| 9 | [1930. Unique Length-3 Palindromic Subsequences](https://leetcode.com/problems/unique-length-3-palindromic-subsequences/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Strings/02.%20Palindromes/1930.%20Unique%20Length-3%20Palindromic%20Subsequences/1930.%20Unique%20Length-3%20Palindromic%20Subsequences.md) |
| 10 | [2697. Lexicographically Smallest Palindrome](https://leetcode.com/problems/lexicographically-smallest-palindrome/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](02.%20Strings/02.%20Palindromes/2697.%20Lexicographically%20Smallest%20Palindrome/2697.%20Lexicographically%20Smallest%20Palindrome.md) |
| 11 | [3503. Longest Palindrome After Substring Concatenation I](https://leetcode.com/problems/longest-palindrome-after-substring-concatenation-i/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Strings/02.%20Palindromes/3503.%20Longest%20Palindrome%20After%20Substring%20Concatenation%20I/3503.%20Longest%20Palindrome%20After%20Substring%20Concatenation%20I.md) |

### 02.03. Parsing & Validation

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [13. Roman to Integer](https://leetcode.com/problems/roman-to-integer/) | Easy | 3 months | 58.2 | ✅ Solved |  |  |  | [notes](02.%20Strings/03.%20Parsing%20%26%20Validation/0013.%20Roman%20to%20Integer/0013.%20Roman%20to%20Integer.md) |
| 2 | [8. String to Integer (atoi)](https://leetcode.com/problems/string-to-integer-atoi/) | Medium | 6 months | 51.1 | Todo |  |  |  | [notes](02.%20Strings/03.%20Parsing%20%26%20Validation/0008.%20String%20to%20Integer%20%28atoi%29/0008.%20String%20to%20Integer%20%28atoi%29.md) |
| 3 | [65. Valid Number](https://leetcode.com/problems/valid-number/) | Hard | 6+ months | 64.0 | Todo |  |  |  | [notes](02.%20Strings/03.%20Parsing%20%26%20Validation/0065.%20Valid%20Number/0065.%20Valid%20Number.md) |
| 4 | [468. Validate IP Address](https://leetcode.com/problems/validate-ip-address/) | Medium | 6+ months | 7.3 | Todo |  |  |  | [notes](02.%20Strings/03.%20Parsing%20%26%20Validation/0468.%20Validate%20IP%20Address/0468.%20Validate%20IP%20Address.md) |
| 5 | [537. Complex Number Multiplication](https://leetcode.com/problems/complex-number-multiplication/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Strings/03.%20Parsing%20%26%20Validation/0537.%20Complex%20Number%20Multiplication/0537.%20Complex%20Number%20Multiplication.md) |
| 6 | [2047. Number of Valid Words in a Sentence](https://leetcode.com/problems/number-of-valid-words-in-a-sentence/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Strings/03.%20Parsing%20%26%20Validation/2047.%20Number%20of%20Valid%20Words%20in%20a%20Sentence/2047.%20Number%20of%20Valid%20Words%20in%20a%20Sentence.md) |
| 7 | [3136. Valid Word](https://leetcode.com/problems/valid-word/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Strings/03.%20Parsing%20%26%20Validation/3136.%20Valid%20Word/3136.%20Valid%20Word.md) |

### 02.04. String Building & Formatting

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [824. Goat Latin](https://leetcode.com/problems/goat-latin/) | Easy | 3 months | 63.7 | Todo |  |  |  | [notes](02.%20Strings/04.%20String%20Building%20%26%20Formatting/0824.%20Goat%20Latin/0824.%20Goat%20Latin.md) |
| 2 | [6. Zigzag Conversion](https://leetcode.com/problems/zigzag-conversion/) | Medium | 3 months | 32.4 | Todo |  |  |  | [notes](02.%20Strings/04.%20String%20Building%20%26%20Formatting/0006.%20Zigzag%20Conversion/0006.%20Zigzag%20Conversion.md) |
| 3 | [38. Count and Say](https://leetcode.com/problems/count-and-say/) | Medium | 6 months | 42.6 | Todo |  |  |  | [notes](02.%20Strings/04.%20String%20Building%20%26%20Formatting/0038.%20Count%20and%20Say/0038.%20Count%20and%20Say.md) |
| 4 | [12. Integer to Roman](https://leetcode.com/problems/integer-to-roman/) | Medium | 6 months | 25.9 | Todo |  |  |  | [notes](02.%20Strings/04.%20String%20Building%20%26%20Formatting/0012.%20Integer%20to%20Roman/0012.%20Integer%20to%20Roman.md) |
| 5 | [68. Text Justification](https://leetcode.com/problems/text-justification/) | Hard | 6+ months | 45.5 | Todo |  |  |  | [notes](02.%20Strings/04.%20String%20Building%20%26%20Formatting/0068.%20Text%20Justification/0068.%20Text%20Justification.md) |
| 6 | [273. Integer to English Words](https://leetcode.com/problems/integer-to-english-words/) | Hard | 6+ months | 38.0 | Todo |  |  |  | [notes](02.%20Strings/04.%20String%20Building%20%26%20Formatting/0273.%20Integer%20to%20English%20Words/0273.%20Integer%20to%20English%20Words.md) |
| 7 | [271. Encode and Decode Strings](https://leetcode.com/problems/encode-and-decode-strings/) 🔒 | Medium | 6+ months | 6.0 | Todo |  |  |  | [notes](02.%20Strings/04.%20String%20Building%20%26%20Formatting/0271.%20Encode%20and%20Decode%20Strings/0271.%20Encode%20and%20Decode%20Strings.md) |
| 8 | [3163. String Compression III](https://leetcode.com/problems/string-compression-iii/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Strings/04.%20String%20Building%20%26%20Formatting/3163.%20String%20Compression%20III/3163.%20String%20Compression%20III.md) |
| 9 | [1694. Reformat Phone Number](https://leetcode.com/problems/reformat-phone-number/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Strings/04.%20String%20Building%20%26%20Formatting/1694.%20Reformat%20Phone%20Number/1694.%20Reformat%20Phone%20Number.md) |
| 10 | [3614. Process String with Special Operations II](https://leetcode.com/problems/process-string-with-special-operations-ii/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Strings/04.%20String%20Building%20%26%20Formatting/3614.%20Process%20String%20with%20Special%20Operations%20II/3614.%20Process%20String%20with%20Special%20Operations%20II.md) |

### 02.05. Anagrams & Character Counting

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203; | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [242. Valid Anagram](https://leetcode.com/problems/valid-anagram/) | Easy | 3 months | 46.3 | ✅ Solved |  |  |  | [notes](02.%20Strings/05.%20Anagrams%20%26%20Character%20Counting/0242.%20Valid%20Anagram/0242.%20Valid%20Anagram.md) |

### 02.06. String Matching (KMP, Rabin-Karp, Z)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [28. Find the Index of the First Occurrence in a String](https://leetcode.com/problems/find-the-index-of-the-first-occurrence-in-a-string/) | Easy | 3 months | 50.5 | ✅ Solved |  |  |  | [notes](02.%20Strings/06.%20String%20Matching%20%28KMP%2C%20Rabin-Karp%2C%20Z%29/0028.%20Find%20the%20Index%20of%20the%20First%20Occurrence%20in%20a%20String/0028.%20Find%20the%20Index%20of%20the%20First%20Occurrence%20in%20a%20String.md) |
| 2 | [796. Rotate String](https://leetcode.com/problems/rotate-string/) | Easy | 3 months | 30.9 | Todo |  |  |  | [notes](02.%20Strings/06.%20String%20Matching%20%28KMP%2C%20Rabin-Karp%2C%20Z%29/0796.%20Rotate%20String/0796.%20Rotate%20String.md) |
| 3 | [1967. Number of Strings That Appear as Substrings in Word](https://leetcode.com/problems/number-of-strings-that-appear-as-substrings-in-word/) | Easy | 6 months | 19.7 | Todo |  |  |  | [notes](02.%20Strings/06.%20String%20Matching%20%28KMP%2C%20Rabin-Karp%2C%20Z%29/1967.%20Number%20of%20Strings%20That%20Appear%20as%20Substrings%20in%20Word/1967.%20Number%20of%20Strings%20That%20Appear%20as%20Substrings%20in%20Word.md) |
| 4 | [1044. Longest Duplicate Substring](https://leetcode.com/problems/longest-duplicate-substring/) | Hard | 6+ months | 11.8 | Todo |  |  |  | [notes](02.%20Strings/06.%20String%20Matching%20%28KMP%2C%20Rabin-Karp%2C%20Z%29/1044.%20Longest%20Duplicate%20Substring/1044.%20Longest%20Duplicate%20Substring.md) |
| 5 | [459. Repeated Substring Pattern](https://leetcode.com/problems/repeated-substring-pattern/) | Easy | 6+ months | 9.5 | Todo |  |  |  | [notes](02.%20Strings/06.%20String%20Matching%20%28KMP%2C%20Rabin-Karp%2C%20Z%29/0459.%20Repeated%20Substring%20Pattern/0459.%20Repeated%20Substring%20Pattern.md) |
| 6 | [1392. Longest Happy Prefix](https://leetcode.com/problems/longest-happy-prefix/) | Hard | 6+ months | 8.4 | Todo |  |  |  | [notes](02.%20Strings/06.%20String%20Matching%20%28KMP%2C%20Rabin-Karp%2C%20Z%29/1392.%20Longest%20Happy%20Prefix/1392.%20Longest%20Happy%20Prefix.md) |
| 7 | [1408. String Matching in an Array](https://leetcode.com/problems/string-matching-in-an-array/) | Easy | 6+ months | 8.4 | Todo |  |  |  | [notes](02.%20Strings/06.%20String%20Matching%20%28KMP%2C%20Rabin-Karp%2C%20Z%29/1408.%20String%20Matching%20in%20an%20Array/1408.%20String%20Matching%20in%20an%20Array.md) |
| 8 | [214. Shortest Palindrome](https://leetcode.com/problems/shortest-palindrome/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Strings/06.%20String%20Matching%20%28KMP%2C%20Rabin-Karp%2C%20Z%29/0214.%20Shortest%20Palindrome/0214.%20Shortest%20Palindrome.md) |
| 9 | [686. Repeated String Match](https://leetcode.com/problems/repeated-string-match/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Strings/06.%20String%20Matching%20%28KMP%2C%20Rabin-Karp%2C%20Z%29/0686.%20Repeated%20String%20Match/0686.%20Repeated%20String%20Match.md) |
| 10 | [2185. Counting Words With a Given Prefix](https://leetcode.com/problems/counting-words-with-a-given-prefix/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Strings/06.%20String%20Matching%20%28KMP%2C%20Rabin-Karp%2C%20Z%29/2185.%20Counting%20Words%20With%20a%20Given%20Prefix/2185.%20Counting%20Words%20With%20a%20Given%20Prefix.md) |

### 02.07. String Comparison & Sorting

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [14. Longest Common Prefix](https://leetcode.com/problems/longest-common-prefix/) | Easy | 3 months | 59.7 | ✅ Solved |  |  |  | [notes](02.%20Strings/07.%20String%20Comparison%20%26%20Sorting/0014.%20Longest%20Common%20Prefix/0014.%20Longest%20Common%20Prefix.md) |
| 2 | [953. Verifying an Alien Dictionary](https://leetcode.com/problems/verifying-an-alien-dictionary/) | Easy | 6+ months | 40.3 | Todo |  |  |  | [notes](02.%20Strings/07.%20String%20Comparison%20%26%20Sorting/0953.%20Verifying%20an%20Alien%20Dictionary/0953.%20Verifying%20an%20Alien%20Dictionary.md) |
| 3 | [1662. Check If Two String Arrays are Equivalent](https://leetcode.com/problems/check-if-two-string-arrays-are-equivalent/) | Easy | 6+ months | 38.5 | ✅ Solved |  |  |  | [notes](02.%20Strings/07.%20String%20Comparison%20%26%20Sorting/1662.%20Check%20If%20Two%20String%20Arrays%20are%20Equivalent/1662.%20Check%20If%20Two%20String%20Arrays%20are%20Equivalent.md) |
| 4 | [1790. Check if One String Swap Can Make Strings Equal](https://leetcode.com/problems/check-if-one-string-swap-can-make-strings-equal/) | Easy | 6+ months | 37.4 | ✅ Solved |  |  |  | [notes](02.%20Strings/07.%20String%20Comparison%20%26%20Sorting/1790.%20Check%20if%20One%20String%20Swap%20Can%20Make%20Strings%20Equal/1790.%20Check%20if%20One%20String%20Swap%20Can%20Make%20Strings%20Equal.md) |
| 5 | [944. Delete Columns to Make Sorted](https://leetcode.com/problems/delete-columns-to-make-sorted/) | Easy | 6+ months | 13.6 | Todo |  |  |  | [notes](02.%20Strings/07.%20String%20Comparison%20%26%20Sorting/0944.%20Delete%20Columns%20to%20Make%20Sorted/0944.%20Delete%20Columns%20to%20Make%20Sorted.md) |
| 6 | [521. Longest Uncommon Subsequence I](https://leetcode.com/problems/longest-uncommon-subsequence-i/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Strings/07.%20String%20Comparison%20%26%20Sorting/0521.%20Longest%20Uncommon%20Subsequence%20I/0521.%20Longest%20Uncommon%20Subsequence%20I.md) |
| 7 | [859. Buddy Strings](https://leetcode.com/problems/buddy-strings/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Strings/07.%20String%20Comparison%20%26%20Sorting/0859.%20Buddy%20Strings/0859.%20Buddy%20Strings.md) |
| 8 | [3403. Find the Lexicographically Largest String From the Box I](https://leetcode.com/problems/find-the-lexicographically-largest-string-from-the-box-i/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Strings/07.%20String%20Comparison%20%26%20Sorting/3403.%20Find%20the%20Lexicographically%20Largest%20String%20From%20the%20Box%20I/3403.%20Find%20the%20Lexicographically%20Largest%20String%20From%20the%20Box%20I.md) |
| 9 | [2452. Words Within Two Edits of Dictionary](https://leetcode.com/problems/words-within-two-edits-of-dictionary/) | Medium | 6+ months | 36.1 | Todo |  |  |  | [notes](02.%20Strings/07.%20String%20Comparison%20%26%20Sorting/2452.%20Words%20Within%20Two%20Edits%20of%20Dictionary/2452.%20Words%20Within%20Two%20Edits%20of%20Dictionary.md) |

## 03. Two Pointers

54 problems: 23 Easy, 30 Medium, 1 Hard. [Open chapter README](03.%20Two%20Pointers/README.md) · [Back to top](#chapters)

### 03.01. Opposite Ends

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [11. Container With Most Water](https://leetcode.com/problems/container-with-most-water/) | Medium | 30 days | 57.1 | ✅ Solved |  |  |  | [notes](03.%20Two%20Pointers/01.%20Opposite%20Ends/0011.%20Container%20With%20Most%20Water/0011.%20Container%20With%20Most%20Water.md) |
| 2 | [42. Trapping Rain Water](https://leetcode.com/problems/trapping-rain-water/) | Hard | 3 months | 59.5 | ✅ Solved |  |  |  | [notes](03.%20Two%20Pointers/01.%20Opposite%20Ends/0042.%20Trapping%20Rain%20Water/0042.%20Trapping%20Rain%20Water.md) |
| 3 | [344. Reverse String](https://leetcode.com/problems/reverse-string/) | Easy | 3 months | 33.9 | ✅ Solved |  |  |  | [notes](03.%20Two%20Pointers/01.%20Opposite%20Ends/0344.%20Reverse%20String/0344.%20Reverse%20String.md) |
| 4 | [977. Squares of a Sorted Array](https://leetcode.com/problems/squares-of-a-sorted-array/) | Easy | 6 months | 55.1 | ✅ Solved |  |  |  | [notes](03.%20Two%20Pointers/01.%20Opposite%20Ends/0977.%20Squares%20of%20a%20Sorted%20Array/0977.%20Squares%20of%20a%20Sorted%20Array.md) |
| 5 | [881. Boats to Save People](https://leetcode.com/problems/boats-to-save-people/) | Medium | 6 months | 26.7 | ✅ Solved |  |  |  | [notes](03.%20Two%20Pointers/01.%20Opposite%20Ends/0881.%20Boats%20to%20Save%20People/0881.%20Boats%20to%20Save%20People.md) |
| 6 | [633. Sum of Square Numbers](https://leetcode.com/problems/sum-of-square-numbers/) | Medium | 6 months | 20.4 | Todo |  |  |  | [notes](03.%20Two%20Pointers/01.%20Opposite%20Ends/0633.%20Sum%20of%20Square%20Numbers/0633.%20Sum%20of%20Square%20Numbers.md) |
| 7 | [345. Reverse Vowels of a String](https://leetcode.com/problems/reverse-vowels-of-a-string/) | Easy | 6 months | 17.2 | ✅ Solved |  |  |  | [notes](03.%20Two%20Pointers/01.%20Opposite%20Ends/0345.%20Reverse%20Vowels%20of%20a%20String/0345.%20Reverse%20Vowels%20of%20a%20String.md) |
| 8 | [541. Reverse String II](https://leetcode.com/problems/reverse-string-ii/) | Easy | 6 months | 16.9 | ✅ Solved |  |  |  | [notes](03.%20Two%20Pointers/01.%20Opposite%20Ends/0541.%20Reverse%20String%20II/0541.%20Reverse%20String%20II.md) |
| 9 | [1498. Number of Subsequences That Satisfy the Given Sum Condition](https://leetcode.com/problems/number-of-subsequences-that-satisfy-the-given-sum-condition/) | Medium | 6+ months | 11.5 | Todo |  |  |  | [notes](03.%20Two%20Pointers/01.%20Opposite%20Ends/1498.%20Number%20of%20Subsequences%20That%20Satisfy%20the%20Given%20Sum%20Condition/1498.%20Number%20of%20Subsequences%20That%20Satisfy%20the%20Given%20Sum%20Condition.md) |
| 10 | [1750. Minimum Length of String After Deleting Similar Ends](https://leetcode.com/problems/minimum-length-of-string-after-deleting-similar-ends/) | Medium | 6+ months | 9.1 | ✅ Solved |  |  |  | [notes](03.%20Two%20Pointers/01.%20Opposite%20Ends/1750.%20Minimum%20Length%20of%20String%20After%20Deleting%20Similar%20Ends/1750.%20Minimum%20Length%20of%20String%20After%20Deleting%20Similar%20Ends.md) |
| 11 | [557. Reverse Words in a String III](https://leetcode.com/problems/reverse-words-in-a-string-iii/) | Easy | 6+ months | 6.6 | ✅ Solved |  |  |  | [notes](03.%20Two%20Pointers/01.%20Opposite%20Ends/0557.%20Reverse%20Words%20in%20a%20String%20III/0557.%20Reverse%20Words%20in%20a%20String%20III.md) |
| 12 | [360. Sort Transformed Array](https://leetcode.com/problems/sort-transformed-array/) 🔒 | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](03.%20Two%20Pointers/01.%20Opposite%20Ends/0360.%20Sort%20Transformed%20Array/0360.%20Sort%20Transformed%20Array.md) |
| 13 | [948. Bag of Tokens](https://leetcode.com/problems/bag-of-tokens/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](03.%20Two%20Pointers/01.%20Opposite%20Ends/0948.%20Bag%20of%20Tokens/0948.%20Bag%20of%20Tokens.md) |
| 14 | [581. Shortest Unsorted Continuous Subarray](https://leetcode.com/problems/shortest-unsorted-continuous-subarray/) | Medium | 6+ months | 5.7 | Todo |  |  |  | [notes](03.%20Two%20Pointers/01.%20Opposite%20Ends/0581.%20Shortest%20Unsorted%20Continuous%20Subarray/0581.%20Shortest%20Unsorted%20Continuous%20Subarray.md) |
| 15 | [917. Reverse Only Letters](https://leetcode.com/problems/reverse-only-letters/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](03.%20Two%20Pointers/01.%20Opposite%20Ends/0917.%20Reverse%20Only%20Letters/0917.%20Reverse%20Only%20Letters.md) |

### 03.02. Same Direction (Read-Write)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [26. Remove Duplicates from Sorted Array](https://leetcode.com/problems/remove-duplicates-from-sorted-array/) | Easy | 3 months | 67.4 | ✅ Solved |  |  |  | [notes](03.%20Two%20Pointers/02.%20Same%20Direction%20%28Read-Write%29/0026.%20Remove%20Duplicates%20from%20Sorted%20Array/0026.%20Remove%20Duplicates%20from%20Sorted%20Array.md) |
| 2 | [283. Move Zeroes](https://leetcode.com/problems/move-zeroes/) | Easy | 3 months | 59.5 | ✅ Solved |  |  |  | [notes](03.%20Two%20Pointers/02.%20Same%20Direction%20%28Read-Write%29/0283.%20Move%20Zeroes/0283.%20Move%20Zeroes.md) |
| 3 | [80. Remove Duplicates from Sorted Array II](https://leetcode.com/problems/remove-duplicates-from-sorted-array-ii/) | Medium | 3 months | 47.7 | Todo |  |  |  | [notes](03.%20Two%20Pointers/02.%20Same%20Direction%20%28Read-Write%29/0080.%20Remove%20Duplicates%20from%20Sorted%20Array%20II/0080.%20Remove%20Duplicates%20from%20Sorted%20Array%20II.md) |
| 4 | [27. Remove Element](https://leetcode.com/problems/remove-element/) | Easy | 3 months | 35.4 | ✅ Solved |  |  |  | [notes](03.%20Two%20Pointers/02.%20Same%20Direction%20%28Read-Write%29/0027.%20Remove%20Element/0027.%20Remove%20Element.md) |
| 5 | [443. String Compression](https://leetcode.com/problems/string-compression/) | Medium | 6 months | 37.5 | Todo |  |  |  | [notes](03.%20Two%20Pointers/02.%20Same%20Direction%20%28Read-Write%29/0443.%20String%20Compression/0443.%20String%20Compression.md) |
| 6 | [2149. Rearrange Array Elements by Sign](https://leetcode.com/problems/rearrange-array-elements-by-sign/) | Medium | 6 months | 25.1 | ✅ Solved |  |  |  | [notes](03.%20Two%20Pointers/02.%20Same%20Direction%20%28Read-Write%29/2149.%20Rearrange%20Array%20Elements%20by%20Sign/2149.%20Rearrange%20Array%20Elements%20by%20Sign.md) |
| 7 | [277. Find the Celebrity](https://leetcode.com/problems/find-the-celebrity/) 🔒 | Medium | 6+ months | 37.4 | Todo |  |  |  | [notes](03.%20Two%20Pointers/02.%20Same%20Direction%20%28Read-Write%29/0277.%20Find%20the%20Celebrity/0277.%20Find%20the%20Celebrity.md) |
| 8 | [161. One Edit Distance](https://leetcode.com/problems/one-edit-distance/) 🔒 | Medium | 6+ months | 36.1 | Todo |  |  |  | [notes](03.%20Two%20Pointers/02.%20Same%20Direction%20%28Read-Write%29/0161.%20One%20Edit%20Distance/0161.%20One%20Edit%20Distance.md) |
| 9 | [844. Backspace String Compare](https://leetcode.com/problems/backspace-string-compare/) | Easy | 6+ months | 13.5 | ✅ Solved |  |  |  | [notes](03.%20Two%20Pointers/02.%20Same%20Direction%20%28Read-Write%29/0844.%20Backspace%20String%20Compare/0844.%20Backspace%20String%20Compare.md) |
| 10 | [838. Push Dominoes](https://leetcode.com/problems/push-dominoes/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](03.%20Two%20Pointers/02.%20Same%20Direction%20%28Read-Write%29/0838.%20Push%20Dominoes/0838.%20Push%20Dominoes.md) |
| 11 | [845. Longest Mountain in Array](https://leetcode.com/problems/longest-mountain-in-array/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](03.%20Two%20Pointers/02.%20Same%20Direction%20%28Read-Write%29/0845.%20Longest%20Mountain%20in%20Array/0845.%20Longest%20Mountain%20in%20Array.md) |
| 12 | [2109. Adding Spaces to a String](https://leetcode.com/problems/adding-spaces-to-a-string/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](03.%20Two%20Pointers/02.%20Same%20Direction%20%28Read-Write%29/2109.%20Adding%20Spaces%20to%20a%20String/2109.%20Adding%20Spaces%20to%20a%20String.md) |
| 13 | [2200. Find All K-Distant Indices in an Array](https://leetcode.com/problems/find-all-k-distant-indices-in-an-array/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](03.%20Two%20Pointers/02.%20Same%20Direction%20%28Read-Write%29/2200.%20Find%20All%20K-Distant%20Indices%20in%20an%20Array/2200.%20Find%20All%20K-Distant%20Indices%20in%20an%20Array.md) |
| 14 | [2337. Move Pieces to Obtain a String](https://leetcode.com/problems/move-pieces-to-obtain-a-string/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](03.%20Two%20Pointers/02.%20Same%20Direction%20%28Read-Write%29/2337.%20Move%20Pieces%20to%20Obtain%20a%20String/2337.%20Move%20Pieces%20to%20Obtain%20a%20String.md) |
| 15 | [2460. Apply Operations to an Array](https://leetcode.com/problems/apply-operations-to-an-array/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](03.%20Two%20Pointers/02.%20Same%20Direction%20%28Read-Write%29/2460.%20Apply%20Operations%20to%20an%20Array/2460.%20Apply%20Operations%20to%20an%20Array.md) |
| 16 | [1826. Faulty Sensor](https://leetcode.com/problems/faulty-sensor/) 🔒 | Easy | 6+ months | 36.1 | Todo |  |  |  | [notes](03.%20Two%20Pointers/02.%20Same%20Direction%20%28Read-Write%29/1826.%20Faulty%20Sensor/1826.%20Faulty%20Sensor.md) |
| 17 | [3940. Limit Occurrences in Sorted Array](https://leetcode.com/problems/limit-occurrences-in-sorted-array/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](03.%20Two%20Pointers/02.%20Same%20Direction%20%28Read-Write%29/3940.%20Limit%20Occurrences%20in%20Sorted%20Array/3940.%20Limit%20Occurrences%20in%20Sorted%20Array.md) |

### 03.03. Two Sum & K-Sum Variants

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [15. 3Sum](https://leetcode.com/problems/3sum/) | Medium | 3 months | 68.0 | ✅ Solved |  |  |  | [notes](03.%20Two%20Pointers/03.%20Two%20Sum%20%26%20K-Sum%20Variants/0015.%203Sum/0015.%203Sum.md) |
| 2 | [16. 3Sum Closest](https://leetcode.com/problems/3sum-closest/) | Medium | 3 months | 42.1 | Todo |  |  |  | [notes](03.%20Two%20Pointers/03.%20Two%20Sum%20%26%20K-Sum%20Variants/0016.%203Sum%20Closest/0016.%203Sum%20Closest.md) |
| 3 | [167. Two Sum II - Input Array Is Sorted](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted/) | Medium | 6 months | 41.4 | ✅ Solved |  |  |  | [notes](03.%20Two%20Pointers/03.%20Two%20Sum%20%26%20K-Sum%20Variants/0167.%20Two%20Sum%20II%20-%20Input%20Array%20Is%20Sorted/0167.%20Two%20Sum%20II%20-%20Input%20Array%20Is%20Sorted.md) |
| 4 | [18. 4Sum](https://leetcode.com/problems/4sum/) | Medium | 6+ months | 43.6 | ✅ Solved |  |  |  | [notes](03.%20Two%20Pointers/03.%20Two%20Sum%20%26%20K-Sum%20Variants/0018.%204Sum/0018.%204Sum.md) |
| 5 | [2824. Count Pairs Whose Sum is Less than Target](https://leetcode.com/problems/count-pairs-whose-sum-is-less-than-target/) | Easy | 6+ months | 37.4 | ✅ Solved |  |  |  | [notes](03.%20Two%20Pointers/03.%20Two%20Sum%20%26%20K-Sum%20Variants/2824.%20Count%20Pairs%20Whose%20Sum%20is%20Less%20than%20Target/2824.%20Count%20Pairs%20Whose%20Sum%20is%20Less%20than%20Target.md) |
| 6 | [611. Valid Triangle Number](https://leetcode.com/problems/valid-triangle-number/) | Medium | 6+ months | 12.0 | Todo |  |  |  | [notes](03.%20Two%20Pointers/03.%20Two%20Sum%20%26%20K-Sum%20Variants/0611.%20Valid%20Triangle%20Number/0611.%20Valid%20Triangle%20Number.md) |
| 7 | [1679. Max Number of K-Sum Pairs](https://leetcode.com/problems/max-number-of-k-sum-pairs/) | Medium | 6+ months | 11.8 | Todo |  |  |  | [notes](03.%20Two%20Pointers/03.%20Two%20Sum%20%26%20K-Sum%20Variants/1679.%20Max%20Number%20of%20K-Sum%20Pairs/1679.%20Max%20Number%20of%20K-Sum%20Pairs.md) |
| 8 | [259. 3Sum Smaller](https://leetcode.com/problems/3sum-smaller/) 🔒 | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](03.%20Two%20Pointers/03.%20Two%20Sum%20%26%20K-Sum%20Variants/0259.%203Sum%20Smaller/0259.%203Sum%20Smaller.md) |
| 9 | [923. 3Sum With Multiplicity](https://leetcode.com/problems/3sum-with-multiplicity/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](03.%20Two%20Pointers/03.%20Two%20Sum%20%26%20K-Sum%20Variants/0923.%203Sum%20With%20Multiplicity/0923.%203Sum%20With%20Multiplicity.md) |
| 10 | [2563. Count the Number of Fair Pairs](https://leetcode.com/problems/count-the-number-of-fair-pairs/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](03.%20Two%20Pointers/03.%20Two%20Sum%20%26%20K-Sum%20Variants/2563.%20Count%20the%20Number%20of%20Fair%20Pairs/2563.%20Count%20the%20Number%20of%20Fair%20Pairs.md) |

### 03.04. Merge Two Sorted Sequences

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [88. Merge Sorted Array](https://leetcode.com/problems/merge-sorted-array/) | Easy | 3 months | 83.8 | ✅ Solved |  |  |  | [notes](03.%20Two%20Pointers/04.%20Merge%20Two%20Sorted%20Sequences/0088.%20Merge%20Sorted%20Array/0088.%20Merge%20Sorted%20Array.md) |
| 2 | [1768. Merge Strings Alternately](https://leetcode.com/problems/merge-strings-alternately/) | Easy | 6 months | 34.3 | ✅ Solved |  |  |  | [notes](03.%20Two%20Pointers/04.%20Merge%20Two%20Sorted%20Sequences/1768.%20Merge%20Strings%20Alternately/1768.%20Merge%20Strings%20Alternately.md) |
| 3 | [1868. Product of Two Run-Length Encoded Arrays](https://leetcode.com/problems/product-of-two-run-length-encoded-arrays/) 🔒 | Medium | 6+ months | 47.0 | Todo |  |  |  | [notes](03.%20Two%20Pointers/04.%20Merge%20Two%20Sorted%20Sequences/1868.%20Product%20of%20Two%20Run-Length%20Encoded%20Arrays/1868.%20Product%20of%20Two%20Run-Length%20Encoded%20Arrays.md) |
| 4 | [2570. Merge Two 2D Arrays by Summing Values](https://leetcode.com/problems/merge-two-2d-arrays-by-summing-values/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](03.%20Two%20Pointers/04.%20Merge%20Two%20Sorted%20Sequences/2570.%20Merge%20Two%202D%20Arrays%20by%20Summing%20Values/2570.%20Merge%20Two%202D%20Arrays%20by%20Summing%20Values.md) |
| 5 | [1213. Intersection of Three Sorted Arrays](https://leetcode.com/problems/intersection-of-three-sorted-arrays/) 🔒 | Easy | 6+ months | 37.0 | Todo |  |  |  | [notes](03.%20Two%20Pointers/04.%20Merge%20Two%20Sorted%20Sequences/1213.%20Intersection%20of%20Three%20Sorted%20Arrays/1213.%20Intersection%20of%20Three%20Sorted%20Arrays.md) |

### 03.05. Partitioning (Dutch Flag)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [75. Sort Colors](https://leetcode.com/problems/sort-colors/) | Medium | 6 months | 56.8 | ✅ Solved |  |  |  | [notes](03.%20Two%20Pointers/05.%20Partitioning%20%28Dutch%20Flag%29/0075.%20Sort%20Colors/0075.%20Sort%20Colors.md) |
| 2 | [905. Sort Array By Parity](https://leetcode.com/problems/sort-array-by-parity/) | Easy | 6+ months | 33.9 | ✅ Solved |  |  |  | [notes](03.%20Two%20Pointers/05.%20Partitioning%20%28Dutch%20Flag%29/0905.%20Sort%20Array%20By%20Parity/0905.%20Sort%20Array%20By%20Parity.md) |
| 3 | [2161. Partition Array According to Given Pivot](https://leetcode.com/problems/partition-array-according-to-given-pivot/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](03.%20Two%20Pointers/05.%20Partitioning%20%28Dutch%20Flag%29/2161.%20Partition%20Array%20According%20to%20Given%20Pivot/2161.%20Partition%20Array%20According%20to%20Given%20Pivot.md) |

### 03.06. Subsequence Matching

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [408. Valid Word Abbreviation](https://leetcode.com/problems/valid-word-abbreviation/) 🔒 | Easy | 30 days | 97.3 | Todo |  |  |  | [notes](03.%20Two%20Pointers/06.%20Subsequence%20Matching/0408.%20Valid%20Word%20Abbreviation/0408.%20Valid%20Word%20Abbreviation.md) |
| 2 | [392. Is Subsequence](https://leetcode.com/problems/is-subsequence/) | Easy | 6 months | 31.7 | ✅ Solved |  |  |  | [notes](03.%20Two%20Pointers/06.%20Subsequence%20Matching/0392.%20Is%20Subsequence/0392.%20Is%20Subsequence.md) |
| 3 | [792. Number of Matching Subsequences](https://leetcode.com/problems/number-of-matching-subsequences/) | Medium | 6+ months | 9.0 | Todo |  |  |  | [notes](03.%20Two%20Pointers/06.%20Subsequence%20Matching/0792.%20Number%20of%20Matching%20Subsequences/0792.%20Number%20of%20Matching%20Subsequences.md) |
| 4 | [925. Long Pressed Name](https://leetcode.com/problems/long-pressed-name/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](03.%20Two%20Pointers/06.%20Subsequence%20Matching/0925.%20Long%20Pressed%20Name/0925.%20Long%20Pressed%20Name.md) |

## 04. Sliding Window

57 problems: 9 Easy, 41 Medium, 7 Hard. [Open chapter README](04.%20Sliding%20Window/README.md) · [Back to top](#chapters)

### 04.01. Fixed Size Window

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [219. Contains Duplicate II](https://leetcode.com/problems/contains-duplicate-ii/) | Easy | 3 months | 53.9 | ✅ Solved |  |  |  | [notes](04.%20Sliding%20Window/01.%20Fixed%20Size%20Window/0219.%20Contains%20Duplicate%20II/0219.%20Contains%20Duplicate%20II.md) |
| 2 | [643. Maximum Average Subarray I](https://leetcode.com/problems/maximum-average-subarray-i/) | Easy | 6 months | 40.8 | ✅ Solved |  |  |  | [notes](04.%20Sliding%20Window/01.%20Fixed%20Size%20Window/0643.%20Maximum%20Average%20Subarray%20I/0643.%20Maximum%20Average%20Subarray%20I.md) |
| 3 | [1456. Maximum Number of Vowels in a Substring of Given Length](https://leetcode.com/problems/maximum-number-of-vowels-in-a-substring-of-given-length/) | Medium | 6 months | 10.5 | Todo |  |  |  | [notes](04.%20Sliding%20Window/01.%20Fixed%20Size%20Window/1456.%20Maximum%20Number%20of%20Vowels%20in%20a%20Substring%20of%20Given%20Length/1456.%20Maximum%20Number%20of%20Vowels%20in%20a%20Substring%20of%20Given%20Length.md) |
| 4 | [1423. Maximum Points You Can Obtain from Cards](https://leetcode.com/problems/maximum-points-you-can-obtain-from-cards/) | Medium | 6+ months | 28.7 | ✅ Solved |  |  |  | [notes](04.%20Sliding%20Window/01.%20Fixed%20Size%20Window/1423.%20Maximum%20Points%20You%20Can%20Obtain%20from%20Cards/1423.%20Maximum%20Points%20You%20Can%20Obtain%20from%20Cards.md) |
| 5 | [187. Repeated DNA Sequences](https://leetcode.com/problems/repeated-dna-sequences/) | Medium | 6+ months | 22.6 | Todo |  |  |  | [notes](04.%20Sliding%20Window/01.%20Fixed%20Size%20Window/0187.%20Repeated%20DNA%20Sequences/0187.%20Repeated%20DNA%20Sequences.md) |
| 6 | [1888. Minimum Number of Flips to Make the Binary String Alternating](https://leetcode.com/problems/minimum-number-of-flips-to-make-the-binary-string-alternating/) | Medium | 6+ months | 12.9 | Todo |  |  |  | [notes](04.%20Sliding%20Window/01.%20Fixed%20Size%20Window/1888.%20Minimum%20Number%20of%20Flips%20to%20Make%20the%20Binary%20String%20Alternating/1888.%20Minimum%20Number%20of%20Flips%20to%20Make%20the%20Binary%20String%20Alternating.md) |
| 7 | [3652. Best Time to Buy and Sell Stock using Strategy](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-using-strategy/) | Medium | 6+ months | 10.5 | Todo |  |  |  | [notes](04.%20Sliding%20Window/01.%20Fixed%20Size%20Window/3652.%20Best%20Time%20to%20Buy%20and%20Sell%20Stock%20using%20Strategy/3652.%20Best%20Time%20to%20Buy%20and%20Sell%20Stock%20using%20Strategy.md) |
| 8 | [1652. Defuse the Bomb](https://leetcode.com/problems/defuse-the-bomb/) | Easy | 6+ months | 9.0 | Todo |  |  |  | [notes](04.%20Sliding%20Window/01.%20Fixed%20Size%20Window/1652.%20Defuse%20the%20Bomb/1652.%20Defuse%20the%20Bomb.md) |
| 9 | [1052. Grumpy Bookstore Owner](https://leetcode.com/problems/grumpy-bookstore-owner/) | Medium | 6+ months | 6.1 | Todo |  |  |  | [notes](04.%20Sliding%20Window/01.%20Fixed%20Size%20Window/1052.%20Grumpy%20Bookstore%20Owner/1052.%20Grumpy%20Bookstore%20Owner.md) |
| 10 | [2090. K Radius Subarray Averages](https://leetcode.com/problems/k-radius-subarray-averages/) | Medium | 6+ months | 5.8 | Todo |  |  |  | [notes](04.%20Sliding%20Window/01.%20Fixed%20Size%20Window/2090.%20K%20Radius%20Subarray%20Averages/2090.%20K%20Radius%20Subarray%20Averages.md) |
| 11 | [1461. Check If a String Contains All Binary Codes of Size K](https://leetcode.com/problems/check-if-a-string-contains-all-binary-codes-of-size-k/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Sliding%20Window/01.%20Fixed%20Size%20Window/1461.%20Check%20If%20a%20String%20Contains%20All%20Binary%20Codes%20of%20Size%20K/1461.%20Check%20If%20a%20String%20Contains%20All%20Binary%20Codes%20of%20Size%20K.md) |
| 12 | [1984. Minimum Difference Between Highest and Lowest of K Scores](https://leetcode.com/problems/minimum-difference-between-highest-and-lowest-of-k-scores/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Sliding%20Window/01.%20Fixed%20Size%20Window/1984.%20Minimum%20Difference%20Between%20Highest%20and%20Lowest%20of%20K%20Scores/1984.%20Minimum%20Difference%20Between%20Highest%20and%20Lowest%20of%20K%20Scores.md) |
| 13 | [2379. Minimum Recolors to Get K Consecutive Black Blocks](https://leetcode.com/problems/minimum-recolors-to-get-k-consecutive-black-blocks/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Sliding%20Window/01.%20Fixed%20Size%20Window/2379.%20Minimum%20Recolors%20to%20Get%20K%20Consecutive%20Black%20Blocks/2379.%20Minimum%20Recolors%20to%20Get%20K%20Consecutive%20Black%20Blocks.md) |
| 14 | [2461. Maximum Sum of Distinct Subarrays With Length K](https://leetcode.com/problems/maximum-sum-of-distinct-subarrays-with-length-k/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Sliding%20Window/01.%20Fixed%20Size%20Window/2461.%20Maximum%20Sum%20of%20Distinct%20Subarrays%20With%20Length%20K/2461.%20Maximum%20Sum%20of%20Distinct%20Subarrays%20With%20Length%20K.md) |
| 15 | [2653. Sliding Subarray Beauty](https://leetcode.com/problems/sliding-subarray-beauty/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Sliding%20Window/01.%20Fixed%20Size%20Window/2653.%20Sliding%20Subarray%20Beauty/2653.%20Sliding%20Subarray%20Beauty.md) |
| 16 | [3318. Find X-Sum of All K-Long Subarrays I](https://leetcode.com/problems/find-x-sum-of-all-k-long-subarrays-i/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Sliding%20Window/01.%20Fixed%20Size%20Window/3318.%20Find%20X-Sum%20of%20All%20K-Long%20Subarrays%20I/3318.%20Find%20X-Sum%20of%20All%20K-Long%20Subarrays%20I.md) |
| 17 | [3439. Reschedule Meetings for Maximum Free Time I](https://leetcode.com/problems/reschedule-meetings-for-maximum-free-time-i/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Sliding%20Window/01.%20Fixed%20Size%20Window/3439.%20Reschedule%20Meetings%20for%20Maximum%20Free%20Time%20I/3439.%20Reschedule%20Meetings%20for%20Maximum%20Free%20Time%20I.md) |
| 18 | [1040. Moving Stones Until Consecutive II](https://leetcode.com/problems/moving-stones-until-consecutive-ii/) | Medium | 6+ months | 36.1 | Todo |  |  |  | [notes](04.%20Sliding%20Window/01.%20Fixed%20Size%20Window/1040.%20Moving%20Stones%20Until%20Consecutive%20II/1040.%20Moving%20Stones%20Until%20Consecutive%20II.md) |
| 19 | [1343. Number of Sub-arrays of Size K and Average Greater than or Equal to Threshold](https://leetcode.com/problems/number-of-sub-arrays-of-size-k-and-average-greater-than-or-equal-to-threshold/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Sliding%20Window/01.%20Fixed%20Size%20Window/1343.%20Number%20of%20Sub-arrays%20of%20Size%20K%20and%20Average%20Greater%20than%20or%20Equal%20to%20Threshold/1343.%20Number%20of%20Sub-arrays%20of%20Size%20K%20and%20Average%20Greater%20than%20or%20Equal%20to%20Threshold.md) |
| 20 | [1876. Substrings of Size Three with Distinct Characters](https://leetcode.com/problems/substrings-of-size-three-with-distinct-characters/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Sliding%20Window/01.%20Fixed%20Size%20Window/1876.%20Substrings%20of%20Size%20Three%20with%20Distinct%20Characters/1876.%20Substrings%20of%20Size%20Three%20with%20Distinct%20Characters.md) |

### 04.02. Variable Window - Longest

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [1004. Max Consecutive Ones III](https://leetcode.com/problems/max-consecutive-ones-iii/) | Medium | 3 months | 76.0 | ✅ Solved |  |  |  | [notes](04.%20Sliding%20Window/02.%20Variable%20Window%20-%20Longest/1004.%20Max%20Consecutive%20Ones%20III/1004.%20Max%20Consecutive%20Ones%20III.md) |
| 2 | [3. Longest Substring Without Repeating Characters](https://leetcode.com/problems/longest-substring-without-repeating-characters/) | Medium | 3 months | 63.4 | ✅ Solved |  |  |  | [notes](04.%20Sliding%20Window/02.%20Variable%20Window%20-%20Longest/0003.%20Longest%20Substring%20Without%20Repeating%20Characters/0003.%20Longest%20Substring%20Without%20Repeating%20Characters.md) |
| 3 | [904. Fruit Into Baskets](https://leetcode.com/problems/fruit-into-baskets/) | Medium | 3 months | 34.8 | ✅ Solved |  |  |  | [notes](04.%20Sliding%20Window/02.%20Variable%20Window%20-%20Longest/0904.%20Fruit%20Into%20Baskets/0904.%20Fruit%20Into%20Baskets.md) |
| 4 | [713. Subarray Product Less Than K](https://leetcode.com/problems/subarray-product-less-than-k/) | Medium | 3 months | 33.7 | ✅ Solved |  |  |  | [notes](04.%20Sliding%20Window/02.%20Variable%20Window%20-%20Longest/0713.%20Subarray%20Product%20Less%20Than%20K/0713.%20Subarray%20Product%20Less%20Than%20K.md) |
| 5 | [1477. Find Two Non-overlapping Sub-arrays Each With Target Sum](https://leetcode.com/problems/find-two-non-overlapping-sub-arrays-each-with-target-sum/) | Medium | 3 months | 5.0 | Todo |  |  |  | [notes](04.%20Sliding%20Window/02.%20Variable%20Window%20-%20Longest/1477.%20Find%20Two%20Non-overlapping%20Sub-arrays%20Each%20With%20Target%20Sum/1477.%20Find%20Two%20Non-overlapping%20Sub-arrays%20Each%20With%20Target%20Sum.md) |
| 6 | [1838. Frequency of the Most Frequent Element](https://leetcode.com/problems/frequency-of-the-most-frequent-element/) | Medium | 6 months | 28.1 | Todo |  |  |  | [notes](04.%20Sliding%20Window/02.%20Variable%20Window%20-%20Longest/1838.%20Frequency%20of%20the%20Most%20Frequent%20Element/1838.%20Frequency%20of%20the%20Most%20Frequent%20Element.md) |
| 7 | [1493. Longest Subarray of 1's After Deleting One Element](https://leetcode.com/problems/longest-subarray-of-1s-after-deleting-one-element/) | Medium | 6+ months | 10.3 | Todo |  |  |  | [notes](04.%20Sliding%20Window/02.%20Variable%20Window%20-%20Longest/1493.%20Longest%20Subarray%20of%201%27s%20After%20Deleting%20One%20Element/1493.%20Longest%20Subarray%20of%201%27s%20After%20Deleting%20One%20Element.md) |
| 8 | [2779. Maximum Beauty of an Array After Applying Operation](https://leetcode.com/problems/maximum-beauty-of-an-array-after-applying-operation/) | Medium | 6+ months | 9.7 | Todo |  |  |  | [notes](04.%20Sliding%20Window/02.%20Variable%20Window%20-%20Longest/2779.%20Maximum%20Beauty%20of%20an%20Array%20After%20Applying%20Operation/2779.%20Maximum%20Beauty%20of%20an%20Array%20After%20Applying%20Operation.md) |
| 9 | [487. Max Consecutive Ones II](https://leetcode.com/problems/max-consecutive-ones-ii/) 🔒 | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Sliding%20Window/02.%20Variable%20Window%20-%20Longest/0487.%20Max%20Consecutive%20Ones%20II/0487.%20Max%20Consecutive%20Ones%20II.md) |
| 10 | [1695. Maximum Erasure Value](https://leetcode.com/problems/maximum-erasure-value/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Sliding%20Window/02.%20Variable%20Window%20-%20Longest/1695.%20Maximum%20Erasure%20Value/1695.%20Maximum%20Erasure%20Value.md) |
| 11 | [2024. Maximize the Confusion of an Exam](https://leetcode.com/problems/maximize-the-confusion-of-an-exam/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Sliding%20Window/02.%20Variable%20Window%20-%20Longest/2024.%20Maximize%20the%20Confusion%20of%20an%20Exam/2024.%20Maximize%20the%20Confusion%20of%20an%20Exam.md) |
| 12 | [2302. Count Subarrays With Score Less Than K](https://leetcode.com/problems/count-subarrays-with-score-less-than-k/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Sliding%20Window/02.%20Variable%20Window%20-%20Longest/2302.%20Count%20Subarrays%20With%20Score%20Less%20Than%20K/2302.%20Count%20Subarrays%20With%20Score%20Less%20Than%20K.md) |
| 13 | [2401. Longest Nice Subarray](https://leetcode.com/problems/longest-nice-subarray/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Sliding%20Window/02.%20Variable%20Window%20-%20Longest/2401.%20Longest%20Nice%20Subarray/2401.%20Longest%20Nice%20Subarray.md) |
| 14 | [2444. Count Subarrays With Fixed Bounds](https://leetcode.com/problems/count-subarrays-with-fixed-bounds/) | Hard | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](04.%20Sliding%20Window/02.%20Variable%20Window%20-%20Longest/2444.%20Count%20Subarrays%20With%20Fixed%20Bounds/2444.%20Count%20Subarrays%20With%20Fixed%20Bounds.md) |
| 15 | [2760. Longest Even Odd Subarray With Threshold](https://leetcode.com/problems/longest-even-odd-subarray-with-threshold/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Sliding%20Window/02.%20Variable%20Window%20-%20Longest/2760.%20Longest%20Even%20Odd%20Subarray%20With%20Threshold/2760.%20Longest%20Even%20Odd%20Subarray%20With%20Threshold.md) |
| 16 | [2781. Length of the Longest Valid Substring](https://leetcode.com/problems/length-of-the-longest-valid-substring/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Sliding%20Window/02.%20Variable%20Window%20-%20Longest/2781.%20Length%20of%20the%20Longest%20Valid%20Substring/2781.%20Length%20of%20the%20Longest%20Valid%20Substring.md) |
| 17 | [2962. Count Subarrays Where Max Element Appears at Least K Times](https://leetcode.com/problems/count-subarrays-where-max-element-appears-at-least-k-times/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](04.%20Sliding%20Window/02.%20Variable%20Window%20-%20Longest/2962.%20Count%20Subarrays%20Where%20Max%20Element%20Appears%20at%20Least%20K%20Times/2962.%20Count%20Subarrays%20Where%20Max%20Element%20Appears%20at%20Least%20K%20Times.md) |
| 18 | [3234. Count the Number of Substrings With Dominant Ones](https://leetcode.com/problems/count-the-number-of-substrings-with-dominant-ones/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Sliding%20Window/02.%20Variable%20Window%20-%20Longest/3234.%20Count%20the%20Number%20of%20Substrings%20With%20Dominant%20Ones/3234.%20Count%20the%20Number%20of%20Substrings%20With%20Dominant%20Ones.md) |
| 19 | [3634. Minimum Removals to Balance Array](https://leetcode.com/problems/minimum-removals-to-balance-array/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](04.%20Sliding%20Window/02.%20Variable%20Window%20-%20Longest/3634.%20Minimum%20Removals%20to%20Balance%20Array/3634.%20Minimum%20Removals%20to%20Balance%20Array.md) |

### 04.03. Variable Window - Shortest

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [76. Minimum Window Substring](https://leetcode.com/problems/minimum-window-substring/) | Hard | 6 months | 73.0 | ✅ Solved |  |  |  | [notes](04.%20Sliding%20Window/03.%20Variable%20Window%20-%20Shortest/0076.%20Minimum%20Window%20Substring/0076.%20Minimum%20Window%20Substring.md) |
| 2 | [209. Minimum Size Subarray Sum](https://leetcode.com/problems/minimum-size-subarray-sum/) | Medium | 6 months | 50.6 | ✅ Solved |  |  |  | [notes](04.%20Sliding%20Window/03.%20Variable%20Window%20-%20Shortest/0209.%20Minimum%20Size%20Subarray%20Sum/0209.%20Minimum%20Size%20Subarray%20Sum.md) |

### 04.04. Window with Frequency Map

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [567. Permutation in String](https://leetcode.com/problems/permutation-in-string/) | Medium | 3 months | 35.6 | Todo |  |  |  | [notes](04.%20Sliding%20Window/04.%20Window%20with%20Frequency%20Map/0567.%20Permutation%20in%20String/0567.%20Permutation%20in%20String.md) |
| 2 | [2747. Count Zero Request Servers](https://leetcode.com/problems/count-zero-request-servers/) | Medium | 3 months | 10.3 | Todo |  |  |  | [notes](04.%20Sliding%20Window/04.%20Window%20with%20Frequency%20Map/2747.%20Count%20Zero%20Request%20Servers/2747.%20Count%20Zero%20Request%20Servers.md) |
| 3 | [424. Longest Repeating Character Replacement](https://leetcode.com/problems/longest-repeating-character-replacement/) | Medium | 6 months | 43.2 | ✅ Solved |  |  |  | [notes](04.%20Sliding%20Window/04.%20Window%20with%20Frequency%20Map/0424.%20Longest%20Repeating%20Character%20Replacement/0424.%20Longest%20Repeating%20Character%20Replacement.md) |
| 4 | [3090. Maximum Length Substring With Two Occurrences](https://leetcode.com/problems/maximum-length-substring-with-two-occurrences/) | Easy | 6 months | 21.8 | Todo |  |  |  | [notes](04.%20Sliding%20Window/04.%20Window%20with%20Frequency%20Map/3090.%20Maximum%20Length%20Substring%20With%20Two%20Occurrences/3090.%20Maximum%20Length%20Substring%20With%20Two%20Occurrences.md) |
| 5 | [1358. Number of Substrings Containing All Three Characters](https://leetcode.com/problems/number-of-substrings-containing-all-three-characters/) | Medium | 6 months | 14.2 | ✅ Solved |  |  |  | [notes](04.%20Sliding%20Window/04.%20Window%20with%20Frequency%20Map/1358.%20Number%20of%20Substrings%20Containing%20All%20Three%20Characters/1358.%20Number%20of%20Substrings%20Containing%20All%20Three%20Characters.md) |
| 6 | [438. Find All Anagrams in a String](https://leetcode.com/problems/find-all-anagrams-in-a-string/) | Medium | 6+ months | 32.4 | Todo |  |  |  | [notes](04.%20Sliding%20Window/04.%20Window%20with%20Frequency%20Map/0438.%20Find%20All%20Anagrams%20in%20a%20String/0438.%20Find%20All%20Anagrams%20in%20a%20String.md) |
| 7 | [159. Longest Substring with At Most Two Distinct Characters](https://leetcode.com/problems/longest-substring-with-at-most-two-distinct-characters/) 🔒 | Medium | 6+ months | 21.2 | ✅ Solved |  |  |  | [notes](04.%20Sliding%20Window/04.%20Window%20with%20Frequency%20Map/0159.%20Longest%20Substring%20with%20At%20Most%20Two%20Distinct%20Characters/0159.%20Longest%20Substring%20with%20At%20Most%20Two%20Distinct%20Characters.md) |
| 8 | [30. Substring with Concatenation of All Words](https://leetcode.com/problems/substring-with-concatenation-of-all-words/) | Hard | 6+ months | 12.9 | Todo |  |  |  | [notes](04.%20Sliding%20Window/04.%20Window%20with%20Frequency%20Map/0030.%20Substring%20with%20Concatenation%20of%20All%20Words/0030.%20Substring%20with%20Concatenation%20of%20All%20Words.md) |
| 9 | [340. Longest Substring with At Most K Distinct Characters](https://leetcode.com/problems/longest-substring-with-at-most-k-distinct-characters/) 🔒 | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](04.%20Sliding%20Window/04.%20Window%20with%20Frequency%20Map/0340.%20Longest%20Substring%20with%20At%20Most%20K%20Distinct%20Characters/0340.%20Longest%20Substring%20with%20At%20Most%20K%20Distinct%20Characters.md) |
| 10 | [1297. Maximum Number of Occurrences of a Substring](https://leetcode.com/problems/maximum-number-of-occurrences-of-a-substring/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Sliding%20Window/04.%20Window%20with%20Frequency%20Map/1297.%20Maximum%20Number%20of%20Occurrences%20of%20a%20Substring/1297.%20Maximum%20Number%20of%20Occurrences%20of%20a%20Substring.md) |
| 11 | [2537. Count the Number of Good Subarrays](https://leetcode.com/problems/count-the-number-of-good-subarrays/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Sliding%20Window/04.%20Window%20with%20Frequency%20Map/2537.%20Count%20the%20Number%20of%20Good%20Subarrays/2537.%20Count%20the%20Number%20of%20Good%20Subarrays.md) |
| 12 | [2799. Count Complete Subarrays in an Array](https://leetcode.com/problems/count-complete-subarrays-in-an-array/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Sliding%20Window/04.%20Window%20with%20Frequency%20Map/2799.%20Count%20Complete%20Subarrays%20in%20an%20Array/2799.%20Count%20Complete%20Subarrays%20in%20an%20Array.md) |

### 04.05. At Most K Trick (Exactly K)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [1248. Count Number of Nice Subarrays](https://leetcode.com/problems/count-number-of-nice-subarrays/) | Medium | 6 months | 17.6 | ✅ Solved |  |  |  | [notes](04.%20Sliding%20Window/05.%20At%20Most%20K%20Trick%20%28Exactly%20K%29/1248.%20Count%20Number%20of%20Nice%20Subarrays/1248.%20Count%20Number%20of%20Nice%20Subarrays.md) |
| 2 | [930. Binary Subarrays With Sum](https://leetcode.com/problems/binary-subarrays-with-sum/) | Medium | 6+ months | 17.3 | ✅ Solved |  |  |  | [notes](04.%20Sliding%20Window/05.%20At%20Most%20K%20Trick%20%28Exactly%20K%29/0930.%20Binary%20Subarrays%20With%20Sum/0930.%20Binary%20Subarrays%20With%20Sum.md) |
| 3 | [3859. Count Subarrays With K Distinct Integers](https://leetcode.com/problems/count-subarrays-with-k-distinct-integers/) | Hard | 6+ months | 5.1 | Todo |  |  |  | [notes](04.%20Sliding%20Window/05.%20At%20Most%20K%20Trick%20%28Exactly%20K%29/3859.%20Count%20Subarrays%20With%20K%20Distinct%20Integers/3859.%20Count%20Subarrays%20With%20K%20Distinct%20Integers.md) |
| 4 | [992. Subarrays with K Different Integers](https://leetcode.com/problems/subarrays-with-k-different-integers/) | Hard | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](04.%20Sliding%20Window/05.%20At%20Most%20K%20Trick%20%28Exactly%20K%29/0992.%20Subarrays%20with%20K%20Different%20Integers/0992.%20Subarrays%20with%20K%20Different%20Integers.md) |

## 05. Prefix Sum

49 problems: 11 Easy, 34 Medium, 4 Hard. [Open chapter README](05.%20Prefix%20Sum/README.md) · [Back to top](#chapters)

### 05.01. 1D Prefix Sum

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [1524. Number of Sub-arrays With Odd Sum](https://leetcode.com/problems/number-of-sub-arrays-with-odd-sum/) | Medium | 3 months | 15.2 | Todo |  |  |  | [notes](05.%20Prefix%20Sum/01.%201D%20Prefix%20Sum/1524.%20Number%20of%20Sub-arrays%20With%20Odd%20Sum/1524.%20Number%20of%20Sub-arrays%20With%20Odd%20Sum.md) |
| 2 | [303. Range Sum Query - Immutable](https://leetcode.com/problems/range-sum-query-immutable/) | Easy | 6 months | 39.3 | ✅ Solved |  |  |  | [notes](05.%20Prefix%20Sum/01.%201D%20Prefix%20Sum/0303.%20Range%20Sum%20Query%20-%20Immutable/0303.%20Range%20Sum%20Query%20-%20Immutable.md) |
| 3 | [1480. Running Sum of 1d Array](https://leetcode.com/problems/running-sum-of-1d-array/) | Easy | 6 months | 18.2 | ✅ Solved |  |  |  | [notes](05.%20Prefix%20Sum/01.%201D%20Prefix%20Sum/1480.%20Running%20Sum%20of%201d%20Array/1480.%20Running%20Sum%20of%201d%20Array.md) |
| 4 | [1732. Find the Highest Altitude](https://leetcode.com/problems/find-the-highest-altitude/) | Easy | 6 months | 14.2 | ✅ Solved |  |  |  | [notes](05.%20Prefix%20Sum/01.%201D%20Prefix%20Sum/1732.%20Find%20the%20Highest%20Altitude/1732.%20Find%20the%20Highest%20Altitude.md) |
| 5 | [2574. Left and Right Sum Differences](https://leetcode.com/problems/left-and-right-sum-differences/) | Easy | 6 months | 5.0 | ✅ Solved |  |  |  | [notes](05.%20Prefix%20Sum/01.%201D%20Prefix%20Sum/2574.%20Left%20and%20Right%20Sum%20Differences/2574.%20Left%20and%20Right%20Sum%20Differences.md) |
| 6 | [528. Random Pick with Weight](https://leetcode.com/problems/random-pick-with-weight/) | Medium | 6+ months | 85.8 | Todo |  |  |  | [notes](05.%20Prefix%20Sum/01.%201D%20Prefix%20Sum/0528.%20Random%20Pick%20with%20Weight/0528.%20Random%20Pick%20with%20Weight.md) |
| 7 | [689. Maximum Sum of 3 Non-Overlapping Subarrays](https://leetcode.com/problems/maximum-sum-of-3-non-overlapping-subarrays/) | Hard | 6+ months | 42.5 | Todo |  |  |  | [notes](05.%20Prefix%20Sum/01.%201D%20Prefix%20Sum/0689.%20Maximum%20Sum%20of%203%20Non-Overlapping%20Subarrays/0689.%20Maximum%20Sum%20of%203%20Non-Overlapping%20Subarrays.md) |
| 8 | [724. Find Pivot Index](https://leetcode.com/problems/find-pivot-index/) | Easy | 6+ months | 40.9 | ✅ Solved |  |  |  | [notes](05.%20Prefix%20Sum/01.%201D%20Prefix%20Sum/0724.%20Find%20Pivot%20Index/0724.%20Find%20Pivot%20Index.md) |
| 9 | [3737. Count Subarrays With Majority Element I](https://leetcode.com/problems/count-subarrays-with-majority-element-i/) | Medium | 6+ months | 8.4 | Todo |  |  |  | [notes](05.%20Prefix%20Sum/01.%201D%20Prefix%20Sum/3737.%20Count%20Subarrays%20With%20Majority%20Element%20I/3737.%20Count%20Subarrays%20With%20Majority%20Element%20I.md) |
| 10 | [2145. Count the Hidden Sequences](https://leetcode.com/problems/count-the-hidden-sequences/) | Medium | 6+ months | 8.0 | Todo |  |  |  | [notes](05.%20Prefix%20Sum/01.%201D%20Prefix%20Sum/2145.%20Count%20the%20Hidden%20Sequences/2145.%20Count%20the%20Hidden%20Sequences.md) |
| 11 | [3494. Find the Minimum Amount of Time to Brew Potions](https://leetcode.com/problems/find-the-minimum-amount-of-time-to-brew-potions/) | Medium | 6+ months | 6.2 | Todo |  |  |  | [notes](05.%20Prefix%20Sum/01.%201D%20Prefix%20Sum/3494.%20Find%20the%20Minimum%20Amount%20of%20Time%20to%20Brew%20Potions/3494.%20Find%20the%20Minimum%20Amount%20of%20Time%20to%20Brew%20Potions.md) |
| 12 | [1413. Minimum Value to Get Positive Step by Step Sum](https://leetcode.com/problems/minimum-value-to-get-positive-step-by-step-sum/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Prefix%20Sum/01.%201D%20Prefix%20Sum/1413.%20Minimum%20Value%20to%20Get%20Positive%20Step%20by%20Step%20Sum/1413.%20Minimum%20Value%20to%20Get%20Positive%20Step%20by%20Step%20Sum.md) |
| 13 | [1422. Maximum Score After Splitting a String](https://leetcode.com/problems/maximum-score-after-splitting-a-string/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](05.%20Prefix%20Sum/01.%201D%20Prefix%20Sum/1422.%20Maximum%20Score%20After%20Splitting%20a%20String/1422.%20Maximum%20Score%20After%20Splitting%20a%20String.md) |
| 14 | [1664. Ways to Make a Fair Array](https://leetcode.com/problems/ways-to-make-a-fair-array/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Prefix%20Sum/01.%201D%20Prefix%20Sum/1664.%20Ways%20to%20Make%20a%20Fair%20Array/1664.%20Ways%20to%20Make%20a%20Fair%20Array.md) |
| 15 | [1685. Sum of Absolute Differences in a Sorted Array](https://leetcode.com/problems/sum-of-absolute-differences-in-a-sorted-array/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Prefix%20Sum/01.%201D%20Prefix%20Sum/1685.%20Sum%20of%20Absolute%20Differences%20in%20a%20Sorted%20Array/1685.%20Sum%20of%20Absolute%20Differences%20in%20a%20Sorted%20Array.md) |
| 16 | [1769. Minimum Number of Operations to Move All Balls to Each Box](https://leetcode.com/problems/minimum-number-of-operations-to-move-all-balls-to-each-box/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Prefix%20Sum/01.%201D%20Prefix%20Sum/1769.%20Minimum%20Number%20of%20Operations%20to%20Move%20All%20Balls%20to%20Each%20Box/1769.%20Minimum%20Number%20of%20Operations%20to%20Move%20All%20Balls%20to%20Each%20Box.md) |
| 17 | [2256. Minimum Average Difference](https://leetcode.com/problems/minimum-average-difference/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Prefix%20Sum/01.%201D%20Prefix%20Sum/2256.%20Minimum%20Average%20Difference/2256.%20Minimum%20Average%20Difference.md) |
| 18 | [2270. Number of Ways to Split Array](https://leetcode.com/problems/number-of-ways-to-split-array/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](05.%20Prefix%20Sum/01.%201D%20Prefix%20Sum/2270.%20Number%20of%20Ways%20to%20Split%20Array/2270.%20Number%20of%20Ways%20to%20Split%20Array.md) |
| 19 | [2483. Minimum Penalty for a Shop](https://leetcode.com/problems/minimum-penalty-for-a-shop/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Prefix%20Sum/01.%201D%20Prefix%20Sum/2483.%20Minimum%20Penalty%20for%20a%20Shop/2483.%20Minimum%20Penalty%20for%20a%20Shop.md) |
| 20 | [2485. Find the Pivot Integer](https://leetcode.com/problems/find-the-pivot-integer/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](05.%20Prefix%20Sum/01.%201D%20Prefix%20Sum/2485.%20Find%20the%20Pivot%20Integer/2485.%20Find%20the%20Pivot%20Integer.md) |
| 21 | [2559. Count Vowel Strings in Ranges](https://leetcode.com/problems/count-vowel-strings-in-ranges/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](05.%20Prefix%20Sum/01.%201D%20Prefix%20Sum/2559.%20Count%20Vowel%20Strings%20in%20Ranges/2559.%20Count%20Vowel%20Strings%20in%20Ranges.md) |
| 22 | [3354. Make Array Elements Equal to Zero](https://leetcode.com/problems/make-array-elements-equal-to-zero/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Prefix%20Sum/01.%201D%20Prefix%20Sum/3354.%20Make%20Array%20Elements%20Equal%20to%20Zero/3354.%20Make%20Array%20Elements%20Equal%20to%20Zero.md) |
| 23 | [3427. Sum of Variable Length Subarrays](https://leetcode.com/problems/sum-of-variable-length-subarrays/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](05.%20Prefix%20Sum/01.%201D%20Prefix%20Sum/3427.%20Sum%20of%20Variable%20Length%20Subarrays/3427.%20Sum%20of%20Variable%20Length%20Subarrays.md) |
| 24 | [3445. Maximum Difference Between Even and Odd Frequency II](https://leetcode.com/problems/maximum-difference-between-even-and-odd-frequency-ii/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Prefix%20Sum/01.%201D%20Prefix%20Sum/3445.%20Maximum%20Difference%20Between%20Even%20and%20Odd%20Frequency%20II/3445.%20Maximum%20Difference%20Between%20Even%20and%20Odd%20Frequency%20II.md) |

### 05.02. Prefix Sum + Hash Map

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [523. Continuous Subarray Sum](https://leetcode.com/problems/continuous-subarray-sum/) | Medium | 3 months | 59.7 | Todo |  |  |  | [notes](05.%20Prefix%20Sum/02.%20Prefix%20Sum%20%2B%20Hash%20Map/0523.%20Continuous%20Subarray%20Sum/0523.%20Continuous%20Subarray%20Sum.md) |
| 2 | [525. Contiguous Array](https://leetcode.com/problems/contiguous-array/) | Medium | 3 months | 53.4 | ✅ Solved |  |  |  | [notes](05.%20Prefix%20Sum/02.%20Prefix%20Sum%20%2B%20Hash%20Map/0525.%20Contiguous%20Array/0525.%20Contiguous%20Array.md) |
| 3 | [560. Subarray Sum Equals K](https://leetcode.com/problems/subarray-sum-equals-k/) | Medium | 6 months | 88.4 | ✅ Solved |  |  |  | [notes](05.%20Prefix%20Sum/02.%20Prefix%20Sum%20%2B%20Hash%20Map/0560.%20Subarray%20Sum%20Equals%20K/0560.%20Subarray%20Sum%20Equals%20K.md) |
| 4 | [974. Subarray Sums Divisible by K](https://leetcode.com/problems/subarray-sums-divisible-by-k/) | Medium | 6 months | 19.0 | Todo |  |  |  | [notes](05.%20Prefix%20Sum/02.%20Prefix%20Sum%20%2B%20Hash%20Map/0974.%20Subarray%20Sums%20Divisible%20by%20K/0974.%20Subarray%20Sums%20Divisible%20by%20K.md) |
| 5 | [325. Maximum Size Subarray Sum Equals k](https://leetcode.com/problems/maximum-size-subarray-sum-equals-k/) 🔒 | Medium | 6+ months | 40.3 | Todo |  |  |  | [notes](05.%20Prefix%20Sum/02.%20Prefix%20Sum%20%2B%20Hash%20Map/0325.%20Maximum%20Size%20Subarray%20Sum%20Equals%20k/0325.%20Maximum%20Size%20Subarray%20Sum%20Equals%20k.md) |
| 6 | [3714. Longest Balanced Substring II](https://leetcode.com/problems/longest-balanced-substring-ii/) | Medium | 6+ months | 11.3 | Todo |  |  |  | [notes](05.%20Prefix%20Sum/02.%20Prefix%20Sum%20%2B%20Hash%20Map/3714.%20Longest%20Balanced%20Substring%20II/3714.%20Longest%20Balanced%20Substring%20II.md) |
| 7 | [3381. Maximum Subarray Sum With Length Divisible by K](https://leetcode.com/problems/maximum-subarray-sum-with-length-divisible-by-k/) | Medium | 6+ months | 5.9 | Todo |  |  |  | [notes](05.%20Prefix%20Sum/02.%20Prefix%20Sum%20%2B%20Hash%20Map/3381.%20Maximum%20Subarray%20Sum%20With%20Length%20Divisible%20by%20K/3381.%20Maximum%20Subarray%20Sum%20With%20Length%20Divisible%20by%20K.md) |
| 8 | [1590. Make Sum Divisible by P](https://leetcode.com/problems/make-sum-divisible-by-p/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Prefix%20Sum/02.%20Prefix%20Sum%20%2B%20Hash%20Map/1590.%20Make%20Sum%20Divisible%20by%20P/1590.%20Make%20Sum%20Divisible%20by%20P.md) |
| 9 | [2615. Sum of Distances](https://leetcode.com/problems/sum-of-distances/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Prefix%20Sum/02.%20Prefix%20Sum%20%2B%20Hash%20Map/2615.%20Sum%20of%20Distances/2615.%20Sum%20of%20Distances.md) |

### 05.03. 2D Prefix Sum

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [304. Range Sum Query 2D - Immutable](https://leetcode.com/problems/range-sum-query-2d-immutable/) | Medium | 6 months | 12.1 | Todo |  |  |  | [notes](05.%20Prefix%20Sum/03.%202D%20Prefix%20Sum/0304.%20Range%20Sum%20Query%202D%20-%20Immutable/0304.%20Range%20Sum%20Query%202D%20-%20Immutable.md) |
| 2 | [1074. Number of Submatrices That Sum to Target](https://leetcode.com/problems/number-of-submatrices-that-sum-to-target/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Prefix%20Sum/03.%202D%20Prefix%20Sum/1074.%20Number%20of%20Submatrices%20That%20Sum%20to%20Target/1074.%20Number%20of%20Submatrices%20That%20Sum%20to%20Target.md) |
| 3 | [2536. Increment Submatrices by One](https://leetcode.com/problems/increment-submatrices-by-one/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Prefix%20Sum/03.%202D%20Prefix%20Sum/2536.%20Increment%20Submatrices%20by%20One/2536.%20Increment%20Submatrices%20by%20One.md) |

### 05.04. Difference Array

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [1109. Corporate Flight Bookings](https://leetcode.com/problems/corporate-flight-bookings/) | Medium | 6 months | 10.0 | Todo |  |  |  | [notes](05.%20Prefix%20Sum/04.%20Difference%20Array/1109.%20Corporate%20Flight%20Bookings/1109.%20Corporate%20Flight%20Bookings.md) |
| 2 | [1094. Car Pooling](https://leetcode.com/problems/car-pooling/) | Medium | 6+ months | 33.6 | Todo |  |  |  | [notes](05.%20Prefix%20Sum/04.%20Difference%20Array/1094.%20Car%20Pooling/1094.%20Car%20Pooling.md) |
| 3 | [1674. Minimum Moves to Make Array Complementary](https://leetcode.com/problems/minimum-moves-to-make-array-complementary/) | Medium | 6+ months | 6.7 | Todo |  |  |  | [notes](05.%20Prefix%20Sum/04.%20Difference%20Array/1674.%20Minimum%20Moves%20to%20Make%20Array%20Complementary/1674.%20Minimum%20Moves%20to%20Make%20Array%20Complementary.md) |
| 4 | [2381. Shifting Letters II](https://leetcode.com/problems/shifting-letters-ii/) | Medium | 6+ months | 6.6 | Todo |  |  |  | [notes](05.%20Prefix%20Sum/04.%20Difference%20Array/2381.%20Shifting%20Letters%20II/2381.%20Shifting%20Letters%20II.md) |
| 5 | [1871. Jump Game VII](https://leetcode.com/problems/jump-game-vii/) | Medium | 6+ months | 6.4 | Todo |  |  |  | [notes](05.%20Prefix%20Sum/04.%20Difference%20Array/1871.%20Jump%20Game%20VII/1871.%20Jump%20Game%20VII.md) |
| 6 | [1854. Maximum Population Year](https://leetcode.com/problems/maximum-population-year/) | Easy | 6+ months | 5.8 | Todo |  |  |  | [notes](05.%20Prefix%20Sum/04.%20Difference%20Array/1854.%20Maximum%20Population%20Year/1854.%20Maximum%20Population%20Year.md) |
| 7 | [3346. Maximum Frequency of an Element After Performing Operations I](https://leetcode.com/problems/maximum-frequency-of-an-element-after-performing-operations-i/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Prefix%20Sum/04.%20Difference%20Array/3346.%20Maximum%20Frequency%20of%20an%20Element%20After%20Performing%20Operations%20I/3346.%20Maximum%20Frequency%20of%20an%20Element%20After%20Performing%20Operations%20I.md) |
| 8 | [3356. Zero Array Transformation II](https://leetcode.com/problems/zero-array-transformation-ii/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Prefix%20Sum/04.%20Difference%20Array/3356.%20Zero%20Array%20Transformation%20II/3356.%20Zero%20Array%20Transformation%20II.md) |
| 9 | [995. Minimum Number of K Consecutive Bit Flips](https://leetcode.com/problems/minimum-number-of-k-consecutive-bit-flips/) | Hard | 6+ months | 5.5 | Todo |  |  |  | [notes](05.%20Prefix%20Sum/04.%20Difference%20Array/0995.%20Minimum%20Number%20of%20K%20Consecutive%20Bit%20Flips/0995.%20Minimum%20Number%20of%20K%20Consecutive%20Bit%20Flips.md) |

### 05.05. Prefix Product & Prefix XOR

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [238. Product of Array Except Self](https://leetcode.com/problems/product-of-array-except-self/) | Medium | 6 months | 53.2 | ✅ Solved |  |  |  | [notes](05.%20Prefix%20Sum/05.%20Prefix%20Product%20%26%20Prefix%20XOR/0238.%20Product%20of%20Array%20Except%20Self/0238.%20Product%20of%20Array%20Except%20Self.md) |
| 2 | [1352. Product of the Last K Numbers](https://leetcode.com/problems/product-of-the-last-k-numbers/) | Medium | 6+ months | 22.6 | Todo |  |  |  | [notes](05.%20Prefix%20Sum/05.%20Prefix%20Product%20%26%20Prefix%20XOR/1352.%20Product%20of%20the%20Last%20K%20Numbers/1352.%20Product%20of%20the%20Last%20K%20Numbers.md) |
| 3 | [1442. Count Triplets That Can Form Two Arrays of Equal XOR](https://leetcode.com/problems/count-triplets-that-can-form-two-arrays-of-equal-xor/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Prefix%20Sum/05.%20Prefix%20Product%20%26%20Prefix%20XOR/1442.%20Count%20Triplets%20That%20Can%20Form%20Two%20Arrays%20of%20Equal%20XOR/1442.%20Count%20Triplets%20That%20Can%20Form%20Two%20Arrays%20of%20Equal%20XOR.md) |
| 4 | [3862. Find the Smallest Balanced Index](https://leetcode.com/problems/find-the-smallest-balanced-index/) | Medium | 6+ months | 36.1 | ✅ Solved |  |  |  | [notes](05.%20Prefix%20Sum/05.%20Prefix%20Product%20%26%20Prefix%20XOR/3862.%20Find%20the%20Smallest%20Balanced%20Index/3862.%20Find%20the%20Smallest%20Balanced%20Index.md) |

## 06. Sorting

32 problems: 15 Easy, 12 Medium, 5 Hard. [Open chapter README](06.%20Sorting/README.md) · [Back to top](#chapters)

### 06.01. Custom Comparator Sorting

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [179. Largest Number](https://leetcode.com/problems/largest-number/) | Medium | 6 months | 28.8 | Todo |  |  |  | [notes](06.%20Sorting/01.%20Custom%20Comparator%20Sorting/0179.%20Largest%20Number/0179.%20Largest%20Number.md) |
| 2 | [2418. Sort the People](https://leetcode.com/problems/sort-the-people/) | Easy | 6+ months | 8.4 | ✅ Solved |  |  |  | [notes](06.%20Sorting/01.%20Custom%20Comparator%20Sorting/2418.%20Sort%20the%20People/2418.%20Sort%20the%20People.md) |
| 3 | [1636. Sort Array by Increasing Frequency](https://leetcode.com/problems/sort-array-by-increasing-frequency/) | Easy | 6+ months | 5.6 | Todo |  |  |  | [notes](06.%20Sorting/01.%20Custom%20Comparator%20Sorting/1636.%20Sort%20Array%20by%20Increasing%20Frequency/1636.%20Sort%20Array%20by%20Increasing%20Frequency.md) |
| 4 | [937. Reorder Data in Log Files](https://leetcode.com/problems/reorder-data-in-log-files/) | Medium | 6+ months | 5.0 | 🟡 Attempted |  |  |  | [notes](06.%20Sorting/01.%20Custom%20Comparator%20Sorting/0937.%20Reorder%20Data%20in%20Log%20Files/0937.%20Reorder%20Data%20in%20Log%20Files.md) |
| 5 | [3606. Coupon Code Validator](https://leetcode.com/problems/coupon-code-validator/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20Sorting/01.%20Custom%20Comparator%20Sorting/3606.%20Coupon%20Code%20Validator/3606.%20Coupon%20Code%20Validator.md) |

### 06.02. Counting & Bucket Sort

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [451. Sort Characters By Frequency](https://leetcode.com/problems/sort-characters-by-frequency/) | Medium | 6 months | 33.1 | Todo |  |  |  | [notes](06.%20Sorting/02.%20Counting%20%26%20Bucket%20Sort/0451.%20Sort%20Characters%20By%20Frequency/0451.%20Sort%20Characters%20By%20Frequency.md) |
| 2 | [164. Maximum Gap](https://leetcode.com/problems/maximum-gap/) | Medium | 6 months | 16.5 | Todo |  |  |  | [notes](06.%20Sorting/02.%20Counting%20%26%20Bucket%20Sort/0164.%20Maximum%20Gap/0164.%20Maximum%20Gap.md) |
| 3 | [791. Custom Sort String](https://leetcode.com/problems/custom-sort-string/) | Medium | 6+ months | 66.8 | ✅ Solved |  |  |  | [notes](06.%20Sorting/02.%20Counting%20%26%20Bucket%20Sort/0791.%20Custom%20Sort%20String/0791.%20Custom%20Sort%20String.md) |
| 4 | [274. H-Index](https://leetcode.com/problems/h-index/) | Medium | 6+ months | 37.6 | Todo |  |  |  | [notes](06.%20Sorting/02.%20Counting%20%26%20Bucket%20Sort/0274.%20H-Index/0274.%20H-Index.md) |
| 5 | [220. Contains Duplicate III](https://leetcode.com/problems/contains-duplicate-iii/) | Hard | 6+ months | 8.3 | Todo |  |  |  | [notes](06.%20Sorting/02.%20Counting%20%26%20Bucket%20Sort/0220.%20Contains%20Duplicate%20III/0220.%20Contains%20Duplicate%20III.md) |
| 6 | [1122. Relative Sort Array](https://leetcode.com/problems/relative-sort-array/) | Easy | 6+ months | 5.8 | ✅ Solved |  |  |  | [notes](06.%20Sorting/02.%20Counting%20%26%20Bucket%20Sort/1122.%20Relative%20Sort%20Array/1122.%20Relative%20Sort%20Array.md) |
| 7 | [1365. How Many Numbers Are Smaller Than the Current Number](https://leetcode.com/problems/how-many-numbers-are-smaller-than-the-current-number/) | Easy | 6+ months | 5.8 | ✅ Solved |  |  |  | [notes](06.%20Sorting/02.%20Counting%20%26%20Bucket%20Sort/1365.%20How%20Many%20Numbers%20Are%20Smaller%20Than%20the%20Current%20Number/1365.%20How%20Many%20Numbers%20Are%20Smaller%20Than%20the%20Current%20Number.md) |
| 8 | [2089. Find Target Indices After Sorting Array](https://leetcode.com/problems/find-target-indices-after-sorting-array/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](06.%20Sorting/02.%20Counting%20%26%20Bucket%20Sort/2089.%20Find%20Target%20Indices%20After%20Sorting%20Array/2089.%20Find%20Target%20Indices%20After%20Sorting%20Array.md) |
| 9 | [2785. Sort Vowels in a String](https://leetcode.com/problems/sort-vowels-in-a-string/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20Sorting/02.%20Counting%20%26%20Bucket%20Sort/2785.%20Sort%20Vowels%20in%20a%20String/2785.%20Sort%20Vowels%20in%20a%20String.md) |
| 10 | [1051. Height Checker](https://leetcode.com/problems/height-checker/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20Sorting/02.%20Counting%20%26%20Bucket%20Sort/1051.%20Height%20Checker/1051.%20Height%20Checker.md) |

### 06.03. Merge Sort Applications

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [912. Sort an Array](https://leetcode.com/problems/sort-an-array/) | Medium | 6 months | 22.4 | Todo |  |  |  | [notes](06.%20Sorting/03.%20Merge%20Sort%20Applications/0912.%20Sort%20an%20Array/0912.%20Sort%20an%20Array.md) |
| 2 | [493. Reverse Pairs](https://leetcode.com/problems/reverse-pairs/) | Hard | 6+ months | 20.6 | ✅ Solved |  |  |  | [notes](06.%20Sorting/03.%20Merge%20Sort%20Applications/0493.%20Reverse%20Pairs/0493.%20Reverse%20Pairs.md) |
| 3 | [315. Count of Smaller Numbers After Self](https://leetcode.com/problems/count-of-smaller-numbers-after-self/) | Hard | 6+ months | 9.2 | Todo |  |  |  | [notes](06.%20Sorting/03.%20Merge%20Sort%20Applications/0315.%20Count%20of%20Smaller%20Numbers%20After%20Self/0315.%20Count%20of%20Smaller%20Numbers%20After%20Self.md) |
| 4 | [327. Count of Range Sum](https://leetcode.com/problems/count-of-range-sum/) | Hard | 6+ months | 5.5 | Todo |  |  |  | [notes](06.%20Sorting/03.%20Merge%20Sort%20Applications/0327.%20Count%20of%20Range%20Sum/0327.%20Count%20of%20Range%20Sum.md) |
| 5 | [2426. Number of Pairs Satisfying Inequality](https://leetcode.com/problems/number-of-pairs-satisfying-inequality/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20Sorting/03.%20Merge%20Sort%20Applications/2426.%20Number%20of%20Pairs%20Satisfying%20Inequality/2426.%20Number%20of%20Pairs%20Satisfying%20Inequality.md) |

### 06.04. Sort Then Scan

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [1331. Rank Transform of an Array](https://leetcode.com/problems/rank-transform-of-an-array/) | Easy | 6 months | 22.3 | ✅ Solved |  |  |  | [notes](06.%20Sorting/04.%20Sort%20Then%20Scan/1331.%20Rank%20Transform%20of%20an%20Array/1331.%20Rank%20Transform%20of%20an%20Array.md) |
| 2 | [628. Maximum Product of Three Numbers](https://leetcode.com/problems/maximum-product-of-three-numbers/) | Easy | 6 months | 14.8 | Todo |  |  |  | [notes](06.%20Sorting/04.%20Sort%20Then%20Scan/0628.%20Maximum%20Product%20of%20Three%20Numbers/0628.%20Maximum%20Product%20of%20Three%20Numbers.md) |
| 3 | [1502. Can Make Arithmetic Progression From Sequence](https://leetcode.com/problems/can-make-arithmetic-progression-from-sequence/) | Easy | 6 months | 12.4 | Todo |  |  |  | [notes](06.%20Sorting/04.%20Sort%20Then%20Scan/1502.%20Can%20Make%20Arithmetic%20Progression%20From%20Sequence/1502.%20Can%20Make%20Arithmetic%20Progression%20From%20Sequence.md) |
| 4 | [2948. Make Lexicographically Smallest Array by Swapping Elements](https://leetcode.com/problems/make-lexicographically-smallest-array-by-swapping-elements/) | Medium | 6 months | 5.0 | Todo |  |  |  | [notes](06.%20Sorting/04.%20Sort%20Then%20Scan/2948.%20Make%20Lexicographically%20Smallest%20Array%20by%20Swapping%20Elements/2948.%20Make%20Lexicographically%20Smallest%20Array%20by%20Swapping%20Elements.md) |
| 5 | [976. Largest Perimeter Triangle](https://leetcode.com/problems/largest-perimeter-triangle/) | Easy | 6+ months | 10.1 | Todo |  |  |  | [notes](06.%20Sorting/04.%20Sort%20Then%20Scan/0976.%20Largest%20Perimeter%20Triangle/0976.%20Largest%20Perimeter%20Triangle.md) |
| 6 | [1200. Minimum Absolute Difference](https://leetcode.com/problems/minimum-absolute-difference/) | Easy | 6+ months | 9.2 | ✅ Solved |  |  |  | [notes](06.%20Sorting/04.%20Sort%20Then%20Scan/1200.%20Minimum%20Absolute%20Difference/1200.%20Minimum%20Absolute%20Difference.md) |
| 7 | [2974. Minimum Number Game](https://leetcode.com/problems/minimum-number-game/) | Easy | 6+ months | 7.1 | ✅ Solved |  |  |  | [notes](06.%20Sorting/04.%20Sort%20Then%20Scan/2974.%20Minimum%20Number%20Game/2974.%20Minimum%20Number%20Game.md) |
| 8 | [539. Minimum Time Difference](https://leetcode.com/problems/minimum-time-difference/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](06.%20Sorting/04.%20Sort%20Then%20Scan/0539.%20Minimum%20Time%20Difference/0539.%20Minimum%20Time%20Difference.md) |
| 9 | [561. Array Partition](https://leetcode.com/problems/array-partition/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20Sorting/04.%20Sort%20Then%20Scan/0561.%20Array%20Partition/0561.%20Array%20Partition.md) |
| 10 | [2943. Maximize Area of Square Hole in Grid](https://leetcode.com/problems/maximize-area-of-square-hole-in-grid/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20Sorting/04.%20Sort%20Then%20Scan/2943.%20Maximize%20Area%20of%20Square%20Hole%20in%20Grid/2943.%20Maximize%20Area%20of%20Square%20Hole%20in%20Grid.md) |
| 11 | [2966. Divide Array Into Arrays With Max Difference](https://leetcode.com/problems/divide-array-into-arrays-with-max-difference/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](06.%20Sorting/04.%20Sort%20Then%20Scan/2966.%20Divide%20Array%20Into%20Arrays%20With%20Max%20Difference/2966.%20Divide%20Array%20Into%20Arrays%20With%20Max%20Difference.md) |
| 12 | [3010. Divide an Array Into Subarrays With Minimum Cost I](https://leetcode.com/problems/divide-an-array-into-subarrays-with-minimum-cost-i/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20Sorting/04.%20Sort%20Then%20Scan/3010.%20Divide%20an%20Array%20Into%20Subarrays%20With%20Minimum%20Cost%20I/3010.%20Divide%20an%20Array%20Into%20Subarrays%20With%20Minimum%20Cost%20I.md) |

## 07. Matrix & Simulation

42 problems: 22 Easy, 19 Medium, 1 Hard. [Open chapter README](07.%20Matrix%20%26%20Simulation/README.md) · [Back to top](#chapters)

### 07.01. Matrix Traversal (Spiral, Diagonal)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [54. Spiral Matrix](https://leetcode.com/problems/spiral-matrix/) | Medium | 3 months | 48.3 | Todo |  |  |  | [notes](07.%20Matrix%20%26%20Simulation/01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/0054.%20Spiral%20Matrix/0054.%20Spiral%20Matrix.md) |
| 2 | [835. Image Overlap](https://leetcode.com/problems/image-overlap/) | Medium | 6 months | 5.0 | Todo |  |  |  | [notes](07.%20Matrix%20%26%20Simulation/01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/0835.%20Image%20Overlap/0835.%20Image%20Overlap.md) |
| 3 | [498. Diagonal Traverse](https://leetcode.com/problems/diagonal-traverse/) | Medium | 6+ months | 63.4 | Todo |  |  |  | [notes](07.%20Matrix%20%26%20Simulation/01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/0498.%20Diagonal%20Traverse/0498.%20Diagonal%20Traverse.md) |
| 4 | [311. Sparse Matrix Multiplication](https://leetcode.com/problems/sparse-matrix-multiplication/) 🔒 | Medium | 6+ months | 47.1 | Todo |  |  |  | [notes](07.%20Matrix%20%26%20Simulation/01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/0311.%20Sparse%20Matrix%20Multiplication/0311.%20Sparse%20Matrix%20Multiplication.md) |
| 5 | [766. Toeplitz Matrix](https://leetcode.com/problems/toeplitz-matrix/) | Easy | 6+ months | 41.8 | Todo |  |  |  | [notes](07.%20Matrix%20%26%20Simulation/01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/0766.%20Toeplitz%20Matrix/0766.%20Toeplitz%20Matrix.md) |
| 6 | [1424. Diagonal Traverse II](https://leetcode.com/problems/diagonal-traverse-ii/) | Medium | 6+ months | 38.7 | Todo |  |  |  | [notes](07.%20Matrix%20%26%20Simulation/01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/1424.%20Diagonal%20Traverse%20II/1424.%20Diagonal%20Traverse%20II.md) |
| 7 | [59. Spiral Matrix II](https://leetcode.com/problems/spiral-matrix-ii/) | Medium | 6+ months | 13.4 | Todo |  |  |  | [notes](07.%20Matrix%20%26%20Simulation/01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/0059.%20Spiral%20Matrix%20II/0059.%20Spiral%20Matrix%20II.md) |
| 8 | [1672. Richest Customer Wealth](https://leetcode.com/problems/richest-customer-wealth/) | Easy | 6+ months | 8.5 | ✅ Solved |  |  |  | [notes](07.%20Matrix%20%26%20Simulation/01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/1672.%20Richest%20Customer%20Wealth/1672.%20Richest%20Customer%20Wealth.md) |
| 9 | [1572. Matrix Diagonal Sum](https://leetcode.com/problems/matrix-diagonal-sum/) | Easy | 6+ months | 5.3 | ✅ Solved |  |  |  | [notes](07.%20Matrix%20%26%20Simulation/01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/1572.%20Matrix%20Diagonal%20Sum/1572.%20Matrix%20Diagonal%20Sum.md) |
| 10 | [661. Image Smoother](https://leetcode.com/problems/image-smoother/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](07.%20Matrix%20%26%20Simulation/01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/0661.%20Image%20Smoother/0661.%20Image%20Smoother.md) |
| 11 | [885. Spiral Matrix III](https://leetcode.com/problems/spiral-matrix-iii/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](07.%20Matrix%20%26%20Simulation/01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/0885.%20Spiral%20Matrix%20III/0885.%20Spiral%20Matrix%20III.md) |
| 12 | [2326. Spiral Matrix IV](https://leetcode.com/problems/spiral-matrix-iv/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](07.%20Matrix%20%26%20Simulation/01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/2326.%20Spiral%20Matrix%20IV/2326.%20Spiral%20Matrix%20IV.md) |
| 13 | [2373. Largest Local Values in a Matrix](https://leetcode.com/problems/largest-local-values-in-a-matrix/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](07.%20Matrix%20%26%20Simulation/01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/2373.%20Largest%20Local%20Values%20in%20a%20Matrix/2373.%20Largest%20Local%20Values%20in%20a%20Matrix.md) |
| 14 | [3417. Zigzag Grid Traversal With Skip](https://leetcode.com/problems/zigzag-grid-traversal-with-skip/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](07.%20Matrix%20%26%20Simulation/01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/3417.%20Zigzag%20Grid%20Traversal%20With%20Skip/3417.%20Zigzag%20Grid%20Traversal%20With%20Skip.md) |
| 15 | [3446. Sort Matrix by Diagonals](https://leetcode.com/problems/sort-matrix-by-diagonals/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](07.%20Matrix%20%26%20Simulation/01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/3446.%20Sort%20Matrix%20by%20Diagonals/3446.%20Sort%20Matrix%20by%20Diagonals.md) |
| 16 | [3898. Find the Degree of Each Vertex](https://leetcode.com/problems/find-the-degree-of-each-vertex/) | Easy | 6+ months | 6.2 | Todo |  |  |  | [notes](07.%20Matrix%20%26%20Simulation/01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/3898.%20Find%20the%20Degree%20of%20Each%20Vertex/3898.%20Find%20the%20Degree%20of%20Each%20Vertex.md) |
| 17 | [807. Max Increase to Keep City Skyline](https://leetcode.com/problems/max-increase-to-keep-city-skyline/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](07.%20Matrix%20%26%20Simulation/01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/0807.%20Max%20Increase%20to%20Keep%20City%20Skyline/0807.%20Max%20Increase%20to%20Keep%20City%20Skyline.md) |

### 07.02. Matrix Rotation & Transformation

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [48. Rotate Image](https://leetcode.com/problems/rotate-image/) | Medium | 3 months | 44.5 | ✅ Solved |  |  |  | [notes](07.%20Matrix%20%26%20Simulation/02.%20Matrix%20Rotation%20%26%20Transformation/0048.%20Rotate%20Image/0048.%20Rotate%20Image.md) |
| 2 | [867. Transpose Matrix](https://leetcode.com/problems/transpose-matrix/) | Easy | 6+ months | 10.7 | Todo |  |  |  | [notes](07.%20Matrix%20%26%20Simulation/02.%20Matrix%20Rotation%20%26%20Transformation/0867.%20Transpose%20Matrix/0867.%20Transpose%20Matrix.md) |
| 3 | [1914. Cyclically Rotating a Grid](https://leetcode.com/problems/cyclically-rotating-a-grid/) | Medium | 6+ months | 10.1 | Todo |  |  |  | [notes](07.%20Matrix%20%26%20Simulation/02.%20Matrix%20Rotation%20%26%20Transformation/1914.%20Cyclically%20Rotating%20a%20Grid/1914.%20Cyclically%20Rotating%20a%20Grid.md) |
| 4 | [1861. Rotating the Box](https://leetcode.com/problems/rotating-the-box/) | Medium | 6+ months | 9.3 | Todo |  |  |  | [notes](07.%20Matrix%20%26%20Simulation/02.%20Matrix%20Rotation%20%26%20Transformation/1861.%20Rotating%20the%20Box/1861.%20Rotating%20the%20Box.md) |
| 5 | [566. Reshape the Matrix](https://leetcode.com/problems/reshape-the-matrix/) | Easy | 6+ months | 6.5 | Todo |  |  |  | [notes](07.%20Matrix%20%26%20Simulation/02.%20Matrix%20Rotation%20%26%20Transformation/0566.%20Reshape%20the%20Matrix/0566.%20Reshape%20the%20Matrix.md) |
| 6 | [832. Flipping an Image](https://leetcode.com/problems/flipping-an-image/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](07.%20Matrix%20%26%20Simulation/02.%20Matrix%20Rotation%20%26%20Transformation/0832.%20Flipping%20an%20Image/0832.%20Flipping%20an%20Image.md) |
| 7 | [1886. Determine Whether Matrix Can Be Obtained By Rotation](https://leetcode.com/problems/determine-whether-matrix-can-be-obtained-by-rotation/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](07.%20Matrix%20%26%20Simulation/02.%20Matrix%20Rotation%20%26%20Transformation/1886.%20Determine%20Whether%20Matrix%20Can%20Be%20Obtained%20By%20Rotation/1886.%20Determine%20Whether%20Matrix%20Can%20Be%20Obtained%20By%20Rotation.md) |
| 8 | [2946. Matrix Similarity After Cyclic Shifts](https://leetcode.com/problems/matrix-similarity-after-cyclic-shifts/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](07.%20Matrix%20%26%20Simulation/02.%20Matrix%20Rotation%20%26%20Transformation/2946.%20Matrix%20Similarity%20After%20Cyclic%20Shifts/2946.%20Matrix%20Similarity%20After%20Cyclic%20Shifts.md) |
| 9 | [3643. Flip Square Submatrix Vertically](https://leetcode.com/problems/flip-square-submatrix-vertically/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](07.%20Matrix%20%26%20Simulation/02.%20Matrix%20Rotation%20%26%20Transformation/3643.%20Flip%20Square%20Submatrix%20Vertically/3643.%20Flip%20Square%20Submatrix%20Vertically.md) |

### 07.03. In-Place Matrix Marking

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea&ensp;&#8203;&ensp;&#8203;&ensp;&#8203; | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [73. Set Matrix Zeroes](https://leetcode.com/problems/set-matrix-zeroes/) | Medium | 6 months | 54.8 | ✅ Solved |  |  |  | [notes](07.%20Matrix%20%26%20Simulation/03.%20In-Place%20Matrix%20Marking/0073.%20Set%20Matrix%20Zeroes/0073.%20Set%20Matrix%20Zeroes.md) |
| 2 | [289. Game of Life](https://leetcode.com/problems/game-of-life/) | Medium | 6+ months | 11.2 | Todo |  |  |  | [notes](07.%20Matrix%20%26%20Simulation/03.%20In-Place%20Matrix%20Marking/0289.%20Game%20of%20Life/0289.%20Game%20of%20Life.md) |

### 07.04. Grid Simulation

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [419. Battleships in a Board](https://leetcode.com/problems/battleships-in-a-board/) | Medium | 6+ months | 40.4 | Todo |  |  |  | [notes](07.%20Matrix%20%26%20Simulation/04.%20Grid%20Simulation/0419.%20Battleships%20in%20a%20Board/0419.%20Battleships%20in%20a%20Board.md) |
| 2 | [1275. Find Winner on a Tic Tac Toe Game](https://leetcode.com/problems/find-winner-on-a-tic-tac-toe-game/) | Easy | 6+ months | 12.3 | Todo |  |  |  | [notes](07.%20Matrix%20%26%20Simulation/04.%20Grid%20Simulation/1275.%20Find%20Winner%20on%20a%20Tic%20Tac%20Toe%20Game/1275.%20Find%20Winner%20on%20a%20Tic%20Tac%20Toe%20Game.md) |
| 3 | [2257. Count Unguarded Cells in the Grid](https://leetcode.com/problems/count-unguarded-cells-in-the-grid/) | Medium | 6+ months | 10.4 | Todo |  |  |  | [notes](07.%20Matrix%20%26%20Simulation/04.%20Grid%20Simulation/2257.%20Count%20Unguarded%20Cells%20in%20the%20Grid/2257.%20Count%20Unguarded%20Cells%20in%20the%20Grid.md) |
| 4 | [723. Candy Crush](https://leetcode.com/problems/candy-crush/) 🔒 | Medium | 6+ months | 10.0 | Todo |  |  |  | [notes](07.%20Matrix%20%26%20Simulation/04.%20Grid%20Simulation/0723.%20Candy%20Crush/0723.%20Candy%20Crush.md) |
| 5 | [463. Island Perimeter](https://leetcode.com/problems/island-perimeter/) | Easy | 6+ months | 5.8 | ✅ Solved |  |  |  | [notes](07.%20Matrix%20%26%20Simulation/04.%20Grid%20Simulation/0463.%20Island%20Perimeter/0463.%20Island%20Perimeter.md) |
| 6 | [2596. Check Knight Tour Configuration](https://leetcode.com/problems/check-knight-tour-configuration/) | Medium | 6+ months | 36.1 | Todo |  |  |  | [notes](07.%20Matrix%20%26%20Simulation/04.%20Grid%20Simulation/2596.%20Check%20Knight%20Tour%20Configuration/2596.%20Check%20Knight%20Tour%20Configuration.md) |
| 7 | [999. Available Captures for Rook](https://leetcode.com/problems/available-captures-for-rook/) | Easy | 6+ months | 5.5 | Todo |  |  |  | [notes](07.%20Matrix%20%26%20Simulation/04.%20Grid%20Simulation/0999.%20Available%20Captures%20for%20Rook/0999.%20Available%20Captures%20for%20Rook.md) |

### 07.05. Process Simulation

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [3507. Minimum Pair Removal to Sort Array I](https://leetcode.com/problems/minimum-pair-removal-to-sort-array-i/) | Easy | 6+ months | 14.3 | Todo |  |  |  | [notes](07.%20Matrix%20%26%20Simulation/05.%20Process%20Simulation/3507.%20Minimum%20Pair%20Removal%20to%20Sort%20Array%20I/3507.%20Minimum%20Pair%20Removal%20to%20Sort%20Array%20I.md) |
| 2 | [3477. Fruits Into Baskets II](https://leetcode.com/problems/fruits-into-baskets-ii/) | Easy | 6+ months | 14.0 | 🟡 Attempted |  |  |  | [notes](07.%20Matrix%20%26%20Simulation/05.%20Process%20Simulation/3477.%20Fruits%20Into%20Baskets%20II/3477.%20Fruits%20Into%20Baskets%20II.md) |
| 3 | [1389. Create Target Array in the Given Order](https://leetcode.com/problems/create-target-array-in-the-given-order/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](07.%20Matrix%20%26%20Simulation/05.%20Process%20Simulation/1389.%20Create%20Target%20Array%20in%20the%20Given%20Order/1389.%20Create%20Target%20Array%20in%20the%20Given%20Order.md) |
| 4 | [3069. Distribute Elements Into Two Arrays I](https://leetcode.com/problems/distribute-elements-into-two-arrays-i/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](07.%20Matrix%20%26%20Simulation/05.%20Process%20Simulation/3069.%20Distribute%20Elements%20Into%20Two%20Arrays%20I/3069.%20Distribute%20Elements%20Into%20Two%20Arrays%20I.md) |
| 5 | [2303. Calculate Amount Paid in Taxes](https://leetcode.com/problems/calculate-amount-paid-in-taxes/) | Easy | 6+ months | 36.8 | Todo |  |  |  | [notes](07.%20Matrix%20%26%20Simulation/05.%20Process%20Simulation/2303.%20Calculate%20Amount%20Paid%20in%20Taxes/2303.%20Calculate%20Amount%20Paid%20in%20Taxes.md) |
| 6 | [157. Read N Characters Given Read4](https://leetcode.com/problems/read-n-characters-given-read4/) 🔒 | Easy | 6+ months | 36.1 | Todo |  |  |  | [notes](07.%20Matrix%20%26%20Simulation/05.%20Process%20Simulation/0157.%20Read%20N%20Characters%20Given%20Read4/0157.%20Read%20N%20Characters%20Given%20Read4.md) |
| 7 | [158. Read N Characters Given read4 II - Call Multiple Times](https://leetcode.com/problems/read-n-characters-given-read4-ii-call-multiple-times/) 🔒 | Hard | 6+ months | 36.1 | Todo |  |  |  | [notes](07.%20Matrix%20%26%20Simulation/05.%20Process%20Simulation/0158.%20Read%20N%20Characters%20Given%20read4%20II%20-%20Call%20Multiple%20Times/0158.%20Read%20N%20Characters%20Given%20read4%20II%20-%20Call%20Multiple%20Times.md) |

## 08. Math & Number Theory

117 problems: 55 Easy, 46 Medium, 16 Hard. [Open chapter README](08.%20Math%20%26%20Number%20Theory/README.md) · [Back to top](#chapters)

### 08.01. Digit Manipulation

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [9. Palindrome Number](https://leetcode.com/problems/palindrome-number/) | Easy | 3 months | 53.1 | ✅ Solved |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/01.%20Digit%20Manipulation/0009.%20Palindrome%20Number/0009.%20Palindrome%20Number.md) |
| 2 | [66. Plus One](https://leetcode.com/problems/plus-one/) | Easy | 6 months | 48.0 | ✅ Solved |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/01.%20Digit%20Manipulation/0066.%20Plus%20One/0066.%20Plus%20One.md) |
| 3 | [7. Reverse Integer](https://leetcode.com/problems/reverse-integer/) | Medium | 6 months | 45.1 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/01.%20Digit%20Manipulation/0007.%20Reverse%20Integer/0007.%20Reverse%20Integer.md) |
| 4 | [202. Happy Number](https://leetcode.com/problems/happy-number/) | Easy | 6 months | 42.1 | ✅ Solved |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/01.%20Digit%20Manipulation/0202.%20Happy%20Number/0202.%20Happy%20Number.md) |
| 5 | [258. Add Digits](https://leetcode.com/problems/add-digits/) | Easy | 6 months | 19.3 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/01.%20Digit%20Manipulation/0258.%20Add%20Digits/0258.%20Add%20Digits.md) |
| 6 | [3945. Digit Frequency Score](https://leetcode.com/problems/digit-frequency-score/) | Easy | 6 months | 7.1 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/01.%20Digit%20Manipulation/3945.%20Digit%20Frequency%20Score/3945.%20Digit%20Frequency%20Score.md) |
| 7 | [3754. Concatenate Non-Zero Digits and Multiply by Sum I](https://leetcode.com/problems/concatenate-non-zero-digits-and-multiply-by-sum-i/) | Easy | 6 months | 6.1 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/01.%20Digit%20Manipulation/3754.%20Concatenate%20Non-Zero%20Digits%20and%20Multiply%20by%20Sum%20I/3754.%20Concatenate%20Non-Zero%20Digits%20and%20Multiply%20by%20Sum%20I.md) |
| 8 | [1291. Sequential Digits](https://leetcode.com/problems/sequential-digits/) | Medium | 6 months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/01.%20Digit%20Manipulation/1291.%20Sequential%20Digits/1291.%20Sequential%20Digits.md) |
| 9 | [3536. Maximum Product of Two Digits](https://leetcode.com/problems/maximum-product-of-two-digits/) | Easy | 6 months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/01.%20Digit%20Manipulation/3536.%20Maximum%20Product%20of%20Two%20Digits/3536.%20Maximum%20Product%20of%20Two%20Digits.md) |
| 10 | [168. Excel Sheet Column Title](https://leetcode.com/problems/excel-sheet-column-title/) | Easy | 6+ months | 37.3 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/01.%20Digit%20Manipulation/0168.%20Excel%20Sheet%20Column%20Title/0168.%20Excel%20Sheet%20Column%20Title.md) |
| 11 | [2566. Maximum Difference by Remapping a Digit](https://leetcode.com/problems/maximum-difference-by-remapping-a-digit/) | Easy | 6+ months | 12.5 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/01.%20Digit%20Manipulation/2566.%20Maximum%20Difference%20by%20Remapping%20a%20Digit/2566.%20Maximum%20Difference%20by%20Remapping%20a%20Digit.md) |
| 12 | [3300. Minimum Element After Replacement With Digit Sum](https://leetcode.com/problems/minimum-element-after-replacement-with-digit-sum/) | Easy | 6+ months | 11.1 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/01.%20Digit%20Manipulation/3300.%20Minimum%20Element%20After%20Replacement%20With%20Digit%20Sum/3300.%20Minimum%20Element%20After%20Replacement%20With%20Digit%20Sum.md) |
| 13 | [3345. Smallest Divisible Digit Product I](https://leetcode.com/problems/smallest-divisible-digit-product-i/) | Easy | 6+ months | 8.3 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/01.%20Digit%20Manipulation/3345.%20Smallest%20Divisible%20Digit%20Product%20I/3345.%20Smallest%20Divisible%20Digit%20Product%20I.md) |
| 14 | [564. Find the Closest Palindrome](https://leetcode.com/problems/find-the-closest-palindrome/) | Hard | 6+ months | 6.9 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/01.%20Digit%20Manipulation/0564.%20Find%20the%20Closest%20Palindrome/0564.%20Find%20the%20Closest%20Palindrome.md) |
| 15 | [1295. Find Numbers with Even Number of Digits](https://leetcode.com/problems/find-numbers-with-even-number-of-digits/) | Easy | 6+ months | 5.1 | ✅ Solved |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/01.%20Digit%20Manipulation/1295.%20Find%20Numbers%20with%20Even%20Number%20of%20Digits/1295.%20Find%20Numbers%20with%20Even%20Number%20of%20Digits.md) |
| 16 | [788. Rotated Digits](https://leetcode.com/problems/rotated-digits/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/01.%20Digit%20Manipulation/0788.%20Rotated%20Digits/0788.%20Rotated%20Digits.md) |
| 17 | [1281. Subtract the Product and Sum of Digits of an Integer](https://leetcode.com/problems/subtract-the-product-and-sum-of-digits-of-an-integer/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/01.%20Digit%20Manipulation/1281.%20Subtract%20the%20Product%20and%20Sum%20of%20Digits%20of%20an%20Integer/1281.%20Subtract%20the%20Product%20and%20Sum%20of%20Digits%20of%20an%20Integer.md) |
| 18 | [1432. Max Difference You Can Get From Changing an Integer](https://leetcode.com/problems/max-difference-you-can-get-from-changing-an-integer/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/01.%20Digit%20Manipulation/1432.%20Max%20Difference%20You%20Can%20Get%20From%20Changing%20an%20Integer/1432.%20Max%20Difference%20You%20Can%20Get%20From%20Changing%20an%20Integer.md) |
| 19 | [1945. Sum of Digits of String After Convert](https://leetcode.com/problems/sum-of-digits-of-string-after-convert/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/01.%20Digit%20Manipulation/1945.%20Sum%20of%20Digits%20of%20String%20After%20Convert/1945.%20Sum%20of%20Digits%20of%20String%20After%20Convert.md) |
| 20 | [2081. Sum of k-Mirror Numbers](https://leetcode.com/problems/sum-of-k-mirror-numbers/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/01.%20Digit%20Manipulation/2081.%20Sum%20of%20k-Mirror%20Numbers/2081.%20Sum%20of%20k-Mirror%20Numbers.md) |
| 21 | [2119. A Number After a Double Reversal](https://leetcode.com/problems/a-number-after-a-double-reversal/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/01.%20Digit%20Manipulation/2119.%20A%20Number%20After%20a%20Double%20Reversal/2119.%20A%20Number%20After%20a%20Double%20Reversal.md) |
| 22 | [2457. Minimum Addition to Make Integer Beautiful](https://leetcode.com/problems/minimum-addition-to-make-integer-beautiful/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/01.%20Digit%20Manipulation/2457.%20Minimum%20Addition%20to%20Make%20Integer%20Beautiful/2457.%20Minimum%20Addition%20to%20Make%20Integer%20Beautiful.md) |
| 23 | [2843.   Count Symmetric Integers](https://leetcode.com/problems/count-symmetric-integers/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/01.%20Digit%20Manipulation/2843.%20%20%20Count%20Symmetric%20Integers/2843.%20%20%20Count%20Symmetric%20Integers.md) |
| 24 | [3697. Compute Decimal Representation](https://leetcode.com/problems/compute-decimal-representation/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/01.%20Digit%20Manipulation/3697.%20Compute%20Decimal%20Representation/3697.%20Compute%20Decimal%20Representation.md) |
| 25 | [2553. Separate the Digits in an Array](https://leetcode.com/problems/separate-the-digits-in-an-array/) | Easy | 6+ months | 37.6 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/01.%20Digit%20Manipulation/2553.%20Separate%20the%20Digits%20in%20an%20Array/2553.%20Separate%20the%20Digits%20in%20an%20Array.md) |
| 26 | [2520. Count the Digits That Divide a Number](https://leetcode.com/problems/count-the-digits-that-divide-a-number/) | Easy | 6+ months | 5.5 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/01.%20Digit%20Manipulation/2520.%20Count%20the%20Digits%20That%20Divide%20a%20Number/2520.%20Count%20the%20Digits%20That%20Divide%20a%20Number.md) |

### 08.02. Basic Math & Formulas

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [2235. Add Two Integers](https://leetcode.com/problems/add-two-integers/) | Easy | 3 months | 27.3 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/02.%20Basic%20Math%20%26%20Formulas/2235.%20Add%20Two%20Integers/2235.%20Add%20Two%20Integers.md) |
| 2 | [2409. Count Days Spent Together](https://leetcode.com/problems/count-days-spent-together/) | Easy | 3 months | 13.2 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/02.%20Basic%20Math%20%26%20Formulas/2409.%20Count%20Days%20Spent%20Together/2409.%20Count%20Days%20Spent%20Together.md) |
| 3 | [3875. Construct Uniform Parity Array I](https://leetcode.com/problems/construct-uniform-parity-array-i/) | Easy | 3 months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/02.%20Basic%20Math%20%26%20Formulas/3875.%20Construct%20Uniform%20Parity%20Array%20I/3875.%20Construct%20Uniform%20Parity%20Array%20I.md) |
| 4 | [1822. Sign of the Product of an Array](https://leetcode.com/problems/sign-of-the-product-of-an-array/) | Easy | 6 months | 15.1 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/02.%20Basic%20Math%20%26%20Formulas/1822.%20Sign%20of%20the%20Product%20of%20an%20Array/1822.%20Sign%20of%20the%20Product%20of%20an%20Array.md) |
| 5 | [3870. Count Commas in Range](https://leetcode.com/problems/count-commas-in-range/) | Easy | 6 months | 6.8 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/02.%20Basic%20Math%20%26%20Formulas/3870.%20Count%20Commas%20in%20Range/3870.%20Count%20Commas%20in%20Range.md) |
| 6 | [166. Fraction to Recurring Decimal](https://leetcode.com/problems/fraction-to-recurring-decimal/) | Medium | 6+ months | 21.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/02.%20Basic%20Math%20%26%20Formulas/0166.%20Fraction%20to%20Recurring%20Decimal/0166.%20Fraction%20to%20Recurring%20Decimal.md) |
| 7 | [1344. Angle Between Hands of a Clock](https://leetcode.com/problems/angle-between-hands-of-a-clock/) | Medium | 6+ months | 16.2 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/02.%20Basic%20Math%20%26%20Formulas/1344.%20Angle%20Between%20Hands%20of%20a%20Clock/1344.%20Angle%20Between%20Hands%20of%20a%20Clock.md) |
| 8 | [412. Fizz Buzz](https://leetcode.com/problems/fizz-buzz/) | Easy | 6+ months | 14.8 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/02.%20Basic%20Math%20%26%20Formulas/0412.%20Fizz%20Buzz/0412.%20Fizz%20Buzz.md) |
| 9 | [319. Bulb Switcher](https://leetcode.com/problems/bulb-switcher/) | Medium | 6+ months | 8.6 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/02.%20Basic%20Math%20%26%20Formulas/0319.%20Bulb%20Switcher/0319.%20Bulb%20Switcher.md) |
| 10 | [1925. Count Square Sum Triples](https://leetcode.com/problems/count-square-sum-triples/) | Easy | 6+ months | 8.1 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/02.%20Basic%20Math%20%26%20Formulas/1925.%20Count%20Square%20Sum%20Triples/1925.%20Count%20Square%20Sum%20Triples.md) |
| 11 | [3512. Minimum Operations to Make Array Sum Divisible by K](https://leetcode.com/problems/minimum-operations-to-make-array-sum-divisible-by-k/) | Easy | 6+ months | 8.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/02.%20Basic%20Math%20%26%20Formulas/3512.%20Minimum%20Operations%20to%20Make%20Array%20Sum%20Divisible%20by%20K/3512.%20Minimum%20Operations%20to%20Make%20Array%20Sum%20Divisible%20by%20K.md) |
| 12 | [400. Nth Digit](https://leetcode.com/problems/nth-digit/) | Medium | 6+ months | 7.1 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/02.%20Basic%20Math%20%26%20Formulas/0400.%20Nth%20Digit/0400.%20Nth%20Digit.md) |
| 13 | [396. Rotate Function](https://leetcode.com/problems/rotate-function/) | Medium | 6+ months | 5.7 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/02.%20Basic%20Math%20%26%20Formulas/0396.%20Rotate%20Function/0396.%20Rotate%20Function.md) |
| 14 | [2894. Divisible and Non-divisible Sums Difference](https://leetcode.com/problems/divisible-and-non-divisible-sums-difference/) | Easy | 6+ months | 5.2 | ✅ Solved |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/02.%20Basic%20Math%20%26%20Formulas/2894.%20Divisible%20and%20Non-divisible%20Sums%20Difference/2894.%20Divisible%20and%20Non-divisible%20Sums%20Difference.md) |
| 15 | [172. Factorial Trailing Zeroes](https://leetcode.com/problems/factorial-trailing-zeroes/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/02.%20Basic%20Math%20%26%20Formulas/0172.%20Factorial%20Trailing%20Zeroes/0172.%20Factorial%20Trailing%20Zeroes.md) |
| 16 | [296. Best Meeting Point](https://leetcode.com/problems/best-meeting-point/) 🔒 | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/02.%20Basic%20Math%20%26%20Formulas/0296.%20Best%20Meeting%20Point/0296.%20Best%20Meeting%20Point.md) |
| 17 | [326. Power of Three](https://leetcode.com/problems/power-of-three/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/02.%20Basic%20Math%20%26%20Formulas/0326.%20Power%20of%20Three/0326.%20Power%20of%20Three.md) |
| 18 | [453. Minimum Moves to Equal Array Elements](https://leetcode.com/problems/minimum-moves-to-equal-array-elements/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/02.%20Basic%20Math%20%26%20Formulas/0453.%20Minimum%20Moves%20to%20Equal%20Array%20Elements/0453.%20Minimum%20Moves%20to%20Equal%20Array%20Elements.md) |
| 19 | [1304. Find N Unique Integers Sum up to Zero](https://leetcode.com/problems/find-n-unique-integers-sum-up-to-zero/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/02.%20Basic%20Math%20%26%20Formulas/1304.%20Find%20N%20Unique%20Integers%20Sum%20up%20to%20Zero/1304.%20Find%20N%20Unique%20Integers%20Sum%20up%20to%20Zero.md) |
| 20 | [1360. Number of Days Between Two Dates](https://leetcode.com/problems/number-of-days-between-two-dates/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/02.%20Basic%20Math%20%26%20Formulas/1360.%20Number%20of%20Days%20Between%20Two%20Dates/1360.%20Number%20of%20Days%20Between%20Two%20Dates.md) |
| 21 | [1518. Water Bottles](https://leetcode.com/problems/water-bottles/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/02.%20Basic%20Math%20%26%20Formulas/1518.%20Water%20Bottles/1518.%20Water%20Bottles.md) |
| 22 | [1523. Count Odd Numbers in an Interval Range](https://leetcode.com/problems/count-odd-numbers-in-an-interval-range/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/02.%20Basic%20Math%20%26%20Formulas/1523.%20Count%20Odd%20Numbers%20in%20an%20Interval%20Range/1523.%20Count%20Odd%20Numbers%20in%20an%20Interval%20Range.md) |
| 23 | [1716. Calculate Money in Leetcode Bank](https://leetcode.com/problems/calculate-money-in-leetcode-bank/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/02.%20Basic%20Math%20%26%20Formulas/1716.%20Calculate%20Money%20in%20Leetcode%20Bank/1716.%20Calculate%20Money%20in%20Leetcode%20Bank.md) |
| 24 | [2028. Find Missing Observations](https://leetcode.com/problems/find-missing-observations/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/02.%20Basic%20Math%20%26%20Formulas/2028.%20Find%20Missing%20Observations/2028.%20Find%20Missing%20Observations.md) |
| 25 | [2579. Count Total Number of Colored Cells](https://leetcode.com/problems/count-total-number-of-colored-cells/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/02.%20Basic%20Math%20%26%20Formulas/2579.%20Count%20Total%20Number%20of%20Colored%20Cells/2579.%20Count%20Total%20Number%20of%20Colored%20Cells.md) |
| 26 | [2652. Sum Multiples](https://leetcode.com/problems/sum-multiples/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/02.%20Basic%20Math%20%26%20Formulas/2652.%20Sum%20Multiples/2652.%20Sum%20Multiples.md) |
| 27 | [2739. Total Distance Traveled](https://leetcode.com/problems/total-distance-traveled/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/02.%20Basic%20Math%20%26%20Formulas/2739.%20Total%20Distance%20Traveled/2739.%20Total%20Distance%20Traveled.md) |
| 28 | [3100. Water Bottles II](https://leetcode.com/problems/water-bottles-ii/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/02.%20Basic%20Math%20%26%20Formulas/3100.%20Water%20Bottles%20II/3100.%20Water%20Bottles%20II.md) |
| 29 | [3274. Check if Two Chessboard Squares Have the Same Color](https://leetcode.com/problems/check-if-two-chessboard-squares-have-the-same-color/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/02.%20Basic%20Math%20%26%20Formulas/3274.%20Check%20if%20Two%20Chessboard%20Squares%20Have%20the%20Same%20Color/3274.%20Check%20if%20Two%20Chessboard%20Squares%20Have%20the%20Same%20Color.md) |
| 30 | [3495. Minimum Operations to Make Array Elements Zero](https://leetcode.com/problems/minimum-operations-to-make-array-elements-zero/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/02.%20Basic%20Math%20%26%20Formulas/3495.%20Minimum%20Operations%20to%20Make%20Array%20Elements%20Zero/3495.%20Minimum%20Operations%20to%20Make%20Array%20Elements%20Zero.md) |
| 31 | [3516. Find Closest Person](https://leetcode.com/problems/find-closest-person/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/02.%20Basic%20Math%20%26%20Formulas/3516.%20Find%20Closest%20Person/3516.%20Find%20Closest%20Person.md) |
| 32 | [1033. Moving Stones Until Consecutive](https://leetcode.com/problems/moving-stones-until-consecutive/) | Medium | 6+ months | 36.1 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/02.%20Basic%20Math%20%26%20Formulas/1033.%20Moving%20Stones%20Until%20Consecutive/1033.%20Moving%20Stones%20Until%20Consecutive.md) |
| 33 | [3871. Count Commas in Range II](https://leetcode.com/problems/count-commas-in-range-ii/) | Medium | 6+ months | 7.4 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/02.%20Basic%20Math%20%26%20Formulas/3871.%20Count%20Commas%20in%20Range%20II/3871.%20Count%20Commas%20in%20Range%20II.md) |
| 34 | [1154. Day of the Year](https://leetcode.com/problems/day-of-the-year/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/02.%20Basic%20Math%20%26%20Formulas/1154.%20Day%20of%20the%20Year/1154.%20Day%20of%20the%20Year.md) |
| 35 | [1823. Find the Winner of the Circular Game](https://leetcode.com/problems/find-the-winner-of-the-circular-game/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/02.%20Basic%20Math%20%26%20Formulas/1823.%20Find%20the%20Winner%20of%20the%20Circular%20Game/1823.%20Find%20the%20Winner%20of%20the%20Circular%20Game.md) |
| 36 | [2455. Average Value of Even Numbers That Are Divisible by Three](https://leetcode.com/problems/average-value-of-even-numbers-that-are-divisible-by-three/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/02.%20Basic%20Math%20%26%20Formulas/2455.%20Average%20Value%20of%20Even%20Numbers%20That%20Are%20Divisible%20by%20Three/2455.%20Average%20Value%20of%20Even%20Numbers%20That%20Are%20Divisible%20by%20Three.md) |

### 08.03. GCD, LCM & Primes

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [204. Count Primes](https://leetcode.com/problems/count-primes/) | Medium | 3 months | 20.3 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/03.%20GCD%2C%20LCM%20%26%20Primes/0204.%20Count%20Primes/0204.%20Count%20Primes.md) |
| 2 | [1071. Greatest Common Divisor of Strings](https://leetcode.com/problems/greatest-common-divisor-of-strings/) | Easy | 6 months | 16.9 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/03.%20GCD%2C%20LCM%20%26%20Primes/1071.%20Greatest%20Common%20Divisor%20of%20Strings/1071.%20Greatest%20Common%20Divisor%20of%20Strings.md) |
| 3 | [3886. Sum of Sortable Integers](https://leetcode.com/problems/sum-of-sortable-integers/) | Hard | 6+ months | 17.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/03.%20GCD%2C%20LCM%20%26%20Primes/3886.%20Sum%20of%20Sortable%20Integers/3886.%20Sum%20of%20Sortable%20Integers.md) |
| 4 | [507. Perfect Number](https://leetcode.com/problems/perfect-number/) | Easy | 6+ months | 12.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/03.%20GCD%2C%20LCM%20%26%20Primes/0507.%20Perfect%20Number/0507.%20Perfect%20Number.md) |
| 5 | [1390. Four Divisors](https://leetcode.com/problems/four-divisors/) | Medium | 6+ months | 8.7 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/03.%20GCD%2C%20LCM%20%26%20Primes/1390.%20Four%20Divisors/1390.%20Four%20Divisors.md) |
| 6 | [2521. Distinct Prime Factors of Product of Array](https://leetcode.com/problems/distinct-prime-factors-of-product-of-array/) | Medium | 6+ months | 7.9 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/03.%20GCD%2C%20LCM%20%26%20Primes/2521.%20Distinct%20Prime%20Factors%20of%20Product%20of%20Array/2521.%20Distinct%20Prime%20Factors%20of%20Product%20of%20Array.md) |
| 7 | [263. Ugly Number](https://leetcode.com/problems/ugly-number/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/03.%20GCD%2C%20LCM%20%26%20Primes/0263.%20Ugly%20Number/0263.%20Ugly%20Number.md) |
| 8 | [650. 2 Keys Keyboard](https://leetcode.com/problems/2-keys-keyboard/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/03.%20GCD%2C%20LCM%20%26%20Primes/0650.%202%20Keys%20Keyboard/0650.%202%20Keys%20Keyboard.md) |
| 9 | [866. Prime Palindrome](https://leetcode.com/problems/prime-palindrome/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/03.%20GCD%2C%20LCM%20%26%20Primes/0866.%20Prime%20Palindrome/0866.%20Prime%20Palindrome.md) |
| 10 | [2413. Smallest Even Multiple](https://leetcode.com/problems/smallest-even-multiple/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/03.%20GCD%2C%20LCM%20%26%20Primes/2413.%20Smallest%20Even%20Multiple/2413.%20Smallest%20Even%20Multiple.md) |
| 11 | [2427. Number of Common Factors](https://leetcode.com/problems/number-of-common-factors/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/03.%20GCD%2C%20LCM%20%26%20Primes/2427.%20Number%20of%20Common%20Factors/2427.%20Number%20of%20Common%20Factors.md) |
| 12 | [2523. Closest Prime Numbers in Range](https://leetcode.com/problems/closest-prime-numbers-in-range/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/03.%20GCD%2C%20LCM%20%26%20Primes/2523.%20Closest%20Prime%20Numbers%20in%20Range/2523.%20Closest%20Prime%20Numbers%20in%20Range.md) |
| 13 | [3411. Maximum Subarray With Equal Products](https://leetcode.com/problems/maximum-subarray-with-equal-products/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/03.%20GCD%2C%20LCM%20%26%20Primes/3411.%20Maximum%20Subarray%20With%20Equal%20Products/3411.%20Maximum%20Subarray%20With%20Equal%20Products.md) |
| 14 | [3770. Largest Prime from Consecutive Prime Sum](https://leetcode.com/problems/largest-prime-from-consecutive-prime-sum/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/03.%20GCD%2C%20LCM%20%26%20Primes/3770.%20Largest%20Prime%20from%20Consecutive%20Prime%20Sum/3770.%20Largest%20Prime%20from%20Consecutive%20Prime%20Sum.md) |
| 15 | [1250. Check If It Is a Good Array](https://leetcode.com/problems/check-if-it-is-a-good-array/) | Hard | 6+ months | 6.4 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/03.%20GCD%2C%20LCM%20%26%20Primes/1250.%20Check%20If%20It%20Is%20a%20Good%20Array/1250.%20Check%20If%20It%20Is%20a%20Good%20Array.md) |
| 16 | [1492. The kth Factor of n](https://leetcode.com/problems/the-kth-factor-of-n/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/03.%20GCD%2C%20LCM%20%26%20Primes/1492.%20The%20kth%20Factor%20of%20n/1492.%20The%20kth%20Factor%20of%20n.md) |

### 08.04. Modular Arithmetic & Fast Power

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [50. Pow(x, n)](https://leetcode.com/problems/powx-n/) | Medium | 3 months | 84.3 | ✅ Solved |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/04.%20Modular%20Arithmetic%20%26%20Fast%20Power/0050.%20Pow%28x%2C%20n%29/0050.%20Pow%28x%2C%20n%29.md) |
| 2 | [1922. Count Good Numbers](https://leetcode.com/problems/count-good-numbers/) | Medium | 6 months | 21.7 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/04.%20Modular%20Arithmetic%20%26%20Fast%20Power/1922.%20Count%20Good%20Numbers/1922.%20Count%20Good%20Numbers.md) |
| 3 | [3558. Number of Ways to Assign Edge Weights I](https://leetcode.com/problems/number-of-ways-to-assign-edge-weights-i/) | Medium | 6+ months | 7.9 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/04.%20Modular%20Arithmetic%20%26%20Fast%20Power/3558.%20Number%20of%20Ways%20to%20Assign%20Edge%20Weights%20I/3558.%20Number%20of%20Ways%20to%20Assign%20Edge%20Weights%20I.md) |
| 4 | [1015. Smallest Integer Divisible by K](https://leetcode.com/problems/smallest-integer-divisible-by-k/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/04.%20Modular%20Arithmetic%20%26%20Fast%20Power/1015.%20Smallest%20Integer%20Divisible%20by%20K/1015.%20Smallest%20Integer%20Divisible%20by%20K.md) |

### 08.05. Combinatorics & Probability

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [60. Permutation Sequence](https://leetcode.com/problems/permutation-sequence/) | Hard | 6 months | 12.6 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/05.%20Combinatorics%20%26%20Probability/0060.%20Permutation%20Sequence/0060.%20Permutation%20Sequence.md) |
| 2 | [3518. Smallest Palindromic Rearrangement II](https://leetcode.com/problems/smallest-palindromic-rearrangement-ii/) | Hard | 6 months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/05.%20Combinatorics%20%26%20Probability/3518.%20Smallest%20Palindromic%20Rearrangement%20II/3518.%20Smallest%20Palindromic%20Rearrangement%20II.md) |
| 3 | [2929. Distribute Candies Among Children II](https://leetcode.com/problems/distribute-candies-among-children-ii/) | Medium | 6+ months | 7.4 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/05.%20Combinatorics%20%26%20Probability/2929.%20Distribute%20Candies%20Among%20Children%20II/2929.%20Distribute%20Candies%20Among%20Children%20II.md) |
| 4 | [2954. Count the Number of Infection Sequences](https://leetcode.com/problems/count-the-number-of-infection-sequences/) | Hard | 6+ months | 6.3 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/05.%20Combinatorics%20%26%20Probability/2954.%20Count%20the%20Number%20of%20Infection%20Sequences/2954.%20Count%20the%20Number%20of%20Infection%20Sequences.md) |
| 5 | [357. Count Numbers with Unique Digits](https://leetcode.com/problems/count-numbers-with-unique-digits/) | Medium | 6+ months | 5.1 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/05.%20Combinatorics%20%26%20Probability/0357.%20Count%20Numbers%20with%20Unique%20Digits/0357.%20Count%20Numbers%20with%20Unique%20Digits.md) |
| 6 | [3272. Find the Count of Good Integers](https://leetcode.com/problems/find-the-count-of-good-integers/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/05.%20Combinatorics%20%26%20Probability/3272.%20Find%20the%20Count%20of%20Good%20Integers/3272.%20Find%20the%20Count%20of%20Good%20Integers.md) |
| 7 | [3405. Count the Number of Arrays with K Matching Adjacent Elements](https://leetcode.com/problems/count-the-number-of-arrays-with-k-matching-adjacent-elements/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/05.%20Combinatorics%20%26%20Probability/3405.%20Count%20the%20Number%20of%20Arrays%20with%20K%20Matching%20Adjacent%20Elements/3405.%20Count%20the%20Number%20of%20Arrays%20with%20K%20Matching%20Adjacent%20Elements.md) |
| 8 | [3428. Maximum and Minimum Sums of at Most Size K Subsequences](https://leetcode.com/problems/maximum-and-minimum-sums-of-at-most-size-k-subsequences/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/05.%20Combinatorics%20%26%20Probability/3428.%20Maximum%20and%20Minimum%20Sums%20of%20at%20Most%20Size%20K%20Subsequences/3428.%20Maximum%20and%20Minimum%20Sums%20of%20at%20Most%20Size%20K%20Subsequences.md) |
| 9 | [3461. Check If Digits Are Equal in String After Operations I](https://leetcode.com/problems/check-if-digits-are-equal-in-string-after-operations-i/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/05.%20Combinatorics%20%26%20Probability/3461.%20Check%20If%20Digits%20Are%20Equal%20in%20String%20After%20Operations%20I/3461.%20Check%20If%20Digits%20Are%20Equal%20in%20String%20After%20Operations%20I.md) |
| 10 | [3577. Count the Number of Computer Unlocking Permutations](https://leetcode.com/problems/count-the-number-of-computer-unlocking-permutations/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/05.%20Combinatorics%20%26%20Probability/3577.%20Count%20the%20Number%20of%20Computer%20Unlocking%20Permutations/3577.%20Count%20the%20Number%20of%20Computer%20Unlocking%20Permutations.md) |
| 11 | [3623. Count Number of Trapezoids I](https://leetcode.com/problems/count-number-of-trapezoids-i/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/05.%20Combinatorics%20%26%20Probability/3623.%20Count%20Number%20of%20Trapezoids%20I/3623.%20Count%20Number%20of%20Trapezoids%20I.md) |
| 12 | [750. Number Of Corner Rectangles](https://leetcode.com/problems/number-of-corner-rectangles/) 🔒 | Medium | 6+ months | 36.1 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/05.%20Combinatorics%20%26%20Probability/0750.%20Number%20Of%20Corner%20Rectangles/0750.%20Number%20Of%20Corner%20Rectangles.md) |

### 08.06. Geometry

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [149. Max Points on a Line](https://leetcode.com/problems/max-points-on-a-line/) | Hard | 6+ months | 19.2 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/06.%20Geometry/0149.%20Max%20Points%20on%20a%20Line/0149.%20Max%20Points%20on%20a%20Line.md) |
| 2 | [1266. Minimum Time Visiting All Points](https://leetcode.com/problems/minimum-time-visiting-all-points/) | Easy | 6+ months | 17.9 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/06.%20Geometry/1266.%20Minimum%20Time%20Visiting%20All%20Points/1266.%20Minimum%20Time%20Visiting%20All%20Points.md) |
| 3 | [3047. Find the Largest Area of Square Inside Two Rectangles](https://leetcode.com/problems/find-the-largest-area-of-square-inside-two-rectangles/) | Medium | 6+ months | 11.4 | ✅ Solved |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/06.%20Geometry/3047.%20Find%20the%20Largest%20Area%20of%20Square%20Inside%20Two%20Rectangles/3047.%20Find%20the%20Largest%20Area%20of%20Square%20Inside%20Two%20Rectangles.md) |
| 4 | [223. Rectangle Area](https://leetcode.com/problems/rectangle-area/) | Medium | 6+ months | 10.3 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/06.%20Geometry/0223.%20Rectangle%20Area/0223.%20Rectangle%20Area.md) |
| 5 | [593. Valid Square](https://leetcode.com/problems/valid-square/) | Medium | 6+ months | 9.6 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/06.%20Geometry/0593.%20Valid%20Square/0593.%20Valid%20Square.md) |
| 6 | [3625. Count Number of Trapezoids II](https://leetcode.com/problems/count-number-of-trapezoids-ii/) | Hard | 6+ months | 7.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/06.%20Geometry/3625.%20Count%20Number%20of%20Trapezoids%20II/3625.%20Count%20Number%20of%20Trapezoids%20II.md) |
| 7 | [836. Rectangle Overlap](https://leetcode.com/problems/rectangle-overlap/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/06.%20Geometry/0836.%20Rectangle%20Overlap/0836.%20Rectangle%20Overlap.md) |
| 8 | [3024. Type of Triangle](https://leetcode.com/problems/type-of-triangle/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/06.%20Geometry/3024.%20Type%20of%20Triangle/3024.%20Type%20of%20Triangle.md) |
| 9 | [3025. Find the Number of Ways to Place People I](https://leetcode.com/problems/find-the-number-of-ways-to-place-people-i/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/06.%20Geometry/3025.%20Find%20the%20Number%20of%20Ways%20to%20Place%20People%20I/3025.%20Find%20the%20Number%20of%20Ways%20to%20Place%20People%20I.md) |
| 10 | [3027. Find the Number of Ways to Place People II](https://leetcode.com/problems/find-the-number-of-ways-to-place-people-ii/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/06.%20Geometry/3027.%20Find%20the%20Number%20of%20Ways%20to%20Place%20People%20II/3027.%20Find%20the%20Number%20of%20Ways%20to%20Place%20People%20II.md) |
| 11 | [1453. Maximum Number of Darts Inside of a Circular Dartboard](https://leetcode.com/problems/maximum-number-of-darts-inside-of-a-circular-dartboard/) | Hard | 6+ months | 36.1 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/06.%20Geometry/1453.%20Maximum%20Number%20of%20Darts%20Inside%20of%20a%20Circular%20Dartboard/1453.%20Maximum%20Number%20of%20Darts%20Inside%20of%20a%20Circular%20Dartboard.md) |

### 08.07. Game Theory

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [877. Stone Game](https://leetcode.com/problems/stone-game/) | Medium | 6 months | 18.7 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/07.%20Game%20Theory/0877.%20Stone%20Game/0877.%20Stone%20Game.md) |
| 2 | [292. Nim Game](https://leetcode.com/problems/nim-game/) | Easy | 6 months | 5.5 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/07.%20Game%20Theory/0292.%20Nim%20Game/0292.%20Nim%20Game.md) |
| 3 | [1025. Divisor Game](https://leetcode.com/problems/divisor-game/) | Easy | 6+ months | 11.8 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/07.%20Game%20Theory/1025.%20Divisor%20Game/1025.%20Divisor%20Game.md) |
| 4 | [2029. Stone Game IX](https://leetcode.com/problems/stone-game-ix/) | Medium | 6+ months | 7.7 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/07.%20Game%20Theory/2029.%20Stone%20Game%20IX/2029.%20Stone%20Game%20IX.md) |
| 5 | [3227. Vowels Game in a String](https://leetcode.com/problems/vowels-game-in-a-string/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/07.%20Game%20Theory/3227.%20Vowels%20Game%20in%20a%20String/3227.%20Vowels%20Game%20in%20a%20String.md) |

### 08.08. Randomized & Sampling

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [398. Random Pick Index](https://leetcode.com/problems/random-pick-index/) | Medium | 6+ months | 57.4 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/08.%20Randomized%20%26%20Sampling/0398.%20Random%20Pick%20Index/0398.%20Random%20Pick%20Index.md) |
| 2 | [843. Guess the Word](https://leetcode.com/problems/guess-the-word/) | Hard | 6+ months | 11.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/08.%20Randomized%20%26%20Sampling/0843.%20Guess%20the%20Word/0843.%20Guess%20the%20Word.md) |
| 3 | [478. Generate Random Point in a Circle](https://leetcode.com/problems/generate-random-point-in-a-circle/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/08.%20Randomized%20%26%20Sampling/0478.%20Generate%20Random%20Point%20in%20a%20Circle/0478.%20Generate%20Random%20Point%20in%20a%20Circle.md) |

### 08.09. Big Number Arithmetic

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [67. Add Binary](https://leetcode.com/problems/add-binary/) | Easy | 3 months | 49.6 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/09.%20Big%20Number%20Arithmetic/0067.%20Add%20Binary/0067.%20Add%20Binary.md) |
| 2 | [415. Add Strings](https://leetcode.com/problems/add-strings/) | Easy | 6 months | 59.6 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/09.%20Big%20Number%20Arithmetic/0415.%20Add%20Strings/0415.%20Add%20Strings.md) |
| 3 | [43. Multiply Strings](https://leetcode.com/problems/multiply-strings/) | Medium | 6+ months | 51.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/09.%20Big%20Number%20Arithmetic/0043.%20Multiply%20Strings/0043.%20Multiply%20Strings.md) |
| 4 | [989. Add to Array-Form of Integer](https://leetcode.com/problems/add-to-array-form-of-integer/) | Easy | 6+ months | 39.0 | Todo |  |  |  | [notes](08.%20Math%20%26%20Number%20Theory/09.%20Big%20Number%20Arithmetic/0989.%20Add%20to%20Array-Form%20of%20Integer/0989.%20Add%20to%20Array-Form%20of%20Integer.md) |

## 09. Bit Manipulation

33 problems: 19 Easy, 14 Medium, 0 Hard. [Open chapter README](09.%20Bit%20Manipulation/README.md) · [Back to top](#chapters)

### 09.01. Bit Basics & Counting

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [231. Power of Two](https://leetcode.com/problems/power-of-two/) | Easy | 3 months | 37.5 | Todo |  |  |  | [notes](09.%20Bit%20Manipulation/01.%20Bit%20Basics%20%26%20Counting/0231.%20Power%20of%20Two/0231.%20Power%20of%20Two.md) |
| 2 | [477. Total Hamming Distance](https://leetcode.com/problems/total-hamming-distance/) | Medium | 6+ months | 38.1 | Todo |  |  |  | [notes](09.%20Bit%20Manipulation/01.%20Bit%20Basics%20%26%20Counting/0477.%20Total%20Hamming%20Distance/0477.%20Total%20Hamming%20Distance.md) |
| 3 | [29. Divide Two Integers](https://leetcode.com/problems/divide-two-integers/) | Medium | 6+ months | 30.2 | Todo |  |  |  | [notes](09.%20Bit%20Manipulation/01.%20Bit%20Basics%20%26%20Counting/0029.%20Divide%20Two%20Integers/0029.%20Divide%20Two%20Integers.md) |
| 4 | [405. Convert a Number to Hexadecimal](https://leetcode.com/problems/convert-a-number-to-hexadecimal/) | Easy | 6+ months | 17.0 | Todo |  |  |  | [notes](09.%20Bit%20Manipulation/01.%20Bit%20Basics%20%26%20Counting/0405.%20Convert%20a%20Number%20to%20Hexadecimal/0405.%20Convert%20a%20Number%20to%20Hexadecimal.md) |
| 5 | [191. Number of 1 Bits](https://leetcode.com/problems/number-of-1-bits/) | Easy | 6+ months | 14.4 | Todo |  |  |  | [notes](09.%20Bit%20Manipulation/01.%20Bit%20Basics%20%26%20Counting/0191.%20Number%20of%201%20Bits/0191.%20Number%20of%201%20Bits.md) |
| 6 | [190. Reverse Bits](https://leetcode.com/problems/reverse-bits/) | Easy | 6+ months | 12.5 | Todo |  |  |  | [notes](09.%20Bit%20Manipulation/01.%20Bit%20Basics%20%26%20Counting/0190.%20Reverse%20Bits/0190.%20Reverse%20Bits.md) |
| 7 | [476. Number Complement](https://leetcode.com/problems/number-complement/) | Easy | 6+ months | 7.9 | Todo |  |  |  | [notes](09.%20Bit%20Manipulation/01.%20Bit%20Basics%20%26%20Counting/0476.%20Number%20Complement/0476.%20Number%20Complement.md) |
| 8 | [1404. Number of Steps to Reduce a Number in Binary Representation to One](https://leetcode.com/problems/number-of-steps-to-reduce-a-number-in-binary-representation-to-one/) | Medium | 6+ months | 7.2 | ✅ Solved |  |  |  | [notes](09.%20Bit%20Manipulation/01.%20Bit%20Basics%20%26%20Counting/1404.%20Number%20of%20Steps%20to%20Reduce%20a%20Number%20in%20Binary%20Representation%20to%20One/1404.%20Number%20of%20Steps%20to%20Reduce%20a%20Number%20in%20Binary%20Representation%20to%20One.md) |
| 9 | [371. Sum of Two Integers](https://leetcode.com/problems/sum-of-two-integers/) | Medium | 6+ months | 7.0 | Todo |  |  |  | [notes](09.%20Bit%20Manipulation/01.%20Bit%20Basics%20%26%20Counting/0371.%20Sum%20of%20Two%20Integers/0371.%20Sum%20of%20Two%20Integers.md) |
| 10 | [338. Counting Bits](https://leetcode.com/problems/counting-bits/) | Easy | 6+ months | 6.7 | Todo |  |  |  | [notes](09.%20Bit%20Manipulation/01.%20Bit%20Basics%20%26%20Counting/0338.%20Counting%20Bits/0338.%20Counting%20Bits.md) |
| 11 | [2749. Minimum Operations to Make the Integer Zero](https://leetcode.com/problems/minimum-operations-to-make-the-integer-zero/) | Medium | 6+ months | 6.3 | Todo |  |  |  | [notes](09.%20Bit%20Manipulation/01.%20Bit%20Basics%20%26%20Counting/2749.%20Minimum%20Operations%20to%20Make%20the%20Integer%20Zero/2749.%20Minimum%20Operations%20to%20Make%20the%20Integer%20Zero.md) |
| 12 | [342. Power of Four](https://leetcode.com/problems/power-of-four/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](09.%20Bit%20Manipulation/01.%20Bit%20Basics%20%26%20Counting/0342.%20Power%20of%20Four/0342.%20Power%20of%20Four.md) |
| 13 | [393. UTF-8 Validation](https://leetcode.com/problems/utf-8-validation/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](09.%20Bit%20Manipulation/01.%20Bit%20Basics%20%26%20Counting/0393.%20UTF-8%20Validation/0393.%20UTF-8%20Validation.md) |
| 14 | [397. Integer Replacement](https://leetcode.com/problems/integer-replacement/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](09.%20Bit%20Manipulation/01.%20Bit%20Basics%20%26%20Counting/0397.%20Integer%20Replacement/0397.%20Integer%20Replacement.md) |
| 15 | [1009. Complement of Base 10 Integer](https://leetcode.com/problems/complement-of-base-10-integer/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](09.%20Bit%20Manipulation/01.%20Bit%20Basics%20%26%20Counting/1009.%20Complement%20of%20Base%2010%20Integer/1009.%20Complement%20of%20Base%2010%20Integer.md) |
| 16 | [1342. Number of Steps to Reduce a Number to Zero](https://leetcode.com/problems/number-of-steps-to-reduce-a-number-to-zero/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](09.%20Bit%20Manipulation/01.%20Bit%20Basics%20%26%20Counting/1342.%20Number%20of%20Steps%20to%20Reduce%20a%20Number%20to%20Zero/1342.%20Number%20of%20Steps%20to%20Reduce%20a%20Number%20to%20Zero.md) |
| 17 | [3315. Construct the Minimum Bitwise Array II](https://leetcode.com/problems/construct-the-minimum-bitwise-array-ii/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](09.%20Bit%20Manipulation/01.%20Bit%20Basics%20%26%20Counting/3315.%20Construct%20the%20Minimum%20Bitwise%20Array%20II/3315.%20Construct%20the%20Minimum%20Bitwise%20Array%20II.md) |
| 18 | [3644. Maximum K to Sort a Permutation](https://leetcode.com/problems/maximum-k-to-sort-a-permutation/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](09.%20Bit%20Manipulation/01.%20Bit%20Basics%20%26%20Counting/3644.%20Maximum%20K%20to%20Sort%20a%20Permutation/3644.%20Maximum%20K%20to%20Sort%20a%20Permutation.md) |
| 19 | [461. Hamming Distance](https://leetcode.com/problems/hamming-distance/) | Easy | 6+ months | 36.1 | Todo |  |  |  | [notes](09.%20Bit%20Manipulation/01.%20Bit%20Basics%20%26%20Counting/0461.%20Hamming%20Distance/0461.%20Hamming%20Distance.md) |
| 20 | [3688. Bitwise OR of Even Numbers in an Array](https://leetcode.com/problems/bitwise-or-of-even-numbers-in-an-array/) | Easy | 6+ months | 36.1 | Todo |  |  |  | [notes](09.%20Bit%20Manipulation/01.%20Bit%20Basics%20%26%20Counting/3688.%20Bitwise%20OR%20of%20Even%20Numbers%20in%20an%20Array/3688.%20Bitwise%20OR%20of%20Even%20Numbers%20in%20an%20Array.md) |
| 21 | [751. IP to CIDR](https://leetcode.com/problems/ip-to-cidr/) 🔒 | Medium | 6+ months | 6.5 | Todo |  |  |  | [notes](09.%20Bit%20Manipulation/01.%20Bit%20Basics%20%26%20Counting/0751.%20IP%20to%20CIDR/0751.%20IP%20to%20CIDR.md) |
| 22 | [1018. Binary Prefix Divisible By 5](https://leetcode.com/problems/binary-prefix-divisible-by-5/) | Easy | 6+ months | 5.8 | Todo |  |  |  | [notes](09.%20Bit%20Manipulation/01.%20Bit%20Basics%20%26%20Counting/1018.%20Binary%20Prefix%20Divisible%20By%205/1018.%20Binary%20Prefix%20Divisible%20By%205.md) |
| 23 | [2595. Number of Even and Odd Bits](https://leetcode.com/problems/number-of-even-and-odd-bits/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](09.%20Bit%20Manipulation/01.%20Bit%20Basics%20%26%20Counting/2595.%20Number%20of%20Even%20and%20Odd%20Bits/2595.%20Number%20of%20Even%20and%20Odd%20Bits.md) |

### 09.02. XOR Tricks

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [136. Single Number](https://leetcode.com/problems/single-number/) | Easy | 3 months | 41.3 | ✅ Solved |  |  |  | [notes](09.%20Bit%20Manipulation/02.%20XOR%20Tricks/0136.%20Single%20Number/0136.%20Single%20Number.md) |
| 2 | [137. Single Number II](https://leetcode.com/problems/single-number-ii/) | Medium | 3 months | 28.9 | Todo |  |  |  | [notes](09.%20Bit%20Manipulation/02.%20XOR%20Tricks/0137.%20Single%20Number%20II/0137.%20Single%20Number%20II.md) |
| 3 | [268. Missing Number](https://leetcode.com/problems/missing-number/) | Easy | 6 months | 50.1 | ✅ Solved |  |  |  | [notes](09.%20Bit%20Manipulation/02.%20XOR%20Tricks/0268.%20Missing%20Number/0268.%20Missing%20Number.md) |
| 4 | [389. Find the Difference](https://leetcode.com/problems/find-the-difference/) | Easy | 6+ months | 14.3 | ✅ Solved |  |  |  | [notes](09.%20Bit%20Manipulation/02.%20XOR%20Tricks/0389.%20Find%20the%20Difference/0389.%20Find%20the%20Difference.md) |
| 5 | [2220. Minimum Bit Flips to Convert Number](https://leetcode.com/problems/minimum-bit-flips-to-convert-number/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](09.%20Bit%20Manipulation/02.%20XOR%20Tricks/2220.%20Minimum%20Bit%20Flips%20to%20Convert%20Number/2220.%20Minimum%20Bit%20Flips%20to%20Convert%20Number.md) |
| 6 | [3158. Find the XOR of Numbers Which Appear Twice](https://leetcode.com/problems/find-the-xor-of-numbers-which-appear-twice/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](09.%20Bit%20Manipulation/02.%20XOR%20Tricks/3158.%20Find%20the%20XOR%20of%20Numbers%20Which%20Appear%20Twice/3158.%20Find%20the%20XOR%20of%20Numbers%20Which%20Appear%20Twice.md) |

### 09.03. Bitmask Enumeration

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [1386. Cinema Seat Allocation](https://leetcode.com/problems/cinema-seat-allocation/) | Medium | 6 months | 11.5 | Todo |  |  |  | [notes](09.%20Bit%20Manipulation/03.%20Bitmask%20Enumeration/1386.%20Cinema%20Seat%20Allocation/1386.%20Cinema%20Seat%20Allocation.md) |
| 2 | [401. Binary Watch](https://leetcode.com/problems/binary-watch/) | Easy | 6+ months | 5.7 | Todo |  |  |  | [notes](09.%20Bit%20Manipulation/03.%20Bitmask%20Enumeration/0401.%20Binary%20Watch/0401.%20Binary%20Watch.md) |

### 09.04. Bitwise Operations on Ranges

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [898. Bitwise ORs of Subarrays](https://leetcode.com/problems/bitwise-ors-of-subarrays/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](09.%20Bit%20Manipulation/04.%20Bitwise%20Operations%20on%20Ranges/0898.%20Bitwise%20ORs%20of%20Subarrays/0898.%20Bitwise%20ORs%20of%20Subarrays.md) |
| 2 | [2411. Smallest Subarrays With Maximum Bitwise OR](https://leetcode.com/problems/smallest-subarrays-with-maximum-bitwise-or/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](09.%20Bit%20Manipulation/04.%20Bitwise%20Operations%20on%20Ranges/2411.%20Smallest%20Subarrays%20With%20Maximum%20Bitwise%20OR/2411.%20Smallest%20Subarrays%20With%20Maximum%20Bitwise%20OR.md) |

## 10. Stack & Queue

67 problems: 14 Easy, 40 Medium, 13 Hard. [Open chapter README](10.%20Stack%20%26%20Queue/README.md) · [Back to top](#chapters)

### 10.01. Stack Basics

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [682. Baseball Game](https://leetcode.com/problems/baseball-game/) | Easy | 6 months | 19.6 | ✅ Solved |  |  |  | [notes](10.%20Stack%20%26%20Queue/01.%20Stack%20Basics/0682.%20Baseball%20Game/0682.%20Baseball%20Game.md) |
| 2 | [2696. Minimum String Length After Removing Substrings](https://leetcode.com/problems/minimum-string-length-after-removing-substrings/) | Easy | 6 months | 5.0 | Todo |  |  |  | [notes](10.%20Stack%20%26%20Queue/01.%20Stack%20Basics/2696.%20Minimum%20String%20Length%20After%20Removing%20Substrings/2696.%20Minimum%20String%20Length%20After%20Removing%20Substrings.md) |
| 3 | [1047. Remove All Adjacent Duplicates In String](https://leetcode.com/problems/remove-all-adjacent-duplicates-in-string/) | Easy | 6+ months | 49.3 | Todo |  |  |  | [notes](10.%20Stack%20%26%20Queue/01.%20Stack%20Basics/1047.%20Remove%20All%20Adjacent%20Duplicates%20In%20String/1047.%20Remove%20All%20Adjacent%20Duplicates%20In%20String.md) |
| 4 | [1209. Remove All Adjacent Duplicates in String II](https://leetcode.com/problems/remove-all-adjacent-duplicates-in-string-ii/) | Medium | 6+ months | 38.7 | Todo |  |  |  | [notes](10.%20Stack%20%26%20Queue/01.%20Stack%20Basics/1209.%20Remove%20All%20Adjacent%20Duplicates%20in%20String%20II/1209.%20Remove%20All%20Adjacent%20Duplicates%20in%20String%20II.md) |
| 5 | [1598. Crawler Log Folder](https://leetcode.com/problems/crawler-log-folder/) | Easy | 6+ months | 7.8 | Todo |  |  |  | [notes](10.%20Stack%20%26%20Queue/01.%20Stack%20Basics/1598.%20Crawler%20Log%20Folder/1598.%20Crawler%20Log%20Folder.md) |
| 6 | [3561. Resulting String After Adjacent Removals](https://leetcode.com/problems/resulting-string-after-adjacent-removals/) | Medium | 6+ months | 6.4 | Todo |  |  |  | [notes](10.%20Stack%20%26%20Queue/01.%20Stack%20Basics/3561.%20Resulting%20String%20After%20Adjacent%20Removals/3561.%20Resulting%20String%20After%20Adjacent%20Removals.md) |
| 7 | [1910. Remove All Occurrences of a Substring](https://leetcode.com/problems/remove-all-occurrences-of-a-substring/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](10.%20Stack%20%26%20Queue/01.%20Stack%20Basics/1910.%20Remove%20All%20Occurrences%20of%20a%20Substring/1910.%20Remove%20All%20Occurrences%20of%20a%20Substring.md) |
| 8 | [3174. Clear Digits](https://leetcode.com/problems/clear-digits/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](10.%20Stack%20%26%20Queue/01.%20Stack%20Basics/3174.%20Clear%20Digits/3174.%20Clear%20Digits.md) |

### 10.02. Parentheses & Bracket Matching

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [20. Valid Parentheses](https://leetcode.com/problems/valid-parentheses/) | Easy | 30 days | 78.9 | ✅ Solved |  |  |  | [notes](10.%20Stack%20%26%20Queue/02.%20Parentheses%20%26%20Bracket%20Matching/0020.%20Valid%20Parentheses/0020.%20Valid%20Parentheses.md) |
| 2 | [921. Minimum Add to Make Parentheses Valid](https://leetcode.com/problems/minimum-add-to-make-parentheses-valid/) | Medium | 3 months | 68.4 | Todo |  |  |  | [notes](10.%20Stack%20%26%20Queue/02.%20Parentheses%20%26%20Bracket%20Matching/0921.%20Minimum%20Add%20to%20Make%20Parentheses%20Valid/0921.%20Minimum%20Add%20to%20Make%20Parentheses%20Valid.md) |
| 3 | [32. Longest Valid Parentheses](https://leetcode.com/problems/longest-valid-parentheses/) | Hard | 3 months | 54.0 | Todo |  |  |  | [notes](10.%20Stack%20%26%20Queue/02.%20Parentheses%20%26%20Bracket%20Matching/0032.%20Longest%20Valid%20Parentheses/0032.%20Longest%20Valid%20Parentheses.md) |
| 4 | [856. Score of Parentheses](https://leetcode.com/problems/score-of-parentheses/) | Medium | 3 months | 20.5 | Todo |  |  |  | [notes](10.%20Stack%20%26%20Queue/02.%20Parentheses%20%26%20Bracket%20Matching/0856.%20Score%20of%20Parentheses/0856.%20Score%20of%20Parentheses.md) |
| 5 | [1541. Minimum Insertions to Balance a Parentheses String](https://leetcode.com/problems/minimum-insertions-to-balance-a-parentheses-string/) | Medium | 3 months | 18.1 | Todo |  |  |  | [notes](10.%20Stack%20%26%20Queue/02.%20Parentheses%20%26%20Bracket%20Matching/1541.%20Minimum%20Insertions%20to%20Balance%20a%20Parentheses%20String/1541.%20Minimum%20Insertions%20to%20Balance%20a%20Parentheses%20String.md) |
| 6 | [1249. Minimum Remove to Make Valid Parentheses](https://leetcode.com/problems/minimum-remove-to-make-valid-parentheses/) | Medium | 6 months | 100.0 | ✅ Solved |  |  |  | [notes](10.%20Stack%20%26%20Queue/02.%20Parentheses%20%26%20Bracket%20Matching/1249.%20Minimum%20Remove%20to%20Make%20Valid%20Parentheses/1249.%20Minimum%20Remove%20to%20Make%20Valid%20Parentheses.md) |
| 7 | [1614. Maximum Nesting Depth of the Parentheses](https://leetcode.com/problems/maximum-nesting-depth-of-the-parentheses/) | Easy | 6 months | 25.1 | ✅ Solved |  |  |  | [notes](10.%20Stack%20%26%20Queue/02.%20Parentheses%20%26%20Bracket%20Matching/1614.%20Maximum%20Nesting%20Depth%20of%20the%20Parentheses/1614.%20Maximum%20Nesting%20Depth%20of%20the%20Parentheses.md) |
| 8 | [1021. Remove Outermost Parentheses](https://leetcode.com/problems/remove-outermost-parentheses/) | Easy | 6 months | 20.2 | Todo |  |  |  | [notes](10.%20Stack%20%26%20Queue/02.%20Parentheses%20%26%20Bracket%20Matching/1021.%20Remove%20Outermost%20Parentheses/1021.%20Remove%20Outermost%20Parentheses.md) |
| 9 | [1190. Reverse Substrings Between Each Pair of Parentheses](https://leetcode.com/problems/reverse-substrings-between-each-pair-of-parentheses/) | Medium | 6+ months | 7.8 | ✅ Solved |  |  |  | [notes](10.%20Stack%20%26%20Queue/02.%20Parentheses%20%26%20Bracket%20Matching/1190.%20Reverse%20Substrings%20Between%20Each%20Pair%20of%20Parentheses/1190.%20Reverse%20Substrings%20Between%20Each%20Pair%20of%20Parentheses.md) |

### 10.03. Expression Evaluation & Calculator

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [227. Basic Calculator II](https://leetcode.com/problems/basic-calculator-ii/) | Medium | 3 months | 86.0 | Todo |  |  |  | [notes](10.%20Stack%20%26%20Queue/03.%20Expression%20Evaluation%20%26%20Calculator/0227.%20Basic%20Calculator%20II/0227.%20Basic%20Calculator%20II.md) |
| 2 | [394. Decode String](https://leetcode.com/problems/decode-string/) | Medium | 3 months | 53.0 | Todo |  |  |  | [notes](10.%20Stack%20%26%20Queue/03.%20Expression%20Evaluation%20%26%20Calculator/0394.%20Decode%20String/0394.%20Decode%20String.md) |
| 3 | [150. Evaluate Reverse Polish Notation](https://leetcode.com/problems/evaluate-reverse-polish-notation/) | Medium | 3 months | 39.6 | ✅ Solved |  |  |  | [notes](10.%20Stack%20%26%20Queue/03.%20Expression%20Evaluation%20%26%20Calculator/0150.%20Evaluate%20Reverse%20Polish%20Notation/0150.%20Evaluate%20Reverse%20Polish%20Notation.md) |
| 4 | [224. Basic Calculator](https://leetcode.com/problems/basic-calculator/) | Hard | 6+ months | 40.1 | Todo |  |  |  | [notes](10.%20Stack%20%26%20Queue/03.%20Expression%20Evaluation%20%26%20Calculator/0224.%20Basic%20Calculator/0224.%20Basic%20Calculator.md) |
| 5 | [385. Mini Parser](https://leetcode.com/problems/mini-parser/) | Medium | 6+ months | 6.8 | Todo |  |  |  | [notes](10.%20Stack%20%26%20Queue/03.%20Expression%20Evaluation%20%26%20Calculator/0385.%20Mini%20Parser/0385.%20Mini%20Parser.md) |
| 6 | [772. Basic Calculator III](https://leetcode.com/problems/basic-calculator-iii/) 🔒 | Hard | 6+ months | 5.8 | Todo |  |  |  | [notes](10.%20Stack%20%26%20Queue/03.%20Expression%20Evaluation%20%26%20Calculator/0772.%20Basic%20Calculator%20III/0772.%20Basic%20Calculator%20III.md) |
| 7 | [1106. Parsing A Boolean Expression](https://leetcode.com/problems/parsing-a-boolean-expression/) | Hard | 6+ months | 5.3 | Todo |  |  |  | [notes](10.%20Stack%20%26%20Queue/03.%20Expression%20Evaluation%20%26%20Calculator/1106.%20Parsing%20A%20Boolean%20Expression/1106.%20Parsing%20A%20Boolean%20Expression.md) |
| 8 | [1006. Clumsy Factorial](https://leetcode.com/problems/clumsy-factorial/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](10.%20Stack%20%26%20Queue/03.%20Expression%20Evaluation%20%26%20Calculator/1006.%20Clumsy%20Factorial/1006.%20Clumsy%20Factorial.md) |

### 10.04. Monotonic Stack

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [739. Daily Temperatures](https://leetcode.com/problems/daily-temperatures/) | Medium | 6 months | 43.6 | ✅ Solved |  |  |  | [notes](10.%20Stack%20%26%20Queue/04.%20Monotonic%20Stack/0739.%20Daily%20Temperatures/0739.%20Daily%20Temperatures.md) |
| 2 | [496. Next Greater Element I](https://leetcode.com/problems/next-greater-element-i/) | Easy | 6 months | 42.3 | ✅ Solved |  |  |  | [notes](10.%20Stack%20%26%20Queue/04.%20Monotonic%20Stack/0496.%20Next%20Greater%20Element%20I/0496.%20Next%20Greater%20Element%20I.md) |
| 3 | [503. Next Greater Element II](https://leetcode.com/problems/next-greater-element-ii/) | Medium | 6 months | 30.8 | ✅ Solved |  |  |  | [notes](10.%20Stack%20%26%20Queue/04.%20Monotonic%20Stack/0503.%20Next%20Greater%20Element%20II/0503.%20Next%20Greater%20Element%20II.md) |
| 4 | [901. Online Stock Span](https://leetcode.com/problems/online-stock-span/) | Medium | 6 months | 25.0 | ✅ Solved |  |  |  | [notes](10.%20Stack%20%26%20Queue/04.%20Monotonic%20Stack/0901.%20Online%20Stock%20Span/0901.%20Online%20Stock%20Span.md) |
| 5 | [1762. Buildings With an Ocean View](https://leetcode.com/problems/buildings-with-an-ocean-view/) 🔒 | Medium | 6+ months | 83.3 | Todo |  |  |  | [notes](10.%20Stack%20%26%20Queue/04.%20Monotonic%20Stack/1762.%20Buildings%20With%20an%20Ocean%20View/1762.%20Buildings%20With%20an%20Ocean%20View.md) |
| 6 | [85. Maximal Rectangle](https://leetcode.com/problems/maximal-rectangle/) | Hard | 6+ months | 44.2 | ✅ Solved |  |  |  | [notes](10.%20Stack%20%26%20Queue/04.%20Monotonic%20Stack/0085.%20Maximal%20Rectangle/0085.%20Maximal%20Rectangle.md) |
| 7 | [84. Largest Rectangle in Histogram](https://leetcode.com/problems/largest-rectangle-in-histogram/) | Hard | 6+ months | 38.7 | ✅ Solved |  |  |  | [notes](10.%20Stack%20%26%20Queue/04.%20Monotonic%20Stack/0084.%20Largest%20Rectangle%20in%20Histogram/0084.%20Largest%20Rectangle%20in%20Histogram.md) |
| 8 | [402. Remove K Digits](https://leetcode.com/problems/remove-k-digits/) | Medium | 6+ months | 26.6 | ✅ Solved |  |  |  | [notes](10.%20Stack%20%26%20Queue/04.%20Monotonic%20Stack/0402.%20Remove%20K%20Digits/0402.%20Remove%20K%20Digits.md) |
| 9 | [1944. Number of Visible People in a Queue](https://leetcode.com/problems/number-of-visible-people-in-a-queue/) | Hard | 6+ months | 15.3 | Todo |  |  |  | [notes](10.%20Stack%20%26%20Queue/04.%20Monotonic%20Stack/1944.%20Number%20of%20Visible%20People%20in%20a%20Queue/1944.%20Number%20of%20Visible%20People%20in%20a%20Queue.md) |
| 10 | [316. Remove Duplicate Letters](https://leetcode.com/problems/remove-duplicate-letters/) | Medium | 6+ months | 14.3 | Todo |  |  |  | [notes](10.%20Stack%20%26%20Queue/04.%20Monotonic%20Stack/0316.%20Remove%20Duplicate%20Letters/0316.%20Remove%20Duplicate%20Letters.md) |
| 11 | [907. Sum of Subarray Minimums](https://leetcode.com/problems/sum-of-subarray-minimums/) | Medium | 6+ months | 13.4 | ✅ Solved |  |  |  | [notes](10.%20Stack%20%26%20Queue/04.%20Monotonic%20Stack/0907.%20Sum%20of%20Subarray%20Minimums/0907.%20Sum%20of%20Subarray%20Minimums.md) |
| 12 | [456. 132 Pattern](https://leetcode.com/problems/132-pattern/) | Medium | 6+ months | 11.4 | Todo |  |  |  | [notes](10.%20Stack%20%26%20Queue/04.%20Monotonic%20Stack/0456.%20132%20Pattern/0456.%20132%20Pattern.md) |
| 13 | [2104. Sum of Subarray Ranges](https://leetcode.com/problems/sum-of-subarray-ranges/) | Medium | 6+ months | 10.0 | ✅ Solved |  |  |  | [notes](10.%20Stack%20%26%20Queue/04.%20Monotonic%20Stack/2104.%20Sum%20of%20Subarray%20Ranges/2104.%20Sum%20of%20Subarray%20Ranges.md) |
| 14 | [1475. Final Prices With a Special Discount in a Shop](https://leetcode.com/problems/final-prices-with-a-special-discount-in-a-shop/) | Easy | 6+ months | 9.4 | Todo |  |  |  | [notes](10.%20Stack%20%26%20Queue/04.%20Monotonic%20Stack/1475.%20Final%20Prices%20With%20a%20Special%20Discount%20in%20a%20Shop/1475.%20Final%20Prices%20With%20a%20Special%20Discount%20in%20a%20Shop.md) |
| 15 | [2487. Remove Nodes From Linked List](https://leetcode.com/problems/remove-nodes-from-linked-list/) | Medium | 6+ months | 7.5 | ✅ Solved |  |  |  | [notes](10.%20Stack%20%26%20Queue/04.%20Monotonic%20Stack/2487.%20Remove%20Nodes%20From%20Linked%20List/2487.%20Remove%20Nodes%20From%20Linked%20List.md) |
| 16 | [853. Car Fleet](https://leetcode.com/problems/car-fleet/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](10.%20Stack%20%26%20Queue/04.%20Monotonic%20Stack/0853.%20Car%20Fleet/0853.%20Car%20Fleet.md) |
| 17 | [1504. Count Submatrices With All Ones](https://leetcode.com/problems/count-submatrices-with-all-ones/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](10.%20Stack%20%26%20Queue/04.%20Monotonic%20Stack/1504.%20Count%20Submatrices%20With%20All%20Ones/1504.%20Count%20Submatrices%20With%20All%20Ones.md) |
| 18 | [2940. Find Building Where Alice and Bob Can Meet](https://leetcode.com/problems/find-building-where-alice-and-bob-can-meet/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](10.%20Stack%20%26%20Queue/04.%20Monotonic%20Stack/2940.%20Find%20Building%20Where%20Alice%20and%20Bob%20Can%20Meet/2940.%20Find%20Building%20Where%20Alice%20and%20Bob%20Can%20Meet.md) |
| 19 | [3542. Minimum Operations to Convert All Elements to Zero](https://leetcode.com/problems/minimum-operations-to-convert-all-elements-to-zero/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](10.%20Stack%20%26%20Queue/04.%20Monotonic%20Stack/3542.%20Minimum%20Operations%20to%20Convert%20All%20Elements%20to%20Zero/3542.%20Minimum%20Operations%20to%20Convert%20All%20Elements%20to%20Zero.md) |
| 20 | [3816. Lexicographically Smallest String After Deleting Duplicate Characters](https://leetcode.com/problems/lexicographically-smallest-string-after-deleting-duplicate-characters/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](10.%20Stack%20%26%20Queue/04.%20Monotonic%20Stack/3816.%20Lexicographically%20Smallest%20String%20After%20Deleting%20Duplicate%20Characters/3816.%20Lexicographically%20Smallest%20String%20After%20Deleting%20Duplicate%20Characters.md) |
| 21 | [2289. Steps to Make Array Non-decreasing](https://leetcode.com/problems/steps-to-make-array-non-decreasing/) | Medium | 6+ months | 36.1 | Todo |  |  |  | [notes](10.%20Stack%20%26%20Queue/04.%20Monotonic%20Stack/2289.%20Steps%20to%20Make%20Array%20Non-decreasing/2289.%20Steps%20to%20Make%20Array%20Non-decreasing.md) |
| 22 | [2454. Next Greater Element IV](https://leetcode.com/problems/next-greater-element-iv/) | Hard | 6+ months | 6.8 | Todo |  |  |  | [notes](10.%20Stack%20%26%20Queue/04.%20Monotonic%20Stack/2454.%20Next%20Greater%20Element%20IV/2454.%20Next%20Greater%20Element%20IV.md) |
| 23 | [1081. Smallest Subsequence of Distinct Characters](https://leetcode.com/problems/smallest-subsequence-of-distinct-characters/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](10.%20Stack%20%26%20Queue/04.%20Monotonic%20Stack/1081.%20Smallest%20Subsequence%20of%20Distinct%20Characters/1081.%20Smallest%20Subsequence%20of%20Distinct%20Characters.md) |

### 10.05. Monotonic Deque

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [862. Shortest Subarray with Sum at Least K](https://leetcode.com/problems/shortest-subarray-with-sum-at-least-k/) | Hard | 3 months | 11.9 | Todo |  |  |  | [notes](10.%20Stack%20%26%20Queue/05.%20Monotonic%20Deque/0862.%20Shortest%20Subarray%20with%20Sum%20at%20Least%20K/0862.%20Shortest%20Subarray%20with%20Sum%20at%20Least%20K.md) |
| 2 | [239. Sliding Window Maximum](https://leetcode.com/problems/sliding-window-maximum/) | Hard | 6 months | 50.4 | ✅ Solved |  |  |  | [notes](10.%20Stack%20%26%20Queue/05.%20Monotonic%20Deque/0239.%20Sliding%20Window%20Maximum/0239.%20Sliding%20Window%20Maximum.md) |
| 3 | [2762. Continuous Subarrays](https://leetcode.com/problems/continuous-subarrays/) | Medium | 6+ months | 5.2 | Todo |  |  |  | [notes](10.%20Stack%20%26%20Queue/05.%20Monotonic%20Deque/2762.%20Continuous%20Subarrays/2762.%20Continuous%20Subarrays.md) |
| 4 | [1438. Longest Continuous Subarray With Absolute Diff Less Than or Equal to Limit](https://leetcode.com/problems/longest-continuous-subarray-with-absolute-diff-less-than-or-equal-to-limit/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](10.%20Stack%20%26%20Queue/05.%20Monotonic%20Deque/1438.%20Longest%20Continuous%20Subarray%20With%20Absolute%20Diff%20Less%20Than%20or%20Equal%20to%20Limit/1438.%20Longest%20Continuous%20Subarray%20With%20Absolute%20Diff%20Less%20Than%20or%20Equal%20to%20Limit.md) |
| 5 | [1696. Jump Game VI](https://leetcode.com/problems/jump-game-vi/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](10.%20Stack%20%26%20Queue/05.%20Monotonic%20Deque/1696.%20Jump%20Game%20VI/1696.%20Jump%20Game%20VI.md) |
| 6 | [3578. Count Partitions With Max-Min Difference at Most K](https://leetcode.com/problems/count-partitions-with-max-min-difference-at-most-k/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](10.%20Stack%20%26%20Queue/05.%20Monotonic%20Deque/3578.%20Count%20Partitions%20With%20Max-Min%20Difference%20at%20Most%20K/3578.%20Count%20Partitions%20With%20Max-Min%20Difference%20at%20Most%20K.md) |

### 10.06. Queue Basics

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [2073. Time Needed to Buy Tickets](https://leetcode.com/problems/time-needed-to-buy-tickets/) | Easy | 6 months | 5.0 | ✅ Solved |  |  |  | [notes](10.%20Stack%20%26%20Queue/06.%20Queue%20Basics/2073.%20Time%20Needed%20to%20Buy%20Tickets/2073.%20Time%20Needed%20to%20Buy%20Tickets.md) |
| 2 | [225. Implement Stack using Queues](https://leetcode.com/problems/implement-stack-using-queues/) | Easy | 6+ months | 24.5 | Todo |  |  |  | [notes](10.%20Stack%20%26%20Queue/06.%20Queue%20Basics/0225.%20Implement%20Stack%20using%20Queues/0225.%20Implement%20Stack%20using%20Queues.md) |
| 3 | [232. Implement Queue using Stacks](https://leetcode.com/problems/implement-queue-using-stacks/) | Easy | 6+ months | 21.8 | Todo |  |  |  | [notes](10.%20Stack%20%26%20Queue/06.%20Queue%20Basics/0232.%20Implement%20Queue%20using%20Stacks/0232.%20Implement%20Queue%20using%20Stacks.md) |
| 4 | [1700. Number of Students Unable to Eat Lunch](https://leetcode.com/problems/number-of-students-unable-to-eat-lunch/) | Easy | 6+ months | 8.0 | ✅ Solved |  |  |  | [notes](10.%20Stack%20%26%20Queue/06.%20Queue%20Basics/1700.%20Number%20of%20Students%20Unable%20to%20Eat%20Lunch/1700.%20Number%20of%20Students%20Unable%20to%20Eat%20Lunch.md) |
| 5 | [649. Dota2 Senate](https://leetcode.com/problems/dota2-senate/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](10.%20Stack%20%26%20Queue/06.%20Queue%20Basics/0649.%20Dota2%20Senate/0649.%20Dota2%20Senate.md) |

### 10.07. Stack Simulation (Asteroid, Path)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [735. Asteroid Collision](https://leetcode.com/problems/asteroid-collision/) | Medium | 3 months | 32.1 | ✅ Solved |  |  |  | [notes](10.%20Stack%20%26%20Queue/07.%20Stack%20Simulation%20%28Asteroid%2C%20Path%29/0735.%20Asteroid%20Collision/0735.%20Asteroid%20Collision.md) |
| 2 | [71. Simplify Path](https://leetcode.com/problems/simplify-path/) | Medium | 6 months | 83.2 | Todo |  |  |  | [notes](10.%20Stack%20%26%20Queue/07.%20Stack%20Simulation%20%28Asteroid%2C%20Path%29/0071.%20Simplify%20Path/0071.%20Simplify%20Path.md) |
| 3 | [636. Exclusive Time of Functions](https://leetcode.com/problems/exclusive-time-of-functions/) | Medium | 6+ months | 67.3 | Todo |  |  |  | [notes](10.%20Stack%20%26%20Queue/07.%20Stack%20Simulation%20%28Asteroid%2C%20Path%29/0636.%20Exclusive%20Time%20of%20Functions/0636.%20Exclusive%20Time%20of%20Functions.md) |
| 4 | [946. Validate Stack Sequences](https://leetcode.com/problems/validate-stack-sequences/) | Medium | 6+ months | 13.4 | Todo |  |  |  | [notes](10.%20Stack%20%26%20Queue/07.%20Stack%20Simulation%20%28Asteroid%2C%20Path%29/0946.%20Validate%20Stack%20Sequences/0946.%20Validate%20Stack%20Sequences.md) |
| 5 | [388. Longest Absolute File Path](https://leetcode.com/problems/longest-absolute-file-path/) | Medium | 6+ months | 9.4 | Todo |  |  |  | [notes](10.%20Stack%20%26%20Queue/07.%20Stack%20Simulation%20%28Asteroid%2C%20Path%29/0388.%20Longest%20Absolute%20File%20Path/0388.%20Longest%20Absolute%20File%20Path.md) |
| 6 | [2434. Using a Robot to Print the Lexicographically Smallest String](https://leetcode.com/problems/using-a-robot-to-print-the-lexicographically-smallest-string/) | Medium | 6+ months | 8.2 | Todo |  |  |  | [notes](10.%20Stack%20%26%20Queue/07.%20Stack%20Simulation%20%28Asteroid%2C%20Path%29/2434.%20Using%20a%20Robot%20to%20Print%20the%20Lexicographically%20Smallest%20String/2434.%20Using%20a%20Robot%20to%20Print%20the%20Lexicographically%20Smallest%20String.md) |
| 7 | [880. Decoded String at Index](https://leetcode.com/problems/decoded-string-at-index/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](10.%20Stack%20%26%20Queue/07.%20Stack%20Simulation%20%28Asteroid%2C%20Path%29/0880.%20Decoded%20String%20at%20Index/0880.%20Decoded%20String%20at%20Index.md) |
| 8 | [2751. Robot Collisions](https://leetcode.com/problems/robot-collisions/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](10.%20Stack%20%26%20Queue/07.%20Stack%20Simulation%20%28Asteroid%2C%20Path%29/2751.%20Robot%20Collisions/2751.%20Robot%20Collisions.md) |

## 11. Binary Search

54 problems: 14 Easy, 32 Medium, 8 Hard. [Open chapter README](11.%20Binary%20Search/README.md) · [Back to top](#chapters)

### 11.01. Classic Binary Search

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [704. Binary Search](https://leetcode.com/problems/binary-search/) | Easy | 3 months | 31.6 | ✅ Solved |  |  |  | [notes](11.%20Binary%20Search/01.%20Classic%20Binary%20Search/0704.%20Binary%20Search/0704.%20Binary%20Search.md) |
| 2 | [540. Single Element in a Sorted Array](https://leetcode.com/problems/single-element-in-a-sorted-array/) | Medium | 6 months | 45.7 | ✅ Solved |  |  |  | [notes](11.%20Binary%20Search/01.%20Classic%20Binary%20Search/0540.%20Single%20Element%20in%20a%20Sorted%20Array/0540.%20Single%20Element%20in%20a%20Sorted%20Array.md) |
| 3 | [374. Guess Number Higher or Lower](https://leetcode.com/problems/guess-number-higher-or-lower/) | Easy | 6+ months | 6.5 | ✅ Solved |  |  |  | [notes](11.%20Binary%20Search/01.%20Classic%20Binary%20Search/0374.%20Guess%20Number%20Higher%20or%20Lower/0374.%20Guess%20Number%20Higher%20or%20Lower.md) |

### 11.02. Lower & Upper Bound

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [34. Find First and Last Position of Element in Sorted Array](https://leetcode.com/problems/find-first-and-last-position-of-element-in-sorted-array/) | Medium | 3 months | 71.8 | Todo |  |  |  | [notes](11.%20Binary%20Search/02.%20Lower%20%26%20Upper%20Bound/0034.%20Find%20First%20and%20Last%20Position%20of%20Element%20in%20Sorted%20Array/0034.%20Find%20First%20and%20Last%20Position%20of%20Element%20in%20Sorted%20Array.md) |
| 2 | [1385. Find the Distance Value Between Two Arrays](https://leetcode.com/problems/find-the-distance-value-between-two-arrays/) | Easy | 3 months | 9.5 | ✅ Solved |  |  |  | [notes](11.%20Binary%20Search/02.%20Lower%20%26%20Upper%20Bound/1385.%20Find%20the%20Distance%20Value%20Between%20Two%20Arrays/1385.%20Find%20the%20Distance%20Value%20Between%20Two%20Arrays.md) |
| 3 | [278. First Bad Version](https://leetcode.com/problems/first-bad-version/) | Easy | 6 months | 44.6 | ✅ Solved |  |  |  | [notes](11.%20Binary%20Search/02.%20Lower%20%26%20Upper%20Bound/0278.%20First%20Bad%20Version/0278.%20First%20Bad%20Version.md) |
| 4 | [35. Search Insert Position](https://leetcode.com/problems/search-insert-position/) | Easy | 6 months | 43.7 | ✅ Solved |  |  |  | [notes](11.%20Binary%20Search/02.%20Lower%20%26%20Upper%20Bound/0035.%20Search%20Insert%20Position/0035.%20Search%20Insert%20Position.md) |
| 5 | [658. Find K Closest Elements](https://leetcode.com/problems/find-k-closest-elements/) | Medium | 6 months | 36.5 | Todo |  |  |  | [notes](11.%20Binary%20Search/02.%20Lower%20%26%20Upper%20Bound/0658.%20Find%20K%20Closest%20Elements/0658.%20Find%20K%20Closest%20Elements.md) |
| 6 | [1539. Kth Missing Positive Number](https://leetcode.com/problems/kth-missing-positive-number/) | Easy | 6+ months | 64.9 | Todo |  |  |  | [notes](11.%20Binary%20Search/02.%20Lower%20%26%20Upper%20Bound/1539.%20Kth%20Missing%20Positive%20Number/1539.%20Kth%20Missing%20Positive%20Number.md) |
| 7 | [1060. Missing Element in Sorted Array](https://leetcode.com/problems/missing-element-in-sorted-array/) 🔒 | Medium | 6+ months | 41.3 | Todo |  |  |  | [notes](11.%20Binary%20Search/02.%20Lower%20%26%20Upper%20Bound/1060.%20Missing%20Element%20in%20Sorted%20Array/1060.%20Missing%20Element%20in%20Sorted%20Array.md) |
| 8 | [275. H-Index II](https://leetcode.com/problems/h-index-ii/) | Medium | 6+ months | 36.1 | Todo |  |  |  | [notes](11.%20Binary%20Search/02.%20Lower%20%26%20Upper%20Bound/0275.%20H-Index%20II/0275.%20H-Index%20II.md) |
| 9 | [744. Find Smallest Letter Greater Than Target](https://leetcode.com/problems/find-smallest-letter-greater-than-target/) | Easy | 6+ months | 18.6 | ✅ Solved |  |  |  | [notes](11.%20Binary%20Search/02.%20Lower%20%26%20Upper%20Bound/0744.%20Find%20Smallest%20Letter%20Greater%20Than%20Target/0744.%20Find%20Smallest%20Letter%20Greater%20Than%20Target.md) |
| 10 | [2300. Successful Pairs of Spells and Potions](https://leetcode.com/problems/successful-pairs-of-spells-and-potions/) | Medium | 6+ months | 6.9 | Todo |  |  |  | [notes](11.%20Binary%20Search/02.%20Lower%20%26%20Upper%20Bound/2300.%20Successful%20Pairs%20of%20Spells%20and%20Potions/2300.%20Successful%20Pairs%20of%20Spells%20and%20Potions.md) |
| 11 | [475. Heaters](https://leetcode.com/problems/heaters/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](11.%20Binary%20Search/02.%20Lower%20%26%20Upper%20Bound/0475.%20Heaters/0475.%20Heaters.md) |
| 12 | [2250. Count Number of Rectangles Containing Each Point](https://leetcode.com/problems/count-number-of-rectangles-containing-each-point/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](11.%20Binary%20Search/02.%20Lower%20%26%20Upper%20Bound/2250.%20Count%20Number%20of%20Rectangles%20Containing%20Each%20Point/2250.%20Count%20Number%20of%20Rectangles%20Containing%20Each%20Point.md) |
| 13 | [2389. Longest Subsequence With Limited Sum](https://leetcode.com/problems/longest-subsequence-with-limited-sum/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](11.%20Binary%20Search/02.%20Lower%20%26%20Upper%20Bound/2389.%20Longest%20Subsequence%20With%20Limited%20Sum/2389.%20Longest%20Subsequence%20With%20Limited%20Sum.md) |
| 14 | [2529. Maximum Count of Positive Integer and Negative Integer](https://leetcode.com/problems/maximum-count-of-positive-integer-and-negative-integer/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](11.%20Binary%20Search/02.%20Lower%20%26%20Upper%20Bound/2529.%20Maximum%20Count%20of%20Positive%20Integer%20and%20Negative%20Integer/2529.%20Maximum%20Count%20of%20Positive%20Integer%20and%20Negative%20Integer.md) |

### 11.03. Rotated Sorted Array

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [33. Search in Rotated Sorted Array](https://leetcode.com/problems/search-in-rotated-sorted-array/) | Medium | 3 months | 61.3 | ✅ Solved |  |  |  | [notes](11.%20Binary%20Search/03.%20Rotated%20Sorted%20Array/0033.%20Search%20in%20Rotated%20Sorted%20Array/0033.%20Search%20in%20Rotated%20Sorted%20Array.md) |
| 2 | [153. Find Minimum in Rotated Sorted Array](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/) | Medium | 6+ months | 32.8 | ✅ Solved |  |  |  | [notes](11.%20Binary%20Search/03.%20Rotated%20Sorted%20Array/0153.%20Find%20Minimum%20in%20Rotated%20Sorted%20Array/0153.%20Find%20Minimum%20in%20Rotated%20Sorted%20Array.md) |
| 3 | [81. Search in Rotated Sorted Array II](https://leetcode.com/problems/search-in-rotated-sorted-array-ii/) | Medium | 6+ months | 27.5 | Todo |  |  |  | [notes](11.%20Binary%20Search/03.%20Rotated%20Sorted%20Array/0081.%20Search%20in%20Rotated%20Sorted%20Array%20II/0081.%20Search%20in%20Rotated%20Sorted%20Array%20II.md) |
| 4 | [154. Find Minimum in Rotated Sorted Array II](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array-ii/) | Hard | 6+ months | 8.2 | Todo |  |  |  | [notes](11.%20Binary%20Search/03.%20Rotated%20Sorted%20Array/0154.%20Find%20Minimum%20in%20Rotated%20Sorted%20Array%20II/0154.%20Find%20Minimum%20in%20Rotated%20Sorted%20Array%20II.md) |

### 11.04. Binary Search on Answer

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [69. Sqrt(x)](https://leetcode.com/problems/sqrtx/) | Easy | 3 months | 49.1 | Todo |  |  |  | [notes](11.%20Binary%20Search/04.%20Binary%20Search%20on%20Answer/0069.%20Sqrt%28x%29/0069.%20Sqrt%28x%29.md) |
| 2 | [441. Arranging Coins](https://leetcode.com/problems/arranging-coins/) | Easy | 3 months | 20.0 | Todo |  |  |  | [notes](11.%20Binary%20Search/04.%20Binary%20Search%20on%20Answer/0441.%20Arranging%20Coins/0441.%20Arranging%20Coins.md) |
| 3 | [875. Koko Eating Bananas](https://leetcode.com/problems/koko-eating-bananas/) | Medium | 6 months | 56.1 | ✅ Solved |  |  |  | [notes](11.%20Binary%20Search/04.%20Binary%20Search%20on%20Answer/0875.%20Koko%20Eating%20Bananas/0875.%20Koko%20Eating%20Bananas.md) |
| 4 | [410. Split Array Largest Sum](https://leetcode.com/problems/split-array-largest-sum/) | Hard | 6 months | 51.5 | ✅ Solved |  |  |  | [notes](11.%20Binary%20Search/04.%20Binary%20Search%20on%20Answer/0410.%20Split%20Array%20Largest%20Sum/0410.%20Split%20Array%20Largest%20Sum.md) |
| 5 | [1011. Capacity To Ship Packages Within D Days](https://leetcode.com/problems/capacity-to-ship-packages-within-d-days/) | Medium | 6 months | 42.3 | ✅ Solved |  |  |  | [notes](11.%20Binary%20Search/04.%20Binary%20Search%20on%20Answer/1011.%20Capacity%20To%20Ship%20Packages%20Within%20D%20Days/1011.%20Capacity%20To%20Ship%20Packages%20Within%20D%20Days.md) |
| 6 | [1482. Minimum Number of Days to Make m Bouquets](https://leetcode.com/problems/minimum-number-of-days-to-make-m-bouquets/) | Medium | 6 months | 25.0 | Todo |  |  |  | [notes](11.%20Binary%20Search/04.%20Binary%20Search%20on%20Answer/1482.%20Minimum%20Number%20of%20Days%20to%20Make%20m%20Bouquets/1482.%20Minimum%20Number%20of%20Days%20to%20Make%20m%20Bouquets.md) |
| 7 | [1283. Find the Smallest Divisor Given a Threshold](https://leetcode.com/problems/find-the-smallest-divisor-given-a-threshold/) | Medium | 6 months | 19.8 | Todo |  |  |  | [notes](11.%20Binary%20Search/04.%20Binary%20Search%20on%20Answer/1283.%20Find%20the%20Smallest%20Divisor%20Given%20a%20Threshold/1283.%20Find%20the%20Smallest%20Divisor%20Given%20a%20Threshold.md) |
| 8 | [367. Valid Perfect Square](https://leetcode.com/problems/valid-perfect-square/) | Easy | 6 months | 9.3 | Todo |  |  |  | [notes](11.%20Binary%20Search/04.%20Binary%20Search%20on%20Answer/0367.%20Valid%20Perfect%20Square/0367.%20Valid%20Perfect%20Square.md) |
| 9 | [1891. Cutting Ribbons](https://leetcode.com/problems/cutting-ribbons/) 🔒 | Medium | 6+ months | 25.4 | Todo |  |  |  | [notes](11.%20Binary%20Search/04.%20Binary%20Search%20on%20Answer/1891.%20Cutting%20Ribbons/1891.%20Cutting%20Ribbons.md) |
| 10 | [2594. Minimum Time to Repair Cars](https://leetcode.com/problems/minimum-time-to-repair-cars/) | Medium | 6+ months | 14.1 | Todo |  |  |  | [notes](11.%20Binary%20Search/04.%20Binary%20Search%20on%20Answer/2594.%20Minimum%20Time%20to%20Repair%20Cars/2594.%20Minimum%20Time%20to%20Repair%20Cars.md) |
| 11 | [1608. Special Array With X Elements Greater Than or Equal X](https://leetcode.com/problems/special-array-with-x-elements-greater-than-or-equal-x/) | Easy | 6+ months | 10.2 | ✅ Solved |  |  |  | [notes](11.%20Binary%20Search/04.%20Binary%20Search%20on%20Answer/1608.%20Special%20Array%20With%20X%20Elements%20Greater%20Than%20or%20Equal%20X/1608.%20Special%20Array%20With%20X%20Elements%20Greater%20Than%20or%20Equal%20X.md) |
| 12 | [2226. Maximum Candies Allocated to K Children](https://leetcode.com/problems/maximum-candies-allocated-to-k-children/) | Medium | 6+ months | 9.3 | Todo |  |  |  | [notes](11.%20Binary%20Search/04.%20Binary%20Search%20on%20Answer/2226.%20Maximum%20Candies%20Allocated%20to%20K%20Children/2226.%20Maximum%20Candies%20Allocated%20to%20K%20Children.md) |
| 13 | [2187. Minimum Time to Complete Trips](https://leetcode.com/problems/minimum-time-to-complete-trips/) | Medium | 6+ months | 8.6 | Todo |  |  |  | [notes](11.%20Binary%20Search/04.%20Binary%20Search%20on%20Answer/2187.%20Minimum%20Time%20to%20Complete%20Trips/2187.%20Minimum%20Time%20to%20Complete%20Trips.md) |
| 14 | [3453. Separate Squares I](https://leetcode.com/problems/separate-squares-i/) | Medium | 6+ months | 7.6 | Todo |  |  |  | [notes](11.%20Binary%20Search/04.%20Binary%20Search%20on%20Answer/3453.%20Separate%20Squares%20I/3453.%20Separate%20Squares%20I.md) |
| 15 | [2616. Minimize the Maximum Difference of Pairs](https://leetcode.com/problems/minimize-the-maximum-difference-of-pairs/) | Medium | 6+ months | 7.1 | Todo |  |  |  | [notes](11.%20Binary%20Search/04.%20Binary%20Search%20on%20Answer/2616.%20Minimize%20the%20Maximum%20Difference%20of%20Pairs/2616.%20Minimize%20the%20Maximum%20Difference%20of%20Pairs.md) |
| 16 | [1760. Minimum Limit of Balls in a Bag](https://leetcode.com/problems/minimum-limit-of-balls-in-a-bag/) | Medium | 6+ months | 5.7 | ✅ Solved |  |  |  | [notes](11.%20Binary%20Search/04.%20Binary%20Search%20on%20Answer/1760.%20Minimum%20Limit%20of%20Balls%20in%20a%20Bag/1760.%20Minimum%20Limit%20of%20Balls%20in%20a%20Bag.md) |
| 17 | [2560. House Robber IV](https://leetcode.com/problems/house-robber-iv/) | Medium | 6+ months | 5.4 | Todo |  |  |  | [notes](11.%20Binary%20Search/04.%20Binary%20Search%20on%20Answer/2560.%20House%20Robber%20IV/2560.%20House%20Robber%20IV.md) |
| 18 | [668. Kth Smallest Number in Multiplication Table](https://leetcode.com/problems/kth-smallest-number-in-multiplication-table/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](11.%20Binary%20Search/04.%20Binary%20Search%20on%20Answer/0668.%20Kth%20Smallest%20Number%20in%20Multiplication%20Table/0668.%20Kth%20Smallest%20Number%20in%20Multiplication%20Table.md) |
| 19 | [878. Nth Magical Number](https://leetcode.com/problems/nth-magical-number/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](11.%20Binary%20Search/04.%20Binary%20Search%20on%20Answer/0878.%20Nth%20Magical%20Number/0878.%20Nth%20Magical%20Number.md) |
| 20 | [1552. Magnetic Force Between Two Balls](https://leetcode.com/problems/magnetic-force-between-two-balls/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](11.%20Binary%20Search/04.%20Binary%20Search%20on%20Answer/1552.%20Magnetic%20Force%20Between%20Two%20Balls/1552.%20Magnetic%20Force%20Between%20Two%20Balls.md) |
| 21 | [2071. Maximum Number of Tasks You Can Assign](https://leetcode.com/problems/maximum-number-of-tasks-you-can-assign/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](11.%20Binary%20Search/04.%20Binary%20Search%20on%20Answer/2071.%20Maximum%20Number%20of%20Tasks%20You%20Can%20Assign/2071.%20Maximum%20Number%20of%20Tasks%20You%20Can%20Assign.md) |
| 22 | [2141. Maximum Running Time of N Computers](https://leetcode.com/problems/maximum-running-time-of-n-computers/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](11.%20Binary%20Search/04.%20Binary%20Search%20on%20Answer/2141.%20Maximum%20Running%20Time%20of%20N%20Computers/2141.%20Maximum%20Running%20Time%20of%20N%20Computers.md) |
| 23 | [3296. Minimum Number of Seconds to Make Mountain Height Zero](https://leetcode.com/problems/minimum-number-of-seconds-to-make-mountain-height-zero/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](11.%20Binary%20Search/04.%20Binary%20Search%20on%20Answer/3296.%20Minimum%20Number%20of%20Seconds%20to%20Make%20Mountain%20Height%20Zero/3296.%20Minimum%20Number%20of%20Seconds%20to%20Make%20Mountain%20Height%20Zero.md) |
| 24 | [3932. Count K-th Roots in a Range](https://leetcode.com/problems/count-k-th-roots-in-a-range/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](11.%20Binary%20Search/04.%20Binary%20Search%20on%20Answer/3932.%20Count%20K-th%20Roots%20in%20a%20Range/3932.%20Count%20K-th%20Roots%20in%20a%20Range.md) |

### 11.05. Search in 2D Matrix

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [240. Search a 2D Matrix II](https://leetcode.com/problems/search-a-2d-matrix-ii/) | Medium | 6 months | 37.1 | Todo |  |  |  | [notes](11.%20Binary%20Search/05.%20Search%20in%202D%20Matrix/0240.%20Search%20a%202D%20Matrix%20II/0240.%20Search%20a%202D%20Matrix%20II.md) |
| 2 | [74. Search a 2D Matrix](https://leetcode.com/problems/search-a-2d-matrix/) | Medium | 6 months | 36.2 | ✅ Solved |  |  |  | [notes](11.%20Binary%20Search/05.%20Search%20in%202D%20Matrix/0074.%20Search%20a%202D%20Matrix/0074.%20Search%20a%202D%20Matrix.md) |
| 3 | [1351. Count Negative Numbers in a Sorted Matrix](https://leetcode.com/problems/count-negative-numbers-in-a-sorted-matrix/) | Easy | 6+ months | 14.4 | ✅ Solved |  |  |  | [notes](11.%20Binary%20Search/05.%20Search%20in%202D%20Matrix/1351.%20Count%20Negative%20Numbers%20in%20a%20Sorted%20Matrix/1351.%20Count%20Negative%20Numbers%20in%20a%20Sorted%20Matrix.md) |
| 4 | [1428. Leftmost Column with at Least a One](https://leetcode.com/problems/leftmost-column-with-at-least-a-one/) 🔒 | Medium | 6+ months | 36.9 | Todo |  |  |  | [notes](11.%20Binary%20Search/05.%20Search%20in%202D%20Matrix/1428.%20Leftmost%20Column%20with%20at%20Least%20a%20One/1428.%20Leftmost%20Column%20with%20at%20Least%20a%20One.md) |

### 11.06. Peak Finding

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [162. Find Peak Element](https://leetcode.com/problems/find-peak-element/) | Medium | 6 months | 83.3 | Todo |  |  |  | [notes](11.%20Binary%20Search/06.%20Peak%20Finding/0162.%20Find%20Peak%20Element/0162.%20Find%20Peak%20Element.md) |
| 2 | [852. Peak Index in a Mountain Array](https://leetcode.com/problems/peak-index-in-a-mountain-array/) | Medium | 6+ months | 37.6 | Todo |  |  |  | [notes](11.%20Binary%20Search/06.%20Peak%20Finding/0852.%20Peak%20Index%20in%20a%20Mountain%20Array/0852.%20Peak%20Index%20in%20a%20Mountain%20Array.md) |
| 3 | [1901. Find a Peak Element II](https://leetcode.com/problems/find-a-peak-element-ii/) | Medium | 6+ months | 15.2 | Todo |  |  |  | [notes](11.%20Binary%20Search/06.%20Peak%20Finding/1901.%20Find%20a%20Peak%20Element%20II/1901.%20Find%20a%20Peak%20Element%20II.md) |
| 4 | [1095. Find in Mountain Array](https://leetcode.com/problems/find-in-mountain-array/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](11.%20Binary%20Search/06.%20Peak%20Finding/1095.%20Find%20in%20Mountain%20Array/1095.%20Find%20in%20Mountain%20Array.md) |

### 11.07. Binary Search on Two Arrays

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [4. Median of Two Sorted Arrays](https://leetcode.com/problems/median-of-two-sorted-arrays/) | Hard | 30 days | 57.8 | Todo |  |  |  | [notes](11.%20Binary%20Search/07.%20Binary%20Search%20on%20Two%20Arrays/0004.%20Median%20of%20Two%20Sorted%20Arrays/0004.%20Median%20of%20Two%20Sorted%20Arrays.md) |

## 12. Linked List

36 problems: 9 Easy, 26 Medium, 1 Hard. [Open chapter README](12.%20Linked%20List/README.md) · [Back to top](#chapters)

### 12.01. Traversal & Basic Operations

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [237. Delete Node in a Linked List](https://leetcode.com/problems/delete-node-in-a-linked-list/) | Medium | 3 months | 29.4 | ✅ Solved |  |  |  | [notes](12.%20Linked%20List/01.%20Traversal%20%26%20Basic%20Operations/0237.%20Delete%20Node%20in%20a%20Linked%20List/0237.%20Delete%20Node%20in%20a%20Linked%20List.md) |
| 2 | [61. Rotate List](https://leetcode.com/problems/rotate-list/) | Medium | 6 months | 33.0 | Todo |  |  |  | [notes](12.%20Linked%20List/01.%20Traversal%20%26%20Basic%20Operations/0061.%20Rotate%20List/0061.%20Rotate%20List.md) |
| 3 | [83. Remove Duplicates from Sorted List](https://leetcode.com/problems/remove-duplicates-from-sorted-list/) | Easy | 6 months | 23.8 | ✅ Solved |  |  |  | [notes](12.%20Linked%20List/01.%20Traversal%20%26%20Basic%20Operations/0083.%20Remove%20Duplicates%20from%20Sorted%20List/0083.%20Remove%20Duplicates%20from%20Sorted%20List.md) |
| 4 | [708. Insert into a Sorted Circular Linked List](https://leetcode.com/problems/insert-into-a-sorted-circular-linked-list/) 🔒 | Medium | 6+ months | 58.7 | Todo |  |  |  | [notes](12.%20Linked%20List/01.%20Traversal%20%26%20Basic%20Operations/0708.%20Insert%20into%20a%20Sorted%20Circular%20Linked%20List/0708.%20Insert%20into%20a%20Sorted%20Circular%20Linked%20List.md) |
| 5 | [328. Odd Even Linked List](https://leetcode.com/problems/odd-even-linked-list/) | Medium | 6+ months | 25.2 | ✅ Solved |  |  |  | [notes](12.%20Linked%20List/01.%20Traversal%20%26%20Basic%20Operations/0328.%20Odd%20Even%20Linked%20List/0328.%20Odd%20Even%20Linked%20List.md) |
| 6 | [430. Flatten a Multilevel Doubly Linked List](https://leetcode.com/problems/flatten-a-multilevel-doubly-linked-list/) | Medium | 6+ months | 12.3 | Todo |  |  |  | [notes](12.%20Linked%20List/01.%20Traversal%20%26%20Basic%20Operations/0430.%20Flatten%20a%20Multilevel%20Doubly%20Linked%20List/0430.%20Flatten%20a%20Multilevel%20Doubly%20Linked%20List.md) |
| 7 | [725. Split Linked List in Parts](https://leetcode.com/problems/split-linked-list-in-parts/) | Medium | 6+ months | 10.0 | Todo |  |  |  | [notes](12.%20Linked%20List/01.%20Traversal%20%26%20Basic%20Operations/0725.%20Split%20Linked%20List%20in%20Parts/0725.%20Split%20Linked%20List%20in%20Parts.md) |
| 8 | [2058. Find the Minimum and Maximum Number of Nodes Between Critical Points](https://leetcode.com/problems/find-the-minimum-and-maximum-number-of-nodes-between-critical-points/) | Medium | 6+ months | 8.0 | Todo |  |  |  | [notes](12.%20Linked%20List/01.%20Traversal%20%26%20Basic%20Operations/2058.%20Find%20the%20Minimum%20and%20Maximum%20Number%20of%20Nodes%20Between%20Critical%20Points/2058.%20Find%20the%20Minimum%20and%20Maximum%20Number%20of%20Nodes%20Between%20Critical%20Points.md) |
| 9 | [1290. Convert Binary Number in a Linked List to Integer](https://leetcode.com/problems/convert-binary-number-in-a-linked-list-to-integer/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](12.%20Linked%20List/01.%20Traversal%20%26%20Basic%20Operations/1290.%20Convert%20Binary%20Number%20in%20a%20Linked%20List%20to%20Integer/1290.%20Convert%20Binary%20Number%20in%20a%20Linked%20List%20to%20Integer.md) |
| 10 | [2807. Insert Greatest Common Divisors in Linked List](https://leetcode.com/problems/insert-greatest-common-divisors-in-linked-list/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](12.%20Linked%20List/01.%20Traversal%20%26%20Basic%20Operations/2807.%20Insert%20Greatest%20Common%20Divisors%20in%20Linked%20List/2807.%20Insert%20Greatest%20Common%20Divisors%20in%20Linked%20List.md) |

### 12.02. Reversal

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [206. Reverse Linked List](https://leetcode.com/problems/reverse-linked-list/) | Easy | 3 months | 50.8 | ✅ Solved |  |  |  | [notes](12.%20Linked%20List/02.%20Reversal/0206.%20Reverse%20Linked%20List/0206.%20Reverse%20Linked%20List.md) |
| 2 | [25. Reverse Nodes in k-Group](https://leetcode.com/problems/reverse-nodes-in-k-group/) | Hard | 6 months | 45.3 | ✅ Solved |  |  |  | [notes](12.%20Linked%20List/02.%20Reversal/0025.%20Reverse%20Nodes%20in%20k-Group/0025.%20Reverse%20Nodes%20in%20k-Group.md) |
| 3 | [92. Reverse Linked List II](https://leetcode.com/problems/reverse-linked-list-ii/) | Medium | 6 months | 28.6 | Todo |  |  |  | [notes](12.%20Linked%20List/02.%20Reversal/0092.%20Reverse%20Linked%20List%20II/0092.%20Reverse%20Linked%20List%20II.md) |
| 4 | [2074. Reverse Nodes in Even Length Groups](https://leetcode.com/problems/reverse-nodes-in-even-length-groups/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](12.%20Linked%20List/02.%20Reversal/2074.%20Reverse%20Nodes%20in%20Even%20Length%20Groups/2074.%20Reverse%20Nodes%20in%20Even%20Length%20Groups.md) |

### 12.03. Fast & Slow Pointers

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [19. Remove Nth Node From End of List](https://leetcode.com/problems/remove-nth-node-from-end-of-list/) | Medium | 6 months | 61.8 | ✅ Solved |  |  |  | [notes](12.%20Linked%20List/03.%20Fast%20%26%20Slow%20Pointers/0019.%20Remove%20Nth%20Node%20From%20End%20of%20List/0019.%20Remove%20Nth%20Node%20From%20End%20of%20List.md) |
| 2 | [234. Palindrome Linked List](https://leetcode.com/problems/palindrome-linked-list/) | Easy | 6 months | 53.0 | ✅ Solved |  |  |  | [notes](12.%20Linked%20List/03.%20Fast%20%26%20Slow%20Pointers/0234.%20Palindrome%20Linked%20List/0234.%20Palindrome%20Linked%20List.md) |
| 3 | [141. Linked List Cycle](https://leetcode.com/problems/linked-list-cycle/) | Easy | 6 months | 42.0 | ✅ Solved |  |  |  | [notes](12.%20Linked%20List/03.%20Fast%20%26%20Slow%20Pointers/0141.%20Linked%20List%20Cycle/0141.%20Linked%20List%20Cycle.md) |
| 4 | [143. Reorder List](https://leetcode.com/problems/reorder-list/) | Medium | 6 months | 36.0 | ✅ Solved |  |  |  | [notes](12.%20Linked%20List/03.%20Fast%20%26%20Slow%20Pointers/0143.%20Reorder%20List/0143.%20Reorder%20List.md) |
| 5 | [876. Middle of the Linked List](https://leetcode.com/problems/middle-of-the-linked-list/) | Easy | 6 months | 32.6 | ✅ Solved |  |  |  | [notes](12.%20Linked%20List/03.%20Fast%20%26%20Slow%20Pointers/0876.%20Middle%20of%20the%20Linked%20List/0876.%20Middle%20of%20the%20Linked%20List.md) |
| 6 | [160. Intersection of Two Linked Lists](https://leetcode.com/problems/intersection-of-two-linked-lists/) | Easy | 6 months | 28.3 | ✅ Solved |  |  |  | [notes](12.%20Linked%20List/03.%20Fast%20%26%20Slow%20Pointers/0160.%20Intersection%20of%20Two%20Linked%20Lists/0160.%20Intersection%20of%20Two%20Linked%20Lists.md) |
| 7 | [287. Find the Duplicate Number](https://leetcode.com/problems/find-the-duplicate-number/) | Medium | 6 months | 27.0 | ✅ Solved |  |  |  | [notes](12.%20Linked%20List/03.%20Fast%20%26%20Slow%20Pointers/0287.%20Find%20the%20Duplicate%20Number/0287.%20Find%20the%20Duplicate%20Number.md) |
| 8 | [142. Linked List Cycle II](https://leetcode.com/problems/linked-list-cycle-ii/) | Medium | 6 months | 22.8 | ✅ Solved |  |  |  | [notes](12.%20Linked%20List/03.%20Fast%20%26%20Slow%20Pointers/0142.%20Linked%20List%20Cycle%20II/0142.%20Linked%20List%20Cycle%20II.md) |
| 9 | [2095. Delete the Middle Node of a Linked List](https://leetcode.com/problems/delete-the-middle-node-of-a-linked-list/) | Medium | 6+ months | 5.7 | ✅ Solved |  |  |  | [notes](12.%20Linked%20List/03.%20Fast%20%26%20Slow%20Pointers/2095.%20Delete%20the%20Middle%20Node%20of%20a%20Linked%20List/2095.%20Delete%20the%20Middle%20Node%20of%20a%20Linked%20List.md) |
| 10 | [1721. Swapping Nodes in a Linked List](https://leetcode.com/problems/swapping-nodes-in-a-linked-list/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](12.%20Linked%20List/03.%20Fast%20%26%20Slow%20Pointers/1721.%20Swapping%20Nodes%20in%20a%20Linked%20List/1721.%20Swapping%20Nodes%20in%20a%20Linked%20List.md) |
| 11 | [2130. Maximum Twin Sum of a Linked List](https://leetcode.com/problems/maximum-twin-sum-of-a-linked-list/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](12.%20Linked%20List/03.%20Fast%20%26%20Slow%20Pointers/2130.%20Maximum%20Twin%20Sum%20of%20a%20Linked%20List/2130.%20Maximum%20Twin%20Sum%20of%20a%20Linked%20List.md) |

### 12.04. Merge & Sort Lists

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [21. Merge Two Sorted Lists](https://leetcode.com/problems/merge-two-sorted-lists/) | Easy | 3 months | 53.2 | ✅ Solved |  |  |  | [notes](12.%20Linked%20List/04.%20Merge%20%26%20Sort%20Lists/0021.%20Merge%20Two%20Sorted%20Lists/0021.%20Merge%20Two%20Sorted%20Lists.md) |
| 2 | [148. Sort List](https://leetcode.com/problems/sort-list/) | Medium | 6 months | 34.5 | ✅ Solved |  |  |  | [notes](12.%20Linked%20List/04.%20Merge%20%26%20Sort%20Lists/0148.%20Sort%20List/0148.%20Sort%20List.md) |
| 3 | [147. Insertion Sort List](https://leetcode.com/problems/insertion-sort-list/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](12.%20Linked%20List/04.%20Merge%20%26%20Sort%20Lists/0147.%20Insertion%20Sort%20List/0147.%20Insertion%20Sort%20List.md) |

### 12.05. Dummy Node & Deletion

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [24. Swap Nodes in Pairs](https://leetcode.com/problems/swap-nodes-in-pairs/) | Medium | 6 months | 24.6 | Todo |  |  |  | [notes](12.%20Linked%20List/05.%20Dummy%20Node%20%26%20Deletion/0024.%20Swap%20Nodes%20in%20Pairs/0024.%20Swap%20Nodes%20in%20Pairs.md) |
| 2 | [203. Remove Linked List Elements](https://leetcode.com/problems/remove-linked-list-elements/) | Easy | 6 months | 17.6 | ✅ Solved |  |  |  | [notes](12.%20Linked%20List/05.%20Dummy%20Node%20%26%20Deletion/0203.%20Remove%20Linked%20List%20Elements/0203.%20Remove%20Linked%20List%20Elements.md) |
| 3 | [86. Partition List](https://leetcode.com/problems/partition-list/) | Medium | 6+ months | 12.5 | Todo |  |  |  | [notes](12.%20Linked%20List/05.%20Dummy%20Node%20%26%20Deletion/0086.%20Partition%20List/0086.%20Partition%20List.md) |
| 4 | [82. Remove Duplicates from Sorted List II](https://leetcode.com/problems/remove-duplicates-from-sorted-list-ii/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](12.%20Linked%20List/05.%20Dummy%20Node%20%26%20Deletion/0082.%20Remove%20Duplicates%20from%20Sorted%20List%20II/0082.%20Remove%20Duplicates%20from%20Sorted%20List%20II.md) |
| 5 | [3217. Delete Nodes From Linked List Present in Array](https://leetcode.com/problems/delete-nodes-from-linked-list-present-in-array/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](12.%20Linked%20List/05.%20Dummy%20Node%20%26%20Deletion/3217.%20Delete%20Nodes%20From%20Linked%20List%20Present%20in%20Array/3217.%20Delete%20Nodes%20From%20Linked%20List%20Present%20in%20Array.md) |

### 12.06. Add Numbers in Lists

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [2. Add Two Numbers](https://leetcode.com/problems/add-two-numbers/) | Medium | 3 months | 65.3 | ✅ Solved |  |  |  | [notes](12.%20Linked%20List/06.%20Add%20Numbers%20in%20Lists/0002.%20Add%20Two%20Numbers/0002.%20Add%20Two%20Numbers.md) |
| 2 | [445. Add Two Numbers II](https://leetcode.com/problems/add-two-numbers-ii/) | Medium | 6+ months | 8.2 | Todo |  |  |  | [notes](12.%20Linked%20List/06.%20Add%20Numbers%20in%20Lists/0445.%20Add%20Two%20Numbers%20II/0445.%20Add%20Two%20Numbers%20II.md) |

### 12.07. Copy & Clone List

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [138. Copy List with Random Pointer](https://leetcode.com/problems/copy-list-with-random-pointer/) | Medium | 6+ months | 74.7 | ✅ Solved |  |  |  | [notes](12.%20Linked%20List/07.%20Copy%20%26%20Clone%20List/0138.%20Copy%20List%20with%20Random%20Pointer/0138.%20Copy%20List%20with%20Random%20Pointer.md) |

## 13. Recursion & Backtracking

45 problems: 1 Easy, 31 Medium, 13 Hard. [Open chapter README](13.%20Recursion%20%26%20Backtracking/README.md) · [Back to top](#chapters)

### 13.01. Basic Recursion

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [339. Nested List Weight Sum](https://leetcode.com/problems/nested-list-weight-sum/) 🔒 | Medium | 6+ months | 85.1 | Todo |  |  |  | [notes](13.%20Recursion%20%26%20Backtracking/01.%20Basic%20Recursion/0339.%20Nested%20List%20Weight%20Sum/0339.%20Nested%20List%20Weight%20Sum.md) |
| 2 | [1545. Find Kth Bit in Nth Binary String](https://leetcode.com/problems/find-kth-bit-in-nth-binary-string/) | Medium | 6+ months | 18.8 | Todo |  |  |  | [notes](13.%20Recursion%20%26%20Backtracking/01.%20Basic%20Recursion/1545.%20Find%20Kth%20Bit%20in%20Nth%20Binary%20String/1545.%20Find%20Kth%20Bit%20in%20Nth%20Binary%20String.md) |
| 3 | [779. K-th Symbol in Grammar](https://leetcode.com/problems/k-th-symbol-in-grammar/) | Medium | 6+ months | 16.7 | Todo |  |  |  | [notes](13.%20Recursion%20%26%20Backtracking/01.%20Basic%20Recursion/0779.%20K-th%20Symbol%20in%20Grammar/0779.%20K-th%20Symbol%20in%20Grammar.md) |
| 4 | [3304. Find the K-th Character in String Game I](https://leetcode.com/problems/find-the-k-th-character-in-string-game-i/) | Easy | 6+ months | 9.9 | Todo |  |  |  | [notes](13.%20Recursion%20%26%20Backtracking/01.%20Basic%20Recursion/3304.%20Find%20the%20K-th%20Character%20in%20String%20Game%20I/3304.%20Find%20the%20K-th%20Character%20in%20String%20Game%20I.md) |
| 5 | [2625. Flatten Deeply Nested Array](https://leetcode.com/problems/flatten-deeply-nested-array/) | Medium | 6+ months | 8.2 | Todo |  |  |  | [notes](13.%20Recursion%20%26%20Backtracking/01.%20Basic%20Recursion/2625.%20Flatten%20Deeply%20Nested%20Array/2625.%20Flatten%20Deeply%20Nested%20Array.md) |
| 6 | [364. Nested List Weight Sum II](https://leetcode.com/problems/nested-list-weight-sum-ii/) 🔒 | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](13.%20Recursion%20%26%20Backtracking/01.%20Basic%20Recursion/0364.%20Nested%20List%20Weight%20Sum%20II/0364.%20Nested%20List%20Weight%20Sum%20II.md) |

### 13.02. Subsets

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [78. Subsets](https://leetcode.com/problems/subsets/) | Medium | 3 months | 63.4 | ✅ Solved |  |  |  | [notes](13.%20Recursion%20%26%20Backtracking/02.%20Subsets/0078.%20Subsets/0078.%20Subsets.md) |
| 2 | [90. Subsets II](https://leetcode.com/problems/subsets-ii/) | Medium | 6 months | 46.6 | ✅ Solved |  |  |  | [notes](13.%20Recursion%20%26%20Backtracking/02.%20Subsets/0090.%20Subsets%20II/0090.%20Subsets%20II.md) |
| 3 | [784. Letter Case Permutation](https://leetcode.com/problems/letter-case-permutation/) | Medium | 6+ months | 43.4 | Todo |  |  |  | [notes](13.%20Recursion%20%26%20Backtracking/02.%20Subsets/0784.%20Letter%20Case%20Permutation/0784.%20Letter%20Case%20Permutation.md) |
| 4 | [1239. Maximum Length of a Concatenated String with Unique Characters](https://leetcode.com/problems/maximum-length-of-a-concatenated-string-with-unique-characters/) | Medium | 6+ months | 26.8 | Todo |  |  |  | [notes](13.%20Recursion%20%26%20Backtracking/02.%20Subsets/1239.%20Maximum%20Length%20of%20a%20Concatenated%20String%20with%20Unique%20Characters/1239.%20Maximum%20Length%20of%20a%20Concatenated%20String%20with%20Unique%20Characters.md) |
| 5 | [3566. Partition Array into Two Equal Product Subsets](https://leetcode.com/problems/partition-array-into-two-equal-product-subsets/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](13.%20Recursion%20%26%20Backtracking/02.%20Subsets/3566.%20Partition%20Array%20into%20Two%20Equal%20Product%20Subsets/3566.%20Partition%20Array%20into%20Two%20Equal%20Product%20Subsets.md) |

### 13.03. Permutations

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [46. Permutations](https://leetcode.com/problems/permutations/) | Medium | 6 months | 40.8 | ✅ Solved |  |  |  | [notes](13.%20Recursion%20%26%20Backtracking/03.%20Permutations/0046.%20Permutations/0046.%20Permutations.md) |
| 2 | [47. Permutations II](https://leetcode.com/problems/permutations-ii/) | Medium | 6+ months | 13.1 | ✅ Solved |  |  |  | [notes](13.%20Recursion%20%26%20Backtracking/03.%20Permutations/0047.%20Permutations%20II/0047.%20Permutations%20II.md) |
| 3 | [1079. Letter Tile Possibilities](https://leetcode.com/problems/letter-tile-possibilities/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](13.%20Recursion%20%26%20Backtracking/03.%20Permutations/1079.%20Letter%20Tile%20Possibilities/1079.%20Letter%20Tile%20Possibilities.md) |
| 4 | [1718. Construct the Lexicographically Largest Valid Sequence](https://leetcode.com/problems/construct-the-lexicographically-largest-valid-sequence/) | Medium | 6+ months | 36.4 | Todo |  |  |  | [notes](13.%20Recursion%20%26%20Backtracking/03.%20Permutations/1718.%20Construct%20the%20Lexicographically%20Largest%20Valid%20Sequence/1718.%20Construct%20the%20Lexicographically%20Largest%20Valid%20Sequence.md) |

### 13.04. Combinations & Combination Sum

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [77. Combinations](https://leetcode.com/problems/combinations/) | Medium | 3 months | 32.6 | ✅ Solved |  |  |  | [notes](13.%20Recursion%20%26%20Backtracking/04.%20Combinations%20%26%20Combination%20Sum/0077.%20Combinations/0077.%20Combinations.md) |
| 2 | [17. Letter Combinations of a Phone Number](https://leetcode.com/problems/letter-combinations-of-a-phone-number/) | Medium | 6 months | 57.2 | ✅ Solved |  |  |  | [notes](13.%20Recursion%20%26%20Backtracking/04.%20Combinations%20%26%20Combination%20Sum/0017.%20Letter%20Combinations%20of%20a%20Phone%20Number/0017.%20Letter%20Combinations%20of%20a%20Phone%20Number.md) |
| 3 | [39. Combination Sum](https://leetcode.com/problems/combination-sum/) | Medium | 6 months | 47.2 | ✅ Solved |  |  |  | [notes](13.%20Recursion%20%26%20Backtracking/04.%20Combinations%20%26%20Combination%20Sum/0039.%20Combination%20Sum/0039.%20Combination%20Sum.md) |
| 4 | [40. Combination Sum II](https://leetcode.com/problems/combination-sum-ii/) | Medium | 6+ months | 32.3 | ✅ Solved |  |  |  | [notes](13.%20Recursion%20%26%20Backtracking/04.%20Combinations%20%26%20Combination%20Sum/0040.%20Combination%20Sum%20II/0040.%20Combination%20Sum%20II.md) |

### 13.05. Partitioning

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [131. Palindrome Partitioning](https://leetcode.com/problems/palindrome-partitioning/) | Medium | 6 months | 37.6 | ✅ Solved |  |  |  | [notes](13.%20Recursion%20%26%20Backtracking/05.%20Partitioning/0131.%20Palindrome%20Partitioning/0131.%20Palindrome%20Partitioning.md) |
| 2 | [140. Word Break II](https://leetcode.com/problems/word-break-ii/) | Hard | 6+ months | 28.5 | ✅ Solved |  |  |  | [notes](13.%20Recursion%20%26%20Backtracking/05.%20Partitioning/0140.%20Word%20Break%20II/0140.%20Word%20Break%20II.md) |
| 3 | [93. Restore IP Addresses](https://leetcode.com/problems/restore-ip-addresses/) | Medium | 6+ months | 19.4 | Todo |  |  |  | [notes](13.%20Recursion%20%26%20Backtracking/05.%20Partitioning/0093.%20Restore%20IP%20Addresses/0093.%20Restore%20IP%20Addresses.md) |
| 4 | [473. Matchsticks to Square](https://leetcode.com/problems/matchsticks-to-square/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](13.%20Recursion%20%26%20Backtracking/05.%20Partitioning/0473.%20Matchsticks%20to%20Square/0473.%20Matchsticks%20to%20Square.md) |
| 5 | [698. Partition to K Equal Sum Subsets](https://leetcode.com/problems/partition-to-k-equal-sum-subsets/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](13.%20Recursion%20%26%20Backtracking/05.%20Partitioning/0698.%20Partition%20to%20K%20Equal%20Sum%20Subsets/0698.%20Partition%20to%20K%20Equal%20Sum%20Subsets.md) |
| 6 | [1723. Find Minimum Time to Finish All Jobs](https://leetcode.com/problems/find-minimum-time-to-finish-all-jobs/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](13.%20Recursion%20%26%20Backtracking/05.%20Partitioning/1723.%20Find%20Minimum%20Time%20to%20Finish%20All%20Jobs/1723.%20Find%20Minimum%20Time%20to%20Finish%20All%20Jobs.md) |

### 13.06. Board & Grid Search (N-Queens, Sudoku, Word Search)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [51. N-Queens](https://leetcode.com/problems/n-queens/) | Hard | 6 months | 46.5 | ✅ Solved |  |  |  | [notes](13.%20Recursion%20%26%20Backtracking/06.%20Board%20%26%20Grid%20Search%20%28N-Queens%2C%20Sudoku%2C%20Word%20Search%29/0051.%20N-Queens/0051.%20N-Queens.md) |
| 2 | [489. Robot Room Cleaner](https://leetcode.com/problems/robot-room-cleaner/) 🔒 | Hard | 6+ months | 66.8 | Todo |  |  |  | [notes](13.%20Recursion%20%26%20Backtracking/06.%20Board%20%26%20Grid%20Search%20%28N-Queens%2C%20Sudoku%2C%20Word%20Search%29/0489.%20Robot%20Room%20Cleaner/0489.%20Robot%20Room%20Cleaner.md) |
| 3 | [79. Word Search](https://leetcode.com/problems/word-search/) | Medium | 6+ months | 47.5 | ✅ Solved |  |  |  | [notes](13.%20Recursion%20%26%20Backtracking/06.%20Board%20%26%20Grid%20Search%20%28N-Queens%2C%20Sudoku%2C%20Word%20Search%29/0079.%20Word%20Search/0079.%20Word%20Search.md) |
| 4 | [37. Sudoku Solver](https://leetcode.com/problems/sudoku-solver/) | Hard | 6+ months | 24.1 | ✅ Solved |  |  |  | [notes](13.%20Recursion%20%26%20Backtracking/06.%20Board%20%26%20Grid%20Search%20%28N-Queens%2C%20Sudoku%2C%20Word%20Search%29/0037.%20Sudoku%20Solver/0037.%20Sudoku%20Solver.md) |
| 5 | [52. N-Queens II](https://leetcode.com/problems/n-queens-ii/) | Hard | 6+ months | 21.5 | Todo |  |  |  | [notes](13.%20Recursion%20%26%20Backtracking/06.%20Board%20%26%20Grid%20Search%20%28N-Queens%2C%20Sudoku%2C%20Word%20Search%29/0052.%20N-Queens%20II/0052.%20N-Queens%20II.md) |
| 6 | [980. Unique Paths III](https://leetcode.com/problems/unique-paths-iii/) | Hard | 6+ months | 20.4 | Todo |  |  |  | [notes](13.%20Recursion%20%26%20Backtracking/06.%20Board%20%26%20Grid%20Search%20%28N-Queens%2C%20Sudoku%2C%20Word%20Search%29/0980.%20Unique%20Paths%20III/0980.%20Unique%20Paths%20III.md) |

### 13.07. Generate Valid Strings

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [301. Remove Invalid Parentheses](https://leetcode.com/problems/remove-invalid-parentheses/) | Hard | 3 months | 55.3 | Todo |  |  |  | [notes](13.%20Recursion%20%26%20Backtracking/07.%20Generate%20Valid%20Strings/0301.%20Remove%20Invalid%20Parentheses/0301.%20Remove%20Invalid%20Parentheses.md) |
| 2 | [22. Generate Parentheses](https://leetcode.com/problems/generate-parentheses/) | Medium | 3 months | 51.2 | Todo |  |  |  | [notes](13.%20Recursion%20%26%20Backtracking/07.%20Generate%20Valid%20Strings/0022.%20Generate%20Parentheses/0022.%20Generate%20Parentheses.md) |
| 3 | [282. Expression Add Operators](https://leetcode.com/problems/expression-add-operators/) | Hard | 6+ months | 56.9 | ✅ Solved |  |  |  | [notes](13.%20Recursion%20%26%20Backtracking/07.%20Generate%20Valid%20Strings/0282.%20Expression%20Add%20Operators/0282.%20Expression%20Add%20Operators.md) |
| 4 | [247. Strobogrammatic Number II](https://leetcode.com/problems/strobogrammatic-number-ii/) 🔒 | Medium | 6+ months | 25.2 | Todo |  |  |  | [notes](13.%20Recursion%20%26%20Backtracking/07.%20Generate%20Valid%20Strings/0247.%20Strobogrammatic%20Number%20II/0247.%20Strobogrammatic%20Number%20II.md) |
| 5 | [1096. Brace Expansion II](https://leetcode.com/problems/brace-expansion-ii/) | Hard | 6+ months | 12.8 | Todo |  |  |  | [notes](13.%20Recursion%20%26%20Backtracking/07.%20Generate%20Valid%20Strings/1096.%20Brace%20Expansion%20II/1096.%20Brace%20Expansion%20II.md) |
| 6 | [679. 24 Game](https://leetcode.com/problems/24-game/) | Hard | 6+ months | 5.4 | Todo |  |  |  | [notes](13.%20Recursion%20%26%20Backtracking/07.%20Generate%20Valid%20Strings/0679.%2024%20Game/0679.%2024%20Game.md) |
| 7 | [1415. The k-th Lexicographical String of All Happy Strings of Length n](https://leetcode.com/problems/the-k-th-lexicographical-string-of-all-happy-strings-of-length-n/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](13.%20Recursion%20%26%20Backtracking/07.%20Generate%20Valid%20Strings/1415.%20The%20k-th%20Lexicographical%20String%20of%20All%20Happy%20Strings%20of%20Length%20n/1415.%20The%20k-th%20Lexicographical%20String%20of%20All%20Happy%20Strings%20of%20Length%20n.md) |
| 8 | [2048. Next Greater Numerically Balanced Number](https://leetcode.com/problems/next-greater-numerically-balanced-number/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](13.%20Recursion%20%26%20Backtracking/07.%20Generate%20Valid%20Strings/2048.%20Next%20Greater%20Numerically%20Balanced%20Number/2048.%20Next%20Greater%20Numerically%20Balanced%20Number.md) |
| 9 | [2014. Longest Subsequence Repeated k Times](https://leetcode.com/problems/longest-subsequence-repeated-k-times/) | Hard | 6+ months | 36.1 | Todo |  |  |  | [notes](13.%20Recursion%20%26%20Backtracking/07.%20Generate%20Valid%20Strings/2014.%20Longest%20Subsequence%20Repeated%20k%20Times/2014.%20Longest%20Subsequence%20Repeated%20k%20Times.md) |

### 13.08. Divide and Conquer

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [95. Unique Binary Search Trees II](https://leetcode.com/problems/unique-binary-search-trees-ii/) | Medium | 6 months | 26.6 | Todo |  |  |  | [notes](13.%20Recursion%20%26%20Backtracking/08.%20Divide%20and%20Conquer/0095.%20Unique%20Binary%20Search%20Trees%20II/0095.%20Unique%20Binary%20Search%20Trees%20II.md) |
| 2 | [2035. Partition Array Into Two Arrays to Minimize Sum Difference](https://leetcode.com/problems/partition-array-into-two-arrays-to-minimize-sum-difference/) | Hard | 6 months | 5.3 | 🟡 Attempted |  |  |  | [notes](13.%20Recursion%20%26%20Backtracking/08.%20Divide%20and%20Conquer/2035.%20Partition%20Array%20Into%20Two%20Arrays%20to%20Minimize%20Sum%20Difference/2035.%20Partition%20Array%20Into%20Two%20Arrays%20to%20Minimize%20Sum%20Difference.md) |
| 3 | [427. Construct Quad Tree](https://leetcode.com/problems/construct-quad-tree/) | Medium | 6+ months | 8.6 | Todo |  |  |  | [notes](13.%20Recursion%20%26%20Backtracking/08.%20Divide%20and%20Conquer/0427.%20Construct%20Quad%20Tree/0427.%20Construct%20Quad%20Tree.md) |
| 4 | [395. Longest Substring with At Least K Repeating Characters](https://leetcode.com/problems/longest-substring-with-at-least-k-repeating-characters/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](13.%20Recursion%20%26%20Backtracking/08.%20Divide%20and%20Conquer/0395.%20Longest%20Substring%20with%20At%20Least%20K%20Repeating%20Characters/0395.%20Longest%20Substring%20with%20At%20Least%20K%20Repeating%20Characters.md) |
| 5 | [894. All Possible Full Binary Trees](https://leetcode.com/problems/all-possible-full-binary-trees/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](13.%20Recursion%20%26%20Backtracking/08.%20Divide%20and%20Conquer/0894.%20All%20Possible%20Full%20Binary%20Trees/0894.%20All%20Possible%20Full%20Binary%20Trees.md) |

## 14. Trees

103 problems: 30 Easy, 68 Medium, 5 Hard. [Open chapter README](14.%20Trees/README.md) · [Back to top](#chapters)

### 14.01. DFS Traversal (Pre, In, Post)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [101. Symmetric Tree](https://leetcode.com/problems/symmetric-tree/) | Easy | 3 months | 32.0 | ✅ Solved |  |  |  | [notes](14.%20Trees/01.%20DFS%20Traversal%20%28Pre%2C%20In%2C%20Post%29/0101.%20Symmetric%20Tree/0101.%20Symmetric%20Tree.md) |
| 2 | [144. Binary Tree Preorder Traversal](https://leetcode.com/problems/binary-tree-preorder-traversal/) | Easy | 3 months | 12.8 | ✅ Solved |  |  |  | [notes](14.%20Trees/01.%20DFS%20Traversal%20%28Pre%2C%20In%2C%20Post%29/0144.%20Binary%20Tree%20Preorder%20Traversal/0144.%20Binary%20Tree%20Preorder%20Traversal.md) |
| 3 | [94. Binary Tree Inorder Traversal](https://leetcode.com/problems/binary-tree-inorder-traversal/) | Easy | 6 months | 36.3 | ✅ Solved |  |  |  | [notes](14.%20Trees/01.%20DFS%20Traversal%20%28Pre%2C%20In%2C%20Post%29/0094.%20Binary%20Tree%20Inorder%20Traversal/0094.%20Binary%20Tree%20Inorder%20Traversal.md) |
| 4 | [100. Same Tree](https://leetcode.com/problems/same-tree/) | Easy | 6 months | 35.4 | ✅ Solved |  |  |  | [notes](14.%20Trees/01.%20DFS%20Traversal%20%28Pre%2C%20In%2C%20Post%29/0100.%20Same%20Tree/0100.%20Same%20Tree.md) |
| 5 | [404. Sum of Left Leaves](https://leetcode.com/problems/sum-of-left-leaves/) | Easy | 6+ months | 41.0 | ✅ Solved |  |  |  | [notes](14.%20Trees/01.%20DFS%20Traversal%20%28Pre%2C%20In%2C%20Post%29/0404.%20Sum%20of%20Left%20Leaves/0404.%20Sum%20of%20Left%20Leaves.md) |
| 6 | [572. Subtree of Another Tree](https://leetcode.com/problems/subtree-of-another-tree/) | Easy | 6+ months | 40.9 | Todo |  |  |  | [notes](14.%20Trees/01.%20DFS%20Traversal%20%28Pre%2C%20In%2C%20Post%29/0572.%20Subtree%20of%20Another%20Tree/0572.%20Subtree%20of%20Another%20Tree.md) |
| 7 | [1379. Find a Corresponding Node of a Binary Tree in a Clone of That Tree](https://leetcode.com/problems/find-a-corresponding-node-of-a-binary-tree-in-a-clone-of-that-tree/) | Easy | 6+ months | 39.5 | Todo |  |  |  | [notes](14.%20Trees/01.%20DFS%20Traversal%20%28Pre%2C%20In%2C%20Post%29/1379.%20Find%20a%20Corresponding%20Node%20of%20a%20Binary%20Tree%20in%20a%20Clone%20of%20That%20Tree/1379.%20Find%20a%20Corresponding%20Node%20of%20a%20Binary%20Tree%20in%20a%20Clone%20of%20That%20Tree.md) |
| 8 | [1448. Count Good Nodes in Binary Tree](https://leetcode.com/problems/count-good-nodes-in-binary-tree/) | Medium | 6+ months | 9.3 | Todo |  |  |  | [notes](14.%20Trees/01.%20DFS%20Traversal%20%28Pre%2C%20In%2C%20Post%29/1448.%20Count%20Good%20Nodes%20in%20Binary%20Tree/1448.%20Count%20Good%20Nodes%20in%20Binary%20Tree.md) |
| 9 | [979. Distribute Coins in Binary Tree](https://leetcode.com/problems/distribute-coins-in-binary-tree/) | Medium | 6+ months | 8.3 | ✅ Solved |  |  |  | [notes](14.%20Trees/01.%20DFS%20Traversal%20%28Pre%2C%20In%2C%20Post%29/0979.%20Distribute%20Coins%20in%20Binary%20Tree/0979.%20Distribute%20Coins%20in%20Binary%20Tree.md) |
| 10 | [671. Second Minimum Node In a Binary Tree](https://leetcode.com/problems/second-minimum-node-in-a-binary-tree/) | Easy | 6+ months | 5.3 | Todo |  |  |  | [notes](14.%20Trees/01.%20DFS%20Traversal%20%28Pre%2C%20In%2C%20Post%29/0671.%20Second%20Minimum%20Node%20In%20a%20Binary%20Tree/0671.%20Second%20Minimum%20Node%20In%20a%20Binary%20Tree.md) |
| 11 | [145. Binary Tree Postorder Traversal](https://leetcode.com/problems/binary-tree-postorder-traversal/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](14.%20Trees/01.%20DFS%20Traversal%20%28Pre%2C%20In%2C%20Post%29/0145.%20Binary%20Tree%20Postorder%20Traversal/0145.%20Binary%20Tree%20Postorder%20Traversal.md) |
| 12 | [872. Leaf-Similar Trees](https://leetcode.com/problems/leaf-similar-trees/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](14.%20Trees/01.%20DFS%20Traversal%20%28Pre%2C%20In%2C%20Post%29/0872.%20Leaf-Similar%20Trees/0872.%20Leaf-Similar%20Trees.md) |
| 13 | [1315. Sum of Nodes with Even-Valued Grandparent](https://leetcode.com/problems/sum-of-nodes-with-even-valued-grandparent/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](14.%20Trees/01.%20DFS%20Traversal%20%28Pre%2C%20In%2C%20Post%29/1315.%20Sum%20of%20Nodes%20with%20Even-Valued%20Grandparent/1315.%20Sum%20of%20Nodes%20with%20Even-Valued%20Grandparent.md) |
| 14 | [1485. Clone Binary Tree With Random Pointer](https://leetcode.com/problems/clone-binary-tree-with-random-pointer/) 🔒 | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](14.%20Trees/01.%20DFS%20Traversal%20%28Pre%2C%20In%2C%20Post%29/1485.%20Clone%20Binary%20Tree%20With%20Random%20Pointer/1485.%20Clone%20Binary%20Tree%20With%20Random%20Pointer.md) |
| 15 | [2236. Root Equals Sum of Children](https://leetcode.com/problems/root-equals-sum-of-children/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](14.%20Trees/01.%20DFS%20Traversal%20%28Pre%2C%20In%2C%20Post%29/2236.%20Root%20Equals%20Sum%20of%20Children/2236.%20Root%20Equals%20Sum%20of%20Children.md) |

### 14.02. BFS & Level Order

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [103. Binary Tree Zigzag Level Order Traversal](https://leetcode.com/problems/binary-tree-zigzag-level-order-traversal/) | Medium | 3 months | 25.9 | ✅ Solved |  |  |  | [notes](14.%20Trees/02.%20BFS%20%26%20Level%20Order/0103.%20Binary%20Tree%20Zigzag%20Level%20Order%20Traversal/0103.%20Binary%20Tree%20Zigzag%20Level%20Order%20Traversal.md) |
| 2 | [102. Binary Tree Level Order Traversal](https://leetcode.com/problems/binary-tree-level-order-traversal/) | Medium | 6 months | 53.3 | ✅ Solved |  |  |  | [notes](14.%20Trees/02.%20BFS%20%26%20Level%20Order/0102.%20Binary%20Tree%20Level%20Order%20Traversal/0102.%20Binary%20Tree%20Level%20Order%20Traversal.md) |
| 3 | [958. Check Completeness of a Binary Tree](https://leetcode.com/problems/check-completeness-of-a-binary-tree/) | Medium | 6+ months | 54.0 | Todo |  |  |  | [notes](14.%20Trees/02.%20BFS%20%26%20Level%20Order/0958.%20Check%20Completeness%20of%20a%20Binary%20Tree/0958.%20Check%20Completeness%20of%20a%20Binary%20Tree.md) |
| 4 | [117. Populating Next Right Pointers in Each Node II](https://leetcode.com/problems/populating-next-right-pointers-in-each-node-ii/) | Medium | 6+ months | 45.5 | Todo |  |  |  | [notes](14.%20Trees/02.%20BFS%20%26%20Level%20Order/0117.%20Populating%20Next%20Right%20Pointers%20in%20Each%20Node%20II/0117.%20Populating%20Next%20Right%20Pointers%20in%20Each%20Node%20II.md) |
| 5 | [116. Populating Next Right Pointers in Each Node](https://leetcode.com/problems/populating-next-right-pointers-in-each-node/) | Medium | 6+ months | 39.5 | Todo |  |  |  | [notes](14.%20Trees/02.%20BFS%20%26%20Level%20Order/0116.%20Populating%20Next%20Right%20Pointers%20in%20Each%20Node/0116.%20Populating%20Next%20Right%20Pointers%20in%20Each%20Node.md) |
| 6 | [637. Average of Levels in Binary Tree](https://leetcode.com/problems/average-of-levels-in-binary-tree/) | Easy | 6+ months | 37.8 | ✅ Solved |  |  |  | [notes](14.%20Trees/02.%20BFS%20%26%20Level%20Order/0637.%20Average%20of%20Levels%20in%20Binary%20Tree/0637.%20Average%20of%20Levels%20in%20Binary%20Tree.md) |
| 7 | [662. Maximum Width of Binary Tree](https://leetcode.com/problems/maximum-width-of-binary-tree/) | Medium | 6+ months | 18.5 | ✅ Solved |  |  |  | [notes](14.%20Trees/02.%20BFS%20%26%20Level%20Order/0662.%20Maximum%20Width%20of%20Binary%20Tree/0662.%20Maximum%20Width%20of%20Binary%20Tree.md) |
| 8 | [1161. Maximum Level Sum of a Binary Tree](https://leetcode.com/problems/maximum-level-sum-of-a-binary-tree/) | Medium | 6+ months | 17.3 | Todo |  |  |  | [notes](14.%20Trees/02.%20BFS%20%26%20Level%20Order/1161.%20Maximum%20Level%20Sum%20of%20a%20Binary%20Tree/1161.%20Maximum%20Level%20Sum%20of%20a%20Binary%20Tree.md) |
| 9 | [111. Minimum Depth of Binary Tree](https://leetcode.com/problems/minimum-depth-of-binary-tree/) | Easy | 6+ months | 12.0 | Todo |  |  |  | [notes](14.%20Trees/02.%20BFS%20%26%20Level%20Order/0111.%20Minimum%20Depth%20of%20Binary%20Tree/0111.%20Minimum%20Depth%20of%20Binary%20Tree.md) |
| 10 | [1609. Even Odd Tree](https://leetcode.com/problems/even-odd-tree/) | Medium | 6+ months | 6.7 | Todo |  |  |  | [notes](14.%20Trees/02.%20BFS%20%26%20Level%20Order/1609.%20Even%20Odd%20Tree/1609.%20Even%20Odd%20Tree.md) |
| 11 | [107. Binary Tree Level Order Traversal II](https://leetcode.com/problems/binary-tree-level-order-traversal-ii/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](14.%20Trees/02.%20BFS%20%26%20Level%20Order/0107.%20Binary%20Tree%20Level%20Order%20Traversal%20II/0107.%20Binary%20Tree%20Level%20Order%20Traversal%20II.md) |
| 12 | [513. Find Bottom Left Tree Value](https://leetcode.com/problems/find-bottom-left-tree-value/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](14.%20Trees/02.%20BFS%20%26%20Level%20Order/0513.%20Find%20Bottom%20Left%20Tree%20Value/0513.%20Find%20Bottom%20Left%20Tree%20Value.md) |
| 13 | [515. Find Largest Value in Each Tree Row](https://leetcode.com/problems/find-largest-value-in-each-tree-row/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](14.%20Trees/02.%20BFS%20%26%20Level%20Order/0515.%20Find%20Largest%20Value%20in%20Each%20Tree%20Row/0515.%20Find%20Largest%20Value%20in%20Each%20Tree%20Row.md) |
| 14 | [919. Complete Binary Tree Inserter](https://leetcode.com/problems/complete-binary-tree-inserter/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](14.%20Trees/02.%20BFS%20%26%20Level%20Order/0919.%20Complete%20Binary%20Tree%20Inserter/0919.%20Complete%20Binary%20Tree%20Inserter.md) |
| 15 | [993. Cousins in Binary Tree](https://leetcode.com/problems/cousins-in-binary-tree/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](14.%20Trees/02.%20BFS%20%26%20Level%20Order/0993.%20Cousins%20in%20Binary%20Tree/0993.%20Cousins%20in%20Binary%20Tree.md) |

### 14.03. Tree Properties (Height, Diameter, Balance)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [543. Diameter of Binary Tree](https://leetcode.com/problems/diameter-of-binary-tree/) | Easy | 3 months | 88.9 | ✅ Solved |  |  |  | [notes](14.%20Trees/03.%20Tree%20Properties%20%28Height%2C%20Diameter%2C%20Balance%29/0543.%20Diameter%20of%20Binary%20Tree/0543.%20Diameter%20of%20Binary%20Tree.md) |
| 2 | [110. Balanced Binary Tree](https://leetcode.com/problems/balanced-binary-tree/) | Easy | 6 months | 33.4 | ✅ Solved |  |  |  | [notes](14.%20Trees/03.%20Tree%20Properties%20%28Height%2C%20Diameter%2C%20Balance%29/0110.%20Balanced%20Binary%20Tree/0110.%20Balanced%20Binary%20Tree.md) |
| 3 | [222. Count Complete Tree Nodes](https://leetcode.com/problems/count-complete-tree-nodes/) | Medium | 6 months | 18.6 | ✅ Solved |  |  |  | [notes](14.%20Trees/03.%20Tree%20Properties%20%28Height%2C%20Diameter%2C%20Balance%29/0222.%20Count%20Complete%20Tree%20Nodes/0222.%20Count%20Complete%20Tree%20Nodes.md) |
| 4 | [2265. Count Nodes Equal to Average of Subtree](https://leetcode.com/problems/count-nodes-equal-to-average-of-subtree/) | Medium | 6+ months | 58.7 | Todo |  |  |  | [notes](14.%20Trees/03.%20Tree%20Properties%20%28Height%2C%20Diameter%2C%20Balance%29/2265.%20Count%20Nodes%20Equal%20to%20Average%20of%20Subtree/2265.%20Count%20Nodes%20Equal%20to%20Average%20of%20Subtree.md) |
| 5 | [1361. Validate Binary Tree Nodes](https://leetcode.com/problems/validate-binary-tree-nodes/) | Medium | 6+ months | 37.7 | Todo |  |  |  | [notes](14.%20Trees/03.%20Tree%20Properties%20%28Height%2C%20Diameter%2C%20Balance%29/1361.%20Validate%20Binary%20Tree%20Nodes/1361.%20Validate%20Binary%20Tree%20Nodes.md) |
| 6 | [104. Maximum Depth of Binary Tree](https://leetcode.com/problems/maximum-depth-of-binary-tree/) | Easy | 6+ months | 30.2 | ✅ Solved |  |  |  | [notes](14.%20Trees/03.%20Tree%20Properties%20%28Height%2C%20Diameter%2C%20Balance%29/0104.%20Maximum%20Depth%20of%20Binary%20Tree/0104.%20Maximum%20Depth%20of%20Binary%20Tree.md) |
| 7 | [1339. Maximum Product of Splitted Binary Tree](https://leetcode.com/problems/maximum-product-of-splitted-binary-tree/) | Medium | 6+ months | 5.9 | Todo |  |  |  | [notes](14.%20Trees/03.%20Tree%20Properties%20%28Height%2C%20Diameter%2C%20Balance%29/1339.%20Maximum%20Product%20of%20Splitted%20Binary%20Tree/1339.%20Maximum%20Product%20of%20Splitted%20Binary%20Tree.md) |
| 8 | [655. Print Binary Tree](https://leetcode.com/problems/print-binary-tree/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](14.%20Trees/03.%20Tree%20Properties%20%28Height%2C%20Diameter%2C%20Balance%29/0655.%20Print%20Binary%20Tree/0655.%20Print%20Binary%20Tree.md) |
| 9 | [1973. Count Nodes Equal to Sum of Descendants](https://leetcode.com/problems/count-nodes-equal-to-sum-of-descendants/) 🔒 | Medium | 6+ months | 36.1 | Todo |  |  |  | [notes](14.%20Trees/03.%20Tree%20Properties%20%28Height%2C%20Diameter%2C%20Balance%29/1973.%20Count%20Nodes%20Equal%20to%20Sum%20of%20Descendants/1973.%20Count%20Nodes%20Equal%20to%20Sum%20of%20Descendants.md) |
| 10 | [563. Binary Tree Tilt](https://leetcode.com/problems/binary-tree-tilt/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](14.%20Trees/03.%20Tree%20Properties%20%28Height%2C%20Diameter%2C%20Balance%29/0563.%20Binary%20Tree%20Tilt/0563.%20Binary%20Tree%20Tilt.md) |

### 14.04. Path Sum Problems

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [129. Sum Root to Leaf Numbers](https://leetcode.com/problems/sum-root-to-leaf-numbers/) | Medium | 6 months | 78.4 | ✅ Solved |  |  |  | [notes](14.%20Trees/04.%20Path%20Sum%20Problems/0129.%20Sum%20Root%20to%20Leaf%20Numbers/0129.%20Sum%20Root%20to%20Leaf%20Numbers.md) |
| 2 | [124. Binary Tree Maximum Path Sum](https://leetcode.com/problems/binary-tree-maximum-path-sum/) | Hard | 6+ months | 46.3 | ✅ Solved |  |  |  | [notes](14.%20Trees/04.%20Path%20Sum%20Problems/0124.%20Binary%20Tree%20Maximum%20Path%20Sum/0124.%20Binary%20Tree%20Maximum%20Path%20Sum.md) |
| 3 | [257. Binary Tree Paths](https://leetcode.com/problems/binary-tree-paths/) | Easy | 6+ months | 42.5 | ✅ Solved |  |  |  | [notes](14.%20Trees/04.%20Path%20Sum%20Problems/0257.%20Binary%20Tree%20Paths/0257.%20Binary%20Tree%20Paths.md) |
| 4 | [113. Path Sum II](https://leetcode.com/problems/path-sum-ii/) | Medium | 6+ months | 21.5 | Todo |  |  |  | [notes](14.%20Trees/04.%20Path%20Sum%20Problems/0113.%20Path%20Sum%20II/0113.%20Path%20Sum%20II.md) |
| 5 | [112. Path Sum](https://leetcode.com/problems/path-sum/) | Easy | 6+ months | 19.8 | Todo |  |  |  | [notes](14.%20Trees/04.%20Path%20Sum%20Problems/0112.%20Path%20Sum/0112.%20Path%20Sum.md) |
| 6 | [437. Path Sum III](https://leetcode.com/problems/path-sum-iii/) | Medium | 6+ months | 15.8 | Todo |  |  |  | [notes](14.%20Trees/04.%20Path%20Sum%20Problems/0437.%20Path%20Sum%20III/0437.%20Path%20Sum%20III.md) |
| 7 | [298. Binary Tree Longest Consecutive Sequence](https://leetcode.com/problems/binary-tree-longest-consecutive-sequence/) 🔒 | Medium | 6+ months | 11.0 | Todo |  |  |  | [notes](14.%20Trees/04.%20Path%20Sum%20Problems/0298.%20Binary%20Tree%20Longest%20Consecutive%20Sequence/0298.%20Binary%20Tree%20Longest%20Consecutive%20Sequence.md) |
| 8 | [549. Binary Tree Longest Consecutive Sequence II](https://leetcode.com/problems/binary-tree-longest-consecutive-sequence-ii/) 🔒 | Medium | 6+ months | 10.9 | Todo |  |  |  | [notes](14.%20Trees/04.%20Path%20Sum%20Problems/0549.%20Binary%20Tree%20Longest%20Consecutive%20Sequence%20II/0549.%20Binary%20Tree%20Longest%20Consecutive%20Sequence%20II.md) |
| 9 | [1022. Sum of Root To Leaf Binary Numbers](https://leetcode.com/problems/sum-of-root-to-leaf-binary-numbers/) | Easy | 6+ months | 7.1 | ✅ Solved |  |  |  | [notes](14.%20Trees/04.%20Path%20Sum%20Problems/1022.%20Sum%20of%20Root%20To%20Leaf%20Binary%20Numbers/1022.%20Sum%20of%20Root%20To%20Leaf%20Binary%20Numbers.md) |
| 10 | [1026. Maximum Difference Between Node and Ancestor](https://leetcode.com/problems/maximum-difference-between-node-and-ancestor/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](14.%20Trees/04.%20Path%20Sum%20Problems/1026.%20Maximum%20Difference%20Between%20Node%20and%20Ancestor/1026.%20Maximum%20Difference%20Between%20Node%20and%20Ancestor.md) |

### 14.05. Lowest Common Ancestor

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [1650. Lowest Common Ancestor of a Binary Tree III](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree-iii/) 🔒 | Medium | 6+ months | 86.7 | Todo |  |  |  | [notes](14.%20Trees/05.%20Lowest%20Common%20Ancestor/1650.%20Lowest%20Common%20Ancestor%20of%20a%20Binary%20Tree%20III/1650.%20Lowest%20Common%20Ancestor%20of%20a%20Binary%20Tree%20III.md) |
| 2 | [236. Lowest Common Ancestor of a Binary Tree](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree/) | Medium | 6+ months | 86.2 | ✅ Solved |  |  |  | [notes](14.%20Trees/05.%20Lowest%20Common%20Ancestor/0236.%20Lowest%20Common%20Ancestor%20of%20a%20Binary%20Tree/0236.%20Lowest%20Common%20Ancestor%20of%20a%20Binary%20Tree.md) |
| 3 | [235. Lowest Common Ancestor of a Binary Search Tree](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-search-tree/) | Medium | 6+ months | 52.5 | ✅ Solved |  |  |  | [notes](14.%20Trees/05.%20Lowest%20Common%20Ancestor/0235.%20Lowest%20Common%20Ancestor%20of%20a%20Binary%20Search%20Tree/0235.%20Lowest%20Common%20Ancestor%20of%20a%20Binary%20Search%20Tree.md) |
| 4 | [865. Smallest Subtree with all the Deepest Nodes](https://leetcode.com/problems/smallest-subtree-with-all-the-deepest-nodes/) | Medium | 6+ months | 43.6 | Todo |  |  |  | [notes](14.%20Trees/05.%20Lowest%20Common%20Ancestor/0865.%20Smallest%20Subtree%20with%20all%20the%20Deepest%20Nodes/0865.%20Smallest%20Subtree%20with%20all%20the%20Deepest%20Nodes.md) |
| 5 | [1123. Lowest Common Ancestor of Deepest Leaves](https://leetcode.com/problems/lowest-common-ancestor-of-deepest-leaves/) | Medium | 6+ months | 41.3 | ✅ Solved |  |  |  | [notes](14.%20Trees/05.%20Lowest%20Common%20Ancestor/1123.%20Lowest%20Common%20Ancestor%20of%20Deepest%20Leaves/1123.%20Lowest%20Common%20Ancestor%20of%20Deepest%20Leaves.md) |
| 6 | [1644. Lowest Common Ancestor of a Binary Tree II](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree-ii/) 🔒 | Medium | 6+ months | 16.8 | Todo |  |  |  | [notes](14.%20Trees/05.%20Lowest%20Common%20Ancestor/1644.%20Lowest%20Common%20Ancestor%20of%20a%20Binary%20Tree%20II/1644.%20Lowest%20Common%20Ancestor%20of%20a%20Binary%20Tree%20II.md) |

### 14.06. Binary Search Tree

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [98. Validate Binary Search Tree](https://leetcode.com/problems/validate-binary-search-tree/) | Medium | 3 months | 50.3 | ✅ Solved |  |  |  | [notes](14.%20Trees/06.%20Binary%20Search%20Tree/0098.%20Validate%20Binary%20Search%20Tree/0098.%20Validate%20Binary%20Search%20Tree.md) |
| 2 | [938. Range Sum of BST](https://leetcode.com/problems/range-sum-of-bst/) | Easy | 6+ months | 74.6 | ✅ Solved |  |  |  | [notes](14.%20Trees/06.%20Binary%20Search%20Tree/0938.%20Range%20Sum%20of%20BST/0938.%20Range%20Sum%20of%20BST.md) |
| 3 | [270. Closest Binary Search Tree Value](https://leetcode.com/problems/closest-binary-search-tree-value/) 🔒 | Easy | 6+ months | 56.1 | Todo |  |  |  | [notes](14.%20Trees/06.%20Binary%20Search%20Tree/0270.%20Closest%20Binary%20Search%20Tree%20Value/0270.%20Closest%20Binary%20Search%20Tree%20Value.md) |
| 4 | [653. Two Sum IV - Input is a BST](https://leetcode.com/problems/two-sum-iv-input-is-a-bst/) | Easy | 6+ months | 41.9 | ✅ Solved |  |  |  | [notes](14.%20Trees/06.%20Binary%20Search%20Tree/0653.%20Two%20Sum%20IV%20-%20Input%20is%20a%20BST/0653.%20Two%20Sum%20IV%20-%20Input%20is%20a%20BST.md) |
| 5 | [230. Kth Smallest Element in a BST](https://leetcode.com/problems/kth-smallest-element-in-a-bst/) | Medium | 6+ months | 25.1 | ✅ Solved |  |  |  | [notes](14.%20Trees/06.%20Binary%20Search%20Tree/0230.%20Kth%20Smallest%20Element%20in%20a%20BST/0230.%20Kth%20Smallest%20Element%20in%20a%20BST.md) |
| 6 | [510. Inorder Successor in BST II](https://leetcode.com/problems/inorder-successor-in-bst-ii/) 🔒 | Medium | 6+ months | 13.2 | Todo |  |  |  | [notes](14.%20Trees/06.%20Binary%20Search%20Tree/0510.%20Inorder%20Successor%20in%20BST%20II/0510.%20Inorder%20Successor%20in%20BST%20II.md) |
| 7 | [700. Search in a Binary Search Tree](https://leetcode.com/problems/search-in-a-binary-search-tree/) | Easy | 6+ months | 12.9 | ✅ Solved |  |  |  | [notes](14.%20Trees/06.%20Binary%20Search%20Tree/0700.%20Search%20in%20a%20Binary%20Search%20Tree/0700.%20Search%20in%20a%20Binary%20Search%20Tree.md) |
| 8 | [783. Minimum Distance Between BST Nodes](https://leetcode.com/problems/minimum-distance-between-bst-nodes/) | Easy | 6+ months | 12.9 | Todo |  |  |  | [notes](14.%20Trees/06.%20Binary%20Search%20Tree/0783.%20Minimum%20Distance%20Between%20BST%20Nodes/0783.%20Minimum%20Distance%20Between%20BST%20Nodes.md) |
| 9 | [450. Delete Node in a BST](https://leetcode.com/problems/delete-node-in-a-bst/) | Medium | 6+ months | 11.6 | ✅ Solved |  |  |  | [notes](14.%20Trees/06.%20Binary%20Search%20Tree/0450.%20Delete%20Node%20in%20a%20BST/0450.%20Delete%20Node%20in%20a%20BST.md) |
| 10 | [99. Recover Binary Search Tree](https://leetcode.com/problems/recover-binary-search-tree/) | Medium | 6+ months | 9.1 | ✅ Solved |  |  |  | [notes](14.%20Trees/06.%20Binary%20Search%20Tree/0099.%20Recover%20Binary%20Search%20Tree/0099.%20Recover%20Binary%20Search%20Tree.md) |
| 11 | [530. Minimum Absolute Difference in BST](https://leetcode.com/problems/minimum-absolute-difference-in-bst/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](14.%20Trees/06.%20Binary%20Search%20Tree/0530.%20Minimum%20Absolute%20Difference%20in%20BST/0530.%20Minimum%20Absolute%20Difference%20in%20BST.md) |
| 12 | [538. Convert BST to Greater Tree](https://leetcode.com/problems/convert-bst-to-greater-tree/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](14.%20Trees/06.%20Binary%20Search%20Tree/0538.%20Convert%20BST%20to%20Greater%20Tree/0538.%20Convert%20BST%20to%20Greater%20Tree.md) |
| 13 | [701. Insert into a Binary Search Tree](https://leetcode.com/problems/insert-into-a-binary-search-tree/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](14.%20Trees/06.%20Binary%20Search%20Tree/0701.%20Insert%20into%20a%20Binary%20Search%20Tree/0701.%20Insert%20into%20a%20Binary%20Search%20Tree.md) |
| 14 | [1305. All Elements in Two Binary Search Trees](https://leetcode.com/problems/all-elements-in-two-binary-search-trees/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](14.%20Trees/06.%20Binary%20Search%20Tree/1305.%20All%20Elements%20in%20Two%20Binary%20Search%20Trees/1305.%20All%20Elements%20in%20Two%20Binary%20Search%20Trees.md) |
| 15 | [285. Inorder Successor in BST](https://leetcode.com/problems/inorder-successor-in-bst/) 🔒 | Medium | 6+ months | 36.1 | Todo |  |  |  | [notes](14.%20Trees/06.%20Binary%20Search%20Tree/0285.%20Inorder%20Successor%20in%20BST/0285.%20Inorder%20Successor%20in%20BST.md) |

### 14.07. Tree Construction

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [108. Convert Sorted Array to Binary Search Tree](https://leetcode.com/problems/convert-sorted-array-to-binary-search-tree/) | Easy | 6 months | 25.6 | ✅ Solved |  |  |  | [notes](14.%20Trees/07.%20Tree%20Construction/0108.%20Convert%20Sorted%20Array%20to%20Binary%20Search%20Tree/0108.%20Convert%20Sorted%20Array%20to%20Binary%20Search%20Tree.md) |
| 2 | [536. Construct Binary Tree from String](https://leetcode.com/problems/construct-binary-tree-from-string/) 🔒 | Medium | 6+ months | 38.2 | Todo |  |  |  | [notes](14.%20Trees/07.%20Tree%20Construction/0536.%20Construct%20Binary%20Tree%20from%20String/0536.%20Construct%20Binary%20Tree%20from%20String.md) |
| 3 | [1382. Balance a Binary Search Tree](https://leetcode.com/problems/balance-a-binary-search-tree/) | Medium | 6+ months | 16.1 | Todo |  |  |  | [notes](14.%20Trees/07.%20Tree%20Construction/1382.%20Balance%20a%20Binary%20Search%20Tree/1382.%20Balance%20a%20Binary%20Search%20Tree.md) |
| 4 | [109. Convert Sorted List to Binary Search Tree](https://leetcode.com/problems/convert-sorted-list-to-binary-search-tree/) | Medium | 6+ months | 14.0 | Todo |  |  |  | [notes](14.%20Trees/07.%20Tree%20Construction/0109.%20Convert%20Sorted%20List%20to%20Binary%20Search%20Tree/0109.%20Convert%20Sorted%20List%20to%20Binary%20Search%20Tree.md) |
| 5 | [105. Construct Binary Tree from Preorder and Inorder Traversal](https://leetcode.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/) | Medium | 6+ months | 12.0 | ✅ Solved |  |  |  | [notes](14.%20Trees/07.%20Tree%20Construction/0105.%20Construct%20Binary%20Tree%20from%20Preorder%20and%20Inorder%20Traversal/0105.%20Construct%20Binary%20Tree%20from%20Preorder%20and%20Inorder%20Traversal.md) |
| 6 | [1008. Construct Binary Search Tree from Preorder Traversal](https://leetcode.com/problems/construct-binary-search-tree-from-preorder-traversal/) | Medium | 6+ months | 11.8 | Todo |  |  |  | [notes](14.%20Trees/07.%20Tree%20Construction/1008.%20Construct%20Binary%20Search%20Tree%20from%20Preorder%20Traversal/1008.%20Construct%20Binary%20Search%20Tree%20from%20Preorder%20Traversal.md) |
| 7 | [2196. Create Binary Tree From Descriptions](https://leetcode.com/problems/create-binary-tree-from-descriptions/) | Medium | 6+ months | 5.3 | Todo |  |  |  | [notes](14.%20Trees/07.%20Tree%20Construction/2196.%20Create%20Binary%20Tree%20From%20Descriptions/2196.%20Create%20Binary%20Tree%20From%20Descriptions.md) |
| 8 | [1028. Recover a Tree From Preorder Traversal](https://leetcode.com/problems/recover-a-tree-from-preorder-traversal/) | Hard | 6+ months | 5.2 | Todo |  |  |  | [notes](14.%20Trees/07.%20Tree%20Construction/1028.%20Recover%20a%20Tree%20From%20Preorder%20Traversal/1028.%20Recover%20a%20Tree%20From%20Preorder%20Traversal.md) |
| 9 | [106. Construct Binary Tree from Inorder and Postorder Traversal](https://leetcode.com/problems/construct-binary-tree-from-inorder-and-postorder-traversal/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](14.%20Trees/07.%20Tree%20Construction/0106.%20Construct%20Binary%20Tree%20from%20Inorder%20and%20Postorder%20Traversal/0106.%20Construct%20Binary%20Tree%20from%20Inorder%20and%20Postorder%20Traversal.md) |
| 10 | [654. Maximum Binary Tree](https://leetcode.com/problems/maximum-binary-tree/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](14.%20Trees/07.%20Tree%20Construction/0654.%20Maximum%20Binary%20Tree/0654.%20Maximum%20Binary%20Tree.md) |

### 14.08. Tree Views & Vertical Order

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [199. Binary Tree Right Side View](https://leetcode.com/problems/binary-tree-right-side-view/) | Medium | 6 months | 86.1 | ✅ Solved |  |  |  | [notes](14.%20Trees/08.%20Tree%20Views%20%26%20Vertical%20Order/0199.%20Binary%20Tree%20Right%20Side%20View/0199.%20Binary%20Tree%20Right%20Side%20View.md) |
| 2 | [987. Vertical Order Traversal of a Binary Tree](https://leetcode.com/problems/vertical-order-traversal-of-a-binary-tree/) | Hard | 6 months | 63.4 | ✅ Solved |  |  |  | [notes](14.%20Trees/08.%20Tree%20Views%20%26%20Vertical%20Order/0987.%20Vertical%20Order%20Traversal%20of%20a%20Binary%20Tree/0987.%20Vertical%20Order%20Traversal%20of%20a%20Binary%20Tree.md) |
| 3 | [314. Binary Tree Vertical Order Traversal](https://leetcode.com/problems/binary-tree-vertical-order-traversal/) 🔒 | Medium | 6+ months | 92.8 | Todo |  |  |  | [notes](14.%20Trees/08.%20Tree%20Views%20%26%20Vertical%20Order/0314.%20Binary%20Tree%20Vertical%20Order%20Traversal/0314.%20Binary%20Tree%20Vertical%20Order%20Traversal.md) |
| 4 | [545. Boundary of Binary Tree](https://leetcode.com/problems/boundary-of-binary-tree/) 🔒 | Medium | 6+ months | 46.2 | Todo |  |  |  | [notes](14.%20Trees/08.%20Tree%20Views%20%26%20Vertical%20Order/0545.%20Boundary%20of%20Binary%20Tree/0545.%20Boundary%20of%20Binary%20Tree.md) |

### 14.09. Serialize & Deserialize

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [297. Serialize and Deserialize Binary Tree](https://leetcode.com/problems/serialize-and-deserialize-binary-tree/) | Hard | 6 months | 49.3 | ✅ Solved |  |  |  | [notes](14.%20Trees/09.%20Serialize%20%26%20Deserialize/0297.%20Serialize%20and%20Deserialize%20Binary%20Tree/0297.%20Serialize%20and%20Deserialize%20Binary%20Tree.md) |
| 2 | [606. Construct String from Binary Tree](https://leetcode.com/problems/construct-string-from-binary-tree/) | Medium | 6+ months | 5.6 | Todo |  |  |  | [notes](14.%20Trees/09.%20Serialize%20%26%20Deserialize/0606.%20Construct%20String%20from%20Binary%20Tree/0606.%20Construct%20String%20from%20Binary%20Tree.md) |
| 3 | [652. Find Duplicate Subtrees](https://leetcode.com/problems/find-duplicate-subtrees/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](14.%20Trees/09.%20Serialize%20%26%20Deserialize/0652.%20Find%20Duplicate%20Subtrees/0652.%20Find%20Duplicate%20Subtrees.md) |

### 14.10. Tree Modification

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [226. Invert Binary Tree](https://leetcode.com/problems/invert-binary-tree/) | Easy | 6 months | 32.0 | ✅ Solved |  |  |  | [notes](14.%20Trees/10.%20Tree%20Modification/0226.%20Invert%20Binary%20Tree/0226.%20Invert%20Binary%20Tree.md) |
| 2 | [426. Convert Binary Search Tree to Sorted Doubly Linked List](https://leetcode.com/problems/convert-binary-search-tree-to-sorted-doubly-linked-list/) 🔒 | Medium | 6+ months | 57.4 | Todo |  |  |  | [notes](14.%20Trees/10.%20Tree%20Modification/0426.%20Convert%20Binary%20Search%20Tree%20to%20Sorted%20Doubly%20Linked%20List/0426.%20Convert%20Binary%20Search%20Tree%20to%20Sorted%20Doubly%20Linked%20List.md) |
| 3 | [114. Flatten Binary Tree to Linked List](https://leetcode.com/problems/flatten-binary-tree-to-linked-list/) | Medium | 6+ months | 27.0 | ✅ Solved |  |  |  | [notes](14.%20Trees/10.%20Tree%20Modification/0114.%20Flatten%20Binary%20Tree%20to%20Linked%20List/0114.%20Flatten%20Binary%20Tree%20to%20Linked%20List.md) |
| 4 | [1110. Delete Nodes And Return Forest](https://leetcode.com/problems/delete-nodes-and-return-forest/) | Medium | 6+ months | 15.0 | Todo |  |  |  | [notes](14.%20Trees/10.%20Tree%20Modification/1110.%20Delete%20Nodes%20And%20Return%20Forest/1110.%20Delete%20Nodes%20And%20Return%20Forest.md) |
| 5 | [617. Merge Two Binary Trees](https://leetcode.com/problems/merge-two-binary-trees/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](14.%20Trees/10.%20Tree%20Modification/0617.%20Merge%20Two%20Binary%20Trees/0617.%20Merge%20Two%20Binary%20Trees.md) |
| 6 | [814. Binary Tree Pruning](https://leetcode.com/problems/binary-tree-pruning/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](14.%20Trees/10.%20Tree%20Modification/0814.%20Binary%20Tree%20Pruning/0814.%20Binary%20Tree%20Pruning.md) |
| 7 | [998. Maximum Binary Tree II](https://leetcode.com/problems/maximum-binary-tree-ii/) | Medium | 6+ months | 36.1 | Todo |  |  |  | [notes](14.%20Trees/10.%20Tree%20Modification/0998.%20Maximum%20Binary%20Tree%20II/0998.%20Maximum%20Binary%20Tree%20II.md) |

### 14.11. N-ary Tree

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [1522. Diameter of N-Ary Tree](https://leetcode.com/problems/diameter-of-n-ary-tree/) 🔒 | Medium | 6+ months | 38.4 | Todo |  |  |  | [notes](14.%20Trees/11.%20N-ary%20Tree/1522.%20Diameter%20of%20N-Ary%20Tree/1522.%20Diameter%20of%20N-Ary%20Tree.md) |
| 2 | [1506. Find Root of N-Ary Tree](https://leetcode.com/problems/find-root-of-n-ary-tree/) 🔒 | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](14.%20Trees/11.%20N-ary%20Tree/1506.%20Find%20Root%20of%20N-Ary%20Tree/1506.%20Find%20Root%20of%20N-Ary%20Tree.md) |

### 14.12. Tree as Graph (Parent Pointers, Distance K)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [863. All Nodes Distance K in Binary Tree](https://leetcode.com/problems/all-nodes-distance-k-in-binary-tree/) | Medium | 6+ months | 61.5 | ✅ Solved |  |  |  | [notes](14.%20Trees/12.%20Tree%20as%20Graph%20%28Parent%20Pointers%2C%20Distance%20K%29/0863.%20All%20Nodes%20Distance%20K%20in%20Binary%20Tree/0863.%20All%20Nodes%20Distance%20K%20in%20Binary%20Tree.md) |
| 2 | [1443. Minimum Time to Collect All Apples in a Tree](https://leetcode.com/problems/minimum-time-to-collect-all-apples-in-a-tree/) | Medium | 6+ months | 44.0 | Todo |  |  |  | [notes](14.%20Trees/12.%20Tree%20as%20Graph%20%28Parent%20Pointers%2C%20Distance%20K%29/1443.%20Minimum%20Time%20to%20Collect%20All%20Apples%20in%20a%20Tree/1443.%20Minimum%20Time%20to%20Collect%20All%20Apples%20in%20a%20Tree.md) |
| 3 | [1245. Tree Diameter](https://leetcode.com/problems/tree-diameter/) 🔒 | Medium | 6+ months | 8.2 | Todo |  |  |  | [notes](14.%20Trees/12.%20Tree%20as%20Graph%20%28Parent%20Pointers%2C%20Distance%20K%29/1245.%20Tree%20Diameter/1245.%20Tree%20Diameter.md) |
| 4 | [2322. Minimum Score After Removals on a Tree](https://leetcode.com/problems/minimum-score-after-removals-on-a-tree/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](14.%20Trees/12.%20Tree%20as%20Graph%20%28Parent%20Pointers%2C%20Distance%20K%29/2322.%20Minimum%20Score%20After%20Removals%20on%20a%20Tree/2322.%20Minimum%20Score%20After%20Removals%20on%20a%20Tree.md) |
| 5 | [2477. Minimum Fuel Cost to Report to the Capital](https://leetcode.com/problems/minimum-fuel-cost-to-report-to-the-capital/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](14.%20Trees/12.%20Tree%20as%20Graph%20%28Parent%20Pointers%2C%20Distance%20K%29/2477.%20Minimum%20Fuel%20Cost%20to%20Report%20to%20the%20Capital/2477.%20Minimum%20Fuel%20Cost%20to%20Report%20to%20the%20Capital.md) |
| 6 | [2467. Most Profitable Path in a Tree](https://leetcode.com/problems/most-profitable-path-in-a-tree/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](14.%20Trees/12.%20Tree%20as%20Graph%20%28Parent%20Pointers%2C%20Distance%20K%29/2467.%20Most%20Profitable%20Path%20in%20a%20Tree/2467.%20Most%20Profitable%20Path%20in%20a%20Tree.md) |

## 15. Tries

12 problems: 0 Easy, 8 Medium, 4 Hard. [Open chapter README](15.%20Tries/README.md) · [Back to top](#chapters)

### 15.01. Basic Trie

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [208. Implement Trie (Prefix Tree)](https://leetcode.com/problems/implement-trie-prefix-tree/) | Medium | 6 months | 42.9 | Todo |  |  |  | [notes](15.%20Tries/01.%20Basic%20Trie/0208.%20Implement%20Trie%20%28Prefix%20Tree%29/0208.%20Implement%20Trie%20%28Prefix%20Tree%29.md) |
| 2 | [1233. Remove Sub-Folders from the Filesystem](https://leetcode.com/problems/remove-sub-folders-from-the-filesystem/) | Medium | 6+ months | 9.1 | Todo |  |  |  | [notes](15.%20Tries/01.%20Basic%20Trie/1233.%20Remove%20Sub-Folders%20from%20the%20Filesystem/1233.%20Remove%20Sub-Folders%20from%20the%20Filesystem.md) |
| 3 | [1166. Design File System](https://leetcode.com/problems/design-file-system/) 🔒 | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](15.%20Tries/01.%20Basic%20Trie/1166.%20Design%20File%20System/1166.%20Design%20File%20System.md) |

### 15.02. Trie + DFS

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [386. Lexicographical Numbers](https://leetcode.com/problems/lexicographical-numbers/) | Medium | 6 months | 9.7 | Todo |  |  |  | [notes](15.%20Tries/02.%20Trie%20%2B%20DFS/0386.%20Lexicographical%20Numbers/0386.%20Lexicographical%20Numbers.md) |
| 2 | [212. Word Search II](https://leetcode.com/problems/word-search-ii/) | Hard | 6+ months | 10.4 | Todo |  |  |  | [notes](15.%20Tries/02.%20Trie%20%2B%20DFS/0212.%20Word%20Search%20II/0212.%20Word%20Search%20II.md) |
| 3 | [211. Design Add and Search Words Data Structure](https://leetcode.com/problems/design-add-and-search-words-data-structure/) | Medium | 6+ months | 37.5 | Todo |  |  |  | [notes](15.%20Tries/02.%20Trie%20%2B%20DFS/0211.%20Design%20Add%20and%20Search%20Words%20Data%20Structure/0211.%20Design%20Add%20and%20Search%20Words%20Data%20Structure.md) |

### 15.03. Prefix Search & Autocomplete

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [642. Design Search Autocomplete System](https://leetcode.com/problems/design-search-autocomplete-system/) 🔒 | Hard | 6+ months | 36.1 | Todo |  |  |  | [notes](15.%20Tries/03.%20Prefix%20Search%20%26%20Autocomplete/0642.%20Design%20Search%20Autocomplete%20System/0642.%20Design%20Search%20Autocomplete%20System.md) |
| 2 | [3043. Find the Length of the Longest Common Prefix](https://leetcode.com/problems/find-the-length-of-the-longest-common-prefix/) | Medium | 6+ months | 13.0 | Todo |  |  |  | [notes](15.%20Tries/03.%20Prefix%20Search%20%26%20Autocomplete/3043.%20Find%20the%20Length%20of%20the%20Longest%20Common%20Prefix/3043.%20Find%20the%20Length%20of%20the%20Longest%20Common%20Prefix.md) |
| 3 | [1032. Stream of Characters](https://leetcode.com/problems/stream-of-characters/) | Hard | 6+ months | 5.1 | Todo |  |  |  | [notes](15.%20Tries/03.%20Prefix%20Search%20%26%20Autocomplete/1032.%20Stream%20of%20Characters/1032.%20Stream%20of%20Characters.md) |
| 4 | [1268. Search Suggestions System](https://leetcode.com/problems/search-suggestions-system/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](15.%20Tries/03.%20Prefix%20Search%20%26%20Autocomplete/1268.%20Search%20Suggestions%20System/1268.%20Search%20Suggestions%20System.md) |
| 5 | [745. Prefix and Suffix Search](https://leetcode.com/problems/prefix-and-suffix-search/) | Hard | 6+ months | 37.3 | Todo |  |  |  | [notes](15.%20Tries/03.%20Prefix%20Search%20%26%20Autocomplete/0745.%20Prefix%20and%20Suffix%20Search/0745.%20Prefix%20and%20Suffix%20Search.md) |

### 15.04. Bitwise Trie (XOR)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [421. Maximum XOR of Two Numbers in an Array](https://leetcode.com/problems/maximum-xor-of-two-numbers-in-an-array/) | Medium | 6+ months | 6.3 | Todo |  |  |  | [notes](15.%20Tries/04.%20Bitwise%20Trie%20%28XOR%29/0421.%20Maximum%20XOR%20of%20Two%20Numbers%20in%20an%20Array/0421.%20Maximum%20XOR%20of%20Two%20Numbers%20in%20an%20Array.md) |

## 16. Heap & Priority Queue

35 problems: 5 Easy, 19 Medium, 11 Hard. [Open chapter README](16.%20Heap%20%26%20Priority%20Queue/README.md) · [Back to top](#chapters)

### 16.01. Top K Elements

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [347. Top K Frequent Elements](https://leetcode.com/problems/top-k-frequent-elements/) | Medium | 3 months | 81.7 | ✅ Solved |  |  |  | [notes](16.%20Heap%20%26%20Priority%20Queue/01.%20Top%20K%20Elements/0347.%20Top%20K%20Frequent%20Elements/0347.%20Top%20K%20Frequent%20Elements.md) |
| 2 | [973. K Closest Points to Origin](https://leetcode.com/problems/k-closest-points-to-origin/) | Medium | 6+ months | 76.0 | ✅ Solved |  |  |  | [notes](16.%20Heap%20%26%20Priority%20Queue/01.%20Top%20K%20Elements/0973.%20K%20Closest%20Points%20to%20Origin/0973.%20K%20Closest%20Points%20to%20Origin.md) |
| 3 | [692. Top K Frequent Words](https://leetcode.com/problems/top-k-frequent-words/) | Medium | 6+ months | 22.8 | Todo |  |  |  | [notes](16.%20Heap%20%26%20Priority%20Queue/01.%20Top%20K%20Elements/0692.%20Top%20K%20Frequent%20Words/0692.%20Top%20K%20Frequent%20Words.md) |
| 4 | [2099. Find Subsequence of Length K With the Largest Sum](https://leetcode.com/problems/find-subsequence-of-length-k-with-the-largest-sum/) | Easy | 6+ months | 11.5 | Todo |  |  |  | [notes](16.%20Heap%20%26%20Priority%20Queue/01.%20Top%20K%20Elements/2099.%20Find%20Subsequence%20of%20Length%20K%20With%20the%20Largest%20Sum/2099.%20Find%20Subsequence%20of%20Length%20K%20With%20the%20Largest%20Sum.md) |
| 5 | [1337. The K Weakest Rows in a Matrix](https://leetcode.com/problems/the-k-weakest-rows-in-a-matrix/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](16.%20Heap%20%26%20Priority%20Queue/01.%20Top%20K%20Elements/1337.%20The%20K%20Weakest%20Rows%20in%20a%20Matrix/1337.%20The%20K%20Weakest%20Rows%20in%20a%20Matrix.md) |

### 16.02. K-Way Merge

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [23. Merge k Sorted Lists](https://leetcode.com/problems/merge-k-sorted-lists/) | Hard | 6 months | 74.5 | Todo |  |  |  | [notes](16.%20Heap%20%26%20Priority%20Queue/02.%20K-Way%20Merge/0023.%20Merge%20k%20Sorted%20Lists/0023.%20Merge%20k%20Sorted%20Lists.md) |
| 2 | [378. Kth Smallest Element in a Sorted Matrix](https://leetcode.com/problems/kth-smallest-element-in-a-sorted-matrix/) | Medium | 6+ months | 49.7 | Todo |  |  |  | [notes](16.%20Heap%20%26%20Priority%20Queue/02.%20K-Way%20Merge/0378.%20Kth%20Smallest%20Element%20in%20a%20Sorted%20Matrix/0378.%20Kth%20Smallest%20Element%20in%20a%20Sorted%20Matrix.md) |
| 3 | [373. Find K Pairs with Smallest Sums](https://leetcode.com/problems/find-k-pairs-with-smallest-sums/) | Medium | 6+ months | 21.4 | Todo |  |  |  | [notes](16.%20Heap%20%26%20Priority%20Queue/02.%20K-Way%20Merge/0373.%20Find%20K%20Pairs%20with%20Smallest%20Sums/0373.%20Find%20K%20Pairs%20with%20Smallest%20Sums.md) |
| 4 | [313. Super Ugly Number](https://leetcode.com/problems/super-ugly-number/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](16.%20Heap%20%26%20Priority%20Queue/02.%20K-Way%20Merge/0313.%20Super%20Ugly%20Number/0313.%20Super%20Ugly%20Number.md) |
| 5 | [632. Smallest Range Covering Elements from K Lists](https://leetcode.com/problems/smallest-range-covering-elements-from-k-lists/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](16.%20Heap%20%26%20Priority%20Queue/02.%20K-Way%20Merge/0632.%20Smallest%20Range%20Covering%20Elements%20from%20K%20Lists/0632.%20Smallest%20Range%20Covering%20Elements%20from%20K%20Lists.md) |
| 6 | [1439. Find the Kth Smallest Sum of a Matrix With Sorted Rows](https://leetcode.com/problems/find-the-kth-smallest-sum-of-a-matrix-with-sorted-rows/) | Hard | 6+ months | 37.0 | Todo |  |  |  | [notes](16.%20Heap%20%26%20Priority%20Queue/02.%20K-Way%20Merge/1439.%20Find%20the%20Kth%20Smallest%20Sum%20of%20a%20Matrix%20With%20Sorted%20Rows/1439.%20Find%20the%20Kth%20Smallest%20Sum%20of%20a%20Matrix%20With%20Sorted%20Rows.md) |

### 16.03. Two Heaps (Median)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [295. Find Median from Data Stream](https://leetcode.com/problems/find-median-from-data-stream/) | Hard | 6 months | 45.2 | Todo |  |  |  | [notes](16.%20Heap%20%26%20Priority%20Queue/03.%20Two%20Heaps%20%28Median%29/0295.%20Find%20Median%20from%20Data%20Stream/0295.%20Find%20Median%20from%20Data%20Stream.md) |
| 2 | [480. Sliding Window Median](https://leetcode.com/problems/sliding-window-median/) | Hard | 6+ months | 54.1 | Todo |  |  |  | [notes](16.%20Heap%20%26%20Priority%20Queue/03.%20Two%20Heaps%20%28Median%29/0480.%20Sliding%20Window%20Median/0480.%20Sliding%20Window%20Median.md) |
| 3 | [2163. Minimum Difference in Sums After Removal of Elements](https://leetcode.com/problems/minimum-difference-in-sums-after-removal-of-elements/) | Hard | 6+ months | 7.2 | Todo |  |  |  | [notes](16.%20Heap%20%26%20Priority%20Queue/03.%20Two%20Heaps%20%28Median%29/2163.%20Minimum%20Difference%20in%20Sums%20After%20Removal%20of%20Elements/2163.%20Minimum%20Difference%20in%20Sums%20After%20Removal%20of%20Elements.md) |

### 16.04. Scheduling with Heap

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [1353. Maximum Number of Events That Can Be Attended](https://leetcode.com/problems/maximum-number-of-events-that-can-be-attended/) | Medium | 6+ months | 12.3 | Todo |  |  |  | [notes](16.%20Heap%20%26%20Priority%20Queue/04.%20Scheduling%20with%20Heap/1353.%20Maximum%20Number%20of%20Events%20That%20Can%20Be%20Attended/1353.%20Maximum%20Number%20of%20Events%20That%20Can%20Be%20Attended.md) |
| 2 | [2402. Meeting Rooms III](https://leetcode.com/problems/meeting-rooms-iii/) | Hard | 6+ months | 6.4 | Todo |  |  |  | [notes](16.%20Heap%20%26%20Priority%20Queue/04.%20Scheduling%20with%20Heap/2402.%20Meeting%20Rooms%20III/2402.%20Meeting%20Rooms%20III.md) |
| 3 | [1834. Single-Threaded CPU](https://leetcode.com/problems/single-threaded-cpu/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](16.%20Heap%20%26%20Priority%20Queue/04.%20Scheduling%20with%20Heap/1834.%20Single-Threaded%20CPU/1834.%20Single-Threaded%20CPU.md) |
| 4 | [1882. Process Tasks Using Servers](https://leetcode.com/problems/process-tasks-using-servers/) | Medium | 6+ months | 7.4 | Todo |  |  |  | [notes](16.%20Heap%20%26%20Priority%20Queue/04.%20Scheduling%20with%20Heap/1882.%20Process%20Tasks%20Using%20Servers/1882.%20Process%20Tasks%20Using%20Servers.md) |

### 16.05. Kth Smallest or Largest

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [215. Kth Largest Element in an Array](https://leetcode.com/problems/kth-largest-element-in-an-array/) | Medium | 3 months | 93.8 | ✅ Solved |  |  |  | [notes](16.%20Heap%20%26%20Priority%20Queue/05.%20Kth%20Smallest%20or%20Largest/0215.%20Kth%20Largest%20Element%20in%20an%20Array/0215.%20Kth%20Largest%20Element%20in%20an%20Array.md) |
| 2 | [703. Kth Largest Element in a Stream](https://leetcode.com/problems/kth-largest-element-in-a-stream/) | Easy | 6+ months | 42.4 | ✅ Solved |  |  |  | [notes](16.%20Heap%20%26%20Priority%20Queue/05.%20Kth%20Smallest%20or%20Largest/0703.%20Kth%20Largest%20Element%20in%20a%20Stream/0703.%20Kth%20Largest%20Element%20in%20a%20Stream.md) |
| 3 | [1985. Find the Kth Largest Integer in the Array](https://leetcode.com/problems/find-the-kth-largest-integer-in-the-array/) | Medium | 6+ months | 6.9 | Todo |  |  |  | [notes](16.%20Heap%20%26%20Priority%20Queue/05.%20Kth%20Smallest%20or%20Largest/1985.%20Find%20the%20Kth%20Largest%20Integer%20in%20the%20Array/1985.%20Find%20the%20Kth%20Largest%20Integer%20in%20the%20Array.md) |

### 16.06. Greedy with Heap

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [767. Reorganize String](https://leetcode.com/problems/reorganize-string/) | Medium | 6+ months | 14.6 | Todo |  |  |  | [notes](16.%20Heap%20%26%20Priority%20Queue/06.%20Greedy%20with%20Heap/0767.%20Reorganize%20String/0767.%20Reorganize%20String.md) |
| 2 | [407. Trapping Rain Water II](https://leetcode.com/problems/trapping-rain-water-ii/) | Hard | 6+ months | 13.2 | Todo |  |  |  | [notes](16.%20Heap%20%26%20Priority%20Queue/06.%20Greedy%20with%20Heap/0407.%20Trapping%20Rain%20Water%20II/0407.%20Trapping%20Rain%20Water%20II.md) |
| 3 | [1792. Maximum Average Pass Ratio](https://leetcode.com/problems/maximum-average-pass-ratio/) | Medium | 6+ months | 12.2 | Todo |  |  |  | [notes](16.%20Heap%20%26%20Priority%20Queue/06.%20Greedy%20with%20Heap/1792.%20Maximum%20Average%20Pass%20Ratio/1792.%20Maximum%20Average%20Pass%20Ratio.md) |
| 4 | [502. IPO](https://leetcode.com/problems/ipo/) | Hard | 6+ months | 5.7 | Todo |  |  |  | [notes](16.%20Heap%20%26%20Priority%20Queue/06.%20Greedy%20with%20Heap/0502.%20IPO/0502.%20IPO.md) |
| 5 | [1046. Last Stone Weight](https://leetcode.com/problems/last-stone-weight/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](16.%20Heap%20%26%20Priority%20Queue/06.%20Greedy%20with%20Heap/1046.%20Last%20Stone%20Weight/1046.%20Last%20Stone%20Weight.md) |
| 6 | [1054. Distant Barcodes](https://leetcode.com/problems/distant-barcodes/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](16.%20Heap%20%26%20Priority%20Queue/06.%20Greedy%20with%20Heap/1054.%20Distant%20Barcodes/1054.%20Distant%20Barcodes.md) |
| 7 | [1642. Furthest Building You Can Reach](https://leetcode.com/problems/furthest-building-you-can-reach/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](16.%20Heap%20%26%20Priority%20Queue/06.%20Greedy%20with%20Heap/1642.%20Furthest%20Building%20You%20Can%20Reach/1642.%20Furthest%20Building%20You%20Can%20Reach.md) |
| 8 | [2233. Maximum Product After K Increments](https://leetcode.com/problems/maximum-product-after-k-increments/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](16.%20Heap%20%26%20Priority%20Queue/06.%20Greedy%20with%20Heap/2233.%20Maximum%20Product%20After%20K%20Increments/2233.%20Maximum%20Product%20After%20K%20Increments.md) |
| 9 | [2503. Maximum Number of Points From Grid Queries](https://leetcode.com/problems/maximum-number-of-points-from-grid-queries/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](16.%20Heap%20%26%20Priority%20Queue/06.%20Greedy%20with%20Heap/2503.%20Maximum%20Number%20of%20Points%20From%20Grid%20Queries/2503.%20Maximum%20Number%20of%20Points%20From%20Grid%20Queries.md) |
| 10 | [2558. Take Gifts From the Richest Pile](https://leetcode.com/problems/take-gifts-from-the-richest-pile/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](16.%20Heap%20%26%20Priority%20Queue/06.%20Greedy%20with%20Heap/2558.%20Take%20Gifts%20From%20the%20Richest%20Pile/2558.%20Take%20Gifts%20From%20the%20Richest%20Pile.md) |
| 11 | [2593. Find Score of an Array After Marking All Elements](https://leetcode.com/problems/find-score-of-an-array-after-marking-all-elements/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](16.%20Heap%20%26%20Priority%20Queue/06.%20Greedy%20with%20Heap/2593.%20Find%20Score%20of%20an%20Array%20After%20Marking%20All%20Elements/2593.%20Find%20Score%20of%20an%20Array%20After%20Marking%20All%20Elements.md) |
| 12 | [3066. Minimum Operations to Exceed Threshold Value II](https://leetcode.com/problems/minimum-operations-to-exceed-threshold-value-ii/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](16.%20Heap%20%26%20Priority%20Queue/06.%20Greedy%20with%20Heap/3066.%20Minimum%20Operations%20to%20Exceed%20Threshold%20Value%20II/3066.%20Minimum%20Operations%20to%20Exceed%20Threshold%20Value%20II.md) |
| 13 | [3362. Zero Array Transformation III](https://leetcode.com/problems/zero-array-transformation-iii/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](16.%20Heap%20%26%20Priority%20Queue/06.%20Greedy%20with%20Heap/3362.%20Zero%20Array%20Transformation%20III/3362.%20Zero%20Array%20Transformation%20III.md) |
| 14 | [630. Course Schedule III](https://leetcode.com/problems/course-schedule-iii/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](16.%20Heap%20%26%20Priority%20Queue/06.%20Greedy%20with%20Heap/0630.%20Course%20Schedule%20III/0630.%20Course%20Schedule%20III.md) |

## 17. Intervals

15 problems: 1 Easy, 10 Medium, 4 Hard. [Open chapter README](17.%20Intervals/README.md) · [Back to top](#chapters)

### 17.01. Merge Intervals

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [56. Merge Intervals](https://leetcode.com/problems/merge-intervals/) | Medium | 6 months | 86.2 | ✅ Solved |  |  |  | [notes](17.%20Intervals/01.%20Merge%20Intervals/0056.%20Merge%20Intervals/0056.%20Merge%20Intervals.md) |
| 2 | [616. Add Bold Tag in String](https://leetcode.com/problems/add-bold-tag-in-string/) 🔒 | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](17.%20Intervals/01.%20Merge%20Intervals/0616.%20Add%20Bold%20Tag%20in%20String/0616.%20Add%20Bold%20Tag%20in%20String.md) |
| 3 | [759. Employee Free Time](https://leetcode.com/problems/employee-free-time/) 🔒 | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](17.%20Intervals/01.%20Merge%20Intervals/0759.%20Employee%20Free%20Time/0759.%20Employee%20Free%20Time.md) |
| 4 | [1288. Remove Covered Intervals](https://leetcode.com/problems/remove-covered-intervals/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](17.%20Intervals/01.%20Merge%20Intervals/1288.%20Remove%20Covered%20Intervals/1288.%20Remove%20Covered%20Intervals.md) |
| 5 | [2655. Find Maximal Uncovered Ranges](https://leetcode.com/problems/find-maximal-uncovered-ranges/) 🔒 | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](17.%20Intervals/01.%20Merge%20Intervals/2655.%20Find%20Maximal%20Uncovered%20Ranges/2655.%20Find%20Maximal%20Uncovered%20Ranges.md) |

### 17.02. Insert & Remove Interval

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203; | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [57. Insert Interval](https://leetcode.com/problems/insert-interval/) | Medium | 6+ months | 41.2 | ✅ Solved |  |  |  | [notes](17.%20Intervals/02.%20Insert%20%26%20Remove%20Interval/0057.%20Insert%20Interval/0057.%20Insert%20Interval.md) |

### 17.03. Overlapping Intervals & Meeting Rooms

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [986. Interval List Intersections](https://leetcode.com/problems/interval-list-intersections/) | Medium | 6 months | 69.8 | Todo |  |  |  | [notes](17.%20Intervals/03.%20Overlapping%20Intervals%20%26%20Meeting%20Rooms/0986.%20Interval%20List%20Intersections/0986.%20Interval%20List%20Intersections.md) |
| 2 | [253. Meeting Rooms II](https://leetcode.com/problems/meeting-rooms-ii/) 🔒 | Medium | 6+ months | 53.2 | Todo |  |  |  | [notes](17.%20Intervals/03.%20Overlapping%20Intervals%20%26%20Meeting%20Rooms/0253.%20Meeting%20Rooms%20II/0253.%20Meeting%20Rooms%20II.md) |
| 3 | [252. Meeting Rooms](https://leetcode.com/problems/meeting-rooms/) 🔒 | Easy | 6+ months | 39.7 | Todo |  |  |  | [notes](17.%20Intervals/03.%20Overlapping%20Intervals%20%26%20Meeting%20Rooms/0252.%20Meeting%20Rooms/0252.%20Meeting%20Rooms.md) |
| 4 | [1229. Meeting Scheduler](https://leetcode.com/problems/meeting-scheduler/) 🔒 | Medium | 6+ months | 12.9 | Todo |  |  |  | [notes](17.%20Intervals/03.%20Overlapping%20Intervals%20%26%20Meeting%20Rooms/1229.%20Meeting%20Scheduler/1229.%20Meeting%20Scheduler.md) |

### 17.04. Sweep Line

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea&ensp;&#8203; | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [218. The Skyline Problem](https://leetcode.com/problems/the-skyline-problem/) | Hard | 6+ months | 39.3 | Todo |  |  |  | [notes](17.%20Intervals/04.%20Sweep%20Line/0218.%20The%20Skyline%20Problem/0218.%20The%20Skyline%20Problem.md) |

### 17.05. Interval Scheduling

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [435. Non-overlapping Intervals](https://leetcode.com/problems/non-overlapping-intervals/) | Medium | 30 days | 35.3 | Todo |  |  |  | [notes](17.%20Intervals/05.%20Interval%20Scheduling/0435.%20Non-overlapping%20Intervals/0435.%20Non-overlapping%20Intervals.md) |
| 2 | [757. Set Intersection Size At Least Two](https://leetcode.com/problems/set-intersection-size-at-least-two/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](17.%20Intervals/05.%20Interval%20Scheduling/0757.%20Set%20Intersection%20Size%20At%20Least%20Two/0757.%20Set%20Intersection%20Size%20At%20Least%20Two.md) |
| 3 | [2054. Two Best Non-Overlapping Events](https://leetcode.com/problems/two-best-non-overlapping-events/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](17.%20Intervals/05.%20Interval%20Scheduling/2054.%20Two%20Best%20Non-Overlapping%20Events/2054.%20Two%20Best%20Non-Overlapping%20Events.md) |
| 4 | [3414. Maximum Score of Non-overlapping Intervals](https://leetcode.com/problems/maximum-score-of-non-overlapping-intervals/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](17.%20Intervals/05.%20Interval%20Scheduling/3414.%20Maximum%20Score%20of%20Non-overlapping%20Intervals/3414.%20Maximum%20Score%20of%20Non-overlapping%20Intervals.md) |

## 18. Greedy

76 problems: 20 Easy, 47 Medium, 9 Hard. [Open chapter README](18.%20Greedy/README.md) · [Back to top](#chapters)

### 18.01. Greedy Choice

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [3723. Maximize Sum of Squares of Digits](https://leetcode.com/problems/maximize-sum-of-squares-of-digits/) | Medium | 3 months | 5.0 | Todo |  |  |  | [notes](18.%20Greedy/01.%20Greedy%20Choice/3723.%20Maximize%20Sum%20of%20Squares%20of%20Digits/3723.%20Maximize%20Sum%20of%20Squares%20of%20Digits.md) |
| 2 | [122. Best Time to Buy and Sell Stock II](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-ii/) | Medium | 6 months | 43.1 | ✅ Solved |  |  |  | [notes](18.%20Greedy/01.%20Greedy%20Choice/0122.%20Best%20Time%20to%20Buy%20and%20Sell%20Stock%20II/0122.%20Best%20Time%20to%20Buy%20and%20Sell%20Stock%20II.md) |
| 3 | [605. Can Place Flowers](https://leetcode.com/problems/can-place-flowers/) | Easy | 6 months | 41.3 | ✅ Solved |  |  |  | [notes](18.%20Greedy/01.%20Greedy%20Choice/0605.%20Can%20Place%20Flowers/0605.%20Can%20Place%20Flowers.md) |
| 4 | [135. Candy](https://leetcode.com/problems/candy/) | Hard | 6 months | 22.6 | Todo |  |  |  | [notes](18.%20Greedy/01.%20Greedy%20Choice/0135.%20Candy/0135.%20Candy.md) |
| 5 | [330. Patching Array](https://leetcode.com/problems/patching-array/) | Hard | 6 months | 6.6 | Todo |  |  |  | [notes](18.%20Greedy/01.%20Greedy%20Choice/0330.%20Patching%20Array/0330.%20Patching%20Array.md) |
| 6 | [670. Maximum Swap](https://leetcode.com/problems/maximum-swap/) | Medium | 6+ months | 69.4 | Todo |  |  |  | [notes](18.%20Greedy/01.%20Greedy%20Choice/0670.%20Maximum%20Swap/0670.%20Maximum%20Swap.md) |
| 7 | [334. Increasing Triplet Subsequence](https://leetcode.com/problems/increasing-triplet-subsequence/) | Medium | 6+ months | 44.8 | Todo |  |  |  | [notes](18.%20Greedy/01.%20Greedy%20Choice/0334.%20Increasing%20Triplet%20Subsequence/0334.%20Increasing%20Triplet%20Subsequence.md) |
| 8 | [769. Max Chunks To Make Sorted](https://leetcode.com/problems/max-chunks-to-make-sorted/) | Medium | 6+ months | 10.7 | Todo |  |  |  | [notes](18.%20Greedy/01.%20Greedy%20Choice/0769.%20Max%20Chunks%20To%20Make%20Sorted/0769.%20Max%20Chunks%20To%20Make%20Sorted.md) |
| 9 | [2078. Two Furthest Houses With Different Colors](https://leetcode.com/problems/two-furthest-houses-with-different-colors/) | Easy | 6+ months | 5.8 | Todo |  |  |  | [notes](18.%20Greedy/01.%20Greedy%20Choice/2078.%20Two%20Furthest%20Houses%20With%20Different%20Colors/2078.%20Two%20Furthest%20Houses%20With%20Different%20Colors.md) |
| 10 | [3689. Maximum Total Subarray Value I](https://leetcode.com/problems/maximum-total-subarray-value-i/) | Medium | 6+ months | 5.6 | Todo |  |  |  | [notes](18.%20Greedy/01.%20Greedy%20Choice/3689.%20Maximum%20Total%20Subarray%20Value%20I/3689.%20Maximum%20Total%20Subarray%20Value%20I.md) |
| 11 | [1323. Maximum 69 Number](https://leetcode.com/problems/maximum-69-number/) | Easy | 6+ months | 5.4 | Todo |  |  |  | [notes](18.%20Greedy/01.%20Greedy%20Choice/1323.%20Maximum%2069%20Number/1323.%20Maximum%2069%20Number.md) |
| 12 | [665. Non-decreasing Array](https://leetcode.com/problems/non-decreasing-array/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](18.%20Greedy/01.%20Greedy%20Choice/0665.%20Non-decreasing%20Array/0665.%20Non-decreasing%20Array.md) |
| 13 | [2600. K Items With the Maximum Sum](https://leetcode.com/problems/k-items-with-the-maximum-sum/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](18.%20Greedy/01.%20Greedy%20Choice/2600.%20K%20Items%20With%20the%20Maximum%20Sum/2600.%20K%20Items%20With%20the%20Maximum%20Sum.md) |
| 14 | [3191. Minimum Operations to Make Binary Array Elements Equal to One I](https://leetcode.com/problems/minimum-operations-to-make-binary-array-elements-equal-to-one-i/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](18.%20Greedy/01.%20Greedy%20Choice/3191.%20Minimum%20Operations%20to%20Make%20Binary%20Array%20Elements%20Equal%20to%20One%20I/3191.%20Minimum%20Operations%20to%20Make%20Binary%20Array%20Elements%20Equal%20to%20One%20I.md) |
| 15 | [3282. Reach End of Array With Max Score](https://leetcode.com/problems/reach-end-of-array-with-max-score/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](18.%20Greedy/01.%20Greedy%20Choice/3282.%20Reach%20End%20of%20Array%20With%20Max%20Score/3282.%20Reach%20End%20of%20Array%20With%20Max%20Score.md) |
| 16 | [3487. Maximum Unique Subarray Sum After Deletion](https://leetcode.com/problems/maximum-unique-subarray-sum-after-deletion/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](18.%20Greedy/01.%20Greedy%20Choice/3487.%20Maximum%20Unique%20Subarray%20Sum%20After%20Deletion/3487.%20Maximum%20Unique%20Subarray%20Sum%20After%20Deletion.md) |
| 17 | [3576. Transform Array to All Equal Elements](https://leetcode.com/problems/transform-array-to-all-equal-elements/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](18.%20Greedy/01.%20Greedy%20Choice/3576.%20Transform%20Array%20to%20All%20Equal%20Elements/3576.%20Transform%20Array%20to%20All%20Equal%20Elements.md) |
| 18 | [4025. Minimize the Maximum Waiting Time at Synchronized Traffic Lights](https://leetcode.com/problems/minimize-the-maximum-waiting-time-at-synchronized-traffic-lights/) | Medium | 6+ months | 36.1 | Todo |  |  |  | [notes](18.%20Greedy/01.%20Greedy%20Choice/4025.%20Minimize%20the%20Maximum%20Waiting%20Time%20at%20Synchronized%20Traffic%20Lights/4025.%20Minimize%20the%20Maximum%20Waiting%20Time%20at%20Synchronized%20Traffic%20Lights.md) |

### 18.02. Sort + Greedy

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [3727. Maximum Alternating Sum of Squares](https://leetcode.com/problems/maximum-alternating-sum-of-squares/) | Medium | 3 months | 9.1 | Todo |  |  |  | [notes](18.%20Greedy/02.%20Sort%20%2B%20Greedy/3727.%20Maximum%20Alternating%20Sum%20of%20Squares/3727.%20Maximum%20Alternating%20Sum%20of%20Squares.md) |
| 2 | [455. Assign Cookies](https://leetcode.com/problems/assign-cookies/) | Easy | 6+ months | 23.6 | ✅ Solved |  |  |  | [notes](18.%20Greedy/02.%20Sort%20%2B%20Greedy/0455.%20Assign%20Cookies/0455.%20Assign%20Cookies.md) |
| 3 | [1840. Maximum Building Height](https://leetcode.com/problems/maximum-building-height/) | Hard | 6+ months | 13.0 | Todo |  |  |  | [notes](18.%20Greedy/02.%20Sort%20%2B%20Greedy/1840.%20Maximum%20Building%20Height/1840.%20Maximum%20Building%20Height.md) |
| 4 | [406. Queue Reconstruction by Height](https://leetcode.com/problems/queue-reconstruction-by-height/) | Medium | 6+ months | 10.8 | Todo |  |  |  | [notes](18.%20Greedy/02.%20Sort%20%2B%20Greedy/0406.%20Queue%20Reconstruction%20by%20Height/0406.%20Queue%20Reconstruction%20by%20Height.md) |
| 5 | [2410. Maximum Matching of Players With Trainers](https://leetcode.com/problems/maximum-matching-of-players-with-trainers/) | Medium | 6+ months | 9.7 | Todo |  |  |  | [notes](18.%20Greedy/02.%20Sort%20%2B%20Greedy/2410.%20Maximum%20Matching%20of%20Players%20With%20Trainers/2410.%20Maximum%20Matching%20of%20Players%20With%20Trainers.md) |
| 6 | [1710. Maximum Units on a Truck](https://leetcode.com/problems/maximum-units-on-a-truck/) | Easy | 6+ months | 5.4 | Todo |  |  |  | [notes](18.%20Greedy/02.%20Sort%20%2B%20Greedy/1710.%20Maximum%20Units%20on%20a%20Truck/1710.%20Maximum%20Units%20on%20a%20Truck.md) |
| 7 | [826. Most Profit Assigning Work](https://leetcode.com/problems/most-profit-assigning-work/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](18.%20Greedy/02.%20Sort%20%2B%20Greedy/0826.%20Most%20Profit%20Assigning%20Work/0826.%20Most%20Profit%20Assigning%20Work.md) |
| 8 | [910. Smallest Range II](https://leetcode.com/problems/smallest-range-ii/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](18.%20Greedy/02.%20Sort%20%2B%20Greedy/0910.%20Smallest%20Range%20II/0910.%20Smallest%20Range%20II.md) |
| 9 | [1029. Two City Scheduling](https://leetcode.com/problems/two-city-scheduling/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](18.%20Greedy/02.%20Sort%20%2B%20Greedy/1029.%20Two%20City%20Scheduling/1029.%20Two%20City%20Scheduling.md) |
| 10 | [1727. Largest Submatrix With Rearrangements](https://leetcode.com/problems/largest-submatrix-with-rearrangements/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](18.%20Greedy/02.%20Sort%20%2B%20Greedy/1727.%20Largest%20Submatrix%20With%20Rearrangements/1727.%20Largest%20Submatrix%20With%20Rearrangements.md) |
| 11 | [1877. Minimize Maximum Pair Sum in Array](https://leetcode.com/problems/minimize-maximum-pair-sum-in-array/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](18.%20Greedy/02.%20Sort%20%2B%20Greedy/1877.%20Minimize%20Maximum%20Pair%20Sum%20in%20Array/1877.%20Minimize%20Maximum%20Pair%20Sum%20in%20Array.md) |
| 12 | [1921. Eliminate Maximum Number of Monsters](https://leetcode.com/problems/eliminate-maximum-number-of-monsters/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](18.%20Greedy/02.%20Sort%20%2B%20Greedy/1921.%20Eliminate%20Maximum%20Number%20of%20Monsters/1921.%20Eliminate%20Maximum%20Number%20of%20Monsters.md) |
| 13 | [2144. Minimum Cost of Buying Candies With Discount](https://leetcode.com/problems/minimum-cost-of-buying-candies-with-discount/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](18.%20Greedy/02.%20Sort%20%2B%20Greedy/2144.%20Minimum%20Cost%20of%20Buying%20Candies%20With%20Discount/2144.%20Minimum%20Cost%20of%20Buying%20Candies%20With%20Discount.md) |
| 14 | [2412. Minimum Money Required Before Transactions](https://leetcode.com/problems/minimum-money-required-before-transactions/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](18.%20Greedy/02.%20Sort%20%2B%20Greedy/2412.%20Minimum%20Money%20Required%20Before%20Transactions/2412.%20Minimum%20Money%20Required%20Before%20Transactions.md) |
| 15 | [2551. Put Marbles in Bags](https://leetcode.com/problems/put-marbles-in-bags/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](18.%20Greedy/02.%20Sort%20%2B%20Greedy/2551.%20Put%20Marbles%20in%20Bags/2551.%20Put%20Marbles%20in%20Bags.md) |
| 16 | [3397. Maximum Number of Distinct Elements After Operations](https://leetcode.com/problems/maximum-number-of-distinct-elements-after-operations/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](18.%20Greedy/02.%20Sort%20%2B%20Greedy/3397.%20Maximum%20Number%20of%20Distinct%20Elements%20After%20Operations/3397.%20Maximum%20Number%20of%20Distinct%20Elements%20After%20Operations.md) |
| 17 | [3633. Earliest Finish Time for Land and Water Rides I](https://leetcode.com/problems/earliest-finish-time-for-land-and-water-rides-i/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](18.%20Greedy/02.%20Sort%20%2B%20Greedy/3633.%20Earliest%20Finish%20Time%20for%20Land%20and%20Water%20Rides%20I/3633.%20Earliest%20Finish%20Time%20for%20Land%20and%20Water%20Rides%20I.md) |
| 18 | [3732. Maximum Product of Three Elements After One Replacement](https://leetcode.com/problems/maximum-product-of-three-elements-after-one-replacement/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](18.%20Greedy/02.%20Sort%20%2B%20Greedy/3732.%20Maximum%20Product%20of%20Three%20Elements%20After%20One%20Replacement/3732.%20Maximum%20Product%20of%20Three%20Elements%20After%20One%20Replacement.md) |
| 19 | [2037. Minimum Number of Moves to Seat Everyone](https://leetcode.com/problems/minimum-number-of-moves-to-seat-everyone/) | Easy | 6+ months | 5.8 | Todo |  |  |  | [notes](18.%20Greedy/02.%20Sort%20%2B%20Greedy/2037.%20Minimum%20Number%20of%20Moves%20to%20Seat%20Everyone/2037.%20Minimum%20Number%20of%20Moves%20to%20Seat%20Everyone.md) |
| 20 | [2706. Buy Two Chocolates](https://leetcode.com/problems/buy-two-chocolates/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](18.%20Greedy/02.%20Sort%20%2B%20Greedy/2706.%20Buy%20Two%20Chocolates/2706.%20Buy%20Two%20Chocolates.md) |

### 18.03. Jump Game & Reachability

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [55. Jump Game](https://leetcode.com/problems/jump-game/) | Medium | 3 months | 43.0 | Todo |  |  |  | [notes](18.%20Greedy/03.%20Jump%20Game%20%26%20Reachability/0055.%20Jump%20Game/0055.%20Jump%20Game.md) |
| 2 | [45. Jump Game II](https://leetcode.com/problems/jump-game-ii/) | Medium | 6+ months | 31.1 | Todo |  |  |  | [notes](18.%20Greedy/03.%20Jump%20Game%20%26%20Reachability/0045.%20Jump%20Game%20II/0045.%20Jump%20Game%20II.md) |
| 3 | [1326. Minimum Number of Taps to Open to Water a Garden](https://leetcode.com/problems/minimum-number-of-taps-to-open-to-water-a-garden/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](18.%20Greedy/03.%20Jump%20Game%20%26%20Reachability/1326.%20Minimum%20Number%20of%20Taps%20to%20Open%20to%20Water%20a%20Garden/1326.%20Minimum%20Number%20of%20Taps%20to%20Open%20to%20Water%20a%20Garden.md) |

### 18.04. Circular Greedy (Gas Station)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203; | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [134. Gas Station](https://leetcode.com/problems/gas-station/) | Medium | 6+ months | 24.1 | Todo |  |  |  | [notes](18.%20Greedy/04.%20Circular%20Greedy%20%28Gas%20Station%29/0134.%20Gas%20Station/0134.%20Gas%20Station.md) |

### 18.05. String Greedy

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [678. Valid Parenthesis String](https://leetcode.com/problems/valid-parenthesis-string/) | Medium | 3 months | 35.0 | ✅ Solved |  |  |  | [notes](18.%20Greedy/05.%20String%20Greedy/0678.%20Valid%20Parenthesis%20String/0678.%20Valid%20Parenthesis%20String.md) |
| 2 | [2914. Minimum Number of Changes to Make Binary String Beautiful](https://leetcode.com/problems/minimum-number-of-changes-to-make-binary-string-beautiful/) | Medium | 3 months | 10.9 | Todo |  |  |  | [notes](18.%20Greedy/05.%20String%20Greedy/2914.%20Minimum%20Number%20of%20Changes%20to%20Make%20Binary%20String%20Beautiful/2914.%20Minimum%20Number%20of%20Changes%20to%20Make%20Binary%20String%20Beautiful.md) |
| 3 | [3863. Minimum Operations to Sort a String](https://leetcode.com/problems/minimum-operations-to-sort-a-string/) | Medium | 3 months | 10.1 | Todo |  |  |  | [notes](18.%20Greedy/05.%20String%20Greedy/3863.%20Minimum%20Operations%20to%20Sort%20a%20String/3863.%20Minimum%20Operations%20to%20Sort%20a%20String.md) |
| 4 | [3302. Find the Lexicographically Smallest Valid Sequence](https://leetcode.com/problems/find-the-lexicographically-smallest-valid-sequence/) | Medium | 6 months | 12.3 | Todo |  |  |  | [notes](18.%20Greedy/05.%20String%20Greedy/3302.%20Find%20the%20Lexicographically%20Smallest%20Valid%20Sequence/3302.%20Find%20the%20Lexicographically%20Smallest%20Valid%20Sequence.md) |
| 5 | [3348. Smallest Divisible Digit Product II](https://leetcode.com/problems/smallest-divisible-digit-product-ii/) | Hard | 6 months | 7.4 | Todo |  |  |  | [notes](18.%20Greedy/05.%20String%20Greedy/3348.%20Smallest%20Divisible%20Digit%20Product%20II/3348.%20Smallest%20Divisible%20Digit%20Product%20II.md) |
| 6 | [3499. Maximize Active Section with Trade I](https://leetcode.com/problems/maximize-active-section-with-trade-i/) | Medium | 6 months | 7.3 | Todo |  |  |  | [notes](18.%20Greedy/05.%20String%20Greedy/3499.%20Maximize%20Active%20Section%20with%20Trade%20I/3499.%20Maximize%20Active%20Section%20with%20Trade%20I.md) |
| 7 | [1903. Largest Odd Number in String](https://leetcode.com/problems/largest-odd-number-in-string/) | Easy | 6+ months | 17.3 | Todo |  |  |  | [notes](18.%20Greedy/05.%20String%20Greedy/1903.%20Largest%20Odd%20Number%20in%20String/1903.%20Largest%20Odd%20Number%20in%20String.md) |
| 8 | [3228. Maximum Number of Operations to Move Ones to the End](https://leetcode.com/problems/maximum-number-of-operations-to-move-ones-to-the-end/) | Medium | 6+ months | 11.8 | Todo |  |  |  | [notes](18.%20Greedy/05.%20String%20Greedy/3228.%20Maximum%20Number%20of%20Operations%20to%20Move%20Ones%20to%20the%20End/3228.%20Maximum%20Number%20of%20Operations%20to%20Move%20Ones%20to%20the%20End.md) |
| 9 | [763. Partition Labels](https://leetcode.com/problems/partition-labels/) | Medium | 6+ months | 11.7 | Todo |  |  |  | [notes](18.%20Greedy/05.%20String%20Greedy/0763.%20Partition%20Labels/0763.%20Partition%20Labels.md) |
| 10 | [2116. Check if a Parentheses String Can Be Valid](https://leetcode.com/problems/check-if-a-parentheses-string-can-be-valid/) | Medium | 6+ months | 7.5 | Todo |  |  |  | [notes](18.%20Greedy/05.%20String%20Greedy/2116.%20Check%20if%20a%20Parentheses%20String%20Can%20Be%20Valid/2116.%20Check%20if%20a%20Parentheses%20String%20Can%20Be%20Valid.md) |
| 11 | [1221. Split a String in Balanced Strings](https://leetcode.com/problems/split-a-string-in-balanced-strings/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](18.%20Greedy/05.%20String%20Greedy/1221.%20Split%20a%20String%20in%20Balanced%20Strings/1221.%20Split%20a%20String%20in%20Balanced%20Strings.md) |
| 12 | [1717. Maximum Score From Removing Substrings](https://leetcode.com/problems/maximum-score-from-removing-substrings/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](18.%20Greedy/05.%20String%20Greedy/1717.%20Maximum%20Score%20From%20Removing%20Substrings/1717.%20Maximum%20Score%20From%20Removing%20Substrings.md) |
| 13 | [1758. Minimum Changes To Make Alternating Binary String](https://leetcode.com/problems/minimum-changes-to-make-alternating-binary-string/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](18.%20Greedy/05.%20String%20Greedy/1758.%20Minimum%20Changes%20To%20Make%20Alternating%20Binary%20String/1758.%20Minimum%20Changes%20To%20Make%20Alternating%20Binary%20String.md) |
| 14 | [1850. Minimum Adjacent Swaps to Reach the Kth Smallest Number](https://leetcode.com/problems/minimum-adjacent-swaps-to-reach-the-kth-smallest-number/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](18.%20Greedy/05.%20String%20Greedy/1850.%20Minimum%20Adjacent%20Swaps%20to%20Reach%20the%20Kth%20Smallest%20Number/1850.%20Minimum%20Adjacent%20Swaps%20to%20Reach%20the%20Kth%20Smallest%20Number.md) |
| 15 | [1963. Minimum Number of Swaps to Make the String Balanced](https://leetcode.com/problems/minimum-number-of-swaps-to-make-the-string-balanced/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](18.%20Greedy/05.%20String%20Greedy/1963.%20Minimum%20Number%20of%20Swaps%20to%20Make%20the%20String%20Balanced/1963.%20Minimum%20Number%20of%20Swaps%20to%20Make%20the%20String%20Balanced.md) |
| 16 | [2259. Remove Digit From Number to Maximize Result](https://leetcode.com/problems/remove-digit-from-number-to-maximize-result/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](18.%20Greedy/05.%20String%20Greedy/2259.%20Remove%20Digit%20From%20Number%20to%20Maximize%20Result/2259.%20Remove%20Digit%20From%20Number%20to%20Maximize%20Result.md) |
| 17 | [2864. Maximum Odd Binary Number](https://leetcode.com/problems/maximum-odd-binary-number/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](18.%20Greedy/05.%20String%20Greedy/2864.%20Maximum%20Odd%20Binary%20Number/2864.%20Maximum%20Odd%20Binary%20Number.md) |
| 18 | [3170. Lexicographically Minimum String After Removing Stars](https://leetcode.com/problems/lexicographically-minimum-string-after-removing-stars/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](18.%20Greedy/05.%20String%20Greedy/3170.%20Lexicographically%20Minimum%20String%20After%20Removing%20Stars/3170.%20Lexicographically%20Minimum%20String%20After%20Removing%20Stars.md) |
| 19 | [420. Strong Password Checker](https://leetcode.com/problems/strong-password-checker/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](18.%20Greedy/05.%20String%20Greedy/0420.%20Strong%20Password%20Checker/0420.%20Strong%20Password%20Checker.md) |
| 20 | [1980. Find Unique Binary String](https://leetcode.com/problems/find-unique-binary-string/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](18.%20Greedy/05.%20String%20Greedy/1980.%20Find%20Unique%20Binary%20String/1980.%20Find%20Unique%20Binary%20String.md) |

### 18.06. Greedy with Counting

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [621. Task Scheduler](https://leetcode.com/problems/task-scheduler/) | Medium | 6 months | 42.2 | ✅ Solved |  |  |  | [notes](18.%20Greedy/06.%20Greedy%20with%20Counting/0621.%20Task%20Scheduler/0621.%20Task%20Scheduler.md) |
| 2 | [1217. Minimum Cost to Move Chips to The Same Position](https://leetcode.com/problems/minimum-cost-to-move-chips-to-the-same-position/) | Easy | 6 months | 10.4 | Todo |  |  |  | [notes](18.%20Greedy/06.%20Greedy%20with%20Counting/1217.%20Minimum%20Cost%20to%20Move%20Chips%20to%20The%20Same%20Position/1217.%20Minimum%20Cost%20to%20Move%20Chips%20to%20The%20Same%20Position.md) |
| 3 | [3545. Minimum Deletions for At Most K Distinct Characters](https://leetcode.com/problems/minimum-deletions-for-at-most-k-distinct-characters/) | Easy | 6+ months | 20.3 | ✅ Solved |  |  |  | [notes](18.%20Greedy/06.%20Greedy%20with%20Counting/3545.%20Minimum%20Deletions%20for%20At%20Most%20K%20Distinct%20Characters/3545.%20Minimum%20Deletions%20for%20At%20Most%20K%20Distinct%20Characters.md) |
| 4 | [860. Lemonade Change](https://leetcode.com/problems/lemonade-change/) | Easy | 6+ months | 14.5 | Todo |  |  |  | [notes](18.%20Greedy/06.%20Greedy%20with%20Counting/0860.%20Lemonade%20Change/0860.%20Lemonade%20Change.md) |
| 5 | [781. Rabbits in Forest](https://leetcode.com/problems/rabbits-in-forest/) | Medium | 6+ months | 12.3 | Todo |  |  |  | [notes](18.%20Greedy/06.%20Greedy%20with%20Counting/0781.%20Rabbits%20in%20Forest/0781.%20Rabbits%20in%20Forest.md) |
| 6 | [846. Hand of Straights](https://leetcode.com/problems/hand-of-straights/) | Medium | 6+ months | 12.3 | Todo |  |  |  | [notes](18.%20Greedy/06.%20Greedy%20with%20Counting/0846.%20Hand%20of%20Straights/0846.%20Hand%20of%20Straights.md) |
| 7 | [2833. Furthest Point From Origin](https://leetcode.com/problems/furthest-point-from-origin/) | Easy | 6+ months | 9.9 | ✅ Solved |  |  |  | [notes](18.%20Greedy/06.%20Greedy%20with%20Counting/2833.%20Furthest%20Point%20From%20Origin/2833.%20Furthest%20Point%20From%20Origin.md) |
| 8 | [2333. Minimum Sum of Squared Difference](https://leetcode.com/problems/minimum-sum-of-squared-difference/) | Medium | 6+ months | 6.4 | Todo |  |  |  | [notes](18.%20Greedy/06.%20Greedy%20with%20Counting/2333.%20Minimum%20Sum%20of%20Squared%20Difference/2333.%20Minimum%20Sum%20of%20Squared%20Difference.md) |
| 9 | [1975. Maximum Matrix Sum](https://leetcode.com/problems/maximum-matrix-sum/) | Medium | 6+ months | 5.9 | Todo |  |  |  | [notes](18.%20Greedy/06.%20Greedy%20with%20Counting/1975.%20Maximum%20Matrix%20Sum/1975.%20Maximum%20Matrix%20Sum.md) |
| 10 | [1400. Construct K Palindrome Strings](https://leetcode.com/problems/construct-k-palindrome-strings/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](18.%20Greedy/06.%20Greedy%20with%20Counting/1400.%20Construct%20K%20Palindrome%20Strings/1400.%20Construct%20K%20Palindrome%20Strings.md) |
| 11 | [2131. Longest Palindrome by Concatenating Two Letter Words](https://leetcode.com/problems/longest-palindrome-by-concatenating-two-letter-words/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](18.%20Greedy/06.%20Greedy%20with%20Counting/2131.%20Longest%20Palindrome%20by%20Concatenating%20Two%20Letter%20Words/2131.%20Longest%20Palindrome%20by%20Concatenating%20Two%20Letter%20Words.md) |
| 12 | [2561. Rearranging Fruits](https://leetcode.com/problems/rearranging-fruits/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](18.%20Greedy/06.%20Greedy%20with%20Counting/2561.%20Rearranging%20Fruits/2561.%20Rearranging%20Fruits.md) |
| 13 | [2870. Minimum Number of Operations to Make Array Empty](https://leetcode.com/problems/minimum-number-of-operations-to-make-array-empty/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](18.%20Greedy/06.%20Greedy%20with%20Counting/2870.%20Minimum%20Number%20of%20Operations%20to%20Make%20Array%20Empty/2870.%20Minimum%20Number%20of%20Operations%20to%20Make%20Array%20Empty.md) |
| 14 | [3443. Maximum Manhattan Distance After K Changes](https://leetcode.com/problems/maximum-manhattan-distance-after-k-changes/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](18.%20Greedy/06.%20Greedy%20with%20Counting/3443.%20Maximum%20Manhattan%20Distance%20After%20K%20Changes/3443.%20Maximum%20Manhattan%20Distance%20After%20K%20Changes.md) |

## 19. Graphs

62 problems: 4 Easy, 45 Medium, 13 Hard. [Open chapter README](19.%20Graphs/README.md) · [Back to top](#chapters)

### 19.01. Graph DFS & Connected Components

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [547. Number of Provinces](https://leetcode.com/problems/number-of-provinces/) | Medium | 6 months | 31.6 | ✅ Solved |  |  |  | [notes](19.%20Graphs/01.%20Graph%20DFS%20%26%20Connected%20Components/0547.%20Number%20of%20Provinces/0547.%20Number%20of%20Provinces.md) |
| 2 | [1971. Find if Path Exists in Graph](https://leetcode.com/problems/find-if-path-exists-in-graph/) | Easy | 6+ months | 18.1 | ✅ Solved |  |  |  | [notes](19.%20Graphs/01.%20Graph%20DFS%20%26%20Connected%20Components/1971.%20Find%20if%20Path%20Exists%20in%20Graph/1971.%20Find%20if%20Path%20Exists%20in%20Graph.md) |
| 3 | [1466. Reorder Routes to Make All Paths Lead to the City Zero](https://leetcode.com/problems/reorder-routes-to-make-all-paths-lead-to-the-city-zero/) | Medium | 6+ months | 14.5 | Todo |  |  |  | [notes](19.%20Graphs/01.%20Graph%20DFS%20%26%20Connected%20Components/1466.%20Reorder%20Routes%20to%20Make%20All%20Paths%20Lead%20to%20the%20City%20Zero/1466.%20Reorder%20Routes%20to%20Make%20All%20Paths%20Lead%20to%20the%20City%20Zero.md) |
| 4 | [841. Keys and Rooms](https://leetcode.com/problems/keys-and-rooms/) | Medium | 6+ months | 13.7 | ✅ Solved |  |  |  | [notes](19.%20Graphs/01.%20Graph%20DFS%20%26%20Connected%20Components/0841.%20Keys%20and%20Rooms/0841.%20Keys%20and%20Rooms.md) |
| 5 | [399. Evaluate Division](https://leetcode.com/problems/evaluate-division/) | Medium | 6+ months | 12.3 | Todo |  |  |  | [notes](19.%20Graphs/01.%20Graph%20DFS%20%26%20Connected%20Components/0399.%20Evaluate%20Division/0399.%20Evaluate%20Division.md) |
| 6 | [1743. Restore the Array From Adjacent Pairs](https://leetcode.com/problems/restore-the-array-from-adjacent-pairs/) | Medium | 6+ months | 8.0 | Todo |  |  |  | [notes](19.%20Graphs/01.%20Graph%20DFS%20%26%20Connected%20Components/1743.%20Restore%20the%20Array%20From%20Adjacent%20Pairs/1743.%20Restore%20the%20Array%20From%20Adjacent%20Pairs.md) |
| 7 | [323. Number of Connected Components in an Undirected Graph](https://leetcode.com/problems/number-of-connected-components-in-an-undirected-graph/) 🔒 | Medium | 6+ months | 7.9 | Todo |  |  |  | [notes](19.%20Graphs/01.%20Graph%20DFS%20%26%20Connected%20Components/0323.%20Number%20of%20Connected%20Components%20in%20an%20Undirected%20Graph/0323.%20Number%20of%20Connected%20Components%20in%20an%20Undirected%20Graph.md) |
| 8 | [797. All Paths From Source to Target](https://leetcode.com/problems/all-paths-from-source-to-target/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](19.%20Graphs/01.%20Graph%20DFS%20%26%20Connected%20Components/0797.%20All%20Paths%20From%20Source%20to%20Target/0797.%20All%20Paths%20From%20Source%20to%20Target.md) |
| 9 | [997. Find the Town Judge](https://leetcode.com/problems/find-the-town-judge/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](19.%20Graphs/01.%20Graph%20DFS%20%26%20Connected%20Components/0997.%20Find%20the%20Town%20Judge/0997.%20Find%20the%20Town%20Judge.md) |
| 10 | [1791. Find Center of Star Graph](https://leetcode.com/problems/find-center-of-star-graph/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](19.%20Graphs/01.%20Graph%20DFS%20%26%20Connected%20Components/1791.%20Find%20Center%20of%20Star%20Graph/1791.%20Find%20Center%20of%20Star%20Graph.md) |
| 11 | [2685. Count the Number of Complete Components](https://leetcode.com/problems/count-the-number-of-complete-components/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](19.%20Graphs/01.%20Graph%20DFS%20%26%20Connected%20Components/2685.%20Count%20the%20Number%20of%20Complete%20Components/2685.%20Count%20the%20Number%20of%20Complete%20Components.md) |

### 19.02. Grid DFS (Islands)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [200. Number of Islands](https://leetcode.com/problems/number-of-islands/) | Medium | 3 months | 64.0 | ✅ Solved |  |  |  | [notes](19.%20Graphs/02.%20Grid%20DFS%20%28Islands%29/0200.%20Number%20of%20Islands/0200.%20Number%20of%20Islands.md) |
| 2 | [130. Surrounded Regions](https://leetcode.com/problems/surrounded-regions/) | Medium | 6 months | 28.7 | Todo |  |  |  | [notes](19.%20Graphs/02.%20Grid%20DFS%20%28Islands%29/0130.%20Surrounded%20Regions/0130.%20Surrounded%20Regions.md) |
| 3 | [827. Making A Large Island](https://leetcode.com/problems/making-a-large-island/) | Hard | 6+ months | 72.6 | ✅ Solved |  |  |  | [notes](19.%20Graphs/02.%20Grid%20DFS%20%28Islands%29/0827.%20Making%20A%20Large%20Island/0827.%20Making%20A%20Large%20Island.md) |
| 4 | [695. Max Area of Island](https://leetcode.com/problems/max-area-of-island/) | Medium | 6+ months | 41.8 | ✅ Solved |  |  |  | [notes](19.%20Graphs/02.%20Grid%20DFS%20%28Islands%29/0695.%20Max%20Area%20of%20Island/0695.%20Max%20Area%20of%20Island.md) |
| 5 | [529. Minesweeper](https://leetcode.com/problems/minesweeper/) | Medium | 6+ months | 37.1 | Todo |  |  |  | [notes](19.%20Graphs/02.%20Grid%20DFS%20%28Islands%29/0529.%20Minesweeper/0529.%20Minesweeper.md) |
| 6 | [733. Flood Fill](https://leetcode.com/problems/flood-fill/) | Easy | 6+ months | 17.5 | ✅ Solved |  |  |  | [notes](19.%20Graphs/02.%20Grid%20DFS%20%28Islands%29/0733.%20Flood%20Fill/0733.%20Flood%20Fill.md) |
| 7 | [417. Pacific Atlantic Water Flow](https://leetcode.com/problems/pacific-atlantic-water-flow/) | Medium | 6+ months | 9.0 | ✅ Solved |  |  |  | [notes](19.%20Graphs/02.%20Grid%20DFS%20%28Islands%29/0417.%20Pacific%20Atlantic%20Water%20Flow/0417.%20Pacific%20Atlantic%20Water%20Flow.md) |
| 8 | [1254. Number of Closed Islands](https://leetcode.com/problems/number-of-closed-islands/) | Medium | 6+ months | 7.8 | Todo |  |  |  | [notes](19.%20Graphs/02.%20Grid%20DFS%20%28Islands%29/1254.%20Number%20of%20Closed%20Islands/1254.%20Number%20of%20Closed%20Islands.md) |
| 9 | [1020. Number of Enclaves](https://leetcode.com/problems/number-of-enclaves/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](19.%20Graphs/02.%20Grid%20DFS%20%28Islands%29/1020.%20Number%20of%20Enclaves/1020.%20Number%20of%20Enclaves.md) |
| 10 | [2658. Maximum Number of Fish in a Grid](https://leetcode.com/problems/maximum-number-of-fish-in-a-grid/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](19.%20Graphs/02.%20Grid%20DFS%20%28Islands%29/2658.%20Maximum%20Number%20of%20Fish%20in%20a%20Grid/2658.%20Maximum%20Number%20of%20Fish%20in%20a%20Grid.md) |

### 19.03. BFS Shortest Path (Unweighted)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea&ensp;&#8203;&ensp;&#8203; | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [909. Snakes and Ladders](https://leetcode.com/problems/snakes-and-ladders/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](19.%20Graphs/03.%20BFS%20Shortest%20Path%20%28Unweighted%29/0909.%20Snakes%20and%20Ladders/0909.%20Snakes%20and%20Ladders.md) |
| 2 | [1236. Web Crawler](https://leetcode.com/problems/web-crawler/) 🔒 | Medium | 6+ months | 36.1 | Todo |  |  |  | [notes](19.%20Graphs/03.%20BFS%20Shortest%20Path%20%28Unweighted%29/1236.%20Web%20Crawler/1236.%20Web%20Crawler.md) |

### 19.04. Grid BFS

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [1091. Shortest Path in Binary Matrix](https://leetcode.com/problems/shortest-path-in-binary-matrix/) | Medium | 6 months | 77.3 | ✅ Solved |  |  |  | [notes](19.%20Graphs/04.%20Grid%20BFS/1091.%20Shortest%20Path%20in%20Binary%20Matrix/1091.%20Shortest%20Path%20in%20Binary%20Matrix.md) |
| 2 | [1778. Shortest Path in a Hidden Grid](https://leetcode.com/problems/shortest-path-in-a-hidden-grid/) 🔒 | Medium | 6+ months | 43.8 | Todo |  |  |  | [notes](19.%20Graphs/04.%20Grid%20BFS/1778.%20Shortest%20Path%20in%20a%20Hidden%20Grid/1778.%20Shortest%20Path%20in%20a%20Hidden%20Grid.md) |
| 3 | [317. Shortest Distance from All Buildings](https://leetcode.com/problems/shortest-distance-from-all-buildings/) 🔒 | Hard | 6+ months | 34.2 | Todo |  |  |  | [notes](19.%20Graphs/04.%20Grid%20BFS/0317.%20Shortest%20Distance%20from%20All%20Buildings/0317.%20Shortest%20Distance%20from%20All%20Buildings.md) |
| 4 | [490. The Maze](https://leetcode.com/problems/the-maze/) 🔒 | Medium | 6+ months | 25.7 | Todo |  |  |  | [notes](19.%20Graphs/04.%20Grid%20BFS/0490.%20The%20Maze/0490.%20The%20Maze.md) |
| 5 | [1926. Nearest Exit from Entrance in Maze](https://leetcode.com/problems/nearest-exit-from-entrance-in-maze/) | Medium | 6+ months | 15.8 | Todo |  |  |  | [notes](19.%20Graphs/04.%20Grid%20BFS/1926.%20Nearest%20Exit%20from%20Entrance%20in%20Maze/1926.%20Nearest%20Exit%20from%20Entrance%20in%20Maze.md) |
| 6 | [1293. Shortest Path in a Grid with Obstacles Elimination](https://leetcode.com/problems/shortest-path-in-a-grid-with-obstacles-elimination/) | Hard | 6+ months | 12.2 | Todo |  |  |  | [notes](19.%20Graphs/04.%20Grid%20BFS/1293.%20Shortest%20Path%20in%20a%20Grid%20with%20Obstacles%20Elimination/1293.%20Shortest%20Path%20in%20a%20Grid%20with%20Obstacles%20Elimination.md) |

### 19.05. Multi-Source BFS

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [994. Rotting Oranges](https://leetcode.com/problems/rotting-oranges/) | Medium | 6 months | 36.3 | ✅ Solved |  |  |  | [notes](19.%20Graphs/05.%20Multi-Source%20BFS/0994.%20Rotting%20Oranges/0994.%20Rotting%20Oranges.md) |
| 2 | [286. Walls and Gates](https://leetcode.com/problems/walls-and-gates/) 🔒 | Medium | 6+ months | 48.5 | ✅ Solved |  |  |  | [notes](19.%20Graphs/05.%20Multi-Source%20BFS/0286.%20Walls%20and%20Gates/0286.%20Walls%20and%20Gates.md) |
| 3 | [934. Shortest Bridge](https://leetcode.com/problems/shortest-bridge/) | Medium | 6+ months | 37.3 | Todo |  |  |  | [notes](19.%20Graphs/05.%20Multi-Source%20BFS/0934.%20Shortest%20Bridge/0934.%20Shortest%20Bridge.md) |
| 4 | [542. 01 Matrix](https://leetcode.com/problems/01-matrix/) | Medium | 6+ months | 17.4 | ✅ Solved |  |  |  | [notes](19.%20Graphs/05.%20Multi-Source%20BFS/0542.%2001%20Matrix/0542.%2001%20Matrix.md) |
| 5 | [2812. Find the Safest Path in a Grid](https://leetcode.com/problems/find-the-safest-path-in-a-grid/) | Medium | 6+ months | 13.8 | ✅ Solved |  |  |  | [notes](19.%20Graphs/05.%20Multi-Source%20BFS/2812.%20Find%20the%20Safest%20Path%20in%20a%20Grid/2812.%20Find%20the%20Safest%20Path%20in%20a%20Grid.md) |

### 19.06. Topological Sort

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [207. Course Schedule](https://leetcode.com/problems/course-schedule/) | Medium | 3 months | 65.8 | ✅ Solved |  |  |  | [notes](19.%20Graphs/06.%20Topological%20Sort/0207.%20Course%20Schedule/0207.%20Course%20Schedule.md) |
| 2 | [210. Course Schedule II](https://leetcode.com/problems/course-schedule-ii/) | Medium | 6 months | 51.0 | ✅ Solved |  |  |  | [notes](19.%20Graphs/06.%20Topological%20Sort/0210.%20Course%20Schedule%20II/0210.%20Course%20Schedule%20II.md) |
| 3 | [269. Alien Dictionary](https://leetcode.com/problems/alien-dictionary/) 🔒 | Hard | 6+ months | 53.3 | ✅ Solved |  |  |  | [notes](19.%20Graphs/06.%20Topological%20Sort/0269.%20Alien%20Dictionary/0269.%20Alien%20Dictionary.md) |
| 4 | [1857. Largest Color Value in a Directed Graph](https://leetcode.com/problems/largest-color-value-in-a-directed-graph/) | Hard | 6+ months | 7.5 | Todo |  |  |  | [notes](19.%20Graphs/06.%20Topological%20Sort/1857.%20Largest%20Color%20Value%20in%20a%20Directed%20Graph/1857.%20Largest%20Color%20Value%20in%20a%20Directed%20Graph.md) |
| 5 | [2192. All Ancestors of a Node in a Directed Acyclic Graph](https://leetcode.com/problems/all-ancestors-of-a-node-in-a-directed-acyclic-graph/) | Medium | 6+ months | 5.9 | Todo |  |  |  | [notes](19.%20Graphs/06.%20Topological%20Sort/2192.%20All%20Ancestors%20of%20a%20Node%20in%20a%20Directed%20Acyclic%20Graph/2192.%20All%20Ancestors%20of%20a%20Node%20in%20a%20Directed%20Acyclic%20Graph.md) |
| 6 | [310. Minimum Height Trees](https://leetcode.com/problems/minimum-height-trees/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](19.%20Graphs/06.%20Topological%20Sort/0310.%20Minimum%20Height%20Trees/0310.%20Minimum%20Height%20Trees.md) |
| 7 | [851. Loud and Rich](https://leetcode.com/problems/loud-and-rich/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](19.%20Graphs/06.%20Topological%20Sort/0851.%20Loud%20and%20Rich/0851.%20Loud%20and%20Rich.md) |
| 8 | [1136. Parallel Courses](https://leetcode.com/problems/parallel-courses/) 🔒 | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](19.%20Graphs/06.%20Topological%20Sort/1136.%20Parallel%20Courses/1136.%20Parallel%20Courses.md) |
| 9 | [1462. Course Schedule IV](https://leetcode.com/problems/course-schedule-iv/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](19.%20Graphs/06.%20Topological%20Sort/1462.%20Course%20Schedule%20IV/1462.%20Course%20Schedule%20IV.md) |
| 10 | [1557. Minimum Number of Vertices to Reach All Nodes](https://leetcode.com/problems/minimum-number-of-vertices-to-reach-all-nodes/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](19.%20Graphs/06.%20Topological%20Sort/1557.%20Minimum%20Number%20of%20Vertices%20to%20Reach%20All%20Nodes/1557.%20Minimum%20Number%20of%20Vertices%20to%20Reach%20All%20Nodes.md) |
| 11 | [2603. Collect Coins in a Tree](https://leetcode.com/problems/collect-coins-in-a-tree/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](19.%20Graphs/06.%20Topological%20Sort/2603.%20Collect%20Coins%20in%20a%20Tree/2603.%20Collect%20Coins%20in%20a%20Tree.md) |

### 19.07. Cycle Detection

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [802. Find Eventual Safe States](https://leetcode.com/problems/find-eventual-safe-states/) | Medium | 6+ months | 12.3 | ✅ Solved |  |  |  | [notes](19.%20Graphs/07.%20Cycle%20Detection/0802.%20Find%20Eventual%20Safe%20States/0802.%20Find%20Eventual%20Safe%20States.md) |
| 2 | [1559. Detect Cycles in 2D Grid](https://leetcode.com/problems/detect-cycles-in-2d-grid/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](19.%20Graphs/07.%20Cycle%20Detection/1559.%20Detect%20Cycles%20in%202D%20Grid/1559.%20Detect%20Cycles%20in%202D%20Grid.md) |
| 3 | [2608. Shortest Cycle in a Graph](https://leetcode.com/problems/shortest-cycle-in-a-graph/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](19.%20Graphs/07.%20Cycle%20Detection/2608.%20Shortest%20Cycle%20in%20a%20Graph/2608.%20Shortest%20Cycle%20in%20a%20Graph.md) |

### 19.08. Bipartite & Graph Coloring

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [785. Is Graph Bipartite?](https://leetcode.com/problems/is-graph-bipartite/) | Medium | 6+ months | 38.7 | ✅ Solved |  |  |  | [notes](19.%20Graphs/08.%20Bipartite%20%26%20Graph%20Coloring/0785.%20Is%20Graph%20Bipartite%3F/0785.%20Is%20Graph%20Bipartite%3F.md) |
| 2 | [886. Possible Bipartition](https://leetcode.com/problems/possible-bipartition/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](19.%20Graphs/08.%20Bipartite%20%26%20Graph%20Coloring/0886.%20Possible%20Bipartition/0886.%20Possible%20Bipartition.md) |
| 3 | [2493. Divide Nodes Into the Maximum Number of Groups](https://leetcode.com/problems/divide-nodes-into-the-maximum-number-of-groups/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](19.%20Graphs/08.%20Bipartite%20%26%20Graph%20Coloring/2493.%20Divide%20Nodes%20Into%20the%20Maximum%20Number%20of%20Groups/2493.%20Divide%20Nodes%20Into%20the%20Maximum%20Number%20of%20Groups.md) |

### 19.09. Clone & Build Graph

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203; | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [133. Clone Graph](https://leetcode.com/problems/clone-graph/) | Medium | 6+ months | 70.2 | Todo |  |  |  | [notes](19.%20Graphs/09.%20Clone%20%26%20Build%20Graph/0133.%20Clone%20Graph/0133.%20Clone%20Graph.md) |

### 19.10. Implicit Graph BFS (Word Ladder, Lock)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [127. Word Ladder](https://leetcode.com/problems/word-ladder/) | Hard | 6+ months | 58.8 | ✅ Solved |  |  |  | [notes](19.%20Graphs/10.%20Implicit%20Graph%20BFS%20%28Word%20Ladder%2C%20Lock%29/0127.%20Word%20Ladder/0127.%20Word%20Ladder.md) |
| 2 | [126. Word Ladder II](https://leetcode.com/problems/word-ladder-ii/) | Hard | 6+ months | 32.5 | ✅ Solved |  |  |  | [notes](19.%20Graphs/10.%20Implicit%20Graph%20BFS%20%28Word%20Ladder%2C%20Lock%29/0126.%20Word%20Ladder%20II/0126.%20Word%20Ladder%20II.md) |
| 3 | [752. Open the Lock](https://leetcode.com/problems/open-the-lock/) | Medium | 6+ months | 23.4 | ✅ Solved |  |  |  | [notes](19.%20Graphs/10.%20Implicit%20Graph%20BFS%20%28Word%20Ladder%2C%20Lock%29/0752.%20Open%20the%20Lock/0752.%20Open%20the%20Lock.md) |
| 4 | [1197. Minimum Knight Moves](https://leetcode.com/problems/minimum-knight-moves/) 🔒 | Medium | 6+ months | 16.1 | Todo |  |  |  | [notes](19.%20Graphs/10.%20Implicit%20Graph%20BFS%20%28Word%20Ladder%2C%20Lock%29/1197.%20Minimum%20Knight%20Moves/1197.%20Minimum%20Knight%20Moves.md) |
| 5 | [433. Minimum Genetic Mutation](https://leetcode.com/problems/minimum-genetic-mutation/) | Medium | 6+ months | 8.7 | ✅ Solved |  |  |  | [notes](19.%20Graphs/10.%20Implicit%20Graph%20BFS%20%28Word%20Ladder%2C%20Lock%29/0433.%20Minimum%20Genetic%20Mutation/0433.%20Minimum%20Genetic%20Mutation.md) |
| 6 | [1345. Jump Game IV](https://leetcode.com/problems/jump-game-iv/) | Hard | 6+ months | 6.5 | Todo |  |  |  | [notes](19.%20Graphs/10.%20Implicit%20Graph%20BFS%20%28Word%20Ladder%2C%20Lock%29/1345.%20Jump%20Game%20IV/1345.%20Jump%20Game%20IV.md) |
| 7 | [3690. Split and Merge Array Transformation](https://leetcode.com/problems/split-and-merge-array-transformation/) | Medium | 6+ months | 6.2 | Todo |  |  |  | [notes](19.%20Graphs/10.%20Implicit%20Graph%20BFS%20%28Word%20Ladder%2C%20Lock%29/3690.%20Split%20and%20Merge%20Array%20Transformation/3690.%20Split%20and%20Merge%20Array%20Transformation.md) |
| 8 | [3629. Minimum Jumps to Reach End via Prime Teleportation](https://leetcode.com/problems/minimum-jumps-to-reach-end-via-prime-teleportation/) | Medium | 6+ months | 5.2 | Todo |  |  |  | [notes](19.%20Graphs/10.%20Implicit%20Graph%20BFS%20%28Word%20Ladder%2C%20Lock%29/3629.%20Minimum%20Jumps%20to%20Reach%20End%20via%20Prime%20Teleportation/3629.%20Minimum%20Jumps%20to%20Reach%20End%20via%20Prime%20Teleportation.md) |
| 9 | [773. Sliding Puzzle](https://leetcode.com/problems/sliding-puzzle/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](19.%20Graphs/10.%20Implicit%20Graph%20BFS%20%28Word%20Ladder%2C%20Lock%29/0773.%20Sliding%20Puzzle/0773.%20Sliding%20Puzzle.md) |
| 10 | [815. Bus Routes](https://leetcode.com/problems/bus-routes/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](19.%20Graphs/10.%20Implicit%20Graph%20BFS%20%28Word%20Ladder%2C%20Lock%29/0815.%20Bus%20Routes/0815.%20Bus%20Routes.md) |

## 20. Advanced Graphs

31 problems: 0 Easy, 20 Medium, 11 Hard. [Open chapter README](20.%20Advanced%20Graphs/README.md) · [Back to top](#chapters)

### 20.01. Union-Find (Disjoint Set)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [721. Accounts Merge](https://leetcode.com/problems/accounts-merge/) | Medium | 6+ months | 60.6 | ✅ Solved |  |  |  | [notes](20.%20Advanced%20Graphs/01.%20Union-Find%20%28Disjoint%20Set%29/0721.%20Accounts%20Merge/0721.%20Accounts%20Merge.md) |
| 2 | [261. Graph Valid Tree](https://leetcode.com/problems/graph-valid-tree/) 🔒 | Medium | 6+ months | 37.6 | Todo |  |  |  | [notes](20.%20Advanced%20Graphs/01.%20Union-Find%20%28Disjoint%20Set%29/0261.%20Graph%20Valid%20Tree/0261.%20Graph%20Valid%20Tree.md) |
| 3 | [684. Redundant Connection](https://leetcode.com/problems/redundant-connection/) | Medium | 6+ months | 18.3 | ✅ Solved |  |  |  | [notes](20.%20Advanced%20Graphs/01.%20Union-Find%20%28Disjoint%20Set%29/0684.%20Redundant%20Connection/0684.%20Redundant%20Connection.md) |
| 4 | [1319. Number of Operations to Make Network Connected](https://leetcode.com/problems/number-of-operations-to-make-network-connected/) | Medium | 6+ months | 14.2 | ✅ Solved |  |  |  | [notes](20.%20Advanced%20Graphs/01.%20Union-Find%20%28Disjoint%20Set%29/1319.%20Number%20of%20Operations%20to%20Make%20Network%20Connected/1319.%20Number%20of%20Operations%20to%20Make%20Network%20Connected.md) |
| 5 | [1970. Last Day Where You Can Still Cross](https://leetcode.com/problems/last-day-where-you-can-still-cross/) | Hard | 6+ months | 9.5 | Todo |  |  |  | [notes](20.%20Advanced%20Graphs/01.%20Union-Find%20%28Disjoint%20Set%29/1970.%20Last%20Day%20Where%20You%20Can%20Still%20Cross/1970.%20Last%20Day%20Where%20You%20Can%20Still%20Cross.md) |
| 6 | [305. Number of Islands II](https://leetcode.com/problems/number-of-islands-ii/) 🔒 | Hard | 6+ months | 8.8 | ✅ Solved |  |  |  | [notes](20.%20Advanced%20Graphs/01.%20Union-Find%20%28Disjoint%20Set%29/0305.%20Number%20of%20Islands%20II/0305.%20Number%20of%20Islands%20II.md) |
| 7 | [3532. Path Existence Queries in a Graph I](https://leetcode.com/problems/path-existence-queries-in-a-graph-i/) | Medium | 6+ months | 8.5 | Todo |  |  |  | [notes](20.%20Advanced%20Graphs/01.%20Union-Find%20%28Disjoint%20Set%29/3532.%20Path%20Existence%20Queries%20in%20a%20Graph%20I/3532.%20Path%20Existence%20Queries%20in%20a%20Graph%20I.md) |
| 8 | [947. Most Stones Removed with Same Row or Column](https://leetcode.com/problems/most-stones-removed-with-same-row-or-column/) | Medium | 6+ months | 8.2 | ✅ Solved |  |  |  | [notes](20.%20Advanced%20Graphs/01.%20Union-Find%20%28Disjoint%20Set%29/0947.%20Most%20Stones%20Removed%20with%20Same%20Row%20or%20Column/0947.%20Most%20Stones%20Removed%20with%20Same%20Row%20or%20Column.md) |
| 9 | [3607. Power Grid Maintenance](https://leetcode.com/problems/power-grid-maintenance/) | Medium | 6+ months | 7.0 | Todo |  |  |  | [notes](20.%20Advanced%20Graphs/01.%20Union-Find%20%28Disjoint%20Set%29/3607.%20Power%20Grid%20Maintenance/3607.%20Power%20Grid%20Maintenance.md) |
| 10 | [1632. Rank Transform of a Matrix](https://leetcode.com/problems/rank-transform-of-a-matrix/) | Hard | 6+ months | 5.2 | Todo |  |  |  | [notes](20.%20Advanced%20Graphs/01.%20Union-Find%20%28Disjoint%20Set%29/1632.%20Rank%20Transform%20of%20a%20Matrix/1632.%20Rank%20Transform%20of%20a%20Matrix.md) |
| 11 | [990. Satisfiability of Equality Equations](https://leetcode.com/problems/satisfiability-of-equality-equations/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](20.%20Advanced%20Graphs/01.%20Union-Find%20%28Disjoint%20Set%29/0990.%20Satisfiability%20of%20Equality%20Equations/0990.%20Satisfiability%20of%20Equality%20Equations.md) |
| 12 | [1061. Lexicographically Smallest Equivalent String](https://leetcode.com/problems/lexicographically-smallest-equivalent-string/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](20.%20Advanced%20Graphs/01.%20Union-Find%20%28Disjoint%20Set%29/1061.%20Lexicographically%20Smallest%20Equivalent%20String/1061.%20Lexicographically%20Smallest%20Equivalent%20String.md) |
| 13 | [3108. Minimum Cost Walk in Weighted Graph](https://leetcode.com/problems/minimum-cost-walk-in-weighted-graph/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](20.%20Advanced%20Graphs/01.%20Union-Find%20%28Disjoint%20Set%29/3108.%20Minimum%20Cost%20Walk%20in%20Weighted%20Graph/3108.%20Minimum%20Cost%20Walk%20in%20Weighted%20Graph.md) |

### 20.02. Dijkstra's Algorithm

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [778. Swim in Rising Water](https://leetcode.com/problems/swim-in-rising-water/) | Hard | 6+ months | 39.3 | ✅ Solved |  |  |  | [notes](20.%20Advanced%20Graphs/02.%20Dijkstra%27s%20Algorithm/0778.%20Swim%20in%20Rising%20Water/0778.%20Swim%20in%20Rising%20Water.md) |
| 2 | [1928. Minimum Cost to Reach Destination in Time](https://leetcode.com/problems/minimum-cost-to-reach-destination-in-time/) | Hard | 6+ months | 37.8 | Todo |  |  |  | [notes](20.%20Advanced%20Graphs/02.%20Dijkstra%27s%20Algorithm/1928.%20Minimum%20Cost%20to%20Reach%20Destination%20in%20Time/1928.%20Minimum%20Cost%20to%20Reach%20Destination%20in%20Time.md) |
| 3 | [1810. Minimum Path Cost in a Hidden Grid](https://leetcode.com/problems/minimum-path-cost-in-a-hidden-grid/) 🔒 | Medium | 6+ months | 37.2 | Todo |  |  |  | [notes](20.%20Advanced%20Graphs/02.%20Dijkstra%27s%20Algorithm/1810.%20Minimum%20Path%20Cost%20in%20a%20Hidden%20Grid/1810.%20Minimum%20Path%20Cost%20in%20a%20Hidden%20Grid.md) |
| 4 | [3651. Minimum Cost Path with Teleportations](https://leetcode.com/problems/minimum-cost-path-with-teleportations/) | Hard | 6+ months | 11.4 | Todo |  |  |  | [notes](20.%20Advanced%20Graphs/02.%20Dijkstra%27s%20Algorithm/3651.%20Minimum%20Cost%20Path%20with%20Teleportations/3651.%20Minimum%20Cost%20Path%20with%20Teleportations.md) |
| 5 | [505. The Maze II](https://leetcode.com/problems/the-maze-ii/) 🔒 | Medium | 6+ months | 5.9 | Todo |  |  |  | [notes](20.%20Advanced%20Graphs/02.%20Dijkstra%27s%20Algorithm/0505.%20The%20Maze%20II/0505.%20The%20Maze%20II.md) |
| 6 | [743. Network Delay Time](https://leetcode.com/problems/network-delay-time/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](20.%20Advanced%20Graphs/02.%20Dijkstra%27s%20Algorithm/0743.%20Network%20Delay%20Time/0743.%20Network%20Delay%20Time.md) |
| 7 | [1631. Path With Minimum Effort](https://leetcode.com/problems/path-with-minimum-effort/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](20.%20Advanced%20Graphs/02.%20Dijkstra%27s%20Algorithm/1631.%20Path%20With%20Minimum%20Effort/1631.%20Path%20With%20Minimum%20Effort.md) |
| 8 | [3650. Minimum Cost Path with Edge Reversals](https://leetcode.com/problems/minimum-cost-path-with-edge-reversals/) | Medium | 6+ months | 37.0 | Todo |  |  |  | [notes](20.%20Advanced%20Graphs/02.%20Dijkstra%27s%20Algorithm/3650.%20Minimum%20Cost%20Path%20with%20Edge%20Reversals/3650.%20Minimum%20Cost%20Path%20with%20Edge%20Reversals.md) |
| 9 | [1976. Number of Ways to Arrive at Destination](https://leetcode.com/problems/number-of-ways-to-arrive-at-destination/) | Medium | 6+ months | 36.1 | ✅ Solved |  |  |  | [notes](20.%20Advanced%20Graphs/02.%20Dijkstra%27s%20Algorithm/1976.%20Number%20of%20Ways%20to%20Arrive%20at%20Destination/1976.%20Number%20of%20Ways%20to%20Arrive%20at%20Destination.md) |

### 20.03. Bellman-Ford & Floyd-Warshall

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [787. Cheapest Flights Within K Stops](https://leetcode.com/problems/cheapest-flights-within-k-stops/) | Medium | 6 months | 24.2 | ✅ Solved |  |  |  | [notes](20.%20Advanced%20Graphs/03.%20Bellman-Ford%20%26%20Floyd-Warshall/0787.%20Cheapest%20Flights%20Within%20K%20Stops/0787.%20Cheapest%20Flights%20Within%20K%20Stops.md) |
| 2 | [1334. Find the City With the Smallest Number of Neighbors at a Threshold Distance](https://leetcode.com/problems/find-the-city-with-the-smallest-number-of-neighbors-at-a-threshold-distance/) | Medium | 6+ months | 5.1 | Todo |  |  |  | [notes](20.%20Advanced%20Graphs/03.%20Bellman-Ford%20%26%20Floyd-Warshall/1334.%20Find%20the%20City%20With%20the%20Smallest%20Number%20of%20Neighbors%20at%20a%20Threshold%20Distance/1334.%20Find%20the%20City%20With%20the%20Smallest%20Number%20of%20Neighbors%20at%20a%20Threshold%20Distance.md) |

### 20.04. 0-1 BFS

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [1368. Minimum Cost to Make at Least One Valid Path in a Grid](https://leetcode.com/problems/minimum-cost-to-make-at-least-one-valid-path-in-a-grid/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](20.%20Advanced%20Graphs/04.%200-1%20BFS/1368.%20Minimum%20Cost%20to%20Make%20at%20Least%20One%20Valid%20Path%20in%20a%20Grid/1368.%20Minimum%20Cost%20to%20Make%20at%20Least%20One%20Valid%20Path%20in%20a%20Grid.md) |
| 2 | [3552. Grid Teleportation Traversal](https://leetcode.com/problems/grid-teleportation-traversal/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](20.%20Advanced%20Graphs/04.%200-1%20BFS/3552.%20Grid%20Teleportation%20Traversal/3552.%20Grid%20Teleportation%20Traversal.md) |
| 3 | [3286. Find a Safe Walk Through a Grid](https://leetcode.com/problems/find-a-safe-walk-through-a-grid/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](20.%20Advanced%20Graphs/04.%200-1%20BFS/3286.%20Find%20a%20Safe%20Walk%20Through%20a%20Grid/3286.%20Find%20a%20Safe%20Walk%20Through%20a%20Grid.md) |

### 20.05. Minimum Spanning Tree

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [1584. Min Cost to Connect All Points](https://leetcode.com/problems/min-cost-to-connect-all-points/) | Medium | 6+ months | 12.5 | Todo |  |  |  | [notes](20.%20Advanced%20Graphs/05.%20Minimum%20Spanning%20Tree/1584.%20Min%20Cost%20to%20Connect%20All%20Points/1584.%20Min%20Cost%20to%20Connect%20All%20Points.md) |
| 2 | [1489. Find Critical and Pseudo-Critical Edges in Minimum Spanning Tree](https://leetcode.com/problems/find-critical-and-pseudo-critical-edges-in-minimum-spanning-tree/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](20.%20Advanced%20Graphs/05.%20Minimum%20Spanning%20Tree/1489.%20Find%20Critical%20and%20Pseudo-Critical%20Edges%20in%20Minimum%20Spanning%20Tree/1489.%20Find%20Critical%20and%20Pseudo-Critical%20Edges%20in%20Minimum%20Spanning%20Tree.md) |

### 20.06. Strongly Connected Components & Bridges

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [1192. Critical Connections in a Network](https://leetcode.com/problems/critical-connections-in-a-network/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](20.%20Advanced%20Graphs/06.%20Strongly%20Connected%20Components%20%26%20Bridges/1192.%20Critical%20Connections%20in%20a%20Network/1192.%20Critical%20Connections%20in%20a%20Network.md) |

### 20.07. Eulerian Path

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea&ensp;&#8203; | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [332. Reconstruct Itinerary](https://leetcode.com/problems/reconstruct-itinerary/) | Hard | 6+ months | 6.4 | Todo |  |  |  | [notes](20.%20Advanced%20Graphs/07.%20Eulerian%20Path/0332.%20Reconstruct%20Itinerary/0332.%20Reconstruct%20Itinerary.md) |

## 21. Dynamic Programming

135 problems: 6 Easy, 74 Medium, 55 Hard. [Open chapter README](21.%20Dynamic%20Programming/README.md) · [Back to top](#chapters)

### 21.01. 1D DP (Fibonacci Style)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [3505. Minimum Operations to Make Elements Within K Subarrays Equal](https://leetcode.com/problems/minimum-operations-to-make-elements-within-k-subarrays-equal/) | Hard | 30 days | 9.2 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/01.%201D%20DP%20%28Fibonacci%20Style%29/3505.%20Minimum%20Operations%20to%20Make%20Elements%20Within%20K%20Subarrays%20Equal/3505.%20Minimum%20Operations%20to%20Make%20Elements%20Within%20K%20Subarrays%20Equal.md) |
| 2 | [70. Climbing Stairs](https://leetcode.com/problems/climbing-stairs/) | Easy | 3 months | 46.5 | ✅ Solved |  |  |  | [notes](21.%20Dynamic%20Programming/01.%201D%20DP%20%28Fibonacci%20Style%29/0070.%20Climbing%20Stairs/0070.%20Climbing%20Stairs.md) |
| 3 | [3186. Maximum Total Damage With Spell Casting](https://leetcode.com/problems/maximum-total-damage-with-spell-casting/) | Medium | 3 months | 7.1 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/01.%201D%20DP%20%28Fibonacci%20Style%29/3186.%20Maximum%20Total%20Damage%20With%20Spell%20Casting/3186.%20Maximum%20Total%20Damage%20With%20Spell%20Casting.md) |
| 4 | [91. Decode Ways](https://leetcode.com/problems/decode-ways/) | Medium | 6 months | 45.5 | ✅ Solved |  |  |  | [notes](21.%20Dynamic%20Programming/01.%201D%20DP%20%28Fibonacci%20Style%29/0091.%20Decode%20Ways/0091.%20Decode%20Ways.md) |
| 5 | [509. Fibonacci Number](https://leetcode.com/problems/fibonacci-number/) | Easy | 6 months | 39.7 | ✅ Solved |  |  |  | [notes](21.%20Dynamic%20Programming/01.%201D%20DP%20%28Fibonacci%20Style%29/0509.%20Fibonacci%20Number/0509.%20Fibonacci%20Number.md) |
| 6 | [118. Pascal's Triangle](https://leetcode.com/problems/pascals-triangle/) | Easy | 6 months | 39.1 | ✅ Solved |  |  |  | [notes](21.%20Dynamic%20Programming/01.%201D%20DP%20%28Fibonacci%20Style%29/0118.%20Pascal%27s%20Triangle/0118.%20Pascal%27s%20Triangle.md) |
| 7 | [343. Integer Break](https://leetcode.com/problems/integer-break/) | Medium | 6 months | 25.6 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/01.%201D%20DP%20%28Fibonacci%20Style%29/0343.%20Integer%20Break/0343.%20Integer%20Break.md) |
| 8 | [413. Arithmetic Slices](https://leetcode.com/problems/arithmetic-slices/) | Medium | 6 months | 11.8 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/01.%201D%20DP%20%28Fibonacci%20Style%29/0413.%20Arithmetic%20Slices/0413.%20Arithmetic%20Slices.md) |
| 9 | [1235. Maximum Profit in Job Scheduling](https://leetcode.com/problems/maximum-profit-in-job-scheduling/) | Hard | 6 months | 5.5 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/01.%201D%20DP%20%28Fibonacci%20Style%29/1235.%20Maximum%20Profit%20in%20Job%20Scheduling/1235.%20Maximum%20Profit%20in%20Job%20Scheduling.md) |
| 10 | [139. Word Break](https://leetcode.com/problems/word-break/) | Medium | 6+ months | 52.9 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/01.%201D%20DP%20%28Fibonacci%20Style%29/0139.%20Word%20Break/0139.%20Word%20Break.md) |
| 11 | [639. Decode Ways II](https://leetcode.com/problems/decode-ways-ii/) | Hard | 6+ months | 38.1 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/01.%201D%20DP%20%28Fibonacci%20Style%29/0639.%20Decode%20Ways%20II/0639.%20Decode%20Ways%20II.md) |
| 12 | [746. Min Cost Climbing Stairs](https://leetcode.com/problems/min-cost-climbing-stairs/) | Easy | 6+ months | 27.2 | ✅ Solved |  |  |  | [notes](21.%20Dynamic%20Programming/01.%201D%20DP%20%28Fibonacci%20Style%29/0746.%20Min%20Cost%20Climbing%20Stairs/0746.%20Min%20Cost%20Climbing%20Stairs.md) |
| 13 | [983. Minimum Cost For Tickets](https://leetcode.com/problems/minimum-cost-for-tickets/) | Medium | 6+ months | 21.2 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/01.%201D%20DP%20%28Fibonacci%20Style%29/0983.%20Minimum%20Cost%20For%20Tickets/0983.%20Minimum%20Cost%20For%20Tickets.md) |
| 14 | [837. New 21 Game](https://leetcode.com/problems/new-21-game/) | Medium | 6+ months | 10.4 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/01.%201D%20DP%20%28Fibonacci%20Style%29/0837.%20New%2021%20Game/0837.%20New%2021%20Game.md) |
| 15 | [119. Pascal's Triangle II](https://leetcode.com/problems/pascals-triangle-ii/) | Easy | 6+ months | 9.8 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/01.%201D%20DP%20%28Fibonacci%20Style%29/0119.%20Pascal%27s%20Triangle%20II/0119.%20Pascal%27s%20Triangle%20II.md) |
| 16 | [1137. N-th Tribonacci Number](https://leetcode.com/problems/n-th-tribonacci-number/) | Easy | 6+ months | 5.6 | ✅ Solved |  |  |  | [notes](21.%20Dynamic%20Programming/01.%201D%20DP%20%28Fibonacci%20Style%29/1137.%20N-th%20Tribonacci%20Number/1137.%20N-th%20Tribonacci%20Number.md) |
| 17 | [2008. Maximum Earnings From Taxi](https://leetcode.com/problems/maximum-earnings-from-taxi/) | Medium | 6+ months | 5.3 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/01.%201D%20DP%20%28Fibonacci%20Style%29/2008.%20Maximum%20Earnings%20From%20Taxi/2008.%20Maximum%20Earnings%20From%20Taxi.md) |
| 18 | [1406. Stone Game III](https://leetcode.com/problems/stone-game-iii/) | Hard | 6+ months | 5.1 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/01.%201D%20DP%20%28Fibonacci%20Style%29/1406.%20Stone%20Game%20III/1406.%20Stone%20Game%20III.md) |
| 19 | [264. Ugly Number II](https://leetcode.com/problems/ugly-number-ii/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/01.%201D%20DP%20%28Fibonacci%20Style%29/0264.%20Ugly%20Number%20II/0264.%20Ugly%20Number%20II.md) |
| 20 | [276. Paint Fence](https://leetcode.com/problems/paint-fence/) 🔒 | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/01.%201D%20DP%20%28Fibonacci%20Style%29/0276.%20Paint%20Fence/0276.%20Paint%20Fence.md) |
| 21 | [790. Domino and Tromino Tiling](https://leetcode.com/problems/domino-and-tromino-tiling/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/01.%201D%20DP%20%28Fibonacci%20Style%29/0790.%20Domino%20and%20Tromino%20Tiling/0790.%20Domino%20and%20Tromino%20Tiling.md) |
| 22 | [2466. Count Ways To Build Good Strings](https://leetcode.com/problems/count-ways-to-build-good-strings/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/01.%201D%20DP%20%28Fibonacci%20Style%29/2466.%20Count%20Ways%20To%20Build%20Good%20Strings/2466.%20Count%20Ways%20To%20Build%20Good%20Strings.md) |
| 23 | [2770. Maximum Number of Jumps to Reach the Last Index](https://leetcode.com/problems/maximum-number-of-jumps-to-reach-the-last-index/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/01.%201D%20DP%20%28Fibonacci%20Style%29/2770.%20Maximum%20Number%20of%20Jumps%20to%20Reach%20the%20Last%20Index/2770.%20Maximum%20Number%20of%20Jumps%20to%20Reach%20the%20Last%20Index.md) |
| 24 | [3201. Find the Maximum Length of Valid Subsequence I](https://leetcode.com/problems/find-the-maximum-length-of-valid-subsequence-i/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/01.%201D%20DP%20%28Fibonacci%20Style%29/3201.%20Find%20the%20Maximum%20Length%20of%20Valid%20Subsequence%20I/3201.%20Find%20the%20Maximum%20Length%20of%20Valid%20Subsequence%20I.md) |
| 25 | [3202. Find the Maximum Length of Valid Subsequence II](https://leetcode.com/problems/find-the-maximum-length-of-valid-subsequence-ii/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/01.%201D%20DP%20%28Fibonacci%20Style%29/3202.%20Find%20the%20Maximum%20Length%20of%20Valid%20Subsequence%20II/3202.%20Find%20the%20Maximum%20Length%20of%20Valid%20Subsequence%20II.md) |
| 26 | [1043. Partition Array for Maximum Sum](https://leetcode.com/problems/partition-array-for-maximum-sum/) | Medium | 6+ months | 36.6 | ✅ Solved |  |  |  | [notes](21.%20Dynamic%20Programming/01.%201D%20DP%20%28Fibonacci%20Style%29/1043.%20Partition%20Array%20for%20Maximum%20Sum/1043.%20Partition%20Array%20for%20Maximum%20Sum.md) |
| 27 | [265. Paint House II](https://leetcode.com/problems/paint-house-ii/) 🔒 | Hard | 6+ months | 36.1 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/01.%201D%20DP%20%28Fibonacci%20Style%29/0265.%20Paint%20House%20II/0265.%20Paint%20House%20II.md) |
| 28 | [3654. Minimum Sum After Divisible Sum Deletions](https://leetcode.com/problems/minimum-sum-after-divisible-sum-deletions/) | Medium | 6+ months | 6.1 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/01.%201D%20DP%20%28Fibonacci%20Style%29/3654.%20Minimum%20Sum%20After%20Divisible%20Sum%20Deletions/3654.%20Minimum%20Sum%20After%20Divisible%20Sum%20Deletions.md) |

### 21.02. Take or Skip (House Robber)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [198. House Robber](https://leetcode.com/problems/house-robber/) | Medium | 3 months | 42.0 | ✅ Solved |  |  |  | [notes](21.%20Dynamic%20Programming/02.%20Take%20or%20Skip%20%28House%20Robber%29/0198.%20House%20Robber/0198.%20House%20Robber.md) |
| 2 | [213. House Robber II](https://leetcode.com/problems/house-robber-ii/) | Medium | 6 months | 30.4 | ✅ Solved |  |  |  | [notes](21.%20Dynamic%20Programming/02.%20Take%20or%20Skip%20%28House%20Robber%29/0213.%20House%20Robber%20II/0213.%20House%20Robber%20II.md) |
| 3 | [740. Delete and Earn](https://leetcode.com/problems/delete-and-earn/) | Medium | 6+ months | 6.4 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/02.%20Take%20or%20Skip%20%28House%20Robber%29/0740.%20Delete%20and%20Earn/0740.%20Delete%20and%20Earn.md) |
| 4 | [2140. Solving Questions With Brainpower](https://leetcode.com/problems/solving-questions-with-brainpower/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](21.%20Dynamic%20Programming/02.%20Take%20or%20Skip%20%28House%20Robber%29/2140.%20Solving%20Questions%20With%20Brainpower/2140.%20Solving%20Questions%20With%20Brainpower.md) |

### 21.03. 0-1 Knapsack

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [494. Target Sum](https://leetcode.com/problems/target-sum/) | Medium | 6 months | 45.8 | ✅ Solved |  |  |  | [notes](21.%20Dynamic%20Programming/03.%200-1%20Knapsack/0494.%20Target%20Sum/0494.%20Target%20Sum.md) |
| 2 | [416. Partition Equal Subset Sum](https://leetcode.com/problems/partition-equal-subset-sum/) | Medium | 6+ months | 31.3 | ✅ Solved |  |  |  | [notes](21.%20Dynamic%20Programming/03.%200-1%20Knapsack/0416.%20Partition%20Equal%20Subset%20Sum/0416.%20Partition%20Equal%20Subset%20Sum.md) |
| 3 | [474. Ones and Zeroes](https://leetcode.com/problems/ones-and-zeroes/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/03.%200-1%20Knapsack/0474.%20Ones%20and%20Zeroes/0474.%20Ones%20and%20Zeroes.md) |
| 4 | [1049. Last Stone Weight II](https://leetcode.com/problems/last-stone-weight-ii/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/03.%200-1%20Knapsack/1049.%20Last%20Stone%20Weight%20II/1049.%20Last%20Stone%20Weight%20II.md) |
| 5 | [2742. Painting the Walls](https://leetcode.com/problems/painting-the-walls/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/03.%200-1%20Knapsack/2742.%20Painting%20the%20Walls/2742.%20Painting%20the%20Walls.md) |
| 6 | [2915. Length of the Longest Subsequence That Sums to Target](https://leetcode.com/problems/length-of-the-longest-subsequence-that-sums-to-target/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/03.%200-1%20Knapsack/2915.%20Length%20of%20the%20Longest%20Subsequence%20That%20Sums%20to%20Target/2915.%20Length%20of%20the%20Longest%20Subsequence%20That%20Sums%20to%20Target.md) |

### 21.04. Unbounded Knapsack (Coin Change)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [322. Coin Change](https://leetcode.com/problems/coin-change/) | Medium | 3 months | 50.3 | ✅ Solved |  |  |  | [notes](21.%20Dynamic%20Programming/04.%20Unbounded%20Knapsack%20%28Coin%20Change%29/0322.%20Coin%20Change/0322.%20Coin%20Change.md) |
| 2 | [279. Perfect Squares](https://leetcode.com/problems/perfect-squares/) | Medium | 6 months | 15.5 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/04.%20Unbounded%20Knapsack%20%28Coin%20Change%29/0279.%20Perfect%20Squares/0279.%20Perfect%20Squares.md) |
| 3 | [377. Combination Sum IV](https://leetcode.com/problems/combination-sum-iv/) | Medium | 6+ months | 38.8 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/04.%20Unbounded%20Knapsack%20%28Coin%20Change%29/0377.%20Combination%20Sum%20IV/0377.%20Combination%20Sum%20IV.md) |
| 4 | [518. Coin Change II](https://leetcode.com/problems/coin-change-ii/) | Medium | 6+ months | 15.2 | ✅ Solved |  |  |  | [notes](21.%20Dynamic%20Programming/04.%20Unbounded%20Knapsack%20%28Coin%20Change%29/0518.%20Coin%20Change%20II/0518.%20Coin%20Change%20II.md) |
| 5 | [3592. Inverse Coin Change](https://leetcode.com/problems/inverse-coin-change/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/04.%20Unbounded%20Knapsack%20%28Coin%20Change%29/3592.%20Inverse%20Coin%20Change/3592.%20Inverse%20Coin%20Change.md) |

### 21.05. Longest Increasing Subsequence

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [300. Longest Increasing Subsequence](https://leetcode.com/problems/longest-increasing-subsequence/) | Medium | 6 months | 39.3 | ✅ Solved |  |  |  | [notes](21.%20Dynamic%20Programming/05.%20Longest%20Increasing%20Subsequence/0300.%20Longest%20Increasing%20Subsequence/0300.%20Longest%20Increasing%20Subsequence.md) |
| 2 | [1218. Longest Arithmetic Subsequence of Given Difference](https://leetcode.com/problems/longest-arithmetic-subsequence-of-given-difference/) | Medium | 6 months | 12.9 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/05.%20Longest%20Increasing%20Subsequence/1218.%20Longest%20Arithmetic%20Subsequence%20of%20Given%20Difference/1218.%20Longest%20Arithmetic%20Subsequence%20of%20Given%20Difference.md) |
| 3 | [673. Number of Longest Increasing Subsequence](https://leetcode.com/problems/number-of-longest-increasing-subsequence/) | Medium | 6+ months | 37.8 | ✅ Solved |  |  |  | [notes](21.%20Dynamic%20Programming/05.%20Longest%20Increasing%20Subsequence/0673.%20Number%20of%20Longest%20Increasing%20Subsequence/0673.%20Number%20of%20Longest%20Increasing%20Subsequence.md) |
| 4 | [354. Russian Doll Envelopes](https://leetcode.com/problems/russian-doll-envelopes/) | Hard | 6+ months | 25.7 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/05.%20Longest%20Increasing%20Subsequence/0354.%20Russian%20Doll%20Envelopes/0354.%20Russian%20Doll%20Envelopes.md) |
| 5 | [368. Largest Divisible Subset](https://leetcode.com/problems/largest-divisible-subset/) | Medium | 6+ months | 18.7 | ✅ Solved |  |  |  | [notes](21.%20Dynamic%20Programming/05.%20Longest%20Increasing%20Subsequence/0368.%20Largest%20Divisible%20Subset/0368.%20Largest%20Divisible%20Subset.md) |
| 6 | [1691. Maximum Height by Stacking Cuboids ](https://leetcode.com/problems/maximum-height-by-stacking-cuboids/) | Hard | 6+ months | 6.2 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/05.%20Longest%20Increasing%20Subsequence/1691.%20Maximum%20Height%20by%20Stacking%20Cuboids%20/1691.%20Maximum%20Height%20by%20Stacking%20Cuboids%20.md) |
| 7 | [1048. Longest String Chain](https://leetcode.com/problems/longest-string-chain/) | Medium | 6+ months | 5.2 | ✅ Solved |  |  |  | [notes](21.%20Dynamic%20Programming/05.%20Longest%20Increasing%20Subsequence/1048.%20Longest%20String%20Chain/1048.%20Longest%20String%20Chain.md) |

### 21.06. 2D Grid DP

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [62. Unique Paths](https://leetcode.com/problems/unique-paths/) | Medium | 6 months | 48.2 | ✅ Solved |  |  |  | [notes](21.%20Dynamic%20Programming/06.%202D%20Grid%20DP/0062.%20Unique%20Paths/0062.%20Unique%20Paths.md) |
| 2 | [120. Triangle](https://leetcode.com/problems/triangle/) | Medium | 6 months | 24.8 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/06.%202D%20Grid%20DP/0120.%20Triangle/0120.%20Triangle.md) |
| 3 | [63. Unique Paths II](https://leetcode.com/problems/unique-paths-ii/) | Medium | 6 months | 20.7 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/06.%202D%20Grid%20DP/0063.%20Unique%20Paths%20II/0063.%20Unique%20Paths%20II.md) |
| 4 | [221. Maximal Square](https://leetcode.com/problems/maximal-square/) | Medium | 6+ months | 38.8 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/06.%202D%20Grid%20DP/0221.%20Maximal%20Square/0221.%20Maximal%20Square.md) |
| 5 | [764. Largest Plus Sign](https://leetcode.com/problems/largest-plus-sign/) | Medium | 6+ months | 36.1 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/06.%202D%20Grid%20DP/0764.%20Largest%20Plus%20Sign/0764.%20Largest%20Plus%20Sign.md) |
| 6 | [64. Minimum Path Sum](https://leetcode.com/problems/minimum-path-sum/) | Medium | 6+ months | 28.3 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/06.%202D%20Grid%20DP/0064.%20Minimum%20Path%20Sum/0064.%20Minimum%20Path%20Sum.md) |
| 7 | [931. Minimum Falling Path Sum](https://leetcode.com/problems/minimum-falling-path-sum/) | Medium | 6+ months | 12.5 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/06.%202D%20Grid%20DP/0931.%20Minimum%20Falling%20Path%20Sum/0931.%20Minimum%20Falling%20Path%20Sum.md) |
| 8 | [174. Dungeon Game](https://leetcode.com/problems/dungeon-game/) | Hard | 6+ months | 12.0 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/06.%202D%20Grid%20DP/0174.%20Dungeon%20Game/0174.%20Dungeon%20Game.md) |
| 9 | [1277. Count Square Submatrices with All Ones](https://leetcode.com/problems/count-square-submatrices-with-all-ones/) | Medium | 6+ months | 10.3 | ✅ Solved |  |  |  | [notes](21.%20Dynamic%20Programming/06.%202D%20Grid%20DP/1277.%20Count%20Square%20Submatrices%20with%20All%20Ones/1277.%20Count%20Square%20Submatrices%20with%20All%20Ones.md) |
| 10 | [1463. Cherry Pickup II](https://leetcode.com/problems/cherry-pickup-ii/) | Hard | 6+ months | 9.7 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/06.%202D%20Grid%20DP/1463.%20Cherry%20Pickup%20II/1463.%20Cherry%20Pickup%20II.md) |
| 11 | [4003. Minimum Cost Path with Alternating Directions III](https://leetcode.com/problems/minimum-cost-path-with-alternating-directions-iii/) | Hard | 6+ months | 6.3 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/06.%202D%20Grid%20DP/4003.%20Minimum%20Cost%20Path%20with%20Alternating%20Directions%20III/4003.%20Minimum%20Cost%20Path%20with%20Alternating%20Directions%20III.md) |
| 12 | [741. Cherry Pickup](https://leetcode.com/problems/cherry-pickup/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/06.%202D%20Grid%20DP/0741.%20Cherry%20Pickup/0741.%20Cherry%20Pickup.md) |
| 13 | [799. Champagne Tower](https://leetcode.com/problems/champagne-tower/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/06.%202D%20Grid%20DP/0799.%20Champagne%20Tower/0799.%20Champagne%20Tower.md) |
| 14 | [1289. Minimum Falling Path Sum II](https://leetcode.com/problems/minimum-falling-path-sum-ii/) | Hard | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](21.%20Dynamic%20Programming/06.%202D%20Grid%20DP/1289.%20Minimum%20Falling%20Path%20Sum%20II/1289.%20Minimum%20Falling%20Path%20Sum%20II.md) |
| 15 | [1594. Maximum Non Negative Product in a Matrix](https://leetcode.com/problems/maximum-non-negative-product-in-a-matrix/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/06.%202D%20Grid%20DP/1594.%20Maximum%20Non%20Negative%20Product%20in%20a%20Matrix/1594.%20Maximum%20Non%20Negative%20Product%20in%20a%20Matrix.md) |

### 21.07. String DP (LCS, Edit Distance)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [115. Distinct Subsequences](https://leetcode.com/problems/distinct-subsequences/) | Hard | 3 months | 31.4 | ✅ Solved |  |  |  | [notes](21.%20Dynamic%20Programming/07.%20String%20DP%20%28LCS%2C%20Edit%20Distance%29/0115.%20Distinct%20Subsequences/0115.%20Distinct%20Subsequences.md) |
| 2 | [10. Regular Expression Matching](https://leetcode.com/problems/regular-expression-matching/) | Hard | 6 months | 47.8 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/07.%20String%20DP%20%28LCS%2C%20Edit%20Distance%29/0010.%20Regular%20Expression%20Matching/0010.%20Regular%20Expression%20Matching.md) |
| 3 | [44. Wildcard Matching](https://leetcode.com/problems/wildcard-matching/) | Hard | 6 months | 40.6 | ✅ Solved |  |  |  | [notes](21.%20Dynamic%20Programming/07.%20String%20DP%20%28LCS%2C%20Edit%20Distance%29/0044.%20Wildcard%20Matching/0044.%20Wildcard%20Matching.md) |
| 4 | [72. Edit Distance](https://leetcode.com/problems/edit-distance/) | Medium | 6 months | 32.1 | 🟡 Attempted |  |  |  | [notes](21.%20Dynamic%20Programming/07.%20String%20DP%20%28LCS%2C%20Edit%20Distance%29/0072.%20Edit%20Distance/0072.%20Edit%20Distance.md) |
| 5 | [1143. Longest Common Subsequence](https://leetcode.com/problems/longest-common-subsequence/) | Medium | 6 months | 24.3 | ✅ Solved |  |  |  | [notes](21.%20Dynamic%20Programming/07.%20String%20DP%20%28LCS%2C%20Edit%20Distance%29/1143.%20Longest%20Common%20Subsequence/1143.%20Longest%20Common%20Subsequence.md) |
| 6 | [97. Interleaving String](https://leetcode.com/problems/interleaving-string/) | Medium | 6+ months | 12.0 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/07.%20String%20DP%20%28LCS%2C%20Edit%20Distance%29/0097.%20Interleaving%20String/0097.%20Interleaving%20String.md) |
| 7 | [87. Scramble String](https://leetcode.com/problems/scramble-string/) | Hard | 6+ months | 10.1 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/07.%20String%20DP%20%28LCS%2C%20Edit%20Distance%29/0087.%20Scramble%20String/0087.%20Scramble%20String.md) |
| 8 | [2060. Check if an Original String Exists Given Two Encoded Strings](https://leetcode.com/problems/check-if-an-original-string-exists-given-two-encoded-strings/) | Hard | 6+ months | 8.2 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/07.%20String%20DP%20%28LCS%2C%20Edit%20Distance%29/2060.%20Check%20if%20an%20Original%20String%20Exists%20Given%20Two%20Encoded%20Strings/2060.%20Check%20if%20an%20Original%20String%20Exists%20Given%20Two%20Encoded%20Strings.md) |
| 9 | [1092. Shortest Common Supersequence ](https://leetcode.com/problems/shortest-common-supersequence/) | Hard | 6+ months | 6.5 | ✅ Solved |  |  |  | [notes](21.%20Dynamic%20Programming/07.%20String%20DP%20%28LCS%2C%20Edit%20Distance%29/1092.%20Shortest%20Common%20Supersequence%20/1092.%20Shortest%20Common%20Supersequence%20.md) |
| 10 | [712. Minimum ASCII Delete Sum for Two Strings](https://leetcode.com/problems/minimum-ascii-delete-sum-for-two-strings/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/07.%20String%20DP%20%28LCS%2C%20Edit%20Distance%29/0712.%20Minimum%20ASCII%20Delete%20Sum%20for%20Two%20Strings/0712.%20Minimum%20ASCII%20Delete%20Sum%20for%20Two%20Strings.md) |
| 11 | [1458. Max Dot Product of Two Subsequences](https://leetcode.com/problems/max-dot-product-of-two-subsequences/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/07.%20String%20DP%20%28LCS%2C%20Edit%20Distance%29/1458.%20Max%20Dot%20Product%20of%20Two%20Subsequences/1458.%20Max%20Dot%20Product%20of%20Two%20Subsequences.md) |
| 12 | [583. Delete Operation for Two Strings](https://leetcode.com/problems/delete-operation-for-two-strings/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](21.%20Dynamic%20Programming/07.%20String%20DP%20%28LCS%2C%20Edit%20Distance%29/0583.%20Delete%20Operation%20for%20Two%20Strings/0583.%20Delete%20Operation%20for%20Two%20Strings.md) |

### 21.08. Palindrome DP

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [2472. Maximum Number of Non-overlapping Palindrome Substrings](https://leetcode.com/problems/maximum-number-of-non-overlapping-palindrome-substrings/) | Hard | 6 months | 11.9 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/08.%20Palindrome%20DP/2472.%20Maximum%20Number%20of%20Non-overlapping%20Palindrome%20Substrings/2472.%20Maximum%20Number%20of%20Non-overlapping%20Palindrome%20Substrings.md) |
| 2 | [1216. Valid Palindrome III](https://leetcode.com/problems/valid-palindrome-iii/) 🔒 | Hard | 6+ months | 57.5 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/08.%20Palindrome%20DP/1216.%20Valid%20Palindrome%20III/1216.%20Valid%20Palindrome%20III.md) |
| 3 | [516. Longest Palindromic Subsequence](https://leetcode.com/problems/longest-palindromic-subsequence/) | Medium | 6+ months | 20.8 | ✅ Solved |  |  |  | [notes](21.%20Dynamic%20Programming/08.%20Palindrome%20DP/0516.%20Longest%20Palindromic%20Subsequence/0516.%20Longest%20Palindromic%20Subsequence.md) |
| 4 | [132. Palindrome Partitioning II](https://leetcode.com/problems/palindrome-partitioning-ii/) | Hard | 6+ months | 17.5 | ✅ Solved |  |  |  | [notes](21.%20Dynamic%20Programming/08.%20Palindrome%20DP/0132.%20Palindrome%20Partitioning%20II/0132.%20Palindrome%20Partitioning%20II.md) |

### 21.09. Interval DP

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [312. Burst Balloons](https://leetcode.com/problems/burst-balloons/) | Hard | 6 months | 17.8 | ✅ Solved |  |  |  | [notes](21.%20Dynamic%20Programming/09.%20Interval%20DP/0312.%20Burst%20Balloons/0312.%20Burst%20Balloons.md) |
| 2 | [375. Guess Number Higher or Lower II](https://leetcode.com/problems/guess-number-higher-or-lower-ii/) | Medium | 6 months | 9.7 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/09.%20Interval%20DP/0375.%20Guess%20Number%20Higher%20or%20Lower%20II/0375.%20Guess%20Number%20Higher%20or%20Lower%20II.md) |
| 3 | [486. Predict the Winner](https://leetcode.com/problems/predict-the-winner/) | Medium | 6 months | 8.9 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/09.%20Interval%20DP/0486.%20Predict%20the%20Winner/0486.%20Predict%20the%20Winner.md) |
| 4 | [1039. Minimum Score Triangulation of Polygon](https://leetcode.com/problems/minimum-score-triangulation-of-polygon/) | Medium | 6+ months | 10.3 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/09.%20Interval%20DP/1039.%20Minimum%20Score%20Triangulation%20of%20Polygon/1039.%20Minimum%20Score%20Triangulation%20of%20Polygon.md) |
| 5 | [546. Remove Boxes](https://leetcode.com/problems/remove-boxes/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/09.%20Interval%20DP/0546.%20Remove%20Boxes/0546.%20Remove%20Boxes.md) |
| 6 | [664. Strange Printer](https://leetcode.com/problems/strange-printer/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/09.%20Interval%20DP/0664.%20Strange%20Printer/0664.%20Strange%20Printer.md) |
| 7 | [1000. Minimum Cost to Merge Stones](https://leetcode.com/problems/minimum-cost-to-merge-stones/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/09.%20Interval%20DP/1000.%20Minimum%20Cost%20to%20Merge%20Stones/1000.%20Minimum%20Cost%20to%20Merge%20Stones.md) |
| 8 | [1547. Minimum Cost to Cut a Stick](https://leetcode.com/problems/minimum-cost-to-cut-a-stick/) | Hard | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](21.%20Dynamic%20Programming/09.%20Interval%20DP/1547.%20Minimum%20Cost%20to%20Cut%20a%20Stick/1547.%20Minimum%20Cost%20to%20Cut%20a%20Stick.md) |
| 9 | [2019. The Score of Students Solving Math Expression](https://leetcode.com/problems/the-score-of-students-solving-math-expression/) | Hard | 6+ months | 6.8 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/09.%20Interval%20DP/2019.%20The%20Score%20of%20Students%20Solving%20Math%20Expression/2019.%20The%20Score%20of%20Students%20Solving%20Math%20Expression.md) |

### 21.10. DP on Trees

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [968. Binary Tree Cameras](https://leetcode.com/problems/binary-tree-cameras/) | Hard | 6+ months | 39.9 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/10.%20DP%20on%20Trees/0968.%20Binary%20Tree%20Cameras/0968.%20Binary%20Tree%20Cameras.md) |
| 2 | [1373. Maximum Sum BST in Binary Tree](https://leetcode.com/problems/maximum-sum-bst-in-binary-tree/) | Hard | 6+ months | 10.6 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/10.%20DP%20on%20Trees/1373.%20Maximum%20Sum%20BST%20in%20Binary%20Tree/1373.%20Maximum%20Sum%20BST%20in%20Binary%20Tree.md) |
| 3 | [333. Largest BST Subtree](https://leetcode.com/problems/largest-bst-subtree/) 🔒 | Medium | 6+ months | 5.7 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/10.%20DP%20on%20Trees/0333.%20Largest%20BST%20Subtree/0333.%20Largest%20BST%20Subtree.md) |
| 4 | [337. House Robber III](https://leetcode.com/problems/house-robber-iii/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/10.%20DP%20on%20Trees/0337.%20House%20Robber%20III/0337.%20House%20Robber%20III.md) |
| 5 | [834. Sum of Distances in Tree](https://leetcode.com/problems/sum-of-distances-in-tree/) | Hard | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](21.%20Dynamic%20Programming/10.%20DP%20on%20Trees/0834.%20Sum%20of%20Distances%20in%20Tree/0834.%20Sum%20of%20Distances%20in%20Tree.md) |
| 6 | [3562. Maximum Profit from Trading Stocks with Discounts](https://leetcode.com/problems/maximum-profit-from-trading-stocks-with-discounts/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/10.%20DP%20on%20Trees/3562.%20Maximum%20Profit%20from%20Trading%20Stocks%20with%20Discounts/3562.%20Maximum%20Profit%20from%20Trading%20Stocks%20with%20Discounts.md) |

### 21.11. Bitmask DP

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [847. Shortest Path Visiting All Nodes](https://leetcode.com/problems/shortest-path-visiting-all-nodes/) | Hard | 6+ months | 7.4 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/11.%20Bitmask%20DP/0847.%20Shortest%20Path%20Visiting%20All%20Nodes/0847.%20Shortest%20Path%20Visiting%20All%20Nodes.md) |
| 2 | [691. Stickers to Spell Word](https://leetcode.com/problems/stickers-to-spell-word/) | Hard | 6+ months | 6.4 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/11.%20Bitmask%20DP/0691.%20Stickers%20to%20Spell%20Word/0691.%20Stickers%20to%20Spell%20Word.md) |
| 3 | [464. Can I Win](https://leetcode.com/problems/can-i-win/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/11.%20Bitmask%20DP/0464.%20Can%20I%20Win/0464.%20Can%20I%20Win.md) |
| 4 | [1931. Painting a Grid With Three Different Colors](https://leetcode.com/problems/painting-a-grid-with-three-different-colors/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/11.%20Bitmask%20DP/1931.%20Painting%20a%20Grid%20With%20Three%20Different%20Colors/1931.%20Painting%20a%20Grid%20With%20Three%20Different%20Colors.md) |
| 5 | [3533. Concatenated Divisibility](https://leetcode.com/problems/concatenated-divisibility/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/11.%20Bitmask%20DP/3533.%20Concatenated%20Divisibility/3533.%20Concatenated%20Divisibility.md) |
| 6 | [1947. Maximum Compatibility Score Sum](https://leetcode.com/problems/maximum-compatibility-score-sum/) | Medium | 6+ months | 36.1 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/11.%20Bitmask%20DP/1947.%20Maximum%20Compatibility%20Score%20Sum/1947.%20Maximum%20Compatibility%20Score%20Sum.md) |

### 21.12. State Machine DP (Stocks)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [123. Best Time to Buy and Sell Stock III](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-iii/) | Hard | 6+ months | 39.0 | ✅ Solved |  |  |  | [notes](21.%20Dynamic%20Programming/12.%20State%20Machine%20DP%20%28Stocks%29/0123.%20Best%20Time%20to%20Buy%20and%20Sell%20Stock%20III/0123.%20Best%20Time%20to%20Buy%20and%20Sell%20Stock%20III.md) |
| 2 | [1653. Minimum Deletions to Make String Balanced](https://leetcode.com/problems/minimum-deletions-to-make-string-balanced/) | Medium | 6+ months | 15.1 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/12.%20State%20Machine%20DP%20%28Stocks%29/1653.%20Minimum%20Deletions%20to%20Make%20String%20Balanced/1653.%20Minimum%20Deletions%20to%20Make%20String%20Balanced.md) |
| 3 | [1262. Greatest Sum Divisible by Three](https://leetcode.com/problems/greatest-sum-divisible-by-three/) | Medium | 6+ months | 11.4 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/12.%20State%20Machine%20DP%20%28Stocks%29/1262.%20Greatest%20Sum%20Divisible%20by%20Three/1262.%20Greatest%20Sum%20Divisible%20by%20Three.md) |
| 4 | [3640. Trionic Array II](https://leetcode.com/problems/trionic-array-ii/) | Hard | 6+ months | 9.4 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/12.%20State%20Machine%20DP%20%28Stocks%29/3640.%20Trionic%20Array%20II/3640.%20Trionic%20Array%20II.md) |
| 5 | [3573. Best Time to Buy and Sell Stock V](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-v/) | Medium | 6+ months | 6.1 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/12.%20State%20Machine%20DP%20%28Stocks%29/3573.%20Best%20Time%20to%20Buy%20and%20Sell%20Stock%20V/3573.%20Best%20Time%20to%20Buy%20and%20Sell%20Stock%20V.md) |
| 6 | [926. Flip String to Monotone Increasing](https://leetcode.com/problems/flip-string-to-monotone-increasing/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/12.%20State%20Machine%20DP%20%28Stocks%29/0926.%20Flip%20String%20to%20Monotone%20Increasing/0926.%20Flip%20String%20to%20Monotone%20Increasing.md) |
| 7 | [1911. Maximum Alternating Subsequence Sum](https://leetcode.com/problems/maximum-alternating-subsequence-sum/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/12.%20State%20Machine%20DP%20%28Stocks%29/1911.%20Maximum%20Alternating%20Subsequence%20Sum/1911.%20Maximum%20Alternating%20Subsequence%20Sum.md) |
| 8 | [3068. Find the Maximum Sum of Node Values](https://leetcode.com/problems/find-the-maximum-sum-of-node-values/) | Hard | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](21.%20Dynamic%20Programming/12.%20State%20Machine%20DP%20%28Stocks%29/3068.%20Find%20the%20Maximum%20Sum%20of%20Node%20Values/3068.%20Find%20the%20Maximum%20Sum%20of%20Node%20Values.md) |
| 9 | [714. Best Time to Buy and Sell Stock with Transaction Fee](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-with-transaction-fee/) | Medium | 6+ months | 36.9 | ✅ Solved |  |  |  | [notes](21.%20Dynamic%20Programming/12.%20State%20Machine%20DP%20%28Stocks%29/0714.%20Best%20Time%20to%20Buy%20and%20Sell%20Stock%20with%20Transaction%20Fee/0714.%20Best%20Time%20to%20Buy%20and%20Sell%20Stock%20with%20Transaction%20Fee.md) |
| 10 | [801. Minimum Swaps To Make Sequences Increasing](https://leetcode.com/problems/minimum-swaps-to-make-sequences-increasing/) | Hard | 6+ months | 36.1 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/12.%20State%20Machine%20DP%20%28Stocks%29/0801.%20Minimum%20Swaps%20To%20Make%20Sequences%20Increasing/0801.%20Minimum%20Swaps%20To%20Make%20Sequences%20Increasing.md) |
| 11 | [188. Best Time to Buy and Sell Stock IV](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-iv/) | Hard | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](21.%20Dynamic%20Programming/12.%20State%20Machine%20DP%20%28Stocks%29/0188.%20Best%20Time%20to%20Buy%20and%20Sell%20Stock%20IV/0188.%20Best%20Time%20to%20Buy%20and%20Sell%20Stock%20IV.md) |
| 12 | [1186. Maximum Subarray Sum with One Deletion](https://leetcode.com/problems/maximum-subarray-sum-with-one-deletion/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/12.%20State%20Machine%20DP%20%28Stocks%29/1186.%20Maximum%20Subarray%20Sum%20with%20One%20Deletion/1186.%20Maximum%20Subarray%20Sum%20with%20One%20Deletion.md) |

### 21.13. Digit DP

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [233. Number of Digit One](https://leetcode.com/problems/number-of-digit-one/) | Hard | 6 months | 14.1 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/13.%20Digit%20DP/0233.%20Number%20of%20Digit%20One/0233.%20Number%20of%20Digit%20One.md) |
| 2 | [2999. Count the Number of Powerful Integers](https://leetcode.com/problems/count-the-number-of-powerful-integers/) | Hard | 6+ months | 6.0 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/13.%20Digit%20DP/2999.%20Count%20the%20Number%20of%20Powerful%20Integers/2999.%20Count%20the%20Number%20of%20Powerful%20Integers.md) |
| 3 | [3490. Count Beautiful Numbers](https://leetcode.com/problems/count-beautiful-numbers/) | Hard | 6+ months | 5.9 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/13.%20Digit%20DP/3490.%20Count%20Beautiful%20Numbers/3490.%20Count%20Beautiful%20Numbers.md) |

### 21.14. Counting DP

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [96. Unique Binary Search Trees](https://leetcode.com/problems/unique-binary-search-trees/) | Medium | 3 months | 33.8 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/14.%20Counting%20DP/0096.%20Unique%20Binary%20Search%20Trees/0096.%20Unique%20Binary%20Search%20Trees.md) |
| 2 | [3336. Find the Number of Subsequences With Equal GCD](https://leetcode.com/problems/find-the-number-of-subsequences-with-equal-gcd/) | Hard | 6 months | 16.6 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/14.%20Counting%20DP/3336.%20Find%20the%20Number%20of%20Subsequences%20With%20Equal%20GCD/3336.%20Find%20the%20Number%20of%20Subsequences%20With%20Equal%20GCD.md) |
| 3 | [3699. Number of ZigZag Arrays I](https://leetcode.com/problems/number-of-zigzag-arrays-i/) | Hard | 6 months | 5.0 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/14.%20Counting%20DP/3699.%20Number%20of%20ZigZag%20Arrays%20I/3699.%20Number%20of%20ZigZag%20Arrays%20I.md) |
| 4 | [940. Distinct Subsequences II](https://leetcode.com/problems/distinct-subsequences-ii/) | Hard | 6+ months | 11.1 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/14.%20Counting%20DP/0940.%20Distinct%20Subsequences%20II/0940.%20Distinct%20Subsequences%20II.md) |
| 5 | [935. Knight Dialer](https://leetcode.com/problems/knight-dialer/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/14.%20Counting%20DP/0935.%20Knight%20Dialer/0935.%20Knight%20Dialer.md) |
| 6 | [1155. Number of Dice Rolls With Target Sum](https://leetcode.com/problems/number-of-dice-rolls-with-target-sum/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/14.%20Counting%20DP/1155.%20Number%20of%20Dice%20Rolls%20With%20Target%20Sum/1155.%20Number%20of%20Dice%20Rolls%20With%20Target%20Sum.md) |
| 7 | [1411. Number of Ways to Paint N × 3 Grid](https://leetcode.com/problems/number-of-ways-to-paint-n-3-grid/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/14.%20Counting%20DP/1411.%20Number%20of%20Ways%20to%20Paint%20N%20%C3%97%203%20Grid/1411.%20Number%20of%20Ways%20to%20Paint%20N%20%C3%97%203%20Grid.md) |
| 8 | [1621. Number of Sets of K Non-Overlapping Line Segments](https://leetcode.com/problems/number-of-sets-of-k-non-overlapping-line-segments/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/14.%20Counting%20DP/1621.%20Number%20of%20Sets%20of%20K%20Non-Overlapping%20Line%20Segments/1621.%20Number%20of%20Sets%20of%20K%20Non-Overlapping%20Line%20Segments.md) |
| 9 | [1639. Number of Ways to Form a Target String Given a Dictionary](https://leetcode.com/problems/number-of-ways-to-form-a-target-string-given-a-dictionary/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/14.%20Counting%20DP/1639.%20Number%20of%20Ways%20to%20Form%20a%20Target%20String%20Given%20a%20Dictionary/1639.%20Number%20of%20Ways%20to%20Form%20a%20Target%20String%20Given%20a%20Dictionary.md) |
| 10 | [3129. Find All Possible Stable Binary Arrays I](https://leetcode.com/problems/find-all-possible-stable-binary-arrays-i/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/14.%20Counting%20DP/3129.%20Find%20All%20Possible%20Stable%20Binary%20Arrays%20I/3129.%20Find%20All%20Possible%20Stable%20Binary%20Arrays%20I.md) |
| 11 | [3335. Total Characters in String After Transformations I](https://leetcode.com/problems/total-characters-in-string-after-transformations-i/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/14.%20Counting%20DP/3335.%20Total%20Characters%20in%20String%20After%20Transformations%20I/3335.%20Total%20Characters%20in%20String%20After%20Transformations%20I.md) |
| 12 | [3343. Count Number of Balanced Permutations](https://leetcode.com/problems/count-number-of-balanced-permutations/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/14.%20Counting%20DP/3343.%20Count%20Number%20of%20Balanced%20Permutations/3343.%20Count%20Number%20of%20Balanced%20Permutations.md) |
| 13 | [3539. Find Sum of Array Product of Magical Sequences](https://leetcode.com/problems/find-sum-of-array-product-of-magical-sequences/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/14.%20Counting%20DP/3539.%20Find%20Sum%20of%20Array%20Product%20of%20Magical%20Sequences/3539.%20Find%20Sum%20of%20Array%20Product%20of%20Magical%20Sequences.md) |
| 14 | [920. Number of Music Playlists](https://leetcode.com/problems/number-of-music-playlists/) | Hard | 6+ months | 7.6 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/14.%20Counting%20DP/0920.%20Number%20of%20Music%20Playlists/0920.%20Number%20of%20Music%20Playlists.md) |
| 15 | [1395. Count Number of Teams](https://leetcode.com/problems/count-number-of-teams/) | Medium | 6+ months | 5.8 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/14.%20Counting%20DP/1395.%20Count%20Number%20of%20Teams/1395.%20Count%20Number%20of%20Teams.md) |

### 21.15. Memoized DFS

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [1140. Stone Game II](https://leetcode.com/problems/stone-game-ii/) | Medium | 6 months | 7.2 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/15.%20Memoized%20DFS/1140.%20Stone%20Game%20II/1140.%20Stone%20Game%20II.md) |
| 2 | [329. Longest Increasing Path in a Matrix](https://leetcode.com/problems/longest-increasing-path-in-a-matrix/) | Hard | 6+ months | 40.1 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/15.%20Memoized%20DFS/0329.%20Longest%20Increasing%20Path%20in%20a%20Matrix/0329.%20Longest%20Increasing%20Path%20in%20a%20Matrix.md) |
| 3 | [1900. The Earliest and Latest Rounds Where Players Compete](https://leetcode.com/problems/the-earliest-and-latest-rounds-where-players-compete/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](21.%20Dynamic%20Programming/15.%20Memoized%20DFS/1900.%20The%20Earliest%20and%20Latest%20Rounds%20Where%20Players%20Compete/1900.%20The%20Earliest%20and%20Latest%20Rounds%20Where%20Players%20Compete.md) |

## 22. Advanced Data Structures

7 problems: 0 Easy, 3 Medium, 4 Hard. [Open chapter README](22.%20Advanced%20Data%20Structures/README.md) · [Back to top](#chapters)

### 22.01. Segment Tree

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [3161. Block Placement Queries](https://leetcode.com/problems/block-placement-queries/) | Hard | 6+ months | 6.7 | Todo |  |  |  | [notes](22.%20Advanced%20Data%20Structures/01.%20Segment%20Tree/3161.%20Block%20Placement%20Queries/3161.%20Block%20Placement%20Queries.md) |

### 22.02. Ordered Set & TreeMap

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [2817. Minimum Absolute Difference Between Elements With Constraint](https://leetcode.com/problems/minimum-absolute-difference-between-elements-with-constraint/) | Medium | 6+ months | 17.4 | Todo |  |  |  | [notes](22.%20Advanced%20Data%20Structures/02.%20Ordered%20Set%20%26%20TreeMap/2817.%20Minimum%20Absolute%20Difference%20Between%20Elements%20With%20Constraint/2817.%20Minimum%20Absolute%20Difference%20Between%20Elements%20With%20Constraint.md) |
| 2 | [1488. Avoid Flood in The City](https://leetcode.com/problems/avoid-flood-in-the-city/) | Medium | 6+ months | 9.9 | Todo |  |  |  | [notes](22.%20Advanced%20Data%20Structures/02.%20Ordered%20Set%20%26%20TreeMap/1488.%20Avoid%20Flood%20in%20The%20City/1488.%20Avoid%20Flood%20in%20The%20City.md) |
| 3 | [715. Range Module](https://leetcode.com/problems/range-module/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](22.%20Advanced%20Data%20Structures/02.%20Ordered%20Set%20%26%20TreeMap/0715.%20Range%20Module/0715.%20Range%20Module.md) |
| 4 | [729. My Calendar I](https://leetcode.com/problems/my-calendar-i/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](22.%20Advanced%20Data%20Structures/02.%20Ordered%20Set%20%26%20TreeMap/0729.%20My%20Calendar%20I/0729.%20My%20Calendar%20I.md) |
| 5 | [3636. Threshold Majority Queries](https://leetcode.com/problems/threshold-majority-queries/) | Hard | 6+ months | 36.9 | Todo |  |  |  | [notes](22.%20Advanced%20Data%20Structures/02.%20Ordered%20Set%20%26%20TreeMap/3636.%20Threshold%20Majority%20Queries/3636.%20Threshold%20Majority%20Queries.md) |

### 22.03. Sparse Table & Binary Lifting

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [3534. Path Existence Queries in a Graph II](https://leetcode.com/problems/path-existence-queries-in-a-graph-ii/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](22.%20Advanced%20Data%20Structures/03.%20Sparse%20Table%20%26%20Binary%20Lifting/3534.%20Path%20Existence%20Queries%20in%20a%20Graph%20II/3534.%20Path%20Existence%20Queries%20in%20a%20Graph%20II.md) |

## 23. Design

45 problems: 13 Easy, 25 Medium, 7 Hard. [Open chapter README](23.%20Design/README.md) · [Back to top](#chapters)

### 23.01. Data Structure Design

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [155. Min Stack](https://leetcode.com/problems/min-stack/) | Medium | 6 months | 37.0 | ✅ Solved |  |  |  | [notes](23.%20Design/01.%20Data%20Structure%20Design/0155.%20Min%20Stack/0155.%20Min%20Stack.md) |
| 2 | [1570. Dot Product of Two Sparse Vectors](https://leetcode.com/problems/dot-product-of-two-sparse-vectors/) 🔒 | Medium | 6+ months | 76.1 | Todo |  |  |  | [notes](23.%20Design/01.%20Data%20Structure%20Design/1570.%20Dot%20Product%20of%20Two%20Sparse%20Vectors/1570.%20Dot%20Product%20of%20Two%20Sparse%20Vectors.md) |
| 3 | [622. Design Circular Queue](https://leetcode.com/problems/design-circular-queue/) | Medium | 6+ months | 20.7 | Todo |  |  |  | [notes](23.%20Design/01.%20Data%20Structure%20Design/0622.%20Design%20Circular%20Queue/0622.%20Design%20Circular%20Queue.md) |
| 4 | [706. Design HashMap](https://leetcode.com/problems/design-hashmap/) | Easy | 6+ months | 13.9 | Todo |  |  |  | [notes](23.%20Design/01.%20Data%20Structure%20Design/0706.%20Design%20HashMap/0706.%20Design%20HashMap.md) |
| 5 | [432. All O`one Data Structure](https://leetcode.com/problems/all-oone-data-structure/) | Hard | 6+ months | 12.7 | Todo |  |  |  | [notes](23.%20Design/01.%20Data%20Structure%20Design/0432.%20All%20O%60one%20Data%20Structure/0432.%20All%20O%60one%20Data%20Structure.md) |
| 6 | [1206. Design Skiplist](https://leetcode.com/problems/design-skiplist/) | Hard | 6+ months | 10.9 | Todo |  |  |  | [notes](23.%20Design/01.%20Data%20Structure%20Design/1206.%20Design%20Skiplist/1206.%20Design%20Skiplist.md) |
| 7 | [2034. Stock Price Fluctuation ](https://leetcode.com/problems/stock-price-fluctuation/) | Medium | 6+ months | 10.0 | Todo |  |  |  | [notes](23.%20Design/01.%20Data%20Structure%20Design/2034.%20Stock%20Price%20Fluctuation%20/2034.%20Stock%20Price%20Fluctuation%20.md) |
| 8 | [2336. Smallest Number in Infinite Set](https://leetcode.com/problems/smallest-number-in-infinite-set/) | Medium | 6+ months | 10.0 | Todo |  |  |  | [notes](23.%20Design/01.%20Data%20Structure%20Design/2336.%20Smallest%20Number%20in%20Infinite%20Set/2336.%20Smallest%20Number%20in%20Infinite%20Set.md) |
| 9 | [641. Design Circular Deque](https://leetcode.com/problems/design-circular-deque/) | Medium | 6+ months | 8.5 | Todo |  |  |  | [notes](23.%20Design/01.%20Data%20Structure%20Design/0641.%20Design%20Circular%20Deque/0641.%20Design%20Circular%20Deque.md) |
| 10 | [707. Design Linked List](https://leetcode.com/problems/design-linked-list/) | Medium | 6+ months | 7.3 | Todo |  |  |  | [notes](23.%20Design/01.%20Data%20Structure%20Design/0707.%20Design%20Linked%20List/0707.%20Design%20Linked%20List.md) |
| 11 | [895. Maximum Frequency Stack](https://leetcode.com/problems/maximum-frequency-stack/) | Hard | 6+ months | 6.4 | Todo |  |  |  | [notes](23.%20Design/01.%20Data%20Structure%20Design/0895.%20Maximum%20Frequency%20Stack/0895.%20Maximum%20Frequency%20Stack.md) |
| 12 | [705. Design HashSet](https://leetcode.com/problems/design-hashset/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](23.%20Design/01.%20Data%20Structure%20Design/0705.%20Design%20HashSet/0705.%20Design%20HashSet.md) |
| 13 | [716. Max Stack](https://leetcode.com/problems/max-stack/) 🔒 | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](23.%20Design/01.%20Data%20Structure%20Design/0716.%20Max%20Stack/0716.%20Max%20Stack.md) |
| 14 | [1865. Finding Pairs With a Certain Sum](https://leetcode.com/problems/finding-pairs-with-a-certain-sum/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](23.%20Design/01.%20Data%20Structure%20Design/1865.%20Finding%20Pairs%20With%20a%20Certain%20Sum/1865.%20Finding%20Pairs%20With%20a%20Certain%20Sum.md) |
| 15 | [2013. Detect Squares](https://leetcode.com/problems/detect-squares/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](23.%20Design/01.%20Data%20Structure%20Design/2013.%20Detect%20Squares/2013.%20Detect%20Squares.md) |
| 16 | [2296. Design a Text Editor](https://leetcode.com/problems/design-a-text-editor/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](23.%20Design/01.%20Data%20Structure%20Design/2296.%20Design%20a%20Text%20Editor/2296.%20Design%20a%20Text%20Editor.md) |
| 17 | [3829. Design Ride Sharing System](https://leetcode.com/problems/design-ride-sharing-system/) | Medium | 6+ months | 36.1 | Todo |  |  |  | [notes](23.%20Design/01.%20Data%20Structure%20Design/3829.%20Design%20Ride%20Sharing%20System/3829.%20Design%20Ride%20Sharing%20System.md) |

### 23.02. LRU & LFU Cache

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203; | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [146. LRU Cache](https://leetcode.com/problems/lru-cache/) | Medium | 3 months | 76.8 | ✅ Solved |  |  |  | [notes](23.%20Design/02.%20LRU%20%26%20LFU%20Cache/0146.%20LRU%20Cache/0146.%20LRU%20Cache.md) |
| 2 | [460. LFU Cache](https://leetcode.com/problems/lfu-cache/) | Hard | 6+ months | 8.0 | ✅ Solved |  |  |  | [notes](23.%20Design/02.%20LRU%20%26%20LFU%20Cache/0460.%20LFU%20Cache/0460.%20LFU%20Cache.md) |

### 23.03. Iterator Design

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [173. Binary Search Tree Iterator](https://leetcode.com/problems/binary-search-tree-iterator/) | Medium | 6+ months | 60.6 | ✅ Solved |  |  |  | [notes](23.%20Design/03.%20Iterator%20Design/0173.%20Binary%20Search%20Tree%20Iterator/0173.%20Binary%20Search%20Tree%20Iterator.md) |
| 2 | [341. Flatten Nested List Iterator](https://leetcode.com/problems/flatten-nested-list-iterator/) | Medium | 6+ months | 43.8 | Todo |  |  |  | [notes](23.%20Design/03.%20Iterator%20Design/0341.%20Flatten%20Nested%20List%20Iterator/0341.%20Flatten%20Nested%20List%20Iterator.md) |
| 3 | [1586. Binary Search Tree Iterator II](https://leetcode.com/problems/binary-search-tree-iterator-ii/) 🔒 | Medium | 6+ months | 36.1 | Todo |  |  |  | [notes](23.%20Design/03.%20Iterator%20Design/1586.%20Binary%20Search%20Tree%20Iterator%20II/1586.%20Binary%20Search%20Tree%20Iterator%20II.md) |

### 23.04. Data Stream Design

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [346. Moving Average from Data Stream](https://leetcode.com/problems/moving-average-from-data-stream/) 🔒 | Easy | 6+ months | 68.8 | Todo |  |  |  | [notes](23.%20Design/04.%20Data%20Stream%20Design/0346.%20Moving%20Average%20from%20Data%20Stream/0346.%20Moving%20Average%20from%20Data%20Stream.md) |

### 23.05. Randomized Design

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [380. Insert Delete GetRandom O(1)](https://leetcode.com/problems/insert-delete-getrandom-o1/) | Medium | 6+ months | 50.1 | Todo |  |  |  | [notes](23.%20Design/05.%20Randomized%20Design/0380.%20Insert%20Delete%20GetRandom%20O%281%29/0380.%20Insert%20Delete%20GetRandom%20O%281%29.md) |
| 2 | [381. Insert Delete GetRandom O(1) - Duplicates allowed](https://leetcode.com/problems/insert-delete-getrandom-o1-duplicates-allowed/) | Hard | 6+ months | 13.1 | Todo |  |  |  | [notes](23.%20Design/05.%20Randomized%20Design/0381.%20Insert%20Delete%20GetRandom%20O%281%29%20-%20Duplicates%20allowed/0381.%20Insert%20Delete%20GetRandom%20O%281%29%20-%20Duplicates%20allowed.md) |
| 3 | [384. Shuffle an Array](https://leetcode.com/problems/shuffle-an-array/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](23.%20Design/05.%20Randomized%20Design/0384.%20Shuffle%20an%20Array/0384.%20Shuffle%20an%20Array.md) |

### 23.06. System & OOP Design

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [348. Design Tic-Tac-Toe](https://leetcode.com/problems/design-tic-tac-toe/) 🔒 | Medium | 6+ months | 41.8 | Todo |  |  |  | [notes](23.%20Design/06.%20System%20%26%20OOP%20Design/0348.%20Design%20Tic-Tac-Toe/0348.%20Design%20Tic-Tac-Toe.md) |
| 2 | [2043. Simple Bank System](https://leetcode.com/problems/simple-bank-system/) | Medium | 6+ months | 39.0 | Todo |  |  |  | [notes](23.%20Design/06.%20System%20%26%20OOP%20Design/2043.%20Simple%20Bank%20System/2043.%20Simple%20Bank%20System.md) |
| 3 | [2502. Design Memory Allocator](https://leetcode.com/problems/design-memory-allocator/) | Medium | 6+ months | 6.3 | Todo |  |  |  | [notes](23.%20Design/06.%20System%20%26%20OOP%20Design/2502.%20Design%20Memory%20Allocator/2502.%20Design%20Memory%20Allocator.md) |
| 4 | [1603. Design Parking System](https://leetcode.com/problems/design-parking-system/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](23.%20Design/06.%20System%20%26%20OOP%20Design/1603.%20Design%20Parking%20System/1603.%20Design%20Parking%20System.md) |
| 5 | [2619. Array Prototype Last](https://leetcode.com/problems/array-prototype-last/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](23.%20Design/06.%20System%20%26%20OOP%20Design/2619.%20Array%20Prototype%20Last/2619.%20Array%20Prototype%20Last.md) |
| 6 | [2620. Counter](https://leetcode.com/problems/counter/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](23.%20Design/06.%20System%20%26%20OOP%20Design/2620.%20Counter/2620.%20Counter.md) |
| 7 | [2627. Debounce](https://leetcode.com/problems/debounce/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](23.%20Design/06.%20System%20%26%20OOP%20Design/2627.%20Debounce/2627.%20Debounce.md) |
| 8 | [2629. Function Composition](https://leetcode.com/problems/function-composition/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](23.%20Design/06.%20System%20%26%20OOP%20Design/2629.%20Function%20Composition/2629.%20Function%20Composition.md) |
| 9 | [2635. Apply Transform Over Each Element in Array](https://leetcode.com/problems/apply-transform-over-each-element-in-array/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](23.%20Design/06.%20System%20%26%20OOP%20Design/2635.%20Apply%20Transform%20Over%20Each%20Element%20in%20Array/2635.%20Apply%20Transform%20Over%20Each%20Element%20in%20Array.md) |
| 10 | [2694. Event Emitter](https://leetcode.com/problems/event-emitter/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](23.%20Design/06.%20System%20%26%20OOP%20Design/2694.%20Event%20Emitter/2694.%20Event%20Emitter.md) |
| 11 | [2704. To Be Or Not To Be](https://leetcode.com/problems/to-be-or-not-to-be/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](23.%20Design/06.%20System%20%26%20OOP%20Design/2704.%20To%20Be%20Or%20Not%20To%20Be/2704.%20To%20Be%20Or%20Not%20To%20Be.md) |
| 12 | [2715. Timeout Cancellation](https://leetcode.com/problems/timeout-cancellation/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](23.%20Design/06.%20System%20%26%20OOP%20Design/2715.%20Timeout%20Cancellation/2715.%20Timeout%20Cancellation.md) |
| 13 | [2723. Add Two Promises](https://leetcode.com/problems/add-two-promises/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](23.%20Design/06.%20System%20%26%20OOP%20Design/2723.%20Add%20Two%20Promises/2723.%20Add%20Two%20Promises.md) |
| 14 | [1357. Apply Discount Every n Orders](https://leetcode.com/problems/apply-discount-every-n-orders/) | Medium | 6+ months | 37.1 | Todo |  |  |  | [notes](23.%20Design/06.%20System%20%26%20OOP%20Design/1357.%20Apply%20Discount%20Every%20n%20Orders/1357.%20Apply%20Discount%20Every%20n%20Orders.md) |
| 15 | [535. Encode and Decode TinyURL](https://leetcode.com/problems/encode-and-decode-tinyurl/) | Medium | 6+ months | 36.1 | Todo |  |  |  | [notes](23.%20Design/06.%20System%20%26%20OOP%20Design/0535.%20Encode%20and%20Decode%20TinyURL/0535.%20Encode%20and%20Decode%20TinyURL.md) |

### 23.07. Time-Based Design (Rate Limiter, Hit Counter)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [933. Number of Recent Calls](https://leetcode.com/problems/number-of-recent-calls/) | Easy | 6+ months | 23.0 | Todo |  |  |  | [notes](23.%20Design/07.%20Time-Based%20Design%20%28Rate%20Limiter%2C%20Hit%20Counter%29/0933.%20Number%20of%20Recent%20Calls/0933.%20Number%20of%20Recent%20Calls.md) |
| 2 | [981. Time Based Key-Value Store](https://leetcode.com/problems/time-based-key-value-store/) | Medium | 6+ months | 13.7 | ✅ Solved |  |  |  | [notes](23.%20Design/07.%20Time-Based%20Design%20%28Rate%20Limiter%2C%20Hit%20Counter%29/0981.%20Time%20Based%20Key-Value%20Store/0981.%20Time%20Based%20Key-Value%20Store.md) |
| 3 | [362. Design Hit Counter](https://leetcode.com/problems/design-hit-counter/) 🔒 | Medium | 6+ months | 9.3 | Todo |  |  |  | [notes](23.%20Design/07.%20Time-Based%20Design%20%28Rate%20Limiter%2C%20Hit%20Counter%29/0362.%20Design%20Hit%20Counter/0362.%20Design%20Hit%20Counter.md) |
| 4 | [359. Logger Rate Limiter](https://leetcode.com/problems/logger-rate-limiter/) 🔒 | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](23.%20Design/07.%20Time-Based%20Design%20%28Rate%20Limiter%2C%20Hit%20Counter%29/0359.%20Logger%20Rate%20Limiter/0359.%20Logger%20Rate%20Limiter.md) |

## 24. SQL & Database

85 problems: 48 Easy, 32 Medium, 5 Hard. [Open chapter README](24.%20SQL%20%26%20Database/README.md) · [Back to top](#chapters)

### 24.01. Basic Select & Filter

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [1757. Recyclable and Low Fat Products](https://leetcode.com/problems/recyclable-and-low-fat-products/) | Easy | 3 months | 48.7 | ✅ Solved |  |  |  | [notes](24.%20SQL%20%26%20Database/01.%20Basic%20Select%20%26%20Filter/1757.%20Recyclable%20and%20Low%20Fat%20Products/1757.%20Recyclable%20and%20Low%20Fat%20Products.md) |
| 2 | [2891. Method Chaining](https://leetcode.com/problems/method-chaining/) | Easy | 3 months | 8.3 | Todo |  |  |  | [notes](24.%20SQL%20%26%20Database/01.%20Basic%20Select%20%26%20Filter/2891.%20Method%20Chaining/2891.%20Method%20Chaining.md) |
| 3 | [1148. Article Views I](https://leetcode.com/problems/article-views-i/) | Easy | 6 months | 31.2 | ✅ Solved |  |  |  | [notes](24.%20SQL%20%26%20Database/01.%20Basic%20Select%20%26%20Filter/1148.%20Article%20Views%20I/1148.%20Article%20Views%20I.md) |
| 4 | [584. Find Customer Referee](https://leetcode.com/problems/find-customer-referee/) | Easy | 6 months | 15.3 | ✅ Solved |  |  |  | [notes](24.%20SQL%20%26%20Database/01.%20Basic%20Select%20%26%20Filter/0584.%20Find%20Customer%20Referee/0584.%20Find%20Customer%20Referee.md) |
| 5 | [620. Not Boring Movies](https://leetcode.com/problems/not-boring-movies/) | Easy | 6 months | 14.9 | ✅ Solved |  |  |  | [notes](24.%20SQL%20%26%20Database/01.%20Basic%20Select%20%26%20Filter/0620.%20Not%20Boring%20Movies/0620.%20Not%20Boring%20Movies.md) |
| 6 | [1683. Invalid Tweets](https://leetcode.com/problems/invalid-tweets/) | Easy | 6 months | 9.6 | ✅ Solved |  |  |  | [notes](24.%20SQL%20%26%20Database/01.%20Basic%20Select%20%26%20Filter/1683.%20Invalid%20Tweets/1683.%20Invalid%20Tweets.md) |
| 7 | [196. Delete Duplicate Emails](https://leetcode.com/problems/delete-duplicate-emails/) | Easy | 6+ months | 12.7 | ✅ Solved |  |  |  | [notes](24.%20SQL%20%26%20Database/01.%20Basic%20Select%20%26%20Filter/0196.%20Delete%20Duplicate%20Emails/0196.%20Delete%20Duplicate%20Emails.md) |
| 8 | [595. Big Countries](https://leetcode.com/problems/big-countries/) | Easy | 6+ months | 10.1 | ✅ Solved |  |  |  | [notes](24.%20SQL%20%26%20Database/01.%20Basic%20Select%20%26%20Filter/0595.%20Big%20Countries/0595.%20Big%20Countries.md) |
| 9 | [2877. Create a DataFrame from List](https://leetcode.com/problems/create-a-dataframe-from-list/) | Easy | 6+ months | 10.1 | Todo |  |  |  | [notes](24.%20SQL%20%26%20Database/01.%20Basic%20Select%20%26%20Filter/2877.%20Create%20a%20DataFrame%20from%20List/2877.%20Create%20a%20DataFrame%20from%20List.md) |
| 10 | [1795. Rearrange Products Table](https://leetcode.com/problems/rearrange-products-table/) | Easy | 6+ months | 5.6 | Todo |  |  |  | [notes](24.%20SQL%20%26%20Database/01.%20Basic%20Select%20%26%20Filter/1795.%20Rearrange%20Products%20Table/1795.%20Rearrange%20Products%20Table.md) |
| 11 | [2879. Display the First Three Rows](https://leetcode.com/problems/display-the-first-three-rows/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](24.%20SQL%20%26%20Database/01.%20Basic%20Select%20%26%20Filter/2879.%20Display%20the%20First%20Three%20Rows/2879.%20Display%20the%20First%20Three%20Rows.md) |
| 12 | [2889. Reshape Data: Pivot](https://leetcode.com/problems/reshape-data-pivot/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](24.%20SQL%20%26%20Database/01.%20Basic%20Select%20%26%20Filter/2889.%20Reshape%20Data-%20Pivot/2889.%20Reshape%20Data-%20Pivot.md) |

### 24.02. Joins

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [197. Rising Temperature](https://leetcode.com/problems/rising-temperature/) | Easy | 3 months | 24.3 | ✅ Solved |  |  |  | [notes](24.%20SQL%20%26%20Database/02.%20Joins/0197.%20Rising%20Temperature/0197.%20Rising%20Temperature.md) |
| 2 | [175. Combine Two Tables](https://leetcode.com/problems/combine-two-tables/) | Easy | 3 months | 23.8 | ✅ Solved |  |  |  | [notes](24.%20SQL%20%26%20Database/02.%20Joins/0175.%20Combine%20Two%20Tables/0175.%20Combine%20Two%20Tables.md) |
| 3 | [181. Employees Earning More Than Their Managers](https://leetcode.com/problems/employees-earning-more-than-their-managers/) | Easy | 3 months | 16.0 | ✅ Solved |  |  |  | [notes](24.%20SQL%20%26%20Database/02.%20Joins/0181.%20Employees%20Earning%20More%20Than%20Their%20Managers/0181.%20Employees%20Earning%20More%20Than%20Their%20Managers.md) |
| 4 | [577. Employee Bonus](https://leetcode.com/problems/employee-bonus/) | Easy | 6 months | 17.8 | ✅ Solved |  |  |  | [notes](24.%20SQL%20%26%20Database/02.%20Joins/0577.%20Employee%20Bonus/0577.%20Employee%20Bonus.md) |
| 5 | [1280. Students and Examinations](https://leetcode.com/problems/students-and-examinations/) | Easy | 6 months | 12.4 | ✅ Solved |  |  |  | [notes](24.%20SQL%20%26%20Database/02.%20Joins/1280.%20Students%20and%20Examinations/1280.%20Students%20and%20Examinations.md) |
| 6 | [1661. Average Time of Process per Machine](https://leetcode.com/problems/average-time-of-process-per-machine/) | Easy | 6+ months | 40.0 | ✅ Solved |  |  |  | [notes](24.%20SQL%20%26%20Database/02.%20Joins/1661.%20Average%20Time%20of%20Process%20per%20Machine/1661.%20Average%20Time%20of%20Process%20per%20Machine.md) |
| 7 | [1264. Page Recommendations](https://leetcode.com/problems/page-recommendations/) 🔒 | Medium | 6+ months | 39.3 | Todo |  |  |  | [notes](24.%20SQL%20%26%20Database/02.%20Joins/1264.%20Page%20Recommendations/1264.%20Page%20Recommendations.md) |
| 8 | [1892. Page Recommendations II](https://leetcode.com/problems/page-recommendations-ii/) 🔒 | Hard | 6+ months | 37.5 | Todo |  |  |  | [notes](24.%20SQL%20%26%20Database/02.%20Joins/1892.%20Page%20Recommendations%20II/1892.%20Page%20Recommendations%20II.md) |
| 9 | [1949. Strong Friendship](https://leetcode.com/problems/strong-friendship/) 🔒 | Medium | 6+ months | 37.1 | Todo |  |  |  | [notes](24.%20SQL%20%26%20Database/02.%20Joins/1949.%20Strong%20Friendship/1949.%20Strong%20Friendship.md) |
| 10 | [1581. Customer Who Visited but Did Not Make Any Transactions](https://leetcode.com/problems/customer-who-visited-but-did-not-make-any-transactions/) | Easy | 6+ months | 20.6 | ✅ Solved |  |  |  | [notes](24.%20SQL%20%26%20Database/02.%20Joins/1581.%20Customer%20Who%20Visited%20but%20Did%20Not%20Make%20Any%20Transactions/1581.%20Customer%20Who%20Visited%20but%20Did%20Not%20Make%20Any%20Transactions.md) |
| 11 | [1251. Average Selling Price](https://leetcode.com/problems/average-selling-price/) | Easy | 6+ months | 13.8 | ✅ Solved |  |  |  | [notes](24.%20SQL%20%26%20Database/02.%20Joins/1251.%20Average%20Selling%20Price/1251.%20Average%20Selling%20Price.md) |
| 12 | [1378. Replace Employee ID With The Unique Identifier](https://leetcode.com/problems/replace-employee-id-with-the-unique-identifier/) | Easy | 6+ months | 10.2 | ✅ Solved |  |  |  | [notes](24.%20SQL%20%26%20Database/02.%20Joins/1378.%20Replace%20Employee%20ID%20With%20The%20Unique%20Identifier/1378.%20Replace%20Employee%20ID%20With%20The%20Unique%20Identifier.md) |
| 13 | [1934. Confirmation Rate](https://leetcode.com/problems/confirmation-rate/) | Medium | 6+ months | 8.7 | Todo |  |  |  | [notes](24.%20SQL%20%26%20Database/02.%20Joins/1934.%20Confirmation%20Rate/1934.%20Confirmation%20Rate.md) |
| 14 | [1068. Product Sales Analysis I](https://leetcode.com/problems/product-sales-analysis-i/) | Easy | 6+ months | 6.6 | ✅ Solved |  |  |  | [notes](24.%20SQL%20%26%20Database/02.%20Joins/1068.%20Product%20Sales%20Analysis%20I/1068.%20Product%20Sales%20Analysis%20I.md) |
| 15 | [3570. Find Books with No Available Copies](https://leetcode.com/problems/find-books-with-no-available-copies/) | Easy | 6+ months | 6.3 | Todo |  |  |  | [notes](24.%20SQL%20%26%20Database/02.%20Joins/3570.%20Find%20Books%20with%20No%20Available%20Copies/3570.%20Find%20Books%20with%20No%20Available%20Copies.md) |
| 16 | [612. Shortest Distance in a Plane](https://leetcode.com/problems/shortest-distance-in-a-plane/) 🔒 | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](24.%20SQL%20%26%20Database/02.%20Joins/0612.%20Shortest%20Distance%20in%20a%20Plane/0612.%20Shortest%20Distance%20in%20a%20Plane.md) |
| 17 | [1731. The Number of Employees Which Report to Each Employee](https://leetcode.com/problems/the-number-of-employees-which-report-to-each-employee/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](24.%20SQL%20%26%20Database/02.%20Joins/1731.%20The%20Number%20of%20Employees%20Which%20Report%20to%20Each%20Employee/1731.%20The%20Number%20of%20Employees%20Which%20Report%20to%20Each%20Employee.md) |
| 18 | [1241. Number of Comments per Post](https://leetcode.com/problems/number-of-comments-per-post/) 🔒 | Easy | 6+ months | 36.1 | Todo |  |  |  | [notes](24.%20SQL%20%26%20Database/02.%20Joins/1241.%20Number%20of%20Comments%20per%20Post/1241.%20Number%20of%20Comments%20per%20Post.md) |
| 19 | [1951. All the Pairs With the Maximum Number of Common Followers](https://leetcode.com/problems/all-the-pairs-with-the-maximum-number-of-common-followers/) 🔒 | Medium | 6+ months | 36.1 | Todo |  |  |  | [notes](24.%20SQL%20%26%20Database/02.%20Joins/1951.%20All%20the%20Pairs%20With%20the%20Maximum%20Number%20of%20Common%20Followers/1951.%20All%20the%20Pairs%20With%20the%20Maximum%20Number%20of%20Common%20Followers.md) |
| 20 | [2199. Finding the Topic of Each Post](https://leetcode.com/problems/finding-the-topic-of-each-post/) 🔒 | Hard | 6+ months | 36.1 | Todo |  |  |  | [notes](24.%20SQL%20%26%20Database/02.%20Joins/2199.%20Finding%20the%20Topic%20of%20Each%20Post/2199.%20Finding%20the%20Topic%20of%20Each%20Post.md) |

### 24.03. Aggregation & Group By

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [1193. Monthly Transactions I](https://leetcode.com/problems/monthly-transactions-i/) | Medium | 6 months | 23.8 | ✅ Solved |  |  |  | [notes](24.%20SQL%20%26%20Database/03.%20Aggregation%20%26%20Group%20By/1193.%20Monthly%20Transactions%20I/1193.%20Monthly%20Transactions%20I.md) |
| 2 | [1045. Customers Who Bought All Products](https://leetcode.com/problems/customers-who-bought-all-products/) | Medium | 6 months | 21.9 | ✅ Solved |  |  |  | [notes](24.%20SQL%20%26%20Database/03.%20Aggregation%20%26%20Group%20By/1045.%20Customers%20Who%20Bought%20All%20Products/1045.%20Customers%20Who%20Bought%20All%20Products.md) |
| 3 | [511. Game Play Analysis I](https://leetcode.com/problems/game-play-analysis-i/) | Easy | 6 months | 8.5 | ✅ Solved |  |  |  | [notes](24.%20SQL%20%26%20Database/03.%20Aggregation%20%26%20Group%20By/0511.%20Game%20Play%20Analysis%20I/0511.%20Game%20Play%20Analysis%20I.md) |
| 4 | [602. Friend Requests II: Who Has the Most Friends](https://leetcode.com/problems/friend-requests-ii-who-has-the-most-friends/) | Medium | 6+ months | 42.1 | ✅ Solved |  |  |  | [notes](24.%20SQL%20%26%20Database/03.%20Aggregation%20%26%20Group%20By/0602.%20Friend%20Requests%20II-%20Who%20Has%20the%20Most%20Friends/0602.%20Friend%20Requests%20II-%20Who%20Has%20the%20Most%20Friends.md) |
| 5 | [1211. Queries Quality and Percentage](https://leetcode.com/problems/queries-quality-and-percentage/) | Easy | 6+ months | 38.5 | ✅ Solved |  |  |  | [notes](24.%20SQL%20%26%20Database/03.%20Aggregation%20%26%20Group%20By/1211.%20Queries%20Quality%20and%20Percentage/1211.%20Queries%20Quality%20and%20Percentage.md) |
| 6 | [1075. Project Employees I](https://leetcode.com/problems/project-employees-i/) | Easy | 6+ months | 38.3 | ✅ Solved |  |  |  | [notes](24.%20SQL%20%26%20Database/03.%20Aggregation%20%26%20Group%20By/1075.%20Project%20Employees%20I/1075.%20Project%20Employees%20I.md) |
| 7 | [570. Managers with at Least 5 Direct Reports](https://leetcode.com/problems/managers-with-at-least-5-direct-reports/) | Medium | 6+ months | 17.0 | ✅ Solved |  |  |  | [notes](24.%20SQL%20%26%20Database/03.%20Aggregation%20%26%20Group%20By/0570.%20Managers%20with%20at%20Least%205%20Direct%20Reports/0570.%20Managers%20with%20at%20Least%205%20Direct%20Reports.md) |
| 8 | [1341. Movie Rating](https://leetcode.com/problems/movie-rating/) | Medium | 6+ months | 15.9 | Todo |  |  |  | [notes](24.%20SQL%20%26%20Database/03.%20Aggregation%20%26%20Group%20By/1341.%20Movie%20Rating/1341.%20Movie%20Rating.md) |
| 9 | [182. Duplicate Emails](https://leetcode.com/problems/duplicate-emails/) | Easy | 6+ months | 11.6 | ✅ Solved |  |  |  | [notes](24.%20SQL%20%26%20Database/03.%20Aggregation%20%26%20Group%20By/0182.%20Duplicate%20Emails/0182.%20Duplicate%20Emails.md) |
| 10 | [1633. Percentage of Users Attended a Contest](https://leetcode.com/problems/percentage-of-users-attended-a-contest/) | Easy | 6+ months | 10.1 | ✅ Solved |  |  |  | [notes](24.%20SQL%20%26%20Database/03.%20Aggregation%20%26%20Group%20By/1633.%20Percentage%20of%20Users%20Attended%20a%20Contest/1633.%20Percentage%20of%20Users%20Attended%20a%20Contest.md) |
| 11 | [1484. Group Sold Products By The Date](https://leetcode.com/problems/group-sold-products-by-the-date/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](24.%20SQL%20%26%20Database/03.%20Aggregation%20%26%20Group%20By/1484.%20Group%20Sold%20Products%20By%20The%20Date/1484.%20Group%20Sold%20Products%20By%20The%20Date.md) |
| 12 | [578. Get Highest Answer Rate Question](https://leetcode.com/problems/get-highest-answer-rate-question/) 🔒 | Medium | 6+ months | 36.7 | Todo |  |  |  | [notes](24.%20SQL%20%26%20Database/03.%20Aggregation%20%26%20Group%20By/0578.%20Get%20Highest%20Answer%20Rate%20Question/0578.%20Get%20Highest%20Answer%20Rate%20Question.md) |
| 13 | [1113. Reported Posts](https://leetcode.com/problems/reported-posts/) 🔒 | Easy | 6+ months | 36.1 | Todo |  |  |  | [notes](24.%20SQL%20%26%20Database/03.%20Aggregation%20%26%20Group%20By/1113.%20Reported%20Posts/1113.%20Reported%20Posts.md) |
| 14 | [596. Classes With at Least 5 Students](https://leetcode.com/problems/classes-with-at-least-5-students/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](24.%20SQL%20%26%20Database/03.%20Aggregation%20%26%20Group%20By/0596.%20Classes%20With%20at%20Least%205%20Students/0596.%20Classes%20With%20at%20Least%205%20Students.md) |
| 15 | [2356. Number of Unique Subjects Taught by Each Teacher](https://leetcode.com/problems/number-of-unique-subjects-taught-by-each-teacher/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](24.%20SQL%20%26%20Database/03.%20Aggregation%20%26%20Group%20By/2356.%20Number%20of%20Unique%20Subjects%20Taught%20by%20Each%20Teacher/2356.%20Number%20of%20Unique%20Subjects%20Taught%20by%20Each%20Teacher.md) |

### 24.04. Subqueries & CTE

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [183. Customers Who Never Order](https://leetcode.com/problems/customers-who-never-order/) | Easy | 6 months | 21.9 | ✅ Solved |  |  |  | [notes](24.%20SQL%20%26%20Database/04.%20Subqueries%20%26%20CTE/0183.%20Customers%20Who%20Never%20Order/0183.%20Customers%20Who%20Never%20Order.md) |
| 2 | [176. Second Highest Salary](https://leetcode.com/problems/second-highest-salary/) | Medium | 6 months | 20.1 | ✅ Solved |  |  |  | [notes](24.%20SQL%20%26%20Database/04.%20Subqueries%20%26%20CTE/0176.%20Second%20Highest%20Salary/0176.%20Second%20Highest%20Salary.md) |
| 3 | [184. Department Highest Salary](https://leetcode.com/problems/department-highest-salary/) | Medium | 6 months | 13.5 | Todo |  |  |  | [notes](24.%20SQL%20%26%20Database/04.%20Subqueries%20%26%20CTE/0184.%20Department%20Highest%20Salary/0184.%20Department%20Highest%20Salary.md) |
| 4 | [585. Investments in 2016](https://leetcode.com/problems/investments-in-2016/) | Medium | 6 months | 12.9 | ✅ Solved |  |  |  | [notes](24.%20SQL%20%26%20Database/04.%20Subqueries%20%26%20CTE/0585.%20Investments%20in%202016/0585.%20Investments%20in%202016.md) |
| 5 | [597. Friend Requests I: Overall Acceptance Rate](https://leetcode.com/problems/friend-requests-i-overall-acceptance-rate/) 🔒 | Easy | 6+ months | 37.8 | Todo |  |  |  | [notes](24.%20SQL%20%26%20Database/04.%20Subqueries%20%26%20CTE/0597.%20Friend%20Requests%20I-%20Overall%20Acceptance%20Rate/0597.%20Friend%20Requests%20I-%20Overall%20Acceptance%20Rate.md) |
| 6 | [550. Game Play Analysis IV](https://leetcode.com/problems/game-play-analysis-iv/) | Medium | 6+ months | 15.1 | Todo |  |  |  | [notes](24.%20SQL%20%26%20Database/04.%20Subqueries%20%26%20CTE/0550.%20Game%20Play%20Analysis%20IV/0550.%20Game%20Play%20Analysis%20IV.md) |
| 7 | [607. Sales Person](https://leetcode.com/problems/sales-person/) | Easy | 6+ months | 12.7 | ✅ Solved |  |  |  | [notes](24.%20SQL%20%26%20Database/04.%20Subqueries%20%26%20CTE/0607.%20Sales%20Person/0607.%20Sales%20Person.md) |
| 8 | [1174. Immediate Food Delivery II](https://leetcode.com/problems/immediate-food-delivery-ii/) | Medium | 6+ months | 11.3 | Todo |  |  |  | [notes](24.%20SQL%20%26%20Database/04.%20Subqueries%20%26%20CTE/1174.%20Immediate%20Food%20Delivery%20II/1174.%20Immediate%20Food%20Delivery%20II.md) |
| 9 | [1070. Product Sales Analysis III](https://leetcode.com/problems/product-sales-analysis-iii/) | Medium | 6+ months | 9.9 | Todo |  |  |  | [notes](24.%20SQL%20%26%20Database/04.%20Subqueries%20%26%20CTE/1070.%20Product%20Sales%20Analysis%20III/1070.%20Product%20Sales%20Analysis%20III.md) |
| 10 | [177. Nth Highest Salary](https://leetcode.com/problems/nth-highest-salary/) | Medium | 6+ months | 7.6 | Todo |  |  |  | [notes](24.%20SQL%20%26%20Database/04.%20Subqueries%20%26%20CTE/0177.%20Nth%20Highest%20Salary/0177.%20Nth%20Highest%20Salary.md) |
| 11 | [1164. Product Price at a Given Date](https://leetcode.com/problems/product-price-at-a-given-date/) | Medium | 6+ months | 7.1 | Todo |  |  |  | [notes](24.%20SQL%20%26%20Database/04.%20Subqueries%20%26%20CTE/1164.%20Product%20Price%20at%20a%20Given%20Date/1164.%20Product%20Price%20at%20a%20Given%20Date.md) |
| 12 | [1789. Primary Department for Each Employee](https://leetcode.com/problems/primary-department-for-each-employee/) | Easy | 6+ months | 6.4 | Todo |  |  |  | [notes](24.%20SQL%20%26%20Database/04.%20Subqueries%20%26%20CTE/1789.%20Primary%20Department%20for%20Each%20Employee/1789.%20Primary%20Department%20for%20Each%20Employee.md) |
| 13 | [1098. Unpopular Books](https://leetcode.com/problems/unpopular-books/) 🔒 | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](24.%20SQL%20%26%20Database/04.%20Subqueries%20%26%20CTE/1098.%20Unpopular%20Books/1098.%20Unpopular%20Books.md) |
| 14 | [1132. Reported Posts II](https://leetcode.com/problems/reported-posts-ii/) 🔒 | Medium | 6+ months | 36.7 | Todo |  |  |  | [notes](24.%20SQL%20%26%20Database/04.%20Subqueries%20%26%20CTE/1132.%20Reported%20Posts%20II/1132.%20Reported%20Posts%20II.md) |
| 15 | [1076. Project Employees II](https://leetcode.com/problems/project-employees-ii/) 🔒 | Easy | 6+ months | 36.1 | Todo |  |  |  | [notes](24.%20SQL%20%26%20Database/04.%20Subqueries%20%26%20CTE/1076.%20Project%20Employees%20II/1076.%20Project%20Employees%20II.md) |
| 16 | [1142. User Activity for the Past 30 Days II](https://leetcode.com/problems/user-activity-for-the-past-30-days-ii/) 🔒 | Easy | 6+ months | 36.1 | Todo |  |  |  | [notes](24.%20SQL%20%26%20Database/04.%20Subqueries%20%26%20CTE/1142.%20User%20Activity%20for%20the%20Past%2030%20Days%20II/1142.%20User%20Activity%20for%20the%20Past%2030%20Days%20II.md) |

### 24.05. Window Functions

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [180. Consecutive Numbers](https://leetcode.com/problems/consecutive-numbers/) | Medium | 3 months | 21.6 | Todo |  |  |  | [notes](24.%20SQL%20%26%20Database/05.%20Window%20Functions/0180.%20Consecutive%20Numbers/0180.%20Consecutive%20Numbers.md) |
| 2 | [1321. Restaurant Growth](https://leetcode.com/problems/restaurant-growth/) | Medium | 6 months | 7.6 | Todo |  |  |  | [notes](24.%20SQL%20%26%20Database/05.%20Window%20Functions/1321.%20Restaurant%20Growth/1321.%20Restaurant%20Growth.md) |
| 3 | [185. Department Top Three Salaries](https://leetcode.com/problems/department-top-three-salaries/) | Hard | 6 months | 5.4 | Todo |  |  |  | [notes](24.%20SQL%20%26%20Database/05.%20Window%20Functions/0185.%20Department%20Top%20Three%20Salaries/0185.%20Department%20Top%20Three%20Salaries.md) |
| 4 | [178. Rank Scores](https://leetcode.com/problems/rank-scores/) | Medium | 6+ months | 11.9 | Todo |  |  |  | [notes](24.%20SQL%20%26%20Database/05.%20Window%20Functions/0178.%20Rank%20Scores/0178.%20Rank%20Scores.md) |
| 5 | [1204. Last Person to Fit in the Bus](https://leetcode.com/problems/last-person-to-fit-in-the-bus/) | Medium | 6+ months | 9.0 | Todo |  |  |  | [notes](24.%20SQL%20%26%20Database/05.%20Window%20Functions/1204.%20Last%20Person%20to%20Fit%20in%20the%20Bus/1204.%20Last%20Person%20to%20Fit%20in%20the%20Bus.md) |
| 6 | [601. Human Traffic of Stadium](https://leetcode.com/problems/human-traffic-of-stadium/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](24.%20SQL%20%26%20Database/05.%20Window%20Functions/0601.%20Human%20Traffic%20of%20Stadium/0601.%20Human%20Traffic%20of%20Stadium.md) |
| 7 | [1077. Project Employees III](https://leetcode.com/problems/project-employees-iii/) 🔒 | Medium | 6+ months | 36.1 | Todo |  |  |  | [notes](24.%20SQL%20%26%20Database/05.%20Window%20Functions/1077.%20Project%20Employees%20III/1077.%20Project%20Employees%20III.md) |
| 8 | [1225. Report Contiguous Dates](https://leetcode.com/problems/report-contiguous-dates/) 🔒 | Hard | 6+ months | 36.1 | Todo |  |  |  | [notes](24.%20SQL%20%26%20Database/05.%20Window%20Functions/1225.%20Report%20Contiguous%20Dates/1225.%20Report%20Contiguous%20Dates.md) |

### 24.06. Date & String Functions

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [1141. User Activity for the Past 30 Days I](https://leetcode.com/problems/user-activity-for-the-past-30-days-i/) | Easy | 6+ months | 37.9 | ✅ Solved |  |  |  | [notes](24.%20SQL%20%26%20Database/06.%20Date%20%26%20String%20Functions/1141.%20User%20Activity%20for%20the%20Past%2030%20Days%20I/1141.%20User%20Activity%20for%20the%20Past%2030%20Days%20I.md) |
| 2 | [1527. Patients With a Condition](https://leetcode.com/problems/patients-with-a-condition/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](24.%20SQL%20%26%20Database/06.%20Date%20%26%20String%20Functions/1527.%20Patients%20With%20a%20Condition/1527.%20Patients%20With%20a%20Condition.md) |
| 3 | [1667. Fix Names in a Table](https://leetcode.com/problems/fix-names-in-a-table/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](24.%20SQL%20%26%20Database/06.%20Date%20%26%20String%20Functions/1667.%20Fix%20Names%20in%20a%20Table/1667.%20Fix%20Names%20in%20a%20Table.md) |
| 4 | [3475. DNA Pattern Recognition ](https://leetcode.com/problems/dna-pattern-recognition/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](24.%20SQL%20%26%20Database/06.%20Date%20%26%20String%20Functions/3475.%20DNA%20Pattern%20Recognition%20/3475.%20DNA%20Pattern%20Recognition%20.md) |

### 24.07. Conditional Logic (CASE)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [610. Triangle Judgement](https://leetcode.com/problems/triangle-judgement/) | Easy | 6 months | 16.7 | ✅ Solved |  |  |  | [notes](24.%20SQL%20%26%20Database/07.%20Conditional%20Logic%20%28CASE%29/0610.%20Triangle%20Judgement/0610.%20Triangle%20Judgement.md) |
| 2 | [626. Exchange Seats](https://leetcode.com/problems/exchange-seats/) | Medium | 6+ months | 7.2 | Todo |  |  |  | [notes](24.%20SQL%20%26%20Database/07.%20Conditional%20Logic%20%28CASE%29/0626.%20Exchange%20Seats/0626.%20Exchange%20Seats.md) |
| 3 | [608. Tree Node](https://leetcode.com/problems/tree-node/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](24.%20SQL%20%26%20Database/07.%20Conditional%20Logic%20%28CASE%29/0608.%20Tree%20Node/0608.%20Tree%20Node.md) |
| 4 | [627. Swap Sex of Employees](https://leetcode.com/problems/swap-sex-of-employees/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](24.%20SQL%20%26%20Database/07.%20Conditional%20Logic%20%28CASE%29/0627.%20Swap%20Sex%20of%20Employees/0627.%20Swap%20Sex%20of%20Employees.md) |
| 5 | [1179. Reformat Department Table](https://leetcode.com/problems/reformat-department-table/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](24.%20SQL%20%26%20Database/07.%20Conditional%20Logic%20%28CASE%29/1179.%20Reformat%20Department%20Table/1179.%20Reformat%20Department%20Table.md) |
| 6 | [1393. Capital Gain/Loss](https://leetcode.com/problems/capital-gainloss/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](24.%20SQL%20%26%20Database/07.%20Conditional%20Logic%20%28CASE%29/1393.%20Capital%20Gain-Loss/1393.%20Capital%20Gain-Loss.md) |
| 7 | [1873. Calculate Special Bonus](https://leetcode.com/problems/calculate-special-bonus/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](24.%20SQL%20%26%20Database/07.%20Conditional%20Logic%20%28CASE%29/1873.%20Calculate%20Special%20Bonus/1873.%20Calculate%20Special%20Bonus.md) |
| 8 | [1322. Ads Performance](https://leetcode.com/problems/ads-performance/) 🔒 | Easy | 6+ months | 36.1 | Todo |  |  |  | [notes](24.%20SQL%20%26%20Database/07.%20Conditional%20Logic%20%28CASE%29/1322.%20Ads%20Performance/1322.%20Ads%20Performance.md) |
| 9 | [1398. Customers Who Bought Products A and B but Not C](https://leetcode.com/problems/customers-who-bought-products-a-and-b-but-not-c/) 🔒 | Medium | 6+ months | 36.1 | Todo |  |  |  | [notes](24.%20SQL%20%26%20Database/07.%20Conditional%20Logic%20%28CASE%29/1398.%20Customers%20Who%20Bought%20Products%20A%20and%20B%20but%20Not%20C/1398.%20Customers%20Who%20Bought%20Products%20A%20and%20B%20but%20Not%20C.md) |
| 10 | [1445. Apples & Oranges](https://leetcode.com/problems/apples-oranges/) 🔒 | Medium | 6+ months | 36.1 | Todo |  |  |  | [notes](24.%20SQL%20%26%20Database/07.%20Conditional%20Logic%20%28CASE%29/1445.%20Apples%20%26%20Oranges/1445.%20Apples%20%26%20Oranges.md) |

## 25. Shell & Concurrency

5 problems: 2 Easy, 3 Medium, 0 Hard. [Open chapter README](25.%20Shell%20%26%20Concurrency/README.md) · [Back to top](#chapters)

### 25.01. Shell Scripting

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [193. Valid Phone Numbers](https://leetcode.com/problems/valid-phone-numbers/) | Easy | 3 months | 5.0 | Todo |  |  |  | [notes](25.%20Shell%20%26%20Concurrency/01.%20Shell%20Scripting/0193.%20Valid%20Phone%20Numbers/0193.%20Valid%20Phone%20Numbers.md) |
| 2 | [195. Tenth Line](https://leetcode.com/problems/tenth-line/) | Easy | 6+ months | 11.6 | Todo |  |  |  | [notes](25.%20Shell%20%26%20Concurrency/01.%20Shell%20Scripting/0195.%20Tenth%20Line/0195.%20Tenth%20Line.md) |
| 3 | [192. Word Frequency](https://leetcode.com/problems/word-frequency/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](25.%20Shell%20%26%20Concurrency/01.%20Shell%20Scripting/0192.%20Word%20Frequency/0192.%20Word%20Frequency.md) |
| 4 | [194. Transpose File](https://leetcode.com/problems/transpose-file/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](25.%20Shell%20%26%20Concurrency/01.%20Shell%20Scripting/0194.%20Transpose%20File/0194.%20Transpose%20File.md) |

### 25.02. Concurrency

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [1242. Web Crawler Multithreaded](https://leetcode.com/problems/web-crawler-multithreaded/) 🔒 | Medium | 6+ months | 37.2 | Todo |  |  |  | [notes](25.%20Shell%20%26%20Concurrency/02.%20Concurrency/1242.%20Web%20Crawler%20Multithreaded/1242.%20Web%20Crawler%20Multithreaded.md) |
