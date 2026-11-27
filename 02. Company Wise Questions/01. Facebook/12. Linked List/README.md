# 12. Linked List

[Back to Facebook](../README.md) · [Back to DSA Notes](../../../README.md)

36 Meta (Facebook) problems: 9 Easy, 26 Medium, 1 Hard, in 7 sub-patterns.

## Sub-patterns

| # | Sub-pattern | Questions | Easy | Medium | Hard | Last 3 Months | Solved | Most Asked |
|:---:|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---|
| 01 | [Traversal & Basic Operations](#01-traversal--basic-operations) | 10 | 2 | 8 | 0 | 1 | 4 | 708. Insert into a Sorted Circular Linked List, 61. Rotate List, 237. Delete Node in a Linked List |
| 02 | [Reversal](#02-reversal) | 4 | 1 | 2 | 1 | 1 | 2 | 206. Reverse Linked List, 25. Reverse Nodes in k-Group, 92. Reverse Linked List II |
| 03 | [Fast & Slow Pointers](#03-fast--slow-pointers) | 11 | 4 | 7 | 0 | 0 | 9 | 19. Remove Nth Node From End of List, 234. Palindrome Linked List, 141. Linked List Cycle |
| 04 | [Merge & Sort Lists](#04-merge--sort-lists) | 3 | 1 | 2 | 0 | 1 | 2 | 21. Merge Two Sorted Lists, 148. Sort List, 147. Insertion Sort List |
| 05 | [Dummy Node & Deletion](#05-dummy-node--deletion) | 5 | 1 | 4 | 0 | 0 | 2 | 24. Swap Nodes in Pairs, 203. Remove Linked List Elements, 86. Partition List |
| 06 | [Add Numbers in Lists](#06-add-numbers-in-lists) | 2 | 0 | 2 | 0 | 1 | 1 | 2. Add Two Numbers, 445. Add Two Numbers II |
| 07 | [Copy & Clone List](#07-copy--clone-list) | 1 | 0 | 1 | 0 | 0 | 1 | 138. Copy List with Random Pointer |

**Columns**

- **Last Asked**: most recent LeetCode window that lists the problem for Meta (30 days, 3 months, 6 months or 6+ months).
- **Frequency**: LeetCode frequency score (0-100) in the Meta "All" list.
- **Status**: your LeetCode status on the day this file was generated. 🔒 after a title means LeetCode Premium.
- **Logic / Key Idea, Time, Space**: fill these in as you solve. A rebuild keeps what you typed.
- **Notes**: link to the problem's notes file.

Inside each sub-pattern, rows are sorted by most recent window, then by frequency (highest first).

## 01. Traversal & Basic Operations

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [237. Delete Node in a Linked List](https://leetcode.com/problems/delete-node-in-a-linked-list/) | Medium | 3 months | 29.4 | ✅ Solved |  |  |  | [notes](01.%20Traversal%20%26%20Basic%20Operations/0237.%20Delete%20Node%20in%20a%20Linked%20List/0237.%20Delete%20Node%20in%20a%20Linked%20List.md) |
| 2 | [61. Rotate List](https://leetcode.com/problems/rotate-list/) | Medium | 6 months | 33.0 | Todo |  |  |  | [notes](01.%20Traversal%20%26%20Basic%20Operations/0061.%20Rotate%20List/0061.%20Rotate%20List.md) |
| 3 | [83. Remove Duplicates from Sorted List](https://leetcode.com/problems/remove-duplicates-from-sorted-list/) | Easy | 6 months | 23.8 | ✅ Solved |  |  |  | [notes](01.%20Traversal%20%26%20Basic%20Operations/0083.%20Remove%20Duplicates%20from%20Sorted%20List/0083.%20Remove%20Duplicates%20from%20Sorted%20List.md) |
| 4 | [708. Insert into a Sorted Circular Linked List](https://leetcode.com/problems/insert-into-a-sorted-circular-linked-list/) 🔒 | Medium | 6+ months | 58.7 | Todo |  |  |  | [notes](01.%20Traversal%20%26%20Basic%20Operations/0708.%20Insert%20into%20a%20Sorted%20Circular%20Linked%20List/0708.%20Insert%20into%20a%20Sorted%20Circular%20Linked%20List.md) |
| 5 | [328. Odd Even Linked List](https://leetcode.com/problems/odd-even-linked-list/) | Medium | 6+ months | 25.2 | ✅ Solved |  |  |  | [notes](01.%20Traversal%20%26%20Basic%20Operations/0328.%20Odd%20Even%20Linked%20List/0328.%20Odd%20Even%20Linked%20List.md) |
| 6 | [430. Flatten a Multilevel Doubly Linked List](https://leetcode.com/problems/flatten-a-multilevel-doubly-linked-list/) | Medium | 6+ months | 12.3 | Todo |  |  |  | [notes](01.%20Traversal%20%26%20Basic%20Operations/0430.%20Flatten%20a%20Multilevel%20Doubly%20Linked%20List/0430.%20Flatten%20a%20Multilevel%20Doubly%20Linked%20List.md) |
| 7 | [725. Split Linked List in Parts](https://leetcode.com/problems/split-linked-list-in-parts/) | Medium | 6+ months | 10.0 | Todo |  |  |  | [notes](01.%20Traversal%20%26%20Basic%20Operations/0725.%20Split%20Linked%20List%20in%20Parts/0725.%20Split%20Linked%20List%20in%20Parts.md) |
| 8 | [2058. Find the Minimum and Maximum Number of Nodes Between Critical Points](https://leetcode.com/problems/find-the-minimum-and-maximum-number-of-nodes-between-critical-points/) | Medium | 6+ months | 8.0 | Todo |  |  |  | [notes](01.%20Traversal%20%26%20Basic%20Operations/2058.%20Find%20the%20Minimum%20and%20Maximum%20Number%20of%20Nodes%20Between%20Critical%20Points/2058.%20Find%20the%20Minimum%20and%20Maximum%20Number%20of%20Nodes%20Between%20Critical%20Points.md) |
| 9 | [1290. Convert Binary Number in a Linked List to Integer](https://leetcode.com/problems/convert-binary-number-in-a-linked-list-to-integer/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](01.%20Traversal%20%26%20Basic%20Operations/1290.%20Convert%20Binary%20Number%20in%20a%20Linked%20List%20to%20Integer/1290.%20Convert%20Binary%20Number%20in%20a%20Linked%20List%20to%20Integer.md) |
| 10 | [2807. Insert Greatest Common Divisors in Linked List](https://leetcode.com/problems/insert-greatest-common-divisors-in-linked-list/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Traversal%20%26%20Basic%20Operations/2807.%20Insert%20Greatest%20Common%20Divisors%20in%20Linked%20List/2807.%20Insert%20Greatest%20Common%20Divisors%20in%20Linked%20List.md) |

## 02. Reversal

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [206. Reverse Linked List](https://leetcode.com/problems/reverse-linked-list/) | Easy | 3 months | 50.8 | ✅ Solved |  |  |  | [notes](02.%20Reversal/0206.%20Reverse%20Linked%20List/0206.%20Reverse%20Linked%20List.md) |
| 2 | [25. Reverse Nodes in k-Group](https://leetcode.com/problems/reverse-nodes-in-k-group/) | Hard | 6 months | 45.3 | ✅ Solved |  |  |  | [notes](02.%20Reversal/0025.%20Reverse%20Nodes%20in%20k-Group/0025.%20Reverse%20Nodes%20in%20k-Group.md) |
| 3 | [92. Reverse Linked List II](https://leetcode.com/problems/reverse-linked-list-ii/) | Medium | 6 months | 28.6 | Todo |  |  |  | [notes](02.%20Reversal/0092.%20Reverse%20Linked%20List%20II/0092.%20Reverse%20Linked%20List%20II.md) |
| 4 | [2074. Reverse Nodes in Even Length Groups](https://leetcode.com/problems/reverse-nodes-in-even-length-groups/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Reversal/2074.%20Reverse%20Nodes%20in%20Even%20Length%20Groups/2074.%20Reverse%20Nodes%20in%20Even%20Length%20Groups.md) |

## 03. Fast & Slow Pointers

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [19. Remove Nth Node From End of List](https://leetcode.com/problems/remove-nth-node-from-end-of-list/) | Medium | 6 months | 61.8 | ✅ Solved |  |  |  | [notes](03.%20Fast%20%26%20Slow%20Pointers/0019.%20Remove%20Nth%20Node%20From%20End%20of%20List/0019.%20Remove%20Nth%20Node%20From%20End%20of%20List.md) |
| 2 | [234. Palindrome Linked List](https://leetcode.com/problems/palindrome-linked-list/) | Easy | 6 months | 53.0 | ✅ Solved |  |  |  | [notes](03.%20Fast%20%26%20Slow%20Pointers/0234.%20Palindrome%20Linked%20List/0234.%20Palindrome%20Linked%20List.md) |
| 3 | [141. Linked List Cycle](https://leetcode.com/problems/linked-list-cycle/) | Easy | 6 months | 42.0 | ✅ Solved |  |  |  | [notes](03.%20Fast%20%26%20Slow%20Pointers/0141.%20Linked%20List%20Cycle/0141.%20Linked%20List%20Cycle.md) |
| 4 | [143. Reorder List](https://leetcode.com/problems/reorder-list/) | Medium | 6 months | 36.0 | ✅ Solved |  |  |  | [notes](03.%20Fast%20%26%20Slow%20Pointers/0143.%20Reorder%20List/0143.%20Reorder%20List.md) |
| 5 | [876. Middle of the Linked List](https://leetcode.com/problems/middle-of-the-linked-list/) | Easy | 6 months | 32.6 | ✅ Solved |  |  |  | [notes](03.%20Fast%20%26%20Slow%20Pointers/0876.%20Middle%20of%20the%20Linked%20List/0876.%20Middle%20of%20the%20Linked%20List.md) |
| 6 | [160. Intersection of Two Linked Lists](https://leetcode.com/problems/intersection-of-two-linked-lists/) | Easy | 6 months | 28.3 | ✅ Solved |  |  |  | [notes](03.%20Fast%20%26%20Slow%20Pointers/0160.%20Intersection%20of%20Two%20Linked%20Lists/0160.%20Intersection%20of%20Two%20Linked%20Lists.md) |
| 7 | [287. Find the Duplicate Number](https://leetcode.com/problems/find-the-duplicate-number/) | Medium | 6 months | 27.0 | ✅ Solved |  |  |  | [notes](03.%20Fast%20%26%20Slow%20Pointers/0287.%20Find%20the%20Duplicate%20Number/0287.%20Find%20the%20Duplicate%20Number.md) |
| 8 | [142. Linked List Cycle II](https://leetcode.com/problems/linked-list-cycle-ii/) | Medium | 6 months | 22.8 | ✅ Solved |  |  |  | [notes](03.%20Fast%20%26%20Slow%20Pointers/0142.%20Linked%20List%20Cycle%20II/0142.%20Linked%20List%20Cycle%20II.md) |
| 9 | [2095. Delete the Middle Node of a Linked List](https://leetcode.com/problems/delete-the-middle-node-of-a-linked-list/) | Medium | 6+ months | 5.7 | ✅ Solved |  |  |  | [notes](03.%20Fast%20%26%20Slow%20Pointers/2095.%20Delete%20the%20Middle%20Node%20of%20a%20Linked%20List/2095.%20Delete%20the%20Middle%20Node%20of%20a%20Linked%20List.md) |
| 10 | [1721. Swapping Nodes in a Linked List](https://leetcode.com/problems/swapping-nodes-in-a-linked-list/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](03.%20Fast%20%26%20Slow%20Pointers/1721.%20Swapping%20Nodes%20in%20a%20Linked%20List/1721.%20Swapping%20Nodes%20in%20a%20Linked%20List.md) |
| 11 | [2130. Maximum Twin Sum of a Linked List](https://leetcode.com/problems/maximum-twin-sum-of-a-linked-list/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](03.%20Fast%20%26%20Slow%20Pointers/2130.%20Maximum%20Twin%20Sum%20of%20a%20Linked%20List/2130.%20Maximum%20Twin%20Sum%20of%20a%20Linked%20List.md) |

## 04. Merge & Sort Lists

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [21. Merge Two Sorted Lists](https://leetcode.com/problems/merge-two-sorted-lists/) | Easy | 3 months | 53.2 | ✅ Solved |  |  |  | [notes](04.%20Merge%20%26%20Sort%20Lists/0021.%20Merge%20Two%20Sorted%20Lists/0021.%20Merge%20Two%20Sorted%20Lists.md) |
| 2 | [148. Sort List](https://leetcode.com/problems/sort-list/) | Medium | 6 months | 34.5 | ✅ Solved |  |  |  | [notes](04.%20Merge%20%26%20Sort%20Lists/0148.%20Sort%20List/0148.%20Sort%20List.md) |
| 3 | [147. Insertion Sort List](https://leetcode.com/problems/insertion-sort-list/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Merge%20%26%20Sort%20Lists/0147.%20Insertion%20Sort%20List/0147.%20Insertion%20Sort%20List.md) |

## 05. Dummy Node & Deletion

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [24. Swap Nodes in Pairs](https://leetcode.com/problems/swap-nodes-in-pairs/) | Medium | 6 months | 24.6 | Todo |  |  |  | [notes](05.%20Dummy%20Node%20%26%20Deletion/0024.%20Swap%20Nodes%20in%20Pairs/0024.%20Swap%20Nodes%20in%20Pairs.md) |
| 2 | [203. Remove Linked List Elements](https://leetcode.com/problems/remove-linked-list-elements/) | Easy | 6 months | 17.6 | ✅ Solved |  |  |  | [notes](05.%20Dummy%20Node%20%26%20Deletion/0203.%20Remove%20Linked%20List%20Elements/0203.%20Remove%20Linked%20List%20Elements.md) |
| 3 | [86. Partition List](https://leetcode.com/problems/partition-list/) | Medium | 6+ months | 12.5 | Todo |  |  |  | [notes](05.%20Dummy%20Node%20%26%20Deletion/0086.%20Partition%20List/0086.%20Partition%20List.md) |
| 4 | [82. Remove Duplicates from Sorted List II](https://leetcode.com/problems/remove-duplicates-from-sorted-list-ii/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Dummy%20Node%20%26%20Deletion/0082.%20Remove%20Duplicates%20from%20Sorted%20List%20II/0082.%20Remove%20Duplicates%20from%20Sorted%20List%20II.md) |
| 5 | [3217. Delete Nodes From Linked List Present in Array](https://leetcode.com/problems/delete-nodes-from-linked-list-present-in-array/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](05.%20Dummy%20Node%20%26%20Deletion/3217.%20Delete%20Nodes%20From%20Linked%20List%20Present%20in%20Array/3217.%20Delete%20Nodes%20From%20Linked%20List%20Present%20in%20Array.md) |

## 06. Add Numbers in Lists

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [2. Add Two Numbers](https://leetcode.com/problems/add-two-numbers/) | Medium | 3 months | 65.3 | ✅ Solved |  |  |  | [notes](06.%20Add%20Numbers%20in%20Lists/0002.%20Add%20Two%20Numbers/0002.%20Add%20Two%20Numbers.md) |
| 2 | [445. Add Two Numbers II](https://leetcode.com/problems/add-two-numbers-ii/) | Medium | 6+ months | 8.2 | Todo |  |  |  | [notes](06.%20Add%20Numbers%20in%20Lists/0445.%20Add%20Two%20Numbers%20II/0445.%20Add%20Two%20Numbers%20II.md) |

## 07. Copy & Clone List

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [138. Copy List with Random Pointer](https://leetcode.com/problems/copy-list-with-random-pointer/) | Medium | 6+ months | 74.7 | ✅ Solved |  |  |  | [notes](07.%20Copy%20%26%20Clone%20List/0138.%20Copy%20List%20with%20Random%20Pointer/0138.%20Copy%20List%20with%20Random%20Pointer.md) |
