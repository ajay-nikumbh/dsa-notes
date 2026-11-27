# 06. Sorting

[Back to Google](../README.md) · [Back to DSA Notes](../../../README.md)

56 Google problems: 26 Easy, 25 Medium, 5 Hard, in 5 sub-patterns.

## Sub-patterns

| # | Sub-pattern | Questions | Easy | Medium | Hard | Last 3 Months | Solved | Most Asked |
|:---:|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---|
| 01 | [Custom Comparator Sorting](#01-custom-comparator-sorting) | 10 | 6 | 4 | 0 | 2 | 2 | 179. Largest Number, 506. Relative Ranks, 1996. The Number of Weak Characters in the Game |
| 02 | [Counting & Bucket Sort](#02-counting--bucket-sort) | 16 | 8 | 7 | 1 | 4 | 4 | 451. Sort Characters By Frequency, 274. H-Index, 1365. How Many Numbers Are Smaller Than the Current Number |
| 03 | [Merge Sort Applications](#03-merge-sort-applications) | 5 | 0 | 1 | 4 | 1 | 1 | 912. Sort an Array, 493. Reverse Pairs, 315. Count of Smaller Numbers After Self |
| 04 | [Quick Sort & Partition](#04-quick-sort--partition) | 1 | 0 | 1 | 0 | 0 | 0 | 324. Wiggle Sort II |
| 05 | [Sort Then Scan](#05-sort-then-scan) | 24 | 12 | 12 | 0 | 2 | 6 | 1331. Rank Transform of an Array, 1502. Can Make Arithmetic Progression From Sequence, 1630. Arithmetic Subarrays |

**Columns**

- **Last Asked**: most recent LeetCode window that lists the problem for Google (30 days, 3 months, 6 months, 6+ months).
- **Frequency**: LeetCode frequency score (0-100) in the Google "All" list.
- **Status**: your LeetCode status on the day this file was generated. 🔒 after a title means LeetCode Premium.
- **Logic / Key Idea, Time, Space**: fill these in as you solve. A rebuild keeps what you typed.
- **Notes**: link to the problem's notes file.

Inside each sub-pattern, rows are sorted by most recent window, then by frequency (highest first).

## 01. Custom Comparator Sorting

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [179. Largest Number](https://leetcode.com/problems/largest-number/) | Medium | 3 months | 34.1 | Todo |  |  |  | [notes](01.%20Custom%20Comparator%20Sorting/0179.%20Largest%20Number/0179.%20Largest%20Number.md) |
| 2 | [1636. Sort Array by Increasing Frequency](https://leetcode.com/problems/sort-array-by-increasing-frequency/) | Easy | 3 months | 5.8 | Todo |  |  |  | [notes](01.%20Custom%20Comparator%20Sorting/1636.%20Sort%20Array%20by%20Increasing%20Frequency/1636.%20Sort%20Array%20by%20Increasing%20Frequency.md) |
| 3 | [2343. Query Kth Smallest Trimmed Number](https://leetcode.com/problems/query-kth-smallest-trimmed-number/) | Medium | 6 months | 5.5 | Todo |  |  |  | [notes](01.%20Custom%20Comparator%20Sorting/2343.%20Query%20Kth%20Smallest%20Trimmed%20Number/2343.%20Query%20Kth%20Smallest%20Trimmed%20Number.md) |
| 4 | [506. Relative Ranks](https://leetcode.com/problems/relative-ranks/) | Easy | 6+ months | 33.6 | ✅ Solved |  |  |  | [notes](01.%20Custom%20Comparator%20Sorting/0506.%20Relative%20Ranks/0506.%20Relative%20Ranks.md) |
| 5 | [1996. The Number of Weak Characters in the Game](https://leetcode.com/problems/the-number-of-weak-characters-in-the-game/) | Medium | 6+ months | 31.0 | Todo |  |  |  | [notes](01.%20Custom%20Comparator%20Sorting/1996.%20The%20Number%20of%20Weak%20Characters%20in%20the%20Game/1996.%20The%20Number%20of%20Weak%20Characters%20in%20the%20Game.md) |
| 6 | [1366. Rank Teams by Votes](https://leetcode.com/problems/rank-teams-by-votes/) | Medium | 6+ months | 30.6 | Todo |  |  |  | [notes](01.%20Custom%20Comparator%20Sorting/1366.%20Rank%20Teams%20by%20Votes/1366.%20Rank%20Teams%20by%20Votes.md) |
| 7 | [1356. Sort Integers by The Number of 1 Bits](https://leetcode.com/problems/sort-integers-by-the-number-of-1-bits/) | Easy | 6+ months | 11.4 | Todo |  |  |  | [notes](01.%20Custom%20Comparator%20Sorting/1356.%20Sort%20Integers%20by%20The%20Number%20of%201%20Bits/1356.%20Sort%20Integers%20by%20The%20Number%20of%201%20Bits.md) |
| 8 | [2418. Sort the People](https://leetcode.com/problems/sort-the-people/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](01.%20Custom%20Comparator%20Sorting/2418.%20Sort%20the%20People/2418.%20Sort%20the%20People.md) |
| 9 | [3606. Coupon Code Validator](https://leetcode.com/problems/coupon-code-validator/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Custom%20Comparator%20Sorting/3606.%20Coupon%20Code%20Validator/3606.%20Coupon%20Code%20Validator.md) |
| 10 | [3769. Sort Integers by Binary Reflection](https://leetcode.com/problems/sort-integers-by-binary-reflection/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Custom%20Comparator%20Sorting/3769.%20Sort%20Integers%20by%20Binary%20Reflection/3769.%20Sort%20Integers%20by%20Binary%20Reflection.md) |

## 02. Counting & Bucket Sort

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [451. Sort Characters By Frequency](https://leetcode.com/problems/sort-characters-by-frequency/) | Medium | 3 months | 39.9 | Todo |  |  |  | [notes](02.%20Counting%20%26%20Bucket%20Sort/0451.%20Sort%20Characters%20By%20Frequency/0451.%20Sort%20Characters%20By%20Frequency.md) |
| 2 | [2089. Find Target Indices After Sorting Array](https://leetcode.com/problems/find-target-indices-after-sorting-array/) | Easy | 3 months | 35.0 | ✅ Solved |  |  |  | [notes](02.%20Counting%20%26%20Bucket%20Sort/2089.%20Find%20Target%20Indices%20After%20Sorting%20Array/2089.%20Find%20Target%20Indices%20After%20Sorting%20Array.md) |
| 3 | [164. Maximum Gap](https://leetcode.com/problems/maximum-gap/) | Medium | 3 months | 18.9 | Todo |  |  |  | [notes](02.%20Counting%20%26%20Bucket%20Sort/0164.%20Maximum%20Gap/0164.%20Maximum%20Gap.md) |
| 4 | [220. Contains Duplicate III](https://leetcode.com/problems/contains-duplicate-iii/) | Hard | 3 months | 15.3 | Todo |  |  |  | [notes](02.%20Counting%20%26%20Bucket%20Sort/0220.%20Contains%20Duplicate%20III/0220.%20Contains%20Duplicate%20III.md) |
| 5 | [274. H-Index](https://leetcode.com/problems/h-index/) | Medium | 6 months | 37.4 | Todo |  |  |  | [notes](02.%20Counting%20%26%20Bucket%20Sort/0274.%20H-Index/0274.%20H-Index.md) |
| 6 | [1365. How Many Numbers Are Smaller Than the Current Number](https://leetcode.com/problems/how-many-numbers-are-smaller-than-the-current-number/) | Easy | 6 months | 37.4 | ✅ Solved |  |  |  | [notes](02.%20Counting%20%26%20Bucket%20Sort/1365.%20How%20Many%20Numbers%20Are%20Smaller%20Than%20the%20Current%20Number/1365.%20How%20Many%20Numbers%20Are%20Smaller%20Than%20the%20Current%20Number.md) |
| 7 | [1051. Height Checker](https://leetcode.com/problems/height-checker/) | Easy | 6 months | 6.0 | Todo |  |  |  | [notes](02.%20Counting%20%26%20Bucket%20Sort/1051.%20Height%20Checker/1051.%20Height%20Checker.md) |
| 8 | [1122. Relative Sort Array](https://leetcode.com/problems/relative-sort-array/) | Easy | 6+ months | 10.1 | ✅ Solved |  |  |  | [notes](02.%20Counting%20%26%20Bucket%20Sort/1122.%20Relative%20Sort%20Array/1122.%20Relative%20Sort%20Array.md) |
| 9 | [2231. Largest Number After Digit Swaps by Parity](https://leetcode.com/problems/largest-number-after-digit-swaps-by-parity/) | Easy | 6+ months | 5.2 | Todo |  |  |  | [notes](02.%20Counting%20%26%20Bucket%20Sort/2231.%20Largest%20Number%20After%20Digit%20Swaps%20by%20Parity/2231.%20Largest%20Number%20After%20Digit%20Swaps%20by%20Parity.md) |
| 10 | [791. Custom Sort String](https://leetcode.com/problems/custom-sort-string/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](02.%20Counting%20%26%20Bucket%20Sort/0791.%20Custom%20Sort%20String/0791.%20Custom%20Sort%20String.md) |
| 11 | [1370. Increasing Decreasing String](https://leetcode.com/problems/increasing-decreasing-string/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Counting%20%26%20Bucket%20Sort/1370.%20Increasing%20Decreasing%20String/1370.%20Increasing%20Decreasing%20String.md) |
| 12 | [1859. Sorting the Sentence](https://leetcode.com/problems/sorting-the-sentence/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Counting%20%26%20Bucket%20Sort/1859.%20Sorting%20the%20Sentence/1859.%20Sorting%20the%20Sentence.md) |
| 13 | [2164. Sort Even and Odd Indices Independently](https://leetcode.com/problems/sort-even-and-odd-indices-independently/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Counting%20%26%20Bucket%20Sort/2164.%20Sort%20Even%20and%20Odd%20Indices%20Independently/2164.%20Sort%20Even%20and%20Odd%20Indices%20Independently.md) |
| 14 | [2785. Sort Vowels in a String](https://leetcode.com/problems/sort-vowels-in-a-string/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Counting%20%26%20Bucket%20Sort/2785.%20Sort%20Vowels%20in%20a%20String/2785.%20Sort%20Vowels%20in%20a%20String.md) |
| 15 | [1057. Campus Bikes](https://leetcode.com/problems/campus-bikes/) 🔒 | Medium | 6+ months | 28.8 | Todo |  |  |  | [notes](02.%20Counting%20%26%20Bucket%20Sort/1057.%20Campus%20Bikes/1057.%20Campus%20Bikes.md) |
| 16 | [1833. Maximum Ice Cream Bars](https://leetcode.com/problems/maximum-ice-cream-bars/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Counting%20%26%20Bucket%20Sort/1833.%20Maximum%20Ice%20Cream%20Bars/1833.%20Maximum%20Ice%20Cream%20Bars.md) |

## 03. Merge Sort Applications

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [912. Sort an Array](https://leetcode.com/problems/sort-an-array/) | Medium | 30 days | 45.9 | Todo |  |  |  | [notes](03.%20Merge%20Sort%20Applications/0912.%20Sort%20an%20Array/0912.%20Sort%20an%20Array.md) |
| 2 | [493. Reverse Pairs](https://leetcode.com/problems/reverse-pairs/) | Hard | 6 months | 43.8 | ✅ Solved |  |  |  | [notes](03.%20Merge%20Sort%20Applications/0493.%20Reverse%20Pairs/0493.%20Reverse%20Pairs.md) |
| 3 | [315. Count of Smaller Numbers After Self](https://leetcode.com/problems/count-of-smaller-numbers-after-self/) | Hard | 6 months | 39.6 | Todo |  |  |  | [notes](03.%20Merge%20Sort%20Applications/0315.%20Count%20of%20Smaller%20Numbers%20After%20Self/0315.%20Count%20of%20Smaller%20Numbers%20After%20Self.md) |
| 4 | [327. Count of Range Sum](https://leetcode.com/problems/count-of-range-sum/) | Hard | 6 months | 34.5 | Todo |  |  |  | [notes](03.%20Merge%20Sort%20Applications/0327.%20Count%20of%20Range%20Sum/0327.%20Count%20of%20Range%20Sum.md) |
| 5 | [2426. Number of Pairs Satisfying Inequality](https://leetcode.com/problems/number-of-pairs-satisfying-inequality/) | Hard | 6+ months | 30.1 | Todo |  |  |  | [notes](03.%20Merge%20Sort%20Applications/2426.%20Number%20of%20Pairs%20Satisfying%20Inequality/2426.%20Number%20of%20Pairs%20Satisfying%20Inequality.md) |

## 04. Quick Sort & Partition

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203; | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [324. Wiggle Sort II](https://leetcode.com/problems/wiggle-sort-ii/) | Medium | 6 months | 36.0 | Todo |  |  |  | [notes](04.%20Quick%20Sort%20%26%20Partition/0324.%20Wiggle%20Sort%20II/0324.%20Wiggle%20Sort%20II.md) |

## 05. Sort Then Scan

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [462. Minimum Moves to Equal Array Elements II](https://leetcode.com/problems/minimum-moves-to-equal-array-elements-ii/) | Medium | 30 days | 23.3 | Todo |  |  |  | [notes](05.%20Sort%20Then%20Scan/0462.%20Minimum%20Moves%20to%20Equal%20Array%20Elements%20II/0462.%20Minimum%20Moves%20to%20Equal%20Array%20Elements%20II.md) |
| 2 | [1502. Can Make Arithmetic Progression From Sequence](https://leetcode.com/problems/can-make-arithmetic-progression-from-sequence/) | Easy | 3 months | 36.8 | Todo |  |  |  | [notes](05.%20Sort%20Then%20Scan/1502.%20Can%20Make%20Arithmetic%20Progression%20From%20Sequence/1502.%20Can%20Make%20Arithmetic%20Progression%20From%20Sequence.md) |
| 3 | [1331. Rank Transform of an Array](https://leetcode.com/problems/rank-transform-of-an-array/) | Easy | 6 months | 37.3 | ✅ Solved |  |  |  | [notes](05.%20Sort%20Then%20Scan/1331.%20Rank%20Transform%20of%20an%20Array/1331.%20Rank%20Transform%20of%20an%20Array.md) |
| 4 | [628. Maximum Product of Three Numbers](https://leetcode.com/problems/maximum-product-of-three-numbers/) | Easy | 6 months | 26.5 | Todo |  |  |  | [notes](05.%20Sort%20Then%20Scan/0628.%20Maximum%20Product%20of%20Three%20Numbers/0628.%20Maximum%20Product%20of%20Three%20Numbers.md) |
| 5 | [976. Largest Perimeter Triangle](https://leetcode.com/problems/largest-perimeter-triangle/) | Easy | 6 months | 12.0 | Todo |  |  |  | [notes](05.%20Sort%20Then%20Scan/0976.%20Largest%20Perimeter%20Triangle/0976.%20Largest%20Perimeter%20Triangle.md) |
| 6 | [1630. Arithmetic Subarrays](https://leetcode.com/problems/arithmetic-subarrays/) | Medium | 6+ months | 31.7 | Todo |  |  |  | [notes](05.%20Sort%20Then%20Scan/1630.%20Arithmetic%20Subarrays/1630.%20Arithmetic%20Subarrays.md) |
| 7 | [2966. Divide Array Into Arrays With Max Difference](https://leetcode.com/problems/divide-array-into-arrays-with-max-difference/) | Medium | 6+ months | 31.2 | ✅ Solved |  |  |  | [notes](05.%20Sort%20Then%20Scan/2966.%20Divide%20Array%20Into%20Arrays%20With%20Max%20Difference/2966.%20Divide%20Array%20Into%20Arrays%20With%20Max%20Difference.md) |
| 8 | [1509. Minimum Difference Between Largest and Smallest Value in Three Moves](https://leetcode.com/problems/minimum-difference-between-largest-and-smallest-value-in-three-moves/) | Medium | 6+ months | 31.0 | Todo |  |  |  | [notes](05.%20Sort%20Then%20Scan/1509.%20Minimum%20Difference%20Between%20Largest%20and%20Smallest%20Value%20in%20Three%20Moves/1509.%20Minimum%20Difference%20Between%20Largest%20and%20Smallest%20Value%20in%20Three%20Moves.md) |
| 9 | [3010. Divide an Array Into Subarrays With Minimum Cost I](https://leetcode.com/problems/divide-an-array-into-subarrays-with-minimum-cost-i/) | Easy | 6+ months | 17.6 | Todo |  |  |  | [notes](05.%20Sort%20Then%20Scan/3010.%20Divide%20an%20Array%20Into%20Subarrays%20With%20Minimum%20Cost%20I/3010.%20Divide%20an%20Array%20Into%20Subarrays%20With%20Minimum%20Cost%20I.md) |
| 10 | [561. Array Partition](https://leetcode.com/problems/array-partition/) | Easy | 6+ months | 12.2 | Todo |  |  |  | [notes](05.%20Sort%20Then%20Scan/0561.%20Array%20Partition/0561.%20Array%20Partition.md) |
| 11 | [3531. Count Covered Buildings](https://leetcode.com/problems/count-covered-buildings/) | Medium | 6+ months | 10.2 | Todo |  |  |  | [notes](05.%20Sort%20Then%20Scan/3531.%20Count%20Covered%20Buildings/3531.%20Count%20Covered%20Buildings.md) |
| 12 | [1200. Minimum Absolute Difference](https://leetcode.com/problems/minimum-absolute-difference/) | Easy | 6+ months | 8.4 | ✅ Solved |  |  |  | [notes](05.%20Sort%20Then%20Scan/1200.%20Minimum%20Absolute%20Difference/1200.%20Minimum%20Absolute%20Difference.md) |
| 13 | [539. Minimum Time Difference](https://leetcode.com/problems/minimum-time-difference/) | Medium | 6+ months | 7.6 | ✅ Solved |  |  |  | [notes](05.%20Sort%20Then%20Scan/0539.%20Minimum%20Time%20Difference/0539.%20Minimum%20Time%20Difference.md) |
| 14 | [2948. Make Lexicographically Smallest Array by Swapping Elements](https://leetcode.com/problems/make-lexicographically-smallest-array-by-swapping-elements/) | Medium | 6+ months | 6.1 | Todo |  |  |  | [notes](05.%20Sort%20Then%20Scan/2948.%20Make%20Lexicographically%20Smallest%20Array%20by%20Swapping%20Elements/2948.%20Make%20Lexicographically%20Smallest%20Array%20by%20Swapping%20Elements.md) |
| 15 | [1637. Widest Vertical Area Between Two Points Containing No Points](https://leetcode.com/problems/widest-vertical-area-between-two-points-containing-no-points/) | Easy | 6+ months | 5.3 | ✅ Solved |  |  |  | [notes](05.%20Sort%20Then%20Scan/1637.%20Widest%20Vertical%20Area%20Between%20Two%20Points%20Containing%20No%20Points/1637.%20Widest%20Vertical%20Area%20Between%20Two%20Points%20Containing%20No%20Points.md) |
| 16 | [1465. Maximum Area of a Piece of Cake After Horizontal and Vertical Cuts](https://leetcode.com/problems/maximum-area-of-a-piece-of-cake-after-horizontal-and-vertical-cuts/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Sort%20Then%20Scan/1465.%20Maximum%20Area%20of%20a%20Piece%20of%20Cake%20After%20Horizontal%20and%20Vertical%20Cuts/1465.%20Maximum%20Area%20of%20a%20Piece%20of%20Cake%20After%20Horizontal%20and%20Vertical%20Cuts.md) |
| 17 | [2033. Minimum Operations to Make a Uni-Value Grid](https://leetcode.com/problems/minimum-operations-to-make-a-uni-value-grid/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Sort%20Then%20Scan/2033.%20Minimum%20Operations%20to%20Make%20a%20Uni-Value%20Grid/2033.%20Minimum%20Operations%20to%20Make%20a%20Uni-Value%20Grid.md) |
| 18 | [2148. Count Elements With Strictly Smaller and Greater Elements ](https://leetcode.com/problems/count-elements-with-strictly-smaller-and-greater-elements/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Sort%20Then%20Scan/2148.%20Count%20Elements%20With%20Strictly%20Smaller%20and%20Greater%20Elements%20/2148.%20Count%20Elements%20With%20Strictly%20Smaller%20and%20Greater%20Elements%20.md) |
| 19 | [2500. Delete Greatest Value in Each Row](https://leetcode.com/problems/delete-greatest-value-in-each-row/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Sort%20Then%20Scan/2500.%20Delete%20Greatest%20Value%20in%20Each%20Row/2500.%20Delete%20Greatest%20Value%20in%20Each%20Row.md) |
| 20 | [2731. Movement of Robots](https://leetcode.com/problems/movement-of-robots/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Sort%20Then%20Scan/2731.%20Movement%20of%20Robots/2731.%20Movement%20of%20Robots.md) |
| 21 | [2943. Maximize Area of Square Hole in Grid](https://leetcode.com/problems/maximize-area-of-square-hole-in-grid/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Sort%20Then%20Scan/2943.%20Maximize%20Area%20of%20Square%20Hole%20in%20Grid/2943.%20Maximize%20Area%20of%20Square%20Hole%20in%20Grid.md) |
| 22 | [2974. Minimum Number Game](https://leetcode.com/problems/minimum-number-game/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](05.%20Sort%20Then%20Scan/2974.%20Minimum%20Number%20Game/2974.%20Minimum%20Number%20Game.md) |
| 23 | [1619. Mean of Array After Removing Some Elements](https://leetcode.com/problems/mean-of-array-after-removing-some-elements/) | Easy | 6+ months | 28.8 | Todo |  |  |  | [notes](05.%20Sort%20Then%20Scan/1619.%20Mean%20of%20Array%20After%20Removing%20Some%20Elements/1619.%20Mean%20of%20Array%20After%20Removing%20Some%20Elements.md) |
| 24 | [2345. Finding the Number of Visible Mountains](https://leetcode.com/problems/finding-the-number-of-visible-mountains/) 🔒 | Medium | 6+ months | 28.8 | Todo |  |  |  | [notes](05.%20Sort%20Then%20Scan/2345.%20Finding%20the%20Number%20of%20Visible%20Mountains/2345.%20Finding%20the%20Number%20of%20Visible%20Mountains.md) |
