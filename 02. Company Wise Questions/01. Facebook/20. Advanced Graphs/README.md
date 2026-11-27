# 20. Advanced Graphs

[Back to Facebook](../README.md) · [Back to DSA Notes](../../../README.md)

31 Meta (Facebook) problems: 0 Easy, 20 Medium, 11 Hard, in 7 sub-patterns.

## Sub-patterns

| # | Sub-pattern | Questions | Easy | Medium | Hard | Last 3 Months | Solved | Most Asked |
|:---:|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---|
| 01 | [Union-Find (Disjoint Set)](#01-union-find-disjoint-set) | 13 | 0 | 9 | 4 | 0 | 6 | 721. Accounts Merge, 261. Graph Valid Tree, 684. Redundant Connection |
| 02 | [Dijkstra's Algorithm](#02-dijkstras-algorithm) | 9 | 0 | 6 | 3 | 0 | 4 | 778. Swim in Rising Water, 1928. Minimum Cost to Reach Destination in Time, 1810. Minimum Path Cost in a Hidden Grid |
| 03 | [Bellman-Ford & Floyd-Warshall](#03-bellman-ford--floyd-warshall) | 2 | 0 | 2 | 0 | 0 | 1 | 787. Cheapest Flights Within K Stops, 1334. Find the City With the Smallest Number of Neighbors at a Threshold Distance |
| 04 | [0-1 BFS](#04-0-1-bfs) | 3 | 0 | 2 | 1 | 0 | 1 | 1368. Minimum Cost to Make at Least One Valid Path in a Grid, 3286. Find a Safe Walk Through a Grid, 3552. Grid Teleportation Traversal |
| 05 | [Minimum Spanning Tree](#05-minimum-spanning-tree) | 2 | 0 | 1 | 1 | 0 | 0 | 1584. Min Cost to Connect All Points, 1489. Find Critical and Pseudo-Critical Edges in Minimum Spanning Tree |
| 06 | [Strongly Connected Components & Bridges](#06-strongly-connected-components--bridges) | 1 | 0 | 0 | 1 | 0 | 0 | 1192. Critical Connections in a Network |
| 07 | [Eulerian Path](#07-eulerian-path) | 1 | 0 | 0 | 1 | 0 | 0 | 332. Reconstruct Itinerary |

**Columns**

- **Last Asked**: most recent LeetCode window that lists the problem for Meta (30 days, 3 months, 6 months or 6+ months).
- **Frequency**: LeetCode frequency score (0-100) in the Meta "All" list.
- **Status**: your LeetCode status on the day this file was generated. 🔒 after a title means LeetCode Premium.
- **Logic / Key Idea, Time, Space**: fill these in as you solve. A rebuild keeps what you typed.
- **Notes**: link to the problem's notes file.

Inside each sub-pattern, rows are sorted by most recent window, then by frequency (highest first).

## 01. Union-Find (Disjoint Set)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [721. Accounts Merge](https://leetcode.com/problems/accounts-merge/) | Medium | 6+ months | 60.6 | ✅ Solved |  |  |  | [notes](01.%20Union-Find%20%28Disjoint%20Set%29/0721.%20Accounts%20Merge/0721.%20Accounts%20Merge.md) |
| 2 | [261. Graph Valid Tree](https://leetcode.com/problems/graph-valid-tree/) 🔒 | Medium | 6+ months | 37.6 | Todo |  |  |  | [notes](01.%20Union-Find%20%28Disjoint%20Set%29/0261.%20Graph%20Valid%20Tree/0261.%20Graph%20Valid%20Tree.md) |
| 3 | [684. Redundant Connection](https://leetcode.com/problems/redundant-connection/) | Medium | 6+ months | 18.3 | ✅ Solved |  |  |  | [notes](01.%20Union-Find%20%28Disjoint%20Set%29/0684.%20Redundant%20Connection/0684.%20Redundant%20Connection.md) |
| 4 | [1319. Number of Operations to Make Network Connected](https://leetcode.com/problems/number-of-operations-to-make-network-connected/) | Medium | 6+ months | 14.2 | ✅ Solved |  |  |  | [notes](01.%20Union-Find%20%28Disjoint%20Set%29/1319.%20Number%20of%20Operations%20to%20Make%20Network%20Connected/1319.%20Number%20of%20Operations%20to%20Make%20Network%20Connected.md) |
| 5 | [1970. Last Day Where You Can Still Cross](https://leetcode.com/problems/last-day-where-you-can-still-cross/) | Hard | 6+ months | 9.5 | Todo |  |  |  | [notes](01.%20Union-Find%20%28Disjoint%20Set%29/1970.%20Last%20Day%20Where%20You%20Can%20Still%20Cross/1970.%20Last%20Day%20Where%20You%20Can%20Still%20Cross.md) |
| 6 | [305. Number of Islands II](https://leetcode.com/problems/number-of-islands-ii/) 🔒 | Hard | 6+ months | 8.8 | ✅ Solved |  |  |  | [notes](01.%20Union-Find%20%28Disjoint%20Set%29/0305.%20Number%20of%20Islands%20II/0305.%20Number%20of%20Islands%20II.md) |
| 7 | [3532. Path Existence Queries in a Graph I](https://leetcode.com/problems/path-existence-queries-in-a-graph-i/) | Medium | 6+ months | 8.5 | Todo |  |  |  | [notes](01.%20Union-Find%20%28Disjoint%20Set%29/3532.%20Path%20Existence%20Queries%20in%20a%20Graph%20I/3532.%20Path%20Existence%20Queries%20in%20a%20Graph%20I.md) |
| 8 | [947. Most Stones Removed with Same Row or Column](https://leetcode.com/problems/most-stones-removed-with-same-row-or-column/) | Medium | 6+ months | 8.2 | ✅ Solved |  |  |  | [notes](01.%20Union-Find%20%28Disjoint%20Set%29/0947.%20Most%20Stones%20Removed%20with%20Same%20Row%20or%20Column/0947.%20Most%20Stones%20Removed%20with%20Same%20Row%20or%20Column.md) |
| 9 | [3607. Power Grid Maintenance](https://leetcode.com/problems/power-grid-maintenance/) | Medium | 6+ months | 7.0 | Todo |  |  |  | [notes](01.%20Union-Find%20%28Disjoint%20Set%29/3607.%20Power%20Grid%20Maintenance/3607.%20Power%20Grid%20Maintenance.md) |
| 10 | [1632. Rank Transform of a Matrix](https://leetcode.com/problems/rank-transform-of-a-matrix/) | Hard | 6+ months | 5.2 | Todo |  |  |  | [notes](01.%20Union-Find%20%28Disjoint%20Set%29/1632.%20Rank%20Transform%20of%20a%20Matrix/1632.%20Rank%20Transform%20of%20a%20Matrix.md) |
| 11 | [990. Satisfiability of Equality Equations](https://leetcode.com/problems/satisfiability-of-equality-equations/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](01.%20Union-Find%20%28Disjoint%20Set%29/0990.%20Satisfiability%20of%20Equality%20Equations/0990.%20Satisfiability%20of%20Equality%20Equations.md) |
| 12 | [1061. Lexicographically Smallest Equivalent String](https://leetcode.com/problems/lexicographically-smallest-equivalent-string/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Union-Find%20%28Disjoint%20Set%29/1061.%20Lexicographically%20Smallest%20Equivalent%20String/1061.%20Lexicographically%20Smallest%20Equivalent%20String.md) |
| 13 | [3108. Minimum Cost Walk in Weighted Graph](https://leetcode.com/problems/minimum-cost-walk-in-weighted-graph/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Union-Find%20%28Disjoint%20Set%29/3108.%20Minimum%20Cost%20Walk%20in%20Weighted%20Graph/3108.%20Minimum%20Cost%20Walk%20in%20Weighted%20Graph.md) |

## 02. Dijkstra's Algorithm

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [778. Swim in Rising Water](https://leetcode.com/problems/swim-in-rising-water/) | Hard | 6+ months | 39.3 | ✅ Solved |  |  |  | [notes](02.%20Dijkstra%27s%20Algorithm/0778.%20Swim%20in%20Rising%20Water/0778.%20Swim%20in%20Rising%20Water.md) |
| 2 | [1928. Minimum Cost to Reach Destination in Time](https://leetcode.com/problems/minimum-cost-to-reach-destination-in-time/) | Hard | 6+ months | 37.8 | Todo |  |  |  | [notes](02.%20Dijkstra%27s%20Algorithm/1928.%20Minimum%20Cost%20to%20Reach%20Destination%20in%20Time/1928.%20Minimum%20Cost%20to%20Reach%20Destination%20in%20Time.md) |
| 3 | [1810. Minimum Path Cost in a Hidden Grid](https://leetcode.com/problems/minimum-path-cost-in-a-hidden-grid/) 🔒 | Medium | 6+ months | 37.2 | Todo |  |  |  | [notes](02.%20Dijkstra%27s%20Algorithm/1810.%20Minimum%20Path%20Cost%20in%20a%20Hidden%20Grid/1810.%20Minimum%20Path%20Cost%20in%20a%20Hidden%20Grid.md) |
| 4 | [3651. Minimum Cost Path with Teleportations](https://leetcode.com/problems/minimum-cost-path-with-teleportations/) | Hard | 6+ months | 11.4 | Todo |  |  |  | [notes](02.%20Dijkstra%27s%20Algorithm/3651.%20Minimum%20Cost%20Path%20with%20Teleportations/3651.%20Minimum%20Cost%20Path%20with%20Teleportations.md) |
| 5 | [505. The Maze II](https://leetcode.com/problems/the-maze-ii/) 🔒 | Medium | 6+ months | 5.9 | Todo |  |  |  | [notes](02.%20Dijkstra%27s%20Algorithm/0505.%20The%20Maze%20II/0505.%20The%20Maze%20II.md) |
| 6 | [743. Network Delay Time](https://leetcode.com/problems/network-delay-time/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](02.%20Dijkstra%27s%20Algorithm/0743.%20Network%20Delay%20Time/0743.%20Network%20Delay%20Time.md) |
| 7 | [1631. Path With Minimum Effort](https://leetcode.com/problems/path-with-minimum-effort/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](02.%20Dijkstra%27s%20Algorithm/1631.%20Path%20With%20Minimum%20Effort/1631.%20Path%20With%20Minimum%20Effort.md) |
| 8 | [3650. Minimum Cost Path with Edge Reversals](https://leetcode.com/problems/minimum-cost-path-with-edge-reversals/) | Medium | 6+ months | 37.0 | Todo |  |  |  | [notes](02.%20Dijkstra%27s%20Algorithm/3650.%20Minimum%20Cost%20Path%20with%20Edge%20Reversals/3650.%20Minimum%20Cost%20Path%20with%20Edge%20Reversals.md) |
| 9 | [1976. Number of Ways to Arrive at Destination](https://leetcode.com/problems/number-of-ways-to-arrive-at-destination/) | Medium | 6+ months | 36.1 | ✅ Solved |  |  |  | [notes](02.%20Dijkstra%27s%20Algorithm/1976.%20Number%20of%20Ways%20to%20Arrive%20at%20Destination/1976.%20Number%20of%20Ways%20to%20Arrive%20at%20Destination.md) |

## 03. Bellman-Ford & Floyd-Warshall

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [787. Cheapest Flights Within K Stops](https://leetcode.com/problems/cheapest-flights-within-k-stops/) | Medium | 6 months | 24.2 | ✅ Solved |  |  |  | [notes](03.%20Bellman-Ford%20%26%20Floyd-Warshall/0787.%20Cheapest%20Flights%20Within%20K%20Stops/0787.%20Cheapest%20Flights%20Within%20K%20Stops.md) |
| 2 | [1334. Find the City With the Smallest Number of Neighbors at a Threshold Distance](https://leetcode.com/problems/find-the-city-with-the-smallest-number-of-neighbors-at-a-threshold-distance/) | Medium | 6+ months | 5.1 | Todo |  |  |  | [notes](03.%20Bellman-Ford%20%26%20Floyd-Warshall/1334.%20Find%20the%20City%20With%20the%20Smallest%20Number%20of%20Neighbors%20at%20a%20Threshold%20Distance/1334.%20Find%20the%20City%20With%20the%20Smallest%20Number%20of%20Neighbors%20at%20a%20Threshold%20Distance.md) |

## 04. 0-1 BFS

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [1368. Minimum Cost to Make at Least One Valid Path in a Grid](https://leetcode.com/problems/minimum-cost-to-make-at-least-one-valid-path-in-a-grid/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%200-1%20BFS/1368.%20Minimum%20Cost%20to%20Make%20at%20Least%20One%20Valid%20Path%20in%20a%20Grid/1368.%20Minimum%20Cost%20to%20Make%20at%20Least%20One%20Valid%20Path%20in%20a%20Grid.md) |
| 2 | [3552. Grid Teleportation Traversal](https://leetcode.com/problems/grid-teleportation-traversal/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%200-1%20BFS/3552.%20Grid%20Teleportation%20Traversal/3552.%20Grid%20Teleportation%20Traversal.md) |
| 3 | [3286. Find a Safe Walk Through a Grid](https://leetcode.com/problems/find-a-safe-walk-through-a-grid/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](04.%200-1%20BFS/3286.%20Find%20a%20Safe%20Walk%20Through%20a%20Grid/3286.%20Find%20a%20Safe%20Walk%20Through%20a%20Grid.md) |

## 05. Minimum Spanning Tree

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [1584. Min Cost to Connect All Points](https://leetcode.com/problems/min-cost-to-connect-all-points/) | Medium | 6+ months | 12.5 | Todo |  |  |  | [notes](05.%20Minimum%20Spanning%20Tree/1584.%20Min%20Cost%20to%20Connect%20All%20Points/1584.%20Min%20Cost%20to%20Connect%20All%20Points.md) |
| 2 | [1489. Find Critical and Pseudo-Critical Edges in Minimum Spanning Tree](https://leetcode.com/problems/find-critical-and-pseudo-critical-edges-in-minimum-spanning-tree/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Minimum%20Spanning%20Tree/1489.%20Find%20Critical%20and%20Pseudo-Critical%20Edges%20in%20Minimum%20Spanning%20Tree/1489.%20Find%20Critical%20and%20Pseudo-Critical%20Edges%20in%20Minimum%20Spanning%20Tree.md) |

## 06. Strongly Connected Components & Bridges

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [1192. Critical Connections in a Network](https://leetcode.com/problems/critical-connections-in-a-network/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20Strongly%20Connected%20Components%20%26%20Bridges/1192.%20Critical%20Connections%20in%20a%20Network/1192.%20Critical%20Connections%20in%20a%20Network.md) |

## 07. Eulerian Path

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea&ensp;&#8203; | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [332. Reconstruct Itinerary](https://leetcode.com/problems/reconstruct-itinerary/) | Hard | 6+ months | 6.4 | Todo |  |  |  | [notes](07.%20Eulerian%20Path/0332.%20Reconstruct%20Itinerary/0332.%20Reconstruct%20Itinerary.md) |
