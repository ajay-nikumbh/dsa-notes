# 19. Graphs

[Back to Facebook](../README.md) · [Back to DSA Notes](../../../README.md)

62 Meta (Facebook) problems: 4 Easy, 45 Medium, 13 Hard, in 10 sub-patterns.

## Sub-patterns

| # | Sub-pattern | Questions | Easy | Medium | Hard | Last 3 Months | Solved | Most Asked |
|:---:|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---|
| 01 | [Graph DFS & Connected Components](#01-graph-dfs--connected-components) | 11 | 3 | 8 | 0 | 0 | 3 | 547. Number of Provinces, 1971. Find if Path Exists in Graph, 1466. Reorder Routes to Make All Paths Lead to the City Zero |
| 02 | [Grid DFS (Islands)](#02-grid-dfs-islands) | 10 | 1 | 8 | 1 | 1 | 6 | 827. Making A Large Island, 200. Number of Islands, 695. Max Area of Island |
| 03 | [BFS Shortest Path (Unweighted)](#03-bfs-shortest-path-unweighted) | 2 | 0 | 2 | 0 | 0 | 0 | 1236. Web Crawler, 909. Snakes and Ladders |
| 04 | [Grid BFS](#04-grid-bfs) | 6 | 0 | 4 | 2 | 0 | 1 | 1091. Shortest Path in Binary Matrix, 1778. Shortest Path in a Hidden Grid, 317. Shortest Distance from All Buildings |
| 05 | [Multi-Source BFS](#05-multi-source-bfs) | 5 | 0 | 5 | 0 | 0 | 4 | 286. Walls and Gates, 934. Shortest Bridge, 994. Rotting Oranges |
| 06 | [Topological Sort](#06-topological-sort) | 11 | 0 | 8 | 3 | 1 | 4 | 207. Course Schedule, 269. Alien Dictionary, 210. Course Schedule II |
| 07 | [Cycle Detection](#07-cycle-detection) | 3 | 0 | 2 | 1 | 0 | 2 | 802. Find Eventual Safe States, 1559. Detect Cycles in 2D Grid, 2608. Shortest Cycle in a Graph |
| 08 | [Bipartite & Graph Coloring](#08-bipartite--graph-coloring) | 3 | 0 | 2 | 1 | 0 | 1 | 785. Is Graph Bipartite?, 886. Possible Bipartition, 2493. Divide Nodes Into the Maximum Number of Groups |
| 09 | [Clone & Build Graph](#09-clone--build-graph) | 1 | 0 | 1 | 0 | 0 | 0 | 133. Clone Graph |
| 10 | [Implicit Graph BFS (Word Ladder, Lock)](#10-implicit-graph-bfs-word-ladder-lock) | 10 | 0 | 5 | 5 | 0 | 4 | 127. Word Ladder, 126. Word Ladder II, 752. Open the Lock |

**Columns**

- **Last Asked**: most recent LeetCode window that lists the problem for Meta (30 days, 3 months, 6 months or 6+ months).
- **Frequency**: LeetCode frequency score (0-100) in the Meta "All" list.
- **Status**: your LeetCode status on the day this file was generated. 🔒 after a title means LeetCode Premium.
- **Logic / Key Idea, Time, Space**: fill these in as you solve. A rebuild keeps what you typed.
- **Notes**: link to the problem's notes file.

Inside each sub-pattern, rows are sorted by most recent window, then by frequency (highest first).

## 01. Graph DFS & Connected Components

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [547. Number of Provinces](https://leetcode.com/problems/number-of-provinces/) | Medium | 6 months | 31.6 | ✅ Solved |  |  |  | [notes](01.%20Graph%20DFS%20%26%20Connected%20Components/0547.%20Number%20of%20Provinces/0547.%20Number%20of%20Provinces.md) |
| 2 | [1971. Find if Path Exists in Graph](https://leetcode.com/problems/find-if-path-exists-in-graph/) | Easy | 6+ months | 18.1 | ✅ Solved |  |  |  | [notes](01.%20Graph%20DFS%20%26%20Connected%20Components/1971.%20Find%20if%20Path%20Exists%20in%20Graph/1971.%20Find%20if%20Path%20Exists%20in%20Graph.md) |
| 3 | [1466. Reorder Routes to Make All Paths Lead to the City Zero](https://leetcode.com/problems/reorder-routes-to-make-all-paths-lead-to-the-city-zero/) | Medium | 6+ months | 14.5 | Todo |  |  |  | [notes](01.%20Graph%20DFS%20%26%20Connected%20Components/1466.%20Reorder%20Routes%20to%20Make%20All%20Paths%20Lead%20to%20the%20City%20Zero/1466.%20Reorder%20Routes%20to%20Make%20All%20Paths%20Lead%20to%20the%20City%20Zero.md) |
| 4 | [841. Keys and Rooms](https://leetcode.com/problems/keys-and-rooms/) | Medium | 6+ months | 13.7 | ✅ Solved |  |  |  | [notes](01.%20Graph%20DFS%20%26%20Connected%20Components/0841.%20Keys%20and%20Rooms/0841.%20Keys%20and%20Rooms.md) |
| 5 | [399. Evaluate Division](https://leetcode.com/problems/evaluate-division/) | Medium | 6+ months | 12.3 | Todo |  |  |  | [notes](01.%20Graph%20DFS%20%26%20Connected%20Components/0399.%20Evaluate%20Division/0399.%20Evaluate%20Division.md) |
| 6 | [1743. Restore the Array From Adjacent Pairs](https://leetcode.com/problems/restore-the-array-from-adjacent-pairs/) | Medium | 6+ months | 8.0 | Todo |  |  |  | [notes](01.%20Graph%20DFS%20%26%20Connected%20Components/1743.%20Restore%20the%20Array%20From%20Adjacent%20Pairs/1743.%20Restore%20the%20Array%20From%20Adjacent%20Pairs.md) |
| 7 | [323. Number of Connected Components in an Undirected Graph](https://leetcode.com/problems/number-of-connected-components-in-an-undirected-graph/) 🔒 | Medium | 6+ months | 7.9 | Todo |  |  |  | [notes](01.%20Graph%20DFS%20%26%20Connected%20Components/0323.%20Number%20of%20Connected%20Components%20in%20an%20Undirected%20Graph/0323.%20Number%20of%20Connected%20Components%20in%20an%20Undirected%20Graph.md) |
| 8 | [797. All Paths From Source to Target](https://leetcode.com/problems/all-paths-from-source-to-target/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Graph%20DFS%20%26%20Connected%20Components/0797.%20All%20Paths%20From%20Source%20to%20Target/0797.%20All%20Paths%20From%20Source%20to%20Target.md) |
| 9 | [997. Find the Town Judge](https://leetcode.com/problems/find-the-town-judge/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Graph%20DFS%20%26%20Connected%20Components/0997.%20Find%20the%20Town%20Judge/0997.%20Find%20the%20Town%20Judge.md) |
| 10 | [1791. Find Center of Star Graph](https://leetcode.com/problems/find-center-of-star-graph/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Graph%20DFS%20%26%20Connected%20Components/1791.%20Find%20Center%20of%20Star%20Graph/1791.%20Find%20Center%20of%20Star%20Graph.md) |
| 11 | [2685. Count the Number of Complete Components](https://leetcode.com/problems/count-the-number-of-complete-components/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Graph%20DFS%20%26%20Connected%20Components/2685.%20Count%20the%20Number%20of%20Complete%20Components/2685.%20Count%20the%20Number%20of%20Complete%20Components.md) |

## 02. Grid DFS (Islands)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [200. Number of Islands](https://leetcode.com/problems/number-of-islands/) | Medium | 3 months | 64.0 | ✅ Solved |  |  |  | [notes](02.%20Grid%20DFS%20%28Islands%29/0200.%20Number%20of%20Islands/0200.%20Number%20of%20Islands.md) |
| 2 | [130. Surrounded Regions](https://leetcode.com/problems/surrounded-regions/) | Medium | 6 months | 28.7 | Todo |  |  |  | [notes](02.%20Grid%20DFS%20%28Islands%29/0130.%20Surrounded%20Regions/0130.%20Surrounded%20Regions.md) |
| 3 | [827. Making A Large Island](https://leetcode.com/problems/making-a-large-island/) | Hard | 6+ months | 72.6 | ✅ Solved |  |  |  | [notes](02.%20Grid%20DFS%20%28Islands%29/0827.%20Making%20A%20Large%20Island/0827.%20Making%20A%20Large%20Island.md) |
| 4 | [695. Max Area of Island](https://leetcode.com/problems/max-area-of-island/) | Medium | 6+ months | 41.8 | ✅ Solved |  |  |  | [notes](02.%20Grid%20DFS%20%28Islands%29/0695.%20Max%20Area%20of%20Island/0695.%20Max%20Area%20of%20Island.md) |
| 5 | [529. Minesweeper](https://leetcode.com/problems/minesweeper/) | Medium | 6+ months | 37.1 | Todo |  |  |  | [notes](02.%20Grid%20DFS%20%28Islands%29/0529.%20Minesweeper/0529.%20Minesweeper.md) |
| 6 | [733. Flood Fill](https://leetcode.com/problems/flood-fill/) | Easy | 6+ months | 17.5 | ✅ Solved |  |  |  | [notes](02.%20Grid%20DFS%20%28Islands%29/0733.%20Flood%20Fill/0733.%20Flood%20Fill.md) |
| 7 | [417. Pacific Atlantic Water Flow](https://leetcode.com/problems/pacific-atlantic-water-flow/) | Medium | 6+ months | 9.0 | ✅ Solved |  |  |  | [notes](02.%20Grid%20DFS%20%28Islands%29/0417.%20Pacific%20Atlantic%20Water%20Flow/0417.%20Pacific%20Atlantic%20Water%20Flow.md) |
| 8 | [1254. Number of Closed Islands](https://leetcode.com/problems/number-of-closed-islands/) | Medium | 6+ months | 7.8 | Todo |  |  |  | [notes](02.%20Grid%20DFS%20%28Islands%29/1254.%20Number%20of%20Closed%20Islands/1254.%20Number%20of%20Closed%20Islands.md) |
| 9 | [1020. Number of Enclaves](https://leetcode.com/problems/number-of-enclaves/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](02.%20Grid%20DFS%20%28Islands%29/1020.%20Number%20of%20Enclaves/1020.%20Number%20of%20Enclaves.md) |
| 10 | [2658. Maximum Number of Fish in a Grid](https://leetcode.com/problems/maximum-number-of-fish-in-a-grid/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Grid%20DFS%20%28Islands%29/2658.%20Maximum%20Number%20of%20Fish%20in%20a%20Grid/2658.%20Maximum%20Number%20of%20Fish%20in%20a%20Grid.md) |

## 03. BFS Shortest Path (Unweighted)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea&ensp;&#8203;&ensp;&#8203; | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [909. Snakes and Ladders](https://leetcode.com/problems/snakes-and-ladders/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](03.%20BFS%20Shortest%20Path%20%28Unweighted%29/0909.%20Snakes%20and%20Ladders/0909.%20Snakes%20and%20Ladders.md) |
| 2 | [1236. Web Crawler](https://leetcode.com/problems/web-crawler/) 🔒 | Medium | 6+ months | 36.1 | Todo |  |  |  | [notes](03.%20BFS%20Shortest%20Path%20%28Unweighted%29/1236.%20Web%20Crawler/1236.%20Web%20Crawler.md) |

## 04. Grid BFS

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [1091. Shortest Path in Binary Matrix](https://leetcode.com/problems/shortest-path-in-binary-matrix/) | Medium | 6 months | 77.3 | ✅ Solved |  |  |  | [notes](04.%20Grid%20BFS/1091.%20Shortest%20Path%20in%20Binary%20Matrix/1091.%20Shortest%20Path%20in%20Binary%20Matrix.md) |
| 2 | [1778. Shortest Path in a Hidden Grid](https://leetcode.com/problems/shortest-path-in-a-hidden-grid/) 🔒 | Medium | 6+ months | 43.8 | Todo |  |  |  | [notes](04.%20Grid%20BFS/1778.%20Shortest%20Path%20in%20a%20Hidden%20Grid/1778.%20Shortest%20Path%20in%20a%20Hidden%20Grid.md) |
| 3 | [317. Shortest Distance from All Buildings](https://leetcode.com/problems/shortest-distance-from-all-buildings/) 🔒 | Hard | 6+ months | 34.2 | Todo |  |  |  | [notes](04.%20Grid%20BFS/0317.%20Shortest%20Distance%20from%20All%20Buildings/0317.%20Shortest%20Distance%20from%20All%20Buildings.md) |
| 4 | [490. The Maze](https://leetcode.com/problems/the-maze/) 🔒 | Medium | 6+ months | 25.7 | Todo |  |  |  | [notes](04.%20Grid%20BFS/0490.%20The%20Maze/0490.%20The%20Maze.md) |
| 5 | [1926. Nearest Exit from Entrance in Maze](https://leetcode.com/problems/nearest-exit-from-entrance-in-maze/) | Medium | 6+ months | 15.8 | Todo |  |  |  | [notes](04.%20Grid%20BFS/1926.%20Nearest%20Exit%20from%20Entrance%20in%20Maze/1926.%20Nearest%20Exit%20from%20Entrance%20in%20Maze.md) |
| 6 | [1293. Shortest Path in a Grid with Obstacles Elimination](https://leetcode.com/problems/shortest-path-in-a-grid-with-obstacles-elimination/) | Hard | 6+ months | 12.2 | Todo |  |  |  | [notes](04.%20Grid%20BFS/1293.%20Shortest%20Path%20in%20a%20Grid%20with%20Obstacles%20Elimination/1293.%20Shortest%20Path%20in%20a%20Grid%20with%20Obstacles%20Elimination.md) |

## 05. Multi-Source BFS

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [994. Rotting Oranges](https://leetcode.com/problems/rotting-oranges/) | Medium | 6 months | 36.3 | ✅ Solved |  |  |  | [notes](05.%20Multi-Source%20BFS/0994.%20Rotting%20Oranges/0994.%20Rotting%20Oranges.md) |
| 2 | [286. Walls and Gates](https://leetcode.com/problems/walls-and-gates/) 🔒 | Medium | 6+ months | 48.5 | ✅ Solved |  |  |  | [notes](05.%20Multi-Source%20BFS/0286.%20Walls%20and%20Gates/0286.%20Walls%20and%20Gates.md) |
| 3 | [934. Shortest Bridge](https://leetcode.com/problems/shortest-bridge/) | Medium | 6+ months | 37.3 | Todo |  |  |  | [notes](05.%20Multi-Source%20BFS/0934.%20Shortest%20Bridge/0934.%20Shortest%20Bridge.md) |
| 4 | [542. 01 Matrix](https://leetcode.com/problems/01-matrix/) | Medium | 6+ months | 17.4 | ✅ Solved |  |  |  | [notes](05.%20Multi-Source%20BFS/0542.%2001%20Matrix/0542.%2001%20Matrix.md) |
| 5 | [2812. Find the Safest Path in a Grid](https://leetcode.com/problems/find-the-safest-path-in-a-grid/) | Medium | 6+ months | 13.8 | ✅ Solved |  |  |  | [notes](05.%20Multi-Source%20BFS/2812.%20Find%20the%20Safest%20Path%20in%20a%20Grid/2812.%20Find%20the%20Safest%20Path%20in%20a%20Grid.md) |

## 06. Topological Sort

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [207. Course Schedule](https://leetcode.com/problems/course-schedule/) | Medium | 3 months | 65.8 | ✅ Solved |  |  |  | [notes](06.%20Topological%20Sort/0207.%20Course%20Schedule/0207.%20Course%20Schedule.md) |
| 2 | [210. Course Schedule II](https://leetcode.com/problems/course-schedule-ii/) | Medium | 6 months | 51.0 | ✅ Solved |  |  |  | [notes](06.%20Topological%20Sort/0210.%20Course%20Schedule%20II/0210.%20Course%20Schedule%20II.md) |
| 3 | [269. Alien Dictionary](https://leetcode.com/problems/alien-dictionary/) 🔒 | Hard | 6+ months | 53.3 | ✅ Solved |  |  |  | [notes](06.%20Topological%20Sort/0269.%20Alien%20Dictionary/0269.%20Alien%20Dictionary.md) |
| 4 | [1857. Largest Color Value in a Directed Graph](https://leetcode.com/problems/largest-color-value-in-a-directed-graph/) | Hard | 6+ months | 7.5 | Todo |  |  |  | [notes](06.%20Topological%20Sort/1857.%20Largest%20Color%20Value%20in%20a%20Directed%20Graph/1857.%20Largest%20Color%20Value%20in%20a%20Directed%20Graph.md) |
| 5 | [2192. All Ancestors of a Node in a Directed Acyclic Graph](https://leetcode.com/problems/all-ancestors-of-a-node-in-a-directed-acyclic-graph/) | Medium | 6+ months | 5.9 | Todo |  |  |  | [notes](06.%20Topological%20Sort/2192.%20All%20Ancestors%20of%20a%20Node%20in%20a%20Directed%20Acyclic%20Graph/2192.%20All%20Ancestors%20of%20a%20Node%20in%20a%20Directed%20Acyclic%20Graph.md) |
| 6 | [310. Minimum Height Trees](https://leetcode.com/problems/minimum-height-trees/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](06.%20Topological%20Sort/0310.%20Minimum%20Height%20Trees/0310.%20Minimum%20Height%20Trees.md) |
| 7 | [851. Loud and Rich](https://leetcode.com/problems/loud-and-rich/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20Topological%20Sort/0851.%20Loud%20and%20Rich/0851.%20Loud%20and%20Rich.md) |
| 8 | [1136. Parallel Courses](https://leetcode.com/problems/parallel-courses/) 🔒 | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20Topological%20Sort/1136.%20Parallel%20Courses/1136.%20Parallel%20Courses.md) |
| 9 | [1462. Course Schedule IV](https://leetcode.com/problems/course-schedule-iv/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20Topological%20Sort/1462.%20Course%20Schedule%20IV/1462.%20Course%20Schedule%20IV.md) |
| 10 | [1557. Minimum Number of Vertices to Reach All Nodes](https://leetcode.com/problems/minimum-number-of-vertices-to-reach-all-nodes/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20Topological%20Sort/1557.%20Minimum%20Number%20of%20Vertices%20to%20Reach%20All%20Nodes/1557.%20Minimum%20Number%20of%20Vertices%20to%20Reach%20All%20Nodes.md) |
| 11 | [2603. Collect Coins in a Tree](https://leetcode.com/problems/collect-coins-in-a-tree/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20Topological%20Sort/2603.%20Collect%20Coins%20in%20a%20Tree/2603.%20Collect%20Coins%20in%20a%20Tree.md) |

## 07. Cycle Detection

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [802. Find Eventual Safe States](https://leetcode.com/problems/find-eventual-safe-states/) | Medium | 6+ months | 12.3 | ✅ Solved |  |  |  | [notes](07.%20Cycle%20Detection/0802.%20Find%20Eventual%20Safe%20States/0802.%20Find%20Eventual%20Safe%20States.md) |
| 2 | [1559. Detect Cycles in 2D Grid](https://leetcode.com/problems/detect-cycles-in-2d-grid/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](07.%20Cycle%20Detection/1559.%20Detect%20Cycles%20in%202D%20Grid/1559.%20Detect%20Cycles%20in%202D%20Grid.md) |
| 3 | [2608. Shortest Cycle in a Graph](https://leetcode.com/problems/shortest-cycle-in-a-graph/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](07.%20Cycle%20Detection/2608.%20Shortest%20Cycle%20in%20a%20Graph/2608.%20Shortest%20Cycle%20in%20a%20Graph.md) |

## 08. Bipartite & Graph Coloring

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [785. Is Graph Bipartite?](https://leetcode.com/problems/is-graph-bipartite/) | Medium | 6+ months | 38.7 | ✅ Solved |  |  |  | [notes](08.%20Bipartite%20%26%20Graph%20Coloring/0785.%20Is%20Graph%20Bipartite%3F/0785.%20Is%20Graph%20Bipartite%3F.md) |
| 2 | [886. Possible Bipartition](https://leetcode.com/problems/possible-bipartition/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Bipartite%20%26%20Graph%20Coloring/0886.%20Possible%20Bipartition/0886.%20Possible%20Bipartition.md) |
| 3 | [2493. Divide Nodes Into the Maximum Number of Groups](https://leetcode.com/problems/divide-nodes-into-the-maximum-number-of-groups/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](08.%20Bipartite%20%26%20Graph%20Coloring/2493.%20Divide%20Nodes%20Into%20the%20Maximum%20Number%20of%20Groups/2493.%20Divide%20Nodes%20Into%20the%20Maximum%20Number%20of%20Groups.md) |

## 09. Clone & Build Graph

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203; | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [133. Clone Graph](https://leetcode.com/problems/clone-graph/) | Medium | 6+ months | 70.2 | Todo |  |  |  | [notes](09.%20Clone%20%26%20Build%20Graph/0133.%20Clone%20Graph/0133.%20Clone%20Graph.md) |

## 10. Implicit Graph BFS (Word Ladder, Lock)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [127. Word Ladder](https://leetcode.com/problems/word-ladder/) | Hard | 6+ months | 58.8 | ✅ Solved |  |  |  | [notes](10.%20Implicit%20Graph%20BFS%20%28Word%20Ladder%2C%20Lock%29/0127.%20Word%20Ladder/0127.%20Word%20Ladder.md) |
| 2 | [126. Word Ladder II](https://leetcode.com/problems/word-ladder-ii/) | Hard | 6+ months | 32.5 | ✅ Solved |  |  |  | [notes](10.%20Implicit%20Graph%20BFS%20%28Word%20Ladder%2C%20Lock%29/0126.%20Word%20Ladder%20II/0126.%20Word%20Ladder%20II.md) |
| 3 | [752. Open the Lock](https://leetcode.com/problems/open-the-lock/) | Medium | 6+ months | 23.4 | ✅ Solved |  |  |  | [notes](10.%20Implicit%20Graph%20BFS%20%28Word%20Ladder%2C%20Lock%29/0752.%20Open%20the%20Lock/0752.%20Open%20the%20Lock.md) |
| 4 | [1197. Minimum Knight Moves](https://leetcode.com/problems/minimum-knight-moves/) 🔒 | Medium | 6+ months | 16.1 | Todo |  |  |  | [notes](10.%20Implicit%20Graph%20BFS%20%28Word%20Ladder%2C%20Lock%29/1197.%20Minimum%20Knight%20Moves/1197.%20Minimum%20Knight%20Moves.md) |
| 5 | [433. Minimum Genetic Mutation](https://leetcode.com/problems/minimum-genetic-mutation/) | Medium | 6+ months | 8.7 | ✅ Solved |  |  |  | [notes](10.%20Implicit%20Graph%20BFS%20%28Word%20Ladder%2C%20Lock%29/0433.%20Minimum%20Genetic%20Mutation/0433.%20Minimum%20Genetic%20Mutation.md) |
| 6 | [1345. Jump Game IV](https://leetcode.com/problems/jump-game-iv/) | Hard | 6+ months | 6.5 | Todo |  |  |  | [notes](10.%20Implicit%20Graph%20BFS%20%28Word%20Ladder%2C%20Lock%29/1345.%20Jump%20Game%20IV/1345.%20Jump%20Game%20IV.md) |
| 7 | [3690. Split and Merge Array Transformation](https://leetcode.com/problems/split-and-merge-array-transformation/) | Medium | 6+ months | 6.2 | Todo |  |  |  | [notes](10.%20Implicit%20Graph%20BFS%20%28Word%20Ladder%2C%20Lock%29/3690.%20Split%20and%20Merge%20Array%20Transformation/3690.%20Split%20and%20Merge%20Array%20Transformation.md) |
| 8 | [3629. Minimum Jumps to Reach End via Prime Teleportation](https://leetcode.com/problems/minimum-jumps-to-reach-end-via-prime-teleportation/) | Medium | 6+ months | 5.2 | Todo |  |  |  | [notes](10.%20Implicit%20Graph%20BFS%20%28Word%20Ladder%2C%20Lock%29/3629.%20Minimum%20Jumps%20to%20Reach%20End%20via%20Prime%20Teleportation/3629.%20Minimum%20Jumps%20to%20Reach%20End%20via%20Prime%20Teleportation.md) |
| 9 | [773. Sliding Puzzle](https://leetcode.com/problems/sliding-puzzle/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](10.%20Implicit%20Graph%20BFS%20%28Word%20Ladder%2C%20Lock%29/0773.%20Sliding%20Puzzle/0773.%20Sliding%20Puzzle.md) |
| 10 | [815. Bus Routes](https://leetcode.com/problems/bus-routes/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](10.%20Implicit%20Graph%20BFS%20%28Word%20Ladder%2C%20Lock%29/0815.%20Bus%20Routes/0815.%20Bus%20Routes.md) |
