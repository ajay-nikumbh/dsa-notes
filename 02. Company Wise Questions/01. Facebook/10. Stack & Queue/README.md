# 10. Stack & Queue

[Back to Facebook](../README.md) · [Back to DSA Notes](../../../README.md)

67 Meta (Facebook) problems: 14 Easy, 40 Medium, 13 Hard, in 7 sub-patterns.

## Sub-patterns

| # | Sub-pattern | Questions | Easy | Medium | Hard | Last 3 Months | Solved | Most Asked |
|:---:|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---|
| 01 | [Stack Basics](#01-stack-basics) | 8 | 5 | 3 | 0 | 0 | 2 | 1047. Remove All Adjacent Duplicates In String, 1209. Remove All Adjacent Duplicates in String II, 682. Baseball Game |
| 02 | [Parentheses & Bracket Matching](#02-parentheses--bracket-matching) | 9 | 3 | 5 | 1 | 5 | 4 | 1249. Minimum Remove to Make Valid Parentheses, 20. Valid Parentheses, 921. Minimum Add to Make Parentheses Valid |
| 03 | [Expression Evaluation & Calculator](#03-expression-evaluation--calculator) | 8 | 0 | 5 | 3 | 3 | 1 | 227. Basic Calculator II, 394. Decode String, 224. Basic Calculator |
| 04 | [Monotonic Stack](#04-monotonic-stack) | 23 | 2 | 15 | 6 | 0 | 11 | 1762. Buildings With an Ocean View, 85. Maximal Rectangle, 739. Daily Temperatures |
| 05 | [Monotonic Deque](#05-monotonic-deque) | 6 | 0 | 4 | 2 | 1 | 1 | 239. Sliding Window Maximum, 862. Shortest Subarray with Sum at Least K, 2762. Continuous Subarrays |
| 06 | [Queue Basics](#06-queue-basics) | 5 | 4 | 1 | 0 | 0 | 2 | 225. Implement Stack using Queues, 232. Implement Queue using Stacks, 1700. Number of Students Unable to Eat Lunch |
| 07 | [Stack Simulation (Asteroid, Path)](#07-stack-simulation-asteroid-path) | 8 | 0 | 7 | 1 | 1 | 1 | 71. Simplify Path, 636. Exclusive Time of Functions, 735. Asteroid Collision |

**Columns**

- **Last Asked**: most recent LeetCode window that lists the problem for Meta (30 days, 3 months, 6 months or 6+ months).
- **Frequency**: LeetCode frequency score (0-100) in the Meta "All" list.
- **Status**: your LeetCode status on the day this file was generated. 🔒 after a title means LeetCode Premium.
- **Logic / Key Idea, Time, Space**: fill these in as you solve. A rebuild keeps what you typed.
- **Notes**: link to the problem's notes file.

Inside each sub-pattern, rows are sorted by most recent window, then by frequency (highest first).

## 01. Stack Basics

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [682. Baseball Game](https://leetcode.com/problems/baseball-game/) | Easy | 6 months | 19.6 | ✅ Solved |  |  |  | [notes](01.%20Stack%20Basics/0682.%20Baseball%20Game/0682.%20Baseball%20Game.md) |
| 2 | [2696. Minimum String Length After Removing Substrings](https://leetcode.com/problems/minimum-string-length-after-removing-substrings/) | Easy | 6 months | 5.0 | Todo |  |  |  | [notes](01.%20Stack%20Basics/2696.%20Minimum%20String%20Length%20After%20Removing%20Substrings/2696.%20Minimum%20String%20Length%20After%20Removing%20Substrings.md) |
| 3 | [1047. Remove All Adjacent Duplicates In String](https://leetcode.com/problems/remove-all-adjacent-duplicates-in-string/) | Easy | 6+ months | 49.3 | Todo |  |  |  | [notes](01.%20Stack%20Basics/1047.%20Remove%20All%20Adjacent%20Duplicates%20In%20String/1047.%20Remove%20All%20Adjacent%20Duplicates%20In%20String.md) |
| 4 | [1209. Remove All Adjacent Duplicates in String II](https://leetcode.com/problems/remove-all-adjacent-duplicates-in-string-ii/) | Medium | 6+ months | 38.7 | Todo |  |  |  | [notes](01.%20Stack%20Basics/1209.%20Remove%20All%20Adjacent%20Duplicates%20in%20String%20II/1209.%20Remove%20All%20Adjacent%20Duplicates%20in%20String%20II.md) |
| 5 | [1598. Crawler Log Folder](https://leetcode.com/problems/crawler-log-folder/) | Easy | 6+ months | 7.8 | Todo |  |  |  | [notes](01.%20Stack%20Basics/1598.%20Crawler%20Log%20Folder/1598.%20Crawler%20Log%20Folder.md) |
| 6 | [3561. Resulting String After Adjacent Removals](https://leetcode.com/problems/resulting-string-after-adjacent-removals/) | Medium | 6+ months | 6.4 | Todo |  |  |  | [notes](01.%20Stack%20Basics/3561.%20Resulting%20String%20After%20Adjacent%20Removals/3561.%20Resulting%20String%20After%20Adjacent%20Removals.md) |
| 7 | [1910. Remove All Occurrences of a Substring](https://leetcode.com/problems/remove-all-occurrences-of-a-substring/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Stack%20Basics/1910.%20Remove%20All%20Occurrences%20of%20a%20Substring/1910.%20Remove%20All%20Occurrences%20of%20a%20Substring.md) |
| 8 | [3174. Clear Digits](https://leetcode.com/problems/clear-digits/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](01.%20Stack%20Basics/3174.%20Clear%20Digits/3174.%20Clear%20Digits.md) |

## 02. Parentheses & Bracket Matching

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [20. Valid Parentheses](https://leetcode.com/problems/valid-parentheses/) | Easy | 30 days | 78.9 | ✅ Solved |  |  |  | [notes](02.%20Parentheses%20%26%20Bracket%20Matching/0020.%20Valid%20Parentheses/0020.%20Valid%20Parentheses.md) |
| 2 | [921. Minimum Add to Make Parentheses Valid](https://leetcode.com/problems/minimum-add-to-make-parentheses-valid/) | Medium | 3 months | 68.4 | Todo |  |  |  | [notes](02.%20Parentheses%20%26%20Bracket%20Matching/0921.%20Minimum%20Add%20to%20Make%20Parentheses%20Valid/0921.%20Minimum%20Add%20to%20Make%20Parentheses%20Valid.md) |
| 3 | [32. Longest Valid Parentheses](https://leetcode.com/problems/longest-valid-parentheses/) | Hard | 3 months | 54.0 | Todo |  |  |  | [notes](02.%20Parentheses%20%26%20Bracket%20Matching/0032.%20Longest%20Valid%20Parentheses/0032.%20Longest%20Valid%20Parentheses.md) |
| 4 | [856. Score of Parentheses](https://leetcode.com/problems/score-of-parentheses/) | Medium | 3 months | 20.5 | Todo |  |  |  | [notes](02.%20Parentheses%20%26%20Bracket%20Matching/0856.%20Score%20of%20Parentheses/0856.%20Score%20of%20Parentheses.md) |
| 5 | [1541. Minimum Insertions to Balance a Parentheses String](https://leetcode.com/problems/minimum-insertions-to-balance-a-parentheses-string/) | Medium | 3 months | 18.1 | Todo |  |  |  | [notes](02.%20Parentheses%20%26%20Bracket%20Matching/1541.%20Minimum%20Insertions%20to%20Balance%20a%20Parentheses%20String/1541.%20Minimum%20Insertions%20to%20Balance%20a%20Parentheses%20String.md) |
| 6 | [1249. Minimum Remove to Make Valid Parentheses](https://leetcode.com/problems/minimum-remove-to-make-valid-parentheses/) | Medium | 6 months | 100.0 | ✅ Solved |  |  |  | [notes](02.%20Parentheses%20%26%20Bracket%20Matching/1249.%20Minimum%20Remove%20to%20Make%20Valid%20Parentheses/1249.%20Minimum%20Remove%20to%20Make%20Valid%20Parentheses.md) |
| 7 | [1614. Maximum Nesting Depth of the Parentheses](https://leetcode.com/problems/maximum-nesting-depth-of-the-parentheses/) | Easy | 6 months | 25.1 | ✅ Solved |  |  |  | [notes](02.%20Parentheses%20%26%20Bracket%20Matching/1614.%20Maximum%20Nesting%20Depth%20of%20the%20Parentheses/1614.%20Maximum%20Nesting%20Depth%20of%20the%20Parentheses.md) |
| 8 | [1021. Remove Outermost Parentheses](https://leetcode.com/problems/remove-outermost-parentheses/) | Easy | 6 months | 20.2 | Todo |  |  |  | [notes](02.%20Parentheses%20%26%20Bracket%20Matching/1021.%20Remove%20Outermost%20Parentheses/1021.%20Remove%20Outermost%20Parentheses.md) |
| 9 | [1190. Reverse Substrings Between Each Pair of Parentheses](https://leetcode.com/problems/reverse-substrings-between-each-pair-of-parentheses/) | Medium | 6+ months | 7.8 | ✅ Solved |  |  |  | [notes](02.%20Parentheses%20%26%20Bracket%20Matching/1190.%20Reverse%20Substrings%20Between%20Each%20Pair%20of%20Parentheses/1190.%20Reverse%20Substrings%20Between%20Each%20Pair%20of%20Parentheses.md) |

## 03. Expression Evaluation & Calculator

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [227. Basic Calculator II](https://leetcode.com/problems/basic-calculator-ii/) | Medium | 3 months | 86.0 | Todo |  |  |  | [notes](03.%20Expression%20Evaluation%20%26%20Calculator/0227.%20Basic%20Calculator%20II/0227.%20Basic%20Calculator%20II.md) |
| 2 | [394. Decode String](https://leetcode.com/problems/decode-string/) | Medium | 3 months | 53.0 | Todo |  |  |  | [notes](03.%20Expression%20Evaluation%20%26%20Calculator/0394.%20Decode%20String/0394.%20Decode%20String.md) |
| 3 | [150. Evaluate Reverse Polish Notation](https://leetcode.com/problems/evaluate-reverse-polish-notation/) | Medium | 3 months | 39.6 | ✅ Solved |  |  |  | [notes](03.%20Expression%20Evaluation%20%26%20Calculator/0150.%20Evaluate%20Reverse%20Polish%20Notation/0150.%20Evaluate%20Reverse%20Polish%20Notation.md) |
| 4 | [224. Basic Calculator](https://leetcode.com/problems/basic-calculator/) | Hard | 6+ months | 40.1 | Todo |  |  |  | [notes](03.%20Expression%20Evaluation%20%26%20Calculator/0224.%20Basic%20Calculator/0224.%20Basic%20Calculator.md) |
| 5 | [385. Mini Parser](https://leetcode.com/problems/mini-parser/) | Medium | 6+ months | 6.8 | Todo |  |  |  | [notes](03.%20Expression%20Evaluation%20%26%20Calculator/0385.%20Mini%20Parser/0385.%20Mini%20Parser.md) |
| 6 | [772. Basic Calculator III](https://leetcode.com/problems/basic-calculator-iii/) 🔒 | Hard | 6+ months | 5.8 | Todo |  |  |  | [notes](03.%20Expression%20Evaluation%20%26%20Calculator/0772.%20Basic%20Calculator%20III/0772.%20Basic%20Calculator%20III.md) |
| 7 | [1106. Parsing A Boolean Expression](https://leetcode.com/problems/parsing-a-boolean-expression/) | Hard | 6+ months | 5.3 | Todo |  |  |  | [notes](03.%20Expression%20Evaluation%20%26%20Calculator/1106.%20Parsing%20A%20Boolean%20Expression/1106.%20Parsing%20A%20Boolean%20Expression.md) |
| 8 | [1006. Clumsy Factorial](https://leetcode.com/problems/clumsy-factorial/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](03.%20Expression%20Evaluation%20%26%20Calculator/1006.%20Clumsy%20Factorial/1006.%20Clumsy%20Factorial.md) |

## 04. Monotonic Stack

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [739. Daily Temperatures](https://leetcode.com/problems/daily-temperatures/) | Medium | 6 months | 43.6 | ✅ Solved |  |  |  | [notes](04.%20Monotonic%20Stack/0739.%20Daily%20Temperatures/0739.%20Daily%20Temperatures.md) |
| 2 | [496. Next Greater Element I](https://leetcode.com/problems/next-greater-element-i/) | Easy | 6 months | 42.3 | ✅ Solved |  |  |  | [notes](04.%20Monotonic%20Stack/0496.%20Next%20Greater%20Element%20I/0496.%20Next%20Greater%20Element%20I.md) |
| 3 | [503. Next Greater Element II](https://leetcode.com/problems/next-greater-element-ii/) | Medium | 6 months | 30.8 | ✅ Solved |  |  |  | [notes](04.%20Monotonic%20Stack/0503.%20Next%20Greater%20Element%20II/0503.%20Next%20Greater%20Element%20II.md) |
| 4 | [901. Online Stock Span](https://leetcode.com/problems/online-stock-span/) | Medium | 6 months | 25.0 | ✅ Solved |  |  |  | [notes](04.%20Monotonic%20Stack/0901.%20Online%20Stock%20Span/0901.%20Online%20Stock%20Span.md) |
| 5 | [1762. Buildings With an Ocean View](https://leetcode.com/problems/buildings-with-an-ocean-view/) 🔒 | Medium | 6+ months | 83.3 | Todo |  |  |  | [notes](04.%20Monotonic%20Stack/1762.%20Buildings%20With%20an%20Ocean%20View/1762.%20Buildings%20With%20an%20Ocean%20View.md) |
| 6 | [85. Maximal Rectangle](https://leetcode.com/problems/maximal-rectangle/) | Hard | 6+ months | 44.2 | ✅ Solved |  |  |  | [notes](04.%20Monotonic%20Stack/0085.%20Maximal%20Rectangle/0085.%20Maximal%20Rectangle.md) |
| 7 | [84. Largest Rectangle in Histogram](https://leetcode.com/problems/largest-rectangle-in-histogram/) | Hard | 6+ months | 38.7 | ✅ Solved |  |  |  | [notes](04.%20Monotonic%20Stack/0084.%20Largest%20Rectangle%20in%20Histogram/0084.%20Largest%20Rectangle%20in%20Histogram.md) |
| 8 | [402. Remove K Digits](https://leetcode.com/problems/remove-k-digits/) | Medium | 6+ months | 26.6 | ✅ Solved |  |  |  | [notes](04.%20Monotonic%20Stack/0402.%20Remove%20K%20Digits/0402.%20Remove%20K%20Digits.md) |
| 9 | [1944. Number of Visible People in a Queue](https://leetcode.com/problems/number-of-visible-people-in-a-queue/) | Hard | 6+ months | 15.3 | Todo |  |  |  | [notes](04.%20Monotonic%20Stack/1944.%20Number%20of%20Visible%20People%20in%20a%20Queue/1944.%20Number%20of%20Visible%20People%20in%20a%20Queue.md) |
| 10 | [316. Remove Duplicate Letters](https://leetcode.com/problems/remove-duplicate-letters/) | Medium | 6+ months | 14.3 | Todo |  |  |  | [notes](04.%20Monotonic%20Stack/0316.%20Remove%20Duplicate%20Letters/0316.%20Remove%20Duplicate%20Letters.md) |
| 11 | [907. Sum of Subarray Minimums](https://leetcode.com/problems/sum-of-subarray-minimums/) | Medium | 6+ months | 13.4 | ✅ Solved |  |  |  | [notes](04.%20Monotonic%20Stack/0907.%20Sum%20of%20Subarray%20Minimums/0907.%20Sum%20of%20Subarray%20Minimums.md) |
| 12 | [456. 132 Pattern](https://leetcode.com/problems/132-pattern/) | Medium | 6+ months | 11.4 | Todo |  |  |  | [notes](04.%20Monotonic%20Stack/0456.%20132%20Pattern/0456.%20132%20Pattern.md) |
| 13 | [2104. Sum of Subarray Ranges](https://leetcode.com/problems/sum-of-subarray-ranges/) | Medium | 6+ months | 10.0 | ✅ Solved |  |  |  | [notes](04.%20Monotonic%20Stack/2104.%20Sum%20of%20Subarray%20Ranges/2104.%20Sum%20of%20Subarray%20Ranges.md) |
| 14 | [1475. Final Prices With a Special Discount in a Shop](https://leetcode.com/problems/final-prices-with-a-special-discount-in-a-shop/) | Easy | 6+ months | 9.4 | Todo |  |  |  | [notes](04.%20Monotonic%20Stack/1475.%20Final%20Prices%20With%20a%20Special%20Discount%20in%20a%20Shop/1475.%20Final%20Prices%20With%20a%20Special%20Discount%20in%20a%20Shop.md) |
| 15 | [2487. Remove Nodes From Linked List](https://leetcode.com/problems/remove-nodes-from-linked-list/) | Medium | 6+ months | 7.5 | ✅ Solved |  |  |  | [notes](04.%20Monotonic%20Stack/2487.%20Remove%20Nodes%20From%20Linked%20List/2487.%20Remove%20Nodes%20From%20Linked%20List.md) |
| 16 | [853. Car Fleet](https://leetcode.com/problems/car-fleet/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](04.%20Monotonic%20Stack/0853.%20Car%20Fleet/0853.%20Car%20Fleet.md) |
| 17 | [1504. Count Submatrices With All Ones](https://leetcode.com/problems/count-submatrices-with-all-ones/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Monotonic%20Stack/1504.%20Count%20Submatrices%20With%20All%20Ones/1504.%20Count%20Submatrices%20With%20All%20Ones.md) |
| 18 | [2940. Find Building Where Alice and Bob Can Meet](https://leetcode.com/problems/find-building-where-alice-and-bob-can-meet/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Monotonic%20Stack/2940.%20Find%20Building%20Where%20Alice%20and%20Bob%20Can%20Meet/2940.%20Find%20Building%20Where%20Alice%20and%20Bob%20Can%20Meet.md) |
| 19 | [3542. Minimum Operations to Convert All Elements to Zero](https://leetcode.com/problems/minimum-operations-to-convert-all-elements-to-zero/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Monotonic%20Stack/3542.%20Minimum%20Operations%20to%20Convert%20All%20Elements%20to%20Zero/3542.%20Minimum%20Operations%20to%20Convert%20All%20Elements%20to%20Zero.md) |
| 20 | [3816. Lexicographically Smallest String After Deleting Duplicate Characters](https://leetcode.com/problems/lexicographically-smallest-string-after-deleting-duplicate-characters/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Monotonic%20Stack/3816.%20Lexicographically%20Smallest%20String%20After%20Deleting%20Duplicate%20Characters/3816.%20Lexicographically%20Smallest%20String%20After%20Deleting%20Duplicate%20Characters.md) |
| 21 | [2289. Steps to Make Array Non-decreasing](https://leetcode.com/problems/steps-to-make-array-non-decreasing/) | Medium | 6+ months | 36.1 | Todo |  |  |  | [notes](04.%20Monotonic%20Stack/2289.%20Steps%20to%20Make%20Array%20Non-decreasing/2289.%20Steps%20to%20Make%20Array%20Non-decreasing.md) |
| 22 | [2454. Next Greater Element IV](https://leetcode.com/problems/next-greater-element-iv/) | Hard | 6+ months | 6.8 | Todo |  |  |  | [notes](04.%20Monotonic%20Stack/2454.%20Next%20Greater%20Element%20IV/2454.%20Next%20Greater%20Element%20IV.md) |
| 23 | [1081. Smallest Subsequence of Distinct Characters](https://leetcode.com/problems/smallest-subsequence-of-distinct-characters/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Monotonic%20Stack/1081.%20Smallest%20Subsequence%20of%20Distinct%20Characters/1081.%20Smallest%20Subsequence%20of%20Distinct%20Characters.md) |

## 05. Monotonic Deque

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [862. Shortest Subarray with Sum at Least K](https://leetcode.com/problems/shortest-subarray-with-sum-at-least-k/) | Hard | 3 months | 11.9 | Todo |  |  |  | [notes](05.%20Monotonic%20Deque/0862.%20Shortest%20Subarray%20with%20Sum%20at%20Least%20K/0862.%20Shortest%20Subarray%20with%20Sum%20at%20Least%20K.md) |
| 2 | [239. Sliding Window Maximum](https://leetcode.com/problems/sliding-window-maximum/) | Hard | 6 months | 50.4 | ✅ Solved |  |  |  | [notes](05.%20Monotonic%20Deque/0239.%20Sliding%20Window%20Maximum/0239.%20Sliding%20Window%20Maximum.md) |
| 3 | [2762. Continuous Subarrays](https://leetcode.com/problems/continuous-subarrays/) | Medium | 6+ months | 5.2 | Todo |  |  |  | [notes](05.%20Monotonic%20Deque/2762.%20Continuous%20Subarrays/2762.%20Continuous%20Subarrays.md) |
| 4 | [1438. Longest Continuous Subarray With Absolute Diff Less Than or Equal to Limit](https://leetcode.com/problems/longest-continuous-subarray-with-absolute-diff-less-than-or-equal-to-limit/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Monotonic%20Deque/1438.%20Longest%20Continuous%20Subarray%20With%20Absolute%20Diff%20Less%20Than%20or%20Equal%20to%20Limit/1438.%20Longest%20Continuous%20Subarray%20With%20Absolute%20Diff%20Less%20Than%20or%20Equal%20to%20Limit.md) |
| 5 | [1696. Jump Game VI](https://leetcode.com/problems/jump-game-vi/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Monotonic%20Deque/1696.%20Jump%20Game%20VI/1696.%20Jump%20Game%20VI.md) |
| 6 | [3578. Count Partitions With Max-Min Difference at Most K](https://leetcode.com/problems/count-partitions-with-max-min-difference-at-most-k/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Monotonic%20Deque/3578.%20Count%20Partitions%20With%20Max-Min%20Difference%20at%20Most%20K/3578.%20Count%20Partitions%20With%20Max-Min%20Difference%20at%20Most%20K.md) |

## 06. Queue Basics

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [2073. Time Needed to Buy Tickets](https://leetcode.com/problems/time-needed-to-buy-tickets/) | Easy | 6 months | 5.0 | ✅ Solved |  |  |  | [notes](06.%20Queue%20Basics/2073.%20Time%20Needed%20to%20Buy%20Tickets/2073.%20Time%20Needed%20to%20Buy%20Tickets.md) |
| 2 | [225. Implement Stack using Queues](https://leetcode.com/problems/implement-stack-using-queues/) | Easy | 6+ months | 24.5 | Todo |  |  |  | [notes](06.%20Queue%20Basics/0225.%20Implement%20Stack%20using%20Queues/0225.%20Implement%20Stack%20using%20Queues.md) |
| 3 | [232. Implement Queue using Stacks](https://leetcode.com/problems/implement-queue-using-stacks/) | Easy | 6+ months | 21.8 | Todo |  |  |  | [notes](06.%20Queue%20Basics/0232.%20Implement%20Queue%20using%20Stacks/0232.%20Implement%20Queue%20using%20Stacks.md) |
| 4 | [1700. Number of Students Unable to Eat Lunch](https://leetcode.com/problems/number-of-students-unable-to-eat-lunch/) | Easy | 6+ months | 8.0 | ✅ Solved |  |  |  | [notes](06.%20Queue%20Basics/1700.%20Number%20of%20Students%20Unable%20to%20Eat%20Lunch/1700.%20Number%20of%20Students%20Unable%20to%20Eat%20Lunch.md) |
| 5 | [649. Dota2 Senate](https://leetcode.com/problems/dota2-senate/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20Queue%20Basics/0649.%20Dota2%20Senate/0649.%20Dota2%20Senate.md) |

## 07. Stack Simulation (Asteroid, Path)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [735. Asteroid Collision](https://leetcode.com/problems/asteroid-collision/) | Medium | 3 months | 32.1 | ✅ Solved |  |  |  | [notes](07.%20Stack%20Simulation%20%28Asteroid%2C%20Path%29/0735.%20Asteroid%20Collision/0735.%20Asteroid%20Collision.md) |
| 2 | [71. Simplify Path](https://leetcode.com/problems/simplify-path/) | Medium | 6 months | 83.2 | Todo |  |  |  | [notes](07.%20Stack%20Simulation%20%28Asteroid%2C%20Path%29/0071.%20Simplify%20Path/0071.%20Simplify%20Path.md) |
| 3 | [636. Exclusive Time of Functions](https://leetcode.com/problems/exclusive-time-of-functions/) | Medium | 6+ months | 67.3 | Todo |  |  |  | [notes](07.%20Stack%20Simulation%20%28Asteroid%2C%20Path%29/0636.%20Exclusive%20Time%20of%20Functions/0636.%20Exclusive%20Time%20of%20Functions.md) |
| 4 | [946. Validate Stack Sequences](https://leetcode.com/problems/validate-stack-sequences/) | Medium | 6+ months | 13.4 | Todo |  |  |  | [notes](07.%20Stack%20Simulation%20%28Asteroid%2C%20Path%29/0946.%20Validate%20Stack%20Sequences/0946.%20Validate%20Stack%20Sequences.md) |
| 5 | [388. Longest Absolute File Path](https://leetcode.com/problems/longest-absolute-file-path/) | Medium | 6+ months | 9.4 | Todo |  |  |  | [notes](07.%20Stack%20Simulation%20%28Asteroid%2C%20Path%29/0388.%20Longest%20Absolute%20File%20Path/0388.%20Longest%20Absolute%20File%20Path.md) |
| 6 | [2434. Using a Robot to Print the Lexicographically Smallest String](https://leetcode.com/problems/using-a-robot-to-print-the-lexicographically-smallest-string/) | Medium | 6+ months | 8.2 | Todo |  |  |  | [notes](07.%20Stack%20Simulation%20%28Asteroid%2C%20Path%29/2434.%20Using%20a%20Robot%20to%20Print%20the%20Lexicographically%20Smallest%20String/2434.%20Using%20a%20Robot%20to%20Print%20the%20Lexicographically%20Smallest%20String.md) |
| 7 | [880. Decoded String at Index](https://leetcode.com/problems/decoded-string-at-index/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](07.%20Stack%20Simulation%20%28Asteroid%2C%20Path%29/0880.%20Decoded%20String%20at%20Index/0880.%20Decoded%20String%20at%20Index.md) |
| 8 | [2751. Robot Collisions](https://leetcode.com/problems/robot-collisions/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](07.%20Stack%20Simulation%20%28Asteroid%2C%20Path%29/2751.%20Robot%20Collisions/2751.%20Robot%20Collisions.md) |
