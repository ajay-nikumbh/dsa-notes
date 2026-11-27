# 08. Trees

[Back to Foundation](../README.md) · [Back to DSA Notes](../../README.md)

A tree stores things in a hierarchy: one root at the top, and every other node hangs below exactly one parent. A **binary tree** lets each node have at most two children, left and right. Trees are where recursion starts to feel natural: almost every tree problem is solved by asking the same question at the root and at every subtree.

![The Trees chapter in six sections: basics, traversals, basic problems, views, problems on trees, and binary search trees](images/trees-chapter-path.png)

Read the sections in order. Every note follows the same shape as the rest of this repo: it says which tree it uses, walks through it one step at a time with a picture for every step, explains the limits in plain words, and ends with clean code you can paste into LeetCode.

## Chapter plan

| # | Section | What it teaches | Notes | Status |
|:---:|:---|:---|:---:|:---:|
| 01 | Basics | What a tree is, its parts, the five types, and how to store one in code | 2 | Written |
| 02 | Tree Traversals | Visiting every node: preorder, inorder, postorder, level order and zigzag | 7 | Written |
| 03 | Basic Problems | First recursive problems: depth, balance, diameter, path sum, same tree | 5 | Written |
| 04 | Views | What you see from the side, top or bottom, and the boundary walk | 6 | Written |
| 05 | Problems on Trees | Symmetry, paths, ancestors, width, distances, building and flattening trees | 13 | Written |
| 06 | Binary Search Trees | Trees kept in sorted order: search, floor, ceil, insert, delete, validate, iterate, recover | 15 | Planned |

## 01. Basics

What a tree is, its parts, the five types, and how to store one in code.

| # | Note / Problem | Key idea | Source | Status |
|:---:|:---|:---|:---:|:---:|
| 1 | [Introduction to Trees](01.%20Basics/01.%20Introduction%20to%20Trees.md) | Root, leaf, level, height and the five types: full, complete, perfect, balanced, degenerate | Lecture notes | Written |
| 2 | [Tree Representation](01.%20Basics/02.%20Tree%20Representation.md) | Each node holds a value and two links; LeetCode list and array forms | Lecture notes | Written |

## 02. Tree Traversals

Visiting every node: preorder, inorder, postorder, level order and zigzag.

| # | Note / Problem | Key idea | Source | Status |
|:---:|:---|:---|:---:|:---:|
| 1 | [Binary Tree Traversals](02.%20Tree%20traversals/03.%20Binary%20Tree%20Traversals.md) | BFS and DFS; preorder, inorder, postorder and level order, and writing them by hand | Lecture notes | Written |
| 2 | [144. Binary Tree Preorder Traversal](02.%20Tree%20traversals/04.%20144.%20Binary%20Tree%20Preorder%20Traversal.md) | Root, left, right; with a stack, push right before left; Morris for `O(1)` space | [144](https://leetcode.com/problems/binary-tree-preorder-traversal/) | Written |
| 3 | [94. Binary Tree Inorder Traversal](02.%20Tree%20traversals/05.%2094.%20Binary%20Tree%20Inorder%20Traversal.md) | Go left as far as possible, visit on the way back, then turn right | [94](https://leetcode.com/problems/binary-tree-inorder-traversal/) | Written |
| 4 | [145. Binary Tree Postorder Traversal](02.%20Tree%20traversals/06.%20145.%20Binary%20Tree%20Postorder%20Traversal.md) | Visit a node after both subtrees; one stack needs a `prev` pointer | [145](https://leetcode.com/problems/binary-tree-postorder-traversal/) | Written |
| 5 | [102. Binary Tree Level Order Traversal](02.%20Tree%20traversals/07.%20102.%20Binary%20Tree%20Level%20Order%20Traversal.md) | A queue holds one level; take out `len(queue)` nodes per round | [102](https://leetcode.com/problems/binary-tree-level-order-traversal/) | Written |
| 6 | [103. Binary Tree Zigzag Level Order Traversal](02.%20Tree%20traversals/08.%20103.%20Binary%20Tree%20Zigzag%20Level%20Order%20Traversal.md) | Level order with a direction flag; write each level at the back or the front of a deque | [103](https://leetcode.com/problems/binary-tree-zigzag-level-order-traversal/) | Written |
| 7 | [All in One Traversal](02.%20Tree%20traversals/09.%20All%20in%20One%20Traversal.md) | A stack of (node, state): states 1, 2, 3 give preorder, inorder, postorder in one pass | Lecture notes | Written |

## 03. Basic Problems

First recursive problems: depth, balance, diameter, path sum, same tree.

| # | Note / Problem | Key idea | Source | Status |
|:---:|:---|:---|:---:|:---:|
| 1 | [104. Maximum Depth of Binary Tree](03.%20Basic%20problems/10.%20104.%20Maximum%20Depth%20of%20Binary%20Tree.md) | Depth of a node is 1 plus the deeper child; computed bottom-up | [104](https://leetcode.com/problems/maximum-depth-of-binary-tree/) | Written |
| 2 | [110. Balanced Binary Tree](03.%20Basic%20problems/11.%20110.%20Balanced%20Binary%20Tree.md) | Heights bottom-up; return -1 the moment two sides differ by more than 1 | [110](https://leetcode.com/problems/balanced-binary-tree/) | Written |
| 3 | [543. Diameter of Binary Tree](03.%20Basic%20problems/12.%20543.%20Diameter%20of%20Binary%20Tree.md) | Every path bends at one node; track left height plus right height while returning heights | [543](https://leetcode.com/problems/diameter-of-binary-tree/) | Written |
| 4 | [124. Binary Tree Maximum Path Sum](03.%20Basic%20problems/13.%20124.%20Binary%20Tree%20Maximum%20Path%20Sum.md) | Return one-sided gains, drop negative sides, track value plus both gains | [124](https://leetcode.com/problems/binary-tree-maximum-path-sum/) | Written |
| 5 | [100. Same Tree](03.%20Basic%20problems/14.%20100.%20Same%20Tree.md) | Walk both trees together; empty spots must match too | [100](https://leetcode.com/problems/same-tree/) | Written |

## 04. Views

What you see from the side, top or bottom, and the boundary walk.

| # | Note / Problem | Key idea | Source | Status |
|:---:|:---|:---|:---:|:---:|
| 1 | [545. Boundary of Binary Tree](04.%20Views/15.%20545.%20Boundary%20of%20Binary%20Tree.md) | Root, left edge down, leaves left to right, right edge up; leaves added once | [545](https://leetcode.com/problems/boundary-of-binary-tree/) | Written |
| 2 | [987. Vertical Order Traversal of a Binary Tree](04.%20Views/16.%20987.%20Vertical%20Order%20Traversal%20of%20a%20Binary%20Tree.md) | Give each node (column, row); sort by column, row, then value | [987](https://leetcode.com/problems/vertical-order-traversal-of-a-binary-tree/) | Written |
| 3 | [Top View of Binary Tree](04.%20Views/17.%20Top%20View%20of%20Binary%20Tree.md) | BFS with columns; keep the first node met in each column | [GfG](https://www.geeksforgeeks.org/problems/top-view-of-binary-tree/1) | Written |
| 4 | [Bottom View of Binary Tree](04.%20Views/18.%20Bottom%20View%20of%20Binary%20Tree.md) | BFS with columns; overwrite, so the last node met in each column stays | [GfG](https://www.geeksforgeeks.org/problems/bottom-view-of-binary-tree/1) | Written |
| 5 | [199. Binary Tree Right Side View](04.%20Views/19.%20199.%20Binary%20Tree%20Right%20Side%20View.md) | One node per level; DFS right-first records the first node on each new level | [199](https://leetcode.com/problems/binary-tree-right-side-view/) | Written |
| 6 | [Left View of Binary Tree](04.%20Views/20.%20Left%20View%20of%20Binary%20Tree.md) | Same as the right view with the two recursive calls swapped | [GfG](https://www.geeksforgeeks.org/problems/left-view-of-binary-tree/1) | Written |

## 05. Problems on Trees

Symmetry, paths, ancestors, width, distances, building and flattening trees.

| # | Note / Problem | Key idea | Source | Status |
|:---:|:---|:---|:---:|:---:|
| 1 | [101. Symmetric Tree](05.%20Problem%20on%20trees/21.%20101.%20Symmetric%20Tree.md) | Compare the two halves as mirrors: outer with outer, inner with inner | [101](https://leetcode.com/problems/symmetric-tree/) | Written |
| 2 | [257. Binary Tree Paths](05.%20Problem%20on%20trees/22.%20257.%20Binary%20Tree%20Paths.md) | DFS with one shared path list: push going down, save at a leaf, pop going back | [257](https://leetcode.com/problems/binary-tree-paths/) | Written |
| 3 | [236. Lowest Common Ancestor of a Binary Tree](05.%20Problem%20on%20trees/23.%20236.%20Lowest%20Common%20Ancestor%20of%20a%20Binary%20Tree.md) | Return p, q or None from below; the first node where both sides answer is the LCA | [236](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree/) | Written |
| 4 | [662. Maximum Width of Binary Tree](05.%20Problem%20on%20trees/24.%20662.%20Maximum%20Width%20of%20Binary%20Tree.md) | Number spots like a complete tree; width is last minus first plus 1, reset numbers each level | [662](https://leetcode.com/problems/maximum-width-of-binary-tree/) | Written |
| 5 | [Children Sum Property](05.%20Problem%20on%20trees/25.%20Children%20Sum%20Property.md) | Going down, lift small children to the parent; coming back up, set each node to its children's sum | [GfG](https://www.geeksforgeeks.org/problems/children-sum-parent/1) | Written |
| 6 | [863. All Nodes Distance K in Binary Tree](05.%20Problem%20on%20trees/26.%20863.%20All%20Nodes%20Distance%20K%20in%20Binary%20Tree.md) | Store parents, then BFS from the target for k rounds with a visited set | [863](https://leetcode.com/problems/all-nodes-distance-k-in-binary-tree/) | Written |
| 7 | [Time To Burn Tree](05.%20Problem%20on%20trees/27.%20Time%20To%20Burn%20Tree.md) | Parent map, then BFS rounds from the start node; count rounds until all nodes burn | [2385](https://leetcode.com/problems/amount-of-time-for-binary-tree-to-be-infected/) | Written |
| 8 | [222. Count Complete Tree Nodes](05.%20Problem%20on%20trees/28.%20222.%20Count%20Complete%20Tree%20Nodes.md) | Equal left and right edge heights mean a perfect subtree: count it as 2^h - 1 | [222](https://leetcode.com/problems/count-complete-tree-nodes/) | Written |
| 9 | [Requirements needed to construct a Unique Binary Tree](05.%20Problem%20on%20trees/29.%20Requirements%20needed%20to%20construct%20a%20Unique%20Binary%20Tree.md) | Inorder plus preorder, or inorder plus postorder; preorder plus postorder is not enough | Lecture notes | Written |
| 10 | [105. Construct Binary Tree from Preorder and Inorder Traversal](05.%20Problem%20on%20trees/30.%20105.%20Construct%20Binary%20Tree%20from%20Preorder%20and%20Inorder%20Traversal.md) | First preorder value is the root; its inorder index splits left and right; a dict finds it in O(1) | [105](https://leetcode.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/) | Written |
| 11 | [106. Construct Binary Tree from Inorder and Postorder Traversal](05.%20Problem%20on%20trees/31.%20106.%20Construct%20Binary%20Tree%20from%20Inorder%20and%20Postorder%20Traversal.md) | Last postorder value is the root; same inorder split with a dict | [106](https://leetcode.com/problems/construct-binary-tree-from-inorder-and-postorder-traversal/) | Written |
| 12 | [297. Serialize and Deserialize Binary Tree](05.%20Problem%20on%20trees/32.%20297.%20Serialize%20and%20Deserialize%20Binary%20Tree.md) | Level order with a marker for every empty spot; read back in the same order | [297](https://leetcode.com/problems/serialize-and-deserialize-binary-tree/) | Written |
| 13 | [114. Flatten Binary Tree to Linked List](05.%20Problem%20on%20trees/33.%20114.%20Flatten%20Binary%20Tree%20to%20Linked%20List.md) | Hang the old right side on the rightmost node of the left side, move left to right, walk right | [114](https://leetcode.com/problems/flatten-binary-tree-to-linked-list/) | Written |

## 06. Binary Search Trees

Trees kept in sorted order: search, floor, ceil, insert, delete, validate, iterate, recover.

| # | Note / Problem | Key idea | Source | Status |
|:---:|:---|:---|:---:|:---:|
| 1 | Introduction to Binary Search Tree | Key idea is added when this note is written | Lecture notes (GfG style) | Planned |
| 2 | 700. Search in a Binary Search Tree | Key idea is added when this note is written | LeetCode problem 700 | Planned |
| 3 | Ceil in BST | Key idea is added when this note is written | Lecture notes (GfG style) | Planned |
| 4 | Floor in BST | Key idea is added when this note is written | Lecture notes (GfG style) | Planned |
| 5 | 701. Insert into a Binary Search Tree | Key idea is added when this note is written | LeetCode problem 701 | Planned |
| 6 | 450. Delete Node in a BST | Key idea is added when this note is written | LeetCode problem 450 | Planned |
| 7 | 230. Kth Smallest Element in a BST | Key idea is added when this note is written | LeetCode problem 230 | Planned |
| 8 | 98. Validate Binary Search Tree | Key idea is added when this note is written | LeetCode problem 98 | Planned |
| 9 | 235. Lowest Common Ancestor of a Binary Search Tree | Key idea is added when this note is written | LeetCode problem 235 | Planned |
| 10 | 1008. Construct Binary Search Tree from Preorder Traversal | Key idea is added when this note is written | LeetCode problem 1008 | Planned |
| 11 | 285. Inorder Successor in BST | Key idea is added when this note is written | LeetCode problem 285 | Planned |
| 12 | 173. Binary Search Tree Iterator | Key idea is added when this note is written | LeetCode problem 173 | Planned |
| 13 | 653. Two Sum IV - Input is a BST | Key idea is added when this note is written | LeetCode problem 653 | Planned |
| 14 | 99. Recover Binary Search Tree | Key idea is added when this note is written | LeetCode problem 99 | Planned |
| 15 | Largest BST | Key idea is added when this note is written | Lecture notes (GfG style) | Planned |
