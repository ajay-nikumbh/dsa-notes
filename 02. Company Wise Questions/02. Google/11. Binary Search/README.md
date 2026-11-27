# 11. Binary Search

[Back to Google](../README.md) · [Back to DSA Notes](../../../README.md)

81 Google problems: 13 Easy, 49 Medium, 19 Hard, in 7 sub-patterns.

## Sub-patterns

| # | Sub-pattern | Questions | Easy | Medium | Hard | Last 3 Months | Solved | Most Asked |
|:---:|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---|
| 01 | [Classic Binary Search](#01-classic-binary-search) | 5 | 2 | 3 | 0 | 1 | 3 | 540. Single Element in a Sorted Array, 704. Binary Search, 374. Guess Number Higher or Lower |
| 02 | [Lower & Upper Bound](#02-lower--upper-bound) | 19 | 6 | 13 | 0 | 4 | 4 | 34. Find First and Last Position of Element in Sorted Array, 35. Search Insert Position, 658. Find K Closest Elements |
| 03 | [Rotated Sorted Array](#03-rotated-sorted-array) | 4 | 0 | 3 | 1 | 2 | 2 | 33. Search in Rotated Sorted Array, 153. Find Minimum in Rotated Sorted Array, 81. Search in Rotated Sorted Array II |
| 04 | [Binary Search on Answer](#04-binary-search-on-answer) | 44 | 4 | 25 | 15 | 4 | 5 | 875. Koko Eating Bananas, 410. Split Array Largest Sum, 69. Sqrt(x) |
| 05 | [Search in 2D Matrix](#05-search-in-2d-matrix) | 4 | 1 | 2 | 1 | 2 | 2 | 240. Search a 2D Matrix II, 74. Search a 2D Matrix, 302. Smallest Rectangle Enclosing Black Pixels |
| 06 | [Peak Finding](#06-peak-finding) | 4 | 0 | 3 | 1 | 1 | 0 | 162. Find Peak Element, 852. Peak Index in a Mountain Array, 1095. Find in Mountain Array |
| 07 | [Binary Search on Two Arrays](#07-binary-search-on-two-arrays) | 1 | 0 | 0 | 1 | 1 | 0 | 4. Median of Two Sorted Arrays |

**Columns**

- **Last Asked**: most recent LeetCode window that lists the problem for Google (30 days, 3 months, 6 months, 6+ months).
- **Frequency**: LeetCode frequency score (0-100) in the Google "All" list.
- **Status**: your LeetCode status on the day this file was generated. 🔒 after a title means LeetCode Premium.
- **Logic / Key Idea, Time, Space**: fill these in as you solve. A rebuild keeps what you typed.
- **Notes**: link to the problem's notes file.

Inside each sub-pattern, rows are sorted by most recent window, then by frequency (highest first).

## 01. Classic Binary Search

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [704. Binary Search](https://leetcode.com/problems/binary-search/) | Easy | 3 months | 44.6 | ✅ Solved |  |  |  | [notes](01.%20Classic%20Binary%20Search/0704.%20Binary%20Search/0704.%20Binary%20Search.md) |
| 2 | [540. Single Element in a Sorted Array](https://leetcode.com/problems/single-element-in-a-sorted-array/) | Medium | 6 months | 49.8 | ✅ Solved |  |  |  | [notes](01.%20Classic%20Binary%20Search/0540.%20Single%20Element%20in%20a%20Sorted%20Array/0540.%20Single%20Element%20in%20a%20Sorted%20Array.md) |
| 3 | [374. Guess Number Higher or Lower](https://leetcode.com/problems/guess-number-higher-or-lower/) | Easy | 6 months | 31.2 | ✅ Solved |  |  |  | [notes](01.%20Classic%20Binary%20Search/0374.%20Guess%20Number%20Higher%20or%20Lower/0374.%20Guess%20Number%20Higher%20or%20Lower.md) |
| 4 | [702. Search in a Sorted Array of Unknown Size](https://leetcode.com/problems/search-in-a-sorted-array-of-unknown-size/) 🔒 | Medium | 6+ months | 30.2 | Todo |  |  |  | [notes](01.%20Classic%20Binary%20Search/0702.%20Search%20in%20a%20Sorted%20Array%20of%20Unknown%20Size/0702.%20Search%20in%20a%20Sorted%20Array%20of%20Unknown%20Size.md) |
| 5 | [2936. Number of Equal Numbers Blocks](https://leetcode.com/problems/number-of-equal-numbers-blocks/) 🔒 | Medium | 6+ months | 28.8 | Todo |  |  |  | [notes](01.%20Classic%20Binary%20Search/2936.%20Number%20of%20Equal%20Numbers%20Blocks/2936.%20Number%20of%20Equal%20Numbers%20Blocks.md) |

## 02. Lower & Upper Bound

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [34. Find First and Last Position of Element in Sorted Array](https://leetcode.com/problems/find-first-and-last-position-of-element-in-sorted-array/) | Medium | 3 months | 52.8 | Todo |  |  |  | [notes](02.%20Lower%20%26%20Upper%20Bound/0034.%20Find%20First%20and%20Last%20Position%20of%20Element%20in%20Sorted%20Array/0034.%20Find%20First%20and%20Last%20Position%20of%20Element%20in%20Sorted%20Array.md) |
| 2 | [35. Search Insert Position](https://leetcode.com/problems/search-insert-position/) | Easy | 3 months | 49.0 | ✅ Solved |  |  |  | [notes](02.%20Lower%20%26%20Upper%20Bound/0035.%20Search%20Insert%20Position/0035.%20Search%20Insert%20Position.md) |
| 3 | [1539. Kth Missing Positive Number](https://leetcode.com/problems/kth-missing-positive-number/) | Easy | 3 months | 37.8 | Todo |  |  |  | [notes](02.%20Lower%20%26%20Upper%20Bound/1539.%20Kth%20Missing%20Positive%20Number/1539.%20Kth%20Missing%20Positive%20Number.md) |
| 4 | [278. First Bad Version](https://leetcode.com/problems/first-bad-version/) | Easy | 3 months | 32.9 | ✅ Solved |  |  |  | [notes](02.%20Lower%20%26%20Upper%20Bound/0278.%20First%20Bad%20Version/0278.%20First%20Bad%20Version.md) |
| 5 | [658. Find K Closest Elements](https://leetcode.com/problems/find-k-closest-elements/) | Medium | 6 months | 41.6 | Todo |  |  |  | [notes](02.%20Lower%20%26%20Upper%20Bound/0658.%20Find%20K%20Closest%20Elements/0658.%20Find%20K%20Closest%20Elements.md) |
| 6 | [475. Heaters](https://leetcode.com/problems/heaters/) | Medium | 6+ months | 34.5 | Todo |  |  |  | [notes](02.%20Lower%20%26%20Upper%20Bound/0475.%20Heaters/0475.%20Heaters.md) |
| 7 | [744. Find Smallest Letter Greater Than Target](https://leetcode.com/problems/find-smallest-letter-greater-than-target/) | Easy | 6+ months | 15.2 | ✅ Solved |  |  |  | [notes](02.%20Lower%20%26%20Upper%20Bound/0744.%20Find%20Smallest%20Letter%20Greater%20Than%20Target/0744.%20Find%20Smallest%20Letter%20Greater%20Than%20Target.md) |
| 8 | [2300. Successful Pairs of Spells and Potions](https://leetcode.com/problems/successful-pairs-of-spells-and-potions/) | Medium | 6+ months | 11.7 | Todo |  |  |  | [notes](02.%20Lower%20%26%20Upper%20Bound/2300.%20Successful%20Pairs%20of%20Spells%20and%20Potions/2300.%20Successful%20Pairs%20of%20Spells%20and%20Potions.md) |
| 9 | [275. H-Index II](https://leetcode.com/problems/h-index-ii/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Lower%20%26%20Upper%20Bound/0275.%20H-Index%20II/0275.%20H-Index%20II.md) |
| 10 | [436. Find Right Interval](https://leetcode.com/problems/find-right-interval/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Lower%20%26%20Upper%20Bound/0436.%20Find%20Right%20Interval/0436.%20Find%20Right%20Interval.md) |
| 11 | [1060. Missing Element in Sorted Array](https://leetcode.com/problems/missing-element-in-sorted-array/) 🔒 | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Lower%20%26%20Upper%20Bound/1060.%20Missing%20Element%20in%20Sorted%20Array/1060.%20Missing%20Element%20in%20Sorted%20Array.md) |
| 12 | [1712. Ways to Split Array Into Three Subarrays](https://leetcode.com/problems/ways-to-split-array-into-three-subarrays/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Lower%20%26%20Upper%20Bound/1712.%20Ways%20to%20Split%20Array%20Into%20Three%20Subarrays/1712.%20Ways%20to%20Split%20Array%20Into%20Three%20Subarrays.md) |
| 13 | [2389. Longest Subsequence With Limited Sum](https://leetcode.com/problems/longest-subsequence-with-limited-sum/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Lower%20%26%20Upper%20Bound/2389.%20Longest%20Subsequence%20With%20Limited%20Sum/2389.%20Longest%20Subsequence%20With%20Limited%20Sum.md) |
| 14 | [2529. Maximum Count of Positive Integer and Negative Integer](https://leetcode.com/problems/maximum-count-of-positive-integer-and-negative-integer/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](02.%20Lower%20%26%20Upper%20Bound/2529.%20Maximum%20Count%20of%20Positive%20Integer%20and%20Negative%20Integer/2529.%20Maximum%20Count%20of%20Positive%20Integer%20and%20Negative%20Integer.md) |
| 15 | [3488. Closest Equal Element Queries](https://leetcode.com/problems/closest-equal-element-queries/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Lower%20%26%20Upper%20Bound/3488.%20Closest%20Equal%20Element%20Queries/3488.%20Closest%20Equal%20Element%20Queries.md) |
| 16 | [1170. Compare Strings by Frequency of the Smallest Character](https://leetcode.com/problems/compare-strings-by-frequency-of-the-smallest-character/) | Medium | 6+ months | 28.8 | Todo |  |  |  | [notes](02.%20Lower%20%26%20Upper%20Bound/1170.%20Compare%20Strings%20by%20Frequency%20of%20the%20Smallest%20Character/1170.%20Compare%20Strings%20by%20Frequency%20of%20the%20Smallest%20Character.md) |
| 17 | [4053. Minimum Operations to Make Every Element Palindromic](https://leetcode.com/problems/minimum-operations-to-make-every-element-palindromic/) | Medium | 6+ months | 28.8 | Todo |  |  |  | [notes](02.%20Lower%20%26%20Upper%20Bound/4053.%20Minimum%20Operations%20to%20Make%20Every%20Element%20Palindromic/4053.%20Minimum%20Operations%20to%20Make%20Every%20Element%20Palindromic.md) |
| 18 | [1818. Minimum Absolute Sum Difference](https://leetcode.com/problems/minimum-absolute-sum-difference/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Lower%20%26%20Upper%20Bound/1818.%20Minimum%20Absolute%20Sum%20Difference/1818.%20Minimum%20Absolute%20Sum%20Difference.md) |
| 19 | [2250. Count Number of Rectangles Containing Each Point](https://leetcode.com/problems/count-number-of-rectangles-containing-each-point/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Lower%20%26%20Upper%20Bound/2250.%20Count%20Number%20of%20Rectangles%20Containing%20Each%20Point/2250.%20Count%20Number%20of%20Rectangles%20Containing%20Each%20Point.md) |

## 03. Rotated Sorted Array

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [33. Search in Rotated Sorted Array](https://leetcode.com/problems/search-in-rotated-sorted-array/) | Medium | 3 months | 62.2 | ✅ Solved |  |  |  | [notes](03.%20Rotated%20Sorted%20Array/0033.%20Search%20in%20Rotated%20Sorted%20Array/0033.%20Search%20in%20Rotated%20Sorted%20Array.md) |
| 2 | [153. Find Minimum in Rotated Sorted Array](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/) | Medium | 3 months | 38.3 | ✅ Solved |  |  |  | [notes](03.%20Rotated%20Sorted%20Array/0153.%20Find%20Minimum%20in%20Rotated%20Sorted%20Array/0153.%20Find%20Minimum%20in%20Rotated%20Sorted%20Array.md) |
| 3 | [81. Search in Rotated Sorted Array II](https://leetcode.com/problems/search-in-rotated-sorted-array-ii/) | Medium | 6 months | 29.1 | Todo |  |  |  | [notes](03.%20Rotated%20Sorted%20Array/0081.%20Search%20in%20Rotated%20Sorted%20Array%20II/0081.%20Search%20in%20Rotated%20Sorted%20Array%20II.md) |
| 4 | [154. Find Minimum in Rotated Sorted Array II](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array-ii/) | Hard | 6 months | 21.3 | Todo |  |  |  | [notes](03.%20Rotated%20Sorted%20Array/0154.%20Find%20Minimum%20in%20Rotated%20Sorted%20Array%20II/0154.%20Find%20Minimum%20in%20Rotated%20Sorted%20Array%20II.md) |

## 04. Binary Search on Answer

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [875. Koko Eating Bananas](https://leetcode.com/problems/koko-eating-bananas/) | Medium | 30 days | 61.6 | ✅ Solved |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/0875.%20Koko%20Eating%20Bananas/0875.%20Koko%20Eating%20Bananas.md) |
| 2 | [69. Sqrt(x)](https://leetcode.com/problems/sqrtx/) | Easy | 30 days | 48.8 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/0069.%20Sqrt%28x%29/0069.%20Sqrt%28x%29.md) |
| 3 | [410. Split Array Largest Sum](https://leetcode.com/problems/split-array-largest-sum/) | Hard | 3 months | 59.5 | ✅ Solved |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/0410.%20Split%20Array%20Largest%20Sum/0410.%20Split%20Array%20Largest%20Sum.md) |
| 4 | [1011. Capacity To Ship Packages Within D Days](https://leetcode.com/problems/capacity-to-ship-packages-within-d-days/) | Medium | 3 months | 48.0 | ✅ Solved |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/1011.%20Capacity%20To%20Ship%20Packages%20Within%20D%20Days/1011.%20Capacity%20To%20Ship%20Packages%20Within%20D%20Days.md) |
| 5 | [1482. Minimum Number of Days to Make m Bouquets](https://leetcode.com/problems/minimum-number-of-days-to-make-m-bouquets/) | Medium | 6 months | 43.8 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/1482.%20Minimum%20Number%20of%20Days%20to%20Make%20m%20Bouquets/1482.%20Minimum%20Number%20of%20Days%20to%20Make%20m%20Bouquets.md) |
| 6 | [2226. Maximum Candies Allocated to K Children](https://leetcode.com/problems/maximum-candies-allocated-to-k-children/) | Medium | 6 months | 39.2 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/2226.%20Maximum%20Candies%20Allocated%20to%20K%20Children/2226.%20Maximum%20Candies%20Allocated%20to%20K%20Children.md) |
| 7 | [367. Valid Perfect Square](https://leetcode.com/problems/valid-perfect-square/) | Easy | 6 months | 18.1 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/0367.%20Valid%20Perfect%20Square/0367.%20Valid%20Perfect%20Square.md) |
| 8 | [1552. Magnetic Force Between Two Balls](https://leetcode.com/problems/magnetic-force-between-two-balls/) | Medium | 6 months | 13.3 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/1552.%20Magnetic%20Force%20Between%20Two%20Balls/1552.%20Magnetic%20Force%20Between%20Two%20Balls.md) |
| 9 | [2187. Minimum Time to Complete Trips](https://leetcode.com/problems/minimum-time-to-complete-trips/) | Medium | 6 months | 10.9 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/2187.%20Minimum%20Time%20to%20Complete%20Trips/2187.%20Minimum%20Time%20to%20Complete%20Trips.md) |
| 10 | [1760. Minimum Limit of Balls in a Bag](https://leetcode.com/problems/minimum-limit-of-balls-in-a-bag/) | Medium | 6 months | 5.0 | ✅ Solved |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/1760.%20Minimum%20Limit%20of%20Balls%20in%20a%20Bag/1760.%20Minimum%20Limit%20of%20Balls%20in%20a%20Bag.md) |
| 11 | [2064. Minimized Maximum of Products Distributed to Any Store](https://leetcode.com/problems/minimized-maximum-of-products-distributed-to-any-store/) | Medium | 6 months | 5.0 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/2064.%20Minimized%20Maximum%20of%20Products%20Distributed%20to%20Any%20Store/2064.%20Minimized%20Maximum%20of%20Products%20Distributed%20to%20Any%20Store.md) |
| 12 | [3453. Separate Squares I](https://leetcode.com/problems/separate-squares-i/) | Medium | 6+ months | 46.8 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/3453.%20Separate%20Squares%20I/3453.%20Separate%20Squares%20I.md) |
| 13 | [774. Minimize Max Distance to Gas Station](https://leetcode.com/problems/minimize-max-distance-to-gas-station/) 🔒 | Hard | 6+ months | 31.9 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/0774.%20Minimize%20Max%20Distance%20to%20Gas%20Station/0774.%20Minimize%20Max%20Distance%20to%20Gas%20Station.md) |
| 14 | [1300. Sum of Mutated Array Closest to Target](https://leetcode.com/problems/sum-of-mutated-array-closest-to-target/) | Medium | 6+ months | 30.0 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/1300.%20Sum%20of%20Mutated%20Array%20Closest%20to%20Target/1300.%20Sum%20of%20Mutated%20Array%20Closest%20to%20Target.md) |
| 15 | [3007. Maximum Number That Sum of the Prices Is Less Than or Equal to K](https://leetcode.com/problems/maximum-number-that-sum-of-the-prices-is-less-than-or-equal-to-k/) | Medium | 6+ months | 29.9 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/3007.%20Maximum%20Number%20That%20Sum%20of%20the%20Prices%20Is%20Less%20Than%20or%20Equal%20to%20K/3007.%20Maximum%20Number%20That%20Sum%20of%20the%20Prices%20Is%20Less%20Than%20or%20Equal%20to%20K.md) |
| 16 | [1891. Cutting Ribbons](https://leetcode.com/problems/cutting-ribbons/) 🔒 | Medium | 6+ months | 29.4 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/1891.%20Cutting%20Ribbons/1891.%20Cutting%20Ribbons.md) |
| 17 | [1608. Special Array With X Elements Greater Than or Equal X](https://leetcode.com/problems/special-array-with-x-elements-greater-than-or-equal-x/) | Easy | 6+ months | 29.3 | ✅ Solved |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/1608.%20Special%20Array%20With%20X%20Elements%20Greater%20Than%20or%20Equal%20X/1608.%20Special%20Array%20With%20X%20Elements%20Greater%20Than%20or%20Equal%20X.md) |
| 18 | [1283. Find the Smallest Divisor Given a Threshold](https://leetcode.com/problems/find-the-smallest-divisor-given-a-threshold/) | Medium | 6+ months | 25.6 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/1283.%20Find%20the%20Smallest%20Divisor%20Given%20a%20Threshold/1283.%20Find%20the%20Smallest%20Divisor%20Given%20a%20Threshold.md) |
| 19 | [2616. Minimize the Maximum Difference of Pairs](https://leetcode.com/problems/minimize-the-maximum-difference-of-pairs/) | Medium | 6+ months | 14.6 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/2616.%20Minimize%20the%20Maximum%20Difference%20of%20Pairs/2616.%20Minimize%20the%20Maximum%20Difference%20of%20Pairs.md) |
| 20 | [2594. Minimum Time to Repair Cars](https://leetcode.com/problems/minimum-time-to-repair-cars/) | Medium | 6+ months | 13.5 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/2594.%20Minimum%20Time%20to%20Repair%20Cars/2594.%20Minimum%20Time%20to%20Repair%20Cars.md) |
| 21 | [2141. Maximum Running Time of N Computers](https://leetcode.com/problems/maximum-running-time-of-n-computers/) | Hard | 6+ months | 11.2 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/2141.%20Maximum%20Running%20Time%20of%20N%20Computers/2141.%20Maximum%20Running%20Time%20of%20N%20Computers.md) |
| 22 | [1802. Maximum Value at a Given Index in a Bounded Array](https://leetcode.com/problems/maximum-value-at-a-given-index-in-a-bounded-array/) | Medium | 6+ months | 8.8 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/1802.%20Maximum%20Value%20at%20a%20Given%20Index%20in%20a%20Bounded%20Array/1802.%20Maximum%20Value%20at%20a%20Given%20Index%20in%20a%20Bounded%20Array.md) |
| 23 | [3419. Minimize the Maximum Edge Weight of Graph](https://leetcode.com/problems/minimize-the-maximum-edge-weight-of-graph/) | Medium | 6+ months | 8.8 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/3419.%20Minimize%20the%20Maximum%20Edge%20Weight%20of%20Graph/3419.%20Minimize%20the%20Maximum%20Edge%20Weight%20of%20Graph.md) |
| 24 | [441. Arranging Coins](https://leetcode.com/problems/arranging-coins/) | Easy | 6+ months | 8.2 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/0441.%20Arranging%20Coins/0441.%20Arranging%20Coins.md) |
| 25 | [878. Nth Magical Number](https://leetcode.com/problems/nth-magical-number/) | Hard | 6+ months | 8.2 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/0878.%20Nth%20Magical%20Number/0878.%20Nth%20Magical%20Number.md) |
| 26 | [2560. House Robber IV](https://leetcode.com/problems/house-robber-iv/) | Medium | 6+ months | 7.7 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/2560.%20House%20Robber%20IV/2560.%20House%20Robber%20IV.md) |
| 27 | [2040. Kth Smallest Product of Two Sorted Arrays](https://leetcode.com/problems/kth-smallest-product-of-two-sorted-arrays/) | Hard | 6+ months | 7.3 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/2040.%20Kth%20Smallest%20Product%20of%20Two%20Sorted%20Arrays/2040.%20Kth%20Smallest%20Product%20of%20Two%20Sorted%20Arrays.md) |
| 28 | [3464. Maximize the Distance Between Points on a Square](https://leetcode.com/problems/maximize-the-distance-between-points-on-a-square/) | Hard | 6+ months | 6.5 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/3464.%20Maximize%20the%20Distance%20Between%20Points%20on%20a%20Square/3464.%20Maximize%20the%20Distance%20Between%20Points%20on%20a%20Square.md) |
| 29 | [2528. Maximize the Minimum Powered City](https://leetcode.com/problems/maximize-the-minimum-powered-city/) | Hard | 6+ months | 5.1 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/2528.%20Maximize%20the%20Minimum%20Powered%20City/2528.%20Maximize%20the%20Minimum%20Powered%20City.md) |
| 30 | [2071. Maximum Number of Tasks You Can Assign](https://leetcode.com/problems/maximum-number-of-tasks-you-can-assign/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/2071.%20Maximum%20Number%20of%20Tasks%20You%20Can%20Assign/2071.%20Maximum%20Number%20of%20Tasks%20You%20Can%20Assign.md) |
| 31 | [2448. Minimum Cost to Make Array Equal](https://leetcode.com/problems/minimum-cost-to-make-array-equal/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/2448.%20Minimum%20Cost%20to%20Make%20Array%20Equal/2448.%20Minimum%20Cost%20to%20Make%20Array%20Equal.md) |
| 32 | [3296. Minimum Number of Seconds to Make Mountain Height Zero](https://leetcode.com/problems/minimum-number-of-seconds-to-make-mountain-height-zero/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/3296.%20Minimum%20Number%20of%20Seconds%20to%20Make%20Mountain%20Height%20Zero/3296.%20Minimum%20Number%20of%20Seconds%20to%20Make%20Mountain%20Height%20Zero.md) |
| 33 | [3398. Smallest Substring With Identical Characters I](https://leetcode.com/problems/smallest-substring-with-identical-characters-i/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/3398.%20Smallest%20Substring%20With%20Identical%20Characters%20I/3398.%20Smallest%20Substring%20With%20Identical%20Characters%20I.md) |
| 34 | [3710. Maximum Partition Factor](https://leetcode.com/problems/maximum-partition-factor/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/3710.%20Maximum%20Partition%20Factor/3710.%20Maximum%20Partition%20Factor.md) |
| 35 | [3733. Minimum Time to Complete All Deliveries](https://leetcode.com/problems/minimum-time-to-complete-all-deliveries/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/3733.%20Minimum%20Time%20to%20Complete%20All%20Deliveries/3733.%20Minimum%20Time%20to%20Complete%20All%20Deliveries.md) |
| 36 | [3824. Minimum K to Reduce Array Within Limit](https://leetcode.com/problems/minimum-k-to-reduce-array-within-limit/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/3824.%20Minimum%20K%20to%20Reduce%20Array%20Within%20Limit/3824.%20Minimum%20K%20to%20Reduce%20Array%20Within%20Limit.md) |
| 37 | [3932. Count K-th Roots in a Range](https://leetcode.com/problems/count-k-th-roots-in-a-range/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/3932.%20Count%20K-th%20Roots%20in%20a%20Range/3932.%20Count%20K-th%20Roots%20in%20a%20Range.md) |
| 38 | [719. Find K-th Smallest Pair Distance](https://leetcode.com/problems/find-k-th-smallest-pair-distance/) | Hard | 6+ months | 31.4 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/0719.%20Find%20K-th%20Smallest%20Pair%20Distance/0719.%20Find%20K-th%20Smallest%20Pair%20Distance.md) |
| 39 | [1918. Kth Smallest Subarray Sum](https://leetcode.com/problems/kth-smallest-subarray-sum/) 🔒 | Medium | 6+ months | 30.7 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/1918.%20Kth%20Smallest%20Subarray%20Sum/1918.%20Kth%20Smallest%20Subarray%20Sum.md) |
| 40 | [668. Kth Smallest Number in Multiplication Table](https://leetcode.com/problems/kth-smallest-number-in-multiplication-table/) | Hard | 6+ months | 29.3 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/0668.%20Kth%20Smallest%20Number%20in%20Multiplication%20Table/0668.%20Kth%20Smallest%20Number%20in%20Multiplication%20Table.md) |
| 41 | [644. Maximum Average Subarray II](https://leetcode.com/problems/maximum-average-subarray-ii/) 🔒 | Hard | 6+ months | 28.8 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/0644.%20Maximum%20Average%20Subarray%20II/0644.%20Maximum%20Average%20Subarray%20II.md) |
| 42 | [1231. Divide Chocolate](https://leetcode.com/problems/divide-chocolate/) 🔒 | Hard | 6+ months | 28.8 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/1231.%20Divide%20Chocolate/1231.%20Divide%20Chocolate.md) |
| 43 | [1618. Maximum Font to Fit a Sentence in a Screen](https://leetcode.com/problems/maximum-font-to-fit-a-sentence-in-a-screen/) 🔒 | Medium | 6+ months | 28.8 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/1618.%20Maximum%20Font%20to%20Fit%20a%20Sentence%20in%20a%20Screen/1618.%20Maximum%20Font%20to%20Fit%20a%20Sentence%20in%20a%20Screen.md) |
| 44 | [1870. Minimum Speed to Arrive on Time](https://leetcode.com/problems/minimum-speed-to-arrive-on-time/) | Medium | 6+ months | 28.8 | Todo |  |  |  | [notes](04.%20Binary%20Search%20on%20Answer/1870.%20Minimum%20Speed%20to%20Arrive%20on%20Time/1870.%20Minimum%20Speed%20to%20Arrive%20on%20Time.md) |

## 05. Search in 2D Matrix

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [74. Search a 2D Matrix](https://leetcode.com/problems/search-a-2d-matrix/) | Medium | 3 months | 39.5 | ✅ Solved |  |  |  | [notes](05.%20Search%20in%202D%20Matrix/0074.%20Search%20a%202D%20Matrix/0074.%20Search%20a%202D%20Matrix.md) |
| 2 | [302. Smallest Rectangle Enclosing Black Pixels](https://leetcode.com/problems/smallest-rectangle-enclosing-black-pixels/) 🔒 | Hard | 3 months | 34.4 | Todo |  |  |  | [notes](05.%20Search%20in%202D%20Matrix/0302.%20Smallest%20Rectangle%20Enclosing%20Black%20Pixels/0302.%20Smallest%20Rectangle%20Enclosing%20Black%20Pixels.md) |
| 3 | [240. Search a 2D Matrix II](https://leetcode.com/problems/search-a-2d-matrix-ii/) | Medium | 6 months | 47.3 | Todo |  |  |  | [notes](05.%20Search%20in%202D%20Matrix/0240.%20Search%20a%202D%20Matrix%20II/0240.%20Search%20a%202D%20Matrix%20II.md) |
| 4 | [1351. Count Negative Numbers in a Sorted Matrix](https://leetcode.com/problems/count-negative-numbers-in-a-sorted-matrix/) | Easy | 6+ months | 9.9 | ✅ Solved |  |  |  | [notes](05.%20Search%20in%202D%20Matrix/1351.%20Count%20Negative%20Numbers%20in%20a%20Sorted%20Matrix/1351.%20Count%20Negative%20Numbers%20in%20a%20Sorted%20Matrix.md) |

## 06. Peak Finding

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [162. Find Peak Element](https://leetcode.com/problems/find-peak-element/) | Medium | 3 months | 59.8 | Todo |  |  |  | [notes](06.%20Peak%20Finding/0162.%20Find%20Peak%20Element/0162.%20Find%20Peak%20Element.md) |
| 2 | [852. Peak Index in a Mountain Array](https://leetcode.com/problems/peak-index-in-a-mountain-array/) | Medium | 6 months | 45.1 | Todo |  |  |  | [notes](06.%20Peak%20Finding/0852.%20Peak%20Index%20in%20a%20Mountain%20Array/0852.%20Peak%20Index%20in%20a%20Mountain%20Array.md) |
| 3 | [1095. Find in Mountain Array](https://leetcode.com/problems/find-in-mountain-array/) | Hard | 6+ months | 35.4 | Todo |  |  |  | [notes](06.%20Peak%20Finding/1095.%20Find%20in%20Mountain%20Array/1095.%20Find%20in%20Mountain%20Array.md) |
| 4 | [1901. Find a Peak Element II](https://leetcode.com/problems/find-a-peak-element-ii/) | Medium | 6+ months | 9.2 | Todo |  |  |  | [notes](06.%20Peak%20Finding/1901.%20Find%20a%20Peak%20Element%20II/1901.%20Find%20a%20Peak%20Element%20II.md) |

## 07. Binary Search on Two Arrays

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [4. Median of Two Sorted Arrays](https://leetcode.com/problems/median-of-two-sorted-arrays/) | Hard | 30 days | 71.5 | Todo |  |  |  | [notes](07.%20Binary%20Search%20on%20Two%20Arrays/0004.%20Median%20of%20Two%20Sorted%20Arrays/0004.%20Median%20of%20Two%20Sorted%20Arrays.md) |
