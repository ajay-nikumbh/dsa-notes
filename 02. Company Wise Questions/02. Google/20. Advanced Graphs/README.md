# 20. Advanced Graphs

[Back to Google](../README.md) · [Back to DSA Notes](../../../README.md)

68 Google problems: 0 Easy, 37 Medium, 31 Hard, in 8 sub-patterns.

## Sub-patterns

| # | Sub-pattern | Questions | Easy | Medium | Hard | Last 3 Months | Solved | Most Asked |
|:---:|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---|
| 01 | [Union-Find (Disjoint Set)](#01-union-find-disjoint-set) | 34 | 0 | 17 | 17 | 7 | 6 | 1101. The Earliest Moment When Everyone Become Friends, 684. Redundant Connection, 305. Number of Islands II |
| 02 | [Dijkstra's Algorithm](#02-dijkstras-algorithm) | 19 | 0 | 13 | 6 | 5 | 5 | 778. Swim in Rising Water, 1631. Path With Minimum Effort, 743. Network Delay Time |
| 03 | [Bellman-Ford & Floyd-Warshall](#03-bellman-ford--floyd-warshall) | 3 | 0 | 3 | 0 | 1 | 1 | 787. Cheapest Flights Within K Stops, 1334. Find the City With the Smallest Number of Neighbors at a Threshold Distance, 2976. Minimum Cost to Convert String I |
| 04 | [0-1 BFS](#04-0-1-bfs) | 3 | 0 | 1 | 2 | 0 | 1 | 1368. Minimum Cost to Make at Least One Valid Path in a Grid, 2290. Minimum Obstacle Removal to Reach Corner, 3286. Find a Safe Walk Through a Grid |
| 05 | [Minimum Spanning Tree](#05-minimum-spanning-tree) | 5 | 0 | 2 | 3 | 0 | 0 | 1168. Optimize Water Distribution in a Village, 1584. Min Cost to Connect All Points, 1489. Find Critical and Pseudo-Critical Edges in Minimum Spanning Tree |
| 06 | [Strongly Connected Components & Bridges](#06-strongly-connected-components--bridges) | 1 | 0 | 0 | 1 | 1 | 0 | 1192. Critical Connections in a Network |
| 07 | [Eulerian Path](#07-eulerian-path) | 2 | 0 | 0 | 2 | 1 | 0 | 332. Reconstruct Itinerary, 753. Cracking the Safe |
| 08 | [Network Flow & Matching](#08-network-flow--matching) | 1 | 0 | 1 | 0 | 0 | 0 | 1820. Maximum Number of Accepted Invitations |

**Columns**

- **Last Asked**: most recent LeetCode window that lists the problem for Google (30 days, 3 months, 6 months, 6+ months).
- **Frequency**: LeetCode frequency score (0-100) in the Google "All" list.
- **Status**: your LeetCode status on the day this file was generated. 🔒 after a title means LeetCode Premium.
- **Logic / Key Idea, Time, Space**: fill these in as you solve. A rebuild keeps what you typed.
- **Notes**: link to the problem's notes file.

Inside each sub-pattern, rows are sorted by most recent window, then by frequency (highest first).

## 01. Union-Find (Disjoint Set)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [1101. The Earliest Moment When Everyone Become Friends](https://leetcode.com/problems/the-earliest-moment-when-everyone-become-friends/) 🔒 | Medium | 3 months | 41.2 | Todo |  |  |  | [notes](01.%20Union-Find%20%28Disjoint%20Set%29/1101.%20The%20Earliest%20Moment%20When%20Everyone%20Become%20Friends/1101.%20The%20Earliest%20Moment%20When%20Everyone%20Become%20Friends.md) |
| 2 | [261. Graph Valid Tree](https://leetcode.com/problems/graph-valid-tree/) 🔒 | Medium | 3 months | 37.4 | Todo |  |  |  | [notes](01.%20Union-Find%20%28Disjoint%20Set%29/0261.%20Graph%20Valid%20Tree/0261.%20Graph%20Valid%20Tree.md) |
| 3 | [721. Accounts Merge](https://leetcode.com/problems/accounts-merge/) | Medium | 3 months | 37.3 | ✅ Solved |  |  |  | [notes](01.%20Union-Find%20%28Disjoint%20Set%29/0721.%20Accounts%20Merge/0721.%20Accounts%20Merge.md) |
| 4 | [3532. Path Existence Queries in a Graph I](https://leetcode.com/problems/path-existence-queries-in-a-graph-i/) | Medium | 3 months | 35.8 | Todo |  |  |  | [notes](01.%20Union-Find%20%28Disjoint%20Set%29/3532.%20Path%20Existence%20Queries%20in%20a%20Graph%20I/3532.%20Path%20Existence%20Queries%20in%20a%20Graph%20I.md) |
| 5 | [765. Couples Holding Hands](https://leetcode.com/problems/couples-holding-hands/) | Hard | 3 months | 32.4 | Todo |  |  |  | [notes](01.%20Union-Find%20%28Disjoint%20Set%29/0765.%20Couples%20Holding%20Hands/0765.%20Couples%20Holding%20Hands.md) |
| 6 | [1970. Last Day Where You Can Still Cross](https://leetcode.com/problems/last-day-where-you-can-still-cross/) | Hard | 3 months | 28.6 | Todo |  |  |  | [notes](01.%20Union-Find%20%28Disjoint%20Set%29/1970.%20Last%20Day%20Where%20You%20Can%20Still%20Cross/1970.%20Last%20Day%20Where%20You%20Can%20Still%20Cross.md) |
| 7 | [990. Satisfiability of Equality Equations](https://leetcode.com/problems/satisfiability-of-equality-equations/) | Medium | 3 months | 17.6 | ✅ Solved |  |  |  | [notes](01.%20Union-Find%20%28Disjoint%20Set%29/0990.%20Satisfiability%20of%20Equality%20Equations/0990.%20Satisfiability%20of%20Equality%20Equations.md) |
| 8 | [684. Redundant Connection](https://leetcode.com/problems/redundant-connection/) | Medium | 6 months | 40.4 | ✅ Solved |  |  |  | [notes](01.%20Union-Find%20%28Disjoint%20Set%29/0684.%20Redundant%20Connection/0684.%20Redundant%20Connection.md) |
| 9 | [2421. Number of Good Paths](https://leetcode.com/problems/number-of-good-paths/) | Hard | 6 months | 34.7 | Todo |  |  |  | [notes](01.%20Union-Find%20%28Disjoint%20Set%29/2421.%20Number%20of%20Good%20Paths/2421.%20Number%20of%20Good%20Paths.md) |
| 10 | [947. Most Stones Removed with Same Row or Column](https://leetcode.com/problems/most-stones-removed-with-same-row-or-column/) | Medium | 6 months | 15.6 | ✅ Solved |  |  |  | [notes](01.%20Union-Find%20%28Disjoint%20Set%29/0947.%20Most%20Stones%20Removed%20with%20Same%20Row%20or%20Column/0947.%20Most%20Stones%20Removed%20with%20Same%20Row%20or%20Column.md) |
| 11 | [2492. Minimum Score of a Path Between Two Cities](https://leetcode.com/problems/minimum-score-of-a-path-between-two-cities/) | Medium | 6 months | 7.8 | Todo |  |  |  | [notes](01.%20Union-Find%20%28Disjoint%20Set%29/2492.%20Minimum%20Score%20of%20a%20Path%20Between%20Two%20Cities/2492.%20Minimum%20Score%20of%20a%20Path%20Between%20Two%20Cities.md) |
| 12 | [305. Number of Islands II](https://leetcode.com/problems/number-of-islands-ii/) 🔒 | Hard | 6+ months | 39.5 | ✅ Solved |  |  |  | [notes](01.%20Union-Find%20%28Disjoint%20Set%29/0305.%20Number%20of%20Islands%20II/0305.%20Number%20of%20Islands%20II.md) |
| 13 | [1722. Minimize Hamming Distance After Swap Operations](https://leetcode.com/problems/minimize-hamming-distance-after-swap-operations/) | Medium | 6+ months | 35.1 | Todo |  |  |  | [notes](01.%20Union-Find%20%28Disjoint%20Set%29/1722.%20Minimize%20Hamming%20Distance%20After%20Swap%20Operations/1722.%20Minimize%20Hamming%20Distance%20After%20Swap%20Operations.md) |
| 14 | [2092. Find All People With Secret](https://leetcode.com/problems/find-all-people-with-secret/) | Hard | 6+ months | 33.5 | Todo |  |  |  | [notes](01.%20Union-Find%20%28Disjoint%20Set%29/2092.%20Find%20All%20People%20With%20Secret/2092.%20Find%20All%20People%20With%20Secret.md) |
| 15 | [839. Similar String Groups](https://leetcode.com/problems/similar-string-groups/) | Hard | 6+ months | 31.2 | Todo |  |  |  | [notes](01.%20Union-Find%20%28Disjoint%20Set%29/0839.%20Similar%20String%20Groups/0839.%20Similar%20String%20Groups.md) |
| 16 | [1632. Rank Transform of a Matrix](https://leetcode.com/problems/rank-transform-of-a-matrix/) | Hard | 6+ months | 31.0 | Todo |  |  |  | [notes](01.%20Union-Find%20%28Disjoint%20Set%29/1632.%20Rank%20Transform%20of%20a%20Matrix/1632.%20Rank%20Transform%20of%20a%20Matrix.md) |
| 17 | [803. Bricks Falling When Hit](https://leetcode.com/problems/bricks-falling-when-hit/) | Hard | 6+ months | 30.7 | Todo |  |  |  | [notes](01.%20Union-Find%20%28Disjoint%20Set%29/0803.%20Bricks%20Falling%20When%20Hit/0803.%20Bricks%20Falling%20When%20Hit.md) |
| 18 | [737. Sentence Similarity II](https://leetcode.com/problems/sentence-similarity-ii/) 🔒 | Medium | 6+ months | 30.6 | Todo |  |  |  | [notes](01.%20Union-Find%20%28Disjoint%20Set%29/0737.%20Sentence%20Similarity%20II/0737.%20Sentence%20Similarity%20II.md) |
| 19 | [685. Redundant Connection II](https://leetcode.com/problems/redundant-connection-ii/) | Hard | 6+ months | 28.8 | Todo |  |  |  | [notes](01.%20Union-Find%20%28Disjoint%20Set%29/0685.%20Redundant%20Connection%20II/0685.%20Redundant%20Connection%20II.md) |
| 20 | [1202. Smallest String With Swaps](https://leetcode.com/problems/smallest-string-with-swaps/) | Medium | 6+ months | 12.0 | Todo |  |  |  | [notes](01.%20Union-Find%20%28Disjoint%20Set%29/1202.%20Smallest%20String%20With%20Swaps/1202.%20Smallest%20String%20With%20Swaps.md) |
| 21 | [3108. Minimum Cost Walk in Weighted Graph](https://leetcode.com/problems/minimum-cost-walk-in-weighted-graph/) | Hard | 6+ months | 5.8 | Todo |  |  |  | [notes](01.%20Union-Find%20%28Disjoint%20Set%29/3108.%20Minimum%20Cost%20Walk%20in%20Weighted%20Graph/3108.%20Minimum%20Cost%20Walk%20in%20Weighted%20Graph.md) |
| 22 | [924. Minimize Malware Spread](https://leetcode.com/problems/minimize-malware-spread/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Union-Find%20%28Disjoint%20Set%29/0924.%20Minimize%20Malware%20Spread/0924.%20Minimize%20Malware%20Spread.md) |
| 23 | [959. Regions Cut By Slashes](https://leetcode.com/problems/regions-cut-by-slashes/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Union-Find%20%28Disjoint%20Set%29/0959.%20Regions%20Cut%20By%20Slashes/0959.%20Regions%20Cut%20By%20Slashes.md) |
| 24 | [1061. Lexicographically Smallest Equivalent String](https://leetcode.com/problems/lexicographically-smallest-equivalent-string/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Union-Find%20%28Disjoint%20Set%29/1061.%20Lexicographically%20Smallest%20Equivalent%20String/1061.%20Lexicographically%20Smallest%20Equivalent%20String.md) |
| 25 | [1319. Number of Operations to Make Network Connected](https://leetcode.com/problems/number-of-operations-to-make-network-connected/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](01.%20Union-Find%20%28Disjoint%20Set%29/1319.%20Number%20of%20Operations%20to%20Make%20Network%20Connected/1319.%20Number%20of%20Operations%20to%20Make%20Network%20Connected.md) |
| 26 | [1579. Remove Max Number of Edges to Keep Graph Fully Traversable](https://leetcode.com/problems/remove-max-number-of-edges-to-keep-graph-fully-traversable/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Union-Find%20%28Disjoint%20Set%29/1579.%20Remove%20Max%20Number%20of%20Edges%20to%20Keep%20Graph%20Fully%20Traversable/1579.%20Remove%20Max%20Number%20of%20Edges%20to%20Keep%20Graph%20Fully%20Traversable.md) |
| 27 | [3607. Power Grid Maintenance](https://leetcode.com/problems/power-grid-maintenance/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Union-Find%20%28Disjoint%20Set%29/3607.%20Power%20Grid%20Maintenance/3607.%20Power%20Grid%20Maintenance.md) |
| 28 | [952. Largest Component Size by Common Factor](https://leetcode.com/problems/largest-component-size-by-common-factor/) | Hard | 6+ months | 31.0 | Todo |  |  |  | [notes](01.%20Union-Find%20%28Disjoint%20Set%29/0952.%20Largest%20Component%20Size%20by%20Common%20Factor/0952.%20Largest%20Component%20Size%20by%20Common%20Factor.md) |
| 29 | [1697. Checking Existence of Edge Length Limited Paths](https://leetcode.com/problems/checking-existence-of-edge-length-limited-paths/) | Hard | 6+ months | 30.8 | Todo |  |  |  | [notes](01.%20Union-Find%20%28Disjoint%20Set%29/1697.%20Checking%20Existence%20of%20Edge%20Length%20Limited%20Paths/1697.%20Checking%20Existence%20of%20Edge%20Length%20Limited%20Paths.md) |
| 30 | [3695. Maximize Alternating Sum Using Swaps](https://leetcode.com/problems/maximize-alternating-sum-using-swaps/) | Hard | 6+ months | 29.6 | Todo |  |  |  | [notes](01.%20Union-Find%20%28Disjoint%20Set%29/3695.%20Maximize%20Alternating%20Sum%20Using%20Swaps/3695.%20Maximize%20Alternating%20Sum%20Using%20Swaps.md) |
| 31 | [1562. Find Latest Group of Size M](https://leetcode.com/problems/find-latest-group-of-size-m/) | Medium | 6+ months | 28.8 | Todo |  |  |  | [notes](01.%20Union-Find%20%28Disjoint%20Set%29/1562.%20Find%20Latest%20Group%20of%20Size%20M/1562.%20Find%20Latest%20Group%20of%20Size%20M.md) |
| 32 | [1724. Checking Existence of Edge Length Limited Paths II](https://leetcode.com/problems/checking-existence-of-edge-length-limited-paths-ii/) 🔒 | Hard | 6+ months | 28.8 | Todo |  |  |  | [notes](01.%20Union-Find%20%28Disjoint%20Set%29/1724.%20Checking%20Existence%20of%20Edge%20Length%20Limited%20Paths%20II/1724.%20Checking%20Existence%20of%20Edge%20Length%20Limited%20Paths%20II.md) |
| 33 | [2076. Process Restricted Friend Requests](https://leetcode.com/problems/process-restricted-friend-requests/) | Hard | 6+ months | 28.8 | Todo |  |  |  | [notes](01.%20Union-Find%20%28Disjoint%20Set%29/2076.%20Process%20Restricted%20Friend%20Requests/2076.%20Process%20Restricted%20Friend%20Requests.md) |
| 34 | [2316. Count Unreachable Pairs of Nodes in an Undirected Graph](https://leetcode.com/problems/count-unreachable-pairs-of-nodes-in-an-undirected-graph/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Union-Find%20%28Disjoint%20Set%29/2316.%20Count%20Unreachable%20Pairs%20of%20Nodes%20in%20an%20Undirected%20Graph/2316.%20Count%20Unreachable%20Pairs%20of%20Nodes%20in%20an%20Undirected%20Graph.md) |

## 02. Dijkstra's Algorithm

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [1514. Path with Maximum Probability](https://leetcode.com/problems/path-with-maximum-probability/) | Medium | 30 days | 37.0 | ✅ Solved |  |  |  | [notes](02.%20Dijkstra%27s%20Algorithm/1514.%20Path%20with%20Maximum%20Probability/1514.%20Path%20with%20Maximum%20Probability.md) |
| 2 | [3970. Shortest Path With At Most K Consecutive Identical Characters](https://leetcode.com/problems/shortest-path-with-at-most-k-consecutive-identical-characters/) | Medium | 30 days | 7.0 | Todo |  |  |  | [notes](02.%20Dijkstra%27s%20Algorithm/3970.%20Shortest%20Path%20With%20At%20Most%20K%20Consecutive%20Identical%20Characters/3970.%20Shortest%20Path%20With%20At%20Most%20K%20Consecutive%20Identical%20Characters.md) |
| 3 | [778. Swim in Rising Water](https://leetcode.com/problems/swim-in-rising-water/) | Hard | 3 months | 48.6 | ✅ Solved |  |  |  | [notes](02.%20Dijkstra%27s%20Algorithm/0778.%20Swim%20in%20Rising%20Water/0778.%20Swim%20in%20Rising%20Water.md) |
| 4 | [1631. Path With Minimum Effort](https://leetcode.com/problems/path-with-minimum-effort/) | Medium | 3 months | 45.1 | ✅ Solved |  |  |  | [notes](02.%20Dijkstra%27s%20Algorithm/1631.%20Path%20With%20Minimum%20Effort/1631.%20Path%20With%20Minimum%20Effort.md) |
| 5 | [743. Network Delay Time](https://leetcode.com/problems/network-delay-time/) | Medium | 3 months | 39.8 | ✅ Solved |  |  |  | [notes](02.%20Dijkstra%27s%20Algorithm/0743.%20Network%20Delay%20Time/0743.%20Network%20Delay%20Time.md) |
| 6 | [1976. Number of Ways to Arrive at Destination](https://leetcode.com/problems/number-of-ways-to-arrive-at-destination/) | Medium | 6 months | 22.1 | ✅ Solved |  |  |  | [notes](02.%20Dijkstra%27s%20Algorithm/1976.%20Number%20of%20Ways%20to%20Arrive%20at%20Destination/1976.%20Number%20of%20Ways%20to%20Arrive%20at%20Destination.md) |
| 7 | [2203. Minimum Weighted Subgraph With the Required Paths](https://leetcode.com/problems/minimum-weighted-subgraph-with-the-required-paths/) | Hard | 6+ months | 36.1 | Todo |  |  |  | [notes](02.%20Dijkstra%27s%20Algorithm/2203.%20Minimum%20Weighted%20Subgraph%20With%20the%20Required%20Paths/2203.%20Minimum%20Weighted%20Subgraph%20With%20the%20Required%20Paths.md) |
| 8 | [3650. Minimum Cost Path with Edge Reversals](https://leetcode.com/problems/minimum-cost-path-with-edge-reversals/) | Medium | 6+ months | 31.7 | Todo |  |  |  | [notes](02.%20Dijkstra%27s%20Algorithm/3650.%20Minimum%20Cost%20Path%20with%20Edge%20Reversals/3650.%20Minimum%20Cost%20Path%20with%20Edge%20Reversals.md) |
| 9 | [1786. Number of Restricted Paths From First to Last Node](https://leetcode.com/problems/number-of-restricted-paths-from-first-to-last-node/) | Medium | 6+ months | 29.6 | Todo |  |  |  | [notes](02.%20Dijkstra%27s%20Algorithm/1786.%20Number%20of%20Restricted%20Paths%20From%20First%20to%20Last%20Node/1786.%20Number%20of%20Restricted%20Paths%20From%20First%20to%20Last%20Node.md) |
| 10 | [1102. Path With Maximum Minimum Value](https://leetcode.com/problems/path-with-maximum-minimum-value/) 🔒 | Medium | 6+ months | 22.1 | Todo |  |  |  | [notes](02.%20Dijkstra%27s%20Algorithm/1102.%20Path%20With%20Maximum%20Minimum%20Value/1102.%20Path%20With%20Maximum%20Minimum%20Value.md) |
| 11 | [3651. Minimum Cost Path with Teleportations](https://leetcode.com/problems/minimum-cost-path-with-teleportations/) | Hard | 6+ months | 8.3 | Todo |  |  |  | [notes](02.%20Dijkstra%27s%20Algorithm/3651.%20Minimum%20Cost%20Path%20with%20Teleportations/3651.%20Minimum%20Cost%20Path%20with%20Teleportations.md) |
| 12 | [1928. Minimum Cost to Reach Destination in Time](https://leetcode.com/problems/minimum-cost-to-reach-destination-in-time/) | Hard | 6+ months | 7.6 | Todo |  |  |  | [notes](02.%20Dijkstra%27s%20Algorithm/1928.%20Minimum%20Cost%20to%20Reach%20Destination%20in%20Time/1928.%20Minimum%20Cost%20to%20Reach%20Destination%20in%20Time.md) |
| 13 | [2577. Minimum Time to Visit a Cell In a Grid](https://leetcode.com/problems/minimum-time-to-visit-a-cell-in-a-grid/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Dijkstra%27s%20Algorithm/2577.%20Minimum%20Time%20to%20Visit%20a%20Cell%20In%20a%20Grid/2577.%20Minimum%20Time%20to%20Visit%20a%20Cell%20In%20a%20Grid.md) |
| 14 | [3341. Find Minimum Time to Reach Last Room I](https://leetcode.com/problems/find-minimum-time-to-reach-last-room-i/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Dijkstra%27s%20Algorithm/3341.%20Find%20Minimum%20Time%20to%20Reach%20Last%20Room%20I/3341.%20Find%20Minimum%20Time%20to%20Reach%20Last%20Room%20I.md) |
| 15 | [3342. Find Minimum Time to Reach Last Room II](https://leetcode.com/problems/find-minimum-time-to-reach-last-room-ii/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Dijkstra%27s%20Algorithm/3342.%20Find%20Minimum%20Time%20to%20Reach%20Last%20Room%20II/3342.%20Find%20Minimum%20Time%20to%20Reach%20Last%20Room%20II.md) |
| 16 | [3377. Digit Operations to Make Two Integers Equal](https://leetcode.com/problems/digit-operations-to-make-two-integers-equal/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Dijkstra%27s%20Algorithm/3377.%20Digit%20Operations%20to%20Make%20Two%20Integers%20Equal/3377.%20Digit%20Operations%20to%20Make%20Two%20Integers%20Equal.md) |
| 17 | [505. The Maze II](https://leetcode.com/problems/the-maze-ii/) 🔒 | Medium | 6+ months | 30.5 | Todo |  |  |  | [notes](02.%20Dijkstra%27s%20Algorithm/0505.%20The%20Maze%20II/0505.%20The%20Maze%20II.md) |
| 18 | [1810. Minimum Path Cost in a Hidden Grid](https://leetcode.com/problems/minimum-path-cost-in-a-hidden-grid/) 🔒 | Medium | 6+ months | 29.5 | Todo |  |  |  | [notes](02.%20Dijkstra%27s%20Algorithm/1810.%20Minimum%20Path%20Cost%20in%20a%20Hidden%20Grid/1810.%20Minimum%20Path%20Cost%20in%20a%20Hidden%20Grid.md) |
| 19 | [882. Reachable Nodes In Subdivided Graph](https://leetcode.com/problems/reachable-nodes-in-subdivided-graph/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Dijkstra%27s%20Algorithm/0882.%20Reachable%20Nodes%20In%20Subdivided%20Graph/0882.%20Reachable%20Nodes%20In%20Subdivided%20Graph.md) |

## 03. Bellman-Ford & Floyd-Warshall

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [787. Cheapest Flights Within K Stops](https://leetcode.com/problems/cheapest-flights-within-k-stops/) | Medium | 3 months | 36.6 | ✅ Solved |  |  |  | [notes](03.%20Bellman-Ford%20%26%20Floyd-Warshall/0787.%20Cheapest%20Flights%20Within%20K%20Stops/0787.%20Cheapest%20Flights%20Within%20K%20Stops.md) |
| 2 | [1334. Find the City With the Smallest Number of Neighbors at a Threshold Distance](https://leetcode.com/problems/find-the-city-with-the-smallest-number-of-neighbors-at-a-threshold-distance/) | Medium | 6+ months | 7.9 | Todo |  |  |  | [notes](03.%20Bellman-Ford%20%26%20Floyd-Warshall/1334.%20Find%20the%20City%20With%20the%20Smallest%20Number%20of%20Neighbors%20at%20a%20Threshold%20Distance/1334.%20Find%20the%20City%20With%20the%20Smallest%20Number%20of%20Neighbors%20at%20a%20Threshold%20Distance.md) |
| 3 | [2976. Minimum Cost to Convert String I](https://leetcode.com/problems/minimum-cost-to-convert-string-i/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](03.%20Bellman-Ford%20%26%20Floyd-Warshall/2976.%20Minimum%20Cost%20to%20Convert%20String%20I/2976.%20Minimum%20Cost%20to%20Convert%20String%20I.md) |

## 04. 0-1 BFS

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [3286. Find a Safe Walk Through a Grid](https://leetcode.com/problems/find-a-safe-walk-through-a-grid/) | Medium | 6 months | 12.8 | ✅ Solved |  |  |  | [notes](04.%200-1%20BFS/3286.%20Find%20a%20Safe%20Walk%20Through%20a%20Grid/3286.%20Find%20a%20Safe%20Walk%20Through%20a%20Grid.md) |
| 2 | [1368. Minimum Cost to Make at Least One Valid Path in a Grid](https://leetcode.com/problems/minimum-cost-to-make-at-least-one-valid-path-in-a-grid/) | Hard | 6+ months | 36.5 | Todo |  |  |  | [notes](04.%200-1%20BFS/1368.%20Minimum%20Cost%20to%20Make%20at%20Least%20One%20Valid%20Path%20in%20a%20Grid/1368.%20Minimum%20Cost%20to%20Make%20at%20Least%20One%20Valid%20Path%20in%20a%20Grid.md) |
| 3 | [2290. Minimum Obstacle Removal to Reach Corner](https://leetcode.com/problems/minimum-obstacle-removal-to-reach-corner/) | Hard | 6+ months | 30.7 | Todo |  |  |  | [notes](04.%200-1%20BFS/2290.%20Minimum%20Obstacle%20Removal%20to%20Reach%20Corner/2290.%20Minimum%20Obstacle%20Removal%20to%20Reach%20Corner.md) |

## 05. Minimum Spanning Tree

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [1584. Min Cost to Connect All Points](https://leetcode.com/problems/min-cost-to-connect-all-points/) | Medium | 6 months | 24.7 | Todo |  |  |  | [notes](05.%20Minimum%20Spanning%20Tree/1584.%20Min%20Cost%20to%20Connect%20All%20Points/1584.%20Min%20Cost%20to%20Connect%20All%20Points.md) |
| 2 | [1489. Find Critical and Pseudo-Critical Edges in Minimum Spanning Tree](https://leetcode.com/problems/find-critical-and-pseudo-critical-edges-in-minimum-spanning-tree/) | Hard | 6+ months | 7.0 | Todo |  |  |  | [notes](05.%20Minimum%20Spanning%20Tree/1489.%20Find%20Critical%20and%20Pseudo-Critical%20Edges%20in%20Minimum%20Spanning%20Tree/1489.%20Find%20Critical%20and%20Pseudo-Critical%20Edges%20in%20Minimum%20Spanning%20Tree.md) |
| 3 | [3600. Maximize Spanning Tree Stability with Upgrades](https://leetcode.com/problems/maximize-spanning-tree-stability-with-upgrades/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Minimum%20Spanning%20Tree/3600.%20Maximize%20Spanning%20Tree%20Stability%20with%20Upgrades/3600.%20Maximize%20Spanning%20Tree%20Stability%20with%20Upgrades.md) |
| 4 | [3613. Minimize Maximum Component Cost](https://leetcode.com/problems/minimize-maximum-component-cost/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Minimum%20Spanning%20Tree/3613.%20Minimize%20Maximum%20Component%20Cost/3613.%20Minimize%20Maximum%20Component%20Cost.md) |
| 5 | [1168. Optimize Water Distribution in a Village](https://leetcode.com/problems/optimize-water-distribution-in-a-village/) 🔒 | Hard | 6+ months | 30.1 | Todo |  |  |  | [notes](05.%20Minimum%20Spanning%20Tree/1168.%20Optimize%20Water%20Distribution%20in%20a%20Village/1168.%20Optimize%20Water%20Distribution%20in%20a%20Village.md) |

## 06. Strongly Connected Components & Bridges

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [1192. Critical Connections in a Network](https://leetcode.com/problems/critical-connections-in-a-network/) | Hard | 30 days | 16.3 | Todo |  |  |  | [notes](06.%20Strongly%20Connected%20Components%20%26%20Bridges/1192.%20Critical%20Connections%20in%20a%20Network/1192.%20Critical%20Connections%20in%20a%20Network.md) |

## 07. Eulerian Path

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea&ensp;&#8203; | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [332. Reconstruct Itinerary](https://leetcode.com/problems/reconstruct-itinerary/) | Hard | 3 months | 40.0 | Todo |  |  |  | [notes](07.%20Eulerian%20Path/0332.%20Reconstruct%20Itinerary/0332.%20Reconstruct%20Itinerary.md) |
| 2 | [753. Cracking the Safe](https://leetcode.com/problems/cracking-the-safe/) | Hard | 6+ months | 32.4 | Todo |  |  |  | [notes](07.%20Eulerian%20Path/0753.%20Cracking%20the%20Safe/0753.%20Cracking%20the%20Safe.md) |

## 08. Network Flow & Matching

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [1820. Maximum Number of Accepted Invitations](https://leetcode.com/problems/maximum-number-of-accepted-invitations/) 🔒 | Medium | 6+ months | 8.2 | Todo |  |  |  | [notes](08.%20Network%20Flow%20%26%20Matching/1820.%20Maximum%20Number%20of%20Accepted%20Invitations/1820.%20Maximum%20Number%20of%20Accepted%20Invitations.md) |
