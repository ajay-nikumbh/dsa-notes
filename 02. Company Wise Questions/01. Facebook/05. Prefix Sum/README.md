# 05. Prefix Sum

[Back to Facebook](../README.md) · [Back to DSA Notes](../../../README.md)

49 Meta (Facebook) problems: 11 Easy, 34 Medium, 4 Hard, in 5 sub-patterns.

## Sub-patterns

| # | Sub-pattern | Questions | Easy | Medium | Hard | Last 3 Months | Solved | Most Asked |
|:---:|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---|
| 01 | [1D Prefix Sum](#01-1d-prefix-sum) | 24 | 10 | 12 | 2 | 1 | 10 | 528. Random Pick with Weight, 689. Maximum Sum of 3 Non-Overlapping Subarrays, 724. Find Pivot Index |
| 02 | [Prefix Sum + Hash Map](#02-prefix-sum--hash-map) | 9 | 0 | 9 | 0 | 2 | 2 | 560. Subarray Sum Equals K, 523. Continuous Subarray Sum, 525. Contiguous Array |
| 03 | [2D Prefix Sum](#03-2d-prefix-sum) | 3 | 0 | 2 | 1 | 0 | 0 | 304. Range Sum Query 2D - Immutable, 1074. Number of Submatrices That Sum to Target, 2536. Increment Submatrices by One |
| 04 | [Difference Array](#04-difference-array) | 9 | 1 | 7 | 1 | 0 | 0 | 1094. Car Pooling, 1109. Corporate Flight Bookings, 1674. Minimum Moves to Make Array Complementary |
| 05 | [Prefix Product & Prefix XOR](#05-prefix-product--prefix-xor) | 4 | 0 | 4 | 0 | 0 | 2 | 238. Product of Array Except Self, 3862. Find the Smallest Balanced Index, 1352. Product of the Last K Numbers |

**Columns**

- **Last Asked**: most recent LeetCode window that lists the problem for Meta (30 days, 3 months, 6 months or 6+ months).
- **Frequency**: LeetCode frequency score (0-100) in the Meta "All" list.
- **Status**: your LeetCode status on the day this file was generated. 🔒 after a title means LeetCode Premium.
- **Logic / Key Idea, Time, Space**: fill these in as you solve. A rebuild keeps what you typed.
- **Notes**: link to the problem's notes file.

Inside each sub-pattern, rows are sorted by most recent window, then by frequency (highest first).

## 01. 1D Prefix Sum

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [1524. Number of Sub-arrays With Odd Sum](https://leetcode.com/problems/number-of-sub-arrays-with-odd-sum/) | Medium | 3 months | 15.2 | Todo |  |  |  | [notes](01.%201D%20Prefix%20Sum/1524.%20Number%20of%20Sub-arrays%20With%20Odd%20Sum/1524.%20Number%20of%20Sub-arrays%20With%20Odd%20Sum.md) |
| 2 | [303. Range Sum Query - Immutable](https://leetcode.com/problems/range-sum-query-immutable/) | Easy | 6 months | 39.3 | ✅ Solved |  |  |  | [notes](01.%201D%20Prefix%20Sum/0303.%20Range%20Sum%20Query%20-%20Immutable/0303.%20Range%20Sum%20Query%20-%20Immutable.md) |
| 3 | [1480. Running Sum of 1d Array](https://leetcode.com/problems/running-sum-of-1d-array/) | Easy | 6 months | 18.2 | ✅ Solved |  |  |  | [notes](01.%201D%20Prefix%20Sum/1480.%20Running%20Sum%20of%201d%20Array/1480.%20Running%20Sum%20of%201d%20Array.md) |
| 4 | [1732. Find the Highest Altitude](https://leetcode.com/problems/find-the-highest-altitude/) | Easy | 6 months | 14.2 | ✅ Solved |  |  |  | [notes](01.%201D%20Prefix%20Sum/1732.%20Find%20the%20Highest%20Altitude/1732.%20Find%20the%20Highest%20Altitude.md) |
| 5 | [2574. Left and Right Sum Differences](https://leetcode.com/problems/left-and-right-sum-differences/) | Easy | 6 months | 5.0 | ✅ Solved |  |  |  | [notes](01.%201D%20Prefix%20Sum/2574.%20Left%20and%20Right%20Sum%20Differences/2574.%20Left%20and%20Right%20Sum%20Differences.md) |
| 6 | [528. Random Pick with Weight](https://leetcode.com/problems/random-pick-with-weight/) | Medium | 6+ months | 85.8 | Todo |  |  |  | [notes](01.%201D%20Prefix%20Sum/0528.%20Random%20Pick%20with%20Weight/0528.%20Random%20Pick%20with%20Weight.md) |
| 7 | [689. Maximum Sum of 3 Non-Overlapping Subarrays](https://leetcode.com/problems/maximum-sum-of-3-non-overlapping-subarrays/) | Hard | 6+ months | 42.5 | Todo |  |  |  | [notes](01.%201D%20Prefix%20Sum/0689.%20Maximum%20Sum%20of%203%20Non-Overlapping%20Subarrays/0689.%20Maximum%20Sum%20of%203%20Non-Overlapping%20Subarrays.md) |
| 8 | [724. Find Pivot Index](https://leetcode.com/problems/find-pivot-index/) | Easy | 6+ months | 40.9 | ✅ Solved |  |  |  | [notes](01.%201D%20Prefix%20Sum/0724.%20Find%20Pivot%20Index/0724.%20Find%20Pivot%20Index.md) |
| 9 | [3737. Count Subarrays With Majority Element I](https://leetcode.com/problems/count-subarrays-with-majority-element-i/) | Medium | 6+ months | 8.4 | Todo |  |  |  | [notes](01.%201D%20Prefix%20Sum/3737.%20Count%20Subarrays%20With%20Majority%20Element%20I/3737.%20Count%20Subarrays%20With%20Majority%20Element%20I.md) |
| 10 | [2145. Count the Hidden Sequences](https://leetcode.com/problems/count-the-hidden-sequences/) | Medium | 6+ months | 8.0 | Todo |  |  |  | [notes](01.%201D%20Prefix%20Sum/2145.%20Count%20the%20Hidden%20Sequences/2145.%20Count%20the%20Hidden%20Sequences.md) |
| 11 | [3494. Find the Minimum Amount of Time to Brew Potions](https://leetcode.com/problems/find-the-minimum-amount-of-time-to-brew-potions/) | Medium | 6+ months | 6.2 | Todo |  |  |  | [notes](01.%201D%20Prefix%20Sum/3494.%20Find%20the%20Minimum%20Amount%20of%20Time%20to%20Brew%20Potions/3494.%20Find%20the%20Minimum%20Amount%20of%20Time%20to%20Brew%20Potions.md) |
| 12 | [1413. Minimum Value to Get Positive Step by Step Sum](https://leetcode.com/problems/minimum-value-to-get-positive-step-by-step-sum/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%201D%20Prefix%20Sum/1413.%20Minimum%20Value%20to%20Get%20Positive%20Step%20by%20Step%20Sum/1413.%20Minimum%20Value%20to%20Get%20Positive%20Step%20by%20Step%20Sum.md) |
| 13 | [1422. Maximum Score After Splitting a String](https://leetcode.com/problems/maximum-score-after-splitting-a-string/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](01.%201D%20Prefix%20Sum/1422.%20Maximum%20Score%20After%20Splitting%20a%20String/1422.%20Maximum%20Score%20After%20Splitting%20a%20String.md) |
| 14 | [1664. Ways to Make a Fair Array](https://leetcode.com/problems/ways-to-make-a-fair-array/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%201D%20Prefix%20Sum/1664.%20Ways%20to%20Make%20a%20Fair%20Array/1664.%20Ways%20to%20Make%20a%20Fair%20Array.md) |
| 15 | [1685. Sum of Absolute Differences in a Sorted Array](https://leetcode.com/problems/sum-of-absolute-differences-in-a-sorted-array/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%201D%20Prefix%20Sum/1685.%20Sum%20of%20Absolute%20Differences%20in%20a%20Sorted%20Array/1685.%20Sum%20of%20Absolute%20Differences%20in%20a%20Sorted%20Array.md) |
| 16 | [1769. Minimum Number of Operations to Move All Balls to Each Box](https://leetcode.com/problems/minimum-number-of-operations-to-move-all-balls-to-each-box/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%201D%20Prefix%20Sum/1769.%20Minimum%20Number%20of%20Operations%20to%20Move%20All%20Balls%20to%20Each%20Box/1769.%20Minimum%20Number%20of%20Operations%20to%20Move%20All%20Balls%20to%20Each%20Box.md) |
| 17 | [2256. Minimum Average Difference](https://leetcode.com/problems/minimum-average-difference/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%201D%20Prefix%20Sum/2256.%20Minimum%20Average%20Difference/2256.%20Minimum%20Average%20Difference.md) |
| 18 | [2270. Number of Ways to Split Array](https://leetcode.com/problems/number-of-ways-to-split-array/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](01.%201D%20Prefix%20Sum/2270.%20Number%20of%20Ways%20to%20Split%20Array/2270.%20Number%20of%20Ways%20to%20Split%20Array.md) |
| 19 | [2483. Minimum Penalty for a Shop](https://leetcode.com/problems/minimum-penalty-for-a-shop/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%201D%20Prefix%20Sum/2483.%20Minimum%20Penalty%20for%20a%20Shop/2483.%20Minimum%20Penalty%20for%20a%20Shop.md) |
| 20 | [2485. Find the Pivot Integer](https://leetcode.com/problems/find-the-pivot-integer/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](01.%201D%20Prefix%20Sum/2485.%20Find%20the%20Pivot%20Integer/2485.%20Find%20the%20Pivot%20Integer.md) |
| 21 | [2559. Count Vowel Strings in Ranges](https://leetcode.com/problems/count-vowel-strings-in-ranges/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](01.%201D%20Prefix%20Sum/2559.%20Count%20Vowel%20Strings%20in%20Ranges/2559.%20Count%20Vowel%20Strings%20in%20Ranges.md) |
| 22 | [3354. Make Array Elements Equal to Zero](https://leetcode.com/problems/make-array-elements-equal-to-zero/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%201D%20Prefix%20Sum/3354.%20Make%20Array%20Elements%20Equal%20to%20Zero/3354.%20Make%20Array%20Elements%20Equal%20to%20Zero.md) |
| 23 | [3427. Sum of Variable Length Subarrays](https://leetcode.com/problems/sum-of-variable-length-subarrays/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](01.%201D%20Prefix%20Sum/3427.%20Sum%20of%20Variable%20Length%20Subarrays/3427.%20Sum%20of%20Variable%20Length%20Subarrays.md) |
| 24 | [3445. Maximum Difference Between Even and Odd Frequency II](https://leetcode.com/problems/maximum-difference-between-even-and-odd-frequency-ii/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%201D%20Prefix%20Sum/3445.%20Maximum%20Difference%20Between%20Even%20and%20Odd%20Frequency%20II/3445.%20Maximum%20Difference%20Between%20Even%20and%20Odd%20Frequency%20II.md) |

## 02. Prefix Sum + Hash Map

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [523. Continuous Subarray Sum](https://leetcode.com/problems/continuous-subarray-sum/) | Medium | 3 months | 59.7 | Todo |  |  |  | [notes](02.%20Prefix%20Sum%20%2B%20Hash%20Map/0523.%20Continuous%20Subarray%20Sum/0523.%20Continuous%20Subarray%20Sum.md) |
| 2 | [525. Contiguous Array](https://leetcode.com/problems/contiguous-array/) | Medium | 3 months | 53.4 | ✅ Solved |  |  |  | [notes](02.%20Prefix%20Sum%20%2B%20Hash%20Map/0525.%20Contiguous%20Array/0525.%20Contiguous%20Array.md) |
| 3 | [560. Subarray Sum Equals K](https://leetcode.com/problems/subarray-sum-equals-k/) | Medium | 6 months | 88.4 | ✅ Solved |  |  |  | [notes](02.%20Prefix%20Sum%20%2B%20Hash%20Map/0560.%20Subarray%20Sum%20Equals%20K/0560.%20Subarray%20Sum%20Equals%20K.md) |
| 4 | [974. Subarray Sums Divisible by K](https://leetcode.com/problems/subarray-sums-divisible-by-k/) | Medium | 6 months | 19.0 | Todo |  |  |  | [notes](02.%20Prefix%20Sum%20%2B%20Hash%20Map/0974.%20Subarray%20Sums%20Divisible%20by%20K/0974.%20Subarray%20Sums%20Divisible%20by%20K.md) |
| 5 | [325. Maximum Size Subarray Sum Equals k](https://leetcode.com/problems/maximum-size-subarray-sum-equals-k/) 🔒 | Medium | 6+ months | 40.3 | Todo |  |  |  | [notes](02.%20Prefix%20Sum%20%2B%20Hash%20Map/0325.%20Maximum%20Size%20Subarray%20Sum%20Equals%20k/0325.%20Maximum%20Size%20Subarray%20Sum%20Equals%20k.md) |
| 6 | [3714. Longest Balanced Substring II](https://leetcode.com/problems/longest-balanced-substring-ii/) | Medium | 6+ months | 11.3 | Todo |  |  |  | [notes](02.%20Prefix%20Sum%20%2B%20Hash%20Map/3714.%20Longest%20Balanced%20Substring%20II/3714.%20Longest%20Balanced%20Substring%20II.md) |
| 7 | [3381. Maximum Subarray Sum With Length Divisible by K](https://leetcode.com/problems/maximum-subarray-sum-with-length-divisible-by-k/) | Medium | 6+ months | 5.9 | Todo |  |  |  | [notes](02.%20Prefix%20Sum%20%2B%20Hash%20Map/3381.%20Maximum%20Subarray%20Sum%20With%20Length%20Divisible%20by%20K/3381.%20Maximum%20Subarray%20Sum%20With%20Length%20Divisible%20by%20K.md) |
| 8 | [1590. Make Sum Divisible by P](https://leetcode.com/problems/make-sum-divisible-by-p/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Prefix%20Sum%20%2B%20Hash%20Map/1590.%20Make%20Sum%20Divisible%20by%20P/1590.%20Make%20Sum%20Divisible%20by%20P.md) |
| 9 | [2615. Sum of Distances](https://leetcode.com/problems/sum-of-distances/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Prefix%20Sum%20%2B%20Hash%20Map/2615.%20Sum%20of%20Distances/2615.%20Sum%20of%20Distances.md) |

## 03. 2D Prefix Sum

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [304. Range Sum Query 2D - Immutable](https://leetcode.com/problems/range-sum-query-2d-immutable/) | Medium | 6 months | 12.1 | Todo |  |  |  | [notes](03.%202D%20Prefix%20Sum/0304.%20Range%20Sum%20Query%202D%20-%20Immutable/0304.%20Range%20Sum%20Query%202D%20-%20Immutable.md) |
| 2 | [1074. Number of Submatrices That Sum to Target](https://leetcode.com/problems/number-of-submatrices-that-sum-to-target/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](03.%202D%20Prefix%20Sum/1074.%20Number%20of%20Submatrices%20That%20Sum%20to%20Target/1074.%20Number%20of%20Submatrices%20That%20Sum%20to%20Target.md) |
| 3 | [2536. Increment Submatrices by One](https://leetcode.com/problems/increment-submatrices-by-one/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](03.%202D%20Prefix%20Sum/2536.%20Increment%20Submatrices%20by%20One/2536.%20Increment%20Submatrices%20by%20One.md) |

## 04. Difference Array

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [1109. Corporate Flight Bookings](https://leetcode.com/problems/corporate-flight-bookings/) | Medium | 6 months | 10.0 | Todo |  |  |  | [notes](04.%20Difference%20Array/1109.%20Corporate%20Flight%20Bookings/1109.%20Corporate%20Flight%20Bookings.md) |
| 2 | [1094. Car Pooling](https://leetcode.com/problems/car-pooling/) | Medium | 6+ months | 33.6 | Todo |  |  |  | [notes](04.%20Difference%20Array/1094.%20Car%20Pooling/1094.%20Car%20Pooling.md) |
| 3 | [1674. Minimum Moves to Make Array Complementary](https://leetcode.com/problems/minimum-moves-to-make-array-complementary/) | Medium | 6+ months | 6.7 | Todo |  |  |  | [notes](04.%20Difference%20Array/1674.%20Minimum%20Moves%20to%20Make%20Array%20Complementary/1674.%20Minimum%20Moves%20to%20Make%20Array%20Complementary.md) |
| 4 | [2381. Shifting Letters II](https://leetcode.com/problems/shifting-letters-ii/) | Medium | 6+ months | 6.6 | Todo |  |  |  | [notes](04.%20Difference%20Array/2381.%20Shifting%20Letters%20II/2381.%20Shifting%20Letters%20II.md) |
| 5 | [1871. Jump Game VII](https://leetcode.com/problems/jump-game-vii/) | Medium | 6+ months | 6.4 | Todo |  |  |  | [notes](04.%20Difference%20Array/1871.%20Jump%20Game%20VII/1871.%20Jump%20Game%20VII.md) |
| 6 | [1854. Maximum Population Year](https://leetcode.com/problems/maximum-population-year/) | Easy | 6+ months | 5.8 | Todo |  |  |  | [notes](04.%20Difference%20Array/1854.%20Maximum%20Population%20Year/1854.%20Maximum%20Population%20Year.md) |
| 7 | [3346. Maximum Frequency of an Element After Performing Operations I](https://leetcode.com/problems/maximum-frequency-of-an-element-after-performing-operations-i/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Difference%20Array/3346.%20Maximum%20Frequency%20of%20an%20Element%20After%20Performing%20Operations%20I/3346.%20Maximum%20Frequency%20of%20an%20Element%20After%20Performing%20Operations%20I.md) |
| 8 | [3356. Zero Array Transformation II](https://leetcode.com/problems/zero-array-transformation-ii/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Difference%20Array/3356.%20Zero%20Array%20Transformation%20II/3356.%20Zero%20Array%20Transformation%20II.md) |
| 9 | [995. Minimum Number of K Consecutive Bit Flips](https://leetcode.com/problems/minimum-number-of-k-consecutive-bit-flips/) | Hard | 6+ months | 5.5 | Todo |  |  |  | [notes](04.%20Difference%20Array/0995.%20Minimum%20Number%20of%20K%20Consecutive%20Bit%20Flips/0995.%20Minimum%20Number%20of%20K%20Consecutive%20Bit%20Flips.md) |

## 05. Prefix Product & Prefix XOR

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [238. Product of Array Except Self](https://leetcode.com/problems/product-of-array-except-self/) | Medium | 6 months | 53.2 | ✅ Solved |  |  |  | [notes](05.%20Prefix%20Product%20%26%20Prefix%20XOR/0238.%20Product%20of%20Array%20Except%20Self/0238.%20Product%20of%20Array%20Except%20Self.md) |
| 2 | [1352. Product of the Last K Numbers](https://leetcode.com/problems/product-of-the-last-k-numbers/) | Medium | 6+ months | 22.6 | Todo |  |  |  | [notes](05.%20Prefix%20Product%20%26%20Prefix%20XOR/1352.%20Product%20of%20the%20Last%20K%20Numbers/1352.%20Product%20of%20the%20Last%20K%20Numbers.md) |
| 3 | [1442. Count Triplets That Can Form Two Arrays of Equal XOR](https://leetcode.com/problems/count-triplets-that-can-form-two-arrays-of-equal-xor/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Prefix%20Product%20%26%20Prefix%20XOR/1442.%20Count%20Triplets%20That%20Can%20Form%20Two%20Arrays%20of%20Equal%20XOR/1442.%20Count%20Triplets%20That%20Can%20Form%20Two%20Arrays%20of%20Equal%20XOR.md) |
| 4 | [3862. Find the Smallest Balanced Index](https://leetcode.com/problems/find-the-smallest-balanced-index/) | Medium | 6+ months | 36.1 | ✅ Solved |  |  |  | [notes](05.%20Prefix%20Product%20%26%20Prefix%20XOR/3862.%20Find%20the%20Smallest%20Balanced%20Index/3862.%20Find%20the%20Smallest%20Balanced%20Index.md) |
