# 03. Two Pointers

[Back to Facebook](../README.md) · [Back to DSA Notes](../../../README.md)

54 Meta (Facebook) problems: 23 Easy, 30 Medium, 1 Hard, in 6 sub-patterns.

## Sub-patterns

| # | Sub-pattern | Questions | Easy | Medium | Hard | Last 3 Months | Solved | Most Asked |
|:---:|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---|
| 01 | [Opposite Ends](#01-opposite-ends) | 15 | 6 | 8 | 1 | 3 | 11 | 42. Trapping Rain Water, 11. Container With Most Water, 977. Squares of a Sorted Array |
| 02 | [Same Direction (Read-Write)](#02-same-direction-read-write) | 17 | 8 | 9 | 0 | 4 | 9 | 26. Remove Duplicates from Sorted Array, 283. Move Zeroes, 80. Remove Duplicates from Sorted Array II |
| 03 | [Two Sum & K-Sum Variants](#03-two-sum--k-sum-variants) | 10 | 1 | 9 | 0 | 2 | 4 | 15. 3Sum, 18. 4Sum, 16. 3Sum Closest |
| 04 | [Merge Two Sorted Sequences](#04-merge-two-sorted-sequences) | 5 | 4 | 1 | 0 | 1 | 3 | 88. Merge Sorted Array, 1868. Product of Two Run-Length Encoded Arrays, 1213. Intersection of Three Sorted Arrays |
| 05 | [Partitioning (Dutch Flag)](#05-partitioning-dutch-flag) | 3 | 1 | 2 | 0 | 0 | 2 | 75. Sort Colors, 905. Sort Array By Parity, 2161. Partition Array According to Given Pivot |
| 06 | [Subsequence Matching](#06-subsequence-matching) | 4 | 3 | 1 | 0 | 1 | 2 | 408. Valid Word Abbreviation, 392. Is Subsequence, 792. Number of Matching Subsequences |

**Columns**

- **Last Asked**: most recent LeetCode window that lists the problem for Meta (30 days, 3 months, 6 months or 6+ months).
- **Frequency**: LeetCode frequency score (0-100) in the Meta "All" list.
- **Status**: your LeetCode status on the day this file was generated. 🔒 after a title means LeetCode Premium.
- **Logic / Key Idea, Time, Space**: fill these in as you solve. A rebuild keeps what you typed.
- **Notes**: link to the problem's notes file.

Inside each sub-pattern, rows are sorted by most recent window, then by frequency (highest first).

## 01. Opposite Ends

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [11. Container With Most Water](https://leetcode.com/problems/container-with-most-water/) | Medium | 30 days | 57.1 | ✅ Solved |  |  |  | [notes](01.%20Opposite%20Ends/0011.%20Container%20With%20Most%20Water/0011.%20Container%20With%20Most%20Water.md) |
| 2 | [42. Trapping Rain Water](https://leetcode.com/problems/trapping-rain-water/) | Hard | 3 months | 59.5 | ✅ Solved |  |  |  | [notes](01.%20Opposite%20Ends/0042.%20Trapping%20Rain%20Water/0042.%20Trapping%20Rain%20Water.md) |
| 3 | [344. Reverse String](https://leetcode.com/problems/reverse-string/) | Easy | 3 months | 33.9 | ✅ Solved |  |  |  | [notes](01.%20Opposite%20Ends/0344.%20Reverse%20String/0344.%20Reverse%20String.md) |
| 4 | [977. Squares of a Sorted Array](https://leetcode.com/problems/squares-of-a-sorted-array/) | Easy | 6 months | 55.1 | ✅ Solved |  |  |  | [notes](01.%20Opposite%20Ends/0977.%20Squares%20of%20a%20Sorted%20Array/0977.%20Squares%20of%20a%20Sorted%20Array.md) |
| 5 | [881. Boats to Save People](https://leetcode.com/problems/boats-to-save-people/) | Medium | 6 months | 26.7 | ✅ Solved |  |  |  | [notes](01.%20Opposite%20Ends/0881.%20Boats%20to%20Save%20People/0881.%20Boats%20to%20Save%20People.md) |
| 6 | [633. Sum of Square Numbers](https://leetcode.com/problems/sum-of-square-numbers/) | Medium | 6 months | 20.4 | Todo |  |  |  | [notes](01.%20Opposite%20Ends/0633.%20Sum%20of%20Square%20Numbers/0633.%20Sum%20of%20Square%20Numbers.md) |
| 7 | [345. Reverse Vowels of a String](https://leetcode.com/problems/reverse-vowels-of-a-string/) | Easy | 6 months | 17.2 | ✅ Solved |  |  |  | [notes](01.%20Opposite%20Ends/0345.%20Reverse%20Vowels%20of%20a%20String/0345.%20Reverse%20Vowels%20of%20a%20String.md) |
| 8 | [541. Reverse String II](https://leetcode.com/problems/reverse-string-ii/) | Easy | 6 months | 16.9 | ✅ Solved |  |  |  | [notes](01.%20Opposite%20Ends/0541.%20Reverse%20String%20II/0541.%20Reverse%20String%20II.md) |
| 9 | [1498. Number of Subsequences That Satisfy the Given Sum Condition](https://leetcode.com/problems/number-of-subsequences-that-satisfy-the-given-sum-condition/) | Medium | 6+ months | 11.5 | Todo |  |  |  | [notes](01.%20Opposite%20Ends/1498.%20Number%20of%20Subsequences%20That%20Satisfy%20the%20Given%20Sum%20Condition/1498.%20Number%20of%20Subsequences%20That%20Satisfy%20the%20Given%20Sum%20Condition.md) |
| 10 | [1750. Minimum Length of String After Deleting Similar Ends](https://leetcode.com/problems/minimum-length-of-string-after-deleting-similar-ends/) | Medium | 6+ months | 9.1 | ✅ Solved |  |  |  | [notes](01.%20Opposite%20Ends/1750.%20Minimum%20Length%20of%20String%20After%20Deleting%20Similar%20Ends/1750.%20Minimum%20Length%20of%20String%20After%20Deleting%20Similar%20Ends.md) |
| 11 | [557. Reverse Words in a String III](https://leetcode.com/problems/reverse-words-in-a-string-iii/) | Easy | 6+ months | 6.6 | ✅ Solved |  |  |  | [notes](01.%20Opposite%20Ends/0557.%20Reverse%20Words%20in%20a%20String%20III/0557.%20Reverse%20Words%20in%20a%20String%20III.md) |
| 12 | [360. Sort Transformed Array](https://leetcode.com/problems/sort-transformed-array/) 🔒 | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Opposite%20Ends/0360.%20Sort%20Transformed%20Array/0360.%20Sort%20Transformed%20Array.md) |
| 13 | [948. Bag of Tokens](https://leetcode.com/problems/bag-of-tokens/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](01.%20Opposite%20Ends/0948.%20Bag%20of%20Tokens/0948.%20Bag%20of%20Tokens.md) |
| 14 | [581. Shortest Unsorted Continuous Subarray](https://leetcode.com/problems/shortest-unsorted-continuous-subarray/) | Medium | 6+ months | 5.7 | Todo |  |  |  | [notes](01.%20Opposite%20Ends/0581.%20Shortest%20Unsorted%20Continuous%20Subarray/0581.%20Shortest%20Unsorted%20Continuous%20Subarray.md) |
| 15 | [917. Reverse Only Letters](https://leetcode.com/problems/reverse-only-letters/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](01.%20Opposite%20Ends/0917.%20Reverse%20Only%20Letters/0917.%20Reverse%20Only%20Letters.md) |

## 02. Same Direction (Read-Write)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [26. Remove Duplicates from Sorted Array](https://leetcode.com/problems/remove-duplicates-from-sorted-array/) | Easy | 3 months | 67.4 | ✅ Solved |  |  |  | [notes](02.%20Same%20Direction%20%28Read-Write%29/0026.%20Remove%20Duplicates%20from%20Sorted%20Array/0026.%20Remove%20Duplicates%20from%20Sorted%20Array.md) |
| 2 | [283. Move Zeroes](https://leetcode.com/problems/move-zeroes/) | Easy | 3 months | 59.5 | ✅ Solved |  |  |  | [notes](02.%20Same%20Direction%20%28Read-Write%29/0283.%20Move%20Zeroes/0283.%20Move%20Zeroes.md) |
| 3 | [80. Remove Duplicates from Sorted Array II](https://leetcode.com/problems/remove-duplicates-from-sorted-array-ii/) | Medium | 3 months | 47.7 | Todo |  |  |  | [notes](02.%20Same%20Direction%20%28Read-Write%29/0080.%20Remove%20Duplicates%20from%20Sorted%20Array%20II/0080.%20Remove%20Duplicates%20from%20Sorted%20Array%20II.md) |
| 4 | [27. Remove Element](https://leetcode.com/problems/remove-element/) | Easy | 3 months | 35.4 | ✅ Solved |  |  |  | [notes](02.%20Same%20Direction%20%28Read-Write%29/0027.%20Remove%20Element/0027.%20Remove%20Element.md) |
| 5 | [443. String Compression](https://leetcode.com/problems/string-compression/) | Medium | 6 months | 37.5 | Todo |  |  |  | [notes](02.%20Same%20Direction%20%28Read-Write%29/0443.%20String%20Compression/0443.%20String%20Compression.md) |
| 6 | [2149. Rearrange Array Elements by Sign](https://leetcode.com/problems/rearrange-array-elements-by-sign/) | Medium | 6 months | 25.1 | ✅ Solved |  |  |  | [notes](02.%20Same%20Direction%20%28Read-Write%29/2149.%20Rearrange%20Array%20Elements%20by%20Sign/2149.%20Rearrange%20Array%20Elements%20by%20Sign.md) |
| 7 | [277. Find the Celebrity](https://leetcode.com/problems/find-the-celebrity/) 🔒 | Medium | 6+ months | 37.4 | Todo |  |  |  | [notes](02.%20Same%20Direction%20%28Read-Write%29/0277.%20Find%20the%20Celebrity/0277.%20Find%20the%20Celebrity.md) |
| 8 | [161. One Edit Distance](https://leetcode.com/problems/one-edit-distance/) 🔒 | Medium | 6+ months | 36.1 | Todo |  |  |  | [notes](02.%20Same%20Direction%20%28Read-Write%29/0161.%20One%20Edit%20Distance/0161.%20One%20Edit%20Distance.md) |
| 9 | [844. Backspace String Compare](https://leetcode.com/problems/backspace-string-compare/) | Easy | 6+ months | 13.5 | ✅ Solved |  |  |  | [notes](02.%20Same%20Direction%20%28Read-Write%29/0844.%20Backspace%20String%20Compare/0844.%20Backspace%20String%20Compare.md) |
| 10 | [838. Push Dominoes](https://leetcode.com/problems/push-dominoes/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Same%20Direction%20%28Read-Write%29/0838.%20Push%20Dominoes/0838.%20Push%20Dominoes.md) |
| 11 | [845. Longest Mountain in Array](https://leetcode.com/problems/longest-mountain-in-array/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Same%20Direction%20%28Read-Write%29/0845.%20Longest%20Mountain%20in%20Array/0845.%20Longest%20Mountain%20in%20Array.md) |
| 12 | [2109. Adding Spaces to a String](https://leetcode.com/problems/adding-spaces-to-a-string/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](02.%20Same%20Direction%20%28Read-Write%29/2109.%20Adding%20Spaces%20to%20a%20String/2109.%20Adding%20Spaces%20to%20a%20String.md) |
| 13 | [2200. Find All K-Distant Indices in an Array](https://leetcode.com/problems/find-all-k-distant-indices-in-an-array/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](02.%20Same%20Direction%20%28Read-Write%29/2200.%20Find%20All%20K-Distant%20Indices%20in%20an%20Array/2200.%20Find%20All%20K-Distant%20Indices%20in%20an%20Array.md) |
| 14 | [2337. Move Pieces to Obtain a String](https://leetcode.com/problems/move-pieces-to-obtain-a-string/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](02.%20Same%20Direction%20%28Read-Write%29/2337.%20Move%20Pieces%20to%20Obtain%20a%20String/2337.%20Move%20Pieces%20to%20Obtain%20a%20String.md) |
| 15 | [2460. Apply Operations to an Array](https://leetcode.com/problems/apply-operations-to-an-array/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](02.%20Same%20Direction%20%28Read-Write%29/2460.%20Apply%20Operations%20to%20an%20Array/2460.%20Apply%20Operations%20to%20an%20Array.md) |
| 16 | [1826. Faulty Sensor](https://leetcode.com/problems/faulty-sensor/) 🔒 | Easy | 6+ months | 36.1 | Todo |  |  |  | [notes](02.%20Same%20Direction%20%28Read-Write%29/1826.%20Faulty%20Sensor/1826.%20Faulty%20Sensor.md) |
| 17 | [3940. Limit Occurrences in Sorted Array](https://leetcode.com/problems/limit-occurrences-in-sorted-array/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Same%20Direction%20%28Read-Write%29/3940.%20Limit%20Occurrences%20in%20Sorted%20Array/3940.%20Limit%20Occurrences%20in%20Sorted%20Array.md) |

## 03. Two Sum & K-Sum Variants

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [15. 3Sum](https://leetcode.com/problems/3sum/) | Medium | 3 months | 68.0 | ✅ Solved |  |  |  | [notes](03.%20Two%20Sum%20%26%20K-Sum%20Variants/0015.%203Sum/0015.%203Sum.md) |
| 2 | [16. 3Sum Closest](https://leetcode.com/problems/3sum-closest/) | Medium | 3 months | 42.1 | Todo |  |  |  | [notes](03.%20Two%20Sum%20%26%20K-Sum%20Variants/0016.%203Sum%20Closest/0016.%203Sum%20Closest.md) |
| 3 | [167. Two Sum II - Input Array Is Sorted](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted/) | Medium | 6 months | 41.4 | ✅ Solved |  |  |  | [notes](03.%20Two%20Sum%20%26%20K-Sum%20Variants/0167.%20Two%20Sum%20II%20-%20Input%20Array%20Is%20Sorted/0167.%20Two%20Sum%20II%20-%20Input%20Array%20Is%20Sorted.md) |
| 4 | [18. 4Sum](https://leetcode.com/problems/4sum/) | Medium | 6+ months | 43.6 | ✅ Solved |  |  |  | [notes](03.%20Two%20Sum%20%26%20K-Sum%20Variants/0018.%204Sum/0018.%204Sum.md) |
| 5 | [2824. Count Pairs Whose Sum is Less than Target](https://leetcode.com/problems/count-pairs-whose-sum-is-less-than-target/) | Easy | 6+ months | 37.4 | ✅ Solved |  |  |  | [notes](03.%20Two%20Sum%20%26%20K-Sum%20Variants/2824.%20Count%20Pairs%20Whose%20Sum%20is%20Less%20than%20Target/2824.%20Count%20Pairs%20Whose%20Sum%20is%20Less%20than%20Target.md) |
| 6 | [611. Valid Triangle Number](https://leetcode.com/problems/valid-triangle-number/) | Medium | 6+ months | 12.0 | Todo |  |  |  | [notes](03.%20Two%20Sum%20%26%20K-Sum%20Variants/0611.%20Valid%20Triangle%20Number/0611.%20Valid%20Triangle%20Number.md) |
| 7 | [1679. Max Number of K-Sum Pairs](https://leetcode.com/problems/max-number-of-k-sum-pairs/) | Medium | 6+ months | 11.8 | Todo |  |  |  | [notes](03.%20Two%20Sum%20%26%20K-Sum%20Variants/1679.%20Max%20Number%20of%20K-Sum%20Pairs/1679.%20Max%20Number%20of%20K-Sum%20Pairs.md) |
| 8 | [259. 3Sum Smaller](https://leetcode.com/problems/3sum-smaller/) 🔒 | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](03.%20Two%20Sum%20%26%20K-Sum%20Variants/0259.%203Sum%20Smaller/0259.%203Sum%20Smaller.md) |
| 9 | [923. 3Sum With Multiplicity](https://leetcode.com/problems/3sum-with-multiplicity/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](03.%20Two%20Sum%20%26%20K-Sum%20Variants/0923.%203Sum%20With%20Multiplicity/0923.%203Sum%20With%20Multiplicity.md) |
| 10 | [2563. Count the Number of Fair Pairs](https://leetcode.com/problems/count-the-number-of-fair-pairs/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](03.%20Two%20Sum%20%26%20K-Sum%20Variants/2563.%20Count%20the%20Number%20of%20Fair%20Pairs/2563.%20Count%20the%20Number%20of%20Fair%20Pairs.md) |

## 04. Merge Two Sorted Sequences

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [88. Merge Sorted Array](https://leetcode.com/problems/merge-sorted-array/) | Easy | 3 months | 83.8 | ✅ Solved |  |  |  | [notes](04.%20Merge%20Two%20Sorted%20Sequences/0088.%20Merge%20Sorted%20Array/0088.%20Merge%20Sorted%20Array.md) |
| 2 | [1768. Merge Strings Alternately](https://leetcode.com/problems/merge-strings-alternately/) | Easy | 6 months | 34.3 | ✅ Solved |  |  |  | [notes](04.%20Merge%20Two%20Sorted%20Sequences/1768.%20Merge%20Strings%20Alternately/1768.%20Merge%20Strings%20Alternately.md) |
| 3 | [1868. Product of Two Run-Length Encoded Arrays](https://leetcode.com/problems/product-of-two-run-length-encoded-arrays/) 🔒 | Medium | 6+ months | 47.0 | Todo |  |  |  | [notes](04.%20Merge%20Two%20Sorted%20Sequences/1868.%20Product%20of%20Two%20Run-Length%20Encoded%20Arrays/1868.%20Product%20of%20Two%20Run-Length%20Encoded%20Arrays.md) |
| 4 | [2570. Merge Two 2D Arrays by Summing Values](https://leetcode.com/problems/merge-two-2d-arrays-by-summing-values/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](04.%20Merge%20Two%20Sorted%20Sequences/2570.%20Merge%20Two%202D%20Arrays%20by%20Summing%20Values/2570.%20Merge%20Two%202D%20Arrays%20by%20Summing%20Values.md) |
| 5 | [1213. Intersection of Three Sorted Arrays](https://leetcode.com/problems/intersection-of-three-sorted-arrays/) 🔒 | Easy | 6+ months | 37.0 | Todo |  |  |  | [notes](04.%20Merge%20Two%20Sorted%20Sequences/1213.%20Intersection%20of%20Three%20Sorted%20Arrays/1213.%20Intersection%20of%20Three%20Sorted%20Arrays.md) |

## 05. Partitioning (Dutch Flag)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [75. Sort Colors](https://leetcode.com/problems/sort-colors/) | Medium | 6 months | 56.8 | ✅ Solved |  |  |  | [notes](05.%20Partitioning%20%28Dutch%20Flag%29/0075.%20Sort%20Colors/0075.%20Sort%20Colors.md) |
| 2 | [905. Sort Array By Parity](https://leetcode.com/problems/sort-array-by-parity/) | Easy | 6+ months | 33.9 | ✅ Solved |  |  |  | [notes](05.%20Partitioning%20%28Dutch%20Flag%29/0905.%20Sort%20Array%20By%20Parity/0905.%20Sort%20Array%20By%20Parity.md) |
| 3 | [2161. Partition Array According to Given Pivot](https://leetcode.com/problems/partition-array-according-to-given-pivot/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Partitioning%20%28Dutch%20Flag%29/2161.%20Partition%20Array%20According%20to%20Given%20Pivot/2161.%20Partition%20Array%20According%20to%20Given%20Pivot.md) |

## 06. Subsequence Matching

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [408. Valid Word Abbreviation](https://leetcode.com/problems/valid-word-abbreviation/) 🔒 | Easy | 30 days | 97.3 | Todo |  |  |  | [notes](06.%20Subsequence%20Matching/0408.%20Valid%20Word%20Abbreviation/0408.%20Valid%20Word%20Abbreviation.md) |
| 2 | [392. Is Subsequence](https://leetcode.com/problems/is-subsequence/) | Easy | 6 months | 31.7 | ✅ Solved |  |  |  | [notes](06.%20Subsequence%20Matching/0392.%20Is%20Subsequence/0392.%20Is%20Subsequence.md) |
| 3 | [792. Number of Matching Subsequences](https://leetcode.com/problems/number-of-matching-subsequences/) | Medium | 6+ months | 9.0 | Todo |  |  |  | [notes](06.%20Subsequence%20Matching/0792.%20Number%20of%20Matching%20Subsequences/0792.%20Number%20of%20Matching%20Subsequences.md) |
| 4 | [925. Long Pressed Name](https://leetcode.com/problems/long-pressed-name/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](06.%20Subsequence%20Matching/0925.%20Long%20Pressed%20Name/0925.%20Long%20Pressed%20Name.md) |
