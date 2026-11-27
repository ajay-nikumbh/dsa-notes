# 16. Heap & Priority Queue

[Back to Google](../README.md) · [Back to DSA Notes](../../../README.md)

49 Google problems: 5 Easy, 27 Medium, 17 Hard, in 6 sub-patterns.

## Sub-patterns

| # | Sub-pattern | Questions | Easy | Medium | Hard | Last 3 Months | Solved | Most Asked |
|:---:|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---|
| 01 | [Top K Elements](#01-top-k-elements) | 5 | 2 | 3 | 0 | 1 | 2 | 347. Top K Frequent Elements, 692. Top K Frequent Words, 973. K Closest Points to Origin |
| 02 | [K-Way Merge](#02-k-way-merge) | 6 | 0 | 4 | 2 | 1 | 0 | 23. Merge k Sorted Lists, 373. Find K Pairs with Smallest Sums, 378. Kth Smallest Element in a Sorted Matrix |
| 03 | [Two Heaps (Median)](#03-two-heaps-median) | 3 | 0 | 0 | 3 | 0 | 0 | 295. Find Median from Data Stream, 480. Sliding Window Median, 2163. Minimum Difference in Sums After Removal of Elements |
| 04 | [Scheduling with Heap](#04-scheduling-with-heap) | 6 | 0 | 4 | 2 | 4 | 0 | 2402. Meeting Rooms III, 1834. Single-Threaded CPU, 1851. Minimum Interval to Include Each Query |
| 05 | [Kth Smallest or Largest](#05-kth-smallest-or-largest) | 5 | 1 | 3 | 1 | 1 | 2 | 215. Kth Largest Element in an Array, 703. Kth Largest Element in a Stream, 3935. Power Update After K-th Largest Insertion I |
| 06 | [Greedy with Heap](#06-greedy-with-heap) | 24 | 2 | 13 | 9 | 2 | 2 | 407. Trapping Rain Water II, 857. Minimum Cost to Hire K Workers, 358. Rearrange String k Distance Apart |

**Columns**

- **Last Asked**: most recent LeetCode window that lists the problem for Google (30 days, 3 months, 6 months, 6+ months).
- **Frequency**: LeetCode frequency score (0-100) in the Google "All" list.
- **Status**: your LeetCode status on the day this file was generated. 🔒 after a title means LeetCode Premium.
- **Logic / Key Idea, Time, Space**: fill these in as you solve. A rebuild keeps what you typed.
- **Notes**: link to the problem's notes file.

Inside each sub-pattern, rows are sorted by most recent window, then by frequency (highest first).

## 01. Top K Elements

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [347. Top K Frequent Elements](https://leetcode.com/problems/top-k-frequent-elements/) | Medium | 3 months | 65.1 | ✅ Solved |  |  |  | [notes](01.%20Top%20K%20Elements/0347.%20Top%20K%20Frequent%20Elements/0347.%20Top%20K%20Frequent%20Elements.md) |
| 2 | [692. Top K Frequent Words](https://leetcode.com/problems/top-k-frequent-words/) | Medium | 6 months | 30.5 | Todo |  |  |  | [notes](01.%20Top%20K%20Elements/0692.%20Top%20K%20Frequent%20Words/0692.%20Top%20K%20Frequent%20Words.md) |
| 3 | [973. K Closest Points to Origin](https://leetcode.com/problems/k-closest-points-to-origin/) | Medium | 6+ months | 15.5 | ✅ Solved |  |  |  | [notes](01.%20Top%20K%20Elements/0973.%20K%20Closest%20Points%20to%20Origin/0973.%20K%20Closest%20Points%20to%20Origin.md) |
| 4 | [1337. The K Weakest Rows in a Matrix](https://leetcode.com/problems/the-k-weakest-rows-in-a-matrix/) | Easy | 6+ months | 5.5 | Todo |  |  |  | [notes](01.%20Top%20K%20Elements/1337.%20The%20K%20Weakest%20Rows%20in%20a%20Matrix/1337.%20The%20K%20Weakest%20Rows%20in%20a%20Matrix.md) |
| 5 | [2099. Find Subsequence of Length K With the Largest Sum](https://leetcode.com/problems/find-subsequence-of-length-k-with-the-largest-sum/) | Easy | 6+ months | 5.3 | Todo |  |  |  | [notes](01.%20Top%20K%20Elements/2099.%20Find%20Subsequence%20of%20Length%20K%20With%20the%20Largest%20Sum/2099.%20Find%20Subsequence%20of%20Length%20K%20With%20the%20Largest%20Sum.md) |

## 02. K-Way Merge

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [23. Merge k Sorted Lists](https://leetcode.com/problems/merge-k-sorted-lists/) | Hard | 3 months | 54.2 | Todo |  |  |  | [notes](02.%20K-Way%20Merge/0023.%20Merge%20k%20Sorted%20Lists/0023.%20Merge%20k%20Sorted%20Lists.md) |
| 2 | [373. Find K Pairs with Smallest Sums](https://leetcode.com/problems/find-k-pairs-with-smallest-sums/) | Medium | 6 months | 40.8 | Todo |  |  |  | [notes](02.%20K-Way%20Merge/0373.%20Find%20K%20Pairs%20with%20Smallest%20Sums/0373.%20Find%20K%20Pairs%20with%20Smallest%20Sums.md) |
| 3 | [378. Kth Smallest Element in a Sorted Matrix](https://leetcode.com/problems/kth-smallest-element-in-a-sorted-matrix/) | Medium | 6 months | 35.0 | Todo |  |  |  | [notes](02.%20K-Way%20Merge/0378.%20Kth%20Smallest%20Element%20in%20a%20Sorted%20Matrix/0378.%20Kth%20Smallest%20Element%20in%20a%20Sorted%20Matrix.md) |
| 4 | [632. Smallest Range Covering Elements from K Lists](https://leetcode.com/problems/smallest-range-covering-elements-from-k-lists/) | Hard | 6 months | 6.8 | Todo |  |  |  | [notes](02.%20K-Way%20Merge/0632.%20Smallest%20Range%20Covering%20Elements%20from%20K%20Lists/0632.%20Smallest%20Range%20Covering%20Elements%20from%20K%20Lists.md) |
| 5 | [313. Super Ugly Number](https://leetcode.com/problems/super-ugly-number/) | Medium | 6+ months | 30.3 | Todo |  |  |  | [notes](02.%20K-Way%20Merge/0313.%20Super%20Ugly%20Number/0313.%20Super%20Ugly%20Number.md) |
| 6 | [1508. Range Sum of Sorted Subarray Sums](https://leetcode.com/problems/range-sum-of-sorted-subarray-sums/) | Medium | 6+ months | 30.1 | Todo |  |  |  | [notes](02.%20K-Way%20Merge/1508.%20Range%20Sum%20of%20Sorted%20Subarray%20Sums/1508.%20Range%20Sum%20of%20Sorted%20Subarray%20Sums.md) |

## 03. Two Heaps (Median)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [295. Find Median from Data Stream](https://leetcode.com/problems/find-median-from-data-stream/) | Hard | 6 months | 52.9 | Todo |  |  |  | [notes](03.%20Two%20Heaps%20%28Median%29/0295.%20Find%20Median%20from%20Data%20Stream/0295.%20Find%20Median%20from%20Data%20Stream.md) |
| 2 | [480. Sliding Window Median](https://leetcode.com/problems/sliding-window-median/) | Hard | 6+ months | 36.7 | Todo |  |  |  | [notes](03.%20Two%20Heaps%20%28Median%29/0480.%20Sliding%20Window%20Median/0480.%20Sliding%20Window%20Median.md) |
| 3 | [2163. Minimum Difference in Sums After Removal of Elements](https://leetcode.com/problems/minimum-difference-in-sums-after-removal-of-elements/) | Hard | 6+ months | 7.0 | Todo |  |  |  | [notes](03.%20Two%20Heaps%20%28Median%29/2163.%20Minimum%20Difference%20in%20Sums%20After%20Removal%20of%20Elements/2163.%20Minimum%20Difference%20in%20Sums%20After%20Removal%20of%20Elements.md) |

## 04. Scheduling with Heap

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [1882. Process Tasks Using Servers](https://leetcode.com/problems/process-tasks-using-servers/) | Medium | 30 days | 16.9 | Todo |  |  |  | [notes](04.%20Scheduling%20with%20Heap/1882.%20Process%20Tasks%20Using%20Servers/1882.%20Process%20Tasks%20Using%20Servers.md) |
| 2 | [2402. Meeting Rooms III](https://leetcode.com/problems/meeting-rooms-iii/) | Hard | 3 months | 46.8 | Todo |  |  |  | [notes](04.%20Scheduling%20with%20Heap/2402.%20Meeting%20Rooms%20III/2402.%20Meeting%20Rooms%20III.md) |
| 3 | [1353. Maximum Number of Events That Can Be Attended](https://leetcode.com/problems/maximum-number-of-events-that-can-be-attended/) | Medium | 3 months | 29.9 | Todo |  |  |  | [notes](04.%20Scheduling%20with%20Heap/1353.%20Maximum%20Number%20of%20Events%20That%20Can%20Be%20Attended/1353.%20Maximum%20Number%20of%20Events%20That%20Can%20Be%20Attended.md) |
| 4 | [1801. Number of Orders in the Backlog](https://leetcode.com/problems/number-of-orders-in-the-backlog/) | Medium | 3 months | 5.0 | Todo |  |  |  | [notes](04.%20Scheduling%20with%20Heap/1801.%20Number%20of%20Orders%20in%20the%20Backlog/1801.%20Number%20of%20Orders%20in%20the%20Backlog.md) |
| 5 | [1834. Single-Threaded CPU](https://leetcode.com/problems/single-threaded-cpu/) | Medium | 6 months | 40.6 | Todo |  |  |  | [notes](04.%20Scheduling%20with%20Heap/1834.%20Single-Threaded%20CPU/1834.%20Single-Threaded%20CPU.md) |
| 6 | [1851. Minimum Interval to Include Each Query](https://leetcode.com/problems/minimum-interval-to-include-each-query/) | Hard | 6 months | 36.4 | Todo |  |  |  | [notes](04.%20Scheduling%20with%20Heap/1851.%20Minimum%20Interval%20to%20Include%20Each%20Query/1851.%20Minimum%20Interval%20to%20Include%20Each%20Query.md) |

## 05. Kth Smallest or Largest

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [215. Kth Largest Element in an Array](https://leetcode.com/problems/kth-largest-element-in-an-array/) | Medium | 3 months | 56.5 | ✅ Solved |  |  |  | [notes](05.%20Kth%20Smallest%20or%20Largest/0215.%20Kth%20Largest%20Element%20in%20an%20Array/0215.%20Kth%20Largest%20Element%20in%20an%20Array.md) |
| 2 | [703. Kth Largest Element in a Stream](https://leetcode.com/problems/kth-largest-element-in-a-stream/) | Easy | 6 months | 34.5 | ✅ Solved |  |  |  | [notes](05.%20Kth%20Smallest%20or%20Largest/0703.%20Kth%20Largest%20Element%20in%20a%20Stream/0703.%20Kth%20Largest%20Element%20in%20a%20Stream.md) |
| 3 | [2386. Find the K-Sum of an Array](https://leetcode.com/problems/find-the-k-sum-of-an-array/) | Hard | 6+ months | 5.7 | Todo |  |  |  | [notes](05.%20Kth%20Smallest%20or%20Largest/2386.%20Find%20the%20K-Sum%20of%20an%20Array/2386.%20Find%20the%20K-Sum%20of%20an%20Array.md) |
| 4 | [3935. Power Update After K-th Largest Insertion I](https://leetcode.com/problems/power-update-after-k-th-largest-insertion-i/) 🔒 | Medium | 6+ months | 28.8 | Todo |  |  |  | [notes](05.%20Kth%20Smallest%20or%20Largest/3935.%20Power%20Update%20After%20K-th%20Largest%20Insertion%20I/3935.%20Power%20Update%20After%20K-th%20Largest%20Insertion%20I.md) |
| 5 | [1845. Seat Reservation Manager](https://leetcode.com/problems/seat-reservation-manager/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Kth%20Smallest%20or%20Largest/1845.%20Seat%20Reservation%20Manager/1845.%20Seat%20Reservation%20Manager.md) |

## 06. Greedy with Heap

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [1046. Last Stone Weight](https://leetcode.com/problems/last-stone-weight/) | Easy | 3 months | 19.9 | ✅ Solved |  |  |  | [notes](06.%20Greedy%20with%20Heap/1046.%20Last%20Stone%20Weight/1046.%20Last%20Stone%20Weight.md) |
| 2 | [1405. Longest Happy String](https://leetcode.com/problems/longest-happy-string/) | Medium | 3 months | 5.0 | Todo |  |  |  | [notes](06.%20Greedy%20with%20Heap/1405.%20Longest%20Happy%20String/1405.%20Longest%20Happy%20String.md) |
| 3 | [767. Reorganize String](https://leetcode.com/problems/reorganize-string/) | Medium | 6 months | 31.0 | Todo |  |  |  | [notes](06.%20Greedy%20with%20Heap/0767.%20Reorganize%20String/0767.%20Reorganize%20String.md) |
| 4 | [502. IPO](https://leetcode.com/problems/ipo/) | Hard | 6 months | 17.6 | Todo |  |  |  | [notes](06.%20Greedy%20with%20Heap/0502.%20IPO/0502.%20IPO.md) |
| 5 | [407. Trapping Rain Water II](https://leetcode.com/problems/trapping-rain-water-ii/) | Hard | 6+ months | 40.3 | Todo |  |  |  | [notes](06.%20Greedy%20with%20Heap/0407.%20Trapping%20Rain%20Water%20II/0407.%20Trapping%20Rain%20Water%20II.md) |
| 6 | [857. Minimum Cost to Hire K Workers](https://leetcode.com/problems/minimum-cost-to-hire-k-workers/) | Hard | 6+ months | 32.0 | ✅ Solved |  |  |  | [notes](06.%20Greedy%20with%20Heap/0857.%20Minimum%20Cost%20to%20Hire%20K%20Workers/0857.%20Minimum%20Cost%20to%20Hire%20K%20Workers.md) |
| 7 | [1642. Furthest Building You Can Reach](https://leetcode.com/problems/furthest-building-you-can-reach/) | Medium | 6+ months | 31.4 | Todo |  |  |  | [notes](06.%20Greedy%20with%20Heap/1642.%20Furthest%20Building%20You%20Can%20Reach/1642.%20Furthest%20Building%20You%20Can%20Reach.md) |
| 8 | [871. Minimum Number of Refueling Stops](https://leetcode.com/problems/minimum-number-of-refueling-stops/) | Hard | 6+ months | 8.7 | Todo |  |  |  | [notes](06.%20Greedy%20with%20Heap/0871.%20Minimum%20Number%20of%20Refueling%20Stops/0871.%20Minimum%20Number%20of%20Refueling%20Stops.md) |
| 9 | [2542. Maximum Subsequence Score](https://leetcode.com/problems/maximum-subsequence-score/) | Medium | 6+ months | 6.6 | Todo |  |  |  | [notes](06.%20Greedy%20with%20Heap/2542.%20Maximum%20Subsequence%20Score/2542.%20Maximum%20Subsequence%20Score.md) |
| 10 | [1383. Maximum Performance of a Team](https://leetcode.com/problems/maximum-performance-of-a-team/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20Greedy%20with%20Heap/1383.%20Maximum%20Performance%20of%20a%20Team/1383.%20Maximum%20Performance%20of%20a%20Team.md) |
| 11 | [1792. Maximum Average Pass Ratio](https://leetcode.com/problems/maximum-average-pass-ratio/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20Greedy%20with%20Heap/1792.%20Maximum%20Average%20Pass%20Ratio/1792.%20Maximum%20Average%20Pass%20Ratio.md) |
| 12 | [2182. Construct String With Repeat Limit](https://leetcode.com/problems/construct-string-with-repeat-limit/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20Greedy%20with%20Heap/2182.%20Construct%20String%20With%20Repeat%20Limit/2182.%20Construct%20String%20With%20Repeat%20Limit.md) |
| 13 | [2233. Maximum Product After K Increments](https://leetcode.com/problems/maximum-product-after-k-increments/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20Greedy%20with%20Heap/2233.%20Maximum%20Product%20After%20K%20Increments/2233.%20Maximum%20Product%20After%20K%20Increments.md) |
| 14 | [2503. Maximum Number of Points From Grid Queries](https://leetcode.com/problems/maximum-number-of-points-from-grid-queries/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20Greedy%20with%20Heap/2503.%20Maximum%20Number%20of%20Points%20From%20Grid%20Queries/2503.%20Maximum%20Number%20of%20Points%20From%20Grid%20Queries.md) |
| 15 | [2558. Take Gifts From the Richest Pile](https://leetcode.com/problems/take-gifts-from-the-richest-pile/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20Greedy%20with%20Heap/2558.%20Take%20Gifts%20From%20the%20Richest%20Pile/2558.%20Take%20Gifts%20From%20the%20Richest%20Pile.md) |
| 16 | [2593. Find Score of an Array After Marking All Elements](https://leetcode.com/problems/find-score-of-an-array-after-marking-all-elements/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20Greedy%20with%20Heap/2593.%20Find%20Score%20of%20an%20Array%20After%20Marking%20All%20Elements/2593.%20Find%20Score%20of%20an%20Array%20After%20Marking%20All%20Elements.md) |
| 17 | [3066. Minimum Operations to Exceed Threshold Value II](https://leetcode.com/problems/minimum-operations-to-exceed-threshold-value-ii/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20Greedy%20with%20Heap/3066.%20Minimum%20Operations%20to%20Exceed%20Threshold%20Value%20II/3066.%20Minimum%20Operations%20to%20Exceed%20Threshold%20Value%20II.md) |
| 18 | [3362. Zero Array Transformation III](https://leetcode.com/problems/zero-array-transformation-iii/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20Greedy%20with%20Heap/3362.%20Zero%20Array%20Transformation%20III/3362.%20Zero%20Array%20Transformation%20III.md) |
| 19 | [358. Rearrange String k Distance Apart](https://leetcode.com/problems/rearrange-string-k-distance-apart/) 🔒 | Hard | 6+ months | 31.7 | Todo |  |  |  | [notes](06.%20Greedy%20with%20Heap/0358.%20Rearrange%20String%20k%20Distance%20Apart/0358.%20Rearrange%20String%20k%20Distance%20Apart.md) |
| 20 | [1167. Minimum Cost to Connect Sticks](https://leetcode.com/problems/minimum-cost-to-connect-sticks/) 🔒 | Medium | 6+ months | 29.7 | Todo |  |  |  | [notes](06.%20Greedy%20with%20Heap/1167.%20Minimum%20Cost%20to%20Connect%20Sticks/1167.%20Minimum%20Cost%20to%20Connect%20Sticks.md) |
| 21 | [1199. Minimum Time to Build Blocks](https://leetcode.com/problems/minimum-time-to-build-blocks/) 🔒 | Hard | 6+ months | 28.8 | Todo |  |  |  | [notes](06.%20Greedy%20with%20Heap/1199.%20Minimum%20Time%20to%20Build%20Blocks/1199.%20Minimum%20Time%20to%20Build%20Blocks.md) |
| 22 | [1753. Maximum Score From Removing Stones](https://leetcode.com/problems/maximum-score-from-removing-stones/) | Medium | 6+ months | 28.8 | Todo |  |  |  | [notes](06.%20Greedy%20with%20Heap/1753.%20Maximum%20Score%20From%20Removing%20Stones/1753.%20Maximum%20Score%20From%20Removing%20Stones.md) |
| 23 | [630. Course Schedule III](https://leetcode.com/problems/course-schedule-iii/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20Greedy%20with%20Heap/0630.%20Course%20Schedule%20III/0630.%20Course%20Schedule%20III.md) |
| 24 | [1962. Remove Stones to Minimize the Total](https://leetcode.com/problems/remove-stones-to-minimize-the-total/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20Greedy%20with%20Heap/1962.%20Remove%20Stones%20to%20Minimize%20the%20Total/1962.%20Remove%20Stones%20to%20Minimize%20the%20Total.md) |
