# 22. Advanced Data Structures

[Back to Google](../README.md) · [Back to DSA Notes](../../../README.md)

39 Google problems: 0 Easy, 6 Medium, 33 Hard, in 4 sub-patterns.

## Sub-patterns

| # | Sub-pattern | Questions | Easy | Medium | Hard | Last 3 Months | Solved | Most Asked |
|:---:|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---|
| 01 | [Segment Tree](#01-segment-tree) | 14 | 0 | 2 | 12 | 1 | 0 | 2407. Longest Increasing Subsequence II, 2158. Amount of New Area Painted Each Day, 2286. Booking Concert Tickets in Groups |
| 02 | [Binary Indexed Tree (Fenwick)](#02-binary-indexed-tree-fenwick) | 6 | 0 | 1 | 5 | 0 | 0 | 308. Range Sum Query 2D - Mutable, 2179. Count Good Triplets in an Array, 2659. Make Array Empty |
| 03 | [Ordered Set & TreeMap](#03-ordered-set--treemap) | 12 | 0 | 3 | 9 | 1 | 0 | 975. Odd Even Jump, 715. Range Module, 729. My Calendar I |
| 04 | [Sparse Table & Binary Lifting](#04-sparse-table--binary-lifting) | 7 | 0 | 0 | 7 | 1 | 0 | 1483. Kth Ancestor of a Tree Node, 3534. Path Existence Queries in a Graph II, 3559. Number of Ways to Assign Edge Weights II |

**Columns**

- **Last Asked**: most recent LeetCode window that lists the problem for Google (30 days, 3 months, 6 months, 6+ months).
- **Frequency**: LeetCode frequency score (0-100) in the Google "All" list.
- **Status**: your LeetCode status on the day this file was generated. 🔒 after a title means LeetCode Premium.
- **Logic / Key Idea, Time, Space**: fill these in as you solve. A rebuild keeps what you typed.
- **Notes**: link to the problem's notes file.

Inside each sub-pattern, rows are sorted by most recent window, then by frequency (highest first).

## 01. Segment Tree

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [2916. Subarrays Distinct Element Sum of Squares II](https://leetcode.com/problems/subarrays-distinct-element-sum-of-squares-ii/) | Hard | 3 months | 6.7 | Todo |  |  |  | [notes](01.%20Segment%20Tree/2916.%20Subarrays%20Distinct%20Element%20Sum%20of%20Squares%20II/2916.%20Subarrays%20Distinct%20Element%20Sum%20of%20Squares%20II.md) |
| 2 | [2407. Longest Increasing Subsequence II](https://leetcode.com/problems/longest-increasing-subsequence-ii/) | Hard | 6 months | 32.5 | Todo |  |  |  | [notes](01.%20Segment%20Tree/2407.%20Longest%20Increasing%20Subsequence%20II/2407.%20Longest%20Increasing%20Subsequence%20II.md) |
| 3 | [3479. Fruits Into Baskets III](https://leetcode.com/problems/fruits-into-baskets-iii/) | Medium | 6 months | 14.6 | Todo |  |  |  | [notes](01.%20Segment%20Tree/3479.%20Fruits%20Into%20Baskets%20III/3479.%20Fruits%20Into%20Baskets%20III.md) |
| 4 | [3525. Find X Value of Array II](https://leetcode.com/problems/find-x-value-of-array-ii/) | Hard | 6 months | 7.3 | Todo |  |  |  | [notes](01.%20Segment%20Tree/3525.%20Find%20X%20Value%20of%20Array%20II/3525.%20Find%20X%20Value%20of%20Array%20II.md) |
| 5 | [2213. Longest Substring of One Repeating Character](https://leetcode.com/problems/longest-substring-of-one-repeating-character/) | Hard | 6 months | 5.0 | Todo |  |  |  | [notes](01.%20Segment%20Tree/2213.%20Longest%20Substring%20of%20One%20Repeating%20Character/2213.%20Longest%20Substring%20of%20One%20Repeating%20Character.md) |
| 6 | [3161. Block Placement Queries](https://leetcode.com/problems/block-placement-queries/) | Hard | 6+ months | 13.8 | Todo |  |  |  | [notes](01.%20Segment%20Tree/3161.%20Block%20Placement%20Queries/3161.%20Block%20Placement%20Queries.md) |
| 7 | [3454. Separate Squares II](https://leetcode.com/problems/separate-squares-ii/) | Hard | 6+ months | 13.6 | Todo |  |  |  | [notes](01.%20Segment%20Tree/3454.%20Separate%20Squares%20II/3454.%20Separate%20Squares%20II.md) |
| 8 | [3721. Longest Balanced Subarray II](https://leetcode.com/problems/longest-balanced-subarray-ii/) | Hard | 6+ months | 13.6 | Todo |  |  |  | [notes](01.%20Segment%20Tree/3721.%20Longest%20Balanced%20Subarray%20II/3721.%20Longest%20Balanced%20Subarray%20II.md) |
| 9 | [307. Range Sum Query - Mutable](https://leetcode.com/problems/range-sum-query-mutable/) | Medium | 6+ months | 6.4 | Todo |  |  |  | [notes](01.%20Segment%20Tree/0307.%20Range%20Sum%20Query%20-%20Mutable/0307.%20Range%20Sum%20Query%20-%20Mutable.md) |
| 10 | [3165. Maximum Sum of Subsequence With Non-adjacent Elements](https://leetcode.com/problems/maximum-sum-of-subsequence-with-non-adjacent-elements/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Segment%20Tree/3165.%20Maximum%20Sum%20of%20Subsequence%20With%20Non-adjacent%20Elements/3165.%20Maximum%20Sum%20of%20Subsequence%20With%20Non-adjacent%20Elements.md) |
| 11 | [3410. Maximize Subarray Sum After Removing All Occurrences of One Element](https://leetcode.com/problems/maximize-subarray-sum-after-removing-all-occurrences-of-one-element/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Segment%20Tree/3410.%20Maximize%20Subarray%20Sum%20After%20Removing%20All%20Occurrences%20of%20One%20Element/3410.%20Maximize%20Subarray%20Sum%20After%20Removing%20All%20Occurrences%20of%20One%20Element.md) |
| 12 | [3569. Maximize Count of Distinct Primes After Split](https://leetcode.com/problems/maximize-count-of-distinct-primes-after-split/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Segment%20Tree/3569.%20Maximize%20Count%20of%20Distinct%20Primes%20After%20Split/3569.%20Maximize%20Count%20of%20Distinct%20Primes%20After%20Split.md) |
| 13 | [2158. Amount of New Area Painted Each Day](https://leetcode.com/problems/amount-of-new-area-painted-each-day/) 🔒 | Hard | 6+ months | 28.8 | Todo |  |  |  | [notes](01.%20Segment%20Tree/2158.%20Amount%20of%20New%20Area%20Painted%20Each%20Day/2158.%20Amount%20of%20New%20Area%20Painted%20Each%20Day.md) |
| 14 | [2286. Booking Concert Tickets in Groups](https://leetcode.com/problems/booking-concert-tickets-in-groups/) | Hard | 6+ months | 28.8 | Todo |  |  |  | [notes](01.%20Segment%20Tree/2286.%20Booking%20Concert%20Tickets%20in%20Groups/2286.%20Booking%20Concert%20Tickets%20in%20Groups.md) |

## 02. Binary Indexed Tree (Fenwick)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [308. Range Sum Query 2D - Mutable](https://leetcode.com/problems/range-sum-query-2d-mutable/) 🔒 | Medium | 6+ months | 33.0 | Todo |  |  |  | [notes](02.%20Binary%20Indexed%20Tree%20%28Fenwick%29/0308.%20Range%20Sum%20Query%202D%20-%20Mutable/0308.%20Range%20Sum%20Query%202D%20-%20Mutable.md) |
| 2 | [2179. Count Good Triplets in an Array](https://leetcode.com/problems/count-good-triplets-in-an-array/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Binary%20Indexed%20Tree%20%28Fenwick%29/2179.%20Count%20Good%20Triplets%20in%20an%20Array/2179.%20Count%20Good%20Triplets%20in%20an%20Array.md) |
| 3 | [2659. Make Array Empty](https://leetcode.com/problems/make-array-empty/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Binary%20Indexed%20Tree%20%28Fenwick%29/2659.%20Make%20Array%20Empty/2659.%20Make%20Array%20Empty.md) |
| 4 | [3072. Distribute Elements Into Two Arrays II](https://leetcode.com/problems/distribute-elements-into-two-arrays-ii/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Binary%20Indexed%20Tree%20%28Fenwick%29/3072.%20Distribute%20Elements%20Into%20Two%20Arrays%20II/3072.%20Distribute%20Elements%20Into%20Two%20Arrays%20II.md) |
| 5 | [3382. Maximum Area Rectangle With Point Constraints II](https://leetcode.com/problems/maximum-area-rectangle-with-point-constraints-ii/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Binary%20Indexed%20Tree%20%28Fenwick%29/3382.%20Maximum%20Area%20Rectangle%20With%20Point%20Constraints%20II/3382.%20Maximum%20Area%20Rectangle%20With%20Point%20Constraints%20II.md) |
| 6 | [3671. Sum of Beautiful Subsequences](https://leetcode.com/problems/sum-of-beautiful-subsequences/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Binary%20Indexed%20Tree%20%28Fenwick%29/3671.%20Sum%20of%20Beautiful%20Subsequences/3671.%20Sum%20of%20Beautiful%20Subsequences.md) |

## 03. Ordered Set & TreeMap

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [715. Range Module](https://leetcode.com/problems/range-module/) | Hard | 3 months | 39.5 | Todo |  |  |  | [notes](03.%20Ordered%20Set%20%26%20TreeMap/0715.%20Range%20Module/0715.%20Range%20Module.md) |
| 2 | [975. Odd Even Jump](https://leetcode.com/problems/odd-even-jump/) | Hard | 6 months | 39.7 | Todo |  |  |  | [notes](03.%20Ordered%20Set%20%26%20TreeMap/0975.%20Odd%20Even%20Jump/0975.%20Odd%20Even%20Jump.md) |
| 3 | [729. My Calendar I](https://leetcode.com/problems/my-calendar-i/) | Medium | 6+ months | 34.5 | Todo |  |  |  | [notes](03.%20Ordered%20Set%20%26%20TreeMap/0729.%20My%20Calendar%20I/0729.%20My%20Calendar%20I.md) |
| 4 | [363. Max Sum of Rectangle No Larger Than K](https://leetcode.com/problems/max-sum-of-rectangle-no-larger-than-k/) | Hard | 6+ months | 32.5 | Todo |  |  |  | [notes](03.%20Ordered%20Set%20%26%20TreeMap/0363.%20Max%20Sum%20of%20Rectangle%20No%20Larger%20Than%20K/0363.%20Max%20Sum%20of%20Rectangle%20No%20Larger%20Than%20K.md) |
| 5 | [1488. Avoid Flood in The City](https://leetcode.com/problems/avoid-flood-in-the-city/) | Medium | 6+ months | 30.7 | Todo |  |  |  | [notes](03.%20Ordered%20Set%20%26%20TreeMap/1488.%20Avoid%20Flood%20in%20The%20City/1488.%20Avoid%20Flood%20in%20The%20City.md) |
| 6 | [352. Data Stream as Disjoint Intervals](https://leetcode.com/problems/data-stream-as-disjoint-intervals/) | Hard | 6+ months | 7.0 | Todo |  |  |  | [notes](03.%20Ordered%20Set%20%26%20TreeMap/0352.%20Data%20Stream%20as%20Disjoint%20Intervals/0352.%20Data%20Stream%20as%20Disjoint%20Intervals.md) |
| 7 | [2276. Count Integers in Intervals](https://leetcode.com/problems/count-integers-in-intervals/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](03.%20Ordered%20Set%20%26%20TreeMap/2276.%20Count%20Integers%20in%20Intervals/2276.%20Count%20Integers%20in%20Intervals.md) |
| 8 | [3013. Divide an Array Into Subarrays With Minimum Cost II](https://leetcode.com/problems/divide-an-array-into-subarrays-with-minimum-cost-ii/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](03.%20Ordered%20Set%20%26%20TreeMap/3013.%20Divide%20an%20Array%20Into%20Subarrays%20With%20Minimum%20Cost%20II/3013.%20Divide%20an%20Array%20Into%20Subarrays%20With%20Minimum%20Cost%20II.md) |
| 9 | [3321. Find X-Sum of All K-Long Subarrays II](https://leetcode.com/problems/find-x-sum-of-all-k-long-subarrays-ii/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](03.%20Ordered%20Set%20%26%20TreeMap/3321.%20Find%20X-Sum%20of%20All%20K-Long%20Subarrays%20II/3321.%20Find%20X-Sum%20of%20All%20K-Long%20Subarrays%20II.md) |
| 10 | [3510. Minimum Pair Removal to Sort Array II](https://leetcode.com/problems/minimum-pair-removal-to-sort-array-ii/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](03.%20Ordered%20Set%20%26%20TreeMap/3510.%20Minimum%20Pair%20Removal%20to%20Sort%20Array%20II/3510.%20Minimum%20Pair%20Removal%20to%20Sort%20Array%20II.md) |
| 11 | [2817. Minimum Absolute Difference Between Elements With Constraint](https://leetcode.com/problems/minimum-absolute-difference-between-elements-with-constraint/) | Medium | 6+ months | 28.8 | Todo |  |  |  | [notes](03.%20Ordered%20Set%20%26%20TreeMap/2817.%20Minimum%20Absolute%20Difference%20Between%20Elements%20With%20Constraint/2817.%20Minimum%20Absolute%20Difference%20Between%20Elements%20With%20Constraint.md) |
| 12 | [3636. Threshold Majority Queries](https://leetcode.com/problems/threshold-majority-queries/) | Hard | 6+ months | 28.8 | Todo |  |  |  | [notes](03.%20Ordered%20Set%20%26%20TreeMap/3636.%20Threshold%20Majority%20Queries/3636.%20Threshold%20Majority%20Queries.md) |

## 04. Sparse Table & Binary Lifting

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [1483. Kth Ancestor of a Tree Node](https://leetcode.com/problems/kth-ancestor-of-a-tree-node/) | Hard | 3 months | 36.9 | Todo |  |  |  | [notes](04.%20Sparse%20Table%20%26%20Binary%20Lifting/1483.%20Kth%20Ancestor%20of%20a%20Tree%20Node/1483.%20Kth%20Ancestor%20of%20a%20Tree%20Node.md) |
| 2 | [3534. Path Existence Queries in a Graph II](https://leetcode.com/problems/path-existence-queries-in-a-graph-ii/) | Hard | 6 months | 18.3 | Todo |  |  |  | [notes](04.%20Sparse%20Table%20%26%20Binary%20Lifting/3534.%20Path%20Existence%20Queries%20in%20a%20Graph%20II/3534.%20Path%20Existence%20Queries%20in%20a%20Graph%20II.md) |
| 3 | [3559. Number of Ways to Assign Edge Weights II](https://leetcode.com/problems/number-of-ways-to-assign-edge-weights-ii/) | Hard | 6 months | 10.1 | Todo |  |  |  | [notes](04.%20Sparse%20Table%20%26%20Binary%20Lifting/3559.%20Number%20of%20Ways%20to%20Assign%20Edge%20Weights%20II/3559.%20Number%20of%20Ways%20to%20Assign%20Edge%20Weights%20II.md) |
| 4 | [3501. Maximize Active Section with Trade II](https://leetcode.com/problems/maximize-active-section-with-trade-ii/) | Hard | 6 months | 6.7 | Todo |  |  |  | [notes](04.%20Sparse%20Table%20%26%20Binary%20Lifting/3501.%20Maximize%20Active%20Section%20with%20Trade%20II/3501.%20Maximize%20Active%20Section%20with%20Trade%20II.md) |
| 5 | [3691. Maximum Total Subarray Value II](https://leetcode.com/problems/maximum-total-subarray-value-ii/) | Hard | 6 months | 5.0 | Todo |  |  |  | [notes](04.%20Sparse%20Table%20%26%20Binary%20Lifting/3691.%20Maximum%20Total%20Subarray%20Value%20II/3691.%20Maximum%20Total%20Subarray%20Value%20II.md) |
| 6 | [3585. Find Weighted Median Node in Tree](https://leetcode.com/problems/find-weighted-median-node-in-tree/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Sparse%20Table%20%26%20Binary%20Lifting/3585.%20Find%20Weighted%20Median%20Node%20in%20Tree/3585.%20Find%20Weighted%20Median%20Node%20in%20Tree.md) |
| 7 | [3841. Palindromic Path Queries in a Tree](https://leetcode.com/problems/palindromic-path-queries-in-a-tree/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Sparse%20Table%20%26%20Binary%20Lifting/3841.%20Palindromic%20Path%20Queries%20in%20a%20Tree/3841.%20Palindromic%20Path%20Queries%20in%20a%20Tree.md) |
