# 15. Tries - Meta (Facebook) Interview Questions

12 problems: 0 Easy, 8 Medium, 4 Hard. 4 sub-patterns.

[Back to Facebook](../README.md) · [Back to DSA Notes](../../../README.md)

## Sub-patterns

<table width="100%" style="width:100%">
<thead><tr><th>#</th><th>Name</th><th>Total</th><th>Easy</th><th>Medium</th><th>Hard</th><th>Last 30 Days</th><th>Last 3 Months</th><th>Last 6 Months</th><th>Solved</th></tr></thead>
<tbody>
<tr><td>1</td><td><a href="#01-basic-trie">Basic Trie</a></td><td>3</td><td>0</td><td>3</td><td>0</td><td>0</td><td>0</td><td>1</td><td>0</td></tr>
<tr><td>2</td><td><a href="#02-trie--dfs">Trie + DFS</a></td><td>3</td><td>0</td><td>2</td><td>1</td><td>0</td><td>0</td><td>1</td><td>0</td></tr>
<tr><td>3</td><td><a href="#03-prefix-search--autocomplete">Prefix Search &amp; Autocomplete</a></td><td>5</td><td>0</td><td>2</td><td>3</td><td>0</td><td>0</td><td>0</td><td>0</td></tr>
<tr><td>4</td><td><a href="#04-bitwise-trie-xor">Bitwise Trie (XOR)</a></td><td>1</td><td>0</td><td>1</td><td>0</td><td>0</td><td>0</td><td>0</td><td>0</td></tr>
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

## 01. Basic Trie

<table width="100%" style="width:100%">
<thead><tr><th>#</th><th>Problem</th><th>Difficulty</th><th>Sub-pattern</th><th>Last Asked</th><th>30 Days</th><th>3 Months</th><th>6 Months</th><th>6+ Months</th><th>Frequency</th><th>Premium</th><th>Status</th><th>Logic / Key Idea</th><th>Time</th><th>Space</th><th>Date Solved</th><th>Revisions</th><th>Confidence</th><th>Remarks</th><th>Topic Tags</th><th>Notes</th></tr></thead>
<tbody>
<tr><td>1</td><td><a href="https://leetcode.com/problems/implement-trie-prefix-tree/">208. Implement Trie (Prefix Tree)</a></td><td>Medium</td><td>Basic Trie</td><td>Last 6 months</td><td></td><td></td><td>✅</td><td>✅</td><td>42.9</td><td></td><td>Todo</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Hash Table, String, Design, Trie</td><td><a href="01.%20Basic%20Trie/0208.%20Implement%20Trie%20%28Prefix%20Tree%29/0208.%20Implement%20Trie%20%28Prefix%20Tree%29.md">notes</a></td></tr>
<tr><td>2</td><td><a href="https://leetcode.com/problems/remove-sub-folders-from-the-filesystem/">1233. Remove Sub-Folders from the Filesystem</a></td><td>Medium</td><td>Basic Trie</td><td>More than 6 months</td><td></td><td></td><td></td><td>✅</td><td>9.1</td><td></td><td>Todo</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Array, String, Depth-First Search, Trie</td><td><a href="01.%20Basic%20Trie/1233.%20Remove%20Sub-Folders%20from%20the%20Filesystem/1233.%20Remove%20Sub-Folders%20from%20the%20Filesystem.md">notes</a></td></tr>
<tr><td>3</td><td><a href="https://leetcode.com/problems/design-file-system/">1166. Design File System</a></td><td>Medium</td><td>Basic Trie</td><td>More than 6 months</td><td></td><td></td><td></td><td>✅</td><td>5.0</td><td>🔒</td><td>Todo</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Hash Table, String, Design, Trie</td><td><a href="01.%20Basic%20Trie/1166.%20Design%20File%20System/1166.%20Design%20File%20System.md">notes</a></td></tr>
</tbody>
</table>

## 02. Trie + DFS

<table width="100%" style="width:100%">
<thead><tr><th>#</th><th>Problem</th><th>Difficulty</th><th>Sub-pattern</th><th>Last Asked</th><th>30 Days</th><th>3 Months</th><th>6 Months</th><th>6+ Months</th><th>Frequency</th><th>Premium</th><th>Status</th><th>Logic / Key Idea</th><th>Time</th><th>Space</th><th>Date Solved</th><th>Revisions</th><th>Confidence</th><th>Remarks</th><th>Topic Tags</th><th>Notes</th></tr></thead>
<tbody>
<tr><td>1</td><td><a href="https://leetcode.com/problems/lexicographical-numbers/">386. Lexicographical Numbers</a></td><td>Medium</td><td>Trie + DFS</td><td>Last 6 months</td><td></td><td></td><td>✅</td><td>✅</td><td>9.7</td><td></td><td>Todo</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Depth-First Search, Trie</td><td><a href="02.%20Trie%20+%20DFS/0386.%20Lexicographical%20Numbers/0386.%20Lexicographical%20Numbers.md">notes</a></td></tr>
<tr><td>2</td><td><a href="https://leetcode.com/problems/word-search-ii/">212. Word Search II</a></td><td>Hard</td><td>Trie + DFS</td><td>More than 6 months</td><td></td><td></td><td></td><td>✅</td><td>10.4</td><td></td><td>Todo</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Array, String, Backtracking, Trie, Matrix</td><td><a href="02.%20Trie%20+%20DFS/0212.%20Word%20Search%20II/0212.%20Word%20Search%20II.md">notes</a></td></tr>
<tr><td>3</td><td><a href="https://leetcode.com/problems/design-add-and-search-words-data-structure/">211. Design Add and Search Words Data Structure</a></td><td>Medium</td><td>Trie + DFS</td><td>More than 6 months</td><td></td><td></td><td></td><td></td><td>37.5</td><td></td><td>Todo</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>String, Depth-First Search, Design, Trie</td><td><a href="02.%20Trie%20+%20DFS/0211.%20Design%20Add%20and%20Search%20Words%20Data%20Structure/0211.%20Design%20Add%20and%20Search%20Words%20Data%20Structure.md">notes</a></td></tr>
</tbody>
</table>

## 03. Prefix Search & Autocomplete

<table width="100%" style="width:100%">
<thead><tr><th>#</th><th>Problem</th><th>Difficulty</th><th>Sub-pattern</th><th>Last Asked</th><th>30 Days</th><th>3 Months</th><th>6 Months</th><th>6+ Months</th><th>Frequency</th><th>Premium</th><th>Status</th><th>Logic / Key Idea</th><th>Time</th><th>Space</th><th>Date Solved</th><th>Revisions</th><th>Confidence</th><th>Remarks</th><th>Topic Tags</th><th>Notes</th></tr></thead>
<tbody>
<tr><td>1</td><td><a href="https://leetcode.com/problems/design-search-autocomplete-system/">642. Design Search Autocomplete System</a></td><td>Hard</td><td>Prefix Search &amp; Autocomplete</td><td>More than 6 months</td><td></td><td></td><td></td><td>✅</td><td>36.1</td><td>🔒</td><td>Todo</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>String, Depth-First Search, Design, Trie, Sorting, Heap (Priority Queue), Data Stream</td><td><a href="03.%20Prefix%20Search%20%26%20Autocomplete/0642.%20Design%20Search%20Autocomplete%20System/0642.%20Design%20Search%20Autocomplete%20System.md">notes</a></td></tr>
<tr><td>2</td><td><a href="https://leetcode.com/problems/find-the-length-of-the-longest-common-prefix/">3043. Find the Length of the Longest Common Prefix</a></td><td>Medium</td><td>Prefix Search &amp; Autocomplete</td><td>More than 6 months</td><td></td><td></td><td></td><td>✅</td><td>13.0</td><td></td><td>Todo</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Array, Hash Table, String, Trie</td><td><a href="03.%20Prefix%20Search%20%26%20Autocomplete/3043.%20Find%20the%20Length%20of%20the%20Longest%20Common%20Prefix/3043.%20Find%20the%20Length%20of%20the%20Longest%20Common%20Prefix.md">notes</a></td></tr>
<tr><td>3</td><td><a href="https://leetcode.com/problems/stream-of-characters/">1032. Stream of Characters</a></td><td>Hard</td><td>Prefix Search &amp; Autocomplete</td><td>More than 6 months</td><td></td><td></td><td></td><td>✅</td><td>5.1</td><td></td><td>Todo</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Array, String, Design, Trie, Data Stream, Aho–Corasick Algorithm</td><td><a href="03.%20Prefix%20Search%20%26%20Autocomplete/1032.%20Stream%20of%20Characters/1032.%20Stream%20of%20Characters.md">notes</a></td></tr>
<tr><td>4</td><td><a href="https://leetcode.com/problems/search-suggestions-system/">1268. Search Suggestions System</a></td><td>Medium</td><td>Prefix Search &amp; Autocomplete</td><td>More than 6 months</td><td></td><td></td><td></td><td>✅</td><td>5.0</td><td></td><td>Todo</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Array, String, Binary Search, Trie, Sorting, Heap (Priority Queue)</td><td><a href="03.%20Prefix%20Search%20%26%20Autocomplete/1268.%20Search%20Suggestions%20System/1268.%20Search%20Suggestions%20System.md">notes</a></td></tr>
<tr><td>5</td><td><a href="https://leetcode.com/problems/prefix-and-suffix-search/">745. Prefix and Suffix Search</a></td><td>Hard</td><td>Prefix Search &amp; Autocomplete</td><td>More than 6 months</td><td></td><td></td><td></td><td></td><td>37.3</td><td></td><td>Todo</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Array, Hash Table, String, Design, Trie</td><td><a href="03.%20Prefix%20Search%20%26%20Autocomplete/0745.%20Prefix%20and%20Suffix%20Search/0745.%20Prefix%20and%20Suffix%20Search.md">notes</a></td></tr>
</tbody>
</table>

## 04. Bitwise Trie (XOR)

<table width="100%" style="width:100%">
<thead><tr><th>#</th><th>Problem</th><th>Difficulty</th><th>Sub-pattern</th><th>Last Asked</th><th>30 Days</th><th>3 Months</th><th>6 Months</th><th>6+ Months</th><th>Frequency</th><th>Premium</th><th>Status</th><th>Logic / Key Idea</th><th>Time</th><th>Space</th><th>Date Solved</th><th>Revisions</th><th>Confidence</th><th>Remarks</th><th>Topic Tags</th><th>Notes</th></tr></thead>
<tbody>
<tr><td>1</td><td><a href="https://leetcode.com/problems/maximum-xor-of-two-numbers-in-an-array/">421. Maximum XOR of Two Numbers in an Array</a></td><td>Medium</td><td>Bitwise Trie (XOR)</td><td>More than 6 months</td><td></td><td></td><td></td><td>✅</td><td>6.3</td><td></td><td>Todo</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>Array, Hash Table, Bit Manipulation, Trie</td><td><a href="04.%20Bitwise%20Trie%20%28XOR%29/0421.%20Maximum%20XOR%20of%20Two%20Numbers%20in%20an%20Array/0421.%20Maximum%20XOR%20of%20Two%20Numbers%20in%20an%20Array.md">notes</a></td></tr>
</tbody>
</table>
