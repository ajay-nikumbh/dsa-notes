# 07. Matrix & Simulation

[Back to Google](../README.md) · [Back to DSA Notes](../../../README.md)

73 Google problems: 33 Easy, 37 Medium, 3 Hard, in 5 sub-patterns.

## Sub-patterns

| # | Sub-pattern | Questions | Easy | Medium | Hard | Last 3 Months | Solved | Most Asked |
|:---:|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---|
| 01 | [Matrix Traversal (Spiral, Diagonal)](#01-matrix-traversal-spiral-diagonal) | 34 | 13 | 20 | 1 | 5 | 4 | 54. Spiral Matrix, 498. Diagonal Traverse, 1672. Richest Customer Wealth |
| 02 | [Matrix Rotation & Transformation](#02-matrix-rotation--transformation) | 11 | 8 | 3 | 0 | 1 | 2 | 48. Rotate Image, 832. Flipping an Image, 2022. Convert 1D Array Into 2D Array |
| 03 | [In-Place Matrix Marking](#03-in-place-matrix-marking) | 3 | 0 | 2 | 1 | 1 | 1 | 73. Set Matrix Zeroes, 289. Game of Life, 782. Transform to Chessboard |
| 04 | [Grid Simulation](#04-grid-simulation) | 10 | 3 | 7 | 0 | 2 | 1 | 463. Island Perimeter, 1706. Where Will the Ball Fall, 419. Battleships in a Board |
| 05 | [Process Simulation](#05-process-simulation) | 15 | 9 | 5 | 1 | 0 | 2 | 657. Robot Return to Origin, 158. Read N Characters Given read4 II - Call Multiple Times, 1138. Alphabet Board Path |

**Columns**

- **Last Asked**: most recent LeetCode window that lists the problem for Google (30 days, 3 months, 6 months, 6+ months).
- **Frequency**: LeetCode frequency score (0-100) in the Google "All" list.
- **Status**: your LeetCode status on the day this file was generated. 🔒 after a title means LeetCode Premium.
- **Logic / Key Idea, Time, Space**: fill these in as you solve. A rebuild keeps what you typed.
- **Notes**: link to the problem's notes file.

Inside each sub-pattern, rows are sorted by most recent window, then by frequency (highest first).

## 01. Matrix Traversal (Spiral, Diagonal)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [54. Spiral Matrix](https://leetcode.com/problems/spiral-matrix/) | Medium | 3 months | 61.1 | Todo |  |  |  | [notes](01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/0054.%20Spiral%20Matrix/0054.%20Spiral%20Matrix.md) |
| 2 | [1672. Richest Customer Wealth](https://leetcode.com/problems/richest-customer-wealth/) | Easy | 3 months | 38.1 | ✅ Solved |  |  |  | [notes](01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/1672.%20Richest%20Customer%20Wealth/1672.%20Richest%20Customer%20Wealth.md) |
| 3 | [835. Image Overlap](https://leetcode.com/problems/image-overlap/) | Medium | 3 months | 36.0 | Todo |  |  |  | [notes](01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/0835.%20Image%20Overlap/0835.%20Image%20Overlap.md) |
| 4 | [1572. Matrix Diagonal Sum](https://leetcode.com/problems/matrix-diagonal-sum/) | Easy | 3 months | 9.9 | ✅ Solved |  |  |  | [notes](01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/1572.%20Matrix%20Diagonal%20Sum/1572.%20Matrix%20Diagonal%20Sum.md) |
| 5 | [1380. Lucky Numbers in a Matrix](https://leetcode.com/problems/lucky-numbers-in-a-matrix/) | Easy | 3 months | 5.0 | Todo |  |  |  | [notes](01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/1380.%20Lucky%20Numbers%20in%20a%20Matrix/1380.%20Lucky%20Numbers%20in%20a%20Matrix.md) |
| 6 | [2643. Row With Maximum Ones](https://leetcode.com/problems/row-with-maximum-ones/) | Easy | 6 months | 10.1 | Todo |  |  |  | [notes](01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/2643.%20Row%20With%20Maximum%20Ones/2643.%20Row%20With%20Maximum%20Ones.md) |
| 7 | [498. Diagonal Traverse](https://leetcode.com/problems/diagonal-traverse/) | Medium | 6+ months | 38.4 | Todo |  |  |  | [notes](01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/0498.%20Diagonal%20Traverse/0498.%20Diagonal%20Traverse.md) |
| 8 | [1267. Count Servers that Communicate](https://leetcode.com/problems/count-servers-that-communicate/) | Medium | 6+ months | 35.7 | ✅ Solved |  |  |  | [notes](01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/1267.%20Count%20Servers%20that%20Communicate/1267.%20Count%20Servers%20that%20Communicate.md) |
| 9 | [1582. Special Positions in a Binary Matrix](https://leetcode.com/problems/special-positions-in-a-binary-matrix/) | Easy | 6+ months | 33.8 | Todo |  |  |  | [notes](01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/1582.%20Special%20Positions%20in%20a%20Binary%20Matrix/1582.%20Special%20Positions%20in%20a%20Binary%20Matrix.md) |
| 10 | [766. Toeplitz Matrix](https://leetcode.com/problems/toeplitz-matrix/) | Easy | 6+ months | 33.1 | Todo |  |  |  | [notes](01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/0766.%20Toeplitz%20Matrix/0766.%20Toeplitz%20Matrix.md) |
| 11 | [2018. Check if Word Can Be Placed In Crossword](https://leetcode.com/problems/check-if-word-can-be-placed-in-crossword/) | Medium | 6+ months | 31.9 | Todo |  |  |  | [notes](01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/2018.%20Check%20if%20Word%20Can%20Be%20Placed%20In%20Crossword/2018.%20Check%20if%20Word%20Can%20Be%20Placed%20In%20Crossword.md) |
| 12 | [840. Magic Squares In Grid](https://leetcode.com/problems/magic-squares-in-grid/) | Medium | 6+ months | 31.4 | Todo |  |  |  | [notes](01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/0840.%20Magic%20Squares%20In%20Grid/0840.%20Magic%20Squares%20In%20Grid.md) |
| 13 | [2373. Largest Local Values in a Matrix](https://leetcode.com/problems/largest-local-values-in-a-matrix/) | Easy | 6+ months | 30.2 | ✅ Solved |  |  |  | [notes](01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/2373.%20Largest%20Local%20Values%20in%20a%20Matrix/2373.%20Largest%20Local%20Values%20in%20a%20Matrix.md) |
| 14 | [59. Spiral Matrix II](https://leetcode.com/problems/spiral-matrix-ii/) | Medium | 6+ months | 18.7 | Todo |  |  |  | [notes](01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/0059.%20Spiral%20Matrix%20II/0059.%20Spiral%20Matrix%20II.md) |
| 15 | [3240. Minimum Number of Flips to Make Binary Grid Palindromic II](https://leetcode.com/problems/minimum-number-of-flips-to-make-binary-grid-palindromic-ii/) | Medium | 6+ months | 8.2 | Todo |  |  |  | [notes](01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/3240.%20Minimum%20Number%20of%20Flips%20to%20Make%20Binary%20Grid%20Palindromic%20II/3240.%20Minimum%20Number%20of%20Flips%20to%20Make%20Binary%20Grid%20Palindromic%20II.md) |
| 16 | [885. Spiral Matrix III](https://leetcode.com/problems/spiral-matrix-iii/) | Medium | 6+ months | 8.1 | Todo |  |  |  | [notes](01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/0885.%20Spiral%20Matrix%20III/0885.%20Spiral%20Matrix%20III.md) |
| 17 | [3446. Sort Matrix by Diagonals](https://leetcode.com/problems/sort-matrix-by-diagonals/) | Medium | 6+ months | 7.4 | Todo |  |  |  | [notes](01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/3446.%20Sort%20Matrix%20by%20Diagonals/3446.%20Sort%20Matrix%20by%20Diagonals.md) |
| 18 | [3567. Minimum Absolute Difference in Sliding Submatrix](https://leetcode.com/problems/minimum-absolute-difference-in-sliding-submatrix/) | Medium | 6+ months | 5.1 | Todo |  |  |  | [notes](01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/3567.%20Minimum%20Absolute%20Difference%20in%20Sliding%20Submatrix/3567.%20Minimum%20Absolute%20Difference%20in%20Sliding%20Submatrix.md) |
| 19 | [311. Sparse Matrix Multiplication](https://leetcode.com/problems/sparse-matrix-multiplication/) 🔒 | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/0311.%20Sparse%20Matrix%20Multiplication/0311.%20Sparse%20Matrix%20Multiplication.md) |
| 20 | [807. Max Increase to Keep City Skyline](https://leetcode.com/problems/max-increase-to-keep-city-skyline/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/0807.%20Max%20Increase%20to%20Keep%20City%20Skyline/0807.%20Max%20Increase%20to%20Keep%20City%20Skyline.md) |
| 21 | [1252. Cells with Odd Values in a Matrix](https://leetcode.com/problems/cells-with-odd-values-in-a-matrix/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/1252.%20Cells%20with%20Odd%20Values%20in%20a%20Matrix/1252.%20Cells%20with%20Odd%20Values%20in%20a%20Matrix.md) |
| 22 | [1329. Sort the Matrix Diagonally](https://leetcode.com/problems/sort-the-matrix-diagonally/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/1329.%20Sort%20the%20Matrix%20Diagonally/1329.%20Sort%20the%20Matrix%20Diagonally.md) |
| 23 | [2075. Decode the Slanted Ciphertext](https://leetcode.com/problems/decode-the-slanted-ciphertext/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/2075.%20Decode%20the%20Slanted%20Ciphertext/2075.%20Decode%20the%20Slanted%20Ciphertext.md) |
| 24 | [2319. Check if Matrix Is X-Matrix](https://leetcode.com/problems/check-if-matrix-is-x-matrix/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/2319.%20Check%20if%20Matrix%20Is%20X-Matrix/2319.%20Check%20if%20Matrix%20Is%20X-Matrix.md) |
| 25 | [3195. Find the Minimum Area to Cover All Ones I](https://leetcode.com/problems/find-the-minimum-area-to-cover-all-ones-i/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/3195.%20Find%20the%20Minimum%20Area%20to%20Cover%20All%20Ones%20I/3195.%20Find%20the%20Minimum%20Area%20to%20Cover%20All%20Ones%20I.md) |
| 26 | [3197. Find the Minimum Area to Cover All Ones II](https://leetcode.com/problems/find-the-minimum-area-to-cover-all-ones-ii/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/3197.%20Find%20the%20Minimum%20Area%20to%20Cover%20All%20Ones%20II/3197.%20Find%20the%20Minimum%20Area%20to%20Cover%20All%20Ones%20II.md) |
| 27 | [3417. Zigzag Grid Traversal With Skip](https://leetcode.com/problems/zigzag-grid-traversal-with-skip/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/3417.%20Zigzag%20Grid%20Traversal%20With%20Skip/3417.%20Zigzag%20Grid%20Traversal%20With%20Skip.md) |
| 28 | [422. Valid Word Square](https://leetcode.com/problems/valid-word-square/) 🔒 | Easy | 6+ months | 28.8 | Todo |  |  |  | [notes](01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/0422.%20Valid%20Word%20Square/0422.%20Valid%20Word%20Square.md) |
| 29 | [531. Lonely Pixel I](https://leetcode.com/problems/lonely-pixel-i/) 🔒 | Medium | 6+ months | 28.8 | Todo |  |  |  | [notes](01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/0531.%20Lonely%20Pixel%20I/0531.%20Lonely%20Pixel%20I.md) |
| 30 | [533. Lonely Pixel II](https://leetcode.com/problems/lonely-pixel-ii/) 🔒 | Medium | 6+ months | 28.8 | Todo |  |  |  | [notes](01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/0533.%20Lonely%20Pixel%20II/0533.%20Lonely%20Pixel%20II.md) |
| 31 | [1424. Diagonal Traverse II](https://leetcode.com/problems/diagonal-traverse-ii/) | Medium | 6+ months | 28.8 | Todo |  |  |  | [notes](01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/1424.%20Diagonal%20Traverse%20II/1424.%20Diagonal%20Traverse%20II.md) |
| 32 | [2128. Remove All Ones With Row and Column Flips](https://leetcode.com/problems/remove-all-ones-with-row-and-column-flips/) 🔒 | Medium | 6+ months | 28.8 | Todo |  |  |  | [notes](01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/2128.%20Remove%20All%20Ones%20With%20Row%20and%20Column%20Flips/2128.%20Remove%20All%20Ones%20With%20Row%20and%20Column%20Flips.md) |
| 33 | [2923. Find Champion I](https://leetcode.com/problems/find-champion-i/) | Easy | 6+ months | 28.8 | Todo |  |  |  | [notes](01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/2923.%20Find%20Champion%20I/2923.%20Find%20Champion%20I.md) |
| 34 | [883. Projection Area of 3D Shapes](https://leetcode.com/problems/projection-area-of-3d-shapes/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Matrix%20Traversal%20%28Spiral%2C%20Diagonal%29/0883.%20Projection%20Area%20of%203D%20Shapes/0883.%20Projection%20Area%20of%203D%20Shapes.md) |

## 02. Matrix Rotation & Transformation

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [48. Rotate Image](https://leetcode.com/problems/rotate-image/) | Medium | 3 months | 54.2 | ✅ Solved |  |  |  | [notes](02.%20Matrix%20Rotation%20%26%20Transformation/0048.%20Rotate%20Image/0048.%20Rotate%20Image.md) |
| 2 | [832. Flipping an Image](https://leetcode.com/problems/flipping-an-image/) | Easy | 6 months | 33.9 | ✅ Solved |  |  |  | [notes](02.%20Matrix%20Rotation%20%26%20Transformation/0832.%20Flipping%20an%20Image/0832.%20Flipping%20an%20Image.md) |
| 3 | [1260. Shift 2D Grid](https://leetcode.com/problems/shift-2d-grid/) | Easy | 6 months | 5.0 | Todo |  |  |  | [notes](02.%20Matrix%20Rotation%20%26%20Transformation/1260.%20Shift%202D%20Grid/1260.%20Shift%202D%20Grid.md) |
| 4 | [2022. Convert 1D Array Into 2D Array](https://leetcode.com/problems/convert-1d-array-into-2d-array/) | Easy | 6+ months | 31.2 | Todo |  |  |  | [notes](02.%20Matrix%20Rotation%20%26%20Transformation/2022.%20Convert%201D%20Array%20Into%202D%20Array/2022.%20Convert%201D%20Array%20Into%202D%20Array.md) |
| 5 | [867. Transpose Matrix](https://leetcode.com/problems/transpose-matrix/) | Easy | 6+ months | 17.9 | Todo |  |  |  | [notes](02.%20Matrix%20Rotation%20%26%20Transformation/0867.%20Transpose%20Matrix/0867.%20Transpose%20Matrix.md) |
| 6 | [566. Reshape the Matrix](https://leetcode.com/problems/reshape-the-matrix/) | Easy | 6+ months | 10.9 | Todo |  |  |  | [notes](02.%20Matrix%20Rotation%20%26%20Transformation/0566.%20Reshape%20the%20Matrix/0566.%20Reshape%20the%20Matrix.md) |
| 7 | [1861. Rotating the Box](https://leetcode.com/problems/rotating-the-box/) | Medium | 6+ months | 8.4 | Todo |  |  |  | [notes](02.%20Matrix%20Rotation%20%26%20Transformation/1861.%20Rotating%20the%20Box/1861.%20Rotating%20the%20Box.md) |
| 8 | [1914. Cyclically Rotating a Grid](https://leetcode.com/problems/cyclically-rotating-a-grid/) | Medium | 6+ months | 6.8 | Todo |  |  |  | [notes](02.%20Matrix%20Rotation%20%26%20Transformation/1914.%20Cyclically%20Rotating%20a%20Grid/1914.%20Cyclically%20Rotating%20a%20Grid.md) |
| 9 | [1886. Determine Whether Matrix Can Be Obtained By Rotation](https://leetcode.com/problems/determine-whether-matrix-can-be-obtained-by-rotation/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Matrix%20Rotation%20%26%20Transformation/1886.%20Determine%20Whether%20Matrix%20Can%20Be%20Obtained%20By%20Rotation/1886.%20Determine%20Whether%20Matrix%20Can%20Be%20Obtained%20By%20Rotation.md) |
| 10 | [2946. Matrix Similarity After Cyclic Shifts](https://leetcode.com/problems/matrix-similarity-after-cyclic-shifts/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Matrix%20Rotation%20%26%20Transformation/2946.%20Matrix%20Similarity%20After%20Cyclic%20Shifts/2946.%20Matrix%20Similarity%20After%20Cyclic%20Shifts.md) |
| 11 | [3643. Flip Square Submatrix Vertically](https://leetcode.com/problems/flip-square-submatrix-vertically/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Matrix%20Rotation%20%26%20Transformation/3643.%20Flip%20Square%20Submatrix%20Vertically/3643.%20Flip%20Square%20Submatrix%20Vertically.md) |

## 03. In-Place Matrix Marking

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [73. Set Matrix Zeroes](https://leetcode.com/problems/set-matrix-zeroes/) | Medium | 3 months | 49.8 | ✅ Solved |  |  |  | [notes](03.%20In-Place%20Matrix%20Marking/0073.%20Set%20Matrix%20Zeroes/0073.%20Set%20Matrix%20Zeroes.md) |
| 2 | [289. Game of Life](https://leetcode.com/problems/game-of-life/) | Medium | 6+ months | 31.2 | Todo |  |  |  | [notes](03.%20In-Place%20Matrix%20Marking/0289.%20Game%20of%20Life/0289.%20Game%20of%20Life.md) |
| 3 | [782. Transform to Chessboard](https://leetcode.com/problems/transform-to-chessboard/) | Hard | 6+ months | 28.8 | Todo |  |  |  | [notes](03.%20In-Place%20Matrix%20Marking/0782.%20Transform%20to%20Chessboard/0782.%20Transform%20to%20Chessboard.md) |

## 04. Grid Simulation

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [419. Battleships in a Board](https://leetcode.com/problems/battleships-in-a-board/) | Medium | 30 days | 16.6 | Todo |  |  |  | [notes](04.%20Grid%20Simulation/0419.%20Battleships%20in%20a%20Board/0419.%20Battleships%20in%20a%20Board.md) |
| 2 | [463. Island Perimeter](https://leetcode.com/problems/island-perimeter/) | Easy | 3 months | 38.3 | ✅ Solved |  |  |  | [notes](04.%20Grid%20Simulation/0463.%20Island%20Perimeter/0463.%20Island%20Perimeter.md) |
| 3 | [999. Available Captures for Rook](https://leetcode.com/problems/available-captures-for-rook/) | Easy | 6+ months | 5.1 | Todo |  |  |  | [notes](04.%20Grid%20Simulation/0999.%20Available%20Captures%20for%20Rook/0999.%20Available%20Captures%20for%20Rook.md) |
| 4 | [723. Candy Crush](https://leetcode.com/problems/candy-crush/) 🔒 | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Grid%20Simulation/0723.%20Candy%20Crush/0723.%20Candy%20Crush.md) |
| 5 | [874. Walking Robot Simulation](https://leetcode.com/problems/walking-robot-simulation/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Grid%20Simulation/0874.%20Walking%20Robot%20Simulation/0874.%20Walking%20Robot%20Simulation.md) |
| 6 | [1275. Find Winner on a Tic Tac Toe Game](https://leetcode.com/problems/find-winner-on-a-tic-tac-toe-game/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Grid%20Simulation/1275.%20Find%20Winner%20on%20a%20Tic%20Tac%20Toe%20Game/1275.%20Find%20Winner%20on%20a%20Tic%20Tac%20Toe%20Game.md) |
| 7 | [2257. Count Unguarded Cells in the Grid](https://leetcode.com/problems/count-unguarded-cells-in-the-grid/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Grid%20Simulation/2257.%20Count%20Unguarded%20Cells%20in%20the%20Grid/2257.%20Count%20Unguarded%20Cells%20in%20the%20Grid.md) |
| 8 | [2596. Check Knight Tour Configuration](https://leetcode.com/problems/check-knight-tour-configuration/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Grid%20Simulation/2596.%20Check%20Knight%20Tour%20Configuration/2596.%20Check%20Knight%20Tour%20Configuration.md) |
| 9 | [1706. Where Will the Ball Fall](https://leetcode.com/problems/where-will-the-ball-fall/) | Medium | 6+ months | 29.9 | Todo |  |  |  | [notes](04.%20Grid%20Simulation/1706.%20Where%20Will%20the%20Ball%20Fall/1706.%20Where%20Will%20the%20Ball%20Fall.md) |
| 10 | [1222. Queens That Can Attack the King](https://leetcode.com/problems/queens-that-can-attack-the-king/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Grid%20Simulation/1222.%20Queens%20That%20Can%20Attack%20the%20King/1222.%20Queens%20That%20Can%20Attack%20the%20King.md) |

## 05. Process Simulation

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [3069. Distribute Elements Into Two Arrays I](https://leetcode.com/problems/distribute-elements-into-two-arrays-i/) | Easy | 6 months | 5.0 | Todo |  |  |  | [notes](05.%20Process%20Simulation/3069.%20Distribute%20Elements%20Into%20Two%20Arrays%20I/3069.%20Distribute%20Elements%20Into%20Two%20Arrays%20I.md) |
| 2 | [657. Robot Return to Origin](https://leetcode.com/problems/robot-return-to-origin/) | Easy | 6+ months | 34.8 | Todo |  |  |  | [notes](05.%20Process%20Simulation/0657.%20Robot%20Return%20to%20Origin/0657.%20Robot%20Return%20to%20Origin.md) |
| 3 | [158. Read N Characters Given read4 II - Call Multiple Times](https://leetcode.com/problems/read-n-characters-given-read4-ii-call-multiple-times/) 🔒 | Hard | 6+ months | 30.1 | Todo |  |  |  | [notes](05.%20Process%20Simulation/0158.%20Read%20N%20Characters%20Given%20read4%20II%20-%20Call%20Multiple%20Times/0158.%20Read%20N%20Characters%20Given%20read4%20II%20-%20Call%20Multiple%20Times.md) |
| 4 | [2079. Watering Plants](https://leetcode.com/problems/watering-plants/) | Medium | 6+ months | 30.0 | Todo |  |  |  | [notes](05.%20Process%20Simulation/2079.%20Watering%20Plants/2079.%20Watering%20Plants.md) |
| 5 | [3477. Fruits Into Baskets II](https://leetcode.com/problems/fruits-into-baskets-ii/) | Easy | 6+ months | 19.0 | 🟡 Attempted |  |  |  | [notes](05.%20Process%20Simulation/3477.%20Fruits%20Into%20Baskets%20II/3477.%20Fruits%20Into%20Baskets%20II.md) |
| 6 | [3507. Minimum Pair Removal to Sort Array I](https://leetcode.com/problems/minimum-pair-removal-to-sort-array-i/) | Easy | 6+ months | 15.5 | Todo |  |  |  | [notes](05.%20Process%20Simulation/3507.%20Minimum%20Pair%20Removal%20to%20Sort%20Array%20I/3507.%20Minimum%20Pair%20Removal%20to%20Sort%20Array%20I.md) |
| 7 | [2011. Final Value of Variable After Performing Operations](https://leetcode.com/problems/final-value-of-variable-after-performing-operations/) | Easy | 6+ months | 13.9 | ✅ Solved |  |  |  | [notes](05.%20Process%20Simulation/2011.%20Final%20Value%20of%20Variable%20After%20Performing%20Operations/2011.%20Final%20Value%20of%20Variable%20After%20Performing%20Operations.md) |
| 8 | [2069. Walking Robot Simulation II](https://leetcode.com/problems/walking-robot-simulation-ii/) | Medium | 6+ months | 11.0 | Todo |  |  |  | [notes](05.%20Process%20Simulation/2069.%20Walking%20Robot%20Simulation%20II/2069.%20Walking%20Robot%20Simulation%20II.md) |
| 9 | [157. Read N Characters Given Read4](https://leetcode.com/problems/read-n-characters-given-read4/) 🔒 | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Process%20Simulation/0157.%20Read%20N%20Characters%20Given%20Read4/0157.%20Read%20N%20Characters%20Given%20Read4.md) |
| 10 | [1041. Robot Bounded In Circle](https://leetcode.com/problems/robot-bounded-in-circle/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Process%20Simulation/1041.%20Robot%20Bounded%20In%20Circle/1041.%20Robot%20Bounded%20In%20Circle.md) |
| 11 | [1583. Count Unhappy Friends](https://leetcode.com/problems/count-unhappy-friends/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Process%20Simulation/1583.%20Count%20Unhappy%20Friends/1583.%20Count%20Unhappy%20Friends.md) |
| 12 | [1138. Alphabet Board Path](https://leetcode.com/problems/alphabet-board-path/) | Medium | 6+ months | 30.1 | Todo |  |  |  | [notes](05.%20Process%20Simulation/1138.%20Alphabet%20Board%20Path/1138.%20Alphabet%20Board%20Path.md) |
| 13 | [2728. Count Houses in a Circular Street](https://leetcode.com/problems/count-houses-in-a-circular-street/) 🔒 | Easy | 6+ months | 28.8 | Todo |  |  |  | [notes](05.%20Process%20Simulation/2728.%20Count%20Houses%20in%20a%20Circular%20Street/2728.%20Count%20Houses%20in%20a%20Circular%20Street.md) |
| 14 | [1389. Create Target Array in the Given Order](https://leetcode.com/problems/create-target-array-in-the-given-order/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](05.%20Process%20Simulation/1389.%20Create%20Target%20Array%20in%20the%20Given%20Order/1389.%20Create%20Target%20Array%20in%20the%20Given%20Order.md) |
| 15 | [1646. Get Maximum in Generated Array](https://leetcode.com/problems/get-maximum-in-generated-array/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Process%20Simulation/1646.%20Get%20Maximum%20in%20Generated%20Array/1646.%20Get%20Maximum%20in%20Generated%20Array.md) |
