# 18. Greedy

[Back to Facebook](../README.md) · [Back to DSA Notes](../../../README.md)

76 Meta (Facebook) problems: 20 Easy, 47 Medium, 9 Hard, in 6 sub-patterns.

## Sub-patterns

| # | Sub-pattern | Questions | Easy | Medium | Hard | Last 3 Months | Solved | Most Asked |
|:---:|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---|
| 01 | [Greedy Choice](#01-greedy-choice) | 18 | 5 | 11 | 2 | 1 | 2 | 670. Maximum Swap, 334. Increasing Triplet Subsequence, 122. Best Time to Buy and Sell Stock II |
| 02 | [Sort + Greedy](#02-sort--greedy) | 20 | 6 | 11 | 3 | 1 | 1 | 455. Assign Cookies, 1840. Maximum Building Height, 406. Queue Reconstruction by Height |
| 03 | [Jump Game & Reachability](#03-jump-game--reachability) | 3 | 0 | 2 | 1 | 1 | 0 | 55. Jump Game, 45. Jump Game II, 1326. Minimum Number of Taps to Open to Water a Garden |
| 04 | [Circular Greedy (Gas Station)](#04-circular-greedy-gas-station) | 1 | 0 | 1 | 0 | 0 | 0 | 134. Gas Station |
| 05 | [String Greedy](#05-string-greedy) | 20 | 5 | 13 | 2 | 3 | 3 | 678. Valid Parenthesis String, 1903. Largest Odd Number in String, 3302. Find the Lexicographically Smallest Valid Sequence |
| 06 | [Greedy with Counting](#06-greedy-with-counting) | 14 | 4 | 9 | 1 | 0 | 3 | 621. Task Scheduler, 3545. Minimum Deletions for At Most K Distinct Characters, 860. Lemonade Change |

**Columns**

- **Last Asked**: most recent LeetCode window that lists the problem for Meta (30 days, 3 months, 6 months or 6+ months).
- **Frequency**: LeetCode frequency score (0-100) in the Meta "All" list.
- **Status**: your LeetCode status on the day this file was generated. 🔒 after a title means LeetCode Premium.
- **Logic / Key Idea, Time, Space**: fill these in as you solve. A rebuild keeps what you typed.
- **Notes**: link to the problem's notes file.

Inside each sub-pattern, rows are sorted by most recent window, then by frequency (highest first).

## 01. Greedy Choice

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [3723. Maximize Sum of Squares of Digits](https://leetcode.com/problems/maximize-sum-of-squares-of-digits/) | Medium | 3 months | 5.0 | Todo |  |  |  | [notes](01.%20Greedy%20Choice/3723.%20Maximize%20Sum%20of%20Squares%20of%20Digits/3723.%20Maximize%20Sum%20of%20Squares%20of%20Digits.md) |
| 2 | [122. Best Time to Buy and Sell Stock II](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-ii/) | Medium | 6 months | 43.1 | ✅ Solved |  |  |  | [notes](01.%20Greedy%20Choice/0122.%20Best%20Time%20to%20Buy%20and%20Sell%20Stock%20II/0122.%20Best%20Time%20to%20Buy%20and%20Sell%20Stock%20II.md) |
| 3 | [605. Can Place Flowers](https://leetcode.com/problems/can-place-flowers/) | Easy | 6 months | 41.3 | ✅ Solved |  |  |  | [notes](01.%20Greedy%20Choice/0605.%20Can%20Place%20Flowers/0605.%20Can%20Place%20Flowers.md) |
| 4 | [135. Candy](https://leetcode.com/problems/candy/) | Hard | 6 months | 22.6 | Todo |  |  |  | [notes](01.%20Greedy%20Choice/0135.%20Candy/0135.%20Candy.md) |
| 5 | [330. Patching Array](https://leetcode.com/problems/patching-array/) | Hard | 6 months | 6.6 | Todo |  |  |  | [notes](01.%20Greedy%20Choice/0330.%20Patching%20Array/0330.%20Patching%20Array.md) |
| 6 | [670. Maximum Swap](https://leetcode.com/problems/maximum-swap/) | Medium | 6+ months | 69.4 | Todo |  |  |  | [notes](01.%20Greedy%20Choice/0670.%20Maximum%20Swap/0670.%20Maximum%20Swap.md) |
| 7 | [334. Increasing Triplet Subsequence](https://leetcode.com/problems/increasing-triplet-subsequence/) | Medium | 6+ months | 44.8 | Todo |  |  |  | [notes](01.%20Greedy%20Choice/0334.%20Increasing%20Triplet%20Subsequence/0334.%20Increasing%20Triplet%20Subsequence.md) |
| 8 | [769. Max Chunks To Make Sorted](https://leetcode.com/problems/max-chunks-to-make-sorted/) | Medium | 6+ months | 10.7 | Todo |  |  |  | [notes](01.%20Greedy%20Choice/0769.%20Max%20Chunks%20To%20Make%20Sorted/0769.%20Max%20Chunks%20To%20Make%20Sorted.md) |
| 9 | [2078. Two Furthest Houses With Different Colors](https://leetcode.com/problems/two-furthest-houses-with-different-colors/) | Easy | 6+ months | 5.8 | Todo |  |  |  | [notes](01.%20Greedy%20Choice/2078.%20Two%20Furthest%20Houses%20With%20Different%20Colors/2078.%20Two%20Furthest%20Houses%20With%20Different%20Colors.md) |
| 10 | [3689. Maximum Total Subarray Value I](https://leetcode.com/problems/maximum-total-subarray-value-i/) | Medium | 6+ months | 5.6 | Todo |  |  |  | [notes](01.%20Greedy%20Choice/3689.%20Maximum%20Total%20Subarray%20Value%20I/3689.%20Maximum%20Total%20Subarray%20Value%20I.md) |
| 11 | [1323. Maximum 69 Number](https://leetcode.com/problems/maximum-69-number/) | Easy | 6+ months | 5.4 | Todo |  |  |  | [notes](01.%20Greedy%20Choice/1323.%20Maximum%2069%20Number/1323.%20Maximum%2069%20Number.md) |
| 12 | [665. Non-decreasing Array](https://leetcode.com/problems/non-decreasing-array/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Greedy%20Choice/0665.%20Non-decreasing%20Array/0665.%20Non-decreasing%20Array.md) |
| 13 | [2600. K Items With the Maximum Sum](https://leetcode.com/problems/k-items-with-the-maximum-sum/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Greedy%20Choice/2600.%20K%20Items%20With%20the%20Maximum%20Sum/2600.%20K%20Items%20With%20the%20Maximum%20Sum.md) |
| 14 | [3191. Minimum Operations to Make Binary Array Elements Equal to One I](https://leetcode.com/problems/minimum-operations-to-make-binary-array-elements-equal-to-one-i/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Greedy%20Choice/3191.%20Minimum%20Operations%20to%20Make%20Binary%20Array%20Elements%20Equal%20to%20One%20I/3191.%20Minimum%20Operations%20to%20Make%20Binary%20Array%20Elements%20Equal%20to%20One%20I.md) |
| 15 | [3282. Reach End of Array With Max Score](https://leetcode.com/problems/reach-end-of-array-with-max-score/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Greedy%20Choice/3282.%20Reach%20End%20of%20Array%20With%20Max%20Score/3282.%20Reach%20End%20of%20Array%20With%20Max%20Score.md) |
| 16 | [3487. Maximum Unique Subarray Sum After Deletion](https://leetcode.com/problems/maximum-unique-subarray-sum-after-deletion/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Greedy%20Choice/3487.%20Maximum%20Unique%20Subarray%20Sum%20After%20Deletion/3487.%20Maximum%20Unique%20Subarray%20Sum%20After%20Deletion.md) |
| 17 | [3576. Transform Array to All Equal Elements](https://leetcode.com/problems/transform-array-to-all-equal-elements/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Greedy%20Choice/3576.%20Transform%20Array%20to%20All%20Equal%20Elements/3576.%20Transform%20Array%20to%20All%20Equal%20Elements.md) |
| 18 | [4025. Minimize the Maximum Waiting Time at Synchronized Traffic Lights](https://leetcode.com/problems/minimize-the-maximum-waiting-time-at-synchronized-traffic-lights/) | Medium | 6+ months | 36.1 | Todo |  |  |  | [notes](01.%20Greedy%20Choice/4025.%20Minimize%20the%20Maximum%20Waiting%20Time%20at%20Synchronized%20Traffic%20Lights/4025.%20Minimize%20the%20Maximum%20Waiting%20Time%20at%20Synchronized%20Traffic%20Lights.md) |

## 02. Sort + Greedy

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [3727. Maximum Alternating Sum of Squares](https://leetcode.com/problems/maximum-alternating-sum-of-squares/) | Medium | 3 months | 9.1 | Todo |  |  |  | [notes](02.%20Sort%20%2B%20Greedy/3727.%20Maximum%20Alternating%20Sum%20of%20Squares/3727.%20Maximum%20Alternating%20Sum%20of%20Squares.md) |
| 2 | [455. Assign Cookies](https://leetcode.com/problems/assign-cookies/) | Easy | 6+ months | 23.6 | ✅ Solved |  |  |  | [notes](02.%20Sort%20%2B%20Greedy/0455.%20Assign%20Cookies/0455.%20Assign%20Cookies.md) |
| 3 | [1840. Maximum Building Height](https://leetcode.com/problems/maximum-building-height/) | Hard | 6+ months | 13.0 | Todo |  |  |  | [notes](02.%20Sort%20%2B%20Greedy/1840.%20Maximum%20Building%20Height/1840.%20Maximum%20Building%20Height.md) |
| 4 | [406. Queue Reconstruction by Height](https://leetcode.com/problems/queue-reconstruction-by-height/) | Medium | 6+ months | 10.8 | Todo |  |  |  | [notes](02.%20Sort%20%2B%20Greedy/0406.%20Queue%20Reconstruction%20by%20Height/0406.%20Queue%20Reconstruction%20by%20Height.md) |
| 5 | [2410. Maximum Matching of Players With Trainers](https://leetcode.com/problems/maximum-matching-of-players-with-trainers/) | Medium | 6+ months | 9.7 | Todo |  |  |  | [notes](02.%20Sort%20%2B%20Greedy/2410.%20Maximum%20Matching%20of%20Players%20With%20Trainers/2410.%20Maximum%20Matching%20of%20Players%20With%20Trainers.md) |
| 6 | [1710. Maximum Units on a Truck](https://leetcode.com/problems/maximum-units-on-a-truck/) | Easy | 6+ months | 5.4 | Todo |  |  |  | [notes](02.%20Sort%20%2B%20Greedy/1710.%20Maximum%20Units%20on%20a%20Truck/1710.%20Maximum%20Units%20on%20a%20Truck.md) |
| 7 | [826. Most Profit Assigning Work](https://leetcode.com/problems/most-profit-assigning-work/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Sort%20%2B%20Greedy/0826.%20Most%20Profit%20Assigning%20Work/0826.%20Most%20Profit%20Assigning%20Work.md) |
| 8 | [910. Smallest Range II](https://leetcode.com/problems/smallest-range-ii/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Sort%20%2B%20Greedy/0910.%20Smallest%20Range%20II/0910.%20Smallest%20Range%20II.md) |
| 9 | [1029. Two City Scheduling](https://leetcode.com/problems/two-city-scheduling/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Sort%20%2B%20Greedy/1029.%20Two%20City%20Scheduling/1029.%20Two%20City%20Scheduling.md) |
| 10 | [1727. Largest Submatrix With Rearrangements](https://leetcode.com/problems/largest-submatrix-with-rearrangements/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Sort%20%2B%20Greedy/1727.%20Largest%20Submatrix%20With%20Rearrangements/1727.%20Largest%20Submatrix%20With%20Rearrangements.md) |
| 11 | [1877. Minimize Maximum Pair Sum in Array](https://leetcode.com/problems/minimize-maximum-pair-sum-in-array/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Sort%20%2B%20Greedy/1877.%20Minimize%20Maximum%20Pair%20Sum%20in%20Array/1877.%20Minimize%20Maximum%20Pair%20Sum%20in%20Array.md) |
| 12 | [1921. Eliminate Maximum Number of Monsters](https://leetcode.com/problems/eliminate-maximum-number-of-monsters/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Sort%20%2B%20Greedy/1921.%20Eliminate%20Maximum%20Number%20of%20Monsters/1921.%20Eliminate%20Maximum%20Number%20of%20Monsters.md) |
| 13 | [2144. Minimum Cost of Buying Candies With Discount](https://leetcode.com/problems/minimum-cost-of-buying-candies-with-discount/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Sort%20%2B%20Greedy/2144.%20Minimum%20Cost%20of%20Buying%20Candies%20With%20Discount/2144.%20Minimum%20Cost%20of%20Buying%20Candies%20With%20Discount.md) |
| 14 | [2412. Minimum Money Required Before Transactions](https://leetcode.com/problems/minimum-money-required-before-transactions/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Sort%20%2B%20Greedy/2412.%20Minimum%20Money%20Required%20Before%20Transactions/2412.%20Minimum%20Money%20Required%20Before%20Transactions.md) |
| 15 | [2551. Put Marbles in Bags](https://leetcode.com/problems/put-marbles-in-bags/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Sort%20%2B%20Greedy/2551.%20Put%20Marbles%20in%20Bags/2551.%20Put%20Marbles%20in%20Bags.md) |
| 16 | [3397. Maximum Number of Distinct Elements After Operations](https://leetcode.com/problems/maximum-number-of-distinct-elements-after-operations/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Sort%20%2B%20Greedy/3397.%20Maximum%20Number%20of%20Distinct%20Elements%20After%20Operations/3397.%20Maximum%20Number%20of%20Distinct%20Elements%20After%20Operations.md) |
| 17 | [3633. Earliest Finish Time for Land and Water Rides I](https://leetcode.com/problems/earliest-finish-time-for-land-and-water-rides-i/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Sort%20%2B%20Greedy/3633.%20Earliest%20Finish%20Time%20for%20Land%20and%20Water%20Rides%20I/3633.%20Earliest%20Finish%20Time%20for%20Land%20and%20Water%20Rides%20I.md) |
| 18 | [3732. Maximum Product of Three Elements After One Replacement](https://leetcode.com/problems/maximum-product-of-three-elements-after-one-replacement/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Sort%20%2B%20Greedy/3732.%20Maximum%20Product%20of%20Three%20Elements%20After%20One%20Replacement/3732.%20Maximum%20Product%20of%20Three%20Elements%20After%20One%20Replacement.md) |
| 19 | [2037. Minimum Number of Moves to Seat Everyone](https://leetcode.com/problems/minimum-number-of-moves-to-seat-everyone/) | Easy | 6+ months | 5.8 | Todo |  |  |  | [notes](02.%20Sort%20%2B%20Greedy/2037.%20Minimum%20Number%20of%20Moves%20to%20Seat%20Everyone/2037.%20Minimum%20Number%20of%20Moves%20to%20Seat%20Everyone.md) |
| 20 | [2706. Buy Two Chocolates](https://leetcode.com/problems/buy-two-chocolates/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Sort%20%2B%20Greedy/2706.%20Buy%20Two%20Chocolates/2706.%20Buy%20Two%20Chocolates.md) |

## 03. Jump Game & Reachability

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [55. Jump Game](https://leetcode.com/problems/jump-game/) | Medium | 3 months | 43.0 | Todo |  |  |  | [notes](03.%20Jump%20Game%20%26%20Reachability/0055.%20Jump%20Game/0055.%20Jump%20Game.md) |
| 2 | [45. Jump Game II](https://leetcode.com/problems/jump-game-ii/) | Medium | 6+ months | 31.1 | Todo |  |  |  | [notes](03.%20Jump%20Game%20%26%20Reachability/0045.%20Jump%20Game%20II/0045.%20Jump%20Game%20II.md) |
| 3 | [1326. Minimum Number of Taps to Open to Water a Garden](https://leetcode.com/problems/minimum-number-of-taps-to-open-to-water-a-garden/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](03.%20Jump%20Game%20%26%20Reachability/1326.%20Minimum%20Number%20of%20Taps%20to%20Open%20to%20Water%20a%20Garden/1326.%20Minimum%20Number%20of%20Taps%20to%20Open%20to%20Water%20a%20Garden.md) |

## 04. Circular Greedy (Gas Station)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203; | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [134. Gas Station](https://leetcode.com/problems/gas-station/) | Medium | 6+ months | 24.1 | Todo |  |  |  | [notes](04.%20Circular%20Greedy%20%28Gas%20Station%29/0134.%20Gas%20Station/0134.%20Gas%20Station.md) |

## 05. String Greedy

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [678. Valid Parenthesis String](https://leetcode.com/problems/valid-parenthesis-string/) | Medium | 3 months | 35.0 | ✅ Solved |  |  |  | [notes](05.%20String%20Greedy/0678.%20Valid%20Parenthesis%20String/0678.%20Valid%20Parenthesis%20String.md) |
| 2 | [2914. Minimum Number of Changes to Make Binary String Beautiful](https://leetcode.com/problems/minimum-number-of-changes-to-make-binary-string-beautiful/) | Medium | 3 months | 10.9 | Todo |  |  |  | [notes](05.%20String%20Greedy/2914.%20Minimum%20Number%20of%20Changes%20to%20Make%20Binary%20String%20Beautiful/2914.%20Minimum%20Number%20of%20Changes%20to%20Make%20Binary%20String%20Beautiful.md) |
| 3 | [3863. Minimum Operations to Sort a String](https://leetcode.com/problems/minimum-operations-to-sort-a-string/) | Medium | 3 months | 10.1 | Todo |  |  |  | [notes](05.%20String%20Greedy/3863.%20Minimum%20Operations%20to%20Sort%20a%20String/3863.%20Minimum%20Operations%20to%20Sort%20a%20String.md) |
| 4 | [3302. Find the Lexicographically Smallest Valid Sequence](https://leetcode.com/problems/find-the-lexicographically-smallest-valid-sequence/) | Medium | 6 months | 12.3 | Todo |  |  |  | [notes](05.%20String%20Greedy/3302.%20Find%20the%20Lexicographically%20Smallest%20Valid%20Sequence/3302.%20Find%20the%20Lexicographically%20Smallest%20Valid%20Sequence.md) |
| 5 | [3348. Smallest Divisible Digit Product II](https://leetcode.com/problems/smallest-divisible-digit-product-ii/) | Hard | 6 months | 7.4 | Todo |  |  |  | [notes](05.%20String%20Greedy/3348.%20Smallest%20Divisible%20Digit%20Product%20II/3348.%20Smallest%20Divisible%20Digit%20Product%20II.md) |
| 6 | [3499. Maximize Active Section with Trade I](https://leetcode.com/problems/maximize-active-section-with-trade-i/) | Medium | 6 months | 7.3 | Todo |  |  |  | [notes](05.%20String%20Greedy/3499.%20Maximize%20Active%20Section%20with%20Trade%20I/3499.%20Maximize%20Active%20Section%20with%20Trade%20I.md) |
| 7 | [1903. Largest Odd Number in String](https://leetcode.com/problems/largest-odd-number-in-string/) | Easy | 6+ months | 17.3 | Todo |  |  |  | [notes](05.%20String%20Greedy/1903.%20Largest%20Odd%20Number%20in%20String/1903.%20Largest%20Odd%20Number%20in%20String.md) |
| 8 | [3228. Maximum Number of Operations to Move Ones to the End](https://leetcode.com/problems/maximum-number-of-operations-to-move-ones-to-the-end/) | Medium | 6+ months | 11.8 | Todo |  |  |  | [notes](05.%20String%20Greedy/3228.%20Maximum%20Number%20of%20Operations%20to%20Move%20Ones%20to%20the%20End/3228.%20Maximum%20Number%20of%20Operations%20to%20Move%20Ones%20to%20the%20End.md) |
| 9 | [763. Partition Labels](https://leetcode.com/problems/partition-labels/) | Medium | 6+ months | 11.7 | Todo |  |  |  | [notes](05.%20String%20Greedy/0763.%20Partition%20Labels/0763.%20Partition%20Labels.md) |
| 10 | [2116. Check if a Parentheses String Can Be Valid](https://leetcode.com/problems/check-if-a-parentheses-string-can-be-valid/) | Medium | 6+ months | 7.5 | Todo |  |  |  | [notes](05.%20String%20Greedy/2116.%20Check%20if%20a%20Parentheses%20String%20Can%20Be%20Valid/2116.%20Check%20if%20a%20Parentheses%20String%20Can%20Be%20Valid.md) |
| 11 | [1221. Split a String in Balanced Strings](https://leetcode.com/problems/split-a-string-in-balanced-strings/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](05.%20String%20Greedy/1221.%20Split%20a%20String%20in%20Balanced%20Strings/1221.%20Split%20a%20String%20in%20Balanced%20Strings.md) |
| 12 | [1717. Maximum Score From Removing Substrings](https://leetcode.com/problems/maximum-score-from-removing-substrings/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20String%20Greedy/1717.%20Maximum%20Score%20From%20Removing%20Substrings/1717.%20Maximum%20Score%20From%20Removing%20Substrings.md) |
| 13 | [1758. Minimum Changes To Make Alternating Binary String](https://leetcode.com/problems/minimum-changes-to-make-alternating-binary-string/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20String%20Greedy/1758.%20Minimum%20Changes%20To%20Make%20Alternating%20Binary%20String/1758.%20Minimum%20Changes%20To%20Make%20Alternating%20Binary%20String.md) |
| 14 | [1850. Minimum Adjacent Swaps to Reach the Kth Smallest Number](https://leetcode.com/problems/minimum-adjacent-swaps-to-reach-the-kth-smallest-number/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20String%20Greedy/1850.%20Minimum%20Adjacent%20Swaps%20to%20Reach%20the%20Kth%20Smallest%20Number/1850.%20Minimum%20Adjacent%20Swaps%20to%20Reach%20the%20Kth%20Smallest%20Number.md) |
| 15 | [1963. Minimum Number of Swaps to Make the String Balanced](https://leetcode.com/problems/minimum-number-of-swaps-to-make-the-string-balanced/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20String%20Greedy/1963.%20Minimum%20Number%20of%20Swaps%20to%20Make%20the%20String%20Balanced/1963.%20Minimum%20Number%20of%20Swaps%20to%20Make%20the%20String%20Balanced.md) |
| 16 | [2259. Remove Digit From Number to Maximize Result](https://leetcode.com/problems/remove-digit-from-number-to-maximize-result/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20String%20Greedy/2259.%20Remove%20Digit%20From%20Number%20to%20Maximize%20Result/2259.%20Remove%20Digit%20From%20Number%20to%20Maximize%20Result.md) |
| 17 | [2864. Maximum Odd Binary Number](https://leetcode.com/problems/maximum-odd-binary-number/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](05.%20String%20Greedy/2864.%20Maximum%20Odd%20Binary%20Number/2864.%20Maximum%20Odd%20Binary%20Number.md) |
| 18 | [3170. Lexicographically Minimum String After Removing Stars](https://leetcode.com/problems/lexicographically-minimum-string-after-removing-stars/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20String%20Greedy/3170.%20Lexicographically%20Minimum%20String%20After%20Removing%20Stars/3170.%20Lexicographically%20Minimum%20String%20After%20Removing%20Stars.md) |
| 19 | [420. Strong Password Checker](https://leetcode.com/problems/strong-password-checker/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20String%20Greedy/0420.%20Strong%20Password%20Checker/0420.%20Strong%20Password%20Checker.md) |
| 20 | [1980. Find Unique Binary String](https://leetcode.com/problems/find-unique-binary-string/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20String%20Greedy/1980.%20Find%20Unique%20Binary%20String/1980.%20Find%20Unique%20Binary%20String.md) |

## 06. Greedy with Counting

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [621. Task Scheduler](https://leetcode.com/problems/task-scheduler/) | Medium | 6 months | 42.2 | ✅ Solved |  |  |  | [notes](06.%20Greedy%20with%20Counting/0621.%20Task%20Scheduler/0621.%20Task%20Scheduler.md) |
| 2 | [1217. Minimum Cost to Move Chips to The Same Position](https://leetcode.com/problems/minimum-cost-to-move-chips-to-the-same-position/) | Easy | 6 months | 10.4 | Todo |  |  |  | [notes](06.%20Greedy%20with%20Counting/1217.%20Minimum%20Cost%20to%20Move%20Chips%20to%20The%20Same%20Position/1217.%20Minimum%20Cost%20to%20Move%20Chips%20to%20The%20Same%20Position.md) |
| 3 | [3545. Minimum Deletions for At Most K Distinct Characters](https://leetcode.com/problems/minimum-deletions-for-at-most-k-distinct-characters/) | Easy | 6+ months | 20.3 | ✅ Solved |  |  |  | [notes](06.%20Greedy%20with%20Counting/3545.%20Minimum%20Deletions%20for%20At%20Most%20K%20Distinct%20Characters/3545.%20Minimum%20Deletions%20for%20At%20Most%20K%20Distinct%20Characters.md) |
| 4 | [860. Lemonade Change](https://leetcode.com/problems/lemonade-change/) | Easy | 6+ months | 14.5 | Todo |  |  |  | [notes](06.%20Greedy%20with%20Counting/0860.%20Lemonade%20Change/0860.%20Lemonade%20Change.md) |
| 5 | [781. Rabbits in Forest](https://leetcode.com/problems/rabbits-in-forest/) | Medium | 6+ months | 12.3 | Todo |  |  |  | [notes](06.%20Greedy%20with%20Counting/0781.%20Rabbits%20in%20Forest/0781.%20Rabbits%20in%20Forest.md) |
| 6 | [846. Hand of Straights](https://leetcode.com/problems/hand-of-straights/) | Medium | 6+ months | 12.3 | Todo |  |  |  | [notes](06.%20Greedy%20with%20Counting/0846.%20Hand%20of%20Straights/0846.%20Hand%20of%20Straights.md) |
| 7 | [2833. Furthest Point From Origin](https://leetcode.com/problems/furthest-point-from-origin/) | Easy | 6+ months | 9.9 | ✅ Solved |  |  |  | [notes](06.%20Greedy%20with%20Counting/2833.%20Furthest%20Point%20From%20Origin/2833.%20Furthest%20Point%20From%20Origin.md) |
| 8 | [2333. Minimum Sum of Squared Difference](https://leetcode.com/problems/minimum-sum-of-squared-difference/) | Medium | 6+ months | 6.4 | Todo |  |  |  | [notes](06.%20Greedy%20with%20Counting/2333.%20Minimum%20Sum%20of%20Squared%20Difference/2333.%20Minimum%20Sum%20of%20Squared%20Difference.md) |
| 9 | [1975. Maximum Matrix Sum](https://leetcode.com/problems/maximum-matrix-sum/) | Medium | 6+ months | 5.9 | Todo |  |  |  | [notes](06.%20Greedy%20with%20Counting/1975.%20Maximum%20Matrix%20Sum/1975.%20Maximum%20Matrix%20Sum.md) |
| 10 | [1400. Construct K Palindrome Strings](https://leetcode.com/problems/construct-k-palindrome-strings/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20Greedy%20with%20Counting/1400.%20Construct%20K%20Palindrome%20Strings/1400.%20Construct%20K%20Palindrome%20Strings.md) |
| 11 | [2131. Longest Palindrome by Concatenating Two Letter Words](https://leetcode.com/problems/longest-palindrome-by-concatenating-two-letter-words/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20Greedy%20with%20Counting/2131.%20Longest%20Palindrome%20by%20Concatenating%20Two%20Letter%20Words/2131.%20Longest%20Palindrome%20by%20Concatenating%20Two%20Letter%20Words.md) |
| 12 | [2561. Rearranging Fruits](https://leetcode.com/problems/rearranging-fruits/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20Greedy%20with%20Counting/2561.%20Rearranging%20Fruits/2561.%20Rearranging%20Fruits.md) |
| 13 | [2870. Minimum Number of Operations to Make Array Empty](https://leetcode.com/problems/minimum-number-of-operations-to-make-array-empty/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20Greedy%20with%20Counting/2870.%20Minimum%20Number%20of%20Operations%20to%20Make%20Array%20Empty/2870.%20Minimum%20Number%20of%20Operations%20to%20Make%20Array%20Empty.md) |
| 14 | [3443. Maximum Manhattan Distance After K Changes](https://leetcode.com/problems/maximum-manhattan-distance-after-k-changes/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20Greedy%20with%20Counting/3443.%20Maximum%20Manhattan%20Distance%20After%20K%20Changes/3443.%20Maximum%20Manhattan%20Distance%20After%20K%20Changes.md) |
