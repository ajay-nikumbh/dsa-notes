# 07. Matrix & Simulation

[Back to Facebook](../README.md) · [Back to DSA Notes](../../../README.md)

42 Meta (Facebook) problems: 22 Easy, 19 Medium, 1 Hard, in 5 sub-patterns.

## Sub-patterns

| # | Sub-pattern | Questions | Easy | Medium | Hard | Last 3 Months | Solved | Most Asked |
|:---:|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---|
| 01 | [Matrix Traversal (Spiral, Diagonal)](#01-matrix-traversal-spiral-diagonal) | 17 | 7 | 10 | 0 | 1 | 3 | 498. Diagonal Traverse, 54. Spiral Matrix, 311. Sparse Matrix Multiplication |
| 02 | [Matrix Rotation & Transformation](#02-matrix-rotation--transformation) | 9 | 6 | 3 | 0 | 1 | 2 | 48. Rotate Image, 867. Transpose Matrix, 1914. Cyclically Rotating a Grid |
| 03 | [In-Place Matrix Marking](#03-in-place-matrix-marking) | 2 | 0 | 2 | 0 | 0 | 1 | 73. Set Matrix Zeroes, 289. Game of Life |
| 04 | [Grid Simulation](#04-grid-simulation) | 7 | 3 | 4 | 0 | 0 | 1 | 419. Battleships in a Board, 2596. Check Knight Tour Configuration, 1275. Find Winner on a Tic Tac Toe Game |
| 05 | [Process Simulation](#05-process-simulation) | 7 | 6 | 0 | 1 | 0 | 1 | 2303. Calculate Amount Paid in Taxes, 157. Read N Characters Given Read4, 158. Read N Characters Given read4 II - Call Multiple Times |

**Columns**

- **Last Asked**: most recent LeetCode window that lists the problem for Meta (30 days, 3 months, 6 months or 6+ months).
- **Frequency**: LeetCode frequency score (0-100) in the Meta "All" list.
- **Status**: your LeetCode status on the day this file was generated. 🔒 after a title means LeetCode Premium.
- **Logic / Key Idea, Time, Space**: fill these in as you solve. A rebuild keeps what you typed.
- **Notes**: link to the problem's notes file.

Inside each sub-pattern, rows are sorted by most recent window, then by frequency (highest first).

## 01. Matrix Traversal (Spiral, Diagonal)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [54. Spiral Matrix](https://leetcode.com/problems/spiral-matrix/) | Medium | 3 months | 48.3 | Todo |  |  |  | [notes](01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/0054.%20Spiral%20Matrix/0054.%20Spiral%20Matrix.md) |
| 2 | [835. Image Overlap](https://leetcode.com/problems/image-overlap/) | Medium | 6 months | 5.0 | Todo |  |  |  | [notes](01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/0835.%20Image%20Overlap/0835.%20Image%20Overlap.md) |
| 3 | [498. Diagonal Traverse](https://leetcode.com/problems/diagonal-traverse/) | Medium | 6+ months | 63.4 | Todo |  |  |  | [notes](01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/0498.%20Diagonal%20Traverse/0498.%20Diagonal%20Traverse.md) |
| 4 | [311. Sparse Matrix Multiplication](https://leetcode.com/problems/sparse-matrix-multiplication/) 🔒 | Medium | 6+ months | 47.1 | Todo |  |  |  | [notes](01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/0311.%20Sparse%20Matrix%20Multiplication/0311.%20Sparse%20Matrix%20Multiplication.md) |
| 5 | [766. Toeplitz Matrix](https://leetcode.com/problems/toeplitz-matrix/) | Easy | 6+ months | 41.8 | Todo |  |  |  | [notes](01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/0766.%20Toeplitz%20Matrix/0766.%20Toeplitz%20Matrix.md) |
| 6 | [1424. Diagonal Traverse II](https://leetcode.com/problems/diagonal-traverse-ii/) | Medium | 6+ months | 38.7 | Todo |  |  |  | [notes](01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/1424.%20Diagonal%20Traverse%20II/1424.%20Diagonal%20Traverse%20II.md) |
| 7 | [59. Spiral Matrix II](https://leetcode.com/problems/spiral-matrix-ii/) | Medium | 6+ months | 13.4 | Todo |  |  |  | [notes](01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/0059.%20Spiral%20Matrix%20II/0059.%20Spiral%20Matrix%20II.md) |
| 8 | [1672. Richest Customer Wealth](https://leetcode.com/problems/richest-customer-wealth/) | Easy | 6+ months | 8.5 | ✅ Solved |  |  |  | [notes](01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/1672.%20Richest%20Customer%20Wealth/1672.%20Richest%20Customer%20Wealth.md) |
| 9 | [1572. Matrix Diagonal Sum](https://leetcode.com/problems/matrix-diagonal-sum/) | Easy | 6+ months | 5.3 | ✅ Solved |  |  |  | [notes](01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/1572.%20Matrix%20Diagonal%20Sum/1572.%20Matrix%20Diagonal%20Sum.md) |
| 10 | [661. Image Smoother](https://leetcode.com/problems/image-smoother/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/0661.%20Image%20Smoother/0661.%20Image%20Smoother.md) |
| 11 | [885. Spiral Matrix III](https://leetcode.com/problems/spiral-matrix-iii/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/0885.%20Spiral%20Matrix%20III/0885.%20Spiral%20Matrix%20III.md) |
| 12 | [2326. Spiral Matrix IV](https://leetcode.com/problems/spiral-matrix-iv/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/2326.%20Spiral%20Matrix%20IV/2326.%20Spiral%20Matrix%20IV.md) |
| 13 | [2373. Largest Local Values in a Matrix](https://leetcode.com/problems/largest-local-values-in-a-matrix/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/2373.%20Largest%20Local%20Values%20in%20a%20Matrix/2373.%20Largest%20Local%20Values%20in%20a%20Matrix.md) |
| 14 | [3417. Zigzag Grid Traversal With Skip](https://leetcode.com/problems/zigzag-grid-traversal-with-skip/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/3417.%20Zigzag%20Grid%20Traversal%20With%20Skip/3417.%20Zigzag%20Grid%20Traversal%20With%20Skip.md) |
| 15 | [3446. Sort Matrix by Diagonals](https://leetcode.com/problems/sort-matrix-by-diagonals/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/3446.%20Sort%20Matrix%20by%20Diagonals/3446.%20Sort%20Matrix%20by%20Diagonals.md) |
| 16 | [3898. Find the Degree of Each Vertex](https://leetcode.com/problems/find-the-degree-of-each-vertex/) | Easy | 6+ months | 6.2 | Todo |  |  |  | [notes](01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/3898.%20Find%20the%20Degree%20of%20Each%20Vertex/3898.%20Find%20the%20Degree%20of%20Each%20Vertex.md) |
| 17 | [807. Max Increase to Keep City Skyline](https://leetcode.com/problems/max-increase-to-keep-city-skyline/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/0807.%20Max%20Increase%20to%20Keep%20City%20Skyline/0807.%20Max%20Increase%20to%20Keep%20City%20Skyline.md) |

## 02. Matrix Rotation & Transformation

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [48. Rotate Image](https://leetcode.com/problems/rotate-image/) | Medium | 3 months | 44.5 | ✅ Solved |  |  |  | [notes](02.%20Matrix%20Rotation%20%26%20Transformation/0048.%20Rotate%20Image/0048.%20Rotate%20Image.md) |
| 2 | [867. Transpose Matrix](https://leetcode.com/problems/transpose-matrix/) | Easy | 6+ months | 10.7 | Todo |  |  |  | [notes](02.%20Matrix%20Rotation%20%26%20Transformation/0867.%20Transpose%20Matrix/0867.%20Transpose%20Matrix.md) |
| 3 | [1914. Cyclically Rotating a Grid](https://leetcode.com/problems/cyclically-rotating-a-grid/) | Medium | 6+ months | 10.1 | Todo |  |  |  | [notes](02.%20Matrix%20Rotation%20%26%20Transformation/1914.%20Cyclically%20Rotating%20a%20Grid/1914.%20Cyclically%20Rotating%20a%20Grid.md) |
| 4 | [1861. Rotating the Box](https://leetcode.com/problems/rotating-the-box/) | Medium | 6+ months | 9.3 | Todo |  |  |  | [notes](02.%20Matrix%20Rotation%20%26%20Transformation/1861.%20Rotating%20the%20Box/1861.%20Rotating%20the%20Box.md) |
| 5 | [566. Reshape the Matrix](https://leetcode.com/problems/reshape-the-matrix/) | Easy | 6+ months | 6.5 | Todo |  |  |  | [notes](02.%20Matrix%20Rotation%20%26%20Transformation/0566.%20Reshape%20the%20Matrix/0566.%20Reshape%20the%20Matrix.md) |
| 6 | [832. Flipping an Image](https://leetcode.com/problems/flipping-an-image/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](02.%20Matrix%20Rotation%20%26%20Transformation/0832.%20Flipping%20an%20Image/0832.%20Flipping%20an%20Image.md) |
| 7 | [1886. Determine Whether Matrix Can Be Obtained By Rotation](https://leetcode.com/problems/determine-whether-matrix-can-be-obtained-by-rotation/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Matrix%20Rotation%20%26%20Transformation/1886.%20Determine%20Whether%20Matrix%20Can%20Be%20Obtained%20By%20Rotation/1886.%20Determine%20Whether%20Matrix%20Can%20Be%20Obtained%20By%20Rotation.md) |
| 8 | [2946. Matrix Similarity After Cyclic Shifts](https://leetcode.com/problems/matrix-similarity-after-cyclic-shifts/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Matrix%20Rotation%20%26%20Transformation/2946.%20Matrix%20Similarity%20After%20Cyclic%20Shifts/2946.%20Matrix%20Similarity%20After%20Cyclic%20Shifts.md) |
| 9 | [3643. Flip Square Submatrix Vertically](https://leetcode.com/problems/flip-square-submatrix-vertically/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Matrix%20Rotation%20%26%20Transformation/3643.%20Flip%20Square%20Submatrix%20Vertically/3643.%20Flip%20Square%20Submatrix%20Vertically.md) |

## 03. In-Place Matrix Marking

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea&ensp;&#8203;&ensp;&#8203;&ensp;&#8203; | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [73. Set Matrix Zeroes](https://leetcode.com/problems/set-matrix-zeroes/) | Medium | 6 months | 54.8 | ✅ Solved |  |  |  | [notes](03.%20In-Place%20Matrix%20Marking/0073.%20Set%20Matrix%20Zeroes/0073.%20Set%20Matrix%20Zeroes.md) |
| 2 | [289. Game of Life](https://leetcode.com/problems/game-of-life/) | Medium | 6+ months | 11.2 | Todo |  |  |  | [notes](03.%20In-Place%20Matrix%20Marking/0289.%20Game%20of%20Life/0289.%20Game%20of%20Life.md) |

## 04. Grid Simulation

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [419. Battleships in a Board](https://leetcode.com/problems/battleships-in-a-board/) | Medium | 6+ months | 40.4 | Todo |  |  |  | [notes](04.%20Grid%20Simulation/0419.%20Battleships%20in%20a%20Board/0419.%20Battleships%20in%20a%20Board.md) |
| 2 | [1275. Find Winner on a Tic Tac Toe Game](https://leetcode.com/problems/find-winner-on-a-tic-tac-toe-game/) | Easy | 6+ months | 12.3 | Todo |  |  |  | [notes](04.%20Grid%20Simulation/1275.%20Find%20Winner%20on%20a%20Tic%20Tac%20Toe%20Game/1275.%20Find%20Winner%20on%20a%20Tic%20Tac%20Toe%20Game.md) |
| 3 | [2257. Count Unguarded Cells in the Grid](https://leetcode.com/problems/count-unguarded-cells-in-the-grid/) | Medium | 6+ months | 10.4 | Todo |  |  |  | [notes](04.%20Grid%20Simulation/2257.%20Count%20Unguarded%20Cells%20in%20the%20Grid/2257.%20Count%20Unguarded%20Cells%20in%20the%20Grid.md) |
| 4 | [723. Candy Crush](https://leetcode.com/problems/candy-crush/) 🔒 | Medium | 6+ months | 10.0 | Todo |  |  |  | [notes](04.%20Grid%20Simulation/0723.%20Candy%20Crush/0723.%20Candy%20Crush.md) |
| 5 | [463. Island Perimeter](https://leetcode.com/problems/island-perimeter/) | Easy | 6+ months | 5.8 | ✅ Solved |  |  |  | [notes](04.%20Grid%20Simulation/0463.%20Island%20Perimeter/0463.%20Island%20Perimeter.md) |
| 6 | [2596. Check Knight Tour Configuration](https://leetcode.com/problems/check-knight-tour-configuration/) | Medium | 6+ months | 36.1 | Todo |  |  |  | [notes](04.%20Grid%20Simulation/2596.%20Check%20Knight%20Tour%20Configuration/2596.%20Check%20Knight%20Tour%20Configuration.md) |
| 7 | [999. Available Captures for Rook](https://leetcode.com/problems/available-captures-for-rook/) | Easy | 6+ months | 5.5 | Todo |  |  |  | [notes](04.%20Grid%20Simulation/0999.%20Available%20Captures%20for%20Rook/0999.%20Available%20Captures%20for%20Rook.md) |

## 05. Process Simulation

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [3507. Minimum Pair Removal to Sort Array I](https://leetcode.com/problems/minimum-pair-removal-to-sort-array-i/) | Easy | 6+ months | 14.3 | Todo |  |  |  | [notes](05.%20Process%20Simulation/3507.%20Minimum%20Pair%20Removal%20to%20Sort%20Array%20I/3507.%20Minimum%20Pair%20Removal%20to%20Sort%20Array%20I.md) |
| 2 | [3477. Fruits Into Baskets II](https://leetcode.com/problems/fruits-into-baskets-ii/) | Easy | 6+ months | 14.0 | 🟡 Attempted |  |  |  | [notes](05.%20Process%20Simulation/3477.%20Fruits%20Into%20Baskets%20II/3477.%20Fruits%20Into%20Baskets%20II.md) |
| 3 | [1389. Create Target Array in the Given Order](https://leetcode.com/problems/create-target-array-in-the-given-order/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](05.%20Process%20Simulation/1389.%20Create%20Target%20Array%20in%20the%20Given%20Order/1389.%20Create%20Target%20Array%20in%20the%20Given%20Order.md) |
| 4 | [3069. Distribute Elements Into Two Arrays I](https://leetcode.com/problems/distribute-elements-into-two-arrays-i/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Process%20Simulation/3069.%20Distribute%20Elements%20Into%20Two%20Arrays%20I/3069.%20Distribute%20Elements%20Into%20Two%20Arrays%20I.md) |
| 5 | [2303. Calculate Amount Paid in Taxes](https://leetcode.com/problems/calculate-amount-paid-in-taxes/) | Easy | 6+ months | 36.8 | Todo |  |  |  | [notes](05.%20Process%20Simulation/2303.%20Calculate%20Amount%20Paid%20in%20Taxes/2303.%20Calculate%20Amount%20Paid%20in%20Taxes.md) |
| 6 | [157. Read N Characters Given Read4](https://leetcode.com/problems/read-n-characters-given-read4/) 🔒 | Easy | 6+ months | 36.1 | Todo |  |  |  | [notes](05.%20Process%20Simulation/0157.%20Read%20N%20Characters%20Given%20Read4/0157.%20Read%20N%20Characters%20Given%20Read4.md) |
| 7 | [158. Read N Characters Given read4 II - Call Multiple Times](https://leetcode.com/problems/read-n-characters-given-read4-ii-call-multiple-times/) 🔒 | Hard | 6+ months | 36.1 | Todo |  |  |  | [notes](05.%20Process%20Simulation/0158.%20Read%20N%20Characters%20Given%20read4%20II%20-%20Call%20Multiple%20Times/0158.%20Read%20N%20Characters%20Given%20read4%20II%20-%20Call%20Multiple%20Times.md) |
