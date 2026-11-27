# 02. Strings

[Back to Facebook](../README.md) · [Back to DSA Notes](../../../README.md)

65 Meta (Facebook) problems: 41 Easy, 17 Medium, 7 Hard, in 7 sub-patterns.

## Sub-patterns

| # | Sub-pattern | Questions | Easy | Medium | Hard | Last 3 Months | Solved | Most Asked |
|:---:|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---|
| 01 | [String Basics & Manipulation](#01-string-basics--manipulation) | 17 | 16 | 1 | 0 | 0 | 8 | 151. Reverse Words in a String, 1108. Defanging an IP Address, 1773. Count Items Matching a Rule |
| 02 | [Palindromes](#02-palindromes) | 11 | 6 | 5 | 0 | 2 | 5 | 680. Valid Palindrome II, 125. Valid Palindrome, 647. Palindromic Substrings |
| 03 | [Parsing & Validation](#03-parsing--validation) | 7 | 3 | 3 | 1 | 1 | 1 | 65. Valid Number, 13. Roman to Integer, 8. String to Integer (atoi) |
| 04 | [String Building & Formatting](#04-string-building--formatting) | 10 | 2 | 5 | 3 | 2 | 0 | 824. Goat Latin, 68. Text Justification, 38. Count and Say |
| 05 | [Anagrams & Character Counting](#05-anagrams--character-counting) | 1 | 1 | 0 | 0 | 1 | 1 | 242. Valid Anagram |
| 06 | [String Matching (KMP, Rabin-Karp, Z)](#06-string-matching-kmp-rabin-karp-z) | 10 | 6 | 1 | 3 | 2 | 1 | 28. Find the Index of the First Occurrence in a String, 796. Rotate String, 1967. Number of Strings That Appear as Substrings in Word |
| 07 | [String Comparison & Sorting](#07-string-comparison--sorting) | 9 | 7 | 2 | 0 | 1 | 3 | 14. Longest Common Prefix, 953. Verifying an Alien Dictionary, 1662. Check If Two String Arrays are Equivalent |

**Columns**

- **Last Asked**: most recent LeetCode window that lists the problem for Meta (30 days, 3 months, 6 months or 6+ months).
- **Frequency**: LeetCode frequency score (0-100) in the Meta "All" list.
- **Status**: your LeetCode status on the day this file was generated. 🔒 after a title means LeetCode Premium.
- **Logic / Key Idea, Time, Space**: fill these in as you solve. A rebuild keeps what you typed.
- **Notes**: link to the problem's notes file.

Inside each sub-pattern, rows are sorted by most recent window, then by frequency (highest first).

## 01. String Basics & Manipulation

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [151. Reverse Words in a String](https://leetcode.com/problems/reverse-words-in-a-string/) | Medium | 6 months | 39.3 | Todo |  |  |  | [notes](01.%20String%20Basics%20%26%20Manipulation/0151.%20Reverse%20Words%20in%20a%20String/0151.%20Reverse%20Words%20in%20a%20String.md) |
| 2 | [2667. Create Hello World Function](https://leetcode.com/problems/create-hello-world-function/) | Easy | 6 months | 27.2 | Todo |  |  |  | [notes](01.%20String%20Basics%20%26%20Manipulation/2667.%20Create%20Hello%20World%20Function/2667.%20Create%20Hello%20World%20Function.md) |
| 3 | [58. Length of Last Word](https://leetcode.com/problems/length-of-last-word/) | Easy | 6 months | 21.1 | ✅ Solved |  |  |  | [notes](01.%20String%20Basics%20%26%20Manipulation/0058.%20Length%20of%20Last%20Word/0058.%20Length%20of%20Last%20Word.md) |
| 4 | [1796. Second Largest Digit in a String](https://leetcode.com/problems/second-largest-digit-in-a-string/) | Easy | 6 months | 5.0 | Todo |  |  |  | [notes](01.%20String%20Basics%20%26%20Manipulation/1796.%20Second%20Largest%20Digit%20in%20a%20String/1796.%20Second%20Largest%20Digit%20in%20a%20String.md) |
| 5 | [1108. Defanging an IP Address](https://leetcode.com/problems/defanging-an-ip-address/) | Easy | 6+ months | 38.8 | ✅ Solved |  |  |  | [notes](01.%20String%20Basics%20%26%20Manipulation/1108.%20Defanging%20an%20IP%20Address/1108.%20Defanging%20an%20IP%20Address.md) |
| 6 | [696. Count Binary Substrings](https://leetcode.com/problems/count-binary-substrings/) | Easy | 6+ months | 12.2 | ✅ Solved |  |  |  | [notes](01.%20String%20Basics%20%26%20Manipulation/0696.%20Count%20Binary%20Substrings/0696.%20Count%20Binary%20Substrings.md) |
| 7 | [709. To Lower Case](https://leetcode.com/problems/to-lower-case/) | Easy | 6+ months | 10.2 | Todo |  |  |  | [notes](01.%20String%20Basics%20%26%20Manipulation/0709.%20To%20Lower%20Case/0709.%20To%20Lower%20Case.md) |
| 8 | [1446. Consecutive Characters](https://leetcode.com/problems/consecutive-characters/) | Easy | 6+ months | 8.7 | Todo |  |  |  | [notes](01.%20String%20Basics%20%26%20Manipulation/1446.%20Consecutive%20Characters/1446.%20Consecutive%20Characters.md) |
| 9 | [2942. Find Words Containing Character](https://leetcode.com/problems/find-words-containing-character/) | Easy | 6+ months | 8.6 | ✅ Solved |  |  |  | [notes](01.%20String%20Basics%20%26%20Manipulation/2942.%20Find%20Words%20Containing%20Character/2942.%20Find%20Words%20Containing%20Character.md) |
| 10 | [520. Detect Capital](https://leetcode.com/problems/detect-capital/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20String%20Basics%20%26%20Manipulation/0520.%20Detect%20Capital/0520.%20Detect%20Capital.md) |
| 11 | [2264. Largest 3-Same-Digit Number in String](https://leetcode.com/problems/largest-3-same-digit-number-in-string/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20String%20Basics%20%26%20Manipulation/2264.%20Largest%203-Same-Digit%20Number%20in%20String/2264.%20Largest%203-Same-Digit%20Number%20in%20String.md) |
| 12 | [3019. Number of Changing Keys](https://leetcode.com/problems/number-of-changing-keys/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](01.%20String%20Basics%20%26%20Manipulation/3019.%20Number%20of%20Changing%20Keys/3019.%20Number%20of%20Changing%20Keys.md) |
| 13 | [3110. Score of a String](https://leetcode.com/problems/score-of-a-string/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](01.%20String%20Basics%20%26%20Manipulation/3110.%20Score%20of%20a%20String/3110.%20Score%20of%20a%20String.md) |
| 14 | [3330. Find the Original Typed String I](https://leetcode.com/problems/find-the-original-typed-string-i/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20String%20Basics%20%26%20Manipulation/3330.%20Find%20the%20Original%20Typed%20String%20I/3330.%20Find%20the%20Original%20Typed%20String%20I.md) |
| 15 | [1773. Count Items Matching a Rule](https://leetcode.com/problems/count-items-matching-a-rule/) | Easy | 6+ months | 37.1 | ✅ Solved |  |  |  | [notes](01.%20String%20Basics%20%26%20Manipulation/1773.%20Count%20Items%20Matching%20a%20Rule/1773.%20Count%20Items%20Matching%20a%20Rule.md) |
| 16 | [2124. Check if All A's Appears Before All B's](https://leetcode.com/problems/check-if-all-as-appears-before-all-bs/) | Easy | 6+ months | 7.8 | ✅ Solved |  |  |  | [notes](01.%20String%20Basics%20%26%20Manipulation/2124.%20Check%20if%20All%20A%27s%20Appears%20Before%20All%20B%27s/2124.%20Check%20if%20All%20A%27s%20Appears%20Before%20All%20B%27s.md) |
| 17 | [1816. Truncate Sentence](https://leetcode.com/problems/truncate-sentence/) | Easy | 6+ months | 7.2 | Todo |  |  |  | [notes](01.%20String%20Basics%20%26%20Manipulation/1816.%20Truncate%20Sentence/1816.%20Truncate%20Sentence.md) |

## 02. Palindromes

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [5. Longest Palindromic Substring](https://leetcode.com/problems/longest-palindromic-substring/) | Medium | 30 days | 58.9 | ✅ Solved |  |  |  | [notes](02.%20Palindromes/0005.%20Longest%20Palindromic%20Substring/0005.%20Longest%20Palindromic%20Substring.md) |
| 2 | [125. Valid Palindrome](https://leetcode.com/problems/valid-palindrome/) | Easy | 3 months | 83.8 | ✅ Solved |  |  |  | [notes](02.%20Palindromes/0125.%20Valid%20Palindrome/0125.%20Valid%20Palindrome.md) |
| 3 | [409. Longest Palindrome](https://leetcode.com/problems/longest-palindrome/) | Easy | 6 months | 24.3 | Todo |  |  |  | [notes](02.%20Palindromes/0409.%20Longest%20Palindrome/0409.%20Longest%20Palindrome.md) |
| 4 | [3517. Smallest Palindromic Rearrangement I](https://leetcode.com/problems/smallest-palindromic-rearrangement-i/) | Medium | 6 months | 6.9 | Todo |  |  |  | [notes](02.%20Palindromes/3517.%20Smallest%20Palindromic%20Rearrangement%20I/3517.%20Smallest%20Palindromic%20Rearrangement%20I.md) |
| 5 | [680. Valid Palindrome II](https://leetcode.com/problems/valid-palindrome-ii/) | Easy | 6+ months | 95.7 | ✅ Solved |  |  |  | [notes](02.%20Palindromes/0680.%20Valid%20Palindrome%20II/0680.%20Valid%20Palindrome%20II.md) |
| 6 | [647. Palindromic Substrings](https://leetcode.com/problems/palindromic-substrings/) | Medium | 6+ months | 66.3 | ✅ Solved |  |  |  | [notes](02.%20Palindromes/0647.%20Palindromic%20Substrings/0647.%20Palindromic%20Substrings.md) |
| 7 | [246. Strobogrammatic Number](https://leetcode.com/problems/strobogrammatic-number/) 🔒 | Easy | 6+ months | 45.2 | Todo |  |  |  | [notes](02.%20Palindromes/0246.%20Strobogrammatic%20Number/0246.%20Strobogrammatic%20Number.md) |
| 8 | [266. Palindrome Permutation](https://leetcode.com/problems/palindrome-permutation/) 🔒 | Easy | 6+ months | 5.9 | Todo |  |  |  | [notes](02.%20Palindromes/0266.%20Palindrome%20Permutation/0266.%20Palindrome%20Permutation.md) |
| 9 | [1930. Unique Length-3 Palindromic Subsequences](https://leetcode.com/problems/unique-length-3-palindromic-subsequences/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Palindromes/1930.%20Unique%20Length-3%20Palindromic%20Subsequences/1930.%20Unique%20Length-3%20Palindromic%20Subsequences.md) |
| 10 | [2697. Lexicographically Smallest Palindrome](https://leetcode.com/problems/lexicographically-smallest-palindrome/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](02.%20Palindromes/2697.%20Lexicographically%20Smallest%20Palindrome/2697.%20Lexicographically%20Smallest%20Palindrome.md) |
| 11 | [3503. Longest Palindrome After Substring Concatenation I](https://leetcode.com/problems/longest-palindrome-after-substring-concatenation-i/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Palindromes/3503.%20Longest%20Palindrome%20After%20Substring%20Concatenation%20I/3503.%20Longest%20Palindrome%20After%20Substring%20Concatenation%20I.md) |

## 03. Parsing & Validation

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [13. Roman to Integer](https://leetcode.com/problems/roman-to-integer/) | Easy | 3 months | 58.2 | ✅ Solved |  |  |  | [notes](03.%20Parsing%20%26%20Validation/0013.%20Roman%20to%20Integer/0013.%20Roman%20to%20Integer.md) |
| 2 | [8. String to Integer (atoi)](https://leetcode.com/problems/string-to-integer-atoi/) | Medium | 6 months | 51.1 | Todo |  |  |  | [notes](03.%20Parsing%20%26%20Validation/0008.%20String%20to%20Integer%20%28atoi%29/0008.%20String%20to%20Integer%20%28atoi%29.md) |
| 3 | [65. Valid Number](https://leetcode.com/problems/valid-number/) | Hard | 6+ months | 64.0 | Todo |  |  |  | [notes](03.%20Parsing%20%26%20Validation/0065.%20Valid%20Number/0065.%20Valid%20Number.md) |
| 4 | [468. Validate IP Address](https://leetcode.com/problems/validate-ip-address/) | Medium | 6+ months | 7.3 | Todo |  |  |  | [notes](03.%20Parsing%20%26%20Validation/0468.%20Validate%20IP%20Address/0468.%20Validate%20IP%20Address.md) |
| 5 | [537. Complex Number Multiplication](https://leetcode.com/problems/complex-number-multiplication/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](03.%20Parsing%20%26%20Validation/0537.%20Complex%20Number%20Multiplication/0537.%20Complex%20Number%20Multiplication.md) |
| 6 | [2047. Number of Valid Words in a Sentence](https://leetcode.com/problems/number-of-valid-words-in-a-sentence/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](03.%20Parsing%20%26%20Validation/2047.%20Number%20of%20Valid%20Words%20in%20a%20Sentence/2047.%20Number%20of%20Valid%20Words%20in%20a%20Sentence.md) |
| 7 | [3136. Valid Word](https://leetcode.com/problems/valid-word/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](03.%20Parsing%20%26%20Validation/3136.%20Valid%20Word/3136.%20Valid%20Word.md) |

## 04. String Building & Formatting

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [824. Goat Latin](https://leetcode.com/problems/goat-latin/) | Easy | 3 months | 63.7 | Todo |  |  |  | [notes](04.%20String%20Building%20%26%20Formatting/0824.%20Goat%20Latin/0824.%20Goat%20Latin.md) |
| 2 | [6. Zigzag Conversion](https://leetcode.com/problems/zigzag-conversion/) | Medium | 3 months | 32.4 | Todo |  |  |  | [notes](04.%20String%20Building%20%26%20Formatting/0006.%20Zigzag%20Conversion/0006.%20Zigzag%20Conversion.md) |
| 3 | [38. Count and Say](https://leetcode.com/problems/count-and-say/) | Medium | 6 months | 42.6 | Todo |  |  |  | [notes](04.%20String%20Building%20%26%20Formatting/0038.%20Count%20and%20Say/0038.%20Count%20and%20Say.md) |
| 4 | [12. Integer to Roman](https://leetcode.com/problems/integer-to-roman/) | Medium | 6 months | 25.9 | Todo |  |  |  | [notes](04.%20String%20Building%20%26%20Formatting/0012.%20Integer%20to%20Roman/0012.%20Integer%20to%20Roman.md) |
| 5 | [68. Text Justification](https://leetcode.com/problems/text-justification/) | Hard | 6+ months | 45.5 | Todo |  |  |  | [notes](04.%20String%20Building%20%26%20Formatting/0068.%20Text%20Justification/0068.%20Text%20Justification.md) |
| 6 | [273. Integer to English Words](https://leetcode.com/problems/integer-to-english-words/) | Hard | 6+ months | 38.0 | Todo |  |  |  | [notes](04.%20String%20Building%20%26%20Formatting/0273.%20Integer%20to%20English%20Words/0273.%20Integer%20to%20English%20Words.md) |
| 7 | [271. Encode and Decode Strings](https://leetcode.com/problems/encode-and-decode-strings/) 🔒 | Medium | 6+ months | 6.0 | Todo |  |  |  | [notes](04.%20String%20Building%20%26%20Formatting/0271.%20Encode%20and%20Decode%20Strings/0271.%20Encode%20and%20Decode%20Strings.md) |
| 8 | [3163. String Compression III](https://leetcode.com/problems/string-compression-iii/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20String%20Building%20%26%20Formatting/3163.%20String%20Compression%20III/3163.%20String%20Compression%20III.md) |
| 9 | [1694. Reformat Phone Number](https://leetcode.com/problems/reformat-phone-number/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20String%20Building%20%26%20Formatting/1694.%20Reformat%20Phone%20Number/1694.%20Reformat%20Phone%20Number.md) |
| 10 | [3614. Process String with Special Operations II](https://leetcode.com/problems/process-string-with-special-operations-ii/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20String%20Building%20%26%20Formatting/3614.%20Process%20String%20with%20Special%20Operations%20II/3614.%20Process%20String%20with%20Special%20Operations%20II.md) |

## 05. Anagrams & Character Counting

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203; | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [242. Valid Anagram](https://leetcode.com/problems/valid-anagram/) | Easy | 3 months | 46.3 | ✅ Solved |  |  |  | [notes](05.%20Anagrams%20%26%20Character%20Counting/0242.%20Valid%20Anagram/0242.%20Valid%20Anagram.md) |

## 06. String Matching (KMP, Rabin-Karp, Z)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [28. Find the Index of the First Occurrence in a String](https://leetcode.com/problems/find-the-index-of-the-first-occurrence-in-a-string/) | Easy | 3 months | 50.5 | ✅ Solved |  |  |  | [notes](06.%20String%20Matching%20%28KMP%2C%20Rabin-Karp%2C%20Z%29/0028.%20Find%20the%20Index%20of%20the%20First%20Occurrence%20in%20a%20String/0028.%20Find%20the%20Index%20of%20the%20First%20Occurrence%20in%20a%20String.md) |
| 2 | [796. Rotate String](https://leetcode.com/problems/rotate-string/) | Easy | 3 months | 30.9 | Todo |  |  |  | [notes](06.%20String%20Matching%20%28KMP%2C%20Rabin-Karp%2C%20Z%29/0796.%20Rotate%20String/0796.%20Rotate%20String.md) |
| 3 | [1967. Number of Strings That Appear as Substrings in Word](https://leetcode.com/problems/number-of-strings-that-appear-as-substrings-in-word/) | Easy | 6 months | 19.7 | Todo |  |  |  | [notes](06.%20String%20Matching%20%28KMP%2C%20Rabin-Karp%2C%20Z%29/1967.%20Number%20of%20Strings%20That%20Appear%20as%20Substrings%20in%20Word/1967.%20Number%20of%20Strings%20That%20Appear%20as%20Substrings%20in%20Word.md) |
| 4 | [1044. Longest Duplicate Substring](https://leetcode.com/problems/longest-duplicate-substring/) | Hard | 6+ months | 11.8 | Todo |  |  |  | [notes](06.%20String%20Matching%20%28KMP%2C%20Rabin-Karp%2C%20Z%29/1044.%20Longest%20Duplicate%20Substring/1044.%20Longest%20Duplicate%20Substring.md) |
| 5 | [459. Repeated Substring Pattern](https://leetcode.com/problems/repeated-substring-pattern/) | Easy | 6+ months | 9.5 | Todo |  |  |  | [notes](06.%20String%20Matching%20%28KMP%2C%20Rabin-Karp%2C%20Z%29/0459.%20Repeated%20Substring%20Pattern/0459.%20Repeated%20Substring%20Pattern.md) |
| 6 | [1392. Longest Happy Prefix](https://leetcode.com/problems/longest-happy-prefix/) | Hard | 6+ months | 8.4 | Todo |  |  |  | [notes](06.%20String%20Matching%20%28KMP%2C%20Rabin-Karp%2C%20Z%29/1392.%20Longest%20Happy%20Prefix/1392.%20Longest%20Happy%20Prefix.md) |
| 7 | [1408. String Matching in an Array](https://leetcode.com/problems/string-matching-in-an-array/) | Easy | 6+ months | 8.4 | Todo |  |  |  | [notes](06.%20String%20Matching%20%28KMP%2C%20Rabin-Karp%2C%20Z%29/1408.%20String%20Matching%20in%20an%20Array/1408.%20String%20Matching%20in%20an%20Array.md) |
| 8 | [214. Shortest Palindrome](https://leetcode.com/problems/shortest-palindrome/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20String%20Matching%20%28KMP%2C%20Rabin-Karp%2C%20Z%29/0214.%20Shortest%20Palindrome/0214.%20Shortest%20Palindrome.md) |
| 9 | [686. Repeated String Match](https://leetcode.com/problems/repeated-string-match/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20String%20Matching%20%28KMP%2C%20Rabin-Karp%2C%20Z%29/0686.%20Repeated%20String%20Match/0686.%20Repeated%20String%20Match.md) |
| 10 | [2185. Counting Words With a Given Prefix](https://leetcode.com/problems/counting-words-with-a-given-prefix/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20String%20Matching%20%28KMP%2C%20Rabin-Karp%2C%20Z%29/2185.%20Counting%20Words%20With%20a%20Given%20Prefix/2185.%20Counting%20Words%20With%20a%20Given%20Prefix.md) |

## 07. String Comparison & Sorting

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [14. Longest Common Prefix](https://leetcode.com/problems/longest-common-prefix/) | Easy | 3 months | 59.7 | ✅ Solved |  |  |  | [notes](07.%20String%20Comparison%20%26%20Sorting/0014.%20Longest%20Common%20Prefix/0014.%20Longest%20Common%20Prefix.md) |
| 2 | [953. Verifying an Alien Dictionary](https://leetcode.com/problems/verifying-an-alien-dictionary/) | Easy | 6+ months | 40.3 | Todo |  |  |  | [notes](07.%20String%20Comparison%20%26%20Sorting/0953.%20Verifying%20an%20Alien%20Dictionary/0953.%20Verifying%20an%20Alien%20Dictionary.md) |
| 3 | [1662. Check If Two String Arrays are Equivalent](https://leetcode.com/problems/check-if-two-string-arrays-are-equivalent/) | Easy | 6+ months | 38.5 | ✅ Solved |  |  |  | [notes](07.%20String%20Comparison%20%26%20Sorting/1662.%20Check%20If%20Two%20String%20Arrays%20are%20Equivalent/1662.%20Check%20If%20Two%20String%20Arrays%20are%20Equivalent.md) |
| 4 | [1790. Check if One String Swap Can Make Strings Equal](https://leetcode.com/problems/check-if-one-string-swap-can-make-strings-equal/) | Easy | 6+ months | 37.4 | ✅ Solved |  |  |  | [notes](07.%20String%20Comparison%20%26%20Sorting/1790.%20Check%20if%20One%20String%20Swap%20Can%20Make%20Strings%20Equal/1790.%20Check%20if%20One%20String%20Swap%20Can%20Make%20Strings%20Equal.md) |
| 5 | [944. Delete Columns to Make Sorted](https://leetcode.com/problems/delete-columns-to-make-sorted/) | Easy | 6+ months | 13.6 | Todo |  |  |  | [notes](07.%20String%20Comparison%20%26%20Sorting/0944.%20Delete%20Columns%20to%20Make%20Sorted/0944.%20Delete%20Columns%20to%20Make%20Sorted.md) |
| 6 | [521. Longest Uncommon Subsequence I](https://leetcode.com/problems/longest-uncommon-subsequence-i/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](07.%20String%20Comparison%20%26%20Sorting/0521.%20Longest%20Uncommon%20Subsequence%20I/0521.%20Longest%20Uncommon%20Subsequence%20I.md) |
| 7 | [859. Buddy Strings](https://leetcode.com/problems/buddy-strings/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](07.%20String%20Comparison%20%26%20Sorting/0859.%20Buddy%20Strings/0859.%20Buddy%20Strings.md) |
| 8 | [3403. Find the Lexicographically Largest String From the Box I](https://leetcode.com/problems/find-the-lexicographically-largest-string-from-the-box-i/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](07.%20String%20Comparison%20%26%20Sorting/3403.%20Find%20the%20Lexicographically%20Largest%20String%20From%20the%20Box%20I/3403.%20Find%20the%20Lexicographically%20Largest%20String%20From%20the%20Box%20I.md) |
| 9 | [2452. Words Within Two Edits of Dictionary](https://leetcode.com/problems/words-within-two-edits-of-dictionary/) | Medium | 6+ months | 36.1 | Todo |  |  |  | [notes](07.%20String%20Comparison%20%26%20Sorting/2452.%20Words%20Within%20Two%20Edits%20of%20Dictionary/2452.%20Words%20Within%20Two%20Edits%20of%20Dictionary.md) |
