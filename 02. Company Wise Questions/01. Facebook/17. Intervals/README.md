# 17. Intervals - Meta (Facebook) Interview Questions

15 problems: 1 Easy, 10 Medium, 4 Hard. 5 sub-patterns.

[Back to Facebook](../README.md) · [Back to DSA Notes](../../../README.md)

## Sub-patterns

<table width="100%" style="width:100%">
<thead><tr><th>#</th><th>Name</th><th>Total</th><th>Easy</th><th>Medium</th><th>Hard</th><th>Last 30 Days</th><th>Last 3 Months</th><th>Last 6 Months</th><th>Solved</th></tr></thead>
<tbody>
<tr><td>1</td><td><a href="#01-merge-intervals">Merge Intervals</a></td><td>5</td><td>0</td><td>4</td><td>1</td><td>0</td><td>0</td><td>1</td><td>1</td></tr>
<tr><td>2</td><td><a href="#02-insert--remove-interval">Insert &amp; Remove Interval</a></td><td>1</td><td>0</td><td>1</td><td>0</td><td>0</td><td>0</td><td>0</td><td>1</td></tr>
<tr><td>3</td><td><a href="#03-overlapping-intervals--meeting-rooms">Overlapping Intervals &amp; Meeting Rooms</a></td><td>4</td><td>1</td><td>3</td><td>0</td><td>0</td><td>0</td><td>1</td><td>0</td></tr>
<tr><td>4</td><td><a href="#04-sweep-line">Sweep Line</a></td><td>1</td><td>0</td><td>0</td><td>1</td><td>0</td><td>0</td><td>0</td><td>0</td></tr>
<tr><td>5</td><td><a href="#05-interval-scheduling">Interval Scheduling</a></td><td>4</td><td>0</td><td>2</td><td>2</td><td>1</td><td>1</td><td>1</td><td>0</td></tr>
</tbody>
</table>

**Columns**

- **Last Asked**: most recent LeetCode window that lists the problem for Meta.
- **30 Days / 3 Months / 6 Months / 6+ Months**: ✅ when the problem appears in that window's list.
- **Frequency**: LeetCode frequency score (0-100) in the Meta "All" list.
- **Premium**: 🔒 means LeetCode Premium problem.
- **Status**: your LeetCode status on the day this file was generated.
- **Logic / Key Idea**: one-line approach, for example "monotonic stack of indices" (you fill it in).
- **Time / Space**: time and space complexity, for example `O(n)` / `O(1)` (you fill it in).
- **Date Solved / Revisions / Confidence / Remarks**: your own tracking (you fill it in). Confidence can be Low, Medium or High.
- **Notes**: link to the problem's notes file.

Fill the hand-written columns in this file or in a chapter README. A rebuild keeps what you typed.

Within each sub-pattern, rows are sorted by most recent window, then by frequency (highest first).

## 01. Merge Intervals

<table width="100%" style="width:100%">
<thead><tr><th>#</th><th>Problem</th><th>Difficulty</th><th>Sub-pattern</th><th>Last Asked</th><th>30 Days</th><th>3 Months</th><th>6 Months</th><th>6+ Months</th><th>Frequency</th><th>Premium</th><th>Status</th><th>Logic / Key Idea</th><th>Time</th><th>Space</th><th>Date Solved</th><th>Revisions</th><th>Confidence</th><th>Remarks</th><th>Topic Tags</th><th>Notes</th></tr></thead>
<tbody>
<tr><td>1</td><td><a href="https://leetcode.com/problems/merge-intervals/">56. Merge Intervals</a></td><td>Medium</td><td>Merge Intervals</td><td>Last 6 months</td><td></td><td></td><td>✅</td><td>✅</td><td>86.2</td><td></td><td>Solved</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Array, Sorting, Quicksort</td><td><a href="01.%20Merge%20Intervals/0056.%20Merge%20Intervals/0056.%20Merge%20Intervals.md">notes</a></td></tr>
<tr><td>2</td><td><a href="https://leetcode.com/problems/add-bold-tag-in-string/">616. Add Bold Tag in String</a></td><td>Medium</td><td>Merge Intervals</td><td>More than 6 months</td><td></td><td></td><td></td><td>✅</td><td>5.0</td><td>🔒</td><td>Todo</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Array, Hash Table, String, Trie, String Matching, Aho–Corasick Algorithm</td><td><a href="01.%20Merge%20Intervals/0616.%20Add%20Bold%20Tag%20in%20String/0616.%20Add%20Bold%20Tag%20in%20String.md">notes</a></td></tr>
<tr><td>3</td><td><a href="https://leetcode.com/problems/employee-free-time/">759. Employee Free Time</a></td><td>Hard</td><td>Merge Intervals</td><td>More than 6 months</td><td></td><td></td><td></td><td>✅</td><td>5.0</td><td>🔒</td><td>Todo</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Array, Sweep Line, Sorting, Heap (Priority Queue)</td><td><a href="01.%20Merge%20Intervals/0759.%20Employee%20Free%20Time/0759.%20Employee%20Free%20Time.md">notes</a></td></tr>
<tr><td>4</td><td><a href="https://leetcode.com/problems/remove-covered-intervals/">1288. Remove Covered Intervals</a></td><td>Medium</td><td>Merge Intervals</td><td>More than 6 months</td><td></td><td></td><td></td><td>✅</td><td>5.0</td><td></td><td>Todo</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Array, Sorting</td><td><a href="01.%20Merge%20Intervals/1288.%20Remove%20Covered%20Intervals/1288.%20Remove%20Covered%20Intervals.md">notes</a></td></tr>
<tr><td>5</td><td><a href="https://leetcode.com/problems/find-maximal-uncovered-ranges/">2655. Find Maximal Uncovered Ranges</a></td><td>Medium</td><td>Merge Intervals</td><td>More than 6 months</td><td></td><td></td><td></td><td>✅</td><td>5.0</td><td>🔒</td><td>Todo</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Array, Sorting</td><td><a href="01.%20Merge%20Intervals/2655.%20Find%20Maximal%20Uncovered%20Ranges/2655.%20Find%20Maximal%20Uncovered%20Ranges.md">notes</a></td></tr>
</tbody>
</table>

## 02. Insert & Remove Interval

<table width="100%" style="width:100%">
<thead><tr><th>#</th><th>Problem</th><th>Difficulty</th><th>Sub-pattern</th><th>Last Asked</th><th>30 Days</th><th>3 Months</th><th>6 Months</th><th>6+ Months</th><th>Frequency</th><th>Premium</th><th>Status</th><th>Logic / Key Idea</th><th>Time</th><th>Space</th><th>Date Solved</th><th>Revisions</th><th>Confidence</th><th>Remarks</th><th>Topic Tags</th><th>Notes</th></tr></thead>
<tbody>
<tr><td>1</td><td><a href="https://leetcode.com/problems/insert-interval/">57. Insert Interval</a></td><td>Medium</td><td>Insert &amp; Remove Interval</td><td>More than 6 months</td><td></td><td></td><td></td><td>✅</td><td>41.2</td><td></td><td>Solved</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Array</td><td><a href="02.%20Insert%20%26%20Remove%20Interval/0057.%20Insert%20Interval/0057.%20Insert%20Interval.md">notes</a></td></tr>
</tbody>
</table>

## 03. Overlapping Intervals & Meeting Rooms

<table width="100%" style="width:100%">
<thead><tr><th>#</th><th>Problem</th><th>Difficulty</th><th>Sub-pattern</th><th>Last Asked</th><th>30 Days</th><th>3 Months</th><th>6 Months</th><th>6+ Months</th><th>Frequency</th><th>Premium</th><th>Status</th><th>Logic / Key Idea</th><th>Time</th><th>Space</th><th>Date Solved</th><th>Revisions</th><th>Confidence</th><th>Remarks</th><th>Topic Tags</th><th>Notes</th></tr></thead>
<tbody>
<tr><td>1</td><td><a href="https://leetcode.com/problems/interval-list-intersections/">986. Interval List Intersections</a></td><td>Medium</td><td>Overlapping Intervals &amp; Meeting Rooms</td><td>Last 6 months</td><td></td><td></td><td>✅</td><td>✅</td><td>69.8</td><td></td><td>Todo</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Array, Two Pointers, Sweep Line</td><td><a href="03.%20Overlapping%20Intervals%20%26%20Meeting%20Rooms/0986.%20Interval%20List%20Intersections/0986.%20Interval%20List%20Intersections.md">notes</a></td></tr>
<tr><td>2</td><td><a href="https://leetcode.com/problems/meeting-rooms-ii/">253. Meeting Rooms II</a></td><td>Medium</td><td>Overlapping Intervals &amp; Meeting Rooms</td><td>More than 6 months</td><td></td><td></td><td></td><td>✅</td><td>53.2</td><td>🔒</td><td>Todo</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Array, Two Pointers, Greedy, Sorting, Heap (Priority Queue), Prefix Sum</td><td><a href="03.%20Overlapping%20Intervals%20%26%20Meeting%20Rooms/0253.%20Meeting%20Rooms%20II/0253.%20Meeting%20Rooms%20II.md">notes</a></td></tr>
<tr><td>3</td><td><a href="https://leetcode.com/problems/meeting-rooms/">252. Meeting Rooms</a></td><td>Easy</td><td>Overlapping Intervals &amp; Meeting Rooms</td><td>More than 6 months</td><td></td><td></td><td></td><td>✅</td><td>39.7</td><td>🔒</td><td>Todo</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Array, Sorting, Quicksort</td><td><a href="03.%20Overlapping%20Intervals%20%26%20Meeting%20Rooms/0252.%20Meeting%20Rooms/0252.%20Meeting%20Rooms.md">notes</a></td></tr>
<tr><td>4</td><td><a href="https://leetcode.com/problems/meeting-scheduler/">1229. Meeting Scheduler</a></td><td>Medium</td><td>Overlapping Intervals &amp; Meeting Rooms</td><td>More than 6 months</td><td></td><td></td><td></td><td>✅</td><td>12.9</td><td>🔒</td><td>Todo</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Array, Two Pointers, Sorting</td><td><a href="03.%20Overlapping%20Intervals%20%26%20Meeting%20Rooms/1229.%20Meeting%20Scheduler/1229.%20Meeting%20Scheduler.md">notes</a></td></tr>
</tbody>
</table>

## 04. Sweep Line

<table width="100%" style="width:100%">
<thead><tr><th>#</th><th>Problem</th><th>Difficulty</th><th>Sub-pattern</th><th>Last Asked</th><th>30 Days</th><th>3 Months</th><th>6 Months</th><th>6+ Months</th><th>Frequency</th><th>Premium</th><th>Status</th><th>Logic / Key Idea</th><th>Time</th><th>Space</th><th>Date Solved</th><th>Revisions</th><th>Confidence</th><th>Remarks</th><th>Topic Tags</th><th>Notes</th></tr></thead>
<tbody>
<tr><td>1</td><td><a href="https://leetcode.com/problems/the-skyline-problem/">218. The Skyline Problem</a></td><td>Hard</td><td>Sweep Line</td><td>More than 6 months</td><td></td><td></td><td></td><td>✅</td><td>39.3</td><td></td><td>Todo</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Array, Divide and Conquer, Binary Indexed Tree, Segment Tree, Sweep Line, Sorting, Heap (Priority Queue), Ordered Set</td><td><a href="04.%20Sweep%20Line/0218.%20The%20Skyline%20Problem/0218.%20The%20Skyline%20Problem.md">notes</a></td></tr>
</tbody>
</table>

## 05. Interval Scheduling

<table width="100%" style="width:100%">
<thead><tr><th>#</th><th>Problem</th><th>Difficulty</th><th>Sub-pattern</th><th>Last Asked</th><th>30 Days</th><th>3 Months</th><th>6 Months</th><th>6+ Months</th><th>Frequency</th><th>Premium</th><th>Status</th><th>Logic / Key Idea</th><th>Time</th><th>Space</th><th>Date Solved</th><th>Revisions</th><th>Confidence</th><th>Remarks</th><th>Topic Tags</th><th>Notes</th></tr></thead>
<tbody>
<tr><td>1</td><td><a href="https://leetcode.com/problems/non-overlapping-intervals/">435. Non-overlapping Intervals</a></td><td>Medium</td><td>Interval Scheduling</td><td>Last 30 days</td><td>✅</td><td>✅</td><td>✅</td><td>✅</td><td>35.3</td><td></td><td>Todo</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Array, Dynamic Programming, Greedy, Sorting</td><td><a href="05.%20Interval%20Scheduling/0435.%20Non-overlapping%20Intervals/0435.%20Non-overlapping%20Intervals.md">notes</a></td></tr>
<tr><td>2</td><td><a href="https://leetcode.com/problems/set-intersection-size-at-least-two/">757. Set Intersection Size At Least Two</a></td><td>Hard</td><td>Interval Scheduling</td><td>More than 6 months</td><td></td><td></td><td></td><td>✅</td><td>5.0</td><td></td><td>Todo</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Array, Greedy, Sorting</td><td><a href="05.%20Interval%20Scheduling/0757.%20Set%20Intersection%20Size%20At%20Least%20Two/0757.%20Set%20Intersection%20Size%20At%20Least%20Two.md">notes</a></td></tr>
<tr><td>3</td><td><a href="https://leetcode.com/problems/two-best-non-overlapping-events/">2054. Two Best Non-Overlapping Events</a></td><td>Medium</td><td>Interval Scheduling</td><td>More than 6 months</td><td></td><td></td><td></td><td>✅</td><td>5.0</td><td></td><td>Todo</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Array, Binary Search, Dynamic Programming, Sorting, Heap (Priority Queue)</td><td><a href="05.%20Interval%20Scheduling/2054.%20Two%20Best%20Non-Overlapping%20Events/2054.%20Two%20Best%20Non-Overlapping%20Events.md">notes</a></td></tr>
<tr><td>4</td><td><a href="https://leetcode.com/problems/maximum-score-of-non-overlapping-intervals/">3414. Maximum Score of Non-overlapping Intervals</a></td><td>Hard</td><td>Interval Scheduling</td><td>More than 6 months</td><td></td><td></td><td></td><td>✅</td><td>5.0</td><td></td><td>Todo</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Array, Binary Search, Dynamic Programming, Sorting</td><td><a href="05.%20Interval%20Scheduling/3414.%20Maximum%20Score%20of%20Non-overlapping%20Intervals/3414.%20Maximum%20Score%20of%20Non-overlapping%20Intervals.md">notes</a></td></tr>
</tbody>
</table>
