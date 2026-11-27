# 03. Two Pointers

[Back to Google](../README.md) · [Back to DSA Notes](../../../README.md)

75 Google problems: 28 Easy, 44 Medium, 3 Hard, in 6 sub-patterns.

## Sub-patterns

| # | Sub-pattern | Questions | Easy | Medium | Hard | Last 3 Months | Solved | Most Asked |
|:---:|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---|
| 01 | [Opposite Ends](#01-opposite-ends) | 24 | 10 | 12 | 2 | 5 | 13 | 42. Trapping Rain Water, 11. Container With Most Water, 345. Reverse Vowels of a String |
| 02 | [Same Direction (Read-Write)](#02-same-direction-read-write) | 21 | 8 | 13 | 0 | 5 | 10 | 26. Remove Duplicates from Sorted Array, 283. Move Zeroes, 27. Remove Element |
| 03 | [Two Sum & K-Sum Variants](#03-two-sum--k-sum-variants) | 10 | 1 | 9 | 0 | 4 | 4 | 15. 3Sum, 18. 4Sum, 16. 3Sum Closest |
| 04 | [Merge Two Sorted Sequences](#04-merge-two-sorted-sequences) | 5 | 4 | 0 | 1 | 2 | 4 | 88. Merge Sorted Array, 1768. Merge Strings Alternately, 2570. Merge Two 2D Arrays by Summing Values |
| 05 | [Partitioning (Dutch Flag)](#05-partitioning-dutch-flag) | 4 | 2 | 2 | 0 | 1 | 3 | 75. Sort Colors, 905. Sort Array By Parity, 2161. Partition Array According to Given Pivot |
| 06 | [Subsequence Matching](#06-subsequence-matching) | 11 | 3 | 8 | 0 | 1 | 4 | 792. Number of Matching Subsequences, 524. Longest Word in Dictionary through Deleting, 408. Valid Word Abbreviation |

**Columns**

- **Last Asked**: most recent LeetCode window that lists the problem for Google (30 days, 3 months, 6 months, 6+ months).
- **Frequency**: LeetCode frequency score (0-100) in the Google "All" list.
- **Status**: your LeetCode status on the day this file was generated. 🔒 after a title means LeetCode Premium.
- **Logic / Key Idea, Time, Space**: fill these in as you solve. A rebuild keeps what you typed.
- **Notes**: link to the problem's notes file.

Inside each sub-pattern, rows are sorted by most recent window, then by frequency (highest first).

## 01. Opposite Ends

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [42. Trapping Rain Water](https://leetcode.com/problems/trapping-rain-water/) | Hard | 30 days | 75.9 | ✅ Solved |  |  |  | [notes](01.%20Opposite%20Ends/0042.%20Trapping%20Rain%20Water/0042.%20Trapping%20Rain%20Water.md) |
| 2 | [11. Container With Most Water](https://leetcode.com/problems/container-with-most-water/) | Medium | 30 days | 64.2 | ✅ Solved |  |  |  | [notes](01.%20Opposite%20Ends/0011.%20Container%20With%20Most%20Water/0011.%20Container%20With%20Most%20Water.md) |
| 3 | [344. Reverse String](https://leetcode.com/problems/reverse-string/) | Easy | 3 months | 43.4 | ✅ Solved |  |  |  | [notes](01.%20Opposite%20Ends/0344.%20Reverse%20String/0344.%20Reverse%20String.md) |
| 4 | [977. Squares of a Sorted Array](https://leetcode.com/problems/squares-of-a-sorted-array/) | Easy | 3 months | 40.8 | ✅ Solved |  |  |  | [notes](01.%20Opposite%20Ends/0977.%20Squares%20of%20a%20Sorted%20Array/0977.%20Squares%20of%20a%20Sorted%20Array.md) |
| 5 | [1793. Maximum Score of a Good Subarray](https://leetcode.com/problems/maximum-score-of-a-good-subarray/) | Hard | 3 months | 29.9 | Todo |  |  |  | [notes](01.%20Opposite%20Ends/1793.%20Maximum%20Score%20of%20a%20Good%20Subarray/1793.%20Maximum%20Score%20of%20a%20Good%20Subarray.md) |
| 6 | [345. Reverse Vowels of a String](https://leetcode.com/problems/reverse-vowels-of-a-string/) | Easy | 6 months | 46.6 | ✅ Solved |  |  |  | [notes](01.%20Opposite%20Ends/0345.%20Reverse%20Vowels%20of%20a%20String/0345.%20Reverse%20Vowels%20of%20a%20String.md) |
| 7 | [541. Reverse String II](https://leetcode.com/problems/reverse-string-ii/) | Easy | 6 months | 37.1 | ✅ Solved |  |  |  | [notes](01.%20Opposite%20Ends/0541.%20Reverse%20String%20II/0541.%20Reverse%20String%20II.md) |
| 8 | [633. Sum of Square Numbers](https://leetcode.com/problems/sum-of-square-numbers/) | Medium | 6 months | 24.7 | Todo |  |  |  | [notes](01.%20Opposite%20Ends/0633.%20Sum%20of%20Square%20Numbers/0633.%20Sum%20of%20Square%20Numbers.md) |
| 9 | [881. Boats to Save People](https://leetcode.com/problems/boats-to-save-people/) | Medium | 6 months | 23.5 | ✅ Solved |  |  |  | [notes](01.%20Opposite%20Ends/0881.%20Boats%20to%20Save%20People/0881.%20Boats%20to%20Save%20People.md) |
| 10 | [581. Shortest Unsorted Continuous Subarray](https://leetcode.com/problems/shortest-unsorted-continuous-subarray/) | Medium | 6+ months | 40.3 | Todo |  |  |  | [notes](01.%20Opposite%20Ends/0581.%20Shortest%20Unsorted%20Continuous%20Subarray/0581.%20Shortest%20Unsorted%20Continuous%20Subarray.md) |
| 11 | [948. Bag of Tokens](https://leetcode.com/problems/bag-of-tokens/) | Medium | 6+ months | 34.1 | ✅ Solved |  |  |  | [notes](01.%20Opposite%20Ends/0948.%20Bag%20of%20Tokens/0948.%20Bag%20of%20Tokens.md) |
| 12 | [1498. Number of Subsequences That Satisfy the Given Sum Condition](https://leetcode.com/problems/number-of-subsequences-that-satisfy-the-given-sum-condition/) | Medium | 6+ months | 33.8 | Todo |  |  |  | [notes](01.%20Opposite%20Ends/1498.%20Number%20of%20Subsequences%20That%20Satisfy%20the%20Given%20Sum%20Condition/1498.%20Number%20of%20Subsequences%20That%20Satisfy%20the%20Given%20Sum%20Condition.md) |
| 13 | [360. Sort Transformed Array](https://leetcode.com/problems/sort-transformed-array/) 🔒 | Medium | 6+ months | 31.7 | Todo |  |  |  | [notes](01.%20Opposite%20Ends/0360.%20Sort%20Transformed%20Array/0360.%20Sort%20Transformed%20Array.md) |
| 14 | [942. DI String Match](https://leetcode.com/problems/di-string-match/) | Easy | 6+ months | 30.9 | ✅ Solved |  |  |  | [notes](01.%20Opposite%20Ends/0942.%20DI%20String%20Match/0942.%20DI%20String%20Match.md) |
| 15 | [917. Reverse Only Letters](https://leetcode.com/problems/reverse-only-letters/) | Easy | 6+ months | 30.8 | ✅ Solved |  |  |  | [notes](01.%20Opposite%20Ends/0917.%20Reverse%20Only%20Letters/0917.%20Reverse%20Only%20Letters.md) |
| 16 | [557. Reverse Words in a String III](https://leetcode.com/problems/reverse-words-in-a-string-iii/) | Easy | 6+ months | 13.1 | ✅ Solved |  |  |  | [notes](01.%20Opposite%20Ends/0557.%20Reverse%20Words%20in%20a%20String%20III/0557.%20Reverse%20Words%20in%20a%20String%20III.md) |
| 17 | [2000. Reverse Prefix of Word](https://leetcode.com/problems/reverse-prefix-of-word/) | Easy | 6+ months | 10.2 | ✅ Solved |  |  |  | [notes](01.%20Opposite%20Ends/2000.%20Reverse%20Prefix%20of%20Word/2000.%20Reverse%20Prefix%20of%20Word.md) |
| 18 | [1574. Shortest Subarray to be Removed to Make Array Sorted](https://leetcode.com/problems/shortest-subarray-to-be-removed-to-make-array-sorted/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Opposite%20Ends/1574.%20Shortest%20Subarray%20to%20be%20Removed%20to%20Make%20Array%20Sorted/1574.%20Shortest%20Subarray%20to%20be%20Removed%20to%20Make%20Array%20Sorted.md) |
| 19 | [2465. Number of Distinct Averages](https://leetcode.com/problems/number-of-distinct-averages/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](01.%20Opposite%20Ends/2465.%20Number%20of%20Distinct%20Averages/2465.%20Number%20of%20Distinct%20Averages.md) |
| 20 | [1813. Sentence Similarity III](https://leetcode.com/problems/sentence-similarity-iii/) | Medium | 6+ months | 31.0 | Todo |  |  |  | [notes](01.%20Opposite%20Ends/1813.%20Sentence%20Similarity%20III/1813.%20Sentence%20Similarity%20III.md) |
| 21 | [1237. Find Positive Integer Solution for a Given Equation](https://leetcode.com/problems/find-positive-integer-solution-for-a-given-equation/) | Medium | 6+ months | 28.8 | Todo |  |  |  | [notes](01.%20Opposite%20Ends/1237.%20Find%20Positive%20Integer%20Solution%20for%20a%20Given%20Equation/1237.%20Find%20Positive%20Integer%20Solution%20for%20a%20Given%20Equation.md) |
| 22 | [1471. The k Strongest Values in an Array](https://leetcode.com/problems/the-k-strongest-values-in-an-array/) | Medium | 6+ months | 28.8 | Todo |  |  |  | [notes](01.%20Opposite%20Ends/1471.%20The%20k%20Strongest%20Values%20in%20an%20Array/1471.%20The%20k%20Strongest%20Values%20in%20an%20Array.md) |
| 23 | [2105. Watering Plants II](https://leetcode.com/problems/watering-plants-ii/) | Medium | 6+ months | 28.8 | Todo |  |  |  | [notes](01.%20Opposite%20Ends/2105.%20Watering%20Plants%20II/2105.%20Watering%20Plants%20II.md) |
| 24 | [3794. Reverse String Prefix](https://leetcode.com/problems/reverse-string-prefix/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Opposite%20Ends/3794.%20Reverse%20String%20Prefix/3794.%20Reverse%20String%20Prefix.md) |

## 02. Same Direction (Read-Write)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [283. Move Zeroes](https://leetcode.com/problems/move-zeroes/) | Easy | 30 days | 54.9 | ✅ Solved |  |  |  | [notes](02.%20Same%20Direction%20%28Read-Write%29/0283.%20Move%20Zeroes/0283.%20Move%20Zeroes.md) |
| 2 | [26. Remove Duplicates from Sorted Array](https://leetcode.com/problems/remove-duplicates-from-sorted-array/) | Easy | 3 months | 61.3 | ✅ Solved |  |  |  | [notes](02.%20Same%20Direction%20%28Read-Write%29/0026.%20Remove%20Duplicates%20from%20Sorted%20Array/0026.%20Remove%20Duplicates%20from%20Sorted%20Array.md) |
| 3 | [27. Remove Element](https://leetcode.com/problems/remove-element/) | Easy | 3 months | 50.5 | ✅ Solved |  |  |  | [notes](02.%20Same%20Direction%20%28Read-Write%29/0027.%20Remove%20Element/0027.%20Remove%20Element.md) |
| 4 | [443. String Compression](https://leetcode.com/problems/string-compression/) | Medium | 3 months | 43.8 | Todo |  |  |  | [notes](02.%20Same%20Direction%20%28Read-Write%29/0443.%20String%20Compression/0443.%20String%20Compression.md) |
| 5 | [2337. Move Pieces to Obtain a String](https://leetcode.com/problems/move-pieces-to-obtain-a-string/) | Medium | 3 months | 42.8 | ✅ Solved |  |  |  | [notes](02.%20Same%20Direction%20%28Read-Write%29/2337.%20Move%20Pieces%20to%20Obtain%20a%20String/2337.%20Move%20Pieces%20to%20Obtain%20a%20String.md) |
| 6 | [844. Backspace String Compare](https://leetcode.com/problems/backspace-string-compare/) | Easy | 6 months | 41.2 | ✅ Solved |  |  |  | [notes](02.%20Same%20Direction%20%28Read-Write%29/0844.%20Backspace%20String%20Compare/0844.%20Backspace%20String%20Compare.md) |
| 7 | [1089. Duplicate Zeros](https://leetcode.com/problems/duplicate-zeros/) | Easy | 6 months | 34.1 | Todo |  |  |  | [notes](02.%20Same%20Direction%20%28Read-Write%29/1089.%20Duplicate%20Zeros/1089.%20Duplicate%20Zeros.md) |
| 8 | [80. Remove Duplicates from Sorted Array II](https://leetcode.com/problems/remove-duplicates-from-sorted-array-ii/) | Medium | 6 months | 33.2 | Todo |  |  |  | [notes](02.%20Same%20Direction%20%28Read-Write%29/0080.%20Remove%20Duplicates%20from%20Sorted%20Array%20II/0080.%20Remove%20Duplicates%20from%20Sorted%20Array%20II.md) |
| 9 | [2149. Rearrange Array Elements by Sign](https://leetcode.com/problems/rearrange-array-elements-by-sign/) | Medium | 6 months | 28.2 | ✅ Solved |  |  |  | [notes](02.%20Same%20Direction%20%28Read-Write%29/2149.%20Rearrange%20Array%20Elements%20by%20Sign/2149.%20Rearrange%20Array%20Elements%20by%20Sign.md) |
| 10 | [777. Swap Adjacent in LR String](https://leetcode.com/problems/swap-adjacent-in-lr-string/) | Medium | 6+ months | 45.7 | Todo |  |  |  | [notes](02.%20Same%20Direction%20%28Read-Write%29/0777.%20Swap%20Adjacent%20in%20LR%20String/0777.%20Swap%20Adjacent%20in%20LR%20String.md) |
| 11 | [845. Longest Mountain in Array](https://leetcode.com/problems/longest-mountain-in-array/) | Medium | 6+ months | 33.8 | Todo |  |  |  | [notes](02.%20Same%20Direction%20%28Read-Write%29/0845.%20Longest%20Mountain%20in%20Array/0845.%20Longest%20Mountain%20in%20Array.md) |
| 12 | [2200. Find All K-Distant Indices in an Array](https://leetcode.com/problems/find-all-k-distant-indices-in-an-array/) | Easy | 6+ months | 32.7 | ✅ Solved |  |  |  | [notes](02.%20Same%20Direction%20%28Read-Write%29/2200.%20Find%20All%20K-Distant%20Indices%20in%20an%20Array/2200.%20Find%20All%20K-Distant%20Indices%20in%20an%20Array.md) |
| 13 | [809. Expressive Words](https://leetcode.com/problems/expressive-words/) | Medium | 6+ months | 31.9 | Todo |  |  |  | [notes](02.%20Same%20Direction%20%28Read-Write%29/0809.%20Expressive%20Words/0809.%20Expressive%20Words.md) |
| 14 | [838. Push Dominoes](https://leetcode.com/problems/push-dominoes/) | Medium | 6+ months | 30.8 | Todo |  |  |  | [notes](02.%20Same%20Direction%20%28Read-Write%29/0838.%20Push%20Dominoes/0838.%20Push%20Dominoes.md) |
| 15 | [481. Magical String](https://leetcode.com/problems/magical-string/) | Medium | 6+ months | 29.9 | Todo |  |  |  | [notes](02.%20Same%20Direction%20%28Read-Write%29/0481.%20Magical%20String/0481.%20Magical%20String.md) |
| 16 | [821. Shortest Distance to a Character](https://leetcode.com/problems/shortest-distance-to-a-character/) | Easy | 6+ months | 9.5 | ✅ Solved |  |  |  | [notes](02.%20Same%20Direction%20%28Read-Write%29/0821.%20Shortest%20Distance%20to%20a%20Character/0821.%20Shortest%20Distance%20to%20a%20Character.md) |
| 17 | [277. Find the Celebrity](https://leetcode.com/problems/find-the-celebrity/) 🔒 | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Same%20Direction%20%28Read-Write%29/0277.%20Find%20the%20Celebrity/0277.%20Find%20the%20Celebrity.md) |
| 18 | [795. Number of Subarrays with Bounded Maximum](https://leetcode.com/problems/number-of-subarrays-with-bounded-maximum/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Same%20Direction%20%28Read-Write%29/0795.%20Number%20of%20Subarrays%20with%20Bounded%20Maximum/0795.%20Number%20of%20Subarrays%20with%20Bounded%20Maximum.md) |
| 19 | [1855. Maximum Distance Between a Pair of Values](https://leetcode.com/problems/maximum-distance-between-a-pair-of-values/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Same%20Direction%20%28Read-Write%29/1855.%20Maximum%20Distance%20Between%20a%20Pair%20of%20Values/1855.%20Maximum%20Distance%20Between%20a%20Pair%20of%20Values.md) |
| 20 | [2109. Adding Spaces to a String](https://leetcode.com/problems/adding-spaces-to-a-string/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](02.%20Same%20Direction%20%28Read-Write%29/2109.%20Adding%20Spaces%20to%20a%20String/2109.%20Adding%20Spaces%20to%20a%20String.md) |
| 21 | [2460. Apply Operations to an Array](https://leetcode.com/problems/apply-operations-to-an-array/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](02.%20Same%20Direction%20%28Read-Write%29/2460.%20Apply%20Operations%20to%20an%20Array/2460.%20Apply%20Operations%20to%20an%20Array.md) |

## 03. Two Sum & K-Sum Variants

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [15. 3Sum](https://leetcode.com/problems/3sum/) | Medium | 30 days | 73.5 | ✅ Solved |  |  |  | [notes](03.%20Two%20Sum%20%26%20K-Sum%20Variants/0015.%203Sum/0015.%203Sum.md) |
| 2 | [18. 4Sum](https://leetcode.com/problems/4sum/) | Medium | 3 months | 53.1 | ✅ Solved |  |  |  | [notes](03.%20Two%20Sum%20%26%20K-Sum%20Variants/0018.%204Sum/0018.%204Sum.md) |
| 3 | [16. 3Sum Closest](https://leetcode.com/problems/3sum-closest/) | Medium | 3 months | 47.8 | Todo |  |  |  | [notes](03.%20Two%20Sum%20%26%20K-Sum%20Variants/0016.%203Sum%20Closest/0016.%203Sum%20Closest.md) |
| 4 | [167. Two Sum II - Input Array Is Sorted](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted/) | Medium | 3 months | 44.5 | ✅ Solved |  |  |  | [notes](03.%20Two%20Sum%20%26%20K-Sum%20Variants/0167.%20Two%20Sum%20II%20-%20Input%20Array%20Is%20Sorted/0167.%20Two%20Sum%20II%20-%20Input%20Array%20Is%20Sorted.md) |
| 5 | [1679. Max Number of K-Sum Pairs](https://leetcode.com/problems/max-number-of-k-sum-pairs/) | Medium | 6 months | 16.2 | Todo |  |  |  | [notes](03.%20Two%20Sum%20%26%20K-Sum%20Variants/1679.%20Max%20Number%20of%20K-Sum%20Pairs/1679.%20Max%20Number%20of%20K-Sum%20Pairs.md) |
| 6 | [259. 3Sum Smaller](https://leetcode.com/problems/3sum-smaller/) 🔒 | Medium | 6+ months | 29.5 | Todo |  |  |  | [notes](03.%20Two%20Sum%20%26%20K-Sum%20Variants/0259.%203Sum%20Smaller/0259.%203Sum%20Smaller.md) |
| 7 | [611. Valid Triangle Number](https://leetcode.com/problems/valid-triangle-number/) | Medium | 6+ months | 9.5 | Todo |  |  |  | [notes](03.%20Two%20Sum%20%26%20K-Sum%20Variants/0611.%20Valid%20Triangle%20Number/0611.%20Valid%20Triangle%20Number.md) |
| 8 | [2563. Count the Number of Fair Pairs](https://leetcode.com/problems/count-the-number-of-fair-pairs/) | Medium | 6+ months | 7.2 | Todo |  |  |  | [notes](03.%20Two%20Sum%20%26%20K-Sum%20Variants/2563.%20Count%20the%20Number%20of%20Fair%20Pairs/2563.%20Count%20the%20Number%20of%20Fair%20Pairs.md) |
| 9 | [923. 3Sum With Multiplicity](https://leetcode.com/problems/3sum-with-multiplicity/) | Medium | 6+ months | 5.1 | Todo |  |  |  | [notes](03.%20Two%20Sum%20%26%20K-Sum%20Variants/0923.%203Sum%20With%20Multiplicity/0923.%203Sum%20With%20Multiplicity.md) |
| 10 | [2824. Count Pairs Whose Sum is Less than Target](https://leetcode.com/problems/count-pairs-whose-sum-is-less-than-target/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](03.%20Two%20Sum%20%26%20K-Sum%20Variants/2824.%20Count%20Pairs%20Whose%20Sum%20is%20Less%20than%20Target/2824.%20Count%20Pairs%20Whose%20Sum%20is%20Less%20than%20Target.md) |

## 04. Merge Two Sorted Sequences

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [88. Merge Sorted Array](https://leetcode.com/problems/merge-sorted-array/) | Easy | 30 days | 67.0 | ✅ Solved |  |  |  | [notes](04.%20Merge%20Two%20Sorted%20Sequences/0088.%20Merge%20Sorted%20Array/0088.%20Merge%20Sorted%20Array.md) |
| 2 | [1768. Merge Strings Alternately](https://leetcode.com/problems/merge-strings-alternately/) | Easy | 3 months | 51.2 | ✅ Solved |  |  |  | [notes](04.%20Merge%20Two%20Sorted%20Sequences/1768.%20Merge%20Strings%20Alternately/1768.%20Merge%20Strings%20Alternately.md) |
| 3 | [1537. Get the Maximum Score](https://leetcode.com/problems/get-the-maximum-score/) | Hard | 6 months | 15.2 | Todo |  |  |  | [notes](04.%20Merge%20Two%20Sorted%20Sequences/1537.%20Get%20the%20Maximum%20Score/1537.%20Get%20the%20Maximum%20Score.md) |
| 4 | [2570. Merge Two 2D Arrays by Summing Values](https://leetcode.com/problems/merge-two-2d-arrays-by-summing-values/) | Easy | 6+ months | 33.0 | ✅ Solved |  |  |  | [notes](04.%20Merge%20Two%20Sorted%20Sequences/2570.%20Merge%20Two%202D%20Arrays%20by%20Summing%20Values/2570.%20Merge%20Two%202D%20Arrays%20by%20Summing%20Values.md) |
| 5 | [2540. Minimum Common Value](https://leetcode.com/problems/minimum-common-value/) | Easy | 6+ months | 7.4 | ✅ Solved |  |  |  | [notes](04.%20Merge%20Two%20Sorted%20Sequences/2540.%20Minimum%20Common%20Value/2540.%20Minimum%20Common%20Value.md) |

## 05. Partitioning (Dutch Flag)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [75. Sort Colors](https://leetcode.com/problems/sort-colors/) | Medium | 3 months | 50.6 | ✅ Solved |  |  |  | [notes](05.%20Partitioning%20%28Dutch%20Flag%29/0075.%20Sort%20Colors/0075.%20Sort%20Colors.md) |
| 2 | [905. Sort Array By Parity](https://leetcode.com/problems/sort-array-by-parity/) | Easy | 6 months | 15.8 | ✅ Solved |  |  |  | [notes](05.%20Partitioning%20%28Dutch%20Flag%29/0905.%20Sort%20Array%20By%20Parity/0905.%20Sort%20Array%20By%20Parity.md) |
| 3 | [2161. Partition Array According to Given Pivot](https://leetcode.com/problems/partition-array-according-to-given-pivot/) | Medium | 6 months | 12.6 | Todo |  |  |  | [notes](05.%20Partitioning%20%28Dutch%20Flag%29/2161.%20Partition%20Array%20According%20to%20Given%20Pivot/2161.%20Partition%20Array%20According%20to%20Given%20Pivot.md) |
| 4 | [922. Sort Array By Parity II](https://leetcode.com/problems/sort-array-by-parity-ii/) | Easy | 6+ months | 9.2 | ✅ Solved |  |  |  | [notes](05.%20Partitioning%20%28Dutch%20Flag%29/0922.%20Sort%20Array%20By%20Parity%20II/0922.%20Sort%20Array%20By%20Parity%20II.md) |

## 06. Subsequence Matching

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [392. Is Subsequence](https://leetcode.com/problems/is-subsequence/) | Easy | 3 months | 29.8 | ✅ Solved |  |  |  | [notes](06.%20Subsequence%20Matching/0392.%20Is%20Subsequence/0392.%20Is%20Subsequence.md) |
| 2 | [925. Long Pressed Name](https://leetcode.com/problems/long-pressed-name/) | Easy | 6 months | 6.2 | ✅ Solved |  |  |  | [notes](06.%20Subsequence%20Matching/0925.%20Long%20Pressed%20Name/0925.%20Long%20Pressed%20Name.md) |
| 3 | [792. Number of Matching Subsequences](https://leetcode.com/problems/number-of-matching-subsequences/) | Medium | 6+ months | 40.2 | Todo |  |  |  | [notes](06.%20Subsequence%20Matching/0792.%20Number%20of%20Matching%20Subsequences/0792.%20Number%20of%20Matching%20Subsequences.md) |
| 4 | [524. Longest Word in Dictionary through Deleting](https://leetcode.com/problems/longest-word-in-dictionary-through-deleting/) | Medium | 6+ months | 31.2 | Todo |  |  |  | [notes](06.%20Subsequence%20Matching/0524.%20Longest%20Word%20in%20Dictionary%20through%20Deleting/0524.%20Longest%20Word%20in%20Dictionary%20through%20Deleting.md) |
| 5 | [408. Valid Word Abbreviation](https://leetcode.com/problems/valid-word-abbreviation/) 🔒 | Easy | 6+ months | 30.2 | Todo |  |  |  | [notes](06.%20Subsequence%20Matching/0408.%20Valid%20Word%20Abbreviation/0408.%20Valid%20Word%20Abbreviation.md) |
| 6 | [522. Longest Uncommon Subsequence II](https://leetcode.com/problems/longest-uncommon-subsequence-ii/) | Medium | 6+ months | 29.6 | Todo |  |  |  | [notes](06.%20Subsequence%20Matching/0522.%20Longest%20Uncommon%20Subsequence%20II/0522.%20Longest%20Uncommon%20Subsequence%20II.md) |
| 7 | [2486. Append Characters to String to Make Subsequence](https://leetcode.com/problems/append-characters-to-string-to-make-subsequence/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](06.%20Subsequence%20Matching/2486.%20Append%20Characters%20to%20String%20to%20Make%20Subsequence/2486.%20Append%20Characters%20to%20String%20to%20Make%20Subsequence.md) |
| 8 | [3983. Subsequence After One Replacement](https://leetcode.com/problems/subsequence-after-one-replacement/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20Subsequence%20Matching/3983.%20Subsequence%20After%20One%20Replacement/3983.%20Subsequence%20After%20One%20Replacement.md) |
| 9 | [1023. Camelcase Matching](https://leetcode.com/problems/camelcase-matching/) | Medium | 6+ months | 28.8 | Todo |  |  |  | [notes](06.%20Subsequence%20Matching/1023.%20Camelcase%20Matching/1023.%20Camelcase%20Matching.md) |
| 10 | [1055. Shortest Way to Form String](https://leetcode.com/problems/shortest-way-to-form-string/) 🔒 | Medium | 6+ months | 28.8 | Todo |  |  |  | [notes](06.%20Subsequence%20Matching/1055.%20Shortest%20Way%20to%20Form%20String/1055.%20Shortest%20Way%20to%20Form%20String.md) |
| 11 | [2825. Make String a Subsequence Using Cyclic Increments](https://leetcode.com/problems/make-string-a-subsequence-using-cyclic-increments/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](06.%20Subsequence%20Matching/2825.%20Make%20String%20a%20Subsequence%20Using%20Cyclic%20Increments/2825.%20Make%20String%20a%20Subsequence%20Using%20Cyclic%20Increments.md) |
