# 17. Intervals

[Back to Google](../README.md) · [Back to DSA Notes](../../../README.md)

29 Google problems: 3 Easy, 19 Medium, 7 Hard, in 5 sub-patterns.

## Sub-patterns

| # | Sub-pattern | Questions | Easy | Medium | Hard | Last 3 Months | Solved | Most Asked |
|:---:|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---|
| 01 | [Merge Intervals](#01-merge-intervals) | 9 | 1 | 7 | 1 | 2 | 1 | 56. Merge Intervals, 3169. Count Days Without Meetings, 759. Employee Free Time |
| 02 | [Insert & Remove Interval](#02-insert--remove-interval) | 2 | 0 | 2 | 0 | 1 | 1 | 57. Insert Interval, 1272. Remove Interval |
| 03 | [Overlapping Intervals & Meeting Rooms](#03-overlapping-intervals--meeting-rooms) | 6 | 2 | 4 | 0 | 1 | 0 | 253. Meeting Rooms II, 2446. Determine if Two Events Have Conflict, 986. Interval List Intersections |
| 04 | [Sweep Line](#04-sweep-line) | 6 | 0 | 2 | 4 | 1 | 0 | 218. The Skyline Problem, 1943. Describe the Painting, 731. My Calendar II |
| 05 | [Interval Scheduling](#05-interval-scheduling) | 6 | 0 | 4 | 2 | 1 | 1 | 435. Non-overlapping Intervals, 452. Minimum Number of Arrows to Burst Balloons, 2054. Two Best Non-Overlapping Events |

**Columns**

- **Last Asked**: most recent LeetCode window that lists the problem for Google (30 days, 3 months, 6 months, 6+ months).
- **Frequency**: LeetCode frequency score (0-100) in the Google "All" list.
- **Status**: your LeetCode status on the day this file was generated. 🔒 after a title means LeetCode Premium.
- **Logic / Key Idea, Time, Space**: fill these in as you solve. A rebuild keeps what you typed.
- **Notes**: link to the problem's notes file.

Inside each sub-pattern, rows are sorted by most recent window, then by frequency (highest first).

## 01. Merge Intervals

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [56. Merge Intervals](https://leetcode.com/problems/merge-intervals/) | Medium | 30 days | 70.6 | ✅ Solved |  |  |  | [notes](01.%20Merge%20Intervals/0056.%20Merge%20Intervals/0056.%20Merge%20Intervals.md) |
| 2 | [759. Employee Free Time](https://leetcode.com/problems/employee-free-time/) 🔒 | Hard | 30 days | 30.4 | Todo |  |  |  | [notes](01.%20Merge%20Intervals/0759.%20Employee%20Free%20Time/0759.%20Employee%20Free%20Time.md) |
| 3 | [1288. Remove Covered Intervals](https://leetcode.com/problems/remove-covered-intervals/) | Medium | 6 months | 15.4 | Todo |  |  |  | [notes](01.%20Merge%20Intervals/1288.%20Remove%20Covered%20Intervals/1288.%20Remove%20Covered%20Intervals.md) |
| 4 | [3169. Count Days Without Meetings](https://leetcode.com/problems/count-days-without-meetings/) | Medium | 6+ months | 34.5 | Todo |  |  |  | [notes](01.%20Merge%20Intervals/3169.%20Count%20Days%20Without%20Meetings/3169.%20Count%20Days%20Without%20Meetings.md) |
| 5 | [3394. Check if Grid can be Cut into Sections](https://leetcode.com/problems/check-if-grid-can-be-cut-into-sections/) | Medium | 6+ months | 16.1 | Todo |  |  |  | [notes](01.%20Merge%20Intervals/3394.%20Check%20if%20Grid%20can%20be%20Cut%20into%20Sections/3394.%20Check%20if%20Grid%20can%20be%20Cut%20into%20Sections.md) |
| 6 | [495. Teemo Attacking](https://leetcode.com/problems/teemo-attacking/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Merge%20Intervals/0495.%20Teemo%20Attacking/0495.%20Teemo%20Attacking.md) |
| 7 | [616. Add Bold Tag in String](https://leetcode.com/problems/add-bold-tag-in-string/) 🔒 | Medium | 6+ months | 28.8 | Todo |  |  |  | [notes](01.%20Merge%20Intervals/0616.%20Add%20Bold%20Tag%20in%20String/0616.%20Add%20Bold%20Tag%20in%20String.md) |
| 8 | [758. Bold Words in String](https://leetcode.com/problems/bold-words-in-string/) 🔒 | Medium | 6+ months | 28.8 | Todo |  |  |  | [notes](01.%20Merge%20Intervals/0758.%20Bold%20Words%20in%20String/0758.%20Bold%20Words%20in%20String.md) |
| 9 | [3975. Filter Occupied Intervals](https://leetcode.com/problems/filter-occupied-intervals/) | Medium | 6+ months | 28.8 | Todo |  |  |  | [notes](01.%20Merge%20Intervals/3975.%20Filter%20Occupied%20Intervals/3975.%20Filter%20Occupied%20Intervals.md) |

## 02. Insert & Remove Interval

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [57. Insert Interval](https://leetcode.com/problems/insert-interval/) | Medium | 3 months | 50.9 | ✅ Solved |  |  |  | [notes](02.%20Insert%20%26%20Remove%20Interval/0057.%20Insert%20Interval/0057.%20Insert%20Interval.md) |
| 2 | [1272. Remove Interval](https://leetcode.com/problems/remove-interval/) 🔒 | Medium | 6+ months | 33.2 | Todo |  |  |  | [notes](02.%20Insert%20%26%20Remove%20Interval/1272.%20Remove%20Interval/1272.%20Remove%20Interval.md) |

## 03. Overlapping Intervals & Meeting Rooms

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [253. Meeting Rooms II](https://leetcode.com/problems/meeting-rooms-ii/) 🔒 | Medium | 30 days | 64.3 | Todo |  |  |  | [notes](03.%20Overlapping%20Intervals%20%26%20Meeting%20Rooms/0253.%20Meeting%20Rooms%20II/0253.%20Meeting%20Rooms%20II.md) |
| 2 | [2446. Determine if Two Events Have Conflict](https://leetcode.com/problems/determine-if-two-events-have-conflict/) | Easy | 6+ months | 30.3 | Todo |  |  |  | [notes](03.%20Overlapping%20Intervals%20%26%20Meeting%20Rooms/2446.%20Determine%20if%20Two%20Events%20Have%20Conflict/2446.%20Determine%20if%20Two%20Events%20Have%20Conflict.md) |
| 3 | [986. Interval List Intersections](https://leetcode.com/problems/interval-list-intersections/) | Medium | 6+ months | 14.4 | Todo |  |  |  | [notes](03.%20Overlapping%20Intervals%20%26%20Meeting%20Rooms/0986.%20Interval%20List%20Intersections/0986.%20Interval%20List%20Intersections.md) |
| 4 | [252. Meeting Rooms](https://leetcode.com/problems/meeting-rooms/) 🔒 | Easy | 6+ months | 11.8 | Todo |  |  |  | [notes](03.%20Overlapping%20Intervals%20%26%20Meeting%20Rooms/0252.%20Meeting%20Rooms/0252.%20Meeting%20Rooms.md) |
| 5 | [1229. Meeting Scheduler](https://leetcode.com/problems/meeting-scheduler/) 🔒 | Medium | 6+ months | 10.0 | Todo |  |  |  | [notes](03.%20Overlapping%20Intervals%20%26%20Meeting%20Rooms/1229.%20Meeting%20Scheduler/1229.%20Meeting%20Scheduler.md) |
| 6 | [2406. Divide Intervals Into Minimum Number of Groups](https://leetcode.com/problems/divide-intervals-into-minimum-number-of-groups/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](03.%20Overlapping%20Intervals%20%26%20Meeting%20Rooms/2406.%20Divide%20Intervals%20Into%20Minimum%20Number%20of%20Groups/2406.%20Divide%20Intervals%20Into%20Minimum%20Number%20of%20Groups.md) |

## 04. Sweep Line

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [1943. Describe the Painting](https://leetcode.com/problems/describe-the-painting/) | Medium | 3 months | 34.4 | Todo |  |  |  | [notes](04.%20Sweep%20Line/1943.%20Describe%20the%20Painting/1943.%20Describe%20the%20Painting.md) |
| 2 | [218. The Skyline Problem](https://leetcode.com/problems/the-skyline-problem/) | Hard | 6+ months | 35.2 | Todo |  |  |  | [notes](04.%20Sweep%20Line/0218.%20The%20Skyline%20Problem/0218.%20The%20Skyline%20Problem.md) |
| 3 | [731. My Calendar II](https://leetcode.com/problems/my-calendar-ii/) | Medium | 6+ months | 33.4 | Todo |  |  |  | [notes](04.%20Sweep%20Line/0731.%20My%20Calendar%20II/0731.%20My%20Calendar%20II.md) |
| 4 | [2251. Number of Flowers in Full Bloom](https://leetcode.com/problems/number-of-flowers-in-full-bloom/) | Hard | 6+ months | 33.2 | Todo |  |  |  | [notes](04.%20Sweep%20Line/2251.%20Number%20of%20Flowers%20in%20Full%20Bloom/2251.%20Number%20of%20Flowers%20in%20Full%20Bloom.md) |
| 5 | [732. My Calendar III](https://leetcode.com/problems/my-calendar-iii/) | Hard | 6+ months | 30.7 | Todo |  |  |  | [notes](04.%20Sweep%20Line/0732.%20My%20Calendar%20III/0732.%20My%20Calendar%20III.md) |
| 6 | [850. Rectangle Area II](https://leetcode.com/problems/rectangle-area-ii/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Sweep%20Line/0850.%20Rectangle%20Area%20II/0850.%20Rectangle%20Area%20II.md) |

## 05. Interval Scheduling

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [3414. Maximum Score of Non-overlapping Intervals](https://leetcode.com/problems/maximum-score-of-non-overlapping-intervals/) | Hard | 3 months | 7.5 | Todo |  |  |  | [notes](05.%20Interval%20Scheduling/3414.%20Maximum%20Score%20of%20Non-overlapping%20Intervals/3414.%20Maximum%20Score%20of%20Non-overlapping%20Intervals.md) |
| 2 | [435. Non-overlapping Intervals](https://leetcode.com/problems/non-overlapping-intervals/) | Medium | 6 months | 32.2 | Todo |  |  |  | [notes](05.%20Interval%20Scheduling/0435.%20Non-overlapping%20Intervals/0435.%20Non-overlapping%20Intervals.md) |
| 3 | [452. Minimum Number of Arrows to Burst Balloons](https://leetcode.com/problems/minimum-number-of-arrows-to-burst-balloons/) | Medium | 6 months | 18.6 | ✅ Solved |  |  |  | [notes](05.%20Interval%20Scheduling/0452.%20Minimum%20Number%20of%20Arrows%20to%20Burst%20Balloons/0452.%20Minimum%20Number%20of%20Arrows%20to%20Burst%20Balloons.md) |
| 4 | [2054. Two Best Non-Overlapping Events](https://leetcode.com/problems/two-best-non-overlapping-events/) | Medium | 6+ months | 18.6 | Todo |  |  |  | [notes](05.%20Interval%20Scheduling/2054.%20Two%20Best%20Non-Overlapping%20Events/2054.%20Two%20Best%20Non-Overlapping%20Events.md) |
| 5 | [646. Maximum Length of Pair Chain](https://leetcode.com/problems/maximum-length-of-pair-chain/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Interval%20Scheduling/0646.%20Maximum%20Length%20of%20Pair%20Chain/0646.%20Maximum%20Length%20of%20Pair%20Chain.md) |
| 6 | [757. Set Intersection Size At Least Two](https://leetcode.com/problems/set-intersection-size-at-least-two/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Interval%20Scheduling/0757.%20Set%20Intersection%20Size%20At%20Least%20Two/0757.%20Set%20Intersection%20Size%20At%20Least%20Two.md) |
