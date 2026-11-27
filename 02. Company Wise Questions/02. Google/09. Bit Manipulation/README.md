# 09. Bit Manipulation

[Back to Google](../README.md) · [Back to DSA Notes](../../../README.md)

57 Google problems: 24 Easy, 28 Medium, 5 Hard, in 4 sub-patterns.

## Sub-patterns

| # | Sub-pattern | Questions | Easy | Medium | Hard | Last 3 Months | Solved | Most Asked |
|:---:|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---|
| 01 | [Bit Basics & Counting](#01-bit-basics--counting) | 36 | 17 | 16 | 3 | 7 | 1 | 231. Power of Two, 29. Divide Two Integers, 397. Integer Replacement |
| 02 | [XOR Tricks](#02-xor-tricks) | 10 | 6 | 4 | 0 | 2 | 5 | 136. Single Number, 268. Missing Number, 389. Find the Difference |
| 03 | [Bitmask Enumeration](#03-bitmask-enumeration) | 8 | 1 | 5 | 2 | 0 | 0 | 318. Maximum Product of Word Lengths, 401. Binary Watch, 3858. Minimum Bitwise OR From Grid |
| 04 | [Bitwise Operations on Ranges](#04-bitwise-operations-on-ranges) | 3 | 0 | 3 | 0 | 0 | 0 | 201. Bitwise AND of Numbers Range, 898. Bitwise ORs of Subarrays, 2411. Smallest Subarrays With Maximum Bitwise OR |

**Columns**

- **Last Asked**: most recent LeetCode window that lists the problem for Google (30 days, 3 months, 6 months, 6+ months).
- **Frequency**: LeetCode frequency score (0-100) in the Google "All" list.
- **Status**: your LeetCode status on the day this file was generated. 🔒 after a title means LeetCode Premium.
- **Logic / Key Idea, Time, Space**: fill these in as you solve. A rebuild keeps what you typed.
- **Notes**: link to the problem's notes file.

Inside each sub-pattern, rows are sorted by most recent window, then by frequency (highest first).

## 01. Bit Basics & Counting

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [231. Power of Two](https://leetcode.com/problems/power-of-two/) | Easy | 30 days | 51.9 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/0231.%20Power%20of%20Two/0231.%20Power%20of%20Two.md) |
| 2 | [29. Divide Two Integers](https://leetcode.com/problems/divide-two-integers/) | Medium | 3 months | 39.4 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/0029.%20Divide%20Two%20Integers/0029.%20Divide%20Two%20Integers.md) |
| 3 | [371. Sum of Two Integers](https://leetcode.com/problems/sum-of-two-integers/) | Medium | 3 months | 30.7 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/0371.%20Sum%20of%20Two%20Integers/0371.%20Sum%20of%20Two%20Integers.md) |
| 4 | [191. Number of 1 Bits](https://leetcode.com/problems/number-of-1-bits/) | Easy | 3 months | 22.3 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/0191.%20Number%20of%201%20Bits/0191.%20Number%20of%201%20Bits.md) |
| 5 | [693. Binary Number with Alternating Bits](https://leetcode.com/problems/binary-number-with-alternating-bits/) | Easy | 3 months | 7.9 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/0693.%20Binary%20Number%20with%20Alternating%20Bits/0693.%20Binary%20Number%20with%20Alternating%20Bits.md) |
| 6 | [2897. Apply Operations on Array to Maximize Sum of Squares](https://leetcode.com/problems/apply-operations-on-array-to-maximize-sum-of-squares/) | Hard | 3 months | 5.2 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/2897.%20Apply%20Operations%20on%20Array%20to%20Maximize%20Sum%20of%20Squares/2897.%20Apply%20Operations%20on%20Array%20to%20Maximize%20Sum%20of%20Squares.md) |
| 7 | [3644. Maximum K to Sort a Permutation](https://leetcode.com/problems/maximum-k-to-sort-a-permutation/) | Medium | 3 months | 5.1 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/3644.%20Maximum%20K%20to%20Sort%20a%20Permutation/3644.%20Maximum%20K%20to%20Sort%20a%20Permutation.md) |
| 8 | [338. Counting Bits](https://leetcode.com/problems/counting-bits/) | Easy | 6 months | 20.3 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/0338.%20Counting%20Bits/0338.%20Counting%20Bits.md) |
| 9 | [190. Reverse Bits](https://leetcode.com/problems/reverse-bits/) | Easy | 6 months | 19.5 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/0190.%20Reverse%20Bits/0190.%20Reverse%20Bits.md) |
| 10 | [3513. Number of Unique XOR Triplets I](https://leetcode.com/problems/number-of-unique-xor-triplets-i/) | Medium | 6 months | 10.6 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/3513.%20Number%20of%20Unique%20XOR%20Triplets%20I/3513.%20Number%20of%20Unique%20XOR%20Triplets%20I.md) |
| 11 | [1342. Number of Steps to Reduce a Number to Zero](https://leetcode.com/problems/number-of-steps-to-reduce-a-number-to-zero/) | Easy | 6 months | 5.0 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/1342.%20Number%20of%20Steps%20to%20Reduce%20a%20Number%20to%20Zero/1342.%20Number%20of%20Steps%20to%20Reduce%20a%20Number%20to%20Zero.md) |
| 12 | [397. Integer Replacement](https://leetcode.com/problems/integer-replacement/) | Medium | 6+ months | 33.2 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/0397.%20Integer%20Replacement/0397.%20Integer%20Replacement.md) |
| 13 | [393. UTF-8 Validation](https://leetcode.com/problems/utf-8-validation/) | Medium | 6+ months | 30.2 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/0393.%20UTF-8%20Validation/0393.%20UTF-8%20Validation.md) |
| 14 | [342. Power of Four](https://leetcode.com/problems/power-of-four/) | Easy | 6+ months | 15.1 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/0342.%20Power%20of%20Four/0342.%20Power%20of%20Four.md) |
| 15 | [89. Gray Code](https://leetcode.com/problems/gray-code/) | Medium | 6+ months | 13.4 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/0089.%20Gray%20Code/0089.%20Gray%20Code.md) |
| 16 | [405. Convert a Number to Hexadecimal](https://leetcode.com/problems/convert-a-number-to-hexadecimal/) | Easy | 6+ months | 5.9 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/0405.%20Convert%20a%20Number%20to%20Hexadecimal/0405.%20Convert%20a%20Number%20to%20Hexadecimal.md) |
| 17 | [461. Hamming Distance](https://leetcode.com/problems/hamming-distance/) | Easy | 6+ months | 5.5 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/0461.%20Hamming%20Distance/0461.%20Hamming%20Distance.md) |
| 18 | [1404. Number of Steps to Reduce a Number in Binary Representation to One](https://leetcode.com/problems/number-of-steps-to-reduce-a-number-in-binary-representation-to-one/) | Medium | 6+ months | 5.4 | ✅ Solved |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/1404.%20Number%20of%20Steps%20to%20Reduce%20a%20Number%20in%20Binary%20Representation%20to%20One/1404.%20Number%20of%20Steps%20to%20Reduce%20a%20Number%20in%20Binary%20Representation%20to%20One.md) |
| 19 | [476. Number Complement](https://leetcode.com/problems/number-complement/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/0476.%20Number%20Complement/0476.%20Number%20Complement.md) |
| 20 | [751. IP to CIDR](https://leetcode.com/problems/ip-to-cidr/) 🔒 | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/0751.%20IP%20to%20CIDR/0751.%20IP%20to%20CIDR.md) |
| 21 | [762. Prime Number of Set Bits in Binary Representation](https://leetcode.com/problems/prime-number-of-set-bits-in-binary-representation/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/0762.%20Prime%20Number%20of%20Set%20Bits%20in%20Binary%20Representation/0762.%20Prime%20Number%20of%20Set%20Bits%20in%20Binary%20Representation.md) |
| 22 | [868. Binary Gap](https://leetcode.com/problems/binary-gap/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/0868.%20Binary%20Gap/0868.%20Binary%20Gap.md) |
| 23 | [1009. Complement of Base 10 Integer](https://leetcode.com/problems/complement-of-base-10-integer/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/1009.%20Complement%20of%20Base%2010%20Integer/1009.%20Complement%20of%20Base%2010%20Integer.md) |
| 24 | [1018. Binary Prefix Divisible By 5](https://leetcode.com/problems/binary-prefix-divisible-by-5/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/1018.%20Binary%20Prefix%20Divisible%20By%205/1018.%20Binary%20Prefix%20Divisible%20By%205.md) |
| 25 | [1318. Minimum Flips to Make a OR b Equal to c](https://leetcode.com/problems/minimum-flips-to-make-a-or-b-equal-to-c/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/1318.%20Minimum%20Flips%20to%20Make%20a%20OR%20b%20Equal%20to%20c/1318.%20Minimum%20Flips%20to%20Make%20a%20OR%20b%20Equal%20to%20c.md) |
| 26 | [1611. Minimum One Bit Operations to Make Integers Zero](https://leetcode.com/problems/minimum-one-bit-operations-to-make-integers-zero/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/1611.%20Minimum%20One%20Bit%20Operations%20to%20Make%20Integers%20Zero/1611.%20Minimum%20One%20Bit%20Operations%20to%20Make%20Integers%20Zero.md) |
| 27 | [1680. Concatenation of Consecutive Binary Numbers](https://leetcode.com/problems/concatenation-of-consecutive-binary-numbers/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/1680.%20Concatenation%20of%20Consecutive%20Binary%20Numbers/1680.%20Concatenation%20of%20Consecutive%20Binary%20Numbers.md) |
| 28 | [2419. Longest Subarray With Maximum Bitwise AND](https://leetcode.com/problems/longest-subarray-with-maximum-bitwise-and/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/2419.%20Longest%20Subarray%20With%20Maximum%20Bitwise%20AND/2419.%20Longest%20Subarray%20With%20Maximum%20Bitwise%20AND.md) |
| 29 | [2429. Minimize XOR](https://leetcode.com/problems/minimize-xor/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/2429.%20Minimize%20XOR/2429.%20Minimize%20XOR.md) |
| 30 | [2595. Number of Even and Odd Bits](https://leetcode.com/problems/number-of-even-and-odd-bits/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/2595.%20Number%20of%20Even%20and%20Odd%20Bits/2595.%20Number%20of%20Even%20and%20Odd%20Bits.md) |
| 31 | [2749. Minimum Operations to Make the Integer Zero](https://leetcode.com/problems/minimum-operations-to-make-the-integer-zero/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/2749.%20Minimum%20Operations%20to%20Make%20the%20Integer%20Zero/2749.%20Minimum%20Operations%20to%20Make%20the%20Integer%20Zero.md) |
| 32 | [2939. Maximum Xor Product](https://leetcode.com/problems/maximum-xor-product/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/2939.%20Maximum%20Xor%20Product/2939.%20Maximum%20Xor%20Product.md) |
| 33 | [3133. Minimum Array End](https://leetcode.com/problems/minimum-array-end/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/3133.%20Minimum%20Array%20End/3133.%20Minimum%20Array%20End.md) |
| 34 | [3307. Find the K-th Character in String Game II](https://leetcode.com/problems/find-the-k-th-character-in-string-game-ii/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/3307.%20Find%20the%20K-th%20Character%20in%20String%20Game%20II/3307.%20Find%20the%20K-th%20Character%20in%20String%20Game%20II.md) |
| 35 | [3314. Construct the Minimum Bitwise Array I](https://leetcode.com/problems/construct-the-minimum-bitwise-array-i/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/3314.%20Construct%20the%20Minimum%20Bitwise%20Array%20I/3314.%20Construct%20the%20Minimum%20Bitwise%20Array%20I.md) |
| 36 | [3370. Smallest Number With All Set Bits](https://leetcode.com/problems/smallest-number-with-all-set-bits/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/3370.%20Smallest%20Number%20With%20All%20Set%20Bits/3370.%20Smallest%20Number%20With%20All%20Set%20Bits.md) |

## 02. XOR Tricks

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [268. Missing Number](https://leetcode.com/problems/missing-number/) | Easy | 30 days | 41.8 | ✅ Solved |  |  |  | [notes](02.%20XOR%20Tricks/0268.%20Missing%20Number/0268.%20Missing%20Number.md) |
| 2 | [136. Single Number](https://leetcode.com/problems/single-number/) | Easy | 3 months | 47.3 | ✅ Solved |  |  |  | [notes](02.%20XOR%20Tricks/0136.%20Single%20Number/0136.%20Single%20Number.md) |
| 3 | [389. Find the Difference](https://leetcode.com/problems/find-the-difference/) | Easy | 6 months | 41.4 | ✅ Solved |  |  |  | [notes](02.%20XOR%20Tricks/0389.%20Find%20the%20Difference/0389.%20Find%20the%20Difference.md) |
| 4 | [137. Single Number II](https://leetcode.com/problems/single-number-ii/) | Medium | 6 months | 38.3 | Todo |  |  |  | [notes](02.%20XOR%20Tricks/0137.%20Single%20Number%20II/0137.%20Single%20Number%20II.md) |
| 5 | [3702. Longest Subsequence With Non-Zero Bitwise XOR](https://leetcode.com/problems/longest-subsequence-with-non-zero-bitwise-xor/) | Medium | 6 months | 10.8 | ✅ Solved |  |  |  | [notes](02.%20XOR%20Tricks/3702.%20Longest%20Subsequence%20With%20Non-Zero%20Bitwise%20XOR/3702.%20Longest%20Subsequence%20With%20Non-Zero%20Bitwise%20XOR.md) |
| 6 | [260. Single Number III](https://leetcode.com/problems/single-number-iii/) | Medium | 6+ months | 8.1 | Todo |  |  |  | [notes](02.%20XOR%20Tricks/0260.%20Single%20Number%20III/0260.%20Single%20Number%20III.md) |
| 7 | [1486. XOR Operation in an Array](https://leetcode.com/problems/xor-operation-in-an-array/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20XOR%20Tricks/1486.%20XOR%20Operation%20in%20an%20Array/1486.%20XOR%20Operation%20in%20an%20Array.md) |
| 8 | [2425. Bitwise XOR of All Pairings](https://leetcode.com/problems/bitwise-xor-of-all-pairings/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20XOR%20Tricks/2425.%20Bitwise%20XOR%20of%20All%20Pairings/2425.%20Bitwise%20XOR%20of%20All%20Pairings.md) |
| 9 | [3158. Find the XOR of Numbers Which Appear Twice](https://leetcode.com/problems/find-the-xor-of-numbers-which-appear-twice/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20XOR%20Tricks/3158.%20Find%20the%20XOR%20of%20Numbers%20Which%20Appear%20Twice/3158.%20Find%20the%20XOR%20of%20Numbers%20Which%20Appear%20Twice.md) |
| 10 | [1720. Decode XORed Array](https://leetcode.com/problems/decode-xored-array/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](02.%20XOR%20Tricks/1720.%20Decode%20XORed%20Array/1720.%20Decode%20XORed%20Array.md) |

## 03. Bitmask Enumeration

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [1386. Cinema Seat Allocation](https://leetcode.com/problems/cinema-seat-allocation/) | Medium | 6 months | 11.4 | Todo |  |  |  | [notes](03.%20Bitmask%20Enumeration/1386.%20Cinema%20Seat%20Allocation/1386.%20Cinema%20Seat%20Allocation.md) |
| 2 | [318. Maximum Product of Word Lengths](https://leetcode.com/problems/maximum-product-of-word-lengths/) | Medium | 6+ months | 33.0 | Todo |  |  |  | [notes](03.%20Bitmask%20Enumeration/0318.%20Maximum%20Product%20of%20Word%20Lengths/0318.%20Maximum%20Product%20of%20Word%20Lengths.md) |
| 3 | [401. Binary Watch](https://leetcode.com/problems/binary-watch/) | Easy | 6+ months | 31.0 | Todo |  |  |  | [notes](03.%20Bitmask%20Enumeration/0401.%20Binary%20Watch/0401.%20Binary%20Watch.md) |
| 4 | [982. Triples with Bitwise AND Equal To Zero](https://leetcode.com/problems/triples-with-bitwise-and-equal-to-zero/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](03.%20Bitmask%20Enumeration/0982.%20Triples%20with%20Bitwise%20AND%20Equal%20To%20Zero/0982.%20Triples%20with%20Bitwise%20AND%20Equal%20To%20Zero.md) |
| 5 | [2002. Maximum Product of the Length of Two Palindromic Subsequences](https://leetcode.com/problems/maximum-product-of-the-length-of-two-palindromic-subsequences/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](03.%20Bitmask%20Enumeration/2002.%20Maximum%20Product%20of%20the%20Length%20of%20Two%20Palindromic%20Subsequences/2002.%20Maximum%20Product%20of%20the%20Length%20of%20Two%20Palindromic%20Subsequences.md) |
| 6 | [3630. Partition Array for Maximum XOR and AND](https://leetcode.com/problems/partition-array-for-maximum-xor-and-and/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](03.%20Bitmask%20Enumeration/3630.%20Partition%20Array%20for%20Maximum%20XOR%20and%20AND/3630.%20Partition%20Array%20for%20Maximum%20XOR%20and%20AND.md) |
| 7 | [3858. Minimum Bitwise OR From Grid](https://leetcode.com/problems/minimum-bitwise-or-from-grid/) | Medium | 6+ months | 30.1 | Todo |  |  |  | [notes](03.%20Bitmask%20Enumeration/3858.%20Minimum%20Bitwise%20OR%20From%20Grid/3858.%20Minimum%20Bitwise%20OR%20From%20Grid.md) |
| 8 | [2135. Count Words Obtained After Adding a Letter](https://leetcode.com/problems/count-words-obtained-after-adding-a-letter/) | Medium | 6+ months | 28.8 | Todo |  |  |  | [notes](03.%20Bitmask%20Enumeration/2135.%20Count%20Words%20Obtained%20After%20Adding%20a%20Letter/2135.%20Count%20Words%20Obtained%20After%20Adding%20a%20Letter.md) |

## 04. Bitwise Operations on Ranges

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [201. Bitwise AND of Numbers Range](https://leetcode.com/problems/bitwise-and-of-numbers-range/) | Medium | 6+ months | 9.2 | Todo |  |  |  | [notes](04.%20Bitwise%20Operations%20on%20Ranges/0201.%20Bitwise%20AND%20of%20Numbers%20Range/0201.%20Bitwise%20AND%20of%20Numbers%20Range.md) |
| 2 | [898. Bitwise ORs of Subarrays](https://leetcode.com/problems/bitwise-ors-of-subarrays/) | Medium | 6+ months | 7.2 | Todo |  |  |  | [notes](04.%20Bitwise%20Operations%20on%20Ranges/0898.%20Bitwise%20ORs%20of%20Subarrays/0898.%20Bitwise%20ORs%20of%20Subarrays.md) |
| 3 | [2411. Smallest Subarrays With Maximum Bitwise OR](https://leetcode.com/problems/smallest-subarrays-with-maximum-bitwise-or/) | Medium | 6+ months | 6.8 | Todo |  |  |  | [notes](04.%20Bitwise%20Operations%20on%20Ranges/2411.%20Smallest%20Subarrays%20With%20Maximum%20Bitwise%20OR/2411.%20Smallest%20Subarrays%20With%20Maximum%20Bitwise%20OR.md) |
