# 23. Design

[Back to Facebook](../README.md) · [Back to DSA Notes](../../../README.md)

45 Meta (Facebook) problems: 13 Easy, 25 Medium, 7 Hard, in 7 sub-patterns.

## Sub-patterns

| # | Sub-pattern | Questions | Easy | Medium | Hard | Last 3 Months | Solved | Most Asked |
|:---:|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---|
| 01 | [Data Structure Design](#01-data-structure-design) | 17 | 2 | 10 | 5 | 0 | 1 | 1570. Dot Product of Two Sparse Vectors, 155. Min Stack, 3829. Design Ride Sharing System |
| 02 | [LRU & LFU Cache](#02-lru--lfu-cache) | 2 | 0 | 1 | 1 | 1 | 2 | 146. LRU Cache, 460. LFU Cache |
| 03 | [Iterator Design](#03-iterator-design) | 3 | 0 | 3 | 0 | 0 | 1 | 173. Binary Search Tree Iterator, 341. Flatten Nested List Iterator, 1586. Binary Search Tree Iterator II |
| 04 | [Data Stream Design](#04-data-stream-design) | 1 | 1 | 0 | 0 | 0 | 0 | 346. Moving Average from Data Stream |
| 05 | [Randomized Design](#05-randomized-design) | 3 | 0 | 2 | 1 | 0 | 0 | 380. Insert Delete GetRandom O(1), 381. Insert Delete GetRandom O(1) - Duplicates allowed, 384. Shuffle an Array |
| 06 | [System & OOP Design](#06-system--oop-design) | 15 | 8 | 7 | 0 | 0 | 0 | 348. Design Tic-Tac-Toe, 2043. Simple Bank System, 1357. Apply Discount Every n Orders |
| 07 | [Time-Based Design (Rate Limiter, Hit Counter)](#07-time-based-design-rate-limiter-hit-counter) | 4 | 2 | 2 | 0 | 0 | 1 | 933. Number of Recent Calls, 981. Time Based Key-Value Store, 362. Design Hit Counter |

**Columns**

- **Last Asked**: most recent LeetCode window that lists the problem for Meta (30 days, 3 months, 6 months or 6+ months).
- **Frequency**: LeetCode frequency score (0-100) in the Meta "All" list.
- **Status**: your LeetCode status on the day this file was generated. 🔒 after a title means LeetCode Premium.
- **Logic / Key Idea, Time, Space**: fill these in as you solve. A rebuild keeps what you typed.
- **Notes**: link to the problem's notes file.

Inside each sub-pattern, rows are sorted by most recent window, then by frequency (highest first).

## 01. Data Structure Design

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [155. Min Stack](https://leetcode.com/problems/min-stack/) | Medium | 6 months | 37.0 | ✅ Solved |  |  |  | [notes](01.%20Data%20Structure%20Design/0155.%20Min%20Stack/0155.%20Min%20Stack.md) |
| 2 | [1570. Dot Product of Two Sparse Vectors](https://leetcode.com/problems/dot-product-of-two-sparse-vectors/) 🔒 | Medium | 6+ months | 76.1 | Todo |  |  |  | [notes](01.%20Data%20Structure%20Design/1570.%20Dot%20Product%20of%20Two%20Sparse%20Vectors/1570.%20Dot%20Product%20of%20Two%20Sparse%20Vectors.md) |
| 3 | [622. Design Circular Queue](https://leetcode.com/problems/design-circular-queue/) | Medium | 6+ months | 20.7 | Todo |  |  |  | [notes](01.%20Data%20Structure%20Design/0622.%20Design%20Circular%20Queue/0622.%20Design%20Circular%20Queue.md) |
| 4 | [706. Design HashMap](https://leetcode.com/problems/design-hashmap/) | Easy | 6+ months | 13.9 | Todo |  |  |  | [notes](01.%20Data%20Structure%20Design/0706.%20Design%20HashMap/0706.%20Design%20HashMap.md) |
| 5 | [432. All O`one Data Structure](https://leetcode.com/problems/all-oone-data-structure/) | Hard | 6+ months | 12.7 | Todo |  |  |  | [notes](01.%20Data%20Structure%20Design/0432.%20All%20O%60one%20Data%20Structure/0432.%20All%20O%60one%20Data%20Structure.md) |
| 6 | [1206. Design Skiplist](https://leetcode.com/problems/design-skiplist/) | Hard | 6+ months | 10.9 | Todo |  |  |  | [notes](01.%20Data%20Structure%20Design/1206.%20Design%20Skiplist/1206.%20Design%20Skiplist.md) |
| 7 | [2034. Stock Price Fluctuation ](https://leetcode.com/problems/stock-price-fluctuation/) | Medium | 6+ months | 10.0 | Todo |  |  |  | [notes](01.%20Data%20Structure%20Design/2034.%20Stock%20Price%20Fluctuation%20/2034.%20Stock%20Price%20Fluctuation%20.md) |
| 8 | [2336. Smallest Number in Infinite Set](https://leetcode.com/problems/smallest-number-in-infinite-set/) | Medium | 6+ months | 10.0 | Todo |  |  |  | [notes](01.%20Data%20Structure%20Design/2336.%20Smallest%20Number%20in%20Infinite%20Set/2336.%20Smallest%20Number%20in%20Infinite%20Set.md) |
| 9 | [641. Design Circular Deque](https://leetcode.com/problems/design-circular-deque/) | Medium | 6+ months | 8.5 | Todo |  |  |  | [notes](01.%20Data%20Structure%20Design/0641.%20Design%20Circular%20Deque/0641.%20Design%20Circular%20Deque.md) |
| 10 | [707. Design Linked List](https://leetcode.com/problems/design-linked-list/) | Medium | 6+ months | 7.3 | Todo |  |  |  | [notes](01.%20Data%20Structure%20Design/0707.%20Design%20Linked%20List/0707.%20Design%20Linked%20List.md) |
| 11 | [895. Maximum Frequency Stack](https://leetcode.com/problems/maximum-frequency-stack/) | Hard | 6+ months | 6.4 | Todo |  |  |  | [notes](01.%20Data%20Structure%20Design/0895.%20Maximum%20Frequency%20Stack/0895.%20Maximum%20Frequency%20Stack.md) |
| 12 | [705. Design HashSet](https://leetcode.com/problems/design-hashset/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Data%20Structure%20Design/0705.%20Design%20HashSet/0705.%20Design%20HashSet.md) |
| 13 | [716. Max Stack](https://leetcode.com/problems/max-stack/) 🔒 | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Data%20Structure%20Design/0716.%20Max%20Stack/0716.%20Max%20Stack.md) |
| 14 | [1865. Finding Pairs With a Certain Sum](https://leetcode.com/problems/finding-pairs-with-a-certain-sum/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Data%20Structure%20Design/1865.%20Finding%20Pairs%20With%20a%20Certain%20Sum/1865.%20Finding%20Pairs%20With%20a%20Certain%20Sum.md) |
| 15 | [2013. Detect Squares](https://leetcode.com/problems/detect-squares/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Data%20Structure%20Design/2013.%20Detect%20Squares/2013.%20Detect%20Squares.md) |
| 16 | [2296. Design a Text Editor](https://leetcode.com/problems/design-a-text-editor/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Data%20Structure%20Design/2296.%20Design%20a%20Text%20Editor/2296.%20Design%20a%20Text%20Editor.md) |
| 17 | [3829. Design Ride Sharing System](https://leetcode.com/problems/design-ride-sharing-system/) | Medium | 6+ months | 36.1 | Todo |  |  |  | [notes](01.%20Data%20Structure%20Design/3829.%20Design%20Ride%20Sharing%20System/3829.%20Design%20Ride%20Sharing%20System.md) |

## 02. LRU & LFU Cache

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203;&ensp;&#8203; | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [146. LRU Cache](https://leetcode.com/problems/lru-cache/) | Medium | 3 months | 76.8 | ✅ Solved |  |  |  | [notes](02.%20LRU%20%26%20LFU%20Cache/0146.%20LRU%20Cache/0146.%20LRU%20Cache.md) |
| 2 | [460. LFU Cache](https://leetcode.com/problems/lfu-cache/) | Hard | 6+ months | 8.0 | ✅ Solved |  |  |  | [notes](02.%20LRU%20%26%20LFU%20Cache/0460.%20LFU%20Cache/0460.%20LFU%20Cache.md) |

## 03. Iterator Design

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [173. Binary Search Tree Iterator](https://leetcode.com/problems/binary-search-tree-iterator/) | Medium | 6+ months | 60.6 | ✅ Solved |  |  |  | [notes](03.%20Iterator%20Design/0173.%20Binary%20Search%20Tree%20Iterator/0173.%20Binary%20Search%20Tree%20Iterator.md) |
| 2 | [341. Flatten Nested List Iterator](https://leetcode.com/problems/flatten-nested-list-iterator/) | Medium | 6+ months | 43.8 | Todo |  |  |  | [notes](03.%20Iterator%20Design/0341.%20Flatten%20Nested%20List%20Iterator/0341.%20Flatten%20Nested%20List%20Iterator.md) |
| 3 | [1586. Binary Search Tree Iterator II](https://leetcode.com/problems/binary-search-tree-iterator-ii/) 🔒 | Medium | 6+ months | 36.1 | Todo |  |  |  | [notes](03.%20Iterator%20Design/1586.%20Binary%20Search%20Tree%20Iterator%20II/1586.%20Binary%20Search%20Tree%20Iterator%20II.md) |

## 04. Data Stream Design

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [346. Moving Average from Data Stream](https://leetcode.com/problems/moving-average-from-data-stream/) 🔒 | Easy | 6+ months | 68.8 | Todo |  |  |  | [notes](04.%20Data%20Stream%20Design/0346.%20Moving%20Average%20from%20Data%20Stream/0346.%20Moving%20Average%20from%20Data%20Stream.md) |

## 05. Randomized Design

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [380. Insert Delete GetRandom O(1)](https://leetcode.com/problems/insert-delete-getrandom-o1/) | Medium | 6+ months | 50.1 | Todo |  |  |  | [notes](05.%20Randomized%20Design/0380.%20Insert%20Delete%20GetRandom%20O%281%29/0380.%20Insert%20Delete%20GetRandom%20O%281%29.md) |
| 2 | [381. Insert Delete GetRandom O(1) - Duplicates allowed](https://leetcode.com/problems/insert-delete-getrandom-o1-duplicates-allowed/) | Hard | 6+ months | 13.1 | Todo |  |  |  | [notes](05.%20Randomized%20Design/0381.%20Insert%20Delete%20GetRandom%20O%281%29%20-%20Duplicates%20allowed/0381.%20Insert%20Delete%20GetRandom%20O%281%29%20-%20Duplicates%20allowed.md) |
| 3 | [384. Shuffle an Array](https://leetcode.com/problems/shuffle-an-array/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Randomized%20Design/0384.%20Shuffle%20an%20Array/0384.%20Shuffle%20an%20Array.md) |

## 06. System & OOP Design

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [348. Design Tic-Tac-Toe](https://leetcode.com/problems/design-tic-tac-toe/) 🔒 | Medium | 6+ months | 41.8 | Todo |  |  |  | [notes](06.%20System%20%26%20OOP%20Design/0348.%20Design%20Tic-Tac-Toe/0348.%20Design%20Tic-Tac-Toe.md) |
| 2 | [2043. Simple Bank System](https://leetcode.com/problems/simple-bank-system/) | Medium | 6+ months | 39.0 | Todo |  |  |  | [notes](06.%20System%20%26%20OOP%20Design/2043.%20Simple%20Bank%20System/2043.%20Simple%20Bank%20System.md) |
| 3 | [2502. Design Memory Allocator](https://leetcode.com/problems/design-memory-allocator/) | Medium | 6+ months | 6.3 | Todo |  |  |  | [notes](06.%20System%20%26%20OOP%20Design/2502.%20Design%20Memory%20Allocator/2502.%20Design%20Memory%20Allocator.md) |
| 4 | [1603. Design Parking System](https://leetcode.com/problems/design-parking-system/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20System%20%26%20OOP%20Design/1603.%20Design%20Parking%20System/1603.%20Design%20Parking%20System.md) |
| 5 | [2619. Array Prototype Last](https://leetcode.com/problems/array-prototype-last/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20System%20%26%20OOP%20Design/2619.%20Array%20Prototype%20Last/2619.%20Array%20Prototype%20Last.md) |
| 6 | [2620. Counter](https://leetcode.com/problems/counter/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20System%20%26%20OOP%20Design/2620.%20Counter/2620.%20Counter.md) |
| 7 | [2627. Debounce](https://leetcode.com/problems/debounce/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20System%20%26%20OOP%20Design/2627.%20Debounce/2627.%20Debounce.md) |
| 8 | [2629. Function Composition](https://leetcode.com/problems/function-composition/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20System%20%26%20OOP%20Design/2629.%20Function%20Composition/2629.%20Function%20Composition.md) |
| 9 | [2635. Apply Transform Over Each Element in Array](https://leetcode.com/problems/apply-transform-over-each-element-in-array/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20System%20%26%20OOP%20Design/2635.%20Apply%20Transform%20Over%20Each%20Element%20in%20Array/2635.%20Apply%20Transform%20Over%20Each%20Element%20in%20Array.md) |
| 10 | [2694. Event Emitter](https://leetcode.com/problems/event-emitter/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20System%20%26%20OOP%20Design/2694.%20Event%20Emitter/2694.%20Event%20Emitter.md) |
| 11 | [2704. To Be Or Not To Be](https://leetcode.com/problems/to-be-or-not-to-be/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20System%20%26%20OOP%20Design/2704.%20To%20Be%20Or%20Not%20To%20Be/2704.%20To%20Be%20Or%20Not%20To%20Be.md) |
| 12 | [2715. Timeout Cancellation](https://leetcode.com/problems/timeout-cancellation/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20System%20%26%20OOP%20Design/2715.%20Timeout%20Cancellation/2715.%20Timeout%20Cancellation.md) |
| 13 | [2723. Add Two Promises](https://leetcode.com/problems/add-two-promises/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20System%20%26%20OOP%20Design/2723.%20Add%20Two%20Promises/2723.%20Add%20Two%20Promises.md) |
| 14 | [1357. Apply Discount Every n Orders](https://leetcode.com/problems/apply-discount-every-n-orders/) | Medium | 6+ months | 37.1 | Todo |  |  |  | [notes](06.%20System%20%26%20OOP%20Design/1357.%20Apply%20Discount%20Every%20n%20Orders/1357.%20Apply%20Discount%20Every%20n%20Orders.md) |
| 15 | [535. Encode and Decode TinyURL](https://leetcode.com/problems/encode-and-decode-tinyurl/) | Medium | 6+ months | 36.1 | Todo |  |  |  | [notes](06.%20System%20%26%20OOP%20Design/0535.%20Encode%20and%20Decode%20TinyURL/0535.%20Encode%20and%20Decode%20TinyURL.md) |

## 07. Time-Based Design (Rate Limiter, Hit Counter)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [933. Number of Recent Calls](https://leetcode.com/problems/number-of-recent-calls/) | Easy | 6+ months | 23.0 | Todo |  |  |  | [notes](07.%20Time-Based%20Design%20%28Rate%20Limiter%2C%20Hit%20Counter%29/0933.%20Number%20of%20Recent%20Calls/0933.%20Number%20of%20Recent%20Calls.md) |
| 2 | [981. Time Based Key-Value Store](https://leetcode.com/problems/time-based-key-value-store/) | Medium | 6+ months | 13.7 | ✅ Solved |  |  |  | [notes](07.%20Time-Based%20Design%20%28Rate%20Limiter%2C%20Hit%20Counter%29/0981.%20Time%20Based%20Key-Value%20Store/0981.%20Time%20Based%20Key-Value%20Store.md) |
| 3 | [362. Design Hit Counter](https://leetcode.com/problems/design-hit-counter/) 🔒 | Medium | 6+ months | 9.3 | Todo |  |  |  | [notes](07.%20Time-Based%20Design%20%28Rate%20Limiter%2C%20Hit%20Counter%29/0362.%20Design%20Hit%20Counter/0362.%20Design%20Hit%20Counter.md) |
| 4 | [359. Logger Rate Limiter](https://leetcode.com/problems/logger-rate-limiter/) 🔒 | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](07.%20Time-Based%20Design%20%28Rate%20Limiter%2C%20Hit%20Counter%29/0359.%20Logger%20Rate%20Limiter/0359.%20Logger%20Rate%20Limiter.md) |
