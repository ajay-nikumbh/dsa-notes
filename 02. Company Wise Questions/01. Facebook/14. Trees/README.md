# 14. Trees

[Back to Facebook](../README.md) · [Back to DSA Notes](../../../README.md)

103 Meta (Facebook) problems: 30 Easy, 68 Medium, 5 Hard, in 12 sub-patterns.

## Sub-patterns

| # | Sub-pattern | Questions | Easy | Medium | Hard | Last 3 Months | Solved | Most Asked |
|:---:|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---|
| 01 | [DFS Traversal (Pre, In, Post)](#01-dfs-traversal-pre-in-post) | 15 | 11 | 4 | 0 | 2 | 9 | 404. Sum of Left Leaves, 572. Subtree of Another Tree, 1379. Find a Corresponding Node of a Binary Tree in a Clone of That Tree |
| 02 | [BFS & Level Order](#02-bfs--level-order) | 15 | 3 | 12 | 0 | 1 | 6 | 958. Check Completeness of a Binary Tree, 102. Binary Tree Level Order Traversal, 117. Populating Next Right Pointers in Each Node II |
| 03 | [Tree Properties (Height, Diameter, Balance)](#03-tree-properties-height-diameter-balance) | 10 | 4 | 6 | 0 | 1 | 5 | 543. Diameter of Binary Tree, 2265. Count Nodes Equal to Average of Subtree, 1361. Validate Binary Tree Nodes |
| 04 | [Path Sum Problems](#04-path-sum-problems) | 10 | 3 | 6 | 1 | 0 | 4 | 129. Sum Root to Leaf Numbers, 124. Binary Tree Maximum Path Sum, 257. Binary Tree Paths |
| 05 | [Lowest Common Ancestor](#05-lowest-common-ancestor) | 6 | 0 | 6 | 0 | 0 | 3 | 1650. Lowest Common Ancestor of a Binary Tree III, 236. Lowest Common Ancestor of a Binary Tree, 235. Lowest Common Ancestor of a Binary Search Tree |
| 06 | [Binary Search Tree](#06-binary-search-tree) | 15 | 6 | 9 | 0 | 1 | 9 | 938. Range Sum of BST, 270. Closest Binary Search Tree Value, 98. Validate Binary Search Tree |
| 07 | [Tree Construction](#07-tree-construction) | 10 | 1 | 8 | 1 | 0 | 3 | 536. Construct Binary Tree from String, 108. Convert Sorted Array to Binary Search Tree, 1382. Balance a Binary Search Tree |
| 08 | [Tree Views & Vertical Order](#08-tree-views--vertical-order) | 4 | 0 | 3 | 1 | 0 | 2 | 314. Binary Tree Vertical Order Traversal, 199. Binary Tree Right Side View, 987. Vertical Order Traversal of a Binary Tree |
| 09 | [Serialize & Deserialize](#09-serialize--deserialize) | 3 | 0 | 2 | 1 | 0 | 1 | 297. Serialize and Deserialize Binary Tree, 606. Construct String from Binary Tree, 652. Find Duplicate Subtrees |
| 10 | [Tree Modification](#10-tree-modification) | 7 | 2 | 5 | 0 | 0 | 3 | 426. Convert Binary Search Tree to Sorted Doubly Linked List, 998. Maximum Binary Tree II, 226. Invert Binary Tree |
| 11 | [N-ary Tree](#11-n-ary-tree) | 2 | 0 | 2 | 0 | 0 | 0 | 1522. Diameter of N-Ary Tree, 1506. Find Root of N-Ary Tree |
| 12 | [Tree as Graph (Parent Pointers, Distance K)](#12-tree-as-graph-parent-pointers-distance-k) | 6 | 0 | 5 | 1 | 0 | 1 | 863. All Nodes Distance K in Binary Tree, 1443. Minimum Time to Collect All Apples in a Tree, 1245. Tree Diameter |

**Columns**

- **Last Asked**: most recent LeetCode window that lists the problem for Meta (30 days, 3 months, 6 months or 6+ months).
- **Frequency**: LeetCode frequency score (0-100) in the Meta "All" list.
- **Status**: your LeetCode status on the day this file was generated. 🔒 after a title means LeetCode Premium.
- **Logic / Key Idea, Time, Space**: fill these in as you solve. A rebuild keeps what you typed.
- **Notes**: link to the problem's notes file.

Inside each sub-pattern, rows are sorted by most recent window, then by frequency (highest first).

## 01. DFS Traversal (Pre, In, Post)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [101. Symmetric Tree](https://leetcode.com/problems/symmetric-tree/) | Easy | 3 months | 32.0 | ✅ Solved |  |  |  | [notes](01.%20DFS%20Traversal%20%28Pre%2C%20In%2C%20Post%29/0101.%20Symmetric%20Tree/0101.%20Symmetric%20Tree.md) |
| 2 | [144. Binary Tree Preorder Traversal](https://leetcode.com/problems/binary-tree-preorder-traversal/) | Easy | 3 months | 12.8 | ✅ Solved |  |  |  | [notes](01.%20DFS%20Traversal%20%28Pre%2C%20In%2C%20Post%29/0144.%20Binary%20Tree%20Preorder%20Traversal/0144.%20Binary%20Tree%20Preorder%20Traversal.md) |
| 3 | [94. Binary Tree Inorder Traversal](https://leetcode.com/problems/binary-tree-inorder-traversal/) | Easy | 6 months | 36.3 | ✅ Solved |  |  |  | [notes](01.%20DFS%20Traversal%20%28Pre%2C%20In%2C%20Post%29/0094.%20Binary%20Tree%20Inorder%20Traversal/0094.%20Binary%20Tree%20Inorder%20Traversal.md) |
| 4 | [100. Same Tree](https://leetcode.com/problems/same-tree/) | Easy | 6 months | 35.4 | ✅ Solved |  |  |  | [notes](01.%20DFS%20Traversal%20%28Pre%2C%20In%2C%20Post%29/0100.%20Same%20Tree/0100.%20Same%20Tree.md) |
| 5 | [404. Sum of Left Leaves](https://leetcode.com/problems/sum-of-left-leaves/) | Easy | 6+ months | 41.0 | ✅ Solved |  |  |  | [notes](01.%20DFS%20Traversal%20%28Pre%2C%20In%2C%20Post%29/0404.%20Sum%20of%20Left%20Leaves/0404.%20Sum%20of%20Left%20Leaves.md) |
| 6 | [572. Subtree of Another Tree](https://leetcode.com/problems/subtree-of-another-tree/) | Easy | 6+ months | 40.9 | Todo |  |  |  | [notes](01.%20DFS%20Traversal%20%28Pre%2C%20In%2C%20Post%29/0572.%20Subtree%20of%20Another%20Tree/0572.%20Subtree%20of%20Another%20Tree.md) |
| 7 | [1379. Find a Corresponding Node of a Binary Tree in a Clone of That Tree](https://leetcode.com/problems/find-a-corresponding-node-of-a-binary-tree-in-a-clone-of-that-tree/) | Easy | 6+ months | 39.5 | Todo |  |  |  | [notes](01.%20DFS%20Traversal%20%28Pre%2C%20In%2C%20Post%29/1379.%20Find%20a%20Corresponding%20Node%20of%20a%20Binary%20Tree%20in%20a%20Clone%20of%20That%20Tree/1379.%20Find%20a%20Corresponding%20Node%20of%20a%20Binary%20Tree%20in%20a%20Clone%20of%20That%20Tree.md) |
| 8 | [1448. Count Good Nodes in Binary Tree](https://leetcode.com/problems/count-good-nodes-in-binary-tree/) | Medium | 6+ months | 9.3 | Todo |  |  |  | [notes](01.%20DFS%20Traversal%20%28Pre%2C%20In%2C%20Post%29/1448.%20Count%20Good%20Nodes%20in%20Binary%20Tree/1448.%20Count%20Good%20Nodes%20in%20Binary%20Tree.md) |
| 9 | [979. Distribute Coins in Binary Tree](https://leetcode.com/problems/distribute-coins-in-binary-tree/) | Medium | 6+ months | 8.3 | ✅ Solved |  |  |  | [notes](01.%20DFS%20Traversal%20%28Pre%2C%20In%2C%20Post%29/0979.%20Distribute%20Coins%20in%20Binary%20Tree/0979.%20Distribute%20Coins%20in%20Binary%20Tree.md) |
| 10 | [671. Second Minimum Node In a Binary Tree](https://leetcode.com/problems/second-minimum-node-in-a-binary-tree/) | Easy | 6+ months | 5.3 | Todo |  |  |  | [notes](01.%20DFS%20Traversal%20%28Pre%2C%20In%2C%20Post%29/0671.%20Second%20Minimum%20Node%20In%20a%20Binary%20Tree/0671.%20Second%20Minimum%20Node%20In%20a%20Binary%20Tree.md) |
| 11 | [145. Binary Tree Postorder Traversal](https://leetcode.com/problems/binary-tree-postorder-traversal/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](01.%20DFS%20Traversal%20%28Pre%2C%20In%2C%20Post%29/0145.%20Binary%20Tree%20Postorder%20Traversal/0145.%20Binary%20Tree%20Postorder%20Traversal.md) |
| 12 | [872. Leaf-Similar Trees](https://leetcode.com/problems/leaf-similar-trees/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](01.%20DFS%20Traversal%20%28Pre%2C%20In%2C%20Post%29/0872.%20Leaf-Similar%20Trees/0872.%20Leaf-Similar%20Trees.md) |
| 13 | [1315. Sum of Nodes with Even-Valued Grandparent](https://leetcode.com/problems/sum-of-nodes-with-even-valued-grandparent/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20DFS%20Traversal%20%28Pre%2C%20In%2C%20Post%29/1315.%20Sum%20of%20Nodes%20with%20Even-Valued%20Grandparent/1315.%20Sum%20of%20Nodes%20with%20Even-Valued%20Grandparent.md) |
| 14 | [1485. Clone Binary Tree With Random Pointer](https://leetcode.com/problems/clone-binary-tree-with-random-pointer/) 🔒 | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20DFS%20Traversal%20%28Pre%2C%20In%2C%20Post%29/1485.%20Clone%20Binary%20Tree%20With%20Random%20Pointer/1485.%20Clone%20Binary%20Tree%20With%20Random%20Pointer.md) |
| 15 | [2236. Root Equals Sum of Children](https://leetcode.com/problems/root-equals-sum-of-children/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](01.%20DFS%20Traversal%20%28Pre%2C%20In%2C%20Post%29/2236.%20Root%20Equals%20Sum%20of%20Children/2236.%20Root%20Equals%20Sum%20of%20Children.md) |

## 02. BFS & Level Order

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [103. Binary Tree Zigzag Level Order Traversal](https://leetcode.com/problems/binary-tree-zigzag-level-order-traversal/) | Medium | 3 months | 25.9 | ✅ Solved |  |  |  | [notes](02.%20BFS%20%26%20Level%20Order/0103.%20Binary%20Tree%20Zigzag%20Level%20Order%20Traversal/0103.%20Binary%20Tree%20Zigzag%20Level%20Order%20Traversal.md) |
| 2 | [102. Binary Tree Level Order Traversal](https://leetcode.com/problems/binary-tree-level-order-traversal/) | Medium | 6 months | 53.3 | ✅ Solved |  |  |  | [notes](02.%20BFS%20%26%20Level%20Order/0102.%20Binary%20Tree%20Level%20Order%20Traversal/0102.%20Binary%20Tree%20Level%20Order%20Traversal.md) |
| 3 | [958. Check Completeness of a Binary Tree](https://leetcode.com/problems/check-completeness-of-a-binary-tree/) | Medium | 6+ months | 54.0 | Todo |  |  |  | [notes](02.%20BFS%20%26%20Level%20Order/0958.%20Check%20Completeness%20of%20a%20Binary%20Tree/0958.%20Check%20Completeness%20of%20a%20Binary%20Tree.md) |
| 4 | [117. Populating Next Right Pointers in Each Node II](https://leetcode.com/problems/populating-next-right-pointers-in-each-node-ii/) | Medium | 6+ months | 45.5 | Todo |  |  |  | [notes](02.%20BFS%20%26%20Level%20Order/0117.%20Populating%20Next%20Right%20Pointers%20in%20Each%20Node%20II/0117.%20Populating%20Next%20Right%20Pointers%20in%20Each%20Node%20II.md) |
| 5 | [116. Populating Next Right Pointers in Each Node](https://leetcode.com/problems/populating-next-right-pointers-in-each-node/) | Medium | 6+ months | 39.5 | Todo |  |  |  | [notes](02.%20BFS%20%26%20Level%20Order/0116.%20Populating%20Next%20Right%20Pointers%20in%20Each%20Node/0116.%20Populating%20Next%20Right%20Pointers%20in%20Each%20Node.md) |
| 6 | [637. Average of Levels in Binary Tree](https://leetcode.com/problems/average-of-levels-in-binary-tree/) | Easy | 6+ months | 37.8 | ✅ Solved |  |  |  | [notes](02.%20BFS%20%26%20Level%20Order/0637.%20Average%20of%20Levels%20in%20Binary%20Tree/0637.%20Average%20of%20Levels%20in%20Binary%20Tree.md) |
| 7 | [662. Maximum Width of Binary Tree](https://leetcode.com/problems/maximum-width-of-binary-tree/) | Medium | 6+ months | 18.5 | ✅ Solved |  |  |  | [notes](02.%20BFS%20%26%20Level%20Order/0662.%20Maximum%20Width%20of%20Binary%20Tree/0662.%20Maximum%20Width%20of%20Binary%20Tree.md) |
| 8 | [1161. Maximum Level Sum of a Binary Tree](https://leetcode.com/problems/maximum-level-sum-of-a-binary-tree/) | Medium | 6+ months | 17.3 | Todo |  |  |  | [notes](02.%20BFS%20%26%20Level%20Order/1161.%20Maximum%20Level%20Sum%20of%20a%20Binary%20Tree/1161.%20Maximum%20Level%20Sum%20of%20a%20Binary%20Tree.md) |
| 9 | [111. Minimum Depth of Binary Tree](https://leetcode.com/problems/minimum-depth-of-binary-tree/) | Easy | 6+ months | 12.0 | Todo |  |  |  | [notes](02.%20BFS%20%26%20Level%20Order/0111.%20Minimum%20Depth%20of%20Binary%20Tree/0111.%20Minimum%20Depth%20of%20Binary%20Tree.md) |
| 10 | [1609. Even Odd Tree](https://leetcode.com/problems/even-odd-tree/) | Medium | 6+ months | 6.7 | Todo |  |  |  | [notes](02.%20BFS%20%26%20Level%20Order/1609.%20Even%20Odd%20Tree/1609.%20Even%20Odd%20Tree.md) |
| 11 | [107. Binary Tree Level Order Traversal II](https://leetcode.com/problems/binary-tree-level-order-traversal-ii/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20BFS%20%26%20Level%20Order/0107.%20Binary%20Tree%20Level%20Order%20Traversal%20II/0107.%20Binary%20Tree%20Level%20Order%20Traversal%20II.md) |
| 12 | [513. Find Bottom Left Tree Value](https://leetcode.com/problems/find-bottom-left-tree-value/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](02.%20BFS%20%26%20Level%20Order/0513.%20Find%20Bottom%20Left%20Tree%20Value/0513.%20Find%20Bottom%20Left%20Tree%20Value.md) |
| 13 | [515. Find Largest Value in Each Tree Row](https://leetcode.com/problems/find-largest-value-in-each-tree-row/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20BFS%20%26%20Level%20Order/0515.%20Find%20Largest%20Value%20in%20Each%20Tree%20Row/0515.%20Find%20Largest%20Value%20in%20Each%20Tree%20Row.md) |
| 14 | [919. Complete Binary Tree Inserter](https://leetcode.com/problems/complete-binary-tree-inserter/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20BFS%20%26%20Level%20Order/0919.%20Complete%20Binary%20Tree%20Inserter/0919.%20Complete%20Binary%20Tree%20Inserter.md) |
| 15 | [993. Cousins in Binary Tree](https://leetcode.com/problems/cousins-in-binary-tree/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](02.%20BFS%20%26%20Level%20Order/0993.%20Cousins%20in%20Binary%20Tree/0993.%20Cousins%20in%20Binary%20Tree.md) |

## 03. Tree Properties (Height, Diameter, Balance)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [543. Diameter of Binary Tree](https://leetcode.com/problems/diameter-of-binary-tree/) | Easy | 3 months | 88.9 | ✅ Solved |  |  |  | [notes](03.%20Tree%20Properties%20%28Height%2C%20Diameter%2C%20Balance%29/0543.%20Diameter%20of%20Binary%20Tree/0543.%20Diameter%20of%20Binary%20Tree.md) |
| 2 | [110. Balanced Binary Tree](https://leetcode.com/problems/balanced-binary-tree/) | Easy | 6 months | 33.4 | ✅ Solved |  |  |  | [notes](03.%20Tree%20Properties%20%28Height%2C%20Diameter%2C%20Balance%29/0110.%20Balanced%20Binary%20Tree/0110.%20Balanced%20Binary%20Tree.md) |
| 3 | [222. Count Complete Tree Nodes](https://leetcode.com/problems/count-complete-tree-nodes/) | Medium | 6 months | 18.6 | ✅ Solved |  |  |  | [notes](03.%20Tree%20Properties%20%28Height%2C%20Diameter%2C%20Balance%29/0222.%20Count%20Complete%20Tree%20Nodes/0222.%20Count%20Complete%20Tree%20Nodes.md) |
| 4 | [2265. Count Nodes Equal to Average of Subtree](https://leetcode.com/problems/count-nodes-equal-to-average-of-subtree/) | Medium | 6+ months | 58.7 | Todo |  |  |  | [notes](03.%20Tree%20Properties%20%28Height%2C%20Diameter%2C%20Balance%29/2265.%20Count%20Nodes%20Equal%20to%20Average%20of%20Subtree/2265.%20Count%20Nodes%20Equal%20to%20Average%20of%20Subtree.md) |
| 5 | [1361. Validate Binary Tree Nodes](https://leetcode.com/problems/validate-binary-tree-nodes/) | Medium | 6+ months | 37.7 | Todo |  |  |  | [notes](03.%20Tree%20Properties%20%28Height%2C%20Diameter%2C%20Balance%29/1361.%20Validate%20Binary%20Tree%20Nodes/1361.%20Validate%20Binary%20Tree%20Nodes.md) |
| 6 | [104. Maximum Depth of Binary Tree](https://leetcode.com/problems/maximum-depth-of-binary-tree/) | Easy | 6+ months | 30.2 | ✅ Solved |  |  |  | [notes](03.%20Tree%20Properties%20%28Height%2C%20Diameter%2C%20Balance%29/0104.%20Maximum%20Depth%20of%20Binary%20Tree/0104.%20Maximum%20Depth%20of%20Binary%20Tree.md) |
| 7 | [1339. Maximum Product of Splitted Binary Tree](https://leetcode.com/problems/maximum-product-of-splitted-binary-tree/) | Medium | 6+ months | 5.9 | Todo |  |  |  | [notes](03.%20Tree%20Properties%20%28Height%2C%20Diameter%2C%20Balance%29/1339.%20Maximum%20Product%20of%20Splitted%20Binary%20Tree/1339.%20Maximum%20Product%20of%20Splitted%20Binary%20Tree.md) |
| 8 | [655. Print Binary Tree](https://leetcode.com/problems/print-binary-tree/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](03.%20Tree%20Properties%20%28Height%2C%20Diameter%2C%20Balance%29/0655.%20Print%20Binary%20Tree/0655.%20Print%20Binary%20Tree.md) |
| 9 | [1973. Count Nodes Equal to Sum of Descendants](https://leetcode.com/problems/count-nodes-equal-to-sum-of-descendants/) 🔒 | Medium | 6+ months | 36.1 | Todo |  |  |  | [notes](03.%20Tree%20Properties%20%28Height%2C%20Diameter%2C%20Balance%29/1973.%20Count%20Nodes%20Equal%20to%20Sum%20of%20Descendants/1973.%20Count%20Nodes%20Equal%20to%20Sum%20of%20Descendants.md) |
| 10 | [563. Binary Tree Tilt](https://leetcode.com/problems/binary-tree-tilt/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](03.%20Tree%20Properties%20%28Height%2C%20Diameter%2C%20Balance%29/0563.%20Binary%20Tree%20Tilt/0563.%20Binary%20Tree%20Tilt.md) |

## 04. Path Sum Problems

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [129. Sum Root to Leaf Numbers](https://leetcode.com/problems/sum-root-to-leaf-numbers/) | Medium | 6 months | 78.4 | ✅ Solved |  |  |  | [notes](04.%20Path%20Sum%20Problems/0129.%20Sum%20Root%20to%20Leaf%20Numbers/0129.%20Sum%20Root%20to%20Leaf%20Numbers.md) |
| 2 | [124. Binary Tree Maximum Path Sum](https://leetcode.com/problems/binary-tree-maximum-path-sum/) | Hard | 6+ months | 46.3 | ✅ Solved |  |  |  | [notes](04.%20Path%20Sum%20Problems/0124.%20Binary%20Tree%20Maximum%20Path%20Sum/0124.%20Binary%20Tree%20Maximum%20Path%20Sum.md) |
| 3 | [257. Binary Tree Paths](https://leetcode.com/problems/binary-tree-paths/) | Easy | 6+ months | 42.5 | ✅ Solved |  |  |  | [notes](04.%20Path%20Sum%20Problems/0257.%20Binary%20Tree%20Paths/0257.%20Binary%20Tree%20Paths.md) |
| 4 | [113. Path Sum II](https://leetcode.com/problems/path-sum-ii/) | Medium | 6+ months | 21.5 | Todo |  |  |  | [notes](04.%20Path%20Sum%20Problems/0113.%20Path%20Sum%20II/0113.%20Path%20Sum%20II.md) |
| 5 | [112. Path Sum](https://leetcode.com/problems/path-sum/) | Easy | 6+ months | 19.8 | Todo |  |  |  | [notes](04.%20Path%20Sum%20Problems/0112.%20Path%20Sum/0112.%20Path%20Sum.md) |
| 6 | [437. Path Sum III](https://leetcode.com/problems/path-sum-iii/) | Medium | 6+ months | 15.8 | Todo |  |  |  | [notes](04.%20Path%20Sum%20Problems/0437.%20Path%20Sum%20III/0437.%20Path%20Sum%20III.md) |
| 7 | [298. Binary Tree Longest Consecutive Sequence](https://leetcode.com/problems/binary-tree-longest-consecutive-sequence/) 🔒 | Medium | 6+ months | 11.0 | Todo |  |  |  | [notes](04.%20Path%20Sum%20Problems/0298.%20Binary%20Tree%20Longest%20Consecutive%20Sequence/0298.%20Binary%20Tree%20Longest%20Consecutive%20Sequence.md) |
| 8 | [549. Binary Tree Longest Consecutive Sequence II](https://leetcode.com/problems/binary-tree-longest-consecutive-sequence-ii/) 🔒 | Medium | 6+ months | 10.9 | Todo |  |  |  | [notes](04.%20Path%20Sum%20Problems/0549.%20Binary%20Tree%20Longest%20Consecutive%20Sequence%20II/0549.%20Binary%20Tree%20Longest%20Consecutive%20Sequence%20II.md) |
| 9 | [1022. Sum of Root To Leaf Binary Numbers](https://leetcode.com/problems/sum-of-root-to-leaf-binary-numbers/) | Easy | 6+ months | 7.1 | ✅ Solved |  |  |  | [notes](04.%20Path%20Sum%20Problems/1022.%20Sum%20of%20Root%20To%20Leaf%20Binary%20Numbers/1022.%20Sum%20of%20Root%20To%20Leaf%20Binary%20Numbers.md) |
| 10 | [1026. Maximum Difference Between Node and Ancestor](https://leetcode.com/problems/maximum-difference-between-node-and-ancestor/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Path%20Sum%20Problems/1026.%20Maximum%20Difference%20Between%20Node%20and%20Ancestor/1026.%20Maximum%20Difference%20Between%20Node%20and%20Ancestor.md) |

## 05. Lowest Common Ancestor

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [1650. Lowest Common Ancestor of a Binary Tree III](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree-iii/) 🔒 | Medium | 6+ months | 86.7 | Todo |  |  |  | [notes](05.%20Lowest%20Common%20Ancestor/1650.%20Lowest%20Common%20Ancestor%20of%20a%20Binary%20Tree%20III/1650.%20Lowest%20Common%20Ancestor%20of%20a%20Binary%20Tree%20III.md) |
| 2 | [236. Lowest Common Ancestor of a Binary Tree](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree/) | Medium | 6+ months | 86.2 | ✅ Solved |  |  |  | [notes](05.%20Lowest%20Common%20Ancestor/0236.%20Lowest%20Common%20Ancestor%20of%20a%20Binary%20Tree/0236.%20Lowest%20Common%20Ancestor%20of%20a%20Binary%20Tree.md) |
| 3 | [235. Lowest Common Ancestor of a Binary Search Tree](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-search-tree/) | Medium | 6+ months | 52.5 | ✅ Solved |  |  |  | [notes](05.%20Lowest%20Common%20Ancestor/0235.%20Lowest%20Common%20Ancestor%20of%20a%20Binary%20Search%20Tree/0235.%20Lowest%20Common%20Ancestor%20of%20a%20Binary%20Search%20Tree.md) |
| 4 | [865. Smallest Subtree with all the Deepest Nodes](https://leetcode.com/problems/smallest-subtree-with-all-the-deepest-nodes/) | Medium | 6+ months | 43.6 | Todo |  |  |  | [notes](05.%20Lowest%20Common%20Ancestor/0865.%20Smallest%20Subtree%20with%20all%20the%20Deepest%20Nodes/0865.%20Smallest%20Subtree%20with%20all%20the%20Deepest%20Nodes.md) |
| 5 | [1123. Lowest Common Ancestor of Deepest Leaves](https://leetcode.com/problems/lowest-common-ancestor-of-deepest-leaves/) | Medium | 6+ months | 41.3 | ✅ Solved |  |  |  | [notes](05.%20Lowest%20Common%20Ancestor/1123.%20Lowest%20Common%20Ancestor%20of%20Deepest%20Leaves/1123.%20Lowest%20Common%20Ancestor%20of%20Deepest%20Leaves.md) |
| 6 | [1644. Lowest Common Ancestor of a Binary Tree II](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree-ii/) 🔒 | Medium | 6+ months | 16.8 | Todo |  |  |  | [notes](05.%20Lowest%20Common%20Ancestor/1644.%20Lowest%20Common%20Ancestor%20of%20a%20Binary%20Tree%20II/1644.%20Lowest%20Common%20Ancestor%20of%20a%20Binary%20Tree%20II.md) |

## 06. Binary Search Tree

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [98. Validate Binary Search Tree](https://leetcode.com/problems/validate-binary-search-tree/) | Medium | 3 months | 50.3 | ✅ Solved |  |  |  | [notes](06.%20Binary%20Search%20Tree/0098.%20Validate%20Binary%20Search%20Tree/0098.%20Validate%20Binary%20Search%20Tree.md) |
| 2 | [938. Range Sum of BST](https://leetcode.com/problems/range-sum-of-bst/) | Easy | 6+ months | 74.6 | ✅ Solved |  |  |  | [notes](06.%20Binary%20Search%20Tree/0938.%20Range%20Sum%20of%20BST/0938.%20Range%20Sum%20of%20BST.md) |
| 3 | [270. Closest Binary Search Tree Value](https://leetcode.com/problems/closest-binary-search-tree-value/) 🔒 | Easy | 6+ months | 56.1 | Todo |  |  |  | [notes](06.%20Binary%20Search%20Tree/0270.%20Closest%20Binary%20Search%20Tree%20Value/0270.%20Closest%20Binary%20Search%20Tree%20Value.md) |
| 4 | [653. Two Sum IV - Input is a BST](https://leetcode.com/problems/two-sum-iv-input-is-a-bst/) | Easy | 6+ months | 41.9 | ✅ Solved |  |  |  | [notes](06.%20Binary%20Search%20Tree/0653.%20Two%20Sum%20IV%20-%20Input%20is%20a%20BST/0653.%20Two%20Sum%20IV%20-%20Input%20is%20a%20BST.md) |
| 5 | [230. Kth Smallest Element in a BST](https://leetcode.com/problems/kth-smallest-element-in-a-bst/) | Medium | 6+ months | 25.1 | ✅ Solved |  |  |  | [notes](06.%20Binary%20Search%20Tree/0230.%20Kth%20Smallest%20Element%20in%20a%20BST/0230.%20Kth%20Smallest%20Element%20in%20a%20BST.md) |
| 6 | [510. Inorder Successor in BST II](https://leetcode.com/problems/inorder-successor-in-bst-ii/) 🔒 | Medium | 6+ months | 13.2 | Todo |  |  |  | [notes](06.%20Binary%20Search%20Tree/0510.%20Inorder%20Successor%20in%20BST%20II/0510.%20Inorder%20Successor%20in%20BST%20II.md) |
| 7 | [700. Search in a Binary Search Tree](https://leetcode.com/problems/search-in-a-binary-search-tree/) | Easy | 6+ months | 12.9 | ✅ Solved |  |  |  | [notes](06.%20Binary%20Search%20Tree/0700.%20Search%20in%20a%20Binary%20Search%20Tree/0700.%20Search%20in%20a%20Binary%20Search%20Tree.md) |
| 8 | [783. Minimum Distance Between BST Nodes](https://leetcode.com/problems/minimum-distance-between-bst-nodes/) | Easy | 6+ months | 12.9 | Todo |  |  |  | [notes](06.%20Binary%20Search%20Tree/0783.%20Minimum%20Distance%20Between%20BST%20Nodes/0783.%20Minimum%20Distance%20Between%20BST%20Nodes.md) |
| 9 | [450. Delete Node in a BST](https://leetcode.com/problems/delete-node-in-a-bst/) | Medium | 6+ months | 11.6 | ✅ Solved |  |  |  | [notes](06.%20Binary%20Search%20Tree/0450.%20Delete%20Node%20in%20a%20BST/0450.%20Delete%20Node%20in%20a%20BST.md) |
| 10 | [99. Recover Binary Search Tree](https://leetcode.com/problems/recover-binary-search-tree/) | Medium | 6+ months | 9.1 | ✅ Solved |  |  |  | [notes](06.%20Binary%20Search%20Tree/0099.%20Recover%20Binary%20Search%20Tree/0099.%20Recover%20Binary%20Search%20Tree.md) |
| 11 | [530. Minimum Absolute Difference in BST](https://leetcode.com/problems/minimum-absolute-difference-in-bst/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](06.%20Binary%20Search%20Tree/0530.%20Minimum%20Absolute%20Difference%20in%20BST/0530.%20Minimum%20Absolute%20Difference%20in%20BST.md) |
| 12 | [538. Convert BST to Greater Tree](https://leetcode.com/problems/convert-bst-to-greater-tree/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20Binary%20Search%20Tree/0538.%20Convert%20BST%20to%20Greater%20Tree/0538.%20Convert%20BST%20to%20Greater%20Tree.md) |
| 13 | [701. Insert into a Binary Search Tree](https://leetcode.com/problems/insert-into-a-binary-search-tree/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](06.%20Binary%20Search%20Tree/0701.%20Insert%20into%20a%20Binary%20Search%20Tree/0701.%20Insert%20into%20a%20Binary%20Search%20Tree.md) |
| 14 | [1305. All Elements in Two Binary Search Trees](https://leetcode.com/problems/all-elements-in-two-binary-search-trees/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20Binary%20Search%20Tree/1305.%20All%20Elements%20in%20Two%20Binary%20Search%20Trees/1305.%20All%20Elements%20in%20Two%20Binary%20Search%20Trees.md) |
| 15 | [285. Inorder Successor in BST](https://leetcode.com/problems/inorder-successor-in-bst/) 🔒 | Medium | 6+ months | 36.1 | Todo |  |  |  | [notes](06.%20Binary%20Search%20Tree/0285.%20Inorder%20Successor%20in%20BST/0285.%20Inorder%20Successor%20in%20BST.md) |

## 07. Tree Construction

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [108. Convert Sorted Array to Binary Search Tree](https://leetcode.com/problems/convert-sorted-array-to-binary-search-tree/) | Easy | 6 months | 25.6 | ✅ Solved |  |  |  | [notes](07.%20Tree%20Construction/0108.%20Convert%20Sorted%20Array%20to%20Binary%20Search%20Tree/0108.%20Convert%20Sorted%20Array%20to%20Binary%20Search%20Tree.md) |
| 2 | [536. Construct Binary Tree from String](https://leetcode.com/problems/construct-binary-tree-from-string/) 🔒 | Medium | 6+ months | 38.2 | Todo |  |  |  | [notes](07.%20Tree%20Construction/0536.%20Construct%20Binary%20Tree%20from%20String/0536.%20Construct%20Binary%20Tree%20from%20String.md) |
| 3 | [1382. Balance a Binary Search Tree](https://leetcode.com/problems/balance-a-binary-search-tree/) | Medium | 6+ months | 16.1 | Todo |  |  |  | [notes](07.%20Tree%20Construction/1382.%20Balance%20a%20Binary%20Search%20Tree/1382.%20Balance%20a%20Binary%20Search%20Tree.md) |
| 4 | [109. Convert Sorted List to Binary Search Tree](https://leetcode.com/problems/convert-sorted-list-to-binary-search-tree/) | Medium | 6+ months | 14.0 | Todo |  |  |  | [notes](07.%20Tree%20Construction/0109.%20Convert%20Sorted%20List%20to%20Binary%20Search%20Tree/0109.%20Convert%20Sorted%20List%20to%20Binary%20Search%20Tree.md) |
| 5 | [105. Construct Binary Tree from Preorder and Inorder Traversal](https://leetcode.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/) | Medium | 6+ months | 12.0 | ✅ Solved |  |  |  | [notes](07.%20Tree%20Construction/0105.%20Construct%20Binary%20Tree%20from%20Preorder%20and%20Inorder%20Traversal/0105.%20Construct%20Binary%20Tree%20from%20Preorder%20and%20Inorder%20Traversal.md) |
| 6 | [1008. Construct Binary Search Tree from Preorder Traversal](https://leetcode.com/problems/construct-binary-search-tree-from-preorder-traversal/) | Medium | 6+ months | 11.8 | Todo |  |  |  | [notes](07.%20Tree%20Construction/1008.%20Construct%20Binary%20Search%20Tree%20from%20Preorder%20Traversal/1008.%20Construct%20Binary%20Search%20Tree%20from%20Preorder%20Traversal.md) |
| 7 | [2196. Create Binary Tree From Descriptions](https://leetcode.com/problems/create-binary-tree-from-descriptions/) | Medium | 6+ months | 5.3 | Todo |  |  |  | [notes](07.%20Tree%20Construction/2196.%20Create%20Binary%20Tree%20From%20Descriptions/2196.%20Create%20Binary%20Tree%20From%20Descriptions.md) |
| 8 | [1028. Recover a Tree From Preorder Traversal](https://leetcode.com/problems/recover-a-tree-from-preorder-traversal/) | Hard | 6+ months | 5.2 | Todo |  |  |  | [notes](07.%20Tree%20Construction/1028.%20Recover%20a%20Tree%20From%20Preorder%20Traversal/1028.%20Recover%20a%20Tree%20From%20Preorder%20Traversal.md) |
| 9 | [106. Construct Binary Tree from Inorder and Postorder Traversal](https://leetcode.com/problems/construct-binary-tree-from-inorder-and-postorder-traversal/) | Medium | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](07.%20Tree%20Construction/0106.%20Construct%20Binary%20Tree%20from%20Inorder%20and%20Postorder%20Traversal/0106.%20Construct%20Binary%20Tree%20from%20Inorder%20and%20Postorder%20Traversal.md) |
| 10 | [654. Maximum Binary Tree](https://leetcode.com/problems/maximum-binary-tree/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](07.%20Tree%20Construction/0654.%20Maximum%20Binary%20Tree/0654.%20Maximum%20Binary%20Tree.md) |

## 08. Tree Views & Vertical Order

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [199. Binary Tree Right Side View](https://leetcode.com/problems/binary-tree-right-side-view/) | Medium | 6 months | 86.1 | ✅ Solved |  |  |  | [notes](08.%20Tree%20Views%20%26%20Vertical%20Order/0199.%20Binary%20Tree%20Right%20Side%20View/0199.%20Binary%20Tree%20Right%20Side%20View.md) |
| 2 | [987. Vertical Order Traversal of a Binary Tree](https://leetcode.com/problems/vertical-order-traversal-of-a-binary-tree/) | Hard | 6 months | 63.4 | ✅ Solved |  |  |  | [notes](08.%20Tree%20Views%20%26%20Vertical%20Order/0987.%20Vertical%20Order%20Traversal%20of%20a%20Binary%20Tree/0987.%20Vertical%20Order%20Traversal%20of%20a%20Binary%20Tree.md) |
| 3 | [314. Binary Tree Vertical Order Traversal](https://leetcode.com/problems/binary-tree-vertical-order-traversal/) 🔒 | Medium | 6+ months | 92.8 | Todo |  |  |  | [notes](08.%20Tree%20Views%20%26%20Vertical%20Order/0314.%20Binary%20Tree%20Vertical%20Order%20Traversal/0314.%20Binary%20Tree%20Vertical%20Order%20Traversal.md) |
| 4 | [545. Boundary of Binary Tree](https://leetcode.com/problems/boundary-of-binary-tree/) 🔒 | Medium | 6+ months | 46.2 | Todo |  |  |  | [notes](08.%20Tree%20Views%20%26%20Vertical%20Order/0545.%20Boundary%20of%20Binary%20Tree/0545.%20Boundary%20of%20Binary%20Tree.md) |

## 09. Serialize & Deserialize

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [297. Serialize and Deserialize Binary Tree](https://leetcode.com/problems/serialize-and-deserialize-binary-tree/) | Hard | 6 months | 49.3 | ✅ Solved |  |  |  | [notes](09.%20Serialize%20%26%20Deserialize/0297.%20Serialize%20and%20Deserialize%20Binary%20Tree/0297.%20Serialize%20and%20Deserialize%20Binary%20Tree.md) |
| 2 | [606. Construct String from Binary Tree](https://leetcode.com/problems/construct-string-from-binary-tree/) | Medium | 6+ months | 5.6 | Todo |  |  |  | [notes](09.%20Serialize%20%26%20Deserialize/0606.%20Construct%20String%20from%20Binary%20Tree/0606.%20Construct%20String%20from%20Binary%20Tree.md) |
| 3 | [652. Find Duplicate Subtrees](https://leetcode.com/problems/find-duplicate-subtrees/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](09.%20Serialize%20%26%20Deserialize/0652.%20Find%20Duplicate%20Subtrees/0652.%20Find%20Duplicate%20Subtrees.md) |

## 10. Tree Modification

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [226. Invert Binary Tree](https://leetcode.com/problems/invert-binary-tree/) | Easy | 6 months | 32.0 | ✅ Solved |  |  |  | [notes](10.%20Tree%20Modification/0226.%20Invert%20Binary%20Tree/0226.%20Invert%20Binary%20Tree.md) |
| 2 | [426. Convert Binary Search Tree to Sorted Doubly Linked List](https://leetcode.com/problems/convert-binary-search-tree-to-sorted-doubly-linked-list/) 🔒 | Medium | 6+ months | 57.4 | Todo |  |  |  | [notes](10.%20Tree%20Modification/0426.%20Convert%20Binary%20Search%20Tree%20to%20Sorted%20Doubly%20Linked%20List/0426.%20Convert%20Binary%20Search%20Tree%20to%20Sorted%20Doubly%20Linked%20List.md) |
| 3 | [114. Flatten Binary Tree to Linked List](https://leetcode.com/problems/flatten-binary-tree-to-linked-list/) | Medium | 6+ months | 27.0 | ✅ Solved |  |  |  | [notes](10.%20Tree%20Modification/0114.%20Flatten%20Binary%20Tree%20to%20Linked%20List/0114.%20Flatten%20Binary%20Tree%20to%20Linked%20List.md) |
| 4 | [1110. Delete Nodes And Return Forest](https://leetcode.com/problems/delete-nodes-and-return-forest/) | Medium | 6+ months | 15.0 | Todo |  |  |  | [notes](10.%20Tree%20Modification/1110.%20Delete%20Nodes%20And%20Return%20Forest/1110.%20Delete%20Nodes%20And%20Return%20Forest.md) |
| 5 | [617. Merge Two Binary Trees](https://leetcode.com/problems/merge-two-binary-trees/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](10.%20Tree%20Modification/0617.%20Merge%20Two%20Binary%20Trees/0617.%20Merge%20Two%20Binary%20Trees.md) |
| 6 | [814. Binary Tree Pruning](https://leetcode.com/problems/binary-tree-pruning/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](10.%20Tree%20Modification/0814.%20Binary%20Tree%20Pruning/0814.%20Binary%20Tree%20Pruning.md) |
| 7 | [998. Maximum Binary Tree II](https://leetcode.com/problems/maximum-binary-tree-ii/) | Medium | 6+ months | 36.1 | Todo |  |  |  | [notes](10.%20Tree%20Modification/0998.%20Maximum%20Binary%20Tree%20II/0998.%20Maximum%20Binary%20Tree%20II.md) |

## 11. N-ary Tree

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [1522. Diameter of N-Ary Tree](https://leetcode.com/problems/diameter-of-n-ary-tree/) 🔒 | Medium | 6+ months | 38.4 | Todo |  |  |  | [notes](11.%20N-ary%20Tree/1522.%20Diameter%20of%20N-Ary%20Tree/1522.%20Diameter%20of%20N-Ary%20Tree.md) |
| 2 | [1506. Find Root of N-Ary Tree](https://leetcode.com/problems/find-root-of-n-ary-tree/) 🔒 | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](11.%20N-ary%20Tree/1506.%20Find%20Root%20of%20N-Ary%20Tree/1506.%20Find%20Root%20of%20N-Ary%20Tree.md) |

## 12. Tree as Graph (Parent Pointers, Distance K)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [863. All Nodes Distance K in Binary Tree](https://leetcode.com/problems/all-nodes-distance-k-in-binary-tree/) | Medium | 6+ months | 61.5 | ✅ Solved |  |  |  | [notes](12.%20Tree%20as%20Graph%20%28Parent%20Pointers%2C%20Distance%20K%29/0863.%20All%20Nodes%20Distance%20K%20in%20Binary%20Tree/0863.%20All%20Nodes%20Distance%20K%20in%20Binary%20Tree.md) |
| 2 | [1443. Minimum Time to Collect All Apples in a Tree](https://leetcode.com/problems/minimum-time-to-collect-all-apples-in-a-tree/) | Medium | 6+ months | 44.0 | Todo |  |  |  | [notes](12.%20Tree%20as%20Graph%20%28Parent%20Pointers%2C%20Distance%20K%29/1443.%20Minimum%20Time%20to%20Collect%20All%20Apples%20in%20a%20Tree/1443.%20Minimum%20Time%20to%20Collect%20All%20Apples%20in%20a%20Tree.md) |
| 3 | [1245. Tree Diameter](https://leetcode.com/problems/tree-diameter/) 🔒 | Medium | 6+ months | 8.2 | Todo |  |  |  | [notes](12.%20Tree%20as%20Graph%20%28Parent%20Pointers%2C%20Distance%20K%29/1245.%20Tree%20Diameter/1245.%20Tree%20Diameter.md) |
| 4 | [2322. Minimum Score After Removals on a Tree](https://leetcode.com/problems/minimum-score-after-removals-on-a-tree/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](12.%20Tree%20as%20Graph%20%28Parent%20Pointers%2C%20Distance%20K%29/2322.%20Minimum%20Score%20After%20Removals%20on%20a%20Tree/2322.%20Minimum%20Score%20After%20Removals%20on%20a%20Tree.md) |
| 5 | [2477. Minimum Fuel Cost to Report to the Capital](https://leetcode.com/problems/minimum-fuel-cost-to-report-to-the-capital/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](12.%20Tree%20as%20Graph%20%28Parent%20Pointers%2C%20Distance%20K%29/2477.%20Minimum%20Fuel%20Cost%20to%20Report%20to%20the%20Capital/2477.%20Minimum%20Fuel%20Cost%20to%20Report%20to%20the%20Capital.md) |
| 6 | [2467. Most Profitable Path in a Tree](https://leetcode.com/problems/most-profitable-path-in-a-tree/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](12.%20Tree%20as%20Graph%20%28Parent%20Pointers%2C%20Distance%20K%29/2467.%20Most%20Profitable%20Path%20in%20a%20Tree/2467.%20Most%20Profitable%20Path%20in%20a%20Tree.md) |
