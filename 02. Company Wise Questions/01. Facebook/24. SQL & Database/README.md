# 24. SQL & Database

[Back to Facebook](../README.md) · [Back to DSA Notes](../../../README.md)

85 Meta (Facebook) problems: 48 Easy, 32 Medium, 5 Hard, in 7 sub-patterns.

## Sub-patterns

| # | Sub-pattern | Questions | Easy | Medium | Hard | Last 3 Months | Solved | Most Asked |
|:---:|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---|
| 01 | [Basic Select & Filter](#01-basic-select--filter) | 12 | 12 | 0 | 0 | 2 | 7 | 1757. Recyclable and Low Fat Products, 1148. Article Views I, 584. Find Customer Referee |
| 02 | [Joins](#02-joins) | 20 | 13 | 5 | 2 | 3 | 11 | 1661. Average Time of Process per Machine, 1264. Page Recommendations, 1892. Page Recommendations II |
| 03 | [Aggregation & Group By](#03-aggregation--group-by) | 15 | 9 | 6 | 0 | 0 | 12 | 602. Friend Requests II: Who Has the Most Friends, 1211. Queries Quality and Percentage, 1075. Project Employees I |
| 04 | [Subqueries & CTE](#04-subqueries--cte) | 16 | 6 | 10 | 0 | 0 | 4 | 597. Friend Requests I: Overall Acceptance Rate, 1132. Reported Posts II, 1076. Project Employees II |
| 05 | [Window Functions](#05-window-functions) | 8 | 0 | 5 | 3 | 1 | 0 | 1077. Project Employees III, 1225. Report Contiguous Dates, 180. Consecutive Numbers |
| 06 | [Date & String Functions](#06-date--string-functions) | 4 | 3 | 1 | 0 | 0 | 3 | 1141. User Activity for the Past 30 Days I, 1527. Patients With a Condition, 1667. Fix Names in a Table |
| 07 | [Conditional Logic (CASE)](#07-conditional-logic-case) | 10 | 5 | 5 | 0 | 0 | 3 | 1322. Ads Performance, 1398. Customers Who Bought Products A and B but Not C, 1445. Apples & Oranges |

**Columns**

- **Last Asked**: most recent LeetCode window that lists the problem for Meta (30 days, 3 months, 6 months or 6+ months).
- **Frequency**: LeetCode frequency score (0-100) in the Meta "All" list.
- **Status**: your LeetCode status on the day this file was generated. 🔒 after a title means LeetCode Premium.
- **Logic / Key Idea, Time, Space**: fill these in as you solve. A rebuild keeps what you typed.
- **Notes**: link to the problem's notes file.

Inside each sub-pattern, rows are sorted by most recent window, then by frequency (highest first).

## 01. Basic Select & Filter

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [1757. Recyclable and Low Fat Products](https://leetcode.com/problems/recyclable-and-low-fat-products/) | Easy | 3 months | 48.7 | ✅ Solved |  |  |  | [notes](01.%20Basic%20Select%20%26%20Filter/1757.%20Recyclable%20and%20Low%20Fat%20Products/1757.%20Recyclable%20and%20Low%20Fat%20Products.md) |
| 2 | [2891. Method Chaining](https://leetcode.com/problems/method-chaining/) | Easy | 3 months | 8.3 | Todo |  |  |  | [notes](01.%20Basic%20Select%20%26%20Filter/2891.%20Method%20Chaining/2891.%20Method%20Chaining.md) |
| 3 | [1148. Article Views I](https://leetcode.com/problems/article-views-i/) | Easy | 6 months | 31.2 | ✅ Solved |  |  |  | [notes](01.%20Basic%20Select%20%26%20Filter/1148.%20Article%20Views%20I/1148.%20Article%20Views%20I.md) |
| 4 | [584. Find Customer Referee](https://leetcode.com/problems/find-customer-referee/) | Easy | 6 months | 15.3 | ✅ Solved |  |  |  | [notes](01.%20Basic%20Select%20%26%20Filter/0584.%20Find%20Customer%20Referee/0584.%20Find%20Customer%20Referee.md) |
| 5 | [620. Not Boring Movies](https://leetcode.com/problems/not-boring-movies/) | Easy | 6 months | 14.9 | ✅ Solved |  |  |  | [notes](01.%20Basic%20Select%20%26%20Filter/0620.%20Not%20Boring%20Movies/0620.%20Not%20Boring%20Movies.md) |
| 6 | [1683. Invalid Tweets](https://leetcode.com/problems/invalid-tweets/) | Easy | 6 months | 9.6 | ✅ Solved |  |  |  | [notes](01.%20Basic%20Select%20%26%20Filter/1683.%20Invalid%20Tweets/1683.%20Invalid%20Tweets.md) |
| 7 | [196. Delete Duplicate Emails](https://leetcode.com/problems/delete-duplicate-emails/) | Easy | 6+ months | 12.7 | ✅ Solved |  |  |  | [notes](01.%20Basic%20Select%20%26%20Filter/0196.%20Delete%20Duplicate%20Emails/0196.%20Delete%20Duplicate%20Emails.md) |
| 8 | [595. Big Countries](https://leetcode.com/problems/big-countries/) | Easy | 6+ months | 10.1 | ✅ Solved |  |  |  | [notes](01.%20Basic%20Select%20%26%20Filter/0595.%20Big%20Countries/0595.%20Big%20Countries.md) |
| 9 | [2877. Create a DataFrame from List](https://leetcode.com/problems/create-a-dataframe-from-list/) | Easy | 6+ months | 10.1 | Todo |  |  |  | [notes](01.%20Basic%20Select%20%26%20Filter/2877.%20Create%20a%20DataFrame%20from%20List/2877.%20Create%20a%20DataFrame%20from%20List.md) |
| 10 | [1795. Rearrange Products Table](https://leetcode.com/problems/rearrange-products-table/) | Easy | 6+ months | 5.6 | Todo |  |  |  | [notes](01.%20Basic%20Select%20%26%20Filter/1795.%20Rearrange%20Products%20Table/1795.%20Rearrange%20Products%20Table.md) |
| 11 | [2879. Display the First Three Rows](https://leetcode.com/problems/display-the-first-three-rows/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Basic%20Select%20%26%20Filter/2879.%20Display%20the%20First%20Three%20Rows/2879.%20Display%20the%20First%20Three%20Rows.md) |
| 12 | [2889. Reshape Data: Pivot](https://leetcode.com/problems/reshape-data-pivot/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Basic%20Select%20%26%20Filter/2889.%20Reshape%20Data-%20Pivot/2889.%20Reshape%20Data-%20Pivot.md) |

## 02. Joins

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [197. Rising Temperature](https://leetcode.com/problems/rising-temperature/) | Easy | 3 months | 24.3 | ✅ Solved |  |  |  | [notes](02.%20Joins/0197.%20Rising%20Temperature/0197.%20Rising%20Temperature.md) |
| 2 | [175. Combine Two Tables](https://leetcode.com/problems/combine-two-tables/) | Easy | 3 months | 23.8 | ✅ Solved |  |  |  | [notes](02.%20Joins/0175.%20Combine%20Two%20Tables/0175.%20Combine%20Two%20Tables.md) |
| 3 | [181. Employees Earning More Than Their Managers](https://leetcode.com/problems/employees-earning-more-than-their-managers/) | Easy | 3 months | 16.0 | ✅ Solved |  |  |  | [notes](02.%20Joins/0181.%20Employees%20Earning%20More%20Than%20Their%20Managers/0181.%20Employees%20Earning%20More%20Than%20Their%20Managers.md) |
| 4 | [577. Employee Bonus](https://leetcode.com/problems/employee-bonus/) | Easy | 6 months | 17.8 | ✅ Solved |  |  |  | [notes](02.%20Joins/0577.%20Employee%20Bonus/0577.%20Employee%20Bonus.md) |
| 5 | [1280. Students and Examinations](https://leetcode.com/problems/students-and-examinations/) | Easy | 6 months | 12.4 | ✅ Solved |  |  |  | [notes](02.%20Joins/1280.%20Students%20and%20Examinations/1280.%20Students%20and%20Examinations.md) |
| 6 | [1661. Average Time of Process per Machine](https://leetcode.com/problems/average-time-of-process-per-machine/) | Easy | 6+ months | 40.0 | ✅ Solved |  |  |  | [notes](02.%20Joins/1661.%20Average%20Time%20of%20Process%20per%20Machine/1661.%20Average%20Time%20of%20Process%20per%20Machine.md) |
| 7 | [1264. Page Recommendations](https://leetcode.com/problems/page-recommendations/) 🔒 | Medium | 6+ months | 39.3 | Todo |  |  |  | [notes](02.%20Joins/1264.%20Page%20Recommendations/1264.%20Page%20Recommendations.md) |
| 8 | [1892. Page Recommendations II](https://leetcode.com/problems/page-recommendations-ii/) 🔒 | Hard | 6+ months | 37.5 | Todo |  |  |  | [notes](02.%20Joins/1892.%20Page%20Recommendations%20II/1892.%20Page%20Recommendations%20II.md) |
| 9 | [1949. Strong Friendship](https://leetcode.com/problems/strong-friendship/) 🔒 | Medium | 6+ months | 37.1 | Todo |  |  |  | [notes](02.%20Joins/1949.%20Strong%20Friendship/1949.%20Strong%20Friendship.md) |
| 10 | [1581. Customer Who Visited but Did Not Make Any Transactions](https://leetcode.com/problems/customer-who-visited-but-did-not-make-any-transactions/) | Easy | 6+ months | 20.6 | ✅ Solved |  |  |  | [notes](02.%20Joins/1581.%20Customer%20Who%20Visited%20but%20Did%20Not%20Make%20Any%20Transactions/1581.%20Customer%20Who%20Visited%20but%20Did%20Not%20Make%20Any%20Transactions.md) |
| 11 | [1251. Average Selling Price](https://leetcode.com/problems/average-selling-price/) | Easy | 6+ months | 13.8 | ✅ Solved |  |  |  | [notes](02.%20Joins/1251.%20Average%20Selling%20Price/1251.%20Average%20Selling%20Price.md) |
| 12 | [1378. Replace Employee ID With The Unique Identifier](https://leetcode.com/problems/replace-employee-id-with-the-unique-identifier/) | Easy | 6+ months | 10.2 | ✅ Solved |  |  |  | [notes](02.%20Joins/1378.%20Replace%20Employee%20ID%20With%20The%20Unique%20Identifier/1378.%20Replace%20Employee%20ID%20With%20The%20Unique%20Identifier.md) |
| 13 | [1934. Confirmation Rate](https://leetcode.com/problems/confirmation-rate/) | Medium | 6+ months | 8.7 | Todo |  |  |  | [notes](02.%20Joins/1934.%20Confirmation%20Rate/1934.%20Confirmation%20Rate.md) |
| 14 | [1068. Product Sales Analysis I](https://leetcode.com/problems/product-sales-analysis-i/) | Easy | 6+ months | 6.6 | ✅ Solved |  |  |  | [notes](02.%20Joins/1068.%20Product%20Sales%20Analysis%20I/1068.%20Product%20Sales%20Analysis%20I.md) |
| 15 | [3570. Find Books with No Available Copies](https://leetcode.com/problems/find-books-with-no-available-copies/) | Easy | 6+ months | 6.3 | Todo |  |  |  | [notes](02.%20Joins/3570.%20Find%20Books%20with%20No%20Available%20Copies/3570.%20Find%20Books%20with%20No%20Available%20Copies.md) |
| 16 | [612. Shortest Distance in a Plane](https://leetcode.com/problems/shortest-distance-in-a-plane/) 🔒 | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Joins/0612.%20Shortest%20Distance%20in%20a%20Plane/0612.%20Shortest%20Distance%20in%20a%20Plane.md) |
| 17 | [1731. The Number of Employees Which Report to Each Employee](https://leetcode.com/problems/the-number-of-employees-which-report-to-each-employee/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](02.%20Joins/1731.%20The%20Number%20of%20Employees%20Which%20Report%20to%20Each%20Employee/1731.%20The%20Number%20of%20Employees%20Which%20Report%20to%20Each%20Employee.md) |
| 18 | [1241. Number of Comments per Post](https://leetcode.com/problems/number-of-comments-per-post/) 🔒 | Easy | 6+ months | 36.1 | Todo |  |  |  | [notes](02.%20Joins/1241.%20Number%20of%20Comments%20per%20Post/1241.%20Number%20of%20Comments%20per%20Post.md) |
| 19 | [1951. All the Pairs With the Maximum Number of Common Followers](https://leetcode.com/problems/all-the-pairs-with-the-maximum-number-of-common-followers/) 🔒 | Medium | 6+ months | 36.1 | Todo |  |  |  | [notes](02.%20Joins/1951.%20All%20the%20Pairs%20With%20the%20Maximum%20Number%20of%20Common%20Followers/1951.%20All%20the%20Pairs%20With%20the%20Maximum%20Number%20of%20Common%20Followers.md) |
| 20 | [2199. Finding the Topic of Each Post](https://leetcode.com/problems/finding-the-topic-of-each-post/) 🔒 | Hard | 6+ months | 36.1 | Todo |  |  |  | [notes](02.%20Joins/2199.%20Finding%20the%20Topic%20of%20Each%20Post/2199.%20Finding%20the%20Topic%20of%20Each%20Post.md) |

## 03. Aggregation & Group By

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [1193. Monthly Transactions I](https://leetcode.com/problems/monthly-transactions-i/) | Medium | 6 months | 23.8 | ✅ Solved |  |  |  | [notes](03.%20Aggregation%20%26%20Group%20By/1193.%20Monthly%20Transactions%20I/1193.%20Monthly%20Transactions%20I.md) |
| 2 | [1045. Customers Who Bought All Products](https://leetcode.com/problems/customers-who-bought-all-products/) | Medium | 6 months | 21.9 | ✅ Solved |  |  |  | [notes](03.%20Aggregation%20%26%20Group%20By/1045.%20Customers%20Who%20Bought%20All%20Products/1045.%20Customers%20Who%20Bought%20All%20Products.md) |
| 3 | [511. Game Play Analysis I](https://leetcode.com/problems/game-play-analysis-i/) | Easy | 6 months | 8.5 | ✅ Solved |  |  |  | [notes](03.%20Aggregation%20%26%20Group%20By/0511.%20Game%20Play%20Analysis%20I/0511.%20Game%20Play%20Analysis%20I.md) |
| 4 | [602. Friend Requests II: Who Has the Most Friends](https://leetcode.com/problems/friend-requests-ii-who-has-the-most-friends/) | Medium | 6+ months | 42.1 | ✅ Solved |  |  |  | [notes](03.%20Aggregation%20%26%20Group%20By/0602.%20Friend%20Requests%20II-%20Who%20Has%20the%20Most%20Friends/0602.%20Friend%20Requests%20II-%20Who%20Has%20the%20Most%20Friends.md) |
| 5 | [1211. Queries Quality and Percentage](https://leetcode.com/problems/queries-quality-and-percentage/) | Easy | 6+ months | 38.5 | ✅ Solved |  |  |  | [notes](03.%20Aggregation%20%26%20Group%20By/1211.%20Queries%20Quality%20and%20Percentage/1211.%20Queries%20Quality%20and%20Percentage.md) |
| 6 | [1075. Project Employees I](https://leetcode.com/problems/project-employees-i/) | Easy | 6+ months | 38.3 | ✅ Solved |  |  |  | [notes](03.%20Aggregation%20%26%20Group%20By/1075.%20Project%20Employees%20I/1075.%20Project%20Employees%20I.md) |
| 7 | [570. Managers with at Least 5 Direct Reports](https://leetcode.com/problems/managers-with-at-least-5-direct-reports/) | Medium | 6+ months | 17.0 | ✅ Solved |  |  |  | [notes](03.%20Aggregation%20%26%20Group%20By/0570.%20Managers%20with%20at%20Least%205%20Direct%20Reports/0570.%20Managers%20with%20at%20Least%205%20Direct%20Reports.md) |
| 8 | [1341. Movie Rating](https://leetcode.com/problems/movie-rating/) | Medium | 6+ months | 15.9 | Todo |  |  |  | [notes](03.%20Aggregation%20%26%20Group%20By/1341.%20Movie%20Rating/1341.%20Movie%20Rating.md) |
| 9 | [182. Duplicate Emails](https://leetcode.com/problems/duplicate-emails/) | Easy | 6+ months | 11.6 | ✅ Solved |  |  |  | [notes](03.%20Aggregation%20%26%20Group%20By/0182.%20Duplicate%20Emails/0182.%20Duplicate%20Emails.md) |
| 10 | [1633. Percentage of Users Attended a Contest](https://leetcode.com/problems/percentage-of-users-attended-a-contest/) | Easy | 6+ months | 10.1 | ✅ Solved |  |  |  | [notes](03.%20Aggregation%20%26%20Group%20By/1633.%20Percentage%20of%20Users%20Attended%20a%20Contest/1633.%20Percentage%20of%20Users%20Attended%20a%20Contest.md) |
| 11 | [1484. Group Sold Products By The Date](https://leetcode.com/problems/group-sold-products-by-the-date/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](03.%20Aggregation%20%26%20Group%20By/1484.%20Group%20Sold%20Products%20By%20The%20Date/1484.%20Group%20Sold%20Products%20By%20The%20Date.md) |
| 12 | [578. Get Highest Answer Rate Question](https://leetcode.com/problems/get-highest-answer-rate-question/) 🔒 | Medium | 6+ months | 36.7 | Todo |  |  |  | [notes](03.%20Aggregation%20%26%20Group%20By/0578.%20Get%20Highest%20Answer%20Rate%20Question/0578.%20Get%20Highest%20Answer%20Rate%20Question.md) |
| 13 | [1113. Reported Posts](https://leetcode.com/problems/reported-posts/) 🔒 | Easy | 6+ months | 36.1 | Todo |  |  |  | [notes](03.%20Aggregation%20%26%20Group%20By/1113.%20Reported%20Posts/1113.%20Reported%20Posts.md) |
| 14 | [596. Classes With at Least 5 Students](https://leetcode.com/problems/classes-with-at-least-5-students/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](03.%20Aggregation%20%26%20Group%20By/0596.%20Classes%20With%20at%20Least%205%20Students/0596.%20Classes%20With%20at%20Least%205%20Students.md) |
| 15 | [2356. Number of Unique Subjects Taught by Each Teacher](https://leetcode.com/problems/number-of-unique-subjects-taught-by-each-teacher/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](03.%20Aggregation%20%26%20Group%20By/2356.%20Number%20of%20Unique%20Subjects%20Taught%20by%20Each%20Teacher/2356.%20Number%20of%20Unique%20Subjects%20Taught%20by%20Each%20Teacher.md) |

## 04. Subqueries & CTE

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [183. Customers Who Never Order](https://leetcode.com/problems/customers-who-never-order/) | Easy | 6 months | 21.9 | ✅ Solved |  |  |  | [notes](04.%20Subqueries%20%26%20CTE/0183.%20Customers%20Who%20Never%20Order/0183.%20Customers%20Who%20Never%20Order.md) |
| 2 | [176. Second Highest Salary](https://leetcode.com/problems/second-highest-salary/) | Medium | 6 months | 20.1 | ✅ Solved |  |  |  | [notes](04.%20Subqueries%20%26%20CTE/0176.%20Second%20Highest%20Salary/0176.%20Second%20Highest%20Salary.md) |
| 3 | [184. Department Highest Salary](https://leetcode.com/problems/department-highest-salary/) | Medium | 6 months | 13.5 | Todo |  |  |  | [notes](04.%20Subqueries%20%26%20CTE/0184.%20Department%20Highest%20Salary/0184.%20Department%20Highest%20Salary.md) |
| 4 | [585. Investments in 2016](https://leetcode.com/problems/investments-in-2016/) | Medium | 6 months | 12.9 | ✅ Solved |  |  |  | [notes](04.%20Subqueries%20%26%20CTE/0585.%20Investments%20in%202016/0585.%20Investments%20in%202016.md) |
| 5 | [597. Friend Requests I: Overall Acceptance Rate](https://leetcode.com/problems/friend-requests-i-overall-acceptance-rate/) 🔒 | Easy | 6+ months | 37.8 | Todo |  |  |  | [notes](04.%20Subqueries%20%26%20CTE/0597.%20Friend%20Requests%20I-%20Overall%20Acceptance%20Rate/0597.%20Friend%20Requests%20I-%20Overall%20Acceptance%20Rate.md) |
| 6 | [550. Game Play Analysis IV](https://leetcode.com/problems/game-play-analysis-iv/) | Medium | 6+ months | 15.1 | Todo |  |  |  | [notes](04.%20Subqueries%20%26%20CTE/0550.%20Game%20Play%20Analysis%20IV/0550.%20Game%20Play%20Analysis%20IV.md) |
| 7 | [607. Sales Person](https://leetcode.com/problems/sales-person/) | Easy | 6+ months | 12.7 | ✅ Solved |  |  |  | [notes](04.%20Subqueries%20%26%20CTE/0607.%20Sales%20Person/0607.%20Sales%20Person.md) |
| 8 | [1174. Immediate Food Delivery II](https://leetcode.com/problems/immediate-food-delivery-ii/) | Medium | 6+ months | 11.3 | Todo |  |  |  | [notes](04.%20Subqueries%20%26%20CTE/1174.%20Immediate%20Food%20Delivery%20II/1174.%20Immediate%20Food%20Delivery%20II.md) |
| 9 | [1070. Product Sales Analysis III](https://leetcode.com/problems/product-sales-analysis-iii/) | Medium | 6+ months | 9.9 | Todo |  |  |  | [notes](04.%20Subqueries%20%26%20CTE/1070.%20Product%20Sales%20Analysis%20III/1070.%20Product%20Sales%20Analysis%20III.md) |
| 10 | [177. Nth Highest Salary](https://leetcode.com/problems/nth-highest-salary/) | Medium | 6+ months | 7.6 | Todo |  |  |  | [notes](04.%20Subqueries%20%26%20CTE/0177.%20Nth%20Highest%20Salary/0177.%20Nth%20Highest%20Salary.md) |
| 11 | [1164. Product Price at a Given Date](https://leetcode.com/problems/product-price-at-a-given-date/) | Medium | 6+ months | 7.1 | Todo |  |  |  | [notes](04.%20Subqueries%20%26%20CTE/1164.%20Product%20Price%20at%20a%20Given%20Date/1164.%20Product%20Price%20at%20a%20Given%20Date.md) |
| 12 | [1789. Primary Department for Each Employee](https://leetcode.com/problems/primary-department-for-each-employee/) | Easy | 6+ months | 6.4 | Todo |  |  |  | [notes](04.%20Subqueries%20%26%20CTE/1789.%20Primary%20Department%20for%20Each%20Employee/1789.%20Primary%20Department%20for%20Each%20Employee.md) |
| 13 | [1098. Unpopular Books](https://leetcode.com/problems/unpopular-books/) 🔒 | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](04.%20Subqueries%20%26%20CTE/1098.%20Unpopular%20Books/1098.%20Unpopular%20Books.md) |
| 14 | [1132. Reported Posts II](https://leetcode.com/problems/reported-posts-ii/) 🔒 | Medium | 6+ months | 36.7 | Todo |  |  |  | [notes](04.%20Subqueries%20%26%20CTE/1132.%20Reported%20Posts%20II/1132.%20Reported%20Posts%20II.md) |
| 15 | [1076. Project Employees II](https://leetcode.com/problems/project-employees-ii/) 🔒 | Easy | 6+ months | 36.1 | Todo |  |  |  | [notes](04.%20Subqueries%20%26%20CTE/1076.%20Project%20Employees%20II/1076.%20Project%20Employees%20II.md) |
| 16 | [1142. User Activity for the Past 30 Days II](https://leetcode.com/problems/user-activity-for-the-past-30-days-ii/) 🔒 | Easy | 6+ months | 36.1 | Todo |  |  |  | [notes](04.%20Subqueries%20%26%20CTE/1142.%20User%20Activity%20for%20the%20Past%2030%20Days%20II/1142.%20User%20Activity%20for%20the%20Past%2030%20Days%20II.md) |

## 05. Window Functions

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [180. Consecutive Numbers](https://leetcode.com/problems/consecutive-numbers/) | Medium | 3 months | 21.6 | Todo |  |  |  | [notes](05.%20Window%20Functions/0180.%20Consecutive%20Numbers/0180.%20Consecutive%20Numbers.md) |
| 2 | [1321. Restaurant Growth](https://leetcode.com/problems/restaurant-growth/) | Medium | 6 months | 7.6 | Todo |  |  |  | [notes](05.%20Window%20Functions/1321.%20Restaurant%20Growth/1321.%20Restaurant%20Growth.md) |
| 3 | [185. Department Top Three Salaries](https://leetcode.com/problems/department-top-three-salaries/) | Hard | 6 months | 5.4 | Todo |  |  |  | [notes](05.%20Window%20Functions/0185.%20Department%20Top%20Three%20Salaries/0185.%20Department%20Top%20Three%20Salaries.md) |
| 4 | [178. Rank Scores](https://leetcode.com/problems/rank-scores/) | Medium | 6+ months | 11.9 | Todo |  |  |  | [notes](05.%20Window%20Functions/0178.%20Rank%20Scores/0178.%20Rank%20Scores.md) |
| 5 | [1204. Last Person to Fit in the Bus](https://leetcode.com/problems/last-person-to-fit-in-the-bus/) | Medium | 6+ months | 9.0 | Todo |  |  |  | [notes](05.%20Window%20Functions/1204.%20Last%20Person%20to%20Fit%20in%20the%20Bus/1204.%20Last%20Person%20to%20Fit%20in%20the%20Bus.md) |
| 6 | [601. Human Traffic of Stadium](https://leetcode.com/problems/human-traffic-of-stadium/) | Hard | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Window%20Functions/0601.%20Human%20Traffic%20of%20Stadium/0601.%20Human%20Traffic%20of%20Stadium.md) |
| 7 | [1077. Project Employees III](https://leetcode.com/problems/project-employees-iii/) 🔒 | Medium | 6+ months | 36.1 | Todo |  |  |  | [notes](05.%20Window%20Functions/1077.%20Project%20Employees%20III/1077.%20Project%20Employees%20III.md) |
| 8 | [1225. Report Contiguous Dates](https://leetcode.com/problems/report-contiguous-dates/) 🔒 | Hard | 6+ months | 36.1 | Todo |  |  |  | [notes](05.%20Window%20Functions/1225.%20Report%20Contiguous%20Dates/1225.%20Report%20Contiguous%20Dates.md) |

## 06. Date & String Functions

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [1141. User Activity for the Past 30 Days I](https://leetcode.com/problems/user-activity-for-the-past-30-days-i/) | Easy | 6+ months | 37.9 | ✅ Solved |  |  |  | [notes](06.%20Date%20%26%20String%20Functions/1141.%20User%20Activity%20for%20the%20Past%2030%20Days%20I/1141.%20User%20Activity%20for%20the%20Past%2030%20Days%20I.md) |
| 2 | [1527. Patients With a Condition](https://leetcode.com/problems/patients-with-a-condition/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](06.%20Date%20%26%20String%20Functions/1527.%20Patients%20With%20a%20Condition/1527.%20Patients%20With%20a%20Condition.md) |
| 3 | [1667. Fix Names in a Table](https://leetcode.com/problems/fix-names-in-a-table/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](06.%20Date%20%26%20String%20Functions/1667.%20Fix%20Names%20in%20a%20Table/1667.%20Fix%20Names%20in%20a%20Table.md) |
| 4 | [3475. DNA Pattern Recognition ](https://leetcode.com/problems/dna-pattern-recognition/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20Date%20%26%20String%20Functions/3475.%20DNA%20Pattern%20Recognition%20/3475.%20DNA%20Pattern%20Recognition%20.md) |

## 07. Conditional Logic (CASE)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [610. Triangle Judgement](https://leetcode.com/problems/triangle-judgement/) | Easy | 6 months | 16.7 | ✅ Solved |  |  |  | [notes](07.%20Conditional%20Logic%20%28CASE%29/0610.%20Triangle%20Judgement/0610.%20Triangle%20Judgement.md) |
| 2 | [626. Exchange Seats](https://leetcode.com/problems/exchange-seats/) | Medium | 6+ months | 7.2 | Todo |  |  |  | [notes](07.%20Conditional%20Logic%20%28CASE%29/0626.%20Exchange%20Seats/0626.%20Exchange%20Seats.md) |
| 3 | [608. Tree Node](https://leetcode.com/problems/tree-node/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](07.%20Conditional%20Logic%20%28CASE%29/0608.%20Tree%20Node/0608.%20Tree%20Node.md) |
| 4 | [627. Swap Sex of Employees](https://leetcode.com/problems/swap-sex-of-employees/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](07.%20Conditional%20Logic%20%28CASE%29/0627.%20Swap%20Sex%20of%20Employees/0627.%20Swap%20Sex%20of%20Employees.md) |
| 5 | [1179. Reformat Department Table](https://leetcode.com/problems/reformat-department-table/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](07.%20Conditional%20Logic%20%28CASE%29/1179.%20Reformat%20Department%20Table/1179.%20Reformat%20Department%20Table.md) |
| 6 | [1393. Capital Gain/Loss](https://leetcode.com/problems/capital-gainloss/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](07.%20Conditional%20Logic%20%28CASE%29/1393.%20Capital%20Gain-Loss/1393.%20Capital%20Gain-Loss.md) |
| 7 | [1873. Calculate Special Bonus](https://leetcode.com/problems/calculate-special-bonus/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](07.%20Conditional%20Logic%20%28CASE%29/1873.%20Calculate%20Special%20Bonus/1873.%20Calculate%20Special%20Bonus.md) |
| 8 | [1322. Ads Performance](https://leetcode.com/problems/ads-performance/) 🔒 | Easy | 6+ months | 36.1 | Todo |  |  |  | [notes](07.%20Conditional%20Logic%20%28CASE%29/1322.%20Ads%20Performance/1322.%20Ads%20Performance.md) |
| 9 | [1398. Customers Who Bought Products A and B but Not C](https://leetcode.com/problems/customers-who-bought-products-a-and-b-but-not-c/) 🔒 | Medium | 6+ months | 36.1 | Todo |  |  |  | [notes](07.%20Conditional%20Logic%20%28CASE%29/1398.%20Customers%20Who%20Bought%20Products%20A%20and%20B%20but%20Not%20C/1398.%20Customers%20Who%20Bought%20Products%20A%20and%20B%20but%20Not%20C.md) |
| 10 | [1445. Apples & Oranges](https://leetcode.com/problems/apples-oranges/) 🔒 | Medium | 6+ months | 36.1 | Todo |  |  |  | [notes](07.%20Conditional%20Logic%20%28CASE%29/1445.%20Apples%20%26%20Oranges/1445.%20Apples%20%26%20Oranges.md) |
