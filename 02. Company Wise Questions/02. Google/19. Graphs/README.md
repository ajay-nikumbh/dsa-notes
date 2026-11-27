# 19. Graphs

[Back to Google](../README.md) · [Back to DSA Notes](../../../README.md)

103 Google problems: 4 Easy, 65 Medium, 34 Hard, in 10 sub-patterns.

## Sub-patterns

| # | Sub-pattern | Questions | Easy | Medium | Hard | Last 3 Months | Solved | Most Asked |
|:---:|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---|
| 01 | [Graph DFS & Connected Components](#01-graph-dfs--connected-components) | 17 | 3 | 13 | 1 | 2 | 4 | 3481. Apply Substitutions, 399. Evaluate Division, 841. Keys and Rooms |
| 02 | [Grid DFS (Islands)](#02-grid-dfs-islands) | 19 | 1 | 14 | 4 | 5 | 8 | 200. Number of Islands, 417. Pacific Atlantic Water Flow, 1254. Number of Closed Islands |
| 03 | [BFS Shortest Path (Unweighted)](#03-bfs-shortest-path-unweighted) | 6 | 0 | 4 | 2 | 0 | 0 | 909. Snakes and Ladders, 1306. Jump Game III, 2045. Second Minimum Time to Reach Destination |
| 04 | [Grid BFS](#04-grid-bfs) | 7 | 0 | 5 | 2 | 1 | 1 | 1293. Shortest Path in a Grid with Obstacles Elimination, 1091. Shortest Path in Binary Matrix, 317. Shortest Distance from All Buildings |
| 05 | [Multi-Source BFS](#05-multi-source-bfs) | 8 | 0 | 7 | 1 | 2 | 6 | 994. Rotting Oranges, 2812. Find the Safest Path in a Grid, 542. 01 Matrix |
| 06 | [Topological Sort](#06-topological-sort) | 17 | 0 | 10 | 7 | 4 | 4 | 207. Course Schedule, 269. Alien Dictionary, 444. Sequence Reconstruction |
| 07 | [Cycle Detection](#07-cycle-detection) | 8 | 0 | 4 | 4 | 0 | 2 | 802. Find Eventual Safe States, 1059. All Paths from Source Lead to Destination, 1153. String Transforms Into Another String |
| 08 | [Bipartite & Graph Coloring](#08-bipartite--graph-coloring) | 4 | 0 | 2 | 2 | 1 | 1 | 785. Is Graph Bipartite?, 2493. Divide Nodes Into the Maximum Number of Groups, 886. Possible Bipartition |
| 09 | [Clone & Build Graph](#09-clone--build-graph) | 1 | 0 | 1 | 0 | 0 | 0 | 133. Clone Graph |
| 10 | [Implicit Graph BFS (Word Ladder, Lock)](#10-implicit-graph-bfs-word-ladder-lock) | 16 | 0 | 5 | 11 | 1 | 4 | 815. Bus Routes, 127. Word Ladder, 818. Race Car |

**Columns**

- **Last Asked**: most recent LeetCode window that lists the problem for Google (30 days, 3 months, 6 months, 6+ months).
- **Frequency**: LeetCode frequency score (0-100) in the Google "All" list.
- **Status**: your LeetCode status on the day this file was generated. 🔒 after a title means LeetCode Premium.
- **Logic / Key Idea, Time, Space**: fill these in as you solve. A rebuild keeps what you typed.
- **Notes**: link to the problem's notes file.

Inside each sub-pattern, rows are sorted by most recent window, then by frequency (highest first).

## 01. Graph DFS & Connected Components

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [547. Number of Provinces](https://leetcode.com/problems/number-of-provinces/) | Medium | 30 days | 40.7 | ✅ Solved |  |  |  | [notes](01.%20Graph%20DFS%20%26%20Connected%20Components/0547.%20Number%20of%20Provinces/0547.%20Number%20of%20Provinces.md) |
| 2 | [2101. Detonate the Maximum Bombs](https://leetcode.com/problems/detonate-the-maximum-bombs/) | Medium | 3 months | 37.1 | Todo |  |  |  | [notes](01.%20Graph%20DFS%20%26%20Connected%20Components/2101.%20Detonate%20the%20Maximum%20Bombs/2101.%20Detonate%20the%20Maximum%20Bombs.md) |
| 3 | [399. Evaluate Division](https://leetcode.com/problems/evaluate-division/) | Medium | 6 months | 43.3 | Todo |  |  |  | [notes](01.%20Graph%20DFS%20%26%20Connected%20Components/0399.%20Evaluate%20Division/0399.%20Evaluate%20Division.md) |
| 4 | [841. Keys and Rooms](https://leetcode.com/problems/keys-and-rooms/) | Medium | 6 months | 40.8 | ✅ Solved |  |  |  | [notes](01.%20Graph%20DFS%20%26%20Connected%20Components/0841.%20Keys%20and%20Rooms/0841.%20Keys%20and%20Rooms.md) |
| 5 | [3310. Remove Methods From Project](https://leetcode.com/problems/remove-methods-from-project/) | Medium | 6 months | 5.2 | Todo |  |  |  | [notes](01.%20Graph%20DFS%20%26%20Connected%20Components/3310.%20Remove%20Methods%20From%20Project/3310.%20Remove%20Methods%20From%20Project.md) |
| 6 | [3481. Apply Substitutions](https://leetcode.com/problems/apply-substitutions/) 🔒 | Medium | 6+ months | 43.5 | ✅ Solved |  |  |  | [notes](01.%20Graph%20DFS%20%26%20Connected%20Components/3481.%20Apply%20Substitutions/3481.%20Apply%20Substitutions.md) |
| 7 | [2242. Maximum Score of a Node Sequence](https://leetcode.com/problems/maximum-score-of-a-node-sequence/) | Hard | 6+ months | 33.7 | Todo |  |  |  | [notes](01.%20Graph%20DFS%20%26%20Connected%20Components/2242.%20Maximum%20Score%20of%20a%20Node%20Sequence/2242.%20Maximum%20Score%20of%20a%20Node%20Sequence.md) |
| 8 | [323. Number of Connected Components in an Undirected Graph](https://leetcode.com/problems/number-of-connected-components-in-an-undirected-graph/) 🔒 | Medium | 6+ months | 31.6 | Todo |  |  |  | [notes](01.%20Graph%20DFS%20%26%20Connected%20Components/0323.%20Number%20of%20Connected%20Components%20in%20an%20Undirected%20Graph/0323.%20Number%20of%20Connected%20Components%20in%20an%20Undirected%20Graph.md) |
| 9 | [1971. Find if Path Exists in Graph](https://leetcode.com/problems/find-if-path-exists-in-graph/) | Easy | 6+ months | 23.9 | ✅ Solved |  |  |  | [notes](01.%20Graph%20DFS%20%26%20Connected%20Components/1971.%20Find%20if%20Path%20Exists%20in%20Graph/1971.%20Find%20if%20Path%20Exists%20in%20Graph.md) |
| 10 | [690. Employee Importance](https://leetcode.com/problems/employee-importance/) | Medium | 6+ months | 16.0 | Todo |  |  |  | [notes](01.%20Graph%20DFS%20%26%20Connected%20Components/0690.%20Employee%20Importance/0690.%20Employee%20Importance.md) |
| 11 | [997. Find the Town Judge](https://leetcode.com/problems/find-the-town-judge/) | Easy | 6+ months | 9.0 | Todo |  |  |  | [notes](01.%20Graph%20DFS%20%26%20Connected%20Components/0997.%20Find%20the%20Town%20Judge/0997.%20Find%20the%20Town%20Judge.md) |
| 12 | [2368. Reachable Nodes With Restrictions](https://leetcode.com/problems/reachable-nodes-with-restrictions/) | Medium | 6+ months | 7.7 | Todo |  |  |  | [notes](01.%20Graph%20DFS%20%26%20Connected%20Components/2368.%20Reachable%20Nodes%20With%20Restrictions/2368.%20Reachable%20Nodes%20With%20Restrictions.md) |
| 13 | [2685. Count the Number of Complete Components](https://leetcode.com/problems/count-the-number-of-complete-components/) | Medium | 6+ months | 5.8 | Todo |  |  |  | [notes](01.%20Graph%20DFS%20%26%20Connected%20Components/2685.%20Count%20the%20Number%20of%20Complete%20Components/2685.%20Count%20the%20Number%20of%20Complete%20Components.md) |
| 14 | [797. All Paths From Source to Target](https://leetcode.com/problems/all-paths-from-source-to-target/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Graph%20DFS%20%26%20Connected%20Components/0797.%20All%20Paths%20From%20Source%20to%20Target/0797.%20All%20Paths%20From%20Source%20to%20Target.md) |
| 15 | [1466. Reorder Routes to Make All Paths Lead to the City Zero](https://leetcode.com/problems/reorder-routes-to-make-all-paths-lead-to-the-city-zero/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Graph%20DFS%20%26%20Connected%20Components/1466.%20Reorder%20Routes%20to%20Make%20All%20Paths%20Lead%20to%20the%20City%20Zero/1466.%20Reorder%20Routes%20to%20Make%20All%20Paths%20Lead%20to%20the%20City%20Zero.md) |
| 16 | [1791. Find Center of Star Graph](https://leetcode.com/problems/find-center-of-star-graph/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Graph%20DFS%20%26%20Connected%20Components/1791.%20Find%20Center%20of%20Star%20Graph/1791.%20Find%20Center%20of%20Star%20Graph.md) |
| 17 | [3387. Maximize Amount After Two Days of Conversions](https://leetcode.com/problems/maximize-amount-after-two-days-of-conversions/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Graph%20DFS%20%26%20Connected%20Components/3387.%20Maximize%20Amount%20After%20Two%20Days%20of%20Conversions/3387.%20Maximize%20Amount%20After%20Two%20Days%20of%20Conversions.md) |

## 02. Grid DFS (Islands)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [200. Number of Islands](https://leetcode.com/problems/number-of-islands/) | Medium | 30 days | 68.3 | ✅ Solved |  |  |  | [notes](02.%20Grid%20DFS%20%28Islands%29/0200.%20Number%20of%20Islands/0200.%20Number%20of%20Islands.md) |
| 2 | [417. Pacific Atlantic Water Flow](https://leetcode.com/problems/pacific-atlantic-water-flow/) | Medium | 3 months | 47.4 | ✅ Solved |  |  |  | [notes](02.%20Grid%20DFS%20%28Islands%29/0417.%20Pacific%20Atlantic%20Water%20Flow/0417.%20Pacific%20Atlantic%20Water%20Flow.md) |
| 3 | [1254. Number of Closed Islands](https://leetcode.com/problems/number-of-closed-islands/) | Medium | 3 months | 41.3 | Todo |  |  |  | [notes](02.%20Grid%20DFS%20%28Islands%29/1254.%20Number%20of%20Closed%20Islands/1254.%20Number%20of%20Closed%20Islands.md) |
| 4 | [130. Surrounded Regions](https://leetcode.com/problems/surrounded-regions/) | Medium | 3 months | 38.6 | Todo |  |  |  | [notes](02.%20Grid%20DFS%20%28Islands%29/0130.%20Surrounded%20Regions/0130.%20Surrounded%20Regions.md) |
| 5 | [827. Making A Large Island](https://leetcode.com/problems/making-a-large-island/) | Hard | 3 months | 25.3 | ✅ Solved |  |  |  | [notes](02.%20Grid%20DFS%20%28Islands%29/0827.%20Making%20A%20Large%20Island/0827.%20Making%20A%20Large%20Island.md) |
| 6 | [695. Max Area of Island](https://leetcode.com/problems/max-area-of-island/) | Medium | 6 months | 24.7 | ✅ Solved |  |  |  | [notes](02.%20Grid%20DFS%20%28Islands%29/0695.%20Max%20Area%20of%20Island/0695.%20Max%20Area%20of%20Island.md) |
| 7 | [733. Flood Fill](https://leetcode.com/problems/flood-fill/) | Easy | 6 months | 24.5 | ✅ Solved |  |  |  | [notes](02.%20Grid%20DFS%20%28Islands%29/0733.%20Flood%20Fill/0733.%20Flood%20Fill.md) |
| 8 | [1020. Number of Enclaves](https://leetcode.com/problems/number-of-enclaves/) | Medium | 6+ months | 33.6 | ✅ Solved |  |  |  | [notes](02.%20Grid%20DFS%20%28Islands%29/1020.%20Number%20of%20Enclaves/1020.%20Number%20of%20Enclaves.md) |
| 9 | [2556. Disconnect Path in a Binary Matrix by at Most One Flip](https://leetcode.com/problems/disconnect-path-in-a-binary-matrix-by-at-most-one-flip/) | Medium | 6+ months | 30.1 | Todo |  |  |  | [notes](02.%20Grid%20DFS%20%28Islands%29/2556.%20Disconnect%20Path%20in%20a%20Binary%20Matrix%20by%20at%20Most%20One%20Flip/2556.%20Disconnect%20Path%20in%20a%20Binary%20Matrix%20by%20at%20Most%20One%20Flip.md) |
| 10 | [694. Number of Distinct Islands](https://leetcode.com/problems/number-of-distinct-islands/) 🔒 | Medium | 6+ months | 9.1 | Todo |  |  |  | [notes](02.%20Grid%20DFS%20%28Islands%29/0694.%20Number%20of%20Distinct%20Islands/0694.%20Number%20of%20Distinct%20Islands.md) |
| 11 | [3619. Count Islands With Total Value Divisible by K](https://leetcode.com/problems/count-islands-with-total-value-divisible-by-k/) | Medium | 6+ months | 5.5 | ✅ Solved |  |  |  | [notes](02.%20Grid%20DFS%20%28Islands%29/3619.%20Count%20Islands%20With%20Total%20Value%20Divisible%20by%20K/3619.%20Count%20Islands%20With%20Total%20Value%20Divisible%20by%20K.md) |
| 12 | [529. Minesweeper](https://leetcode.com/problems/minesweeper/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Grid%20DFS%20%28Islands%29/0529.%20Minesweeper/0529.%20Minesweeper.md) |
| 13 | [711. Number of Distinct Islands II](https://leetcode.com/problems/number-of-distinct-islands-ii/) 🔒 | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Grid%20DFS%20%28Islands%29/0711.%20Number%20of%20Distinct%20Islands%20II/0711.%20Number%20of%20Distinct%20Islands%20II.md) |
| 14 | [1034. Coloring A Border](https://leetcode.com/problems/coloring-a-border/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Grid%20DFS%20%28Islands%29/1034.%20Coloring%20A%20Border/1034.%20Coloring%20A%20Border.md) |
| 15 | [1391. Check if There is a Valid Path in a Grid](https://leetcode.com/problems/check-if-there-is-a-valid-path-in-a-grid/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Grid%20DFS%20%28Islands%29/1391.%20Check%20if%20There%20is%20a%20Valid%20Path%20in%20a%20Grid/1391.%20Check%20if%20There%20is%20a%20Valid%20Path%20in%20a%20Grid.md) |
| 16 | [1568. Minimum Number of Days to Disconnect Island](https://leetcode.com/problems/minimum-number-of-days-to-disconnect-island/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Grid%20DFS%20%28Islands%29/1568.%20Minimum%20Number%20of%20Days%20to%20Disconnect%20Island/1568.%20Minimum%20Number%20of%20Days%20to%20Disconnect%20Island.md) |
| 17 | [1992. Find All Groups of Farmland](https://leetcode.com/problems/find-all-groups-of-farmland/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](02.%20Grid%20DFS%20%28Islands%29/1992.%20Find%20All%20Groups%20of%20Farmland/1992.%20Find%20All%20Groups%20of%20Farmland.md) |
| 18 | [749. Contain Virus](https://leetcode.com/problems/contain-virus/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Grid%20DFS%20%28Islands%29/0749.%20Contain%20Virus/0749.%20Contain%20Virus.md) |
| 19 | [2658. Maximum Number of Fish in a Grid](https://leetcode.com/problems/maximum-number-of-fish-in-a-grid/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Grid%20DFS%20%28Islands%29/2658.%20Maximum%20Number%20of%20Fish%20in%20a%20Grid/2658.%20Maximum%20Number%20of%20Fish%20in%20a%20Grid.md) |

## 03. BFS Shortest Path (Unweighted)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [2045. Second Minimum Time to Reach Destination](https://leetcode.com/problems/second-minimum-time-to-reach-destination/) | Hard | 6 months | 8.5 | Todo |  |  |  | [notes](03.%20BFS%20Shortest%20Path%20%28Unweighted%29/2045.%20Second%20Minimum%20Time%20to%20Reach%20Destination/2045.%20Second%20Minimum%20Time%20to%20Reach%20Destination.md) |
| 2 | [909. Snakes and Ladders](https://leetcode.com/problems/snakes-and-ladders/) | Medium | 6+ months | 34.1 | Todo |  |  |  | [notes](03.%20BFS%20Shortest%20Path%20%28Unweighted%29/0909.%20Snakes%20and%20Ladders/0909.%20Snakes%20and%20Ladders.md) |
| 3 | [1306. Jump Game III](https://leetcode.com/problems/jump-game-iii/) | Medium | 6+ months | 8.5 | Todo |  |  |  | [notes](03.%20BFS%20Shortest%20Path%20%28Unweighted%29/1306.%20Jump%20Game%20III/1306.%20Jump%20Game%20III.md) |
| 4 | [1129. Shortest Path with Alternating Colors](https://leetcode.com/problems/shortest-path-with-alternating-colors/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](03.%20BFS%20Shortest%20Path%20%28Unweighted%29/1129.%20Shortest%20Path%20with%20Alternating%20Colors/1129.%20Shortest%20Path%20with%20Alternating%20Colors.md) |
| 5 | [1298. Maximum Candies You Can Get from Boxes](https://leetcode.com/problems/maximum-candies-you-can-get-from-boxes/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](03.%20BFS%20Shortest%20Path%20%28Unweighted%29/1298.%20Maximum%20Candies%20You%20Can%20Get%20from%20Boxes/1298.%20Maximum%20Candies%20You%20Can%20Get%20from%20Boxes.md) |
| 6 | [2359. Find Closest Node to Given Two Nodes](https://leetcode.com/problems/find-closest-node-to-given-two-nodes/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](03.%20BFS%20Shortest%20Path%20%28Unweighted%29/2359.%20Find%20Closest%20Node%20to%20Given%20Two%20Nodes/2359.%20Find%20Closest%20Node%20to%20Given%20Two%20Nodes.md) |

## 04. Grid BFS

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [1091. Shortest Path in Binary Matrix](https://leetcode.com/problems/shortest-path-in-binary-matrix/) | Medium | 3 months | 35.6 | ✅ Solved |  |  |  | [notes](04.%20Grid%20BFS/1091.%20Shortest%20Path%20in%20Binary%20Matrix/1091.%20Shortest%20Path%20in%20Binary%20Matrix.md) |
| 2 | [1293. Shortest Path in a Grid with Obstacles Elimination](https://leetcode.com/problems/shortest-path-in-a-grid-with-obstacles-elimination/) | Hard | 6 months | 37.2 | Todo |  |  |  | [notes](04.%20Grid%20BFS/1293.%20Shortest%20Path%20in%20a%20Grid%20with%20Obstacles%20Elimination/1293.%20Shortest%20Path%20in%20a%20Grid%20with%20Obstacles%20Elimination.md) |
| 3 | [3568. Minimum Moves to Clean the Classroom](https://leetcode.com/problems/minimum-moves-to-clean-the-classroom/) | Medium | 6 months | 15.2 | Todo |  |  |  | [notes](04.%20Grid%20BFS/3568.%20Minimum%20Moves%20to%20Clean%20the%20Classroom/3568.%20Minimum%20Moves%20to%20Clean%20the%20Classroom.md) |
| 4 | [317. Shortest Distance from All Buildings](https://leetcode.com/problems/shortest-distance-from-all-buildings/) 🔒 | Hard | 6+ months | 33.9 | Todo |  |  |  | [notes](04.%20Grid%20BFS/0317.%20Shortest%20Distance%20from%20All%20Buildings/0317.%20Shortest%20Distance%20from%20All%20Buildings.md) |
| 5 | [490. The Maze](https://leetcode.com/problems/the-maze/) 🔒 | Medium | 6+ months | 30.1 | Todo |  |  |  | [notes](04.%20Grid%20BFS/0490.%20The%20Maze/0490.%20The%20Maze.md) |
| 6 | [1926. Nearest Exit from Entrance in Maze](https://leetcode.com/problems/nearest-exit-from-entrance-in-maze/) | Medium | 6+ months | 6.4 | Todo |  |  |  | [notes](04.%20Grid%20BFS/1926.%20Nearest%20Exit%20from%20Entrance%20in%20Maze/1926.%20Nearest%20Exit%20from%20Entrance%20in%20Maze.md) |
| 7 | [1778. Shortest Path in a Hidden Grid](https://leetcode.com/problems/shortest-path-in-a-hidden-grid/) 🔒 | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Grid%20BFS/1778.%20Shortest%20Path%20in%20a%20Hidden%20Grid/1778.%20Shortest%20Path%20in%20a%20Hidden%20Grid.md) |

## 05. Multi-Source BFS

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [994. Rotting Oranges](https://leetcode.com/problems/rotting-oranges/) | Medium | 3 months | 53.9 | ✅ Solved |  |  |  | [notes](05.%20Multi-Source%20BFS/0994.%20Rotting%20Oranges/0994.%20Rotting%20Oranges.md) |
| 2 | [2812. Find the Safest Path in a Grid](https://leetcode.com/problems/find-the-safest-path-in-a-grid/) | Medium | 3 months | 41.5 | ✅ Solved |  |  |  | [notes](05.%20Multi-Source%20BFS/2812.%20Find%20the%20Safest%20Path%20in%20a%20Grid/2812.%20Find%20the%20Safest%20Path%20in%20a%20Grid.md) |
| 3 | [542. 01 Matrix](https://leetcode.com/problems/01-matrix/) | Medium | 6 months | 39.5 | ✅ Solved |  |  |  | [notes](05.%20Multi-Source%20BFS/0542.%2001%20Matrix/0542.%2001%20Matrix.md) |
| 4 | [286. Walls and Gates](https://leetcode.com/problems/walls-and-gates/) 🔒 | Medium | 6+ months | 32.9 | ✅ Solved |  |  |  | [notes](05.%20Multi-Source%20BFS/0286.%20Walls%20and%20Gates/0286.%20Walls%20and%20Gates.md) |
| 5 | [934. Shortest Bridge](https://leetcode.com/problems/shortest-bridge/) | Medium | 6+ months | 16.2 | Todo |  |  |  | [notes](05.%20Multi-Source%20BFS/0934.%20Shortest%20Bridge/0934.%20Shortest%20Bridge.md) |
| 6 | [1162. As Far from Land as Possible](https://leetcode.com/problems/as-far-from-land-as-possible/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](05.%20Multi-Source%20BFS/1162.%20As%20Far%20from%20Land%20as%20Possible/1162.%20As%20Far%20from%20Land%20as%20Possible.md) |
| 7 | [2258. Escape the Spreading Fire](https://leetcode.com/problems/escape-the-spreading-fire/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Multi-Source%20BFS/2258.%20Escape%20the%20Spreading%20Fire/2258.%20Escape%20the%20Spreading%20Fire.md) |
| 8 | [1765. Map of Highest Peak](https://leetcode.com/problems/map-of-highest-peak/) | Medium | 6+ months | 29.6 | ✅ Solved |  |  |  | [notes](05.%20Multi-Source%20BFS/1765.%20Map%20of%20Highest%20Peak/1765.%20Map%20of%20Highest%20Peak.md) |

## 06. Topological Sort

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [207. Course Schedule](https://leetcode.com/problems/course-schedule/) | Medium | 3 months | 55.0 | ✅ Solved |  |  |  | [notes](06.%20Topological%20Sort/0207.%20Course%20Schedule/0207.%20Course%20Schedule.md) |
| 2 | [269. Alien Dictionary](https://leetcode.com/problems/alien-dictionary/) 🔒 | Hard | 3 months | 41.3 | ✅ Solved |  |  |  | [notes](06.%20Topological%20Sort/0269.%20Alien%20Dictionary/0269.%20Alien%20Dictionary.md) |
| 3 | [310. Minimum Height Trees](https://leetcode.com/problems/minimum-height-trees/) | Medium | 3 months | 39.1 | ✅ Solved |  |  |  | [notes](06.%20Topological%20Sort/0310.%20Minimum%20Height%20Trees/0310.%20Minimum%20Height%20Trees.md) |
| 4 | [210. Course Schedule II](https://leetcode.com/problems/course-schedule-ii/) | Medium | 3 months | 38.6 | ✅ Solved |  |  |  | [notes](06.%20Topological%20Sort/0210.%20Course%20Schedule%20II/0210.%20Course%20Schedule%20II.md) |
| 5 | [444. Sequence Reconstruction](https://leetcode.com/problems/sequence-reconstruction/) 🔒 | Medium | 6 months | 40.3 | Todo |  |  |  | [notes](06.%20Topological%20Sort/0444.%20Sequence%20Reconstruction/0444.%20Sequence%20Reconstruction.md) |
| 6 | [2115. Find All Possible Recipes from Given Supplies](https://leetcode.com/problems/find-all-possible-recipes-from-given-supplies/) | Medium | 6+ months | 36.0 | Todo |  |  |  | [notes](06.%20Topological%20Sort/2115.%20Find%20All%20Possible%20Recipes%20from%20Given%20Supplies/2115.%20Find%20All%20Possible%20Recipes%20from%20Given%20Supplies.md) |
| 7 | [2392. Build a Matrix With Conditions](https://leetcode.com/problems/build-a-matrix-with-conditions/) | Hard | 6+ months | 32.3 | Todo |  |  |  | [notes](06.%20Topological%20Sort/2392.%20Build%20a%20Matrix%20With%20Conditions/2392.%20Build%20a%20Matrix%20With%20Conditions.md) |
| 8 | [1557. Minimum Number of Vertices to Reach All Nodes](https://leetcode.com/problems/minimum-number-of-vertices-to-reach-all-nodes/) | Medium | 6+ months | 31.9 | Todo |  |  |  | [notes](06.%20Topological%20Sort/1557.%20Minimum%20Number%20of%20Vertices%20to%20Reach%20All%20Nodes/1557.%20Minimum%20Number%20of%20Vertices%20to%20Reach%20All%20Nodes.md) |
| 9 | [1136. Parallel Courses](https://leetcode.com/problems/parallel-courses/) 🔒 | Medium | 6+ months | 31.6 | Todo |  |  |  | [notes](06.%20Topological%20Sort/1136.%20Parallel%20Courses/1136.%20Parallel%20Courses.md) |
| 10 | [2050. Parallel Courses III](https://leetcode.com/problems/parallel-courses-iii/) | Hard | 6+ months | 31.6 | Todo |  |  |  | [notes](06.%20Topological%20Sort/2050.%20Parallel%20Courses%20III/2050.%20Parallel%20Courses%20III.md) |
| 11 | [2192. All Ancestors of a Node in a Directed Acyclic Graph](https://leetcode.com/problems/all-ancestors-of-a-node-in-a-directed-acyclic-graph/) | Medium | 6+ months | 30.8 | Todo |  |  |  | [notes](06.%20Topological%20Sort/2192.%20All%20Ancestors%20of%20a%20Node%20in%20a%20Directed%20Acyclic%20Graph/2192.%20All%20Ancestors%20of%20a%20Node%20in%20a%20Directed%20Acyclic%20Graph.md) |
| 12 | [1857. Largest Color Value in a Directed Graph](https://leetcode.com/problems/largest-color-value-in-a-directed-graph/) | Hard | 6+ months | 30.7 | Todo |  |  |  | [notes](06.%20Topological%20Sort/1857.%20Largest%20Color%20Value%20in%20a%20Directed%20Graph/1857.%20Largest%20Color%20Value%20in%20a%20Directed%20Graph.md) |
| 13 | [1462. Course Schedule IV](https://leetcode.com/problems/course-schedule-iv/) | Medium | 6+ months | 7.2 | Todo |  |  |  | [notes](06.%20Topological%20Sort/1462.%20Course%20Schedule%20IV/1462.%20Course%20Schedule%20IV.md) |
| 14 | [1203. Sort Items by Groups Respecting Dependencies](https://leetcode.com/problems/sort-items-by-groups-respecting-dependencies/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20Topological%20Sort/1203.%20Sort%20Items%20by%20Groups%20Respecting%20Dependencies/1203.%20Sort%20Items%20by%20Groups%20Respecting%20Dependencies.md) |
| 15 | [2603. Collect Coins in a Tree](https://leetcode.com/problems/collect-coins-in-a-tree/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20Topological%20Sort/2603.%20Collect%20Coins%20in%20a%20Tree/2603.%20Collect%20Coins%20in%20a%20Tree.md) |
| 16 | [2924. Find Champion II](https://leetcode.com/problems/find-champion-ii/) | Medium | 6+ months | 30.4 | Todo |  |  |  | [notes](06.%20Topological%20Sort/2924.%20Find%20Champion%20II/2924.%20Find%20Champion%20II.md) |
| 17 | [1591. Strange Printer II](https://leetcode.com/problems/strange-printer-ii/) | Hard | 6+ months | 30.1 | Todo |  |  |  | [notes](06.%20Topological%20Sort/1591.%20Strange%20Printer%20II/1591.%20Strange%20Printer%20II.md) |

## 07. Cycle Detection

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [802. Find Eventual Safe States](https://leetcode.com/problems/find-eventual-safe-states/) | Medium | 6 months | 37.5 | ✅ Solved |  |  |  | [notes](07.%20Cycle%20Detection/0802.%20Find%20Eventual%20Safe%20States/0802.%20Find%20Eventual%20Safe%20States.md) |
| 2 | [1559. Detect Cycles in 2D Grid](https://leetcode.com/problems/detect-cycles-in-2d-grid/) | Medium | 6+ months | 13.4 | ✅ Solved |  |  |  | [notes](07.%20Cycle%20Detection/1559.%20Detect%20Cycles%20in%202D%20Grid/1559.%20Detect%20Cycles%20in%202D%20Grid.md) |
| 3 | [2127. Maximum Employees to Be Invited to a Meeting](https://leetcode.com/problems/maximum-employees-to-be-invited-to-a-meeting/) | Hard | 6+ months | 11.0 | Todo |  |  |  | [notes](07.%20Cycle%20Detection/2127.%20Maximum%20Employees%20to%20Be%20Invited%20to%20a%20Meeting/2127.%20Maximum%20Employees%20to%20Be%20Invited%20to%20a%20Meeting.md) |
| 4 | [2360. Longest Cycle in a Graph](https://leetcode.com/problems/longest-cycle-in-a-graph/) | Hard | 6+ months | 8.7 | Todo |  |  |  | [notes](07.%20Cycle%20Detection/2360.%20Longest%20Cycle%20in%20a%20Graph/2360.%20Longest%20Cycle%20in%20a%20Graph.md) |
| 5 | [1059. All Paths from Source Lead to Destination](https://leetcode.com/problems/all-paths-from-source-lead-to-destination/) 🔒 | Medium | 6+ months | 29.5 | Todo |  |  |  | [notes](07.%20Cycle%20Detection/1059.%20All%20Paths%20from%20Source%20Lead%20to%20Destination/1059.%20All%20Paths%20from%20Source%20Lead%20to%20Destination.md) |
| 6 | [1153. String Transforms Into Another String](https://leetcode.com/problems/string-transforms-into-another-string/) 🔒 | Hard | 6+ months | 28.8 | Todo |  |  |  | [notes](07.%20Cycle%20Detection/1153.%20String%20Transforms%20Into%20Another%20String/1153.%20String%20Transforms%20Into%20Another%20String.md) |
| 7 | [2077. Paths in Maze That Lead to Same Room](https://leetcode.com/problems/paths-in-maze-that-lead-to-same-room/) 🔒 | Medium | 6+ months | 28.8 | Todo |  |  |  | [notes](07.%20Cycle%20Detection/2077.%20Paths%20in%20Maze%20That%20Lead%20to%20Same%20Room/2077.%20Paths%20in%20Maze%20That%20Lead%20to%20Same%20Room.md) |
| 8 | [2608. Shortest Cycle in a Graph](https://leetcode.com/problems/shortest-cycle-in-a-graph/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](07.%20Cycle%20Detection/2608.%20Shortest%20Cycle%20in%20a%20Graph/2608.%20Shortest%20Cycle%20in%20a%20Graph.md) |

## 08. Bipartite & Graph Coloring

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [785. Is Graph Bipartite?](https://leetcode.com/problems/is-graph-bipartite/) | Medium | 3 months | 25.9 | ✅ Solved |  |  |  | [notes](08.%20Bipartite%20%26%20Graph%20Coloring/0785.%20Is%20Graph%20Bipartite%3F/0785.%20Is%20Graph%20Bipartite%3F.md) |
| 2 | [2493. Divide Nodes Into the Maximum Number of Groups](https://leetcode.com/problems/divide-nodes-into-the-maximum-number-of-groups/) | Hard | 6+ months | 5.8 | Todo |  |  |  | [notes](08.%20Bipartite%20%26%20Graph%20Coloring/2493.%20Divide%20Nodes%20Into%20the%20Maximum%20Number%20of%20Groups/2493.%20Divide%20Nodes%20Into%20the%20Maximum%20Number%20of%20Groups.md) |
| 3 | [886. Possible Bipartition](https://leetcode.com/problems/possible-bipartition/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Bipartite%20%26%20Graph%20Coloring/0886.%20Possible%20Bipartition/0886.%20Possible%20Bipartition.md) |
| 4 | [3373. Maximize the Number of Target Nodes After Connecting Trees II](https://leetcode.com/problems/maximize-the-number-of-target-nodes-after-connecting-trees-ii/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Bipartite%20%26%20Graph%20Coloring/3373.%20Maximize%20the%20Number%20of%20Target%20Nodes%20After%20Connecting%20Trees%20II/3373.%20Maximize%20the%20Number%20of%20Target%20Nodes%20After%20Connecting%20Trees%20II.md) |

## 09. Clone & Build Graph

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203; | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [133. Clone Graph](https://leetcode.com/problems/clone-graph/) | Medium | 6 months | 45.6 | Todo |  |  |  | [notes](09.%20Clone%20%26%20Build%20Graph/0133.%20Clone%20Graph/0133.%20Clone%20Graph.md) |

## 10. Implicit Graph BFS (Word Ladder, Lock)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [127. Word Ladder](https://leetcode.com/problems/word-ladder/) | Hard | 3 months | 38.7 | ✅ Solved |  |  |  | [notes](10.%20Implicit%20Graph%20BFS%20%28Word%20Ladder%2C%20Lock%29/0127.%20Word%20Ladder/0127.%20Word%20Ladder.md) |
| 2 | [815. Bus Routes](https://leetcode.com/problems/bus-routes/) | Hard | 6 months | 41.4 | Todo |  |  |  | [notes](10.%20Implicit%20Graph%20BFS%20%28Word%20Ladder%2C%20Lock%29/0815.%20Bus%20Routes/0815.%20Bus%20Routes.md) |
| 3 | [864. Shortest Path to Get All Keys](https://leetcode.com/problems/shortest-path-to-get-all-keys/) | Hard | 6 months | 31.8 | Todo |  |  |  | [notes](10.%20Implicit%20Graph%20BFS%20%28Word%20Ladder%2C%20Lock%29/0864.%20Shortest%20Path%20to%20Get%20All%20Keys/0864.%20Shortest%20Path%20to%20Get%20All%20Keys.md) |
| 4 | [126. Word Ladder II](https://leetcode.com/problems/word-ladder-ii/) | Hard | 6 months | 26.3 | ✅ Solved |  |  |  | [notes](10.%20Implicit%20Graph%20BFS%20%28Word%20Ladder%2C%20Lock%29/0126.%20Word%20Ladder%20II/0126.%20Word%20Ladder%20II.md) |
| 5 | [433. Minimum Genetic Mutation](https://leetcode.com/problems/minimum-genetic-mutation/) | Medium | 6 months | 15.6 | ✅ Solved |  |  |  | [notes](10.%20Implicit%20Graph%20BFS%20%28Word%20Ladder%2C%20Lock%29/0433.%20Minimum%20Genetic%20Mutation/0433.%20Minimum%20Genetic%20Mutation.md) |
| 6 | [818. Race Car](https://leetcode.com/problems/race-car/) | Hard | 6+ months | 35.4 | Todo |  |  |  | [notes](10.%20Implicit%20Graph%20BFS%20%28Word%20Ladder%2C%20Lock%29/0818.%20Race%20Car/0818.%20Race%20Car.md) |
| 7 | [1345. Jump Game IV](https://leetcode.com/problems/jump-game-iv/) | Hard | 6+ months | 32.9 | Todo |  |  |  | [notes](10.%20Implicit%20Graph%20BFS%20%28Word%20Ladder%2C%20Lock%29/1345.%20Jump%20Game%20IV/1345.%20Jump%20Game%20IV.md) |
| 8 | [1197. Minimum Knight Moves](https://leetcode.com/problems/minimum-knight-moves/) 🔒 | Medium | 6+ months | 30.8 | Todo |  |  |  | [notes](10.%20Implicit%20Graph%20BFS%20%28Word%20Ladder%2C%20Lock%29/1197.%20Minimum%20Knight%20Moves/1197.%20Minimum%20Knight%20Moves.md) |
| 9 | [854. K-Similar Strings](https://leetcode.com/problems/k-similar-strings/) | Hard | 6+ months | 30.2 | Todo |  |  |  | [notes](10.%20Implicit%20Graph%20BFS%20%28Word%20Ladder%2C%20Lock%29/0854.%20K-Similar%20Strings/0854.%20K-Similar%20Strings.md) |
| 10 | [3666. Minimum Operations to Equalize Binary String](https://leetcode.com/problems/minimum-operations-to-equalize-binary-string/) | Hard | 6+ months | 5.4 | Todo |  |  |  | [notes](10.%20Implicit%20Graph%20BFS%20%28Word%20Ladder%2C%20Lock%29/3666.%20Minimum%20Operations%20to%20Equalize%20Binary%20String/3666.%20Minimum%20Operations%20to%20Equalize%20Binary%20String.md) |
| 11 | [1263. Minimum Moves to Move a Box to Their Target Location](https://leetcode.com/problems/minimum-moves-to-move-a-box-to-their-target-location/) | Hard | 6+ months | 5.2 | Todo |  |  |  | [notes](10.%20Implicit%20Graph%20BFS%20%28Word%20Ladder%2C%20Lock%29/1263.%20Minimum%20Moves%20to%20Move%20a%20Box%20to%20Their%20Target%20Location/1263.%20Minimum%20Moves%20to%20Move%20a%20Box%20to%20Their%20Target%20Location.md) |
| 12 | [488. Zuma Game](https://leetcode.com/problems/zuma-game/) | Hard | 6+ months | 5.1 | Todo |  |  |  | [notes](10.%20Implicit%20Graph%20BFS%20%28Word%20Ladder%2C%20Lock%29/0488.%20Zuma%20Game/0488.%20Zuma%20Game.md) |
| 13 | [752. Open the Lock](https://leetcode.com/problems/open-the-lock/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](10.%20Implicit%20Graph%20BFS%20%28Word%20Ladder%2C%20Lock%29/0752.%20Open%20the%20Lock/0752.%20Open%20the%20Lock.md) |
| 14 | [3629. Minimum Jumps to Reach End via Prime Teleportation](https://leetcode.com/problems/minimum-jumps-to-reach-end-via-prime-teleportation/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](10.%20Implicit%20Graph%20BFS%20%28Word%20Ladder%2C%20Lock%29/3629.%20Minimum%20Jumps%20to%20Reach%20End%20via%20Prime%20Teleportation/3629.%20Minimum%20Jumps%20to%20Reach%20End%20via%20Prime%20Teleportation.md) |
| 15 | [2059. Minimum Operations to Convert Number](https://leetcode.com/problems/minimum-operations-to-convert-number/) | Medium | 6+ months | 29.3 | Todo |  |  |  | [notes](10.%20Implicit%20Graph%20BFS%20%28Word%20Ladder%2C%20Lock%29/2059.%20Minimum%20Operations%20to%20Convert%20Number/2059.%20Minimum%20Operations%20to%20Convert%20Number.md) |
| 16 | [773. Sliding Puzzle](https://leetcode.com/problems/sliding-puzzle/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](10.%20Implicit%20Graph%20BFS%20%28Word%20Ladder%2C%20Lock%29/0773.%20Sliding%20Puzzle/0773.%20Sliding%20Puzzle.md) |
