# 23. Design

[Back to Google](../README.md) · [Back to DSA Notes](../../../README.md)

94 Google problems: 23 Easy, 58 Medium, 13 Hard, in 7 sub-patterns.

## Sub-patterns

| # | Sub-pattern | Questions | Easy | Medium | Hard | Last 3 Months | Solved | Most Asked |
|:---:|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---|
| 01 | [Data Structure Design](#01-data-structure-design) | 33 | 2 | 24 | 7 | 4 | 1 | 155. Min Stack, 2013. Detect Squares, 2034. Stock Price Fluctuation  |
| 02 | [LRU & LFU Cache](#02-lru--lfu-cache) | 2 | 0 | 1 | 1 | 2 | 2 | 146. LRU Cache, 460. LFU Cache |
| 03 | [Iterator Design](#03-iterator-design) | 8 | 1 | 7 | 0 | 0 | 1 | 900. RLE Iterator, 341. Flatten Nested List Iterator, 173. Binary Search Tree Iterator |
| 04 | [Data Stream Design](#04-data-stream-design) | 3 | 1 | 1 | 1 | 0 | 0 | 1825. Finding MK Average, 346. Moving Average from Data Stream, 1429. First Unique Number |
| 05 | [Randomized Design](#05-randomized-design) | 6 | 0 | 4 | 2 | 1 | 0 | 380. Insert Delete GetRandom O(1), 497. Random Point in Non-overlapping Rectangles, 519. Random Flip Matrix |
| 06 | [System & OOP Design](#06-system--oop-design) | 35 | 17 | 16 | 2 | 2 | 0 | 535. Encode and Decode TinyURL, 348. Design Tic-Tac-Toe, 1600. Throne Inheritance |
| 07 | [Time-Based Design (Rate Limiter, Hit Counter)](#07-time-based-design-rate-limiter-hit-counter) | 7 | 2 | 5 | 0 | 2 | 1 | 359. Logger Rate Limiter, 362. Design Hit Counter, 1146. Snapshot Array |

**Columns**

- **Last Asked**: most recent LeetCode window that lists the problem for Google (30 days, 3 months, 6 months, 6+ months).
- **Frequency**: LeetCode frequency score (0-100) in the Google "All" list.
- **Status**: your LeetCode status on the day this file was generated. 🔒 after a title means LeetCode Premium.
- **Logic / Key Idea, Time, Space**: fill these in as you solve. A rebuild keeps what you typed.
- **Notes**: link to the problem's notes file.

Inside each sub-pattern, rows are sorted by most recent window, then by frequency (highest first).

## 01. Data Structure Design

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [707. Design Linked List](https://leetcode.com/problems/design-linked-list/) | Medium | 30 days | 24.6 | Todo |  |  |  | [notes](01.%20Data%20Structure%20Design/0707.%20Design%20Linked%20List/0707.%20Design%20Linked%20List.md) |
| 2 | [706. Design HashMap](https://leetcode.com/problems/design-hashmap/) | Easy | 30 days | 14.8 | Todo |  |  |  | [notes](01.%20Data%20Structure%20Design/0706.%20Design%20HashMap/0706.%20Design%20HashMap.md) |
| 3 | [155. Min Stack](https://leetcode.com/problems/min-stack/) | Medium | 3 months | 51.6 | ✅ Solved |  |  |  | [notes](01.%20Data%20Structure%20Design/0155.%20Min%20Stack/0155.%20Min%20Stack.md) |
| 4 | [1244. Design A Leaderboard](https://leetcode.com/problems/design-a-leaderboard/) 🔒 | Medium | 3 months | 13.6 | Todo |  |  |  | [notes](01.%20Data%20Structure%20Design/1244.%20Design%20A%20Leaderboard/1244.%20Design%20A%20Leaderboard.md) |
| 5 | [2034. Stock Price Fluctuation ](https://leetcode.com/problems/stock-price-fluctuation/) | Medium | 6 months | 34.6 | Todo |  |  |  | [notes](01.%20Data%20Structure%20Design/2034.%20Stock%20Price%20Fluctuation%20/2034.%20Stock%20Price%20Fluctuation%20.md) |
| 6 | [2424. Longest Uploaded Prefix](https://leetcode.com/problems/longest-uploaded-prefix/) | Medium | 6 months | 32.5 | Todo |  |  |  | [notes](01.%20Data%20Structure%20Design/2424.%20Longest%20Uploaded%20Prefix/2424.%20Longest%20Uploaded%20Prefix.md) |
| 7 | [1472. Design Browser History](https://leetcode.com/problems/design-browser-history/) | Medium | 6 months | 7.7 | Todo |  |  |  | [notes](01.%20Data%20Structure%20Design/1472.%20Design%20Browser%20History/1472.%20Design%20Browser%20History.md) |
| 8 | [2013. Detect Squares](https://leetcode.com/problems/detect-squares/) | Medium | 6+ months | 35.3 | Todo |  |  |  | [notes](01.%20Data%20Structure%20Design/2013.%20Detect%20Squares/2013.%20Detect%20Squares.md) |
| 9 | [2296. Design a Text Editor](https://leetcode.com/problems/design-a-text-editor/) | Hard | 6+ months | 33.7 | Todo |  |  |  | [notes](01.%20Data%20Structure%20Design/2296.%20Design%20a%20Text%20Editor/2296.%20Design%20a%20Text%20Editor.md) |
| 10 | [2349. Design a Number Container System](https://leetcode.com/problems/design-a-number-container-system/) | Medium | 6+ months | 30.8 | Todo |  |  |  | [notes](01.%20Data%20Structure%20Design/2349.%20Design%20a%20Number%20Container%20System/2349.%20Design%20a%20Number%20Container%20System.md) |
| 11 | [855. Exam Room](https://leetcode.com/problems/exam-room/) | Medium | 6+ months | 30.6 | Todo |  |  |  | [notes](01.%20Data%20Structure%20Design/0855.%20Exam%20Room/0855.%20Exam%20Room.md) |
| 12 | [622. Design Circular Queue](https://leetcode.com/problems/design-circular-queue/) | Medium | 6+ months | 17.8 | Todo |  |  |  | [notes](01.%20Data%20Structure%20Design/0622.%20Design%20Circular%20Queue/0622.%20Design%20Circular%20Queue.md) |
| 13 | [1381. Design a Stack With Increment Operation](https://leetcode.com/problems/design-a-stack-with-increment-operation/) | Medium | 6+ months | 17.2 | Todo |  |  |  | [notes](01.%20Data%20Structure%20Design/1381.%20Design%20a%20Stack%20With%20Increment%20Operation/1381.%20Design%20a%20Stack%20With%20Increment%20Operation.md) |
| 14 | [705. Design HashSet](https://leetcode.com/problems/design-hashset/) | Easy | 6+ months | 13.0 | Todo |  |  |  | [notes](01.%20Data%20Structure%20Design/0705.%20Design%20HashSet/0705.%20Design%20HashSet.md) |
| 15 | [3408. Design Task Manager](https://leetcode.com/problems/design-task-manager/) | Medium | 6+ months | 10.3 | Todo |  |  |  | [notes](01.%20Data%20Structure%20Design/3408.%20Design%20Task%20Manager/3408.%20Design%20Task%20Manager.md) |
| 16 | [895. Maximum Frequency Stack](https://leetcode.com/problems/maximum-frequency-stack/) | Hard | 6+ months | 6.8 | Todo |  |  |  | [notes](01.%20Data%20Structure%20Design/0895.%20Maximum%20Frequency%20Stack/0895.%20Maximum%20Frequency%20Stack.md) |
| 17 | [432. All O`one Data Structure](https://leetcode.com/problems/all-oone-data-structure/) | Hard | 6+ months | 6.7 | Todo |  |  |  | [notes](01.%20Data%20Structure%20Design/0432.%20All%20O%60one%20Data%20Structure/0432.%20All%20O%60one%20Data%20Structure.md) |
| 18 | [244. Shortest Word Distance II](https://leetcode.com/problems/shortest-word-distance-ii/) 🔒 | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Data%20Structure%20Design/0244.%20Shortest%20Word%20Distance%20II/0244.%20Shortest%20Word%20Distance%20II.md) |
| 19 | [641. Design Circular Deque](https://leetcode.com/problems/design-circular-deque/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Data%20Structure%20Design/0641.%20Design%20Circular%20Deque/0641.%20Design%20Circular%20Deque.md) |
| 20 | [716. Max Stack](https://leetcode.com/problems/max-stack/) 🔒 | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Data%20Structure%20Design/0716.%20Max%20Stack/0716.%20Max%20Stack.md) |
| 21 | [1172. Dinner Plate Stacks](https://leetcode.com/problems/dinner-plate-stacks/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Data%20Structure%20Design/1172.%20Dinner%20Plate%20Stacks/1172.%20Dinner%20Plate%20Stacks.md) |
| 22 | [1670. Design Front Middle Back Queue](https://leetcode.com/problems/design-front-middle-back-queue/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Data%20Structure%20Design/1670.%20Design%20Front%20Middle%20Back%20Queue/1670.%20Design%20Front%20Middle%20Back%20Queue.md) |
| 23 | [1865. Finding Pairs With a Certain Sum](https://leetcode.com/problems/finding-pairs-with-a-certain-sum/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Data%20Structure%20Design/1865.%20Finding%20Pairs%20With%20a%20Certain%20Sum/1865.%20Finding%20Pairs%20With%20a%20Certain%20Sum.md) |
| 24 | [2336. Smallest Number in Infinite Set](https://leetcode.com/problems/smallest-number-in-infinite-set/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Data%20Structure%20Design/2336.%20Smallest%20Number%20in%20Infinite%20Set/2336.%20Smallest%20Number%20in%20Infinite%20Set.md) |
| 25 | [2353. Design a Food Rating System](https://leetcode.com/problems/design-a-food-rating-system/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Data%20Structure%20Design/2353.%20Design%20a%20Food%20Rating%20System/2353.%20Design%20a%20Food%20Rating%20System.md) |
| 26 | [3508. Implement Router](https://leetcode.com/problems/implement-router/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Data%20Structure%20Design/3508.%20Implement%20Router/3508.%20Implement%20Router.md) |
| 27 | [3815. Design Auction System](https://leetcode.com/problems/design-auction-system/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Data%20Structure%20Design/3815.%20Design%20Auction%20System/3815.%20Design%20Auction%20System.md) |
| 28 | [288. Unique Word Abbreviation](https://leetcode.com/problems/unique-word-abbreviation/) 🔒 | Medium | 6+ months | 28.8 | Todo |  |  |  | [notes](01.%20Data%20Structure%20Design/0288.%20Unique%20Word%20Abbreviation/0288.%20Unique%20Word%20Abbreviation.md) |
| 29 | [379. Design Phone Directory](https://leetcode.com/problems/design-phone-directory/) 🔒 | Medium | 6+ months | 28.8 | Todo |  |  |  | [notes](01.%20Data%20Structure%20Design/0379.%20Design%20Phone%20Directory/0379.%20Design%20Phone%20Directory.md) |
| 30 | [1206. Design Skiplist](https://leetcode.com/problems/design-skiplist/) | Hard | 6+ months | 28.8 | Todo |  |  |  | [notes](01.%20Data%20Structure%20Design/1206.%20Design%20Skiplist/1206.%20Design%20Skiplist.md) |
| 31 | [1756. Design Most Recently Used Queue](https://leetcode.com/problems/design-most-recently-used-queue/) 🔒 | Medium | 6+ months | 28.8 | Todo |  |  |  | [notes](01.%20Data%20Structure%20Design/1756.%20Design%20Most%20Recently%20Used%20Queue/1756.%20Design%20Most%20Recently%20Used%20Queue.md) |
| 32 | [2254. Design Video Sharing Platform](https://leetcode.com/problems/design-video-sharing-platform/) 🔒 | Hard | 6+ months | 28.8 | Todo |  |  |  | [notes](01.%20Data%20Structure%20Design/2254.%20Design%20Video%20Sharing%20Platform/2254.%20Design%20Video%20Sharing%20Platform.md) |
| 33 | [1500. Design a File Sharing System](https://leetcode.com/problems/design-a-file-sharing-system/) 🔒 | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Data%20Structure%20Design/1500.%20Design%20a%20File%20Sharing%20System/1500.%20Design%20a%20File%20Sharing%20System.md) |

## 02. LRU & LFU Cache

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203; | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [146. LRU Cache](https://leetcode.com/problems/lru-cache/) | Medium | 3 months | 61.3 | ✅ Solved |  |  |  | [notes](02.%20LRU%20%26%20LFU%20Cache/0146.%20LRU%20Cache/0146.%20LRU%20Cache.md) |
| 2 | [460. LFU Cache](https://leetcode.com/problems/lfu-cache/) | Hard | 3 months | 43.2 | ✅ Solved |  |  |  | [notes](02.%20LRU%20%26%20LFU%20Cache/0460.%20LFU%20Cache/0460.%20LFU%20Cache.md) |

## 03. Iterator Design

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [900. RLE Iterator](https://leetcode.com/problems/rle-iterator/) | Medium | 6 months | 35.2 | Todo |  |  |  | [notes](03.%20Iterator%20Design/0900.%20RLE%20Iterator/0900.%20RLE%20Iterator.md) |
| 2 | [341. Flatten Nested List Iterator](https://leetcode.com/problems/flatten-nested-list-iterator/) | Medium | 6+ months | 35.1 | Todo |  |  |  | [notes](03.%20Iterator%20Design/0341.%20Flatten%20Nested%20List%20Iterator/0341.%20Flatten%20Nested%20List%20Iterator.md) |
| 3 | [173. Binary Search Tree Iterator](https://leetcode.com/problems/binary-search-tree-iterator/) | Medium | 6+ months | 34.3 | ✅ Solved |  |  |  | [notes](03.%20Iterator%20Design/0173.%20Binary%20Search%20Tree%20Iterator/0173.%20Binary%20Search%20Tree%20Iterator.md) |
| 4 | [604. Design Compressed String Iterator](https://leetcode.com/problems/design-compressed-string-iterator/) 🔒 | Easy | 6+ months | 30.1 | Todo |  |  |  | [notes](03.%20Iterator%20Design/0604.%20Design%20Compressed%20String%20Iterator/0604.%20Design%20Compressed%20String%20Iterator.md) |
| 5 | [284. Peeking Iterator](https://leetcode.com/problems/peeking-iterator/) | Medium | 6+ months | 29.5 | Todo |  |  |  | [notes](03.%20Iterator%20Design/0284.%20Peeking%20Iterator/0284.%20Peeking%20Iterator.md) |
| 6 | [251. Flatten 2D Vector](https://leetcode.com/problems/flatten-2d-vector/) 🔒 | Medium | 6+ months | 28.8 | Todo |  |  |  | [notes](03.%20Iterator%20Design/0251.%20Flatten%202D%20Vector/0251.%20Flatten%202D%20Vector.md) |
| 7 | [281. Zigzag Iterator](https://leetcode.com/problems/zigzag-iterator/) 🔒 | Medium | 6+ months | 28.8 | Todo |  |  |  | [notes](03.%20Iterator%20Design/0281.%20Zigzag%20Iterator/0281.%20Zigzag%20Iterator.md) |
| 8 | [1286. Iterator for Combination](https://leetcode.com/problems/iterator-for-combination/) | Medium | 6+ months | 28.8 | Todo |  |  |  | [notes](03.%20Iterator%20Design/1286.%20Iterator%20for%20Combination/1286.%20Iterator%20for%20Combination.md) |

## 04. Data Stream Design

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [1825. Finding MK Average](https://leetcode.com/problems/finding-mk-average/) | Hard | 6+ months | 38.6 | Todo |  |  |  | [notes](04.%20Data%20Stream%20Design/1825.%20Finding%20MK%20Average/1825.%20Finding%20MK%20Average.md) |
| 2 | [346. Moving Average from Data Stream](https://leetcode.com/problems/moving-average-from-data-stream/) 🔒 | Easy | 6+ months | 36.3 | Todo |  |  |  | [notes](04.%20Data%20Stream%20Design/0346.%20Moving%20Average%20from%20Data%20Stream/0346.%20Moving%20Average%20from%20Data%20Stream.md) |
| 3 | [1429. First Unique Number](https://leetcode.com/problems/first-unique-number/) 🔒 | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Data%20Stream%20Design/1429.%20First%20Unique%20Number/1429.%20First%20Unique%20Number.md) |

## 05. Randomized Design

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [380. Insert Delete GetRandom O(1)](https://leetcode.com/problems/insert-delete-getrandom-o1/) | Medium | 3 months | 51.5 | Todo |  |  |  | [notes](05.%20Randomized%20Design/0380.%20Insert%20Delete%20GetRandom%20O%281%29/0380.%20Insert%20Delete%20GetRandom%20O%281%29.md) |
| 2 | [384. Shuffle an Array](https://leetcode.com/problems/shuffle-an-array/) | Medium | 6 months | 13.5 | Todo |  |  |  | [notes](05.%20Randomized%20Design/0384.%20Shuffle%20an%20Array/0384.%20Shuffle%20an%20Array.md) |
| 3 | [497. Random Point in Non-overlapping Rectangles](https://leetcode.com/problems/random-point-in-non-overlapping-rectangles/) | Medium | 6+ months | 31.4 | Todo |  |  |  | [notes](05.%20Randomized%20Design/0497.%20Random%20Point%20in%20Non-overlapping%20Rectangles/0497.%20Random%20Point%20in%20Non-overlapping%20Rectangles.md) |
| 4 | [381. Insert Delete GetRandom O(1) - Duplicates allowed](https://leetcode.com/problems/insert-delete-getrandom-o1-duplicates-allowed/) | Hard | 6+ months | 19.8 | Todo |  |  |  | [notes](05.%20Randomized%20Design/0381.%20Insert%20Delete%20GetRandom%20O%281%29%20-%20Duplicates%20allowed/0381.%20Insert%20Delete%20GetRandom%20O%281%29%20-%20Duplicates%20allowed.md) |
| 5 | [519. Random Flip Matrix](https://leetcode.com/problems/random-flip-matrix/) | Medium | 6+ months | 28.8 | Todo |  |  |  | [notes](05.%20Randomized%20Design/0519.%20Random%20Flip%20Matrix/0519.%20Random%20Flip%20Matrix.md) |
| 6 | [710. Random Pick with Blacklist](https://leetcode.com/problems/random-pick-with-blacklist/) | Hard | 6+ months | 28.8 | Todo |  |  |  | [notes](05.%20Randomized%20Design/0710.%20Random%20Pick%20with%20Blacklist/0710.%20Random%20Pick%20with%20Blacklist.md) |

## 06. System & OOP Design

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [2620. Counter](https://leetcode.com/problems/counter/) | Easy | 3 months | 23.5 | Todo |  |  |  | [notes](06.%20System%20%26%20OOP%20Design/2620.%20Counter/2620.%20Counter.md) |
| 2 | [2619. Array Prototype Last](https://leetcode.com/problems/array-prototype-last/) | Easy | 3 months | 18.6 | Todo |  |  |  | [notes](06.%20System%20%26%20OOP%20Design/2619.%20Array%20Prototype%20Last/2619.%20Array%20Prototype%20Last.md) |
| 3 | [355. Design Twitter](https://leetcode.com/problems/design-twitter/) | Medium | 6 months | 23.1 | Todo |  |  |  | [notes](06.%20System%20%26%20OOP%20Design/0355.%20Design%20Twitter/0355.%20Design%20Twitter.md) |
| 4 | [1603. Design Parking System](https://leetcode.com/problems/design-parking-system/) | Easy | 6 months | 8.5 | Todo |  |  |  | [notes](06.%20System%20%26%20OOP%20Design/1603.%20Design%20Parking%20System/1603.%20Design%20Parking%20System.md) |
| 5 | [2618. Check if Object Instance of Class](https://leetcode.com/problems/check-if-object-instance-of-class/) | Medium | 6 months | 5.0 | Todo |  |  |  | [notes](06.%20System%20%26%20OOP%20Design/2618.%20Check%20if%20Object%20Instance%20of%20Class/2618.%20Check%20if%20Object%20Instance%20of%20Class.md) |
| 6 | [535. Encode and Decode TinyURL](https://leetcode.com/problems/encode-and-decode-tinyurl/) | Medium | 6+ months | 30.6 | Todo |  |  |  | [notes](06.%20System%20%26%20OOP%20Design/0535.%20Encode%20and%20Decode%20TinyURL/0535.%20Encode%20and%20Decode%20TinyURL.md) |
| 7 | [2633. Convert Object to JSON String](https://leetcode.com/problems/convert-object-to-json-string/) 🔒 | Medium | 6+ months | 14.0 | Todo |  |  |  | [notes](06.%20System%20%26%20OOP%20Design/2633.%20Convert%20Object%20to%20JSON%20String/2633.%20Convert%20Object%20to%20JSON%20String.md) |
| 8 | [2665. Counter II](https://leetcode.com/problems/counter-ii/) | Easy | 6+ months | 10.3 | Todo |  |  |  | [notes](06.%20System%20%26%20OOP%20Design/2665.%20Counter%20II/2665.%20Counter%20II.md) |
| 9 | [2704. To Be Or Not To Be](https://leetcode.com/problems/to-be-or-not-to-be/) | Easy | 6+ months | 10.0 | Todo |  |  |  | [notes](06.%20System%20%26%20OOP%20Design/2704.%20To%20Be%20Or%20Not%20To%20Be/2704.%20To%20Be%20Or%20Not%20To%20Be.md) |
| 10 | [631. Design Excel Sum Formula](https://leetcode.com/problems/design-excel-sum-formula/) 🔒 | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20System%20%26%20OOP%20Design/0631.%20Design%20Excel%20Sum%20Formula/0631.%20Design%20Excel%20Sum%20Formula.md) |
| 11 | [1396. Design Underground System](https://leetcode.com/problems/design-underground-system/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20System%20%26%20OOP%20Design/1396.%20Design%20Underground%20System/1396.%20Design%20Underground%20System.md) |
| 12 | [2043. Simple Bank System](https://leetcode.com/problems/simple-bank-system/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20System%20%26%20OOP%20Design/2043.%20Simple%20Bank%20System/2043.%20Simple%20Bank%20System.md) |
| 13 | [2502. Design Memory Allocator](https://leetcode.com/problems/design-memory-allocator/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20System%20%26%20OOP%20Design/2502.%20Design%20Memory%20Allocator/2502.%20Design%20Memory%20Allocator.md) |
| 14 | [2621. Sleep](https://leetcode.com/problems/sleep/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20System%20%26%20OOP%20Design/2621.%20Sleep/2621.%20Sleep.md) |
| 15 | [2626. Array Reduce Transformation](https://leetcode.com/problems/array-reduce-transformation/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20System%20%26%20OOP%20Design/2626.%20Array%20Reduce%20Transformation/2626.%20Array%20Reduce%20Transformation.md) |
| 16 | [2629. Function Composition](https://leetcode.com/problems/function-composition/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20System%20%26%20OOP%20Design/2629.%20Function%20Composition/2629.%20Function%20Composition.md) |
| 17 | [2630. Memoize II](https://leetcode.com/problems/memoize-ii/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20System%20%26%20OOP%20Design/2630.%20Memoize%20II/2630.%20Memoize%20II.md) |
| 18 | [2634. Filter Elements from Array](https://leetcode.com/problems/filter-elements-from-array/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20System%20%26%20OOP%20Design/2634.%20Filter%20Elements%20from%20Array/2634.%20Filter%20Elements%20from%20Array.md) |
| 19 | [2635. Apply Transform Over Each Element in Array](https://leetcode.com/problems/apply-transform-over-each-element-in-array/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20System%20%26%20OOP%20Design/2635.%20Apply%20Transform%20Over%20Each%20Element%20in%20Array/2635.%20Apply%20Transform%20Over%20Each%20Element%20in%20Array.md) |
| 20 | [2637. Promise Time Limit](https://leetcode.com/problems/promise-time-limit/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20System%20%26%20OOP%20Design/2637.%20Promise%20Time%20Limit/2637.%20Promise%20Time%20Limit.md) |
| 21 | [2648. Generate Fibonacci Sequence](https://leetcode.com/problems/generate-fibonacci-sequence/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20System%20%26%20OOP%20Design/2648.%20Generate%20Fibonacci%20Sequence/2648.%20Generate%20Fibonacci%20Sequence.md) |
| 22 | [2666. Allow One Function Call](https://leetcode.com/problems/allow-one-function-call/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20System%20%26%20OOP%20Design/2666.%20Allow%20One%20Function%20Call/2666.%20Allow%20One%20Function%20Call.md) |
| 23 | [2677. Chunk Array](https://leetcode.com/problems/chunk-array/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20System%20%26%20OOP%20Design/2677.%20Chunk%20Array/2677.%20Chunk%20Array.md) |
| 24 | [2700. Differences Between Two Objects](https://leetcode.com/problems/differences-between-two-objects/) 🔒 | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20System%20%26%20OOP%20Design/2700.%20Differences%20Between%20Two%20Objects/2700.%20Differences%20Between%20Two%20Objects.md) |
| 25 | [2703. Return Length of Arguments Passed](https://leetcode.com/problems/return-length-of-arguments-passed/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20System%20%26%20OOP%20Design/2703.%20Return%20Length%20of%20Arguments%20Passed/2703.%20Return%20Length%20of%20Arguments%20Passed.md) |
| 26 | [2715. Timeout Cancellation](https://leetcode.com/problems/timeout-cancellation/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20System%20%26%20OOP%20Design/2715.%20Timeout%20Cancellation/2715.%20Timeout%20Cancellation.md) |
| 27 | [2723. Add Two Promises](https://leetcode.com/problems/add-two-promises/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20System%20%26%20OOP%20Design/2723.%20Add%20Two%20Promises/2723.%20Add%20Two%20Promises.md) |
| 28 | [2724. Sort By](https://leetcode.com/problems/sort-by/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20System%20%26%20OOP%20Design/2724.%20Sort%20By/2724.%20Sort%20By.md) |
| 29 | [3484. Design Spreadsheet](https://leetcode.com/problems/design-spreadsheet/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20System%20%26%20OOP%20Design/3484.%20Design%20Spreadsheet/3484.%20Design%20Spreadsheet.md) |
| 30 | [348. Design Tic-Tac-Toe](https://leetcode.com/problems/design-tic-tac-toe/) 🔒 | Medium | 6+ months | 29.9 | Todo |  |  |  | [notes](06.%20System%20%26%20OOP%20Design/0348.%20Design%20Tic-Tac-Toe/0348.%20Design%20Tic-Tac-Toe.md) |
| 31 | [1600. Throne Inheritance](https://leetcode.com/problems/throne-inheritance/) | Medium | 6+ months | 29.7 | Todo |  |  |  | [notes](06.%20System%20%26%20OOP%20Design/1600.%20Throne%20Inheritance/1600.%20Throne%20Inheritance.md) |
| 32 | [353. Design Snake Game](https://leetcode.com/problems/design-snake-game/) 🔒 | Medium | 6+ months | 28.8 | Todo |  |  |  | [notes](06.%20System%20%26%20OOP%20Design/0353.%20Design%20Snake%20Game/0353.%20Design%20Snake%20Game.md) |
| 33 | [1993. Operations on Tree](https://leetcode.com/problems/operations-on-tree/) | Medium | 6+ months | 28.8 | Todo |  |  |  | [notes](06.%20System%20%26%20OOP%20Design/1993.%20Operations%20on%20Tree/1993.%20Operations%20on%20Tree.md) |
| 34 | [2241. Design an ATM Machine](https://leetcode.com/problems/design-an-atm-machine/) | Medium | 6+ months | 28.8 | Todo |  |  |  | [notes](06.%20System%20%26%20OOP%20Design/2241.%20Design%20an%20ATM%20Machine/2241.%20Design%20an%20ATM%20Machine.md) |
| 35 | [2623. Memoize](https://leetcode.com/problems/memoize/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20System%20%26%20OOP%20Design/2623.%20Memoize/2623.%20Memoize.md) |

## 07. Time-Based Design (Rate Limiter, Hit Counter)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [359. Logger Rate Limiter](https://leetcode.com/problems/logger-rate-limiter/) 🔒 | Easy | 3 months | 55.9 | Todo |  |  |  | [notes](07.%20Time-Based%20Design%20%28Rate%20Limiter%2C%20Hit%20Counter%29/0359.%20Logger%20Rate%20Limiter/0359.%20Logger%20Rate%20Limiter.md) |
| 2 | [981. Time Based Key-Value Store](https://leetcode.com/problems/time-based-key-value-store/) | Medium | 3 months | 34.2 | ✅ Solved |  |  |  | [notes](07.%20Time-Based%20Design%20%28Rate%20Limiter%2C%20Hit%20Counter%29/0981.%20Time%20Based%20Key-Value%20Store/0981.%20Time%20Based%20Key-Value%20Store.md) |
| 3 | [362. Design Hit Counter](https://leetcode.com/problems/design-hit-counter/) 🔒 | Medium | 6 months | 39.1 | Todo |  |  |  | [notes](07.%20Time-Based%20Design%20%28Rate%20Limiter%2C%20Hit%20Counter%29/0362.%20Design%20Hit%20Counter/0362.%20Design%20Hit%20Counter.md) |
| 4 | [1146. Snapshot Array](https://leetcode.com/problems/snapshot-array/) | Medium | 6 months | 36.9 | Todo |  |  |  | [notes](07.%20Time-Based%20Design%20%28Rate%20Limiter%2C%20Hit%20Counter%29/1146.%20Snapshot%20Array/1146.%20Snapshot%20Array.md) |
| 5 | [933. Number of Recent Calls](https://leetcode.com/problems/number-of-recent-calls/) | Easy | 6 months | 32.1 | Todo |  |  |  | [notes](07.%20Time-Based%20Design%20%28Rate%20Limiter%2C%20Hit%20Counter%29/0933.%20Number%20of%20Recent%20Calls/0933.%20Number%20of%20Recent%20Calls.md) |
| 6 | [911. Online Election](https://leetcode.com/problems/online-election/) | Medium | 6+ months | 31.0 | Todo |  |  |  | [notes](07.%20Time-Based%20Design%20%28Rate%20Limiter%2C%20Hit%20Counter%29/0911.%20Online%20Election/0911.%20Online%20Election.md) |
| 7 | [2622. Cache With Time Limit](https://leetcode.com/problems/cache-with-time-limit/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](07.%20Time-Based%20Design%20%28Rate%20Limiter%2C%20Hit%20Counter%29/2622.%20Cache%20With%20Time%20Limit/2622.%20Cache%20With%20Time%20Limit.md) |
