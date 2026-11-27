# 16. Heap & Priority Queue

[Back to Facebook](../README.md) · [Back to DSA Notes](../../../README.md)

35 Meta (Facebook) problems: 5 Easy, 19 Medium, 11 Hard, in 6 sub-patterns.

## Sub-patterns

| # | Sub-pattern | Questions | Easy | Medium | Hard | Last 3 Months | Solved | Most Asked |
|:---:|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---|
| 01 | [Top K Elements](#01-top-k-elements) | 5 | 2 | 3 | 0 | 1 | 2 | 347. Top K Frequent Elements, 973. K Closest Points to Origin, 692. Top K Frequent Words |
| 02 | [K-Way Merge](#02-k-way-merge) | 6 | 0 | 3 | 3 | 0 | 0 | 23. Merge k Sorted Lists, 378. Kth Smallest Element in a Sorted Matrix, 1439. Find the Kth Smallest Sum of a Matrix With Sorted Rows |
| 03 | [Two Heaps (Median)](#03-two-heaps-median) | 3 | 0 | 0 | 3 | 0 | 0 | 480. Sliding Window Median, 295. Find Median from Data Stream, 2163. Minimum Difference in Sums After Removal of Elements |
| 04 | [Scheduling with Heap](#04-scheduling-with-heap) | 4 | 0 | 3 | 1 | 0 | 0 | 1353. Maximum Number of Events That Can Be Attended, 1882. Process Tasks Using Servers, 2402. Meeting Rooms III |
| 05 | [Kth Smallest or Largest](#05-kth-smallest-or-largest) | 3 | 1 | 2 | 0 | 1 | 2 | 215. Kth Largest Element in an Array, 703. Kth Largest Element in a Stream, 1985. Find the Kth Largest Integer in the Array |
| 06 | [Greedy with Heap](#06-greedy-with-heap) | 14 | 2 | 8 | 4 | 0 | 1 | 767. Reorganize String, 407. Trapping Rain Water II, 1792. Maximum Average Pass Ratio |

**Columns**

- **Last Asked**: most recent LeetCode window that lists the problem for Meta (30 days, 3 months, 6 months or 6+ months).
- **Frequency**: LeetCode frequency score (0-100) in the Meta "All" list.
- **Status**: your LeetCode status on the day this file was generated. 🔒 after a title means LeetCode Premium.
- **Logic / Key Idea, Time, Space**: fill these in as you solve. A rebuild keeps what you typed.
- **Notes**: link to the problem's notes file.

Inside each sub-pattern, rows are sorted by most recent window, then by frequency (highest first).

## 01. Top K Elements

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [347. Top K Frequent Elements](https://leetcode.com/problems/top-k-frequent-elements/) | Medium | 3 months | 81.7 | ✅ Solved |  |  |  | [notes](01.%20Top%20K%20Elements/0347.%20Top%20K%20Frequent%20Elements/0347.%20Top%20K%20Frequent%20Elements.md) |
| 2 | [973. K Closest Points to Origin](https://leetcode.com/problems/k-closest-points-to-origin/) | Medium | 6+ months | 76.0 | ✅ Solved |  |  |  | [notes](01.%20Top%20K%20Elements/0973.%20K%20Closest%20Points%20to%20Origin/0973.%20K%20Closest%20Points%20to%20Origin.md) |
| 3 | [692. Top K Frequent Words](https://leetcode.com/problems/top-k-frequent-words/) | Medium | 6+ months | 22.8 | Todo |  |  |  | [notes](01.%20Top%20K%20Elements/0692.%20Top%20K%20Frequent%20Words/0692.%20Top%20K%20Frequent%20Words.md) |
| 4 | [2099. Find Subsequence of Length K With the Largest Sum](https://leetcode.com/problems/find-subsequence-of-length-k-with-the-largest-sum/) | Easy | 6+ months | 11.5 | Todo |  |  |  | [notes](01.%20Top%20K%20Elements/2099.%20Find%20Subsequence%20of%20Length%20K%20With%20the%20Largest%20Sum/2099.%20Find%20Subsequence%20of%20Length%20K%20With%20the%20Largest%20Sum.md) |
| 5 | [1337. The K Weakest Rows in a Matrix](https://leetcode.com/problems/the-k-weakest-rows-in-a-matrix/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Top%20K%20Elements/1337.%20The%20K%20Weakest%20Rows%20in%20a%20Matrix/1337.%20The%20K%20Weakest%20Rows%20in%20a%20Matrix.md) |

## 02. K-Way Merge

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [23. Merge k Sorted Lists](https://leetcode.com/problems/merge-k-sorted-lists/) | Hard | 6 months | 74.5 | Todo |  |  |  | [notes](02.%20K-Way%20Merge/0023.%20Merge%20k%20Sorted%20Lists/0023.%20Merge%20k%20Sorted%20Lists.md) |
| 2 | [378. Kth Smallest Element in a Sorted Matrix](https://leetcode.com/problems/kth-smallest-element-in-a-sorted-matrix/) | Medium | 6+ months | 49.7 | Todo |  |  |  | [notes](02.%20K-Way%20Merge/0378.%20Kth%20Smallest%20Element%20in%20a%20Sorted%20Matrix/0378.%20Kth%20Smallest%20Element%20in%20a%20Sorted%20Matrix.md) |
| 3 | [373. Find K Pairs with Smallest Sums](https://leetcode.com/problems/find-k-pairs-with-smallest-sums/) | Medium | 6+ months | 21.4 | Todo |  |  |  | [notes](02.%20K-Way%20Merge/0373.%20Find%20K%20Pairs%20with%20Smallest%20Sums/0373.%20Find%20K%20Pairs%20with%20Smallest%20Sums.md) |
| 4 | [313. Super Ugly Number](https://leetcode.com/problems/super-ugly-number/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20K-Way%20Merge/0313.%20Super%20Ugly%20Number/0313.%20Super%20Ugly%20Number.md) |
| 5 | [632. Smallest Range Covering Elements from K Lists](https://leetcode.com/problems/smallest-range-covering-elements-from-k-lists/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20K-Way%20Merge/0632.%20Smallest%20Range%20Covering%20Elements%20from%20K%20Lists/0632.%20Smallest%20Range%20Covering%20Elements%20from%20K%20Lists.md) |
| 6 | [1439. Find the Kth Smallest Sum of a Matrix With Sorted Rows](https://leetcode.com/problems/find-the-kth-smallest-sum-of-a-matrix-with-sorted-rows/) | Hard | 6+ months | 37.0 | Todo |  |  |  | [notes](02.%20K-Way%20Merge/1439.%20Find%20the%20Kth%20Smallest%20Sum%20of%20a%20Matrix%20With%20Sorted%20Rows/1439.%20Find%20the%20Kth%20Smallest%20Sum%20of%20a%20Matrix%20With%20Sorted%20Rows.md) |

## 03. Two Heaps (Median)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [295. Find Median from Data Stream](https://leetcode.com/problems/find-median-from-data-stream/) | Hard | 6 months | 45.2 | Todo |  |  |  | [notes](03.%20Two%20Heaps%20%28Median%29/0295.%20Find%20Median%20from%20Data%20Stream/0295.%20Find%20Median%20from%20Data%20Stream.md) |
| 2 | [480. Sliding Window Median](https://leetcode.com/problems/sliding-window-median/) | Hard | 6+ months | 54.1 | Todo |  |  |  | [notes](03.%20Two%20Heaps%20%28Median%29/0480.%20Sliding%20Window%20Median/0480.%20Sliding%20Window%20Median.md) |
| 3 | [2163. Minimum Difference in Sums After Removal of Elements](https://leetcode.com/problems/minimum-difference-in-sums-after-removal-of-elements/) | Hard | 6+ months | 7.2 | Todo |  |  |  | [notes](03.%20Two%20Heaps%20%28Median%29/2163.%20Minimum%20Difference%20in%20Sums%20After%20Removal%20of%20Elements/2163.%20Minimum%20Difference%20in%20Sums%20After%20Removal%20of%20Elements.md) |

## 04. Scheduling with Heap

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [1353. Maximum Number of Events That Can Be Attended](https://leetcode.com/problems/maximum-number-of-events-that-can-be-attended/) | Medium | 6+ months | 12.3 | Todo |  |  |  | [notes](04.%20Scheduling%20with%20Heap/1353.%20Maximum%20Number%20of%20Events%20That%20Can%20Be%20Attended/1353.%20Maximum%20Number%20of%20Events%20That%20Can%20Be%20Attended.md) |
| 2 | [2402. Meeting Rooms III](https://leetcode.com/problems/meeting-rooms-iii/) | Hard | 6+ months | 6.4 | Todo |  |  |  | [notes](04.%20Scheduling%20with%20Heap/2402.%20Meeting%20Rooms%20III/2402.%20Meeting%20Rooms%20III.md) |
| 3 | [1834. Single-Threaded CPU](https://leetcode.com/problems/single-threaded-cpu/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Scheduling%20with%20Heap/1834.%20Single-Threaded%20CPU/1834.%20Single-Threaded%20CPU.md) |
| 4 | [1882. Process Tasks Using Servers](https://leetcode.com/problems/process-tasks-using-servers/) | Medium | 6+ months | 7.4 | Todo |  |  |  | [notes](04.%20Scheduling%20with%20Heap/1882.%20Process%20Tasks%20Using%20Servers/1882.%20Process%20Tasks%20Using%20Servers.md) |

## 05. Kth Smallest or Largest

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [215. Kth Largest Element in an Array](https://leetcode.com/problems/kth-largest-element-in-an-array/) | Medium | 3 months | 93.8 | ✅ Solved |  |  |  | [notes](05.%20Kth%20Smallest%20or%20Largest/0215.%20Kth%20Largest%20Element%20in%20an%20Array/0215.%20Kth%20Largest%20Element%20in%20an%20Array.md) |
| 2 | [703. Kth Largest Element in a Stream](https://leetcode.com/problems/kth-largest-element-in-a-stream/) | Easy | 6+ months | 42.4 | ✅ Solved |  |  |  | [notes](05.%20Kth%20Smallest%20or%20Largest/0703.%20Kth%20Largest%20Element%20in%20a%20Stream/0703.%20Kth%20Largest%20Element%20in%20a%20Stream.md) |
| 3 | [1985. Find the Kth Largest Integer in the Array](https://leetcode.com/problems/find-the-kth-largest-integer-in-the-array/) | Medium | 6+ months | 6.9 | Todo |  |  |  | [notes](05.%20Kth%20Smallest%20or%20Largest/1985.%20Find%20the%20Kth%20Largest%20Integer%20in%20the%20Array/1985.%20Find%20the%20Kth%20Largest%20Integer%20in%20the%20Array.md) |

## 06. Greedy with Heap

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [767. Reorganize String](https://leetcode.com/problems/reorganize-string/) | Medium | 6+ months | 14.6 | Todo |  |  |  | [notes](06.%20Greedy%20with%20Heap/0767.%20Reorganize%20String/0767.%20Reorganize%20String.md) |
| 2 | [407. Trapping Rain Water II](https://leetcode.com/problems/trapping-rain-water-ii/) | Hard | 6+ months | 13.2 | Todo |  |  |  | [notes](06.%20Greedy%20with%20Heap/0407.%20Trapping%20Rain%20Water%20II/0407.%20Trapping%20Rain%20Water%20II.md) |
| 3 | [1792. Maximum Average Pass Ratio](https://leetcode.com/problems/maximum-average-pass-ratio/) | Medium | 6+ months | 12.2 | Todo |  |  |  | [notes](06.%20Greedy%20with%20Heap/1792.%20Maximum%20Average%20Pass%20Ratio/1792.%20Maximum%20Average%20Pass%20Ratio.md) |
| 4 | [502. IPO](https://leetcode.com/problems/ipo/) | Hard | 6+ months | 5.7 | Todo |  |  |  | [notes](06.%20Greedy%20with%20Heap/0502.%20IPO/0502.%20IPO.md) |
| 5 | [1046. Last Stone Weight](https://leetcode.com/problems/last-stone-weight/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](06.%20Greedy%20with%20Heap/1046.%20Last%20Stone%20Weight/1046.%20Last%20Stone%20Weight.md) |
| 6 | [1054. Distant Barcodes](https://leetcode.com/problems/distant-barcodes/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20Greedy%20with%20Heap/1054.%20Distant%20Barcodes/1054.%20Distant%20Barcodes.md) |
| 7 | [1642. Furthest Building You Can Reach](https://leetcode.com/problems/furthest-building-you-can-reach/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20Greedy%20with%20Heap/1642.%20Furthest%20Building%20You%20Can%20Reach/1642.%20Furthest%20Building%20You%20Can%20Reach.md) |
| 8 | [2233. Maximum Product After K Increments](https://leetcode.com/problems/maximum-product-after-k-increments/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20Greedy%20with%20Heap/2233.%20Maximum%20Product%20After%20K%20Increments/2233.%20Maximum%20Product%20After%20K%20Increments.md) |
| 9 | [2503. Maximum Number of Points From Grid Queries](https://leetcode.com/problems/maximum-number-of-points-from-grid-queries/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20Greedy%20with%20Heap/2503.%20Maximum%20Number%20of%20Points%20From%20Grid%20Queries/2503.%20Maximum%20Number%20of%20Points%20From%20Grid%20Queries.md) |
| 10 | [2558. Take Gifts From the Richest Pile](https://leetcode.com/problems/take-gifts-from-the-richest-pile/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20Greedy%20with%20Heap/2558.%20Take%20Gifts%20From%20the%20Richest%20Pile/2558.%20Take%20Gifts%20From%20the%20Richest%20Pile.md) |
| 11 | [2593. Find Score of an Array After Marking All Elements](https://leetcode.com/problems/find-score-of-an-array-after-marking-all-elements/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20Greedy%20with%20Heap/2593.%20Find%20Score%20of%20an%20Array%20After%20Marking%20All%20Elements/2593.%20Find%20Score%20of%20an%20Array%20After%20Marking%20All%20Elements.md) |
| 12 | [3066. Minimum Operations to Exceed Threshold Value II](https://leetcode.com/problems/minimum-operations-to-exceed-threshold-value-ii/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20Greedy%20with%20Heap/3066.%20Minimum%20Operations%20to%20Exceed%20Threshold%20Value%20II/3066.%20Minimum%20Operations%20to%20Exceed%20Threshold%20Value%20II.md) |
| 13 | [3362. Zero Array Transformation III](https://leetcode.com/problems/zero-array-transformation-iii/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20Greedy%20with%20Heap/3362.%20Zero%20Array%20Transformation%20III/3362.%20Zero%20Array%20Transformation%20III.md) |
| 14 | [630. Course Schedule III](https://leetcode.com/problems/course-schedule-iii/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20Greedy%20with%20Heap/0630.%20Course%20Schedule%20III/0630.%20Course%20Schedule%20III.md) |
