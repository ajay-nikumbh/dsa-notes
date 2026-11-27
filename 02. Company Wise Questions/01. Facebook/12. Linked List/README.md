# 12. Linked List - Meta (Facebook) Interview Questions

36 problems: 9 Easy, 26 Medium, 1 Hard. 7 sub-patterns.

[Back to Facebook](../README.md) · [Back to DSA Notes](../../../README.md)

## Sub-patterns

<table width="100%" style="width:100%">
<thead><tr><th>#</th><th>Name</th><th>Total</th><th>Easy</th><th>Medium</th><th>Hard</th><th>Last 30 Days</th><th>Last 3 Months</th><th>Last 6 Months</th><th>Solved</th></tr></thead>
<tbody>
<tr><td>1</td><td><a href="#01-traversal--basic-operations">Traversal &amp; Basic Operations</a></td><td>10</td><td>2</td><td>8</td><td>0</td><td>0</td><td>1</td><td>3</td><td>4</td></tr>
<tr><td>2</td><td><a href="#02-reversal">Reversal</a></td><td>4</td><td>1</td><td>2</td><td>1</td><td>0</td><td>1</td><td>3</td><td>2</td></tr>
<tr><td>3</td><td><a href="#03-fast--slow-pointers">Fast &amp; Slow Pointers</a></td><td>11</td><td>4</td><td>7</td><td>0</td><td>0</td><td>0</td><td>8</td><td>9</td></tr>
<tr><td>4</td><td><a href="#04-merge--sort-lists">Merge &amp; Sort Lists</a></td><td>3</td><td>1</td><td>2</td><td>0</td><td>0</td><td>1</td><td>2</td><td>2</td></tr>
<tr><td>5</td><td><a href="#05-dummy-node--deletion">Dummy Node &amp; Deletion</a></td><td>5</td><td>1</td><td>4</td><td>0</td><td>0</td><td>0</td><td>2</td><td>2</td></tr>
<tr><td>6</td><td><a href="#06-add-numbers-in-lists">Add Numbers in Lists</a></td><td>2</td><td>0</td><td>2</td><td>0</td><td>0</td><td>1</td><td>1</td><td>1</td></tr>
<tr><td>7</td><td><a href="#07-copy--clone-list">Copy &amp; Clone List</a></td><td>1</td><td>0</td><td>1</td><td>0</td><td>0</td><td>0</td><td>0</td><td>1</td></tr>
</tbody>
</table>

**Columns**

- **Last Asked**: most recent LeetCode window that lists the problem for Meta.
- **30 Days / 3 Months / 6 Months / 6+ Months**: ✅ when the problem appears in that window's list.
- **Frequency**: LeetCode frequency score (0-100) in the Meta "All" list.
- **Premium**: 🔒 means LeetCode Premium problem.
- **Status**: your LeetCode status on the day this file was generated.
- **Logic / Key Idea**: one-line approach, for example "monotonic stack of indices" (you fill it in).
- **Time / Space**: time and space complexity, for example `O(n)` / `O(1)` (you fill it in).
- **Date Solved / Revisions / Confidence / Remarks**: your own tracking (you fill it in). Confidence can be Low, Medium or High.
- **Notes**: link to the problem's notes file.

Fill the hand-written columns in this file or in a chapter README. A rebuild keeps what you typed.

Within each sub-pattern, rows are sorted by most recent window, then by frequency (highest first).

## 01. Traversal & Basic Operations

<table width="100%" style="width:100%">
<thead><tr><th>#</th><th>Problem</th><th>Difficulty</th><th>Sub-pattern</th><th>Last Asked</th><th>30 Days</th><th>3 Months</th><th>6 Months</th><th>6+ Months</th><th>Frequency</th><th>Premium</th><th>Status</th><th>Logic / Key Idea</th><th>Time</th><th>Space</th><th>Date Solved</th><th>Revisions</th><th>Confidence</th><th>Remarks</th><th>Topic Tags</th><th>Notes</th></tr></thead>
<tbody>
<tr><td>1</td><td><a href="https://leetcode.com/problems/delete-node-in-a-linked-list/">237. Delete Node in a Linked List</a></td><td>Medium</td><td>Traversal &amp; Basic Operations</td><td>Last 3 months</td><td></td><td>✅</td><td>✅</td><td>✅</td><td>29.4</td><td></td><td>Solved</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Linked List</td><td><a href="01.%20Traversal%20%26%20Basic%20Operations/0237.%20Delete%20Node%20in%20a%20Linked%20List/0237.%20Delete%20Node%20in%20a%20Linked%20List.md">notes</a></td></tr>
<tr><td>2</td><td><a href="https://leetcode.com/problems/rotate-list/">61. Rotate List</a></td><td>Medium</td><td>Traversal &amp; Basic Operations</td><td>Last 6 months</td><td></td><td></td><td>✅</td><td>✅</td><td>33.0</td><td></td><td>Todo</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Linked List, Two Pointers</td><td><a href="01.%20Traversal%20%26%20Basic%20Operations/0061.%20Rotate%20List/0061.%20Rotate%20List.md">notes</a></td></tr>
<tr><td>3</td><td><a href="https://leetcode.com/problems/remove-duplicates-from-sorted-list/">83. Remove Duplicates from Sorted List</a></td><td>Easy</td><td>Traversal &amp; Basic Operations</td><td>Last 6 months</td><td></td><td></td><td>✅</td><td>✅</td><td>23.8</td><td></td><td>Solved</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Linked List</td><td><a href="01.%20Traversal%20%26%20Basic%20Operations/0083.%20Remove%20Duplicates%20from%20Sorted%20List/0083.%20Remove%20Duplicates%20from%20Sorted%20List.md">notes</a></td></tr>
<tr><td>4</td><td><a href="https://leetcode.com/problems/insert-into-a-sorted-circular-linked-list/">708. Insert into a Sorted Circular Linked List</a></td><td>Medium</td><td>Traversal &amp; Basic Operations</td><td>More than 6 months</td><td></td><td></td><td></td><td>✅</td><td>58.7</td><td>🔒</td><td>Todo</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Linked List</td><td><a href="01.%20Traversal%20%26%20Basic%20Operations/0708.%20Insert%20into%20a%20Sorted%20Circular%20Linked%20List/0708.%20Insert%20into%20a%20Sorted%20Circular%20Linked%20List.md">notes</a></td></tr>
<tr><td>5</td><td><a href="https://leetcode.com/problems/odd-even-linked-list/">328. Odd Even Linked List</a></td><td>Medium</td><td>Traversal &amp; Basic Operations</td><td>More than 6 months</td><td></td><td></td><td></td><td>✅</td><td>25.2</td><td></td><td>Solved</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Linked List</td><td><a href="01.%20Traversal%20%26%20Basic%20Operations/0328.%20Odd%20Even%20Linked%20List/0328.%20Odd%20Even%20Linked%20List.md">notes</a></td></tr>
<tr><td>6</td><td><a href="https://leetcode.com/problems/flatten-a-multilevel-doubly-linked-list/">430. Flatten a Multilevel Doubly Linked List</a></td><td>Medium</td><td>Traversal &amp; Basic Operations</td><td>More than 6 months</td><td></td><td></td><td></td><td>✅</td><td>12.3</td><td></td><td>Todo</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Linked List, Depth-First Search, Doubly-Linked List</td><td><a href="01.%20Traversal%20%26%20Basic%20Operations/0430.%20Flatten%20a%20Multilevel%20Doubly%20Linked%20List/0430.%20Flatten%20a%20Multilevel%20Doubly%20Linked%20List.md">notes</a></td></tr>
<tr><td>7</td><td><a href="https://leetcode.com/problems/split-linked-list-in-parts/">725. Split Linked List in Parts</a></td><td>Medium</td><td>Traversal &amp; Basic Operations</td><td>More than 6 months</td><td></td><td></td><td></td><td>✅</td><td>10.0</td><td></td><td>Todo</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Linked List</td><td><a href="01.%20Traversal%20%26%20Basic%20Operations/0725.%20Split%20Linked%20List%20in%20Parts/0725.%20Split%20Linked%20List%20in%20Parts.md">notes</a></td></tr>
<tr><td>8</td><td><a href="https://leetcode.com/problems/find-the-minimum-and-maximum-number-of-nodes-between-critical-points/">2058. Find the Minimum and Maximum Number of Nodes Between Critical Points</a></td><td>Medium</td><td>Traversal &amp; Basic Operations</td><td>More than 6 months</td><td></td><td></td><td></td><td>✅</td><td>8.0</td><td></td><td>Todo</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Linked List</td><td><a href="01.%20Traversal%20%26%20Basic%20Operations/2058.%20Find%20the%20Minimum%20and%20Maximum%20Number%20of%20Nodes%20Between%20Critical%20Points/2058.%20Find%20the%20Minimum%20and%20Maximum%20Number%20of%20Nodes%20Between%20Critical%20Points.md">notes</a></td></tr>
<tr><td>9</td><td><a href="https://leetcode.com/problems/convert-binary-number-in-a-linked-list-to-integer/">1290. Convert Binary Number in a Linked List to Integer</a></td><td>Easy</td><td>Traversal &amp; Basic Operations</td><td>More than 6 months</td><td></td><td></td><td></td><td>✅</td><td>5.0</td><td></td><td>Solved</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Linked List, Math</td><td><a href="01.%20Traversal%20%26%20Basic%20Operations/1290.%20Convert%20Binary%20Number%20in%20a%20Linked%20List%20to%20Integer/1290.%20Convert%20Binary%20Number%20in%20a%20Linked%20List%20to%20Integer.md">notes</a></td></tr>
<tr><td>10</td><td><a href="https://leetcode.com/problems/insert-greatest-common-divisors-in-linked-list/">2807. Insert Greatest Common Divisors in Linked List</a></td><td>Medium</td><td>Traversal &amp; Basic Operations</td><td>More than 6 months</td><td></td><td></td><td></td><td>✅</td><td>5.0</td><td></td><td>Todo</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Linked List, Math, Number Theory</td><td><a href="01.%20Traversal%20%26%20Basic%20Operations/2807.%20Insert%20Greatest%20Common%20Divisors%20in%20Linked%20List/2807.%20Insert%20Greatest%20Common%20Divisors%20in%20Linked%20List.md">notes</a></td></tr>
</tbody>
</table>

## 02. Reversal

<table width="100%" style="width:100%">
<thead><tr><th>#</th><th>Problem</th><th>Difficulty</th><th>Sub-pattern</th><th>Last Asked</th><th>30 Days</th><th>3 Months</th><th>6 Months</th><th>6+ Months</th><th>Frequency</th><th>Premium</th><th>Status</th><th>Logic / Key Idea</th><th>Time</th><th>Space</th><th>Date Solved</th><th>Revisions</th><th>Confidence</th><th>Remarks</th><th>Topic Tags</th><th>Notes</th></tr></thead>
<tbody>
<tr><td>1</td><td><a href="https://leetcode.com/problems/reverse-linked-list/">206. Reverse Linked List</a></td><td>Easy</td><td>Reversal</td><td>Last 3 months</td><td></td><td>✅</td><td>✅</td><td>✅</td><td>50.8</td><td></td><td>Solved</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Linked List, Recursion</td><td><a href="02.%20Reversal/0206.%20Reverse%20Linked%20List/0206.%20Reverse%20Linked%20List.md">notes</a></td></tr>
<tr><td>2</td><td><a href="https://leetcode.com/problems/reverse-nodes-in-k-group/">25. Reverse Nodes in k-Group</a></td><td>Hard</td><td>Reversal</td><td>Last 6 months</td><td></td><td></td><td>✅</td><td>✅</td><td>45.3</td><td></td><td>Solved</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Linked List, Recursion</td><td><a href="02.%20Reversal/0025.%20Reverse%20Nodes%20in%20k-Group/0025.%20Reverse%20Nodes%20in%20k-Group.md">notes</a></td></tr>
<tr><td>3</td><td><a href="https://leetcode.com/problems/reverse-linked-list-ii/">92. Reverse Linked List II</a></td><td>Medium</td><td>Reversal</td><td>Last 6 months</td><td></td><td></td><td>✅</td><td>✅</td><td>28.6</td><td></td><td>Todo</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Linked List</td><td><a href="02.%20Reversal/0092.%20Reverse%20Linked%20List%20II/0092.%20Reverse%20Linked%20List%20II.md">notes</a></td></tr>
<tr><td>4</td><td><a href="https://leetcode.com/problems/reverse-nodes-in-even-length-groups/">2074. Reverse Nodes in Even Length Groups</a></td><td>Medium</td><td>Reversal</td><td>More than 6 months</td><td></td><td></td><td></td><td>✅</td><td>5.0</td><td></td><td>Todo</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Linked List</td><td><a href="02.%20Reversal/2074.%20Reverse%20Nodes%20in%20Even%20Length%20Groups/2074.%20Reverse%20Nodes%20in%20Even%20Length%20Groups.md">notes</a></td></tr>
</tbody>
</table>

## 03. Fast & Slow Pointers

<table width="100%" style="width:100%">
<thead><tr><th>#</th><th>Problem</th><th>Difficulty</th><th>Sub-pattern</th><th>Last Asked</th><th>30 Days</th><th>3 Months</th><th>6 Months</th><th>6+ Months</th><th>Frequency</th><th>Premium</th><th>Status</th><th>Logic / Key Idea</th><th>Time</th><th>Space</th><th>Date Solved</th><th>Revisions</th><th>Confidence</th><th>Remarks</th><th>Topic Tags</th><th>Notes</th></tr></thead>
<tbody>
<tr><td>1</td><td><a href="https://leetcode.com/problems/remove-nth-node-from-end-of-list/">19. Remove Nth Node From End of List</a></td><td>Medium</td><td>Fast &amp; Slow Pointers</td><td>Last 6 months</td><td></td><td></td><td>✅</td><td>✅</td><td>61.8</td><td></td><td>Solved</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Linked List, Two Pointers</td><td><a href="03.%20Fast%20%26%20Slow%20Pointers/0019.%20Remove%20Nth%20Node%20From%20End%20of%20List/0019.%20Remove%20Nth%20Node%20From%20End%20of%20List.md">notes</a></td></tr>
<tr><td>2</td><td><a href="https://leetcode.com/problems/palindrome-linked-list/">234. Palindrome Linked List</a></td><td>Easy</td><td>Fast &amp; Slow Pointers</td><td>Last 6 months</td><td></td><td></td><td>✅</td><td>✅</td><td>53.0</td><td></td><td>Solved</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Linked List, Two Pointers, Stack, Recursion</td><td><a href="03.%20Fast%20%26%20Slow%20Pointers/0234.%20Palindrome%20Linked%20List/0234.%20Palindrome%20Linked%20List.md">notes</a></td></tr>
<tr><td>3</td><td><a href="https://leetcode.com/problems/linked-list-cycle/">141. Linked List Cycle</a></td><td>Easy</td><td>Fast &amp; Slow Pointers</td><td>Last 6 months</td><td></td><td></td><td>✅</td><td>✅</td><td>42.0</td><td></td><td>Solved</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Hash Table, Linked List, Two Pointers, Floyd&#x27;s Cycle Finding Algorithm</td><td><a href="03.%20Fast%20%26%20Slow%20Pointers/0141.%20Linked%20List%20Cycle/0141.%20Linked%20List%20Cycle.md">notes</a></td></tr>
<tr><td>4</td><td><a href="https://leetcode.com/problems/reorder-list/">143. Reorder List</a></td><td>Medium</td><td>Fast &amp; Slow Pointers</td><td>Last 6 months</td><td></td><td></td><td>✅</td><td>✅</td><td>36.0</td><td></td><td>Solved</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Linked List, Two Pointers, Stack, Recursion</td><td><a href="03.%20Fast%20%26%20Slow%20Pointers/0143.%20Reorder%20List/0143.%20Reorder%20List.md">notes</a></td></tr>
<tr><td>5</td><td><a href="https://leetcode.com/problems/middle-of-the-linked-list/">876. Middle of the Linked List</a></td><td>Easy</td><td>Fast &amp; Slow Pointers</td><td>Last 6 months</td><td></td><td></td><td>✅</td><td>✅</td><td>32.6</td><td></td><td>Solved</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Linked List, Two Pointers</td><td><a href="03.%20Fast%20%26%20Slow%20Pointers/0876.%20Middle%20of%20the%20Linked%20List/0876.%20Middle%20of%20the%20Linked%20List.md">notes</a></td></tr>
<tr><td>6</td><td><a href="https://leetcode.com/problems/intersection-of-two-linked-lists/">160. Intersection of Two Linked Lists</a></td><td>Easy</td><td>Fast &amp; Slow Pointers</td><td>Last 6 months</td><td></td><td></td><td>✅</td><td>✅</td><td>28.3</td><td></td><td>Solved</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Hash Table, Linked List, Two Pointers</td><td><a href="03.%20Fast%20%26%20Slow%20Pointers/0160.%20Intersection%20of%20Two%20Linked%20Lists/0160.%20Intersection%20of%20Two%20Linked%20Lists.md">notes</a></td></tr>
<tr><td>7</td><td><a href="https://leetcode.com/problems/find-the-duplicate-number/">287. Find the Duplicate Number</a></td><td>Medium</td><td>Fast &amp; Slow Pointers</td><td>Last 6 months</td><td></td><td></td><td>✅</td><td>✅</td><td>27.0</td><td></td><td>Solved</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Array, Two Pointers, Binary Search, Bit Manipulation, Pigeonhole Principle, Floyd&#x27;s Cycle Finding Algorithm</td><td><a href="03.%20Fast%20%26%20Slow%20Pointers/0287.%20Find%20the%20Duplicate%20Number/0287.%20Find%20the%20Duplicate%20Number.md">notes</a></td></tr>
<tr><td>8</td><td><a href="https://leetcode.com/problems/linked-list-cycle-ii/">142. Linked List Cycle II</a></td><td>Medium</td><td>Fast &amp; Slow Pointers</td><td>Last 6 months</td><td></td><td></td><td>✅</td><td>✅</td><td>22.8</td><td></td><td>Solved</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Hash Table, Linked List, Two Pointers, Floyd&#x27;s Cycle Finding Algorithm</td><td><a href="03.%20Fast%20%26%20Slow%20Pointers/0142.%20Linked%20List%20Cycle%20II/0142.%20Linked%20List%20Cycle%20II.md">notes</a></td></tr>
<tr><td>9</td><td><a href="https://leetcode.com/problems/delete-the-middle-node-of-a-linked-list/">2095. Delete the Middle Node of a Linked List</a></td><td>Medium</td><td>Fast &amp; Slow Pointers</td><td>More than 6 months</td><td></td><td></td><td></td><td>✅</td><td>5.7</td><td></td><td>Solved</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Linked List, Two Pointers</td><td><a href="03.%20Fast%20%26%20Slow%20Pointers/2095.%20Delete%20the%20Middle%20Node%20of%20a%20Linked%20List/2095.%20Delete%20the%20Middle%20Node%20of%20a%20Linked%20List.md">notes</a></td></tr>
<tr><td>10</td><td><a href="https://leetcode.com/problems/swapping-nodes-in-a-linked-list/">1721. Swapping Nodes in a Linked List</a></td><td>Medium</td><td>Fast &amp; Slow Pointers</td><td>More than 6 months</td><td></td><td></td><td></td><td>✅</td><td>5.0</td><td></td><td>Todo</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Linked List, Two Pointers</td><td><a href="03.%20Fast%20%26%20Slow%20Pointers/1721.%20Swapping%20Nodes%20in%20a%20Linked%20List/1721.%20Swapping%20Nodes%20in%20a%20Linked%20List.md">notes</a></td></tr>
<tr><td>11</td><td><a href="https://leetcode.com/problems/maximum-twin-sum-of-a-linked-list/">2130. Maximum Twin Sum of a Linked List</a></td><td>Medium</td><td>Fast &amp; Slow Pointers</td><td>More than 6 months</td><td></td><td></td><td></td><td>✅</td><td>5.0</td><td></td><td>Todo</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Linked List, Two Pointers, Stack</td><td><a href="03.%20Fast%20%26%20Slow%20Pointers/2130.%20Maximum%20Twin%20Sum%20of%20a%20Linked%20List/2130.%20Maximum%20Twin%20Sum%20of%20a%20Linked%20List.md">notes</a></td></tr>
</tbody>
</table>

## 04. Merge & Sort Lists

<table width="100%" style="width:100%">
<thead><tr><th>#</th><th>Problem</th><th>Difficulty</th><th>Sub-pattern</th><th>Last Asked</th><th>30 Days</th><th>3 Months</th><th>6 Months</th><th>6+ Months</th><th>Frequency</th><th>Premium</th><th>Status</th><th>Logic / Key Idea</th><th>Time</th><th>Space</th><th>Date Solved</th><th>Revisions</th><th>Confidence</th><th>Remarks</th><th>Topic Tags</th><th>Notes</th></tr></thead>
<tbody>
<tr><td>1</td><td><a href="https://leetcode.com/problems/merge-two-sorted-lists/">21. Merge Two Sorted Lists</a></td><td>Easy</td><td>Merge &amp; Sort Lists</td><td>Last 3 months</td><td></td><td>✅</td><td>✅</td><td>✅</td><td>53.2</td><td></td><td>Solved</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Linked List, Recursion</td><td><a href="04.%20Merge%20%26%20Sort%20Lists/0021.%20Merge%20Two%20Sorted%20Lists/0021.%20Merge%20Two%20Sorted%20Lists.md">notes</a></td></tr>
<tr><td>2</td><td><a href="https://leetcode.com/problems/sort-list/">148. Sort List</a></td><td>Medium</td><td>Merge &amp; Sort Lists</td><td>Last 6 months</td><td></td><td></td><td>✅</td><td>✅</td><td>34.5</td><td></td><td>Solved</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Linked List, Two Pointers, Divide and Conquer, Sorting, Merge Sort</td><td><a href="04.%20Merge%20%26%20Sort%20Lists/0148.%20Sort%20List/0148.%20Sort%20List.md">notes</a></td></tr>
<tr><td>3</td><td><a href="https://leetcode.com/problems/insertion-sort-list/">147. Insertion Sort List</a></td><td>Medium</td><td>Merge &amp; Sort Lists</td><td>More than 6 months</td><td></td><td></td><td></td><td>✅</td><td>5.0</td><td></td><td>Todo</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Linked List, Sorting</td><td><a href="04.%20Merge%20%26%20Sort%20Lists/0147.%20Insertion%20Sort%20List/0147.%20Insertion%20Sort%20List.md">notes</a></td></tr>
</tbody>
</table>

## 05. Dummy Node & Deletion

<table width="100%" style="width:100%">
<thead><tr><th>#</th><th>Problem</th><th>Difficulty</th><th>Sub-pattern</th><th>Last Asked</th><th>30 Days</th><th>3 Months</th><th>6 Months</th><th>6+ Months</th><th>Frequency</th><th>Premium</th><th>Status</th><th>Logic / Key Idea</th><th>Time</th><th>Space</th><th>Date Solved</th><th>Revisions</th><th>Confidence</th><th>Remarks</th><th>Topic Tags</th><th>Notes</th></tr></thead>
<tbody>
<tr><td>1</td><td><a href="https://leetcode.com/problems/swap-nodes-in-pairs/">24. Swap Nodes in Pairs</a></td><td>Medium</td><td>Dummy Node &amp; Deletion</td><td>Last 6 months</td><td></td><td></td><td>✅</td><td>✅</td><td>24.6</td><td></td><td>Todo</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Linked List, Recursion</td><td><a href="05.%20Dummy%20Node%20%26%20Deletion/0024.%20Swap%20Nodes%20in%20Pairs/0024.%20Swap%20Nodes%20in%20Pairs.md">notes</a></td></tr>
<tr><td>2</td><td><a href="https://leetcode.com/problems/remove-linked-list-elements/">203. Remove Linked List Elements</a></td><td>Easy</td><td>Dummy Node &amp; Deletion</td><td>Last 6 months</td><td></td><td></td><td>✅</td><td>✅</td><td>17.6</td><td></td><td>Solved</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Linked List, Recursion</td><td><a href="05.%20Dummy%20Node%20%26%20Deletion/0203.%20Remove%20Linked%20List%20Elements/0203.%20Remove%20Linked%20List%20Elements.md">notes</a></td></tr>
<tr><td>3</td><td><a href="https://leetcode.com/problems/partition-list/">86. Partition List</a></td><td>Medium</td><td>Dummy Node &amp; Deletion</td><td>More than 6 months</td><td></td><td></td><td></td><td>✅</td><td>12.5</td><td></td><td>Todo</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Linked List, Two Pointers</td><td><a href="05.%20Dummy%20Node%20%26%20Deletion/0086.%20Partition%20List/0086.%20Partition%20List.md">notes</a></td></tr>
<tr><td>4</td><td><a href="https://leetcode.com/problems/remove-duplicates-from-sorted-list-ii/">82. Remove Duplicates from Sorted List II</a></td><td>Medium</td><td>Dummy Node &amp; Deletion</td><td>More than 6 months</td><td></td><td></td><td></td><td>✅</td><td>5.0</td><td></td><td>Todo</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Linked List, Two Pointers</td><td><a href="05.%20Dummy%20Node%20%26%20Deletion/0082.%20Remove%20Duplicates%20from%20Sorted%20List%20II/0082.%20Remove%20Duplicates%20from%20Sorted%20List%20II.md">notes</a></td></tr>
<tr><td>5</td><td><a href="https://leetcode.com/problems/delete-nodes-from-linked-list-present-in-array/">3217. Delete Nodes From Linked List Present in Array</a></td><td>Medium</td><td>Dummy Node &amp; Deletion</td><td>More than 6 months</td><td></td><td></td><td></td><td>✅</td><td>5.0</td><td></td><td>Solved</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Array, Hash Table, Linked List</td><td><a href="05.%20Dummy%20Node%20%26%20Deletion/3217.%20Delete%20Nodes%20From%20Linked%20List%20Present%20in%20Array/3217.%20Delete%20Nodes%20From%20Linked%20List%20Present%20in%20Array.md">notes</a></td></tr>
</tbody>
</table>

## 06. Add Numbers in Lists

<table width="100%" style="width:100%">
<thead><tr><th>#</th><th>Problem</th><th>Difficulty</th><th>Sub-pattern</th><th>Last Asked</th><th>30 Days</th><th>3 Months</th><th>6 Months</th><th>6+ Months</th><th>Frequency</th><th>Premium</th><th>Status</th><th>Logic / Key Idea</th><th>Time</th><th>Space</th><th>Date Solved</th><th>Revisions</th><th>Confidence</th><th>Remarks</th><th>Topic Tags</th><th>Notes</th></tr></thead>
<tbody>
<tr><td>1</td><td><a href="https://leetcode.com/problems/add-two-numbers/">2. Add Two Numbers</a></td><td>Medium</td><td>Add Numbers in Lists</td><td>Last 3 months</td><td></td><td>✅</td><td>✅</td><td>✅</td><td>65.3</td><td></td><td>Solved</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Linked List, Math, Recursion</td><td><a href="06.%20Add%20Numbers%20in%20Lists/0002.%20Add%20Two%20Numbers/0002.%20Add%20Two%20Numbers.md">notes</a></td></tr>
<tr><td>2</td><td><a href="https://leetcode.com/problems/add-two-numbers-ii/">445. Add Two Numbers II</a></td><td>Medium</td><td>Add Numbers in Lists</td><td>More than 6 months</td><td></td><td></td><td></td><td>✅</td><td>8.2</td><td></td><td>Todo</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Linked List, Math, Stack</td><td><a href="06.%20Add%20Numbers%20in%20Lists/0445.%20Add%20Two%20Numbers%20II/0445.%20Add%20Two%20Numbers%20II.md">notes</a></td></tr>
</tbody>
</table>

## 07. Copy & Clone List

<table width="100%" style="width:100%">
<thead><tr><th>#</th><th>Problem</th><th>Difficulty</th><th>Sub-pattern</th><th>Last Asked</th><th>30 Days</th><th>3 Months</th><th>6 Months</th><th>6+ Months</th><th>Frequency</th><th>Premium</th><th>Status</th><th>Logic / Key Idea</th><th>Time</th><th>Space</th><th>Date Solved</th><th>Revisions</th><th>Confidence</th><th>Remarks</th><th>Topic Tags</th><th>Notes</th></tr></thead>
<tbody>
<tr><td>1</td><td><a href="https://leetcode.com/problems/copy-list-with-random-pointer/">138. Copy List with Random Pointer</a></td><td>Medium</td><td>Copy &amp; Clone List</td><td>More than 6 months</td><td></td><td></td><td></td><td>✅</td><td>74.7</td><td></td><td>Solved</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Hash Table, Linked List</td><td><a href="07.%20Copy%20%26%20Clone%20List/0138.%20Copy%20List%20with%20Random%20Pointer/0138.%20Copy%20List%20with%20Random%20Pointer.md">notes</a></td></tr>
</tbody>
</table>
