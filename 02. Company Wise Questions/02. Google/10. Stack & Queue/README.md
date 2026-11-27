# 10. Stack & Queue

[Back to Google](../README.md) · [Back to DSA Notes](../../../README.md)

89 Google problems: 14 Easy, 49 Medium, 26 Hard, in 7 sub-patterns.

## Sub-patterns

| # | Sub-pattern | Questions | Easy | Medium | Hard | Last 3 Months | Solved | Most Asked |
|:---:|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---|
| 01 | [Stack Basics](#01-stack-basics) | 9 | 5 | 4 | 0 | 2 | 3 | 1544. Make The String Great, 1047. Remove All Adjacent Duplicates In String, 1910. Remove All Occurrences of a Substring |
| 02 | [Parentheses & Bracket Matching](#02-parentheses--bracket-matching) | 10 | 3 | 6 | 1 | 7 | 4 | 20. Valid Parentheses, 32. Longest Valid Parentheses, 1021. Remove Outermost Parentheses |
| 03 | [Expression Evaluation & Calculator](#03-expression-evaluation--calculator) | 11 | 0 | 3 | 8 | 6 | 1 | 394. Decode String, 224. Basic Calculator, 150. Evaluate Reverse Polish Notation |
| 04 | [Monotonic Stack](#04-monotonic-stack) | 33 | 2 | 22 | 9 | 7 | 11 | 1944. Number of Visible People in a Queue, 739. Daily Temperatures, 84. Largest Rectangle in Histogram |
| 05 | [Monotonic Deque](#05-monotonic-deque) | 10 | 0 | 5 | 5 | 2 | 1 | 239. Sliding Window Maximum, 1438. Longest Continuous Subarray With Absolute Diff Less Than or Equal to Limit, 2762. Continuous Subarrays |
| 06 | [Queue Basics](#06-queue-basics) | 7 | 4 | 2 | 1 | 2 | 3 | 232. Implement Queue using Stacks, 225. Implement Stack using Queues, 2534. Time Taken to Cross the Door |
| 07 | [Stack Simulation (Asteroid, Path)](#07-stack-simulation-asteroid-path) | 9 | 0 | 7 | 2 | 0 | 1 | 388. Longest Absolute File Path, 1441. Build an Array With Stack Operations, 71. Simplify Path |

**Columns**

- **Last Asked**: most recent LeetCode window that lists the problem for Google (30 days, 3 months, 6 months, 6+ months).
- **Frequency**: LeetCode frequency score (0-100) in the Google "All" list.
- **Status**: your LeetCode status on the day this file was generated. 🔒 after a title means LeetCode Premium.
- **Logic / Key Idea, Time, Space**: fill these in as you solve. A rebuild keeps what you typed.
- **Notes**: link to the problem's notes file.

Inside each sub-pattern, rows are sorted by most recent window, then by frequency (highest first).

## 01. Stack Basics

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [1047. Remove All Adjacent Duplicates In String](https://leetcode.com/problems/remove-all-adjacent-duplicates-in-string/) | Easy | 3 months | 29.7 | Todo |  |  |  | [notes](01.%20Stack%20Basics/1047.%20Remove%20All%20Adjacent%20Duplicates%20In%20String/1047.%20Remove%20All%20Adjacent%20Duplicates%20In%20String.md) |
| 2 | [682. Baseball Game](https://leetcode.com/problems/baseball-game/) | Easy | 3 months | 10.8 | ✅ Solved |  |  |  | [notes](01.%20Stack%20Basics/0682.%20Baseball%20Game/0682.%20Baseball%20Game.md) |
| 3 | [1544. Make The String Great](https://leetcode.com/problems/make-the-string-great/) | Easy | 6 months | 35.5 | ✅ Solved |  |  |  | [notes](01.%20Stack%20Basics/1544.%20Make%20The%20String%20Great/1544.%20Make%20The%20String%20Great.md) |
| 4 | [1910. Remove All Occurrences of a Substring](https://leetcode.com/problems/remove-all-occurrences-of-a-substring/) | Medium | 6 months | 14.9 | Todo |  |  |  | [notes](01.%20Stack%20Basics/1910.%20Remove%20All%20Occurrences%20of%20a%20Substring/1910.%20Remove%20All%20Occurrences%20of%20a%20Substring.md) |
| 5 | [2390. Removing Stars From a String](https://leetcode.com/problems/removing-stars-from-a-string/) | Medium | 6 months | 8.4 | Todo |  |  |  | [notes](01.%20Stack%20Basics/2390.%20Removing%20Stars%20From%20a%20String/2390.%20Removing%20Stars%20From%20a%20String.md) |
| 6 | [1209. Remove All Adjacent Duplicates in String II](https://leetcode.com/problems/remove-all-adjacent-duplicates-in-string-ii/) | Medium | 6 months | 6.1 | Todo |  |  |  | [notes](01.%20Stack%20Basics/1209.%20Remove%20All%20Adjacent%20Duplicates%20in%20String%20II/1209.%20Remove%20All%20Adjacent%20Duplicates%20in%20String%20II.md) |
| 7 | [3174. Clear Digits](https://leetcode.com/problems/clear-digits/) | Easy | 6+ months | 6.6 | ✅ Solved |  |  |  | [notes](01.%20Stack%20Basics/3174.%20Clear%20Digits/3174.%20Clear%20Digits.md) |
| 8 | [2696. Minimum String Length After Removing Substrings](https://leetcode.com/problems/minimum-string-length-after-removing-substrings/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Stack%20Basics/2696.%20Minimum%20String%20Length%20After%20Removing%20Substrings/2696.%20Minimum%20String%20Length%20After%20Removing%20Substrings.md) |
| 9 | [3412. Find Mirror Score of a String](https://leetcode.com/problems/find-mirror-score-of-a-string/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Stack%20Basics/3412.%20Find%20Mirror%20Score%20of%20a%20String/3412.%20Find%20Mirror%20Score%20of%20a%20String.md) |

## 02. Parentheses & Bracket Matching

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [20. Valid Parentheses](https://leetcode.com/problems/valid-parentheses/) | Easy | 3 months | 72.2 | ✅ Solved |  |  |  | [notes](02.%20Parentheses%20%26%20Bracket%20Matching/0020.%20Valid%20Parentheses/0020.%20Valid%20Parentheses.md) |
| 2 | [32. Longest Valid Parentheses](https://leetcode.com/problems/longest-valid-parentheses/) | Hard | 3 months | 43.3 | Todo |  |  |  | [notes](02.%20Parentheses%20%26%20Bracket%20Matching/0032.%20Longest%20Valid%20Parentheses/0032.%20Longest%20Valid%20Parentheses.md) |
| 3 | [921. Minimum Add to Make Parentheses Valid](https://leetcode.com/problems/minimum-add-to-make-parentheses-valid/) | Medium | 3 months | 28.1 | Todo |  |  |  | [notes](02.%20Parentheses%20%26%20Bracket%20Matching/0921.%20Minimum%20Add%20to%20Make%20Parentheses%20Valid/0921.%20Minimum%20Add%20to%20Make%20Parentheses%20Valid.md) |
| 4 | [856. Score of Parentheses](https://leetcode.com/problems/score-of-parentheses/) | Medium | 3 months | 18.6 | Todo |  |  |  | [notes](02.%20Parentheses%20%26%20Bracket%20Matching/0856.%20Score%20of%20Parentheses/0856.%20Score%20of%20Parentheses.md) |
| 5 | [1111. Maximum Nesting Depth of Two Valid Parentheses Strings](https://leetcode.com/problems/maximum-nesting-depth-of-two-valid-parentheses-strings/) | Medium | 3 months | 15.5 | Todo |  |  |  | [notes](02.%20Parentheses%20%26%20Bracket%20Matching/1111.%20Maximum%20Nesting%20Depth%20of%20Two%20Valid%20Parentheses%20Strings/1111.%20Maximum%20Nesting%20Depth%20of%20Two%20Valid%20Parentheses%20Strings.md) |
| 6 | [1190. Reverse Substrings Between Each Pair of Parentheses](https://leetcode.com/problems/reverse-substrings-between-each-pair-of-parentheses/) | Medium | 3 months | 14.4 | ✅ Solved |  |  |  | [notes](02.%20Parentheses%20%26%20Bracket%20Matching/1190.%20Reverse%20Substrings%20Between%20Each%20Pair%20of%20Parentheses/1190.%20Reverse%20Substrings%20Between%20Each%20Pair%20of%20Parentheses.md) |
| 7 | [1541. Minimum Insertions to Balance a Parentheses String](https://leetcode.com/problems/minimum-insertions-to-balance-a-parentheses-string/) | Medium | 3 months | 5.0 | Todo |  |  |  | [notes](02.%20Parentheses%20%26%20Bracket%20Matching/1541.%20Minimum%20Insertions%20to%20Balance%20a%20Parentheses%20String/1541.%20Minimum%20Insertions%20to%20Balance%20a%20Parentheses%20String.md) |
| 8 | [1021. Remove Outermost Parentheses](https://leetcode.com/problems/remove-outermost-parentheses/) | Easy | 6 months | 35.8 | Todo |  |  |  | [notes](02.%20Parentheses%20%26%20Bracket%20Matching/1021.%20Remove%20Outermost%20Parentheses/1021.%20Remove%20Outermost%20Parentheses.md) |
| 9 | [1614. Maximum Nesting Depth of the Parentheses](https://leetcode.com/problems/maximum-nesting-depth-of-the-parentheses/) | Easy | 6 months | 26.4 | ✅ Solved |  |  |  | [notes](02.%20Parentheses%20%26%20Bracket%20Matching/1614.%20Maximum%20Nesting%20Depth%20of%20the%20Parentheses/1614.%20Maximum%20Nesting%20Depth%20of%20the%20Parentheses.md) |
| 10 | [1249. Minimum Remove to Make Valid Parentheses](https://leetcode.com/problems/minimum-remove-to-make-valid-parentheses/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](02.%20Parentheses%20%26%20Bracket%20Matching/1249.%20Minimum%20Remove%20to%20Make%20Valid%20Parentheses/1249.%20Minimum%20Remove%20to%20Make%20Valid%20Parentheses.md) |

## 03. Expression Evaluation & Calculator

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [394. Decode String](https://leetcode.com/problems/decode-string/) | Medium | 3 months | 61.9 | Todo |  |  |  | [notes](03.%20Expression%20Evaluation%20%26%20Calculator/0394.%20Decode%20String/0394.%20Decode%20String.md) |
| 2 | [224. Basic Calculator](https://leetcode.com/problems/basic-calculator/) | Hard | 3 months | 51.4 | Todo |  |  |  | [notes](03.%20Expression%20Evaluation%20%26%20Calculator/0224.%20Basic%20Calculator/0224.%20Basic%20Calculator.md) |
| 3 | [150. Evaluate Reverse Polish Notation](https://leetcode.com/problems/evaluate-reverse-polish-notation/) | Medium | 3 months | 39.5 | ✅ Solved |  |  |  | [notes](03.%20Expression%20Evaluation%20%26%20Calculator/0150.%20Evaluate%20Reverse%20Polish%20Notation/0150.%20Evaluate%20Reverse%20Polish%20Notation.md) |
| 4 | [772. Basic Calculator III](https://leetcode.com/problems/basic-calculator-iii/) 🔒 | Hard | 3 months | 20.3 | Todo |  |  |  | [notes](03.%20Expression%20Evaluation%20%26%20Calculator/0772.%20Basic%20Calculator%20III/0772.%20Basic%20Calculator%20III.md) |
| 5 | [736. Parse Lisp Expression](https://leetcode.com/problems/parse-lisp-expression/) | Hard | 3 months | 13.8 | Todo |  |  |  | [notes](03.%20Expression%20Evaluation%20%26%20Calculator/0736.%20Parse%20Lisp%20Expression/0736.%20Parse%20Lisp%20Expression.md) |
| 6 | [3749. Evaluate Valid Expressions](https://leetcode.com/problems/evaluate-valid-expressions/) 🔒 | Hard | 3 months | 12.0 | Todo |  |  |  | [notes](03.%20Expression%20Evaluation%20%26%20Calculator/3749.%20Evaluate%20Valid%20Expressions/3749.%20Evaluate%20Valid%20Expressions.md) |
| 7 | [726. Number of Atoms](https://leetcode.com/problems/number-of-atoms/) | Hard | 6 months | 33.9 | Todo |  |  |  | [notes](03.%20Expression%20Evaluation%20%26%20Calculator/0726.%20Number%20of%20Atoms/0726.%20Number%20of%20Atoms.md) |
| 8 | [227. Basic Calculator II](https://leetcode.com/problems/basic-calculator-ii/) | Medium | 6 months | 24.6 | Todo |  |  |  | [notes](03.%20Expression%20Evaluation%20%26%20Calculator/0227.%20Basic%20Calculator%20II/0227.%20Basic%20Calculator%20II.md) |
| 9 | [1106. Parsing A Boolean Expression](https://leetcode.com/problems/parsing-a-boolean-expression/) | Hard | 6+ months | 7.7 | Todo |  |  |  | [notes](03.%20Expression%20Evaluation%20%26%20Calculator/1106.%20Parsing%20A%20Boolean%20Expression/1106.%20Parsing%20A%20Boolean%20Expression.md) |
| 10 | [770. Basic Calculator IV](https://leetcode.com/problems/basic-calculator-iv/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](03.%20Expression%20Evaluation%20%26%20Calculator/0770.%20Basic%20Calculator%20IV/0770.%20Basic%20Calculator%20IV.md) |
| 11 | [1896. Minimum Cost to Change the Final Value of Expression](https://leetcode.com/problems/minimum-cost-to-change-the-final-value-of-expression/) | Hard | 6+ months | 28.8 | Todo |  |  |  | [notes](03.%20Expression%20Evaluation%20%26%20Calculator/1896.%20Minimum%20Cost%20to%20Change%20the%20Final%20Value%20of%20Expression/1896.%20Minimum%20Cost%20to%20Change%20the%20Final%20Value%20of%20Expression.md) |

## 04. Monotonic Stack

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [739. Daily Temperatures](https://leetcode.com/problems/daily-temperatures/) | Medium | 30 days | 56.2 | ✅ Solved |  |  |  | [notes](04.%20Monotonic%20Stack/0739.%20Daily%20Temperatures/0739.%20Daily%20Temperatures.md) |
| 2 | [1944. Number of Visible People in a Queue](https://leetcode.com/problems/number-of-visible-people-in-a-queue/) | Hard | 3 months | 60.9 | Todo |  |  |  | [notes](04.%20Monotonic%20Stack/1944.%20Number%20of%20Visible%20People%20in%20a%20Queue/1944.%20Number%20of%20Visible%20People%20in%20a%20Queue.md) |
| 3 | [84. Largest Rectangle in Histogram](https://leetcode.com/problems/largest-rectangle-in-histogram/) | Hard | 3 months | 56.1 | ✅ Solved |  |  |  | [notes](04.%20Monotonic%20Stack/0084.%20Largest%20Rectangle%20in%20Histogram/0084.%20Largest%20Rectangle%20in%20Histogram.md) |
| 4 | [503. Next Greater Element II](https://leetcode.com/problems/next-greater-element-ii/) | Medium | 3 months | 49.9 | ✅ Solved |  |  |  | [notes](04.%20Monotonic%20Stack/0503.%20Next%20Greater%20Element%20II/0503.%20Next%20Greater%20Element%20II.md) |
| 5 | [402. Remove K Digits](https://leetcode.com/problems/remove-k-digits/) | Medium | 3 months | 48.8 | ✅ Solved |  |  |  | [notes](04.%20Monotonic%20Stack/0402.%20Remove%20K%20Digits/0402.%20Remove%20K%20Digits.md) |
| 6 | [496. Next Greater Element I](https://leetcode.com/problems/next-greater-element-i/) | Easy | 3 months | 45.5 | ✅ Solved |  |  |  | [notes](04.%20Monotonic%20Stack/0496.%20Next%20Greater%20Element%20I/0496.%20Next%20Greater%20Element%20I.md) |
| 7 | [901. Online Stock Span](https://leetcode.com/problems/online-stock-span/) | Medium | 3 months | 35.4 | ✅ Solved |  |  |  | [notes](04.%20Monotonic%20Stack/0901.%20Online%20Stock%20Span/0901.%20Online%20Stock%20Span.md) |
| 8 | [85. Maximal Rectangle](https://leetcode.com/problems/maximal-rectangle/) | Hard | 6 months | 50.6 | ✅ Solved |  |  |  | [notes](04.%20Monotonic%20Stack/0085.%20Maximal%20Rectangle/0085.%20Maximal%20Rectangle.md) |
| 9 | [907. Sum of Subarray Minimums](https://leetcode.com/problems/sum-of-subarray-minimums/) | Medium | 6 months | 39.6 | ✅ Solved |  |  |  | [notes](04.%20Monotonic%20Stack/0907.%20Sum%20of%20Subarray%20Minimums/0907.%20Sum%20of%20Subarray%20Minimums.md) |
| 10 | [1081. Smallest Subsequence of Distinct Characters](https://leetcode.com/problems/smallest-subsequence-of-distinct-characters/) | Medium | 6 months | 39.5 | Todo |  |  |  | [notes](04.%20Monotonic%20Stack/1081.%20Smallest%20Subsequence%20of%20Distinct%20Characters/1081.%20Smallest%20Subsequence%20of%20Distinct%20Characters.md) |
| 11 | [853. Car Fleet](https://leetcode.com/problems/car-fleet/) | Medium | 6 months | 37.4 | ✅ Solved |  |  |  | [notes](04.%20Monotonic%20Stack/0853.%20Car%20Fleet/0853.%20Car%20Fleet.md) |
| 12 | [456. 132 Pattern](https://leetcode.com/problems/132-pattern/) | Medium | 6 months | 22.5 | Todo |  |  |  | [notes](04.%20Monotonic%20Stack/0456.%20132%20Pattern/0456.%20132%20Pattern.md) |
| 13 | [316. Remove Duplicate Letters](https://leetcode.com/problems/remove-duplicate-letters/) | Medium | 6+ months | 39.0 | Todo |  |  |  | [notes](04.%20Monotonic%20Stack/0316.%20Remove%20Duplicate%20Letters/0316.%20Remove%20Duplicate%20Letters.md) |
| 14 | [962. Maximum Width Ramp](https://leetcode.com/problems/maximum-width-ramp/) | Medium | 6+ months | 39.0 | Todo |  |  |  | [notes](04.%20Monotonic%20Stack/0962.%20Maximum%20Width%20Ramp/0962.%20Maximum%20Width%20Ramp.md) |
| 15 | [1673. Find the Most Competitive Subsequence](https://leetcode.com/problems/find-the-most-competitive-subsequence/) | Medium | 6+ months | 34.4 | Todo |  |  |  | [notes](04.%20Monotonic%20Stack/1673.%20Find%20the%20Most%20Competitive%20Subsequence/1673.%20Find%20the%20Most%20Competitive%20Subsequence.md) |
| 16 | [768. Max Chunks To Make Sorted II](https://leetcode.com/problems/max-chunks-to-make-sorted-ii/) | Hard | 6+ months | 33.3 | Todo |  |  |  | [notes](04.%20Monotonic%20Stack/0768.%20Max%20Chunks%20To%20Make%20Sorted%20II/0768.%20Max%20Chunks%20To%20Make%20Sorted%20II.md) |
| 17 | [321. Create Maximum Number](https://leetcode.com/problems/create-maximum-number/) | Hard | 6+ months | 31.6 | Todo |  |  |  | [notes](04.%20Monotonic%20Stack/0321.%20Create%20Maximum%20Number/0321.%20Create%20Maximum%20Number.md) |
| 18 | [1504. Count Submatrices With All Ones](https://leetcode.com/problems/count-submatrices-with-all-ones/) | Medium | 6+ months | 31.3 | Todo |  |  |  | [notes](04.%20Monotonic%20Stack/1504.%20Count%20Submatrices%20With%20All%20Ones/1504.%20Count%20Submatrices%20With%20All%20Ones.md) |
| 19 | [1776. Car Fleet II](https://leetcode.com/problems/car-fleet-ii/) | Hard | 6+ months | 29.5 | Todo |  |  |  | [notes](04.%20Monotonic%20Stack/1776.%20Car%20Fleet%20II/1776.%20Car%20Fleet%20II.md) |
| 20 | [2104. Sum of Subarray Ranges](https://leetcode.com/problems/sum-of-subarray-ranges/) | Medium | 6+ months | 14.3 | ✅ Solved |  |  |  | [notes](04.%20Monotonic%20Stack/2104.%20Sum%20of%20Subarray%20Ranges/2104.%20Sum%20of%20Subarray%20Ranges.md) |
| 21 | [1475. Final Prices With a Special Discount in a Shop](https://leetcode.com/problems/final-prices-with-a-special-discount-in-a-shop/) | Easy | 6+ months | 13.9 | Todo |  |  |  | [notes](04.%20Monotonic%20Stack/1475.%20Final%20Prices%20With%20a%20Special%20Discount%20in%20a%20Shop/1475.%20Final%20Prices%20With%20a%20Special%20Discount%20in%20a%20Shop.md) |
| 22 | [3542. Minimum Operations to Convert All Elements to Zero](https://leetcode.com/problems/minimum-operations-to-convert-all-elements-to-zero/) | Medium | 6+ months | 10.4 | Todo |  |  |  | [notes](04.%20Monotonic%20Stack/3542.%20Minimum%20Operations%20to%20Convert%20All%20Elements%20to%20Zero/3542.%20Minimum%20Operations%20to%20Convert%20All%20Elements%20to%20Zero.md) |
| 23 | [2487. Remove Nodes From Linked List](https://leetcode.com/problems/remove-nodes-from-linked-list/) | Medium | 6+ months | 6.7 | ✅ Solved |  |  |  | [notes](04.%20Monotonic%20Stack/2487.%20Remove%20Nodes%20From%20Linked%20List/2487.%20Remove%20Nodes%20From%20Linked%20List.md) |
| 24 | [3523. Make Array Non-decreasing](https://leetcode.com/problems/make-array-non-decreasing/) | Medium | 6+ months | 6.3 | Todo |  |  |  | [notes](04.%20Monotonic%20Stack/3523.%20Make%20Array%20Non-decreasing/3523.%20Make%20Array%20Non-decreasing.md) |
| 25 | [1130. Minimum Cost Tree From Leaf Values](https://leetcode.com/problems/minimum-cost-tree-from-leaf-values/) | Medium | 6+ months | 6.2 | Todo |  |  |  | [notes](04.%20Monotonic%20Stack/1130.%20Minimum%20Cost%20Tree%20From%20Leaf%20Values/1130.%20Minimum%20Cost%20Tree%20From%20Leaf%20Values.md) |
| 26 | [1019. Next Greater Node In Linked List](https://leetcode.com/problems/next-greater-node-in-linked-list/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Monotonic%20Stack/1019.%20Next%20Greater%20Node%20In%20Linked%20List/1019.%20Next%20Greater%20Node%20In%20Linked%20List.md) |
| 27 | [1762. Buildings With an Ocean View](https://leetcode.com/problems/buildings-with-an-ocean-view/) 🔒 | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Monotonic%20Stack/1762.%20Buildings%20With%20an%20Ocean%20View/1762.%20Buildings%20With%20an%20Ocean%20View.md) |
| 28 | [1856. Maximum Subarray Min-Product](https://leetcode.com/problems/maximum-subarray-min-product/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Monotonic%20Stack/1856.%20Maximum%20Subarray%20Min-Product/1856.%20Maximum%20Subarray%20Min-Product.md) |
| 29 | [2818. Apply Operations to Maximize Score](https://leetcode.com/problems/apply-operations-to-maximize-score/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Monotonic%20Stack/2818.%20Apply%20Operations%20to%20Maximize%20Score/2818.%20Apply%20Operations%20to%20Maximize%20Score.md) |
| 30 | [2940. Find Building Where Alice and Bob Can Meet](https://leetcode.com/problems/find-building-where-alice-and-bob-can-meet/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Monotonic%20Stack/2940.%20Find%20Building%20Where%20Alice%20and%20Bob%20Can%20Meet/2940.%20Find%20Building%20Where%20Alice%20and%20Bob%20Can%20Meet.md) |
| 31 | [3676. Count Bowl Subarrays](https://leetcode.com/problems/count-bowl-subarrays/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Monotonic%20Stack/3676.%20Count%20Bowl%20Subarrays/3676.%20Count%20Bowl%20Subarrays.md) |
| 32 | [2334. Subarray With Elements Greater Than Varying Threshold](https://leetcode.com/problems/subarray-with-elements-greater-than-varying-threshold/) | Hard | 6+ months | 28.8 | Todo |  |  |  | [notes](04.%20Monotonic%20Stack/2334.%20Subarray%20With%20Elements%20Greater%20Than%20Varying%20Threshold/2334.%20Subarray%20With%20Elements%20Greater%20Than%20Varying%20Threshold.md) |
| 33 | [2863. Maximum Length of Semi-Decreasing Subarrays](https://leetcode.com/problems/maximum-length-of-semi-decreasing-subarrays/) 🔒 | Medium | 6+ months | 28.8 | Todo |  |  |  | [notes](04.%20Monotonic%20Stack/2863.%20Maximum%20Length%20of%20Semi-Decreasing%20Subarrays/2863.%20Maximum%20Length%20of%20Semi-Decreasing%20Subarrays.md) |

## 05. Monotonic Deque

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [3420. Count Non-Decreasing Subarrays After K Operations](https://leetcode.com/problems/count-non-decreasing-subarrays-after-k-operations/) | Hard | 30 days | 20.2 | Todo |  |  |  | [notes](05.%20Monotonic%20Deque/3420.%20Count%20Non-Decreasing%20Subarrays%20After%20K%20Operations/3420.%20Count%20Non-Decreasing%20Subarrays%20After%20K%20Operations.md) |
| 2 | [239. Sliding Window Maximum](https://leetcode.com/problems/sliding-window-maximum/) | Hard | 3 months | 61.1 | ✅ Solved |  |  |  | [notes](05.%20Monotonic%20Deque/0239.%20Sliding%20Window%20Maximum/0239.%20Sliding%20Window%20Maximum.md) |
| 3 | [1438. Longest Continuous Subarray With Absolute Diff Less Than or Equal to Limit](https://leetcode.com/problems/longest-continuous-subarray-with-absolute-diff-less-than-or-equal-to-limit/) | Medium | 6 months | 40.0 | Todo |  |  |  | [notes](05.%20Monotonic%20Deque/1438.%20Longest%20Continuous%20Subarray%20With%20Absolute%20Diff%20Less%20Than%20or%20Equal%20to%20Limit/1438.%20Longest%20Continuous%20Subarray%20With%20Absolute%20Diff%20Less%20Than%20or%20Equal%20to%20Limit.md) |
| 4 | [862. Shortest Subarray with Sum at Least K](https://leetcode.com/problems/shortest-subarray-with-sum-at-least-k/) | Hard | 6 months | 22.2 | Todo |  |  |  | [notes](05.%20Monotonic%20Deque/0862.%20Shortest%20Subarray%20with%20Sum%20at%20Least%20K/0862.%20Shortest%20Subarray%20with%20Sum%20at%20Least%20K.md) |
| 5 | [2762. Continuous Subarrays](https://leetcode.com/problems/continuous-subarrays/) | Medium | 6+ months | 32.8 | Todo |  |  |  | [notes](05.%20Monotonic%20Deque/2762.%20Continuous%20Subarrays/2762.%20Continuous%20Subarrays.md) |
| 6 | [3578. Count Partitions With Max-Min Difference at Most K](https://leetcode.com/problems/count-partitions-with-max-min-difference-at-most-k/) | Medium | 6+ months | 8.1 | Todo |  |  |  | [notes](05.%20Monotonic%20Deque/3578.%20Count%20Partitions%20With%20Max-Min%20Difference%20at%20Most%20K/3578.%20Count%20Partitions%20With%20Max-Min%20Difference%20at%20Most%20K.md) |
| 7 | [1425. Constrained Subsequence Sum](https://leetcode.com/problems/constrained-subsequence-sum/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Monotonic%20Deque/1425.%20Constrained%20Subsequence%20Sum/1425.%20Constrained%20Subsequence%20Sum.md) |
| 8 | [1696. Jump Game VI](https://leetcode.com/problems/jump-game-vi/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Monotonic%20Deque/1696.%20Jump%20Game%20VI/1696.%20Jump%20Game%20VI.md) |
| 9 | [3589. Count Prime-Gap Balanced Subarrays](https://leetcode.com/problems/count-prime-gap-balanced-subarrays/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Monotonic%20Deque/3589.%20Count%20Prime-Gap%20Balanced%20Subarrays/3589.%20Count%20Prime-Gap%20Balanced%20Subarrays.md) |
| 10 | [1499. Max Value of Equation](https://leetcode.com/problems/max-value-of-equation/) | Hard | 6+ months | 29.8 | Todo |  |  |  | [notes](05.%20Monotonic%20Deque/1499.%20Max%20Value%20of%20Equation/1499.%20Max%20Value%20of%20Equation.md) |

## 06. Queue Basics

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [232. Implement Queue using Stacks](https://leetcode.com/problems/implement-queue-using-stacks/) | Easy | 3 months | 33.5 | Todo |  |  |  | [notes](06.%20Queue%20Basics/0232.%20Implement%20Queue%20using%20Stacks/0232.%20Implement%20Queue%20using%20Stacks.md) |
| 2 | [2534. Time Taken to Cross the Door](https://leetcode.com/problems/time-taken-to-cross-the-door/) 🔒 | Hard | 3 months | 26.5 | Todo |  |  |  | [notes](06.%20Queue%20Basics/2534.%20Time%20Taken%20to%20Cross%20the%20Door/2534.%20Time%20Taken%20to%20Cross%20the%20Door.md) |
| 3 | [225. Implement Stack using Queues](https://leetcode.com/problems/implement-stack-using-queues/) | Easy | 6 months | 32.9 | Todo |  |  |  | [notes](06.%20Queue%20Basics/0225.%20Implement%20Stack%20using%20Queues/0225.%20Implement%20Stack%20using%20Queues.md) |
| 4 | [950. Reveal Cards In Increasing Order](https://leetcode.com/problems/reveal-cards-in-increasing-order/) | Medium | 6 months | 11.5 | ✅ Solved |  |  |  | [notes](06.%20Queue%20Basics/0950.%20Reveal%20Cards%20In%20Increasing%20Order/0950.%20Reveal%20Cards%20In%20Increasing%20Order.md) |
| 5 | [2073. Time Needed to Buy Tickets](https://leetcode.com/problems/time-needed-to-buy-tickets/) | Easy | 6 months | 10.5 | ✅ Solved |  |  |  | [notes](06.%20Queue%20Basics/2073.%20Time%20Needed%20to%20Buy%20Tickets/2073.%20Time%20Needed%20to%20Buy%20Tickets.md) |
| 6 | [1700. Number of Students Unable to Eat Lunch](https://leetcode.com/problems/number-of-students-unable-to-eat-lunch/) | Easy | 6+ months | 10.2 | ✅ Solved |  |  |  | [notes](06.%20Queue%20Basics/1700.%20Number%20of%20Students%20Unable%20to%20Eat%20Lunch/1700.%20Number%20of%20Students%20Unable%20to%20Eat%20Lunch.md) |
| 7 | [649. Dota2 Senate](https://leetcode.com/problems/dota2-senate/) | Medium | 6+ months | 9.4 | Todo |  |  |  | [notes](06.%20Queue%20Basics/0649.%20Dota2%20Senate/0649.%20Dota2%20Senate.md) |

## 07. Stack Simulation (Asteroid, Path)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [71. Simplify Path](https://leetcode.com/problems/simplify-path/) | Medium | 6 months | 32.5 | Todo |  |  |  | [notes](07.%20Stack%20Simulation%20%28Asteroid%2C%20Path%29/0071.%20Simplify%20Path/0071.%20Simplify%20Path.md) |
| 2 | [636. Exclusive Time of Functions](https://leetcode.com/problems/exclusive-time-of-functions/) | Medium | 6 months | 25.3 | Todo |  |  |  | [notes](07.%20Stack%20Simulation%20%28Asteroid%2C%20Path%29/0636.%20Exclusive%20Time%20of%20Functions/0636.%20Exclusive%20Time%20of%20Functions.md) |
| 3 | [388. Longest Absolute File Path](https://leetcode.com/problems/longest-absolute-file-path/) | Medium | 6+ months | 33.9 | Todo |  |  |  | [notes](07.%20Stack%20Simulation%20%28Asteroid%2C%20Path%29/0388.%20Longest%20Absolute%20File%20Path/0388.%20Longest%20Absolute%20File%20Path.md) |
| 4 | [1441. Build an Array With Stack Operations](https://leetcode.com/problems/build-an-array-with-stack-operations/) | Medium | 6+ months | 33.2 | Todo |  |  |  | [notes](07.%20Stack%20Simulation%20%28Asteroid%2C%20Path%29/1441.%20Build%20an%20Array%20With%20Stack%20Operations/1441.%20Build%20an%20Array%20With%20Stack%20Operations.md) |
| 5 | [735. Asteroid Collision](https://leetcode.com/problems/asteroid-collision/) | Medium | 6+ months | 31.1 | ✅ Solved |  |  |  | [notes](07.%20Stack%20Simulation%20%28Asteroid%2C%20Path%29/0735.%20Asteroid%20Collision/0735.%20Asteroid%20Collision.md) |
| 6 | [2197. Replace Non-Coprime Numbers in Array](https://leetcode.com/problems/replace-non-coprime-numbers-in-array/) | Hard | 6+ months | 5.7 | Todo |  |  |  | [notes](07.%20Stack%20Simulation%20%28Asteroid%2C%20Path%29/2197.%20Replace%20Non-Coprime%20Numbers%20in%20Array/2197.%20Replace%20Non-Coprime%20Numbers%20in%20Array.md) |
| 7 | [2751. Robot Collisions](https://leetcode.com/problems/robot-collisions/) | Hard | 6+ months | 5.4 | Todo |  |  |  | [notes](07.%20Stack%20Simulation%20%28Asteroid%2C%20Path%29/2751.%20Robot%20Collisions/2751.%20Robot%20Collisions.md) |
| 8 | [946. Validate Stack Sequences](https://leetcode.com/problems/validate-stack-sequences/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](07.%20Stack%20Simulation%20%28Asteroid%2C%20Path%29/0946.%20Validate%20Stack%20Sequences/0946.%20Validate%20Stack%20Sequences.md) |
| 9 | [2211. Count Collisions on a Road](https://leetcode.com/problems/count-collisions-on-a-road/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](07.%20Stack%20Simulation%20%28Asteroid%2C%20Path%29/2211.%20Count%20Collisions%20on%20a%20Road/2211.%20Count%20Collisions%20on%20a%20Road.md) |
