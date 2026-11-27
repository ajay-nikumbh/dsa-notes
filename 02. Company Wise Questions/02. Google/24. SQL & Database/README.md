# 24. SQL & Database

[Back to Google](../README.md) · [Back to DSA Notes](../../../README.md)

91 Google problems: 58 Easy, 28 Medium, 5 Hard, in 7 sub-patterns.

## Sub-patterns

| # | Sub-pattern | Questions | Easy | Medium | Hard | Last 3 Months | Solved | Most Asked |
|:---:|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---|
| 01 | [Basic Select & Filter](#01-basic-select--filter) | 17 | 17 | 0 | 0 | 7 | 9 | 1757. Recyclable and Low Fat Products, 1821. Find Customers With Positive Revenue this Year, 1148. Article Views I |
| 02 | [Joins](#02-joins) | 17 | 12 | 4 | 1 | 7 | 12 | 175. Combine Two Tables, 181. Employees Earning More Than Their Managers, 197. Rising Temperature |
| 03 | [Aggregation & Group By](#03-aggregation--group-by) | 19 | 14 | 5 | 0 | 4 | 18 | 1193. Monthly Transactions I, 1211. Queries Quality and Percentage, 1075. Project Employees I |
| 04 | [Subqueries & CTE](#04-subqueries--cte) | 16 | 7 | 8 | 1 | 3 | 8 | 176. Second Highest Salary, 1767. Find the Subtasks That Did Not Execute, 183. Customers Who Never Order |
| 05 | [Window Functions](#05-window-functions) | 9 | 0 | 6 | 3 | 2 | 0 | 569. Median Employee Salary, 180. Consecutive Numbers, 178. Rank Scores |
| 06 | [Date & String Functions](#06-date--string-functions) | 7 | 5 | 2 | 0 | 0 | 3 | 1141. User Activity for the Past 30 Days I, 1667. Fix Names in a Table, 1517. Find Users With Valid E-Mails |
| 07 | [Conditional Logic (CASE)](#07-conditional-logic-case) | 6 | 3 | 3 | 0 | 0 | 3 | 610. Triangle Judgement, 626. Exchange Seats, 1873. Calculate Special Bonus |

**Columns**

- **Last Asked**: most recent LeetCode window that lists the problem for Google (30 days, 3 months, 6 months, 6+ months).
- **Frequency**: LeetCode frequency score (0-100) in the Google "All" list.
- **Status**: your LeetCode status on the day this file was generated. 🔒 after a title means LeetCode Premium.
- **Logic / Key Idea, Time, Space**: fill these in as you solve. A rebuild keeps what you typed.
- **Notes**: link to the problem's notes file.

Inside each sub-pattern, rows are sorted by most recent window, then by frequency (highest first).

## 01. Basic Select & Filter

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [1757. Recyclable and Low Fat Products](https://leetcode.com/problems/recyclable-and-low-fat-products/) | Easy | 30 days | 49.1 | ✅ Solved |  |  |  | [notes](01.%20Basic%20Select%20%26%20Filter/1757.%20Recyclable%20and%20Low%20Fat%20Products/1757.%20Recyclable%20and%20Low%20Fat%20Products.md) |
| 2 | [584. Find Customer Referee](https://leetcode.com/problems/find-customer-referee/) | Easy | 30 days | 25.9 | ✅ Solved |  |  |  | [notes](01.%20Basic%20Select%20%26%20Filter/0584.%20Find%20Customer%20Referee/0584.%20Find%20Customer%20Referee.md) |
| 3 | [1148. Article Views I](https://leetcode.com/problems/article-views-i/) | Easy | 3 months | 28.0 | ✅ Solved |  |  |  | [notes](01.%20Basic%20Select%20%26%20Filter/1148.%20Article%20Views%20I/1148.%20Article%20Views%20I.md) |
| 4 | [2877. Create a DataFrame from List](https://leetcode.com/problems/create-a-dataframe-from-list/) | Easy | 3 months | 22.2 | Todo |  |  |  | [notes](01.%20Basic%20Select%20%26%20Filter/2877.%20Create%20a%20DataFrame%20from%20List/2877.%20Create%20a%20DataFrame%20from%20List.md) |
| 5 | [595. Big Countries](https://leetcode.com/problems/big-countries/) | Easy | 3 months | 19.6 | ✅ Solved |  |  |  | [notes](01.%20Basic%20Select%20%26%20Filter/0595.%20Big%20Countries/0595.%20Big%20Countries.md) |
| 6 | [1683. Invalid Tweets](https://leetcode.com/problems/invalid-tweets/) | Easy | 3 months | 15.9 | ✅ Solved |  |  |  | [notes](01.%20Basic%20Select%20%26%20Filter/1683.%20Invalid%20Tweets/1683.%20Invalid%20Tweets.md) |
| 7 | [196. Delete Duplicate Emails](https://leetcode.com/problems/delete-duplicate-emails/) | Easy | 3 months | 14.0 | ✅ Solved |  |  |  | [notes](01.%20Basic%20Select%20%26%20Filter/0196.%20Delete%20Duplicate%20Emails/0196.%20Delete%20Duplicate%20Emails.md) |
| 8 | [1795. Rearrange Products Table](https://leetcode.com/problems/rearrange-products-table/) | Easy | 6 months | 12.9 | Todo |  |  |  | [notes](01.%20Basic%20Select%20%26%20Filter/1795.%20Rearrange%20Products%20Table/1795.%20Rearrange%20Products%20Table.md) |
| 9 | [2881. Create a New Column](https://leetcode.com/problems/create-a-new-column/) | Easy | 6 months | 6.2 | Todo |  |  |  | [notes](01.%20Basic%20Select%20%26%20Filter/2881.%20Create%20a%20New%20Column/2881.%20Create%20a%20New%20Column.md) |
| 10 | [620. Not Boring Movies](https://leetcode.com/problems/not-boring-movies/) | Easy | 6+ months | 9.2 | ✅ Solved |  |  |  | [notes](01.%20Basic%20Select%20%26%20Filter/0620.%20Not%20Boring%20Movies/0620.%20Not%20Boring%20Movies.md) |
| 11 | [2878. Get the Size of a DataFrame](https://leetcode.com/problems/get-the-size-of-a-dataframe/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Basic%20Select%20%26%20Filter/2878.%20Get%20the%20Size%20of%20a%20DataFrame/2878.%20Get%20the%20Size%20of%20a%20DataFrame.md) |
| 12 | [2879. Display the First Three Rows](https://leetcode.com/problems/display-the-first-three-rows/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Basic%20Select%20%26%20Filter/2879.%20Display%20the%20First%20Three%20Rows/2879.%20Display%20the%20First%20Three%20Rows.md) |
| 13 | [2880. Select Data](https://leetcode.com/problems/select-data/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Basic%20Select%20%26%20Filter/2880.%20Select%20Data/2880.%20Select%20Data.md) |
| 14 | [2887. Fill Missing Data](https://leetcode.com/problems/fill-missing-data/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](01.%20Basic%20Select%20%26%20Filter/2887.%20Fill%20Missing%20Data/2887.%20Fill%20Missing%20Data.md) |
| 15 | [2888. Reshape Data: Concatenate](https://leetcode.com/problems/reshape-data-concatenate/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Basic%20Select%20%26%20Filter/2888.%20Reshape%20Data-%20Concatenate/2888.%20Reshape%20Data-%20Concatenate.md) |
| 16 | [1821. Find Customers With Positive Revenue this Year](https://leetcode.com/problems/find-customers-with-positive-revenue-this-year/) 🔒 | Easy | 6+ months | 28.8 | ✅ Solved |  |  |  | [notes](01.%20Basic%20Select%20%26%20Filter/1821.%20Find%20Customers%20With%20Positive%20Revenue%20this%20Year/1821.%20Find%20Customers%20With%20Positive%20Revenue%20this%20Year.md) |
| 17 | [2882. Drop Duplicate Rows](https://leetcode.com/problems/drop-duplicate-rows/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](01.%20Basic%20Select%20%26%20Filter/2882.%20Drop%20Duplicate%20Rows/2882.%20Drop%20Duplicate%20Rows.md) |

## 02. Joins

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [175. Combine Two Tables](https://leetcode.com/problems/combine-two-tables/) | Easy | 30 days | 51.4 | ✅ Solved |  |  |  | [notes](02.%20Joins/0175.%20Combine%20Two%20Tables/0175.%20Combine%20Two%20Tables.md) |
| 2 | [181. Employees Earning More Than Their Managers](https://leetcode.com/problems/employees-earning-more-than-their-managers/) | Easy | 30 days | 36.8 | ✅ Solved |  |  |  | [notes](02.%20Joins/0181.%20Employees%20Earning%20More%20Than%20Their%20Managers/0181.%20Employees%20Earning%20More%20Than%20Their%20Managers.md) |
| 3 | [197. Rising Temperature](https://leetcode.com/problems/rising-temperature/) | Easy | 3 months | 32.1 | ✅ Solved |  |  |  | [notes](02.%20Joins/0197.%20Rising%20Temperature/0197.%20Rising%20Temperature.md) |
| 4 | [1280. Students and Examinations](https://leetcode.com/problems/students-and-examinations/) | Easy | 3 months | 23.7 | ✅ Solved |  |  |  | [notes](02.%20Joins/1280.%20Students%20and%20Examinations/1280.%20Students%20and%20Examinations.md) |
| 5 | [1934. Confirmation Rate](https://leetcode.com/problems/confirmation-rate/) | Medium | 3 months | 18.3 | Todo |  |  |  | [notes](02.%20Joins/1934.%20Confirmation%20Rate/1934.%20Confirmation%20Rate.md) |
| 6 | [1068. Product Sales Analysis I](https://leetcode.com/problems/product-sales-analysis-i/) | Easy | 3 months | 8.7 | ✅ Solved |  |  |  | [notes](02.%20Joins/1068.%20Product%20Sales%20Analysis%20I/1068.%20Product%20Sales%20Analysis%20I.md) |
| 7 | [262. Trips and Users](https://leetcode.com/problems/trips-and-users/) | Hard | 3 months | 7.6 | Todo |  |  |  | [notes](02.%20Joins/0262.%20Trips%20and%20Users/0262.%20Trips%20and%20Users.md) |
| 8 | [1378. Replace Employee ID With The Unique Identifier](https://leetcode.com/problems/replace-employee-id-with-the-unique-identifier/) | Easy | 6 months | 26.4 | ✅ Solved |  |  |  | [notes](02.%20Joins/1378.%20Replace%20Employee%20ID%20With%20The%20Unique%20Identifier/1378.%20Replace%20Employee%20ID%20With%20The%20Unique%20Identifier.md) |
| 9 | [577. Employee Bonus](https://leetcode.com/problems/employee-bonus/) | Easy | 6 months | 24.6 | ✅ Solved |  |  |  | [notes](02.%20Joins/0577.%20Employee%20Bonus/0577.%20Employee%20Bonus.md) |
| 10 | [1581. Customer Who Visited but Did Not Make Any Transactions](https://leetcode.com/problems/customer-who-visited-but-did-not-make-any-transactions/) | Easy | 6 months | 21.9 | ✅ Solved |  |  |  | [notes](02.%20Joins/1581.%20Customer%20Who%20Visited%20but%20Did%20Not%20Make%20Any%20Transactions/1581.%20Customer%20Who%20Visited%20but%20Did%20Not%20Make%20Any%20Transactions.md) |
| 11 | [1661. Average Time of Process per Machine](https://leetcode.com/problems/average-time-of-process-per-machine/) | Easy | 6 months | 21.9 | ✅ Solved |  |  |  | [notes](02.%20Joins/1661.%20Average%20Time%20of%20Process%20per%20Machine/1661.%20Average%20Time%20of%20Process%20per%20Machine.md) |
| 12 | [1251. Average Selling Price](https://leetcode.com/problems/average-selling-price/) | Easy | 6 months | 20.1 | ✅ Solved |  |  |  | [notes](02.%20Joins/1251.%20Average%20Selling%20Price/1251.%20Average%20Selling%20Price.md) |
| 13 | [1158. Market Analysis I](https://leetcode.com/problems/market-analysis-i/) | Medium | 6+ months | 11.2 | Todo |  |  |  | [notes](02.%20Joins/1158.%20Market%20Analysis%20I/1158.%20Market%20Analysis%20I.md) |
| 14 | [1731. The Number of Employees Which Report to Each Employee](https://leetcode.com/problems/the-number-of-employees-which-report-to-each-employee/) | Easy | 6+ months | 11.1 | ✅ Solved |  |  |  | [notes](02.%20Joins/1731.%20The%20Number%20of%20Employees%20Which%20Report%20to%20Each%20Employee/1731.%20The%20Number%20of%20Employees%20Which%20Report%20to%20Each%20Employee.md) |
| 15 | [1407. Top Travellers](https://leetcode.com/problems/top-travellers/) | Easy | 6+ months | 5.8 | ✅ Solved |  |  |  | [notes](02.%20Joins/1407.%20Top%20Travellers/1407.%20Top%20Travellers.md) |
| 16 | [1949. Strong Friendship](https://leetcode.com/problems/strong-friendship/) 🔒 | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](02.%20Joins/1949.%20Strong%20Friendship/1949.%20Strong%20Friendship.md) |
| 17 | [1270. All People Report to the Given Manager](https://leetcode.com/problems/all-people-report-to-the-given-manager/) 🔒 | Medium | 6+ months | 28.8 | Todo |  |  |  | [notes](02.%20Joins/1270.%20All%20People%20Report%20to%20the%20Given%20Manager/1270.%20All%20People%20Report%20to%20the%20Given%20Manager.md) |

## 03. Aggregation & Group By

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [1193. Monthly Transactions I](https://leetcode.com/problems/monthly-transactions-i/) | Medium | 3 months | 25.5 | ✅ Solved |  |  |  | [notes](03.%20Aggregation%20%26%20Group%20By/1193.%20Monthly%20Transactions%20I/1193.%20Monthly%20Transactions%20I.md) |
| 2 | [1211. Queries Quality and Percentage](https://leetcode.com/problems/queries-quality-and-percentage/) | Easy | 3 months | 24.0 | ✅ Solved |  |  |  | [notes](03.%20Aggregation%20%26%20Group%20By/1211.%20Queries%20Quality%20and%20Percentage/1211.%20Queries%20Quality%20and%20Percentage.md) |
| 3 | [182. Duplicate Emails](https://leetcode.com/problems/duplicate-emails/) | Easy | 3 months | 16.4 | ✅ Solved |  |  |  | [notes](03.%20Aggregation%20%26%20Group%20By/0182.%20Duplicate%20Emails/0182.%20Duplicate%20Emails.md) |
| 4 | [511. Game Play Analysis I](https://leetcode.com/problems/game-play-analysis-i/) | Easy | 3 months | 11.6 | ✅ Solved |  |  |  | [notes](03.%20Aggregation%20%26%20Group%20By/0511.%20Game%20Play%20Analysis%20I/0511.%20Game%20Play%20Analysis%20I.md) |
| 5 | [570. Managers with at Least 5 Direct Reports](https://leetcode.com/problems/managers-with-at-least-5-direct-reports/) | Medium | 6 months | 19.3 | ✅ Solved |  |  |  | [notes](03.%20Aggregation%20%26%20Group%20By/0570.%20Managers%20with%20at%20Least%205%20Direct%20Reports/0570.%20Managers%20with%20at%20Least%205%20Direct%20Reports.md) |
| 6 | [2356. Number of Unique Subjects Taught by Each Teacher](https://leetcode.com/problems/number-of-unique-subjects-taught-by-each-teacher/) | Easy | 6 months | 12.9 | ✅ Solved |  |  |  | [notes](03.%20Aggregation%20%26%20Group%20By/2356.%20Number%20of%20Unique%20Subjects%20Taught%20by%20Each%20Teacher/2356.%20Number%20of%20Unique%20Subjects%20Taught%20by%20Each%20Teacher.md) |
| 7 | [602. Friend Requests II: Who Has the Most Friends](https://leetcode.com/problems/friend-requests-ii-who-has-the-most-friends/) | Medium | 6 months | 10.7 | ✅ Solved |  |  |  | [notes](03.%20Aggregation%20%26%20Group%20By/0602.%20Friend%20Requests%20II-%20Who%20Has%20the%20Most%20Friends/0602.%20Friend%20Requests%20II-%20Who%20Has%20the%20Most%20Friends.md) |
| 8 | [1341. Movie Rating](https://leetcode.com/problems/movie-rating/) | Medium | 6 months | 6.5 | Todo |  |  |  | [notes](03.%20Aggregation%20%26%20Group%20By/1341.%20Movie%20Rating/1341.%20Movie%20Rating.md) |
| 9 | [1741. Find Total Time Spent by Each Employee](https://leetcode.com/problems/find-total-time-spent-by-each-employee/) | Easy | 6 months | 5.0 | ✅ Solved |  |  |  | [notes](03.%20Aggregation%20%26%20Group%20By/1741.%20Find%20Total%20Time%20Spent%20by%20Each%20Employee/1741.%20Find%20Total%20Time%20Spent%20by%20Each%20Employee.md) |
| 10 | [1075. Project Employees I](https://leetcode.com/problems/project-employees-i/) | Easy | 6+ months | 22.3 | ✅ Solved |  |  |  | [notes](03.%20Aggregation%20%26%20Group%20By/1075.%20Project%20Employees%20I/1075.%20Project%20Employees%20I.md) |
| 11 | [1633. Percentage of Users Attended a Contest](https://leetcode.com/problems/percentage-of-users-attended-a-contest/) | Easy | 6+ months | 13.7 | ✅ Solved |  |  |  | [notes](03.%20Aggregation%20%26%20Group%20By/1633.%20Percentage%20of%20Users%20Attended%20a%20Contest/1633.%20Percentage%20of%20Users%20Attended%20a%20Contest.md) |
| 12 | [1484. Group Sold Products By The Date](https://leetcode.com/problems/group-sold-products-by-the-date/) | Easy | 6+ months | 12.5 | ✅ Solved |  |  |  | [notes](03.%20Aggregation%20%26%20Group%20By/1484.%20Group%20Sold%20Products%20By%20The%20Date/1484.%20Group%20Sold%20Products%20By%20The%20Date.md) |
| 13 | [1045. Customers Who Bought All Products](https://leetcode.com/problems/customers-who-bought-all-products/) | Medium | 6+ months | 7.3 | ✅ Solved |  |  |  | [notes](03.%20Aggregation%20%26%20Group%20By/1045.%20Customers%20Who%20Bought%20All%20Products/1045.%20Customers%20Who%20Bought%20All%20Products.md) |
| 14 | [596. Classes With at Least 5 Students](https://leetcode.com/problems/classes-with-at-least-5-students/) | Easy | 6+ months | 5.8 | ✅ Solved |  |  |  | [notes](03.%20Aggregation%20%26%20Group%20By/0596.%20Classes%20With%20at%20Least%205%20Students/0596.%20Classes%20With%20at%20Least%205%20Students.md) |
| 15 | [586. Customer Placing the Largest Number of Orders](https://leetcode.com/problems/customer-placing-the-largest-number-of-orders/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](03.%20Aggregation%20%26%20Group%20By/0586.%20Customer%20Placing%20the%20Largest%20Number%20of%20Orders/0586.%20Customer%20Placing%20the%20Largest%20Number%20of%20Orders.md) |
| 16 | [1050. Actors and Directors Who Cooperated At Least Three Times](https://leetcode.com/problems/actors-and-directors-who-cooperated-at-least-three-times/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](03.%20Aggregation%20%26%20Group%20By/1050.%20Actors%20and%20Directors%20Who%20Cooperated%20At%20Least%20Three%20Times/1050.%20Actors%20and%20Directors%20Who%20Cooperated%20At%20Least%20Three%20Times.md) |
| 17 | [1693. Daily Leads and Partners](https://leetcode.com/problems/daily-leads-and-partners/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](03.%20Aggregation%20%26%20Group%20By/1693.%20Daily%20Leads%20and%20Partners/1693.%20Daily%20Leads%20and%20Partners.md) |
| 18 | [1729. Find Followers Count](https://leetcode.com/problems/find-followers-count/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](03.%20Aggregation%20%26%20Group%20By/1729.%20Find%20Followers%20Count/1729.%20Find%20Followers%20Count.md) |
| 19 | [1587. Bank Account Summary II](https://leetcode.com/problems/bank-account-summary-ii/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](03.%20Aggregation%20%26%20Group%20By/1587.%20Bank%20Account%20Summary%20II/1587.%20Bank%20Account%20Summary%20II.md) |

## 04. Subqueries & CTE

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [1164. Product Price at a Given Date](https://leetcode.com/problems/product-price-at-a-given-date/) | Medium | 3 months | 19.4 | Todo |  |  |  | [notes](04.%20Subqueries%20%26%20CTE/1164.%20Product%20Price%20at%20a%20Given%20Date/1164.%20Product%20Price%20at%20a%20Given%20Date.md) |
| 2 | [184. Department Highest Salary](https://leetcode.com/problems/department-highest-salary/) | Medium | 3 months | 18.5 | Todo |  |  |  | [notes](04.%20Subqueries%20%26%20CTE/0184.%20Department%20Highest%20Salary/0184.%20Department%20Highest%20Salary.md) |
| 3 | [1174. Immediate Food Delivery II](https://leetcode.com/problems/immediate-food-delivery-ii/) | Medium | 3 months | 13.3 | Todo |  |  |  | [notes](04.%20Subqueries%20%26%20CTE/1174.%20Immediate%20Food%20Delivery%20II/1174.%20Immediate%20Food%20Delivery%20II.md) |
| 4 | [176. Second Highest Salary](https://leetcode.com/problems/second-highest-salary/) | Medium | 6 months | 31.3 | ✅ Solved |  |  |  | [notes](04.%20Subqueries%20%26%20CTE/0176.%20Second%20Highest%20Salary/0176.%20Second%20Highest%20Salary.md) |
| 5 | [183. Customers Who Never Order](https://leetcode.com/problems/customers-who-never-order/) | Easy | 6 months | 28.2 | ✅ Solved |  |  |  | [notes](04.%20Subqueries%20%26%20CTE/0183.%20Customers%20Who%20Never%20Order/0183.%20Customers%20Who%20Never%20Order.md) |
| 6 | [1789. Primary Department for Each Employee](https://leetcode.com/problems/primary-department-for-each-employee/) | Easy | 6 months | 9.1 | Todo |  |  |  | [notes](04.%20Subqueries%20%26%20CTE/1789.%20Primary%20Department%20for%20Each%20Employee/1789.%20Primary%20Department%20for%20Each%20Employee.md) |
| 7 | [619. Biggest Single Number](https://leetcode.com/problems/biggest-single-number/) | Easy | 6 months | 5.0 | ✅ Solved |  |  |  | [notes](04.%20Subqueries%20%26%20CTE/0619.%20Biggest%20Single%20Number/0619.%20Biggest%20Single%20Number.md) |
| 8 | [585. Investments in 2016](https://leetcode.com/problems/investments-in-2016/) | Medium | 6+ months | 13.2 | ✅ Solved |  |  |  | [notes](04.%20Subqueries%20%26%20CTE/0585.%20Investments%20in%202016/0585.%20Investments%20in%202016.md) |
| 9 | [550. Game Play Analysis IV](https://leetcode.com/problems/game-play-analysis-iv/) | Medium | 6+ months | 11.9 | Todo |  |  |  | [notes](04.%20Subqueries%20%26%20CTE/0550.%20Game%20Play%20Analysis%20IV/0550.%20Game%20Play%20Analysis%20IV.md) |
| 10 | [177. Nth Highest Salary](https://leetcode.com/problems/nth-highest-salary/) | Medium | 6+ months | 10.4 | Todo |  |  |  | [notes](04.%20Subqueries%20%26%20CTE/0177.%20Nth%20Highest%20Salary/0177.%20Nth%20Highest%20Salary.md) |
| 11 | [1070. Product Sales Analysis III](https://leetcode.com/problems/product-sales-analysis-iii/) | Medium | 6+ months | 6.9 | Todo |  |  |  | [notes](04.%20Subqueries%20%26%20CTE/1070.%20Product%20Sales%20Analysis%20III/1070.%20Product%20Sales%20Analysis%20III.md) |
| 12 | [607. Sales Person](https://leetcode.com/problems/sales-person/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](04.%20Subqueries%20%26%20CTE/0607.%20Sales%20Person/0607.%20Sales%20Person.md) |
| 13 | [1084. Sales Analysis III](https://leetcode.com/problems/sales-analysis-iii/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](04.%20Subqueries%20%26%20CTE/1084.%20Sales%20Analysis%20III/1084.%20Sales%20Analysis%20III.md) |
| 14 | [1965. Employees With Missing Information](https://leetcode.com/problems/employees-with-missing-information/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](04.%20Subqueries%20%26%20CTE/1965.%20Employees%20With%20Missing%20Information/1965.%20Employees%20With%20Missing%20Information.md) |
| 15 | [1978. Employees Whose Manager Left the Company](https://leetcode.com/problems/employees-whose-manager-left-the-company/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](04.%20Subqueries%20%26%20CTE/1978.%20Employees%20Whose%20Manager%20Left%20the%20Company/1978.%20Employees%20Whose%20Manager%20Left%20the%20Company.md) |
| 16 | [1767. Find the Subtasks That Did Not Execute](https://leetcode.com/problems/find-the-subtasks-that-did-not-execute/) 🔒 | Hard | 6+ months | 28.8 | Todo |  |  |  | [notes](04.%20Subqueries%20%26%20CTE/1767.%20Find%20the%20Subtasks%20That%20Did%20Not%20Execute/1767.%20Find%20the%20Subtasks%20That%20Did%20Not%20Execute.md) |

## 05. Window Functions

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [180. Consecutive Numbers](https://leetcode.com/problems/consecutive-numbers/) | Medium | 3 months | 24.5 | Todo |  |  |  | [notes](05.%20Window%20Functions/0180.%20Consecutive%20Numbers/0180.%20Consecutive%20Numbers.md) |
| 2 | [178. Rank Scores](https://leetcode.com/problems/rank-scores/) | Medium | 3 months | 18.8 | Todo |  |  |  | [notes](05.%20Window%20Functions/0178.%20Rank%20Scores/0178.%20Rank%20Scores.md) |
| 3 | [1204. Last Person to Fit in the Bus](https://leetcode.com/problems/last-person-to-fit-in-the-bus/) | Medium | 6 months | 8.3 | Todo |  |  |  | [notes](05.%20Window%20Functions/1204.%20Last%20Person%20to%20Fit%20in%20the%20Bus/1204.%20Last%20Person%20to%20Fit%20in%20the%20Bus.md) |
| 4 | [601. Human Traffic of Stadium](https://leetcode.com/problems/human-traffic-of-stadium/) | Hard | 6 months | 8.2 | Todo |  |  |  | [notes](05.%20Window%20Functions/0601.%20Human%20Traffic%20of%20Stadium/0601.%20Human%20Traffic%20of%20Stadium.md) |
| 5 | [1321. Restaurant Growth](https://leetcode.com/problems/restaurant-growth/) | Medium | 6+ months | 7.9 | Todo |  |  |  | [notes](05.%20Window%20Functions/1321.%20Restaurant%20Growth/1321.%20Restaurant%20Growth.md) |
| 6 | [185. Department Top Three Salaries](https://leetcode.com/problems/department-top-three-salaries/) | Hard | 6+ months | 6.9 | Todo |  |  |  | [notes](05.%20Window%20Functions/0185.%20Department%20Top%20Three%20Salaries/0185.%20Department%20Top%20Three%20Salaries.md) |
| 7 | [1112. Highest Grade For Each Student](https://leetcode.com/problems/highest-grade-for-each-student/) 🔒 | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Window%20Functions/1112.%20Highest%20Grade%20For%20Each%20Student/1112.%20Highest%20Grade%20For%20Each%20Student.md) |
| 8 | [3421. Find Students Who Improved](https://leetcode.com/problems/find-students-who-improved/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](05.%20Window%20Functions/3421.%20Find%20Students%20Who%20Improved/3421.%20Find%20Students%20Who%20Improved.md) |
| 9 | [569. Median Employee Salary](https://leetcode.com/problems/median-employee-salary/) 🔒 | Hard | 6+ months | 28.8 | Todo |  |  |  | [notes](05.%20Window%20Functions/0569.%20Median%20Employee%20Salary/0569.%20Median%20Employee%20Salary.md) |

## 06. Date & String Functions

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [1141. User Activity for the Past 30 Days I](https://leetcode.com/problems/user-activity-for-the-past-30-days-i/) | Easy | 6 months | 16.3 | ✅ Solved |  |  |  | [notes](06.%20Date%20%26%20String%20Functions/1141.%20User%20Activity%20for%20the%20Past%2030%20Days%20I/1141.%20User%20Activity%20for%20the%20Past%2030%20Days%20I.md) |
| 2 | [1517. Find Users With Valid E-Mails](https://leetcode.com/problems/find-users-with-valid-e-mails/) | Easy | 6 months | 5.0 | Todo |  |  |  | [notes](06.%20Date%20%26%20String%20Functions/1517.%20Find%20Users%20With%20Valid%20E-Mails/1517.%20Find%20Users%20With%20Valid%20E-Mails.md) |
| 3 | [1667. Fix Names in a Table](https://leetcode.com/problems/fix-names-in-a-table/) | Easy | 6+ months | 5.9 | ✅ Solved |  |  |  | [notes](06.%20Date%20%26%20String%20Functions/1667.%20Fix%20Names%20in%20a%20Table/1667.%20Fix%20Names%20in%20a%20Table.md) |
| 4 | [1527. Patients With a Condition](https://leetcode.com/problems/patients-with-a-condition/) | Easy | 6+ months | 5.0 | ✅ Solved |  |  |  | [notes](06.%20Date%20%26%20String%20Functions/1527.%20Patients%20With%20a%20Condition/1527.%20Patients%20With%20a%20Condition.md) |
| 5 | [1890. The Latest Login in 2020](https://leetcode.com/problems/the-latest-login-in-2020/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20Date%20%26%20String%20Functions/1890.%20The%20Latest%20Login%20in%202020/1890.%20The%20Latest%20Login%20in%202020.md) |
| 6 | [3475. DNA Pattern Recognition ](https://leetcode.com/problems/dna-pattern-recognition/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20Date%20%26%20String%20Functions/3475.%20DNA%20Pattern%20Recognition%20/3475.%20DNA%20Pattern%20Recognition%20.md) |
| 7 | [3586. Find COVID Recovery Patients](https://leetcode.com/problems/find-covid-recovery-patients/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](06.%20Date%20%26%20String%20Functions/3586.%20Find%20COVID%20Recovery%20Patients/3586.%20Find%20COVID%20Recovery%20Patients.md) |

## 07. Conditional Logic (CASE)

| # | Problem | Difficulty | Last Asked | Frequency | Status | Logic / Key Idea | Time | Space | Notes |
|:---:|:---|:---:|:---:|:---:|:---:|:---|:---:|:---:|:---:|
| 1 | [610. Triangle Judgement](https://leetcode.com/problems/triangle-judgement/) | Easy | 6 months | 17.1 | ✅ Solved |  |  |  | [notes](07.%20Conditional%20Logic%20%28CASE%29/0610.%20Triangle%20Judgement/0610.%20Triangle%20Judgement.md) |
| 2 | [1907. Count Salary Categories](https://leetcode.com/problems/count-salary-categories/) | Medium | 6 months | 5.0 | ✅ Solved |  |  |  | [notes](07.%20Conditional%20Logic%20%28CASE%29/1907.%20Count%20Salary%20Categories/1907.%20Count%20Salary%20Categories.md) |
| 3 | [626. Exchange Seats](https://leetcode.com/problems/exchange-seats/) | Medium | 6+ months | 12.0 | Todo |  |  |  | [notes](07.%20Conditional%20Logic%20%28CASE%29/0626.%20Exchange%20Seats/0626.%20Exchange%20Seats.md) |
| 4 | [1873. Calculate Special Bonus](https://leetcode.com/problems/calculate-special-bonus/) | Easy | 6+ months | 5.6 | ✅ Solved |  |  |  | [notes](07.%20Conditional%20Logic%20%28CASE%29/1873.%20Calculate%20Special%20Bonus/1873.%20Calculate%20Special%20Bonus.md) |
| 5 | [608. Tree Node](https://leetcode.com/problems/tree-node/) | Medium | 6+ months | 5.0 | Todo |  |  |  | [notes](07.%20Conditional%20Logic%20%28CASE%29/0608.%20Tree%20Node/0608.%20Tree%20Node.md) |
| 6 | [1179. Reformat Department Table](https://leetcode.com/problems/reformat-department-table/) | Easy | 6+ months | 5.0 | Todo |  |  |  | [notes](07.%20Conditional%20Logic%20%28CASE%29/1179.%20Reformat%20Department%20Table/1179.%20Reformat%20Department%20Table.md) |
