# 11. Binary Search

[Back to Facebook](../README.md) · [Back to DSA Notes](../../../README.md)

54 Meta (Facebook) problems: 14 Easy, 32 Medium, 8 Hard, in 7 sub-patterns.

## Sub-patterns

| # | Sub-pattern | Questions | Easy | Medium | Hard | Last 3 Months | Solved | Most Asked |
|:---:|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---|
| 01 | [Classic Binary Search](#01-classic-binary-search) | 3 | 2 | 1 | 0 | 1 | 3 | 540. Single Element in a Sorted Array, 704. Binary Search, 374. Guess Number Higher or Lower |
| 02 | [Lower & Upper Bound](#02-lower--upper-bound) | 14 | 7 | 7 | 0 | 2 | 5 | 34. Find First and Last Position of Element in Sorted Array, 1539. Kth Missing Positive Number, 278. First Bad Version |
| 03 | [Rotated Sorted Array](#03-rotated-sorted-array) | 4 | 0 | 3 | 1 | 1 | 2 | 33. Search in Rotated Sorted Array, 153. Find Minimum in Rotated Sorted Array, 81. Search in Rotated Sorted Array II |
| 04 | [Binary Search on Answer](#04-binary-search-on-answer) | 24 | 4 | 15 | 5 | 2 | 5 | 875. Koko Eating Bananas, 410. Split Array Largest Sum, 69. Sqrt(x) |
| 05 | [Search in 2D Matrix](#05-search-in-2d-matrix) | 4 | 1 | 3 | 0 | 0 | 2 | 240. Search a 2D Matrix II, 1428. Leftmost Column with at Least a One, 74. Search a 2D Matrix |
| 06 | [Peak Finding](#06-peak-finding) | 4 | 0 | 3 | 1 | 0 | 0 | 162. Find Peak Element, 852. Peak Index in a Mountain Array, 1901. Find a Peak Element II |
| 07 | [Binary Search on Two Arrays](#07-binary-search-on-two-arrays) | 1 | 0 | 0 | 1 | 1 | 0 | 4. Median of Two Sorted Arrays |

**Columns**

- **Last Asked**: most recent LeetCode window that lists the problem for Meta (30 days, 3 months, 6 months or 6+ months).
- **Frequency**: LeetCode frequency score (0-100) in the Meta "All" list.
- **Status**: your LeetCode status on the day this file was generated. 🔒 after a title means LeetCode Premium.
- **Logic / Key Idea, Time, Space**: fill these in as you solve. A rebuild keeps what you typed.
- **Notes**: link to the problem's notes file.

Inside each sub-pattern, rows are sorted by most recent window, then by frequency (highest first).

## 01. Classic Binary Search

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [704. Binary Search](https://leetcode.com/problems/binary-search/) | Easy | 3 months | 31.6 | ✅ Solved |  |  |  | [notes](01.%20Classic%20Binary%20Search/0704.%20Binary%20Search/0704.%20Binary%20Search.md) |
| 2 | [540. Single Element in a Sorted Array](https://leetcode.com/problems/single-element-in-a-sorted-array/) | Medium | 6 months | 45.7 | ✅ Solved |  |  |  | [notes](01.%20Classic%20Binary%20Search/0540.%20Single%20Element%20in%20a%20Sorted%20Array/0540.%20Single%20Element%20in%20a%20Sorted%20Array.md) |
| 3 | [374. Guess Number Higher or Lower](https://leetcode.com/problems/guess-number-higher-or-lower/) | Easy | 6+ months | 6.5 | ✅ Solved |  |  |  | [notes](01.%20Classic%20Binary%20Search/0374.%20Guess%20Number%20Higher%20or%20Lower/0374.%20Guess%20Number%20Higher%20or%20Lower.md) |

## 02. Lower & Upper Bound

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [34. Find First and Last Position of Element in Sorted Array](https://leetcode.com/problems/find-first-and-last-position-of-element-in-sorted-array/) | Medium | 3 months | 71.8 | Todo |  |  |  | [notes](02.%20Lower%20%26%20Upper%20Bound/0034.%20Find%20First%20and%20Last%20Position%20of%20Element%20in%20Sorted%20Array/0034.%20Find%20First%20and%20Last%20Position%20of%20Element%20in%20Sorted%20Array.md) |
| 2 | [1385. Find the Distance Value Between Two Arrays](https://leetcode.com/problems/find-the-distance-value-between-two-arrays/) | Easy | 3 months | 9.5 | ✅ Solved |  |  |  | [notes](02.%20Lower%20%26%20Upper%20Bound/1385.%20Find%20the%20Distance%20Value%20Between%20Two%20Arrays/1385.%20Find%20the%20Distance%20Value%20Between%20Two%20Arrays.md) |
| 3 | [278. First Bad Version](https://leetcode.com/problems/first-bad-version/) | Easy | 6 months | 44.6 | ✅ Solved |  |  |  | [notes](02.%20Lower%20%26%20Upper%20Bound/0278.%20First%20Bad%20Version/0278.%20First%20Bad%20Version.md) |
| 4 | [35. Search Insert Position](https://leetcode.com/problems/search-insert-position/) | Easy | 6 months | 43.7 | ✅ Solved |  |  |  | [notes](02.%20Lower%20%26%20Upper%20Bound/0035.%20Search%20Insert%20Position/0035.%20Search%20Insert%20Position.md) |
| 5 | [658. Find K Closest Elements](https://leetcode.com/problems/find-k-closest-elements/) | Medium | 6 months | 36.5 | Todo |  |  |  | [notes](02.%20Lower%20%26%20Upper%20Bound/0658.%20Find%20K%20Closest%20Elements/0658.%20Find%20K%20Closest%20Elements.md) |
| 6 | [1539. Kth Missing Positive Number](https://leetcode.com/problems/kth-missing-positive-number/) | Easy | 6+ months | 64.9 | Todo |  |  |  | [notes](02.%20Lower%20%26%20Upper%20Bound/1539.%20Kth%20Missing%20Positive%20Number/1539.%20Kth%20Missing%20Positive%20Number.md) |
| 7 | [1060. Missing Element in Sorted Array](https://leetcode.com/problems/missing-element-in-sorted-array/) 🔒 | Medium | 6+ months | 41.3 | Todo |  |  |  | [notes](02.%20Lower%20%26%20Upper%20Bound/1060.%20Missing%20Element%20in%20Sorted%20Array/1060.%20Missing%20Element%20in%20Sorted%20Array.md) |
| 8 | [275. H-Index II](https://leetcode.com/problems/h-index-ii/) | Medium | 6+ months | 36.1 | Todo |  |  |  | [notes](02.%20Lower%20%26%20Upper%20Bound/0275.%20H-Index%20II/0275.%20H-Index%20II.md) |
| 9 | [744. Find Smallest Letter Greater Than Target](https://leetcode.com/problems/find-smallest-letter-greater-than-target/) | Easy | 6+ months | 18.6 | ✅ Solved |  |  |  | [notes](02.%20Lower%20%26%20Upper%20Bound/0744.%20Find%20Smallest%20Letter%20Greater%20Than%20Target/0744.%20Find%20Smallest%20Letter%20Greater%20Than%20Target.md) |
| 10 | [2300. Successful Pairs of Spells and Potions](https://leetcode.com/problems/successful-pairs-of-spells-and-potions/) | Medium | 6+ months | 6.9 | Todo |  |  |  | [notes](02.%20Lower%20%26%20Upper%20Bound/2300.%20Successful%20Pairs%20of%20Spells%20and%20Potions/2300.%20Successful%20Pairs%20of%20Spells%20and%20Potions.md) |
| 11 | [475. Heaters](https://leetcode.com/problems/heaters/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Lower%20%26%20Upper%20Bound/0475.%20Heaters/0475.%20Heaters.md) |
| 12 | [2250. Count Number of Rectangles Containing Each Point](https://leetcode.com/problems/count-number-of-rectangles-containing-each-point/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Lower%20%26%20Upper%20Bound/2250.%20Count%20Number%20of%20Rectangles%20Containing%20Each%20Point/2250.%20Count%20Number%20of%20Rectangles%20Containing%20Each%20Point.md) |
| 13 | [2389. Longest Subsequence With Limited Sum](https://leetcode.com/problems/longest-subsequence-with-limited-sum/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Lower%20%26%20Upper%20Bound/2389.%20Longest%20Subsequence%20With%20Limited%20Sum/2389.%20Longest%20Subsequence%20With%20Limited%20Sum.md) |
| 14 | [2529. Maximum Count of Positive Integer and Negative Integer](https://leetcode.com/problems/maximum-count-of-positive-integer-and-negative-integer/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](02.%20Lower%20%26%20Upper%20Bound/2529.%20Maximum%20Count%20of%20Positive%20Integer%20and%20Negative%20Integer/2529.%20Maximum%20Count%20of%20Positive%20Integer%20and%20Negative%20Integer.md) |

## 03. Rotated Sorted Array

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [33. Search in Rotated Sorted Array](https://leetcode.com/problems/search-in-rotated-sorted-array/) | Medium | 3 months | 61.3 | ✅ Solved |  |  |  | [notes](03.%20Rotated%20Sorted%20Array/0033.%20Search%20in%20Rotated%20Sorted%20Array/0033.%20Search%20in%20Rotated%20Sorted%20Array.md) |
| 2 | [153. Find Minimum in Rotated Sorted Array](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/) | Medium | 6+ months | 32.8 | ✅ Solved |  |  |  | [notes](03.%20Rotated%20Sorted%20Array/0153.%20Find%20Minimum%20in%20Rotated%20Sorted%20Array/0153.%20Find%20Minimum%20in%20Rotated%20Sorted%20Array.md) |
| 3 | [81. Search in Rotated Sorted Array II](https://leetcode.com/problems/search-in-rotated-sorted-array-ii/) | Medium | 6+ months | 27.5 | Todo |  |  |  | [notes](03.%20Rotated%20Sorted%20Array/0081.%20Search%20in%20Rotated%20Sorted%20Array%20II/0081.%20Search%20in%20Rotated%20Sorted%20Array%20II.md) |
| 4 | [154. Find Minimum in Rotated Sorted Array II](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array-ii/) | Hard | 6+ months | 8.2 | Todo |  |  |  | [notes](03.%20Rotated%20Sorted%20Array/0154.%20Find%20Minimum%20in%20Rotated%20Sorted%20Array%20II/0154.%20Find%20Minimum%20in%20Rotated%20Sorted%20Array%20II.md) |

## 04. Binary Search on Answer

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [69. Sqrt(x)](https://leetcode.com/problems/sqrtx/) | Easy | 3 months | 49.1 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/0069.%20Sqrt%28x%29/0069.%20Sqrt%28x%29.md) |
| 2 | [441. Arranging Coins](https://leetcode.com/problems/arranging-coins/) | Easy | 3 months | 20.0 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/0441.%20Arranging%20Coins/0441.%20Arranging%20Coins.md) |
| 3 | [875. Koko Eating Bananas](https://leetcode.com/problems/koko-eating-bananas/) | Medium | 6 months | 56.1 | ✅ Solved |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/0875.%20Koko%20Eating%20Bananas/0875.%20Koko%20Eating%20Bananas.md) |
| 4 | [410. Split Array Largest Sum](https://leetcode.com/problems/split-array-largest-sum/) | Hard | 6 months | 51.5 | ✅ Solved |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/0410.%20Split%20Array%20Largest%20Sum/0410.%20Split%20Array%20Largest%20Sum.md) |
| 5 | [1011. Capacity To Ship Packages Within D Days](https://leetcode.com/problems/capacity-to-ship-packages-within-d-days/) | Medium | 6 months | 42.3 | ✅ Solved |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/1011.%20Capacity%20To%20Ship%20Packages%20Within%20D%20Days/1011.%20Capacity%20To%20Ship%20Packages%20Within%20D%20Days.md) |
| 6 | [1482. Minimum Number of Days to Make m Bouquets](https://leetcode.com/problems/minimum-number-of-days-to-make-m-bouquets/) | Medium | 6 months | 25.0 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/1482.%20Minimum%20Number%20of%20Days%20to%20Make%20m%20Bouquets/1482.%20Minimum%20Number%20of%20Days%20to%20Make%20m%20Bouquets.md) |
| 7 | [1283. Find the Smallest Divisor Given a Threshold](https://leetcode.com/problems/find-the-smallest-divisor-given-a-threshold/) | Medium | 6 months | 19.8 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/1283.%20Find%20the%20Smallest%20Divisor%20Given%20a%20Threshold/1283.%20Find%20the%20Smallest%20Divisor%20Given%20a%20Threshold.md) |
| 8 | [367. Valid Perfect Square](https://leetcode.com/problems/valid-perfect-square/) | Easy | 6 months | 9.3 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/0367.%20Valid%20Perfect%20Square/0367.%20Valid%20Perfect%20Square.md) |
| 9 | [1891. Cutting Ribbons](https://leetcode.com/problems/cutting-ribbons/) 🔒 | Medium | 6+ months | 25.4 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/1891.%20Cutting%20Ribbons/1891.%20Cutting%20Ribbons.md) |
| 10 | [2594. Minimum Time to Repair Cars](https://leetcode.com/problems/minimum-time-to-repair-cars/) | Medium | 6+ months | 14.1 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/2594.%20Minimum%20Time%20to%20Repair%20Cars/2594.%20Minimum%20Time%20to%20Repair%20Cars.md) |
| 11 | [1608. Special Array With X Elements Greater Than or Equal X](https://leetcode.com/problems/special-array-with-x-elements-greater-than-or-equal-x/) | Easy | 6+ months | 10.2 | ✅ Solved |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/1608.%20Special%20Array%20With%20X%20Elements%20Greater%20Than%20or%20Equal%20X/1608.%20Special%20Array%20With%20X%20Elements%20Greater%20Than%20or%20Equal%20X.md) |
| 12 | [2226. Maximum Candies Allocated to K Children](https://leetcode.com/problems/maximum-candies-allocated-to-k-children/) | Medium | 6+ months | 9.3 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/2226.%20Maximum%20Candies%20Allocated%20to%20K%20Children/2226.%20Maximum%20Candies%20Allocated%20to%20K%20Children.md) |
| 13 | [2187. Minimum Time to Complete Trips](https://leetcode.com/problems/minimum-time-to-complete-trips/) | Medium | 6+ months | 8.6 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/2187.%20Minimum%20Time%20to%20Complete%20Trips/2187.%20Minimum%20Time%20to%20Complete%20Trips.md) |
| 14 | [3453. Separate Squares I](https://leetcode.com/problems/separate-squares-i/) | Medium | 6+ months | 7.6 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/3453.%20Separate%20Squares%20I/3453.%20Separate%20Squares%20I.md) |
| 15 | [2616. Minimize the Maximum Difference of Pairs](https://leetcode.com/problems/minimize-the-maximum-difference-of-pairs/) | Medium | 6+ months | 7.1 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/2616.%20Minimize%20the%20Maximum%20Difference%20of%20Pairs/2616.%20Minimize%20the%20Maximum%20Difference%20of%20Pairs.md) |
| 16 | [1760. Minimum Limit of Balls in a Bag](https://leetcode.com/problems/minimum-limit-of-balls-in-a-bag/) | Medium | 6+ months | 5.7 | ✅ Solved |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/1760.%20Minimum%20Limit%20of%20Balls%20in%20a%20Bag/1760.%20Minimum%20Limit%20of%20Balls%20in%20a%20Bag.md) |
| 17 | [2560. House Robber IV](https://leetcode.com/problems/house-robber-iv/) | Medium | 6+ months | 5.4 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/2560.%20House%20Robber%20IV/2560.%20House%20Robber%20IV.md) |
| 18 | [668. Kth Smallest Number in Multiplication Table](https://leetcode.com/problems/kth-smallest-number-in-multiplication-table/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/0668.%20Kth%20Smallest%20Number%20in%20Multiplication%20Table/0668.%20Kth%20Smallest%20Number%20in%20Multiplication%20Table.md) |
| 19 | [878. Nth Magical Number](https://leetcode.com/problems/nth-magical-number/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/0878.%20Nth%20Magical%20Number/0878.%20Nth%20Magical%20Number.md) |
| 20 | [1552. Magnetic Force Between Two Balls](https://leetcode.com/problems/magnetic-force-between-two-balls/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/1552.%20Magnetic%20Force%20Between%20Two%20Balls/1552.%20Magnetic%20Force%20Between%20Two%20Balls.md) |
| 21 | [2071. Maximum Number of Tasks You Can Assign](https://leetcode.com/problems/maximum-number-of-tasks-you-can-assign/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/2071.%20Maximum%20Number%20of%20Tasks%20You%20Can%20Assign/2071.%20Maximum%20Number%20of%20Tasks%20You%20Can%20Assign.md) |
| 22 | [2141. Maximum Running Time of N Computers](https://leetcode.com/problems/maximum-running-time-of-n-computers/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/2141.%20Maximum%20Running%20Time%20of%20N%20Computers/2141.%20Maximum%20Running%20Time%20of%20N%20Computers.md) |
| 23 | [3296. Minimum Number of Seconds to Make Mountain Height Zero](https://leetcode.com/problems/minimum-number-of-seconds-to-make-mountain-height-zero/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/3296.%20Minimum%20Number%20of%20Seconds%20to%20Make%20Mountain%20Height%20Zero/3296.%20Minimum%20Number%20of%20Seconds%20to%20Make%20Mountain%20Height%20Zero.md) |
| 24 | [3932. Count K-th Roots in a Range](https://leetcode.com/problems/count-k-th-roots-in-a-range/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/3932.%20Count%20K-th%20Roots%20in%20a%20Range/3932.%20Count%20K-th%20Roots%20in%20a%20Range.md) |

## 05. Search in 2D Matrix

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [240. Search a 2D Matrix II](https://leetcode.com/problems/search-a-2d-matrix-ii/) | Medium | 6 months | 37.1 | Todo |  |  |  | [notes](05.%20Search%20in%202D%20Matrix/0240.%20Search%20a%202D%20Matrix%20II/0240.%20Search%20a%202D%20Matrix%20II.md) |
| 2 | [74. Search a 2D Matrix](https://leetcode.com/problems/search-a-2d-matrix/) | Medium | 6 months | 36.2 | ✅ Solved |  |  |  | [notes](05.%20Search%20in%202D%20Matrix/0074.%20Search%20a%202D%20Matrix/0074.%20Search%20a%202D%20Matrix.md) |
| 3 | [1351. Count Negative Numbers in a Sorted Matrix](https://leetcode.com/problems/count-negative-numbers-in-a-sorted-matrix/) | Easy | 6+ months | 14.4 | ✅ Solved |  |  |  | [notes](05.%20Search%20in%202D%20Matrix/1351.%20Count%20Negative%20Numbers%20in%20a%20Sorted%20Matrix/1351.%20Count%20Negative%20Numbers%20in%20a%20Sorted%20Matrix.md) |
| 4 | [1428. Leftmost Column with at Least a One](https://leetcode.com/problems/leftmost-column-with-at-least-a-one/) 🔒 | Medium | 6+ months | 36.9 | Todo |  |  |  | [notes](05.%20Search%20in%202D%20Matrix/1428.%20Leftmost%20Column%20with%20at%20Least%20a%20One/1428.%20Leftmost%20Column%20with%20at%20Least%20a%20One.md) |

## 06. Peak Finding

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [162. Find Peak Element](https://leetcode.com/problems/find-peak-element/) | Medium | 6 months | 83.3 | Todo |  |  |  | [notes](06.%20Peak%20Finding/0162.%20Find%20Peak%20Element/0162.%20Find%20Peak%20Element.md) |
| 2 | [852. Peak Index in a Mountain Array](https://leetcode.com/problems/peak-index-in-a-mountain-array/) | Medium | 6+ months | 37.6 | Todo |  |  |  | [notes](06.%20Peak%20Finding/0852.%20Peak%20Index%20in%20a%20Mountain%20Array/0852.%20Peak%20Index%20in%20a%20Mountain%20Array.md) |
| 3 | [1901. Find a Peak Element II](https://leetcode.com/problems/find-a-peak-element-ii/) | Medium | 6+ months | 15.2 | Todo |  |  |  | [notes](06.%20Peak%20Finding/1901.%20Find%20a%20Peak%20Element%20II/1901.%20Find%20a%20Peak%20Element%20II.md) |
| 4 | [1095. Find in Mountain Array](https://leetcode.com/problems/find-in-mountain-array/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20Peak%20Finding/1095.%20Find%20in%20Mountain%20Array/1095.%20Find%20in%20Mountain%20Array.md) |

## 07. Binary Search on Two Arrays

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [4. Median of Two Sorted Arrays](https://leetcode.com/problems/median-of-two-sorted-arrays/) | Hard | 30 days | 57.8 | Todo |  |  |  | [notes](07.%20Binary%20Search%20on%20Two%20Arrays/0004.%20Median%20of%20Two%20Sorted%20Arrays/0004.%20Median%20of%20Two%20Sorted%20Arrays.md) |
