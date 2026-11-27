# 09. Bit Manipulation

[Back to Facebook](../README.md) · [Back to DSA Notes](../../../README.md)

33 Meta (Facebook) problems: 19 Easy, 14 Medium, 0 Hard, in 4 sub-patterns.

## Sub-patterns

| # | Sub-pattern | Questions | Easy | Medium | Hard | Last 3 Months | Solved | Most Asked |
|:---:|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---|
| 01 | [Bit Basics & Counting](#01-bit-basics--counting) | 23 | 13 | 10 | 0 | 1 | 1 | 477. Total Hamming Distance, 231. Power of Two, 461. Hamming Distance |
| 02 | [XOR Tricks](#02-xor-tricks) | 6 | 5 | 1 | 0 | 2 | 3 | 268. Missing Number, 136. Single Number, 137. Single Number II |
| 03 | [Bitmask Enumeration](#03-bitmask-enumeration) | 2 | 1 | 1 | 0 | 0 | 0 | 1386. Cinema Seat Allocation, 401. Binary Watch |
| 04 | [Bitwise Operations on Ranges](#04-bitwise-operations-on-ranges) | 2 | 0 | 2 | 0 | 0 | 0 | 898. Bitwise ORs of Subarrays, 2411. Smallest Subarrays With Maximum Bitwise OR |

**Columns**

- **Last Asked**: most recent LeetCode window that lists the problem for Meta (30 days, 3 months, 6 months or 6+ months).
- **Frequency**: LeetCode frequency score (0-100) in the Meta "All" list.
- **Status**: your LeetCode status on the day this file was generated. 🔒 after a title means LeetCode Premium.
- **Logic / Key Idea, Time, Space**: fill these in as you solve. A rebuild keeps what you typed.
- **Notes**: link to the problem's notes file.

Inside each sub-pattern, rows are sorted by most recent window, then by frequency (highest first).

## 01. Bit Basics & Counting

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [231. Power of Two](https://leetcode.com/problems/power-of-two/) | Easy | 3 months | 37.5 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/0231.%20Power%20of%20Two/0231.%20Power%20of%20Two.md) |
| 2 | [477. Total Hamming Distance](https://leetcode.com/problems/total-hamming-distance/) | Medium | 6+ months | 38.1 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/0477.%20Total%20Hamming%20Distance/0477.%20Total%20Hamming%20Distance.md) |
| 3 | [29. Divide Two Integers](https://leetcode.com/problems/divide-two-integers/) | Medium | 6+ months | 30.2 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/0029.%20Divide%20Two%20Integers/0029.%20Divide%20Two%20Integers.md) |
| 4 | [405. Convert a Number to Hexadecimal](https://leetcode.com/problems/convert-a-number-to-hexadecimal/) | Easy | 6+ months | 17.0 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/0405.%20Convert%20a%20Number%20to%20Hexadecimal/0405.%20Convert%20a%20Number%20to%20Hexadecimal.md) |
| 5 | [191. Number of 1 Bits](https://leetcode.com/problems/number-of-1-bits/) | Easy | 6+ months | 14.4 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/0191.%20Number%20of%201%20Bits/0191.%20Number%20of%201%20Bits.md) |
| 6 | [190. Reverse Bits](https://leetcode.com/problems/reverse-bits/) | Easy | 6+ months | 12.5 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/0190.%20Reverse%20Bits/0190.%20Reverse%20Bits.md) |
| 7 | [476. Number Complement](https://leetcode.com/problems/number-complement/) | Easy | 6+ months | 7.9 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/0476.%20Number%20Complement/0476.%20Number%20Complement.md) |
| 8 | [1404. Number of Steps to Reduce a Number in Binary Representation to One](https://leetcode.com/problems/number-of-steps-to-reduce-a-number-in-binary-representation-to-one/) | Medium | 6+ months | 7.2 | ✅ Solved |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/1404.%20Number%20of%20Steps%20to%20Reduce%20a%20Number%20in%20Binary%20Representation%20to%20One/1404.%20Number%20of%20Steps%20to%20Reduce%20a%20Number%20in%20Binary%20Representation%20to%20One.md) |
| 9 | [371. Sum of Two Integers](https://leetcode.com/problems/sum-of-two-integers/) | Medium | 6+ months | 7.0 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/0371.%20Sum%20of%20Two%20Integers/0371.%20Sum%20of%20Two%20Integers.md) |
| 10 | [338. Counting Bits](https://leetcode.com/problems/counting-bits/) | Easy | 6+ months | 6.7 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/0338.%20Counting%20Bits/0338.%20Counting%20Bits.md) |
| 11 | [2749. Minimum Operations to Make the Integer Zero](https://leetcode.com/problems/minimum-operations-to-make-the-integer-zero/) | Medium | 6+ months | 6.3 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/2749.%20Minimum%20Operations%20to%20Make%20the%20Integer%20Zero/2749.%20Minimum%20Operations%20to%20Make%20the%20Integer%20Zero.md) |
| 12 | [342. Power of Four](https://leetcode.com/problems/power-of-four/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/0342.%20Power%20of%20Four/0342.%20Power%20of%20Four.md) |
| 13 | [393. UTF-8 Validation](https://leetcode.com/problems/utf-8-validation/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/0393.%20UTF-8%20Validation/0393.%20UTF-8%20Validation.md) |
| 14 | [397. Integer Replacement](https://leetcode.com/problems/integer-replacement/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/0397.%20Integer%20Replacement/0397.%20Integer%20Replacement.md) |
| 15 | [1009. Complement of Base 10 Integer](https://leetcode.com/problems/complement-of-base-10-integer/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/1009.%20Complement%20of%20Base%2010%20Integer/1009.%20Complement%20of%20Base%2010%20Integer.md) |
| 16 | [1342. Number of Steps to Reduce a Number to Zero](https://leetcode.com/problems/number-of-steps-to-reduce-a-number-to-zero/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/1342.%20Number%20of%20Steps%20to%20Reduce%20a%20Number%20to%20Zero/1342.%20Number%20of%20Steps%20to%20Reduce%20a%20Number%20to%20Zero.md) |
| 17 | [3315. Construct the Minimum Bitwise Array II](https://leetcode.com/problems/construct-the-minimum-bitwise-array-ii/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/3315.%20Construct%20the%20Minimum%20Bitwise%20Array%20II/3315.%20Construct%20the%20Minimum%20Bitwise%20Array%20II.md) |
| 18 | [3644. Maximum K to Sort a Permutation](https://leetcode.com/problems/maximum-k-to-sort-a-permutation/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/3644.%20Maximum%20K%20to%20Sort%20a%20Permutation/3644.%20Maximum%20K%20to%20Sort%20a%20Permutation.md) |
| 19 | [461. Hamming Distance](https://leetcode.com/problems/hamming-distance/) | Easy | 6+ months | 36.1 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/0461.%20Hamming%20Distance/0461.%20Hamming%20Distance.md) |
| 20 | [3688. Bitwise OR of Even Numbers in an Array](https://leetcode.com/problems/bitwise-or-of-even-numbers-in-an-array/) | Easy | 6+ months | 36.1 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/3688.%20Bitwise%20OR%20of%20Even%20Numbers%20in%20an%20Array/3688.%20Bitwise%20OR%20of%20Even%20Numbers%20in%20an%20Array.md) |
| 21 | [751. IP to CIDR](https://leetcode.com/problems/ip-to-cidr/) 🔒 | Medium | 6+ months | 6.5 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/0751.%20IP%20to%20CIDR/0751.%20IP%20to%20CIDR.md) |
| 22 | [1018. Binary Prefix Divisible By 5](https://leetcode.com/problems/binary-prefix-divisible-by-5/) | Easy | 6+ months | 5.8 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/1018.%20Binary%20Prefix%20Divisible%20By%205/1018.%20Binary%20Prefix%20Divisible%20By%205.md) |
| 23 | [2595. Number of Even and Odd Bits](https://leetcode.com/problems/number-of-even-and-odd-bits/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Bit%20Basics%20%26%20Counting/2595.%20Number%20of%20Even%20and%20Odd%20Bits/2595.%20Number%20of%20Even%20and%20Odd%20Bits.md) |

## 02. XOR Tricks

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [136. Single Number](https://leetcode.com/problems/single-number/) | Easy | 3 months | 41.3 | ✅ Solved |  |  |  | [notes](02.%20XOR%20Tricks/0136.%20Single%20Number/0136.%20Single%20Number.md) |
| 2 | [137. Single Number II](https://leetcode.com/problems/single-number-ii/) | Medium | 3 months | 28.9 | Todo |  |  |  | [notes](02.%20XOR%20Tricks/0137.%20Single%20Number%20II/0137.%20Single%20Number%20II.md) |
| 3 | [268. Missing Number](https://leetcode.com/problems/missing-number/) | Easy | 6 months | 50.1 | ✅ Solved |  |  |  | [notes](02.%20XOR%20Tricks/0268.%20Missing%20Number/0268.%20Missing%20Number.md) |
| 4 | [389. Find the Difference](https://leetcode.com/problems/find-the-difference/) | Easy | 6+ months | 14.3 | ✅ Solved |  |  |  | [notes](02.%20XOR%20Tricks/0389.%20Find%20the%20Difference/0389.%20Find%20the%20Difference.md) |
| 5 | [2220. Minimum Bit Flips to Convert Number](https://leetcode.com/problems/minimum-bit-flips-to-convert-number/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20XOR%20Tricks/2220.%20Minimum%20Bit%20Flips%20to%20Convert%20Number/2220.%20Minimum%20Bit%20Flips%20to%20Convert%20Number.md) |
| 6 | [3158. Find the XOR of Numbers Which Appear Twice](https://leetcode.com/problems/find-the-xor-of-numbers-which-appear-twice/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20XOR%20Tricks/3158.%20Find%20the%20XOR%20of%20Numbers%20Which%20Appear%20Twice/3158.%20Find%20the%20XOR%20of%20Numbers%20Which%20Appear%20Twice.md) |

## 03. Bitmask Enumeration

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [1386. Cinema Seat Allocation](https://leetcode.com/problems/cinema-seat-allocation/) | Medium | 6 months | 11.5 | Todo |  |  |  | [notes](03.%20Bitmask%20Enumeration/1386.%20Cinema%20Seat%20Allocation/1386.%20Cinema%20Seat%20Allocation.md) |
| 2 | [401. Binary Watch](https://leetcode.com/problems/binary-watch/) | Easy | 6+ months | 5.7 | Todo |  |  |  | [notes](03.%20Bitmask%20Enumeration/0401.%20Binary%20Watch/0401.%20Binary%20Watch.md) |

## 04. Bitwise Operations on Ranges

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [898. Bitwise ORs of Subarrays](https://leetcode.com/problems/bitwise-ors-of-subarrays/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Bitwise%20Operations%20on%20Ranges/0898.%20Bitwise%20ORs%20of%20Subarrays/0898.%20Bitwise%20ORs%20of%20Subarrays.md) |
| 2 | [2411. Smallest Subarrays With Maximum Bitwise OR](https://leetcode.com/problems/smallest-subarrays-with-maximum-bitwise-or/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Bitwise%20Operations%20on%20Ranges/2411.%20Smallest%20Subarrays%20With%20Maximum%20Bitwise%20OR/2411.%20Smallest%20Subarrays%20With%20Maximum%20Bitwise%20OR.md) |
