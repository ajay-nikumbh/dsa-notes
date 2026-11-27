# 17. Intervals

[Back to Facebook](../README.md) · [Back to DSA Notes](../../../README.md)

15 Meta (Facebook) problems: 1 Easy, 10 Medium, 4 Hard, in 5 sub-patterns.

## Sub-patterns

| # | Sub-pattern | Questions | Easy | Medium | Hard | Last 3 Months | Solved | Most Asked |
|:---:|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---|
| 01 | [Merge Intervals](#01-merge-intervals) | 5 | 0 | 4 | 1 | 0 | 1 | 56. Merge Intervals, 616. Add Bold Tag in String, 759. Employee Free Time |
| 02 | [Insert & Remove Interval](#02-insert--remove-interval) | 1 | 0 | 1 | 0 | 0 | 1 | 57. Insert Interval |
| 03 | [Overlapping Intervals & Meeting Rooms](#03-overlapping-intervals--meeting-rooms) | 4 | 1 | 3 | 0 | 0 | 0 | 986. Interval List Intersections, 253. Meeting Rooms II, 252. Meeting Rooms |
| 04 | [Sweep Line](#04-sweep-line) | 1 | 0 | 0 | 1 | 0 | 0 | 218. The Skyline Problem |
| 05 | [Interval Scheduling](#05-interval-scheduling) | 4 | 0 | 2 | 2 | 1 | 0 | 435. Non-overlapping Intervals, 757. Set Intersection Size At Least Two, 2054. Two Best Non-Overlapping Events |

**Columns**

- **Last Asked**: most recent LeetCode window that lists the problem for Meta (30 days, 3 months, 6 months or 6+ months).
- **Frequency**: LeetCode frequency score (0-100) in the Meta "All" list.
- **Status**: your LeetCode status on the day this file was generated. 🔒 after a title means LeetCode Premium.
- **Logic / Key Idea, Time, Space**: fill these in as you solve. A rebuild keeps what you typed.
- **Notes**: link to the problem's notes file.

Inside each sub-pattern, rows are sorted by most recent window, then by frequency (highest first).

## 01. Merge Intervals

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [56. Merge Intervals](https://leetcode.com/problems/merge-intervals/) | Medium | 6 months | 86.2 | ✅ Solved |  |  |  | [notes](01.%20Merge%20Intervals/0056.%20Merge%20Intervals/0056.%20Merge%20Intervals.md) |
| 2 | [616. Add Bold Tag in String](https://leetcode.com/problems/add-bold-tag-in-string/) 🔒 | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Merge%20Intervals/0616.%20Add%20Bold%20Tag%20in%20String/0616.%20Add%20Bold%20Tag%20in%20String.md) |
| 3 | [759. Employee Free Time](https://leetcode.com/problems/employee-free-time/) 🔒 | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Merge%20Intervals/0759.%20Employee%20Free%20Time/0759.%20Employee%20Free%20Time.md) |
| 4 | [1288. Remove Covered Intervals](https://leetcode.com/problems/remove-covered-intervals/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Merge%20Intervals/1288.%20Remove%20Covered%20Intervals/1288.%20Remove%20Covered%20Intervals.md) |
| 5 | [2655. Find Maximal Uncovered Ranges](https://leetcode.com/problems/find-maximal-uncovered-ranges/) 🔒 | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Merge%20Intervals/2655.%20Find%20Maximal%20Uncovered%20Ranges/2655.%20Find%20Maximal%20Uncovered%20Ranges.md) |

## 02. Insert & Remove Interval

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203; | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [57. Insert Interval](https://leetcode.com/problems/insert-interval/) | Medium | 6+ months | 41.2 | ✅ Solved |  |  |  | [notes](02.%20Insert%20%26%20Remove%20Interval/0057.%20Insert%20Interval/0057.%20Insert%20Interval.md) |

## 03. Overlapping Intervals & Meeting Rooms

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [986. Interval List Intersections](https://leetcode.com/problems/interval-list-intersections/) | Medium | 6 months | 69.8 | Todo |  |  |  | [notes](03.%20Overlapping%20Intervals%20%26%20Meeting%20Rooms/0986.%20Interval%20List%20Intersections/0986.%20Interval%20List%20Intersections.md) |
| 2 | [253. Meeting Rooms II](https://leetcode.com/problems/meeting-rooms-ii/) 🔒 | Medium | 6+ months | 53.2 | Todo |  |  |  | [notes](03.%20Overlapping%20Intervals%20%26%20Meeting%20Rooms/0253.%20Meeting%20Rooms%20II/0253.%20Meeting%20Rooms%20II.md) |
| 3 | [252. Meeting Rooms](https://leetcode.com/problems/meeting-rooms/) 🔒 | Easy | 6+ months | 39.7 | Todo |  |  |  | [notes](03.%20Overlapping%20Intervals%20%26%20Meeting%20Rooms/0252.%20Meeting%20Rooms/0252.%20Meeting%20Rooms.md) |
| 4 | [1229. Meeting Scheduler](https://leetcode.com/problems/meeting-scheduler/) 🔒 | Medium | 6+ months | 12.9 | Todo |  |  |  | [notes](03.%20Overlapping%20Intervals%20%26%20Meeting%20Rooms/1229.%20Meeting%20Scheduler/1229.%20Meeting%20Scheduler.md) |

## 04. Sweep Line

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea&ensp;&#8203; | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [218. The Skyline Problem](https://leetcode.com/problems/the-skyline-problem/) | Hard | 6+ months | 39.3 | Todo |  |  |  | [notes](04.%20Sweep%20Line/0218.%20The%20Skyline%20Problem/0218.%20The%20Skyline%20Problem.md) |

## 05. Interval Scheduling

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [435. Non-overlapping Intervals](https://leetcode.com/problems/non-overlapping-intervals/) | Medium | 30 days | 35.3 | Todo |  |  |  | [notes](05.%20Interval%20Scheduling/0435.%20Non-overlapping%20Intervals/0435.%20Non-overlapping%20Intervals.md) |
| 2 | [757. Set Intersection Size At Least Two](https://leetcode.com/problems/set-intersection-size-at-least-two/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Interval%20Scheduling/0757.%20Set%20Intersection%20Size%20At%20Least%20Two/0757.%20Set%20Intersection%20Size%20At%20Least%20Two.md) |
| 3 | [2054. Two Best Non-Overlapping Events](https://leetcode.com/problems/two-best-non-overlapping-events/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Interval%20Scheduling/2054.%20Two%20Best%20Non-Overlapping%20Events/2054.%20Two%20Best%20Non-Overlapping%20Events.md) |
| 4 | [3414. Maximum Score of Non-overlapping Intervals](https://leetcode.com/problems/maximum-score-of-non-overlapping-intervals/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Interval%20Scheduling/3414.%20Maximum%20Score%20of%20Non-overlapping%20Intervals/3414.%20Maximum%20Score%20of%20Non-overlapping%20Intervals.md) |
