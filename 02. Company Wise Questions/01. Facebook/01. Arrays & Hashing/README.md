# 01. Arrays & Hashing

[Back to Facebook](../README.md) · [Back to DSA Notes](../../../README.md)

117 Meta (Facebook) problems: 75 Easy, 41 Medium, 1 Hard, in 9 sub-patterns.

## Sub-patterns

| # | Sub-pattern | Questions | Easy | Medium | Hard | Last 3 Months | Solved | Most Asked |
|:---:|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---|
| 01 | [Array Traversal & Basics](#01-array-traversal--basics) | 32 | 29 | 3 | 0 | 3 | 15 | 121. Best Time to Buy and Sell Stock, 163. Missing Ranges, 896. Monotonic Array |
| 02 | [In-Place Array Manipulation](#02-in-place-array-manipulation) | 4 | 1 | 3 | 0 | 1 | 3 | 31. Next Permutation, 189. Rotate Array, 1920. Build Array from Permutation |
| 03 | [Hash Map Lookup](#03-hash-map-lookup) | 12 | 4 | 8 | 0 | 2 | 5 | 1. Two Sum, 2365. Task Scheduler II, 205. Isomorphic Strings |
| 04 | [Hash Set & Duplicates](#04-hash-set--duplicates) | 21 | 18 | 3 | 0 | 4 | 8 | 128. Longest Consecutive Sequence, 217. Contains Duplicate, 349. Intersection of Two Arrays |
| 05 | [Frequency Counting](#05-frequency-counting) | 33 | 20 | 13 | 0 | 2 | 10 | 825. Friends Of Appropriate Ages, 1748. Sum of Unique Elements, 554. Brick Wall |
| 06 | [Grouping by Key](#06-grouping-by-key) | 4 | 0 | 4 | 0 | 2 | 1 | 49. Group Anagrams, 249. Group Shifted Strings, 893. Groups of Special-Equivalent Strings |
| 07 | [Kadane's Algorithm](#07-kadanes-algorithm) | 4 | 0 | 4 | 0 | 0 | 2 | 53. Maximum Subarray, 152. Maximum Product Subarray, 918. Maximum Sum Circular Subarray |
| 08 | [Cyclic Sort & Index Marking](#08-cyclic-sort--index-marking) | 5 | 2 | 2 | 1 | 0 | 3 | 41. First Missing Positive, 645. Set Mismatch, 442. Find All Duplicates in an Array |
| 09 | [Majority Element (Boyer-Moore)](#09-majority-element-boyer-moore) | 2 | 1 | 1 | 0 | 0 | 2 | 169. Majority Element, 229. Majority Element II |

**Columns**

- **Last Asked**: most recent LeetCode window that lists the problem for Meta (30 days, 3 months, 6 months or 6+ months).
- **Frequency**: LeetCode frequency score (0-100) in the Meta "All" list.
- **Status**: your LeetCode status on the day this file was generated. 🔒 after a title means LeetCode Premium.
- **Logic / Key Idea, Time, Space**: fill these in as you solve. A rebuild keeps what you typed.
- **Notes**: link to the problem's notes file.

Inside each sub-pattern, rows are sorted by most recent window, then by frequency (highest first).

## 01. Array Traversal & Basics

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [3105. Longest Strictly Increasing or Strictly Decreasing Subarray](https://leetcode.com/problems/longest-strictly-increasing-or-strictly-decreasing-subarray/) | Easy | 30 days | 17.0 | ✅ Solved |  |  |  | [notes](01.%20Array%20Traversal%20%26%20Basics/3105.%20Longest%20Strictly%20Increasing%20or%20Strictly%20Decreasing%20Subarray/3105.%20Longest%20Strictly%20Increasing%20or%20Strictly%20Decreasing%20Subarray.md) |
| 2 | [121. Best Time to Buy and Sell Stock](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/) | Easy | 3 months | 84.6 | ✅ Solved |  |  |  | [notes](01.%20Array%20Traversal%20%26%20Basics/0121.%20Best%20Time%20to%20Buy%20and%20Sell%20Stock/0121.%20Best%20Time%20to%20Buy%20and%20Sell%20Stock.md) |
| 3 | [1752. Check if Array Is Sorted and Rotated](https://leetcode.com/problems/check-if-array-is-sorted-and-rotated/) | Easy | 3 months | 32.1 | ✅ Solved |  |  |  | [notes](01.%20Array%20Traversal%20%26%20Basics/1752.%20Check%20if%20Array%20Is%20Sorted%20and%20Rotated/1752.%20Check%20if%20Array%20Is%20Sorted%20and%20Rotated.md) |
| 4 | [1929. Concatenation of Array](https://leetcode.com/problems/concatenation-of-array/) | Easy | 6 months | 33.8 | ✅ Solved |  |  |  | [notes](01.%20Array%20Traversal%20%26%20Basics/1929.%20Concatenation%20of%20Array/1929.%20Concatenation%20of%20Array.md) |
| 5 | [485. Max Consecutive Ones](https://leetcode.com/problems/max-consecutive-ones/) | Easy | 6 months | 31.2 | ✅ Solved |  |  |  | [notes](01.%20Array%20Traversal%20%26%20Basics/0485.%20Max%20Consecutive%20Ones/0485.%20Max%20Consecutive%20Ones.md) |
| 6 | [1431. Kids With the Greatest Number of Candies](https://leetcode.com/problems/kids-with-the-greatest-number-of-candies/) | Easy | 6 months | 19.8 | ✅ Solved |  |  |  | [notes](01.%20Array%20Traversal%20%26%20Basics/1431.%20Kids%20With%20the%20Greatest%20Number%20of%20Candies/1431.%20Kids%20With%20the%20Greatest%20Number%20of%20Candies.md) |
| 7 | [1470. Shuffle the Array](https://leetcode.com/problems/shuffle-the-array/) | Easy | 6 months | 13.5 | ✅ Solved |  |  |  | [notes](01.%20Array%20Traversal%20%26%20Basics/1470.%20Shuffle%20the%20Array/1470.%20Shuffle%20the%20Array.md) |
| 8 | [163. Missing Ranges](https://leetcode.com/problems/missing-ranges/) 🔒 | Easy | 6+ months | 43.4 | Todo |  |  |  | [notes](01.%20Array%20Traversal%20%26%20Basics/0163.%20Missing%20Ranges/0163.%20Missing%20Ranges.md) |
| 9 | [896. Monotonic Array](https://leetcode.com/problems/monotonic-array/) | Easy | 6+ months | 42.0 | ✅ Solved |  |  |  | [notes](01.%20Array%20Traversal%20%26%20Basics/0896.%20Monotonic%20Array/0896.%20Monotonic%20Array.md) |
| 10 | [674. Longest Continuous Increasing Subsequence](https://leetcode.com/problems/longest-continuous-increasing-subsequence/) | Easy | 6+ months | 38.5 | ✅ Solved |  |  |  | [notes](01.%20Array%20Traversal%20%26%20Basics/0674.%20Longest%20Continuous%20Increasing%20Subsequence/0674.%20Longest%20Continuous%20Increasing%20Subsequence.md) |
| 11 | [2210. Count Hills and Valleys in an Array](https://leetcode.com/problems/count-hills-and-valleys-in-an-array/) | Easy | 6+ months | 38.4 | Todo |  |  |  | [notes](01.%20Array%20Traversal%20%26%20Basics/2210.%20Count%20Hills%20and%20Valleys%20in%20an%20Array/2210.%20Count%20Hills%20and%20Valleys%20in%20an%20Array.md) |
| 12 | [1287. Element Appearing More Than 25% In Sorted Array](https://leetcode.com/problems/element-appearing-more-than-25-in-sorted-array/) | Easy | 6+ months | 17.2 | Todo |  |  |  | [notes](01.%20Array%20Traversal%20%26%20Basics/1287.%20Element%20Appearing%20More%20Than%2025%25%20In%20Sorted%20Array/1287.%20Element%20Appearing%20More%20Than%2025%25%20In%20Sorted%20Array.md) |
| 13 | [2016. Maximum Difference Between Increasing Elements](https://leetcode.com/problems/maximum-difference-between-increasing-elements/) | Easy | 6+ months | 12.4 | Todo |  |  |  | [notes](01.%20Array%20Traversal%20%26%20Basics/2016.%20Maximum%20Difference%20Between%20Increasing%20Elements/2016.%20Maximum%20Difference%20Between%20Increasing%20Elements.md) |
| 14 | [1464. Maximum Product of Two Elements in an Array](https://leetcode.com/problems/maximum-product-of-two-elements-in-an-array/) | Easy | 6+ months | 9.4 | ✅ Solved |  |  |  | [notes](01.%20Array%20Traversal%20%26%20Basics/1464.%20Maximum%20Product%20of%20Two%20Elements%20in%20an%20Array/1464.%20Maximum%20Product%20of%20Two%20Elements%20in%20an%20Array.md) |
| 15 | [941. Valid Mountain Array](https://leetcode.com/problems/valid-mountain-array/) | Easy | 6+ months | 8.5 | Todo |  |  |  | [notes](01.%20Array%20Traversal%20%26%20Basics/0941.%20Valid%20Mountain%20Array/0941.%20Valid%20Mountain%20Array.md) |
| 16 | [228. Summary Ranges](https://leetcode.com/problems/summary-ranges/) | Easy | 6+ months | 7.6 | Todo |  |  |  | [notes](01.%20Array%20Traversal%20%26%20Basics/0228.%20Summary%20Ranges/0228.%20Summary%20Ranges.md) |
| 17 | [414. Third Maximum Number](https://leetcode.com/problems/third-maximum-number/) | Easy | 6+ months | 6.9 | Todo |  |  |  | [notes](01.%20Array%20Traversal%20%26%20Basics/0414.%20Third%20Maximum%20Number/0414.%20Third%20Maximum%20Number.md) |
| 18 | [2348. Number of Zero-Filled Subarrays](https://leetcode.com/problems/number-of-zero-filled-subarrays/) | Medium | 6+ months | 6.8 | Todo |  |  |  | [notes](01.%20Array%20Traversal%20%26%20Basics/2348.%20Number%20of%20Zero-Filled%20Subarrays/2348.%20Number%20of%20Zero-Filled%20Subarrays.md) |
| 19 | [1014. Best Sightseeing Pair](https://leetcode.com/problems/best-sightseeing-pair/) | Medium | 6+ months | 6.6 | Todo |  |  |  | [notes](01.%20Array%20Traversal%20%26%20Basics/1014.%20Best%20Sightseeing%20Pair/1014.%20Best%20Sightseeing%20Pair.md) |
| 20 | [1550. Three Consecutive Odds](https://leetcode.com/problems/three-consecutive-odds/) | Easy | 6+ months | 6.0 | ✅ Solved |  |  |  | [notes](01.%20Array%20Traversal%20%26%20Basics/1550.%20Three%20Consecutive%20Odds/1550.%20Three%20Consecutive%20Odds.md) |
| 21 | [2672. Number of Adjacent Elements With the Same Color](https://leetcode.com/problems/number-of-adjacent-elements-with-the-same-color/) | Medium | 6+ months | 5.4 | Todo |  |  |  | [notes](01.%20Array%20Traversal%20%26%20Basics/2672.%20Number%20of%20Adjacent%20Elements%20With%20the%20Same%20Color/2672.%20Number%20of%20Adjacent%20Elements%20With%20the%20Same%20Color.md) |
| 22 | [1299. Replace Elements with Greatest Element on Right Side](https://leetcode.com/problems/replace-elements-with-greatest-element-on-right-side/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Array%20Traversal%20%26%20Basics/1299.%20Replace%20Elements%20with%20Greatest%20Element%20on%20Right%20Side/1299.%20Replace%20Elements%20with%20Greatest%20Element%20on%20Right%20Side.md) |
| 23 | [1437. Check If All 1's Are at Least Length K Places Away](https://leetcode.com/problems/check-if-all-1s-are-at-least-length-k-places-away/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Array%20Traversal%20%26%20Basics/1437.%20Check%20If%20All%201%27s%20Are%20at%20Least%20Length%20K%20Places%20Away/1437.%20Check%20If%20All%201%27s%20Are%20at%20Least%20Length%20K%20Places%20Away.md) |
| 24 | [1534. Count Good Triplets](https://leetcode.com/problems/count-good-triplets/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Array%20Traversal%20%26%20Basics/1534.%20Count%20Good%20Triplets/1534.%20Count%20Good%20Triplets.md) |
| 25 | [1800. Maximum Ascending Subarray Sum](https://leetcode.com/problems/maximum-ascending-subarray-sum/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](01.%20Array%20Traversal%20%26%20Basics/1800.%20Maximum%20Ascending%20Subarray%20Sum/1800.%20Maximum%20Ascending%20Subarray%20Sum.md) |
| 26 | [2176. Count Equal and Divisible Pairs in an Array](https://leetcode.com/problems/count-equal-and-divisible-pairs-in-an-array/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](01.%20Array%20Traversal%20%26%20Basics/2176.%20Count%20Equal%20and%20Divisible%20Pairs%20in%20an%20Array/2176.%20Count%20Equal%20and%20Divisible%20Pairs%20in%20an%20Array.md) |
| 27 | [2239. Find Closest Number to Zero](https://leetcode.com/problems/find-closest-number-to-zero/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Array%20Traversal%20%26%20Basics/2239.%20Find%20Closest%20Number%20to%20Zero/2239.%20Find%20Closest%20Number%20to%20Zero.md) |
| 28 | [2951. Find the Peaks](https://leetcode.com/problems/find-the-peaks/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](01.%20Array%20Traversal%20%26%20Basics/2951.%20Find%20the%20Peaks/2951.%20Find%20the%20Peaks.md) |
| 29 | [3000. Maximum Area of Longest Diagonal Rectangle](https://leetcode.com/problems/maximum-area-of-longest-diagonal-rectangle/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Array%20Traversal%20%26%20Basics/3000.%20Maximum%20Area%20of%20Longest%20Diagonal%20Rectangle/3000.%20Maximum%20Area%20of%20Longest%20Diagonal%20Rectangle.md) |
| 30 | [3151. Special Array I](https://leetcode.com/problems/special-array-i/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](01.%20Array%20Traversal%20%26%20Basics/3151.%20Special%20Array%20I/3151.%20Special%20Array%20I.md) |
| 31 | [3423. Maximum Difference Between Adjacent Elements in a Circular Array](https://leetcode.com/problems/maximum-difference-between-adjacent-elements-in-a-circular-array/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Array%20Traversal%20%26%20Basics/3423.%20Maximum%20Difference%20Between%20Adjacent%20Elements%20in%20a%20Circular%20Array/3423.%20Maximum%20Difference%20Between%20Adjacent%20Elements%20in%20a%20Circular%20Array.md) |
| 32 | [3637. Trionic Array I](https://leetcode.com/problems/trionic-array-i/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Array%20Traversal%20%26%20Basics/3637.%20Trionic%20Array%20I/3637.%20Trionic%20Array%20I.md) |

## 02. In-Place Array Manipulation

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [31. Next Permutation](https://leetcode.com/problems/next-permutation/) | Medium | 3 months | 76.4 | ✅ Solved |  |  |  | [notes](02.%20In-Place%20Array%20Manipulation/0031.%20Next%20Permutation/0031.%20Next%20Permutation.md) |
| 2 | [189. Rotate Array](https://leetcode.com/problems/rotate-array/) | Medium | 6 months | 40.3 | ✅ Solved |  |  |  | [notes](02.%20In-Place%20Array%20Manipulation/0189.%20Rotate%20Array/0189.%20Rotate%20Array.md) |
| 3 | [1920. Build Array from Permutation](https://leetcode.com/problems/build-array-from-permutation/) | Easy | 6+ months | 36.7 | ✅ Solved |  |  |  | [notes](02.%20In-Place%20Array%20Manipulation/1920.%20Build%20Array%20from%20Permutation/1920.%20Build%20Array%20from%20Permutation.md) |
| 4 | [556. Next Greater Element III](https://leetcode.com/problems/next-greater-element-iii/) | Medium | 6+ months | 22.1 | Todo |  |  |  | [notes](02.%20In-Place%20Array%20Manipulation/0556.%20Next%20Greater%20Element%20III/0556.%20Next%20Greater%20Element%20III.md) |

## 03. Hash Map Lookup

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [1. Two Sum](https://leetcode.com/problems/two-sum/) | Easy | 30 days | 84.7 | ✅ Solved |  |  |  | [notes](03.%20Hash%20Map%20Lookup/0001.%20Two%20Sum/0001.%20Two%20Sum.md) |
| 2 | [205. Isomorphic Strings](https://leetcode.com/problems/isomorphic-strings/) | Easy | 3 months | 32.3 | ✅ Solved |  |  |  | [notes](03.%20Hash%20Map%20Lookup/0205.%20Isomorphic%20Strings/0205.%20Isomorphic%20Strings.md) |
| 3 | [290. Word Pattern](https://leetcode.com/problems/word-pattern/) | Easy | 6+ months | 19.1 | Todo |  |  |  | [notes](03.%20Hash%20Map%20Lookup/0290.%20Word%20Pattern/0290.%20Word%20Pattern.md) |
| 4 | [3761. Minimum Absolute Distance Between Mirror Pairs](https://leetcode.com/problems/minimum-absolute-distance-between-mirror-pairs/) | Medium | 6+ months | 9.3 | ✅ Solved |  |  |  | [notes](03.%20Hash%20Map%20Lookup/3761.%20Minimum%20Absolute%20Distance%20Between%20Mirror%20Pairs/3761.%20Minimum%20Absolute%20Distance%20Between%20Mirror%20Pairs.md) |
| 5 | [454. 4Sum II](https://leetcode.com/problems/4sum-ii/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](03.%20Hash%20Map%20Lookup/0454.%204Sum%20II/0454.%204Sum%20II.md) |
| 6 | [966. Vowel Spellchecker](https://leetcode.com/problems/vowel-spellchecker/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](03.%20Hash%20Map%20Lookup/0966.%20Vowel%20Spellchecker/0966.%20Vowel%20Spellchecker.md) |
| 7 | [1814. Count Nice Pairs in an Array](https://leetcode.com/problems/count-nice-pairs-in-an-array/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](03.%20Hash%20Map%20Lookup/1814.%20Count%20Nice%20Pairs%20in%20an%20Array/1814.%20Count%20Nice%20Pairs%20in%20an%20Array.md) |
| 8 | [2325. Decode the Message](https://leetcode.com/problems/decode-the-message/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](03.%20Hash%20Map%20Lookup/2325.%20Decode%20the%20Message/2325.%20Decode%20the%20Message.md) |
| 9 | [2342. Max Sum of a Pair With Equal Sum of Digits](https://leetcode.com/problems/max-sum-of-a-pair-with-equal-sum-of-digits/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](03.%20Hash%20Map%20Lookup/2342.%20Max%20Sum%20of%20a%20Pair%20With%20Equal%20Sum%20of%20Digits/2342.%20Max%20Sum%20of%20a%20Pair%20With%20Equal%20Sum%20of%20Digits.md) |
| 10 | [2352. Equal Row and Column Pairs](https://leetcode.com/problems/equal-row-and-column-pairs/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](03.%20Hash%20Map%20Lookup/2352.%20Equal%20Row%20and%20Column%20Pairs/2352.%20Equal%20Row%20and%20Column%20Pairs.md) |
| 11 | [2365. Task Scheduler II](https://leetcode.com/problems/task-scheduler-ii/) | Medium | 6+ months | 36.1 | Todo |  |  |  | [notes](03.%20Hash%20Map%20Lookup/2365.%20Task%20Scheduler%20II/2365.%20Task%20Scheduler%20II.md) |
| 12 | [890. Find and Replace Pattern](https://leetcode.com/problems/find-and-replace-pattern/) | Medium | 6+ months | 6.8 | Todo |  |  |  | [notes](03.%20Hash%20Map%20Lookup/0890.%20Find%20and%20Replace%20Pattern/0890.%20Find%20and%20Replace%20Pattern.md) |

## 04. Hash Set & Duplicates

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [128. Longest Consecutive Sequence](https://leetcode.com/problems/longest-consecutive-sequence/) | Medium | 3 months | 57.0 | ✅ Solved |  |  |  | [notes](04.%20Hash%20Set%20%26%20Duplicates/0128.%20Longest%20Consecutive%20Sequence/0128.%20Longest%20Consecutive%20Sequence.md) |
| 2 | [217. Contains Duplicate](https://leetcode.com/problems/contains-duplicate/) | Easy | 3 months | 44.4 | ✅ Solved |  |  |  | [notes](04.%20Hash%20Set%20%26%20Duplicates/0217.%20Contains%20Duplicate/0217.%20Contains%20Duplicate.md) |
| 3 | [349. Intersection of Two Arrays](https://leetcode.com/problems/intersection-of-two-arrays/) | Easy | 3 months | 41.3 | ✅ Solved |  |  |  | [notes](04.%20Hash%20Set%20%26%20Duplicates/0349.%20Intersection%20of%20Two%20Arrays/0349.%20Intersection%20of%20Two%20Arrays.md) |
| 4 | [36. Valid Sudoku](https://leetcode.com/problems/valid-sudoku/) | Medium | 3 months | 34.5 | ✅ Solved |  |  |  | [notes](04.%20Hash%20Set%20%26%20Duplicates/0036.%20Valid%20Sudoku/0036.%20Valid%20Sudoku.md) |
| 5 | [1832. Check if the Sentence Is Pangram](https://leetcode.com/problems/check-if-the-sentence-is-pangram/) | Easy | 6+ months | 8.8 | ✅ Solved |  |  |  | [notes](04.%20Hash%20Set%20%26%20Duplicates/1832.%20Check%20if%20the%20Sentence%20Is%20Pangram/1832.%20Check%20if%20the%20Sentence%20Is%20Pangram.md) |
| 6 | [3731. Find Missing Elements](https://leetcode.com/problems/find-missing-elements/) | Easy | 6+ months | 8.6 | Todo |  |  |  | [notes](04.%20Hash%20Set%20%26%20Duplicates/3731.%20Find%20Missing%20Elements/3731.%20Find%20Missing%20Elements.md) |
| 7 | [2657. Find the Prefix Common Array of Two Arrays](https://leetcode.com/problems/find-the-prefix-common-array-of-two-arrays/) | Medium | 6+ months | 8.4 | Todo |  |  |  | [notes](04.%20Hash%20Set%20%26%20Duplicates/2657.%20Find%20the%20Prefix%20Common%20Array%20of%20Two%20Arrays/2657.%20Find%20the%20Prefix%20Common%20Array%20of%20Two%20Arrays.md) |
| 8 | [2215. Find the Difference of Two Arrays](https://leetcode.com/problems/find-the-difference-of-two-arrays/) | Easy | 6+ months | 5.9 | Todo |  |  |  | [notes](04.%20Hash%20Set%20%26%20Duplicates/2215.%20Find%20the%20Difference%20of%20Two%20Arrays/2215.%20Find%20the%20Difference%20of%20Two%20Arrays.md) |
| 9 | [771. Jewels and Stones](https://leetcode.com/problems/jewels-and-stones/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](04.%20Hash%20Set%20%26%20Duplicates/0771.%20Jewels%20and%20Stones/0771.%20Jewels%20and%20Stones.md) |
| 10 | [888. Fair Candy Swap](https://leetcode.com/problems/fair-candy-swap/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Hash%20Set%20%26%20Duplicates/0888.%20Fair%20Candy%20Swap/0888.%20Fair%20Candy%20Swap.md) |
| 11 | [961. N-Repeated Element in Size 2N Array](https://leetcode.com/problems/n-repeated-element-in-size-2n-array/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Hash%20Set%20%26%20Duplicates/0961.%20N-Repeated%20Element%20in%20Size%202N%20Array/0961.%20N-Repeated%20Element%20in%20Size%202N%20Array.md) |
| 12 | [1346. Check If N and Its Double Exist](https://leetcode.com/problems/check-if-n-and-its-double-exist/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](04.%20Hash%20Set%20%26%20Duplicates/1346.%20Check%20If%20N%20and%20Its%20Double%20Exist/1346.%20Check%20If%20N%20and%20Its%20Double%20Exist.md) |
| 13 | [1436. Destination City](https://leetcode.com/problems/destination-city/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](04.%20Hash%20Set%20%26%20Duplicates/1436.%20Destination%20City/1436.%20Destination%20City.md) |
| 14 | [2154. Keep Multiplying Found Values by Two](https://leetcode.com/problems/keep-multiplying-found-values-by-two/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Hash%20Set%20%26%20Duplicates/2154.%20Keep%20Multiplying%20Found%20Values%20by%20Two/2154.%20Keep%20Multiplying%20Found%20Values%20by%20Two.md) |
| 15 | [2956. Find Common Elements Between Two Arrays](https://leetcode.com/problems/find-common-elements-between-two-arrays/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Hash%20Set%20%26%20Duplicates/2956.%20Find%20Common%20Elements%20Between%20Two%20Arrays/2956.%20Find%20Common%20Elements%20Between%20Two%20Arrays.md) |
| 16 | [3120. Count the Number of Special Characters I](https://leetcode.com/problems/count-the-number-of-special-characters-i/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Hash%20Set%20%26%20Duplicates/3120.%20Count%20the%20Number%20of%20Special%20Characters%20I/3120.%20Count%20the%20Number%20of%20Special%20Characters%20I.md) |
| 17 | [3289. The Two Sneaky Numbers of Digitville](https://leetcode.com/problems/the-two-sneaky-numbers-of-digitville/) | Easy | 6+ months | 5.0 | 🟡 Attempted |  |  |  | [notes](04.%20Hash%20Set%20%26%20Duplicates/3289.%20The%20Two%20Sneaky%20Numbers%20of%20Digitville/3289.%20The%20Two%20Sneaky%20Numbers%20of%20Digitville.md) |
| 18 | [3396. Minimum Number of Operations to Make Elements in Array Distinct](https://leetcode.com/problems/minimum-number-of-operations-to-make-elements-in-array-distinct/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Hash%20Set%20%26%20Duplicates/3396.%20Minimum%20Number%20of%20Operations%20to%20Make%20Elements%20in%20Array%20Distinct/3396.%20Minimum%20Number%20of%20Operations%20to%20Make%20Elements%20in%20Array%20Distinct.md) |
| 19 | [575. Distribute Candies](https://leetcode.com/problems/distribute-candies/) | Easy | 6+ months | 5.6 | Todo |  |  |  | [notes](04.%20Hash%20Set%20%26%20Duplicates/0575.%20Distribute%20Candies/0575.%20Distribute%20Candies.md) |
| 20 | [3483. Unique 3-Digit Even Numbers](https://leetcode.com/problems/unique-3-digit-even-numbers/) | Easy | 6+ months | 5.5 | Todo |  |  |  | [notes](04.%20Hash%20Set%20%26%20Duplicates/3483.%20Unique%203-Digit%20Even%20Numbers/3483.%20Unique%203-Digit%20Even%20Numbers.md) |
| 21 | [3668. Restore Finishing Order](https://leetcode.com/problems/restore-finishing-order/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Hash%20Set%20%26%20Duplicates/3668.%20Restore%20Finishing%20Order/3668.%20Restore%20Finishing%20Order.md) |

## 05. Frequency Counting

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [383. Ransom Note](https://leetcode.com/problems/ransom-note/) | Easy | 3 months | 26.7 | Todo |  |  |  | [notes](05.%20Frequency%20Counting/0383.%20Ransom%20Note/0383.%20Ransom%20Note.md) |
| 2 | [2965. Find Missing and Repeated Values](https://leetcode.com/problems/find-missing-and-repeated-values/) | Easy | 3 months | 13.5 | Todo |  |  |  | [notes](05.%20Frequency%20Counting/2965.%20Find%20Missing%20and%20Repeated%20Values/2965.%20Find%20Missing%20and%20Repeated%20Values.md) |
| 3 | [387. First Unique Character in a String](https://leetcode.com/problems/first-unique-character-in-a-string/) | Easy | 6 months | 28.7 | ✅ Solved |  |  |  | [notes](05.%20Frequency%20Counting/0387.%20First%20Unique%20Character%20in%20a%20String/0387.%20First%20Unique%20Character%20in%20a%20String.md) |
| 4 | [3020. Find the Maximum Number of Elements in Subset](https://leetcode.com/problems/find-the-maximum-number-of-elements-in-subset/) | Medium | 6 months | 7.3 | ✅ Solved |  |  |  | [notes](05.%20Frequency%20Counting/3020.%20Find%20the%20Maximum%20Number%20of%20Elements%20in%20Subset/3020.%20Find%20the%20Maximum%20Number%20of%20Elements%20in%20Subset.md) |
| 5 | [3471. Find the Largest Almost Missing Integer](https://leetcode.com/problems/find-the-largest-almost-missing-integer/) | Easy | 6 months | 5.0 | Todo |  |  |  | [notes](05.%20Frequency%20Counting/3471.%20Find%20the%20Largest%20Almost%20Missing%20Integer/3471.%20Find%20the%20Largest%20Almost%20Missing%20Integer.md) |
| 6 | [3960. Frequency Balance Subarray](https://leetcode.com/problems/frequency-balance-subarray/) | Medium | 6 months | 5.0 | Todo |  |  |  | [notes](05.%20Frequency%20Counting/3960.%20Frequency%20Balance%20Subarray/3960.%20Frequency%20Balance%20Subarray.md) |
| 7 | [825. Friends Of Appropriate Ages](https://leetcode.com/problems/friends-of-appropriate-ages/) | Medium | 6+ months | 54.4 | Todo |  |  |  | [notes](05.%20Frequency%20Counting/0825.%20Friends%20Of%20Appropriate%20Ages/0825.%20Friends%20Of%20Appropriate%20Ages.md) |
| 8 | [1748. Sum of Unique Elements](https://leetcode.com/problems/sum-of-unique-elements/) | Easy | 6+ months | 38.6 | ✅ Solved |  |  |  | [notes](05.%20Frequency%20Counting/1748.%20Sum%20of%20Unique%20Elements/1748.%20Sum%20of%20Unique%20Elements.md) |
| 9 | [554. Brick Wall](https://leetcode.com/problems/brick-wall/) | Medium | 6+ months | 38.1 | Todo |  |  |  | [notes](05.%20Frequency%20Counting/0554.%20Brick%20Wall/0554.%20Brick%20Wall.md) |
| 10 | [1207. Unique Number of Occurrences](https://leetcode.com/problems/unique-number-of-occurrences/) | Easy | 6+ months | 20.7 | ✅ Solved |  |  |  | [notes](05.%20Frequency%20Counting/1207.%20Unique%20Number%20of%20Occurrences/1207.%20Unique%20Number%20of%20Occurrences.md) |
| 11 | [3527. Find the Most Common Response](https://leetcode.com/problems/find-the-most-common-response/) | Medium | 6+ months | 19.6 | Todo |  |  |  | [notes](05.%20Frequency%20Counting/3527.%20Find%20the%20Most%20Common%20Response/3527.%20Find%20the%20Most%20Common%20Response.md) |
| 12 | [3371. Identify the Largest Outlier in an Array](https://leetcode.com/problems/identify-the-largest-outlier-in-an-array/) | Medium | 6+ months | 17.7 | Todo |  |  |  | [notes](05.%20Frequency%20Counting/3371.%20Identify%20the%20Largest%20Outlier%20in%20an%20Array/3371.%20Identify%20the%20Largest%20Outlier%20in%20an%20Array.md) |
| 13 | [1394. Find Lucky Integer in an Array](https://leetcode.com/problems/find-lucky-integer-in-an-array/) | Easy | 6+ months | 17.0 | Todo |  |  |  | [notes](05.%20Frequency%20Counting/1394.%20Find%20Lucky%20Integer%20in%20an%20Array/1394.%20Find%20Lucky%20Integer%20in%20an%20Array.md) |
| 14 | [350. Intersection of Two Arrays II](https://leetcode.com/problems/intersection-of-two-arrays-ii/) | Easy | 6+ months | 15.6 | ✅ Solved |  |  |  | [notes](05.%20Frequency%20Counting/0350.%20Intersection%20of%20Two%20Arrays%20II/0350.%20Intersection%20of%20Two%20Arrays%20II.md) |
| 15 | [299. Bulls and Cows](https://leetcode.com/problems/bulls-and-cows/) | Medium | 6+ months | 14.9 | Todo |  |  |  | [notes](05.%20Frequency%20Counting/0299.%20Bulls%20and%20Cows/0299.%20Bulls%20and%20Cows.md) |
| 16 | [594. Longest Harmonious Subsequence](https://leetcode.com/problems/longest-harmonious-subsequence/) | Easy | 6+ months | 10.8 | Todo |  |  |  | [notes](05.%20Frequency%20Counting/0594.%20Longest%20Harmonious%20Subsequence/0594.%20Longest%20Harmonious%20Subsequence.md) |
| 17 | [1781. Sum of Beauty of All Substrings](https://leetcode.com/problems/sum-of-beauty-of-all-substrings/) | Medium | 6+ months | 10.7 | Todo |  |  |  | [notes](05.%20Frequency%20Counting/1781.%20Sum%20of%20Beauty%20of%20All%20Substrings/1781.%20Sum%20of%20Beauty%20of%20All%20Substrings.md) |
| 18 | [2094. Finding 3-Digit Even Numbers](https://leetcode.com/problems/finding-3-digit-even-numbers/) | Easy | 6+ months | 9.8 | ✅ Solved |  |  |  | [notes](05.%20Frequency%20Counting/2094.%20Finding%203-Digit%20Even%20Numbers/2094.%20Finding%203-Digit%20Even%20Numbers.md) |
| 19 | [3583. Count Special Triplets](https://leetcode.com/problems/count-special-triplets/) | Medium | 6+ months | 9.7 | Todo |  |  |  | [notes](05.%20Frequency%20Counting/3583.%20Count%20Special%20Triplets/3583.%20Count%20Special%20Triplets.md) |
| 20 | [3541. Find Most Frequent Vowel and Consonant](https://leetcode.com/problems/find-most-frequent-vowel-and-consonant/) | Easy | 6+ months | 8.0 | Todo |  |  |  | [notes](05.%20Frequency%20Counting/3541.%20Find%20Most%20Frequent%20Vowel%20and%20Consonant/3541.%20Find%20Most%20Frequent%20Vowel%20and%20Consonant.md) |
| 21 | [1002. Find Common Characters](https://leetcode.com/problems/find-common-characters/) | Easy | 6+ months | 6.6 | ✅ Solved |  |  |  | [notes](05.%20Frequency%20Counting/1002.%20Find%20Common%20Characters/1002.%20Find%20Common%20Characters.md) |
| 22 | [819. Most Common Word](https://leetcode.com/problems/most-common-word/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Frequency%20Counting/0819.%20Most%20Common%20Word/0819.%20Most%20Common%20Word.md) |
| 23 | [869. Reordered Power of 2](https://leetcode.com/problems/reordered-power-of-2/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Frequency%20Counting/0869.%20Reordered%20Power%20of%202/0869.%20Reordered%20Power%20of%202.md) |
| 24 | [916. Word Subsets](https://leetcode.com/problems/word-subsets/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Frequency%20Counting/0916.%20Word%20Subsets/0916.%20Word%20Subsets.md) |
| 25 | [1160. Find Words That Can Be Formed by Characters](https://leetcode.com/problems/find-words-that-can-be-formed-by-characters/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Frequency%20Counting/1160.%20Find%20Words%20That%20Can%20Be%20Formed%20by%20Characters/1160.%20Find%20Words%20That%20Can%20Be%20Formed%20by%20Characters.md) |
| 26 | [1399. Count Largest Group](https://leetcode.com/problems/count-largest-group/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Frequency%20Counting/1399.%20Count%20Largest%20Group/1399.%20Count%20Largest%20Group.md) |
| 27 | [2981. Find Longest Special Substring That Occurs Thrice I](https://leetcode.com/problems/find-longest-special-substring-that-occurs-thrice-i/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](05.%20Frequency%20Counting/2981.%20Find%20Longest%20Special%20Substring%20That%20Occurs%20Thrice%20I/2981.%20Find%20Longest%20Special%20Substring%20That%20Occurs%20Thrice%20I.md) |
| 28 | [3005. Count Elements With Maximum Frequency](https://leetcode.com/problems/count-elements-with-maximum-frequency/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](05.%20Frequency%20Counting/3005.%20Count%20Elements%20With%20Maximum%20Frequency/3005.%20Count%20Elements%20With%20Maximum%20Frequency.md) |
| 29 | [3442. Maximum Difference Between Even and Odd Frequency I](https://leetcode.com/problems/maximum-difference-between-even-and-odd-frequency-i/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Frequency%20Counting/3442.%20Maximum%20Difference%20Between%20Even%20and%20Odd%20Frequency%20I/3442.%20Maximum%20Difference%20Between%20Even%20and%20Odd%20Frequency%20I.md) |
| 30 | [3713. Longest Balanced Substring I](https://leetcode.com/problems/longest-balanced-substring-i/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Frequency%20Counting/3713.%20Longest%20Balanced%20Substring%20I/3713.%20Longest%20Balanced%20Substring%20I.md) |
| 31 | [1460. Make Two Arrays Equal by Reversing Subarrays](https://leetcode.com/problems/make-two-arrays-equal-by-reversing-subarrays/) | Easy | 6+ months | 36.1 | Todo |  |  |  | [notes](05.%20Frequency%20Counting/1460.%20Make%20Two%20Arrays%20Equal%20by%20Reversing%20Subarrays/1460.%20Make%20Two%20Arrays%20Equal%20by%20Reversing%20Subarrays.md) |
| 32 | [1189. Maximum Number of Balloons](https://leetcode.com/problems/maximum-number-of-balloons/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Frequency%20Counting/1189.%20Maximum%20Number%20of%20Balloons/1189.%20Maximum%20Number%20of%20Balloons.md) |
| 33 | [1941. Check if All Characters Have Equal Number of Occurrences](https://leetcode.com/problems/check-if-all-characters-have-equal-number-of-occurrences/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](05.%20Frequency%20Counting/1941.%20Check%20if%20All%20Characters%20Have%20Equal%20Number%20of%20Occurrences/1941.%20Check%20if%20All%20Characters%20Have%20Equal%20Number%20of%20Occurrences.md) |

## 06. Grouping by Key

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [49. Group Anagrams](https://leetcode.com/problems/group-anagrams/) | Medium | 3 months | 63.1 | ✅ Solved |  |  |  | [notes](06.%20Grouping%20by%20Key/0049.%20Group%20Anagrams/0049.%20Group%20Anagrams.md) |
| 2 | [249. Group Shifted Strings](https://leetcode.com/problems/group-shifted-strings/) 🔒 | Medium | 3 months | 57.5 | Todo |  |  |  | [notes](06.%20Grouping%20by%20Key/0249.%20Group%20Shifted%20Strings/0249.%20Group%20Shifted%20Strings.md) |
| 3 | [609. Find Duplicate File in System](https://leetcode.com/problems/find-duplicate-file-in-system/) | Medium | 6+ months | 5.8 | Todo |  |  |  | [notes](06.%20Grouping%20by%20Key/0609.%20Find%20Duplicate%20File%20in%20System/0609.%20Find%20Duplicate%20File%20in%20System.md) |
| 4 | [893. Groups of Special-Equivalent Strings](https://leetcode.com/problems/groups-of-special-equivalent-strings/) | Medium | 6+ months | 36.1 | Todo |  |  |  | [notes](06.%20Grouping%20by%20Key/0893.%20Groups%20of%20Special-Equivalent%20Strings/0893.%20Groups%20of%20Special-Equivalent%20Strings.md) |

## 07. Kadane's Algorithm

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [53. Maximum Subarray](https://leetcode.com/problems/maximum-subarray/) | Medium | 6 months | 58.9 | ✅ Solved |  |  |  | [notes](07.%20Kadane%27s%20Algorithm/0053.%20Maximum%20Subarray/0053.%20Maximum%20Subarray.md) |
| 2 | [152. Maximum Product Subarray](https://leetcode.com/problems/maximum-product-subarray/) | Medium | 6 months | 35.5 | ✅ Solved |  |  |  | [notes](07.%20Kadane%27s%20Algorithm/0152.%20Maximum%20Product%20Subarray/0152.%20Maximum%20Product%20Subarray.md) |
| 3 | [918. Maximum Sum Circular Subarray](https://leetcode.com/problems/maximum-sum-circular-subarray/) | Medium | 6+ months | 12.8 | Todo |  |  |  | [notes](07.%20Kadane%27s%20Algorithm/0918.%20Maximum%20Sum%20Circular%20Subarray/0918.%20Maximum%20Sum%20Circular%20Subarray.md) |
| 4 | [1749. Maximum Absolute Sum of Any Subarray](https://leetcode.com/problems/maximum-absolute-sum-of-any-subarray/) | Medium | 6+ months | 10.9 | Todo |  |  |  | [notes](07.%20Kadane%27s%20Algorithm/1749.%20Maximum%20Absolute%20Sum%20of%20Any%20Subarray/1749.%20Maximum%20Absolute%20Sum%20of%20Any%20Subarray.md) |

## 08. Cyclic Sort & Index Marking

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [645. Set Mismatch](https://leetcode.com/problems/set-mismatch/) | Easy | 6 months | 25.6 | 🟡 Attempted |  |  |  | [notes](08.%20Cyclic%20Sort%20%26%20Index%20Marking/0645.%20Set%20Mismatch/0645.%20Set%20Mismatch.md) |
| 2 | [41. First Missing Positive](https://leetcode.com/problems/first-missing-positive/) | Hard | 6+ months | 30.5 | ✅ Solved |  |  |  | [notes](08.%20Cyclic%20Sort%20%26%20Index%20Marking/0041.%20First%20Missing%20Positive/0041.%20First%20Missing%20Positive.md) |
| 3 | [442. Find All Duplicates in an Array](https://leetcode.com/problems/find-all-duplicates-in-an-array/) | Medium | 6+ months | 20.2 | ✅ Solved |  |  |  | [notes](08.%20Cyclic%20Sort%20%26%20Index%20Marking/0442.%20Find%20All%20Duplicates%20in%20an%20Array/0442.%20Find%20All%20Duplicates%20in%20an%20Array.md) |
| 4 | [448. Find All Numbers Disappeared in an Array](https://leetcode.com/problems/find-all-numbers-disappeared-in-an-array/) | Easy | 6+ months | 5.8 | ✅ Solved |  |  |  | [notes](08.%20Cyclic%20Sort%20%26%20Index%20Marking/0448.%20Find%20All%20Numbers%20Disappeared%20in%20an%20Array/0448.%20Find%20All%20Numbers%20Disappeared%20in%20an%20Array.md) |
| 5 | [565. Array Nesting](https://leetcode.com/problems/array-nesting/) | Medium | 6+ months | 5.1 | Todo |  |  |  | [notes](08.%20Cyclic%20Sort%20%26%20Index%20Marking/0565.%20Array%20Nesting/0565.%20Array%20Nesting.md) |

## 09. Majority Element (Boyer-Moore)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea&ensp;&#8203; | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [169. Majority Element](https://leetcode.com/problems/majority-element/) | Easy | 6 months | 46.4 | ✅ Solved |  |  |  | [notes](09.%20Majority%20Element%20%28Boyer-Moore%29/0169.%20Majority%20Element/0169.%20Majority%20Element.md) |
| 2 | [229. Majority Element II](https://leetcode.com/problems/majority-element-ii/) | Medium | 6 months | 24.0 | ✅ Solved |  |  |  | [notes](09.%20Majority%20Element%20%28Boyer-Moore%29/0229.%20Majority%20Element%20II/0229.%20Majority%20Element%20II.md) |
