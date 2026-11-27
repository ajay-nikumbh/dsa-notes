# 15. Tries

[Back to Google](../README.md) · [Back to DSA Notes](../../../README.md)

22 Google problems: 0 Easy, 11 Medium, 11 Hard, in 4 sub-patterns.

## Sub-patterns

| # | Sub-pattern | Questions | Easy | Medium | Hard | Last 3 Months | Solved | Most Asked |
|:---:|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---|
| 01 | [Basic Trie](#01-basic-trie) | 6 | 0 | 4 | 2 | 0 | 0 | 208. Implement Trie (Prefix Tree), 1233. Remove Sub-Folders from the Filesystem, 336. Palindrome Pairs |
| 02 | [Trie + DFS](#02-trie--dfs) | 6 | 0 | 3 | 3 | 0 | 0 | 212. Word Search II, 676. Implement Magic Dictionary, 425. Word Squares |
| 03 | [Prefix Search & Autocomplete](#03-prefix-search--autocomplete) | 8 | 0 | 3 | 5 | 0 | 0 | 1032. Stream of Characters, 3093. Longest Common Suffix Queries, 2416. Sum of Prefix Scores of Strings |
| 04 | [Bitwise Trie (XOR)](#04-bitwise-trie-xor) | 2 | 0 | 1 | 1 | 1 | 0 | 421. Maximum XOR of Two Numbers in an Array, 1707. Maximum XOR With an Element From Array |

**Columns**

- **Last Asked**: most recent LeetCode window that lists the problem for Google (30 days, 3 months, 6 months, 6+ months).
- **Frequency**: LeetCode frequency score (0-100) in the Google "All" list.
- **Status**: your LeetCode status on the day this file was generated. 🔒 after a title means LeetCode Premium.
- **Logic / Key Idea, Time, Space**: fill these in as you solve. A rebuild keeps what you typed.
- **Notes**: link to the problem's notes file.

Inside each sub-pattern, rows are sorted by most recent window, then by frequency (highest first).

## 01. Basic Trie

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [208. Implement Trie (Prefix Tree)](https://leetcode.com/problems/implement-trie-prefix-tree/) | Medium | 6 months | 41.3 | Todo |  |  |  | [notes](01.%20Basic%20Trie/0208.%20Implement%20Trie%20%28Prefix%20Tree%29/0208.%20Implement%20Trie%20%28Prefix%20Tree%29.md) |
| 2 | [1233. Remove Sub-Folders from the Filesystem](https://leetcode.com/problems/remove-sub-folders-from-the-filesystem/) | Medium | 6+ months | 34.6 | Todo |  |  |  | [notes](01.%20Basic%20Trie/1233.%20Remove%20Sub-Folders%20from%20the%20Filesystem/1233.%20Remove%20Sub-Folders%20from%20the%20Filesystem.md) |
| 3 | [336. Palindrome Pairs](https://leetcode.com/problems/palindrome-pairs/) | Hard | 6+ months | 32.2 | Todo |  |  |  | [notes](01.%20Basic%20Trie/0336.%20Palindrome%20Pairs/0336.%20Palindrome%20Pairs.md) |
| 4 | [588. Design In-Memory File System](https://leetcode.com/problems/design-in-memory-file-system/) 🔒 | Hard | 6+ months | 12.5 | Todo |  |  |  | [notes](01.%20Basic%20Trie/0588.%20Design%20In-Memory%20File%20System/0588.%20Design%20In-Memory%20File%20System.md) |
| 5 | [1166. Design File System](https://leetcode.com/problems/design-file-system/) 🔒 | Medium | 6+ months | 9.7 | Todo |  |  |  | [notes](01.%20Basic%20Trie/1166.%20Design%20File%20System/1166.%20Design%20File%20System.md) |
| 6 | [1858. Longest Word With All Prefixes](https://leetcode.com/problems/longest-word-with-all-prefixes/) 🔒 | Medium | 6+ months | 28.8 | Todo |  |  |  | [notes](01.%20Basic%20Trie/1858.%20Longest%20Word%20With%20All%20Prefixes/1858.%20Longest%20Word%20With%20All%20Prefixes.md) |

## 02. Trie + DFS

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [211. Design Add and Search Words Data Structure](https://leetcode.com/problems/design-add-and-search-words-data-structure/) | Medium | 6 months | 18.9 | Todo |  |  |  | [notes](02.%20Trie%20%2B%20DFS/0211.%20Design%20Add%20and%20Search%20Words%20Data%20Structure/0211.%20Design%20Add%20and%20Search%20Words%20Data%20Structure.md) |
| 2 | [212. Word Search II](https://leetcode.com/problems/word-search-ii/) | Hard | 6+ months | 40.8 | Todo |  |  |  | [notes](02.%20Trie%20%2B%20DFS/0212.%20Word%20Search%20II/0212.%20Word%20Search%20II.md) |
| 3 | [676. Implement Magic Dictionary](https://leetcode.com/problems/implement-magic-dictionary/) | Medium | 6+ months | 32.9 | Todo |  |  |  | [notes](02.%20Trie%20%2B%20DFS/0676.%20Implement%20Magic%20Dictionary/0676.%20Implement%20Magic%20Dictionary.md) |
| 4 | [440. K-th Smallest in Lexicographical Order](https://leetcode.com/problems/k-th-smallest-in-lexicographical-order/) | Hard | 6+ months | 16.9 | Todo |  |  |  | [notes](02.%20Trie%20%2B%20DFS/0440.%20K-th%20Smallest%20in%20Lexicographical%20Order/0440.%20K-th%20Smallest%20in%20Lexicographical%20Order.md) |
| 5 | [386. Lexicographical Numbers](https://leetcode.com/problems/lexicographical-numbers/) | Medium | 6+ months | 6.3 | Todo |  |  |  | [notes](02.%20Trie%20%2B%20DFS/0386.%20Lexicographical%20Numbers/0386.%20Lexicographical%20Numbers.md) |
| 6 | [425. Word Squares](https://leetcode.com/problems/word-squares/) 🔒 | Hard | 6+ months | 28.8 | Todo |  |  |  | [notes](02.%20Trie%20%2B%20DFS/0425.%20Word%20Squares/0425.%20Word%20Squares.md) |

## 03. Prefix Search & Autocomplete

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [3043. Find the Length of the Longest Common Prefix](https://leetcode.com/problems/find-the-length-of-the-longest-common-prefix/) | Medium | 6 months | 20.5 | Todo |  |  |  | [notes](03.%20Prefix%20Search%20%26%20Autocomplete/3043.%20Find%20the%20Length%20of%20the%20Longest%20Common%20Prefix/3043.%20Find%20the%20Length%20of%20the%20Longest%20Common%20Prefix.md) |
| 2 | [1032. Stream of Characters](https://leetcode.com/problems/stream-of-characters/) | Hard | 6+ months | 32.5 | Todo |  |  |  | [notes](03.%20Prefix%20Search%20%26%20Autocomplete/1032.%20Stream%20of%20Characters/1032.%20Stream%20of%20Characters.md) |
| 3 | [642. Design Search Autocomplete System](https://leetcode.com/problems/design-search-autocomplete-system/) 🔒 | Hard | 6+ months | 23.5 | Todo |  |  |  | [notes](03.%20Prefix%20Search%20%26%20Autocomplete/0642.%20Design%20Search%20Autocomplete%20System/0642.%20Design%20Search%20Autocomplete%20System.md) |
| 4 | [1268. Search Suggestions System](https://leetcode.com/problems/search-suggestions-system/) | Medium | 6+ months | 10.2 | Todo |  |  |  | [notes](03.%20Prefix%20Search%20%26%20Autocomplete/1268.%20Search%20Suggestions%20System/1268.%20Search%20Suggestions%20System.md) |
| 5 | [648. Replace Words](https://leetcode.com/problems/replace-words/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](03.%20Prefix%20Search%20%26%20Autocomplete/0648.%20Replace%20Words/0648.%20Replace%20Words.md) |
| 6 | [745. Prefix and Suffix Search](https://leetcode.com/problems/prefix-and-suffix-search/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](03.%20Prefix%20Search%20%26%20Autocomplete/0745.%20Prefix%20and%20Suffix%20Search/0745.%20Prefix%20and%20Suffix%20Search.md) |
| 7 | [3093. Longest Common Suffix Queries](https://leetcode.com/problems/longest-common-suffix-queries/) | Hard | 6+ months | 30.1 | Todo |  |  |  | [notes](03.%20Prefix%20Search%20%26%20Autocomplete/3093.%20Longest%20Common%20Suffix%20Queries/3093.%20Longest%20Common%20Suffix%20Queries.md) |
| 8 | [2416. Sum of Prefix Scores of Strings](https://leetcode.com/problems/sum-of-prefix-scores-of-strings/) | Hard | 6+ months | 28.8 | Todo |  |  |  | [notes](03.%20Prefix%20Search%20%26%20Autocomplete/2416.%20Sum%20of%20Prefix%20Scores%20of%20Strings/2416.%20Sum%20of%20Prefix%20Scores%20of%20Strings.md) |

## 04. Bitwise Trie (XOR)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [421. Maximum XOR of Two Numbers in an Array](https://leetcode.com/problems/maximum-xor-of-two-numbers-in-an-array/) | Medium | 3 months | 45.1 | Todo |  |  |  | [notes](04.%20Bitwise%20Trie%20%28XOR%29/0421.%20Maximum%20XOR%20of%20Two%20Numbers%20in%20an%20Array/0421.%20Maximum%20XOR%20of%20Two%20Numbers%20in%20an%20Array.md) |
| 2 | [1707. Maximum XOR With an Element From Array](https://leetcode.com/problems/maximum-xor-with-an-element-from-array/) | Hard | 6+ months | 32.3 | Todo |  |  |  | [notes](04.%20Bitwise%20Trie%20%28XOR%29/1707.%20Maximum%20XOR%20With%20an%20Element%20From%20Array/1707.%20Maximum%20XOR%20With%20an%20Element%20From%20Array.md) |
