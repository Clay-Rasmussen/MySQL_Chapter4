# MySQL_Chapter4_MultiTableQueries

## Overview
___
This chapter focuses on retrieving data from multiple tables in the MySQL Sakila database. The exercises demonstrate different types of SQL
joins and set operations, including inner joins, outer joins, self-joins, cross joins, and unions. The goal is to understand how related
information can be combined from multiple tables using different SQL techniques.

## Table of Contents
___
* [New Concepts](#new-concepts)
* [Tech Stack](#tech-stack)
* [Installation](#installation)
* [Running Output](#running-output)
* [Learning Outcomes](#learning-outcomes)
* [Help](#help)
* [Authors](#author)

### New Concepts
___
* Inner Join – Combines records from two tables when matching values exist.
* Compound Join Condition – Uses multiple conditions when joining tables.
* Self-Join – Joins a table to itself to compare records within the same table.
* Multiple Table Joins – Combines information from more than two tables.
* Implicit Inner Join – Uses comma-separated tables with a `WHERE` clause instead of the `JOIN` keyword.
* Left Outer Join – Returns all records from the left table, including records without a match.
* Right Outer Join – Returns all records from the right table, including records without a match.
* `USING` Keyword – Provides a shorter way to specify a join when the related columns have the same name.
* `NATURAL` Join – Automatically joins tables using columns with matching names.
* Cross Join – Combines every record from one table with every record from another table.
* `UNION` – Combines the results of multiple queries into one result set.
* Full Outer Join – Returns matching records as well as unmatched records from both tables.

## Tech Stack
___
![GitHub](https://img.shields.io/badge/GitHub-000000.svg?style=for-the-badge&logo=GitHub)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
**Sakila Database**

## Installation
___
1. Clone the repository to your local machine. (Or just steal my code.)
2. Install MySQL if it is not already installed.
3. Download and install the Sakila sample database.
4. Open the project in VS Code or your preferred SQL editor.
5. Select the Sakila database before running the queries.
6. Run each query individually to verify the results.

## Running Output
___
**Query 1**

<img src="assets/Query_1.png" alt="Query 1" width="500" />

**Query 2**

<img src="assets/Query_2.png" alt="Query 2" width="500" />

**Query 3**

<img src="assets/Query_3.png" alt="Query 3" width="500" />

**Query 4**

<img src="assets/Query_4.png" alt="Query 4" width="500" />

**Query 5**

<img src="assets/Query_5.png" alt="Query 5" width="500" />

**Query 6**

<img src="assets/Query_6.png" alt="Query 6" width="500" />

**Query 7**

<img src="assets/Query_7.png" alt="Query 7" width="500" />

**Query 8**

<img src="assets/Query_8.png" alt="Query 8" width="500" />

**Query 9**

<img src="assets/Query_9.png" alt="Query 9" width="500" />

**Query 10**

<img src="assets/Query_10.png" alt="Query 10" width="500" />

## Learning Outcomes
___
* Retrieve information from multiple tables using SQL joins.
* Understand and use different types of joins.
* Use table aliases to make SQL queries easier to read.
* Create compound join conditions.
* Use a self-join to compare records within the same table.
* Join three or more tables together.
* Understand the difference between explicit and implicit join syntax.
* Use LEFT OUTER JOIN and RIGHT OUTER JOIN.
* Use the USING and NATURAL JOIN keywords.
* Create a CROSS JOIN to generate combinations of records.
* Combine query results using UNION.
* Understand how a FULL OUTER JOIN works.
* Sort and limit query results using ORDER BY and LIMIT.
* Write properly formatted and documented SQL queries.

## Help
___
* Make sure compiler is running correctly.
* Potentially re-clone repository
* restart IDE

## Author
___
<img src="https://github.com/Clay-Rasmussen.png" alt="Profile Picture" width="100" />

**Clay Rasmussen**
* **Clay's GitHub Profile**: [Clay-Rasmussen](https://github.com/Clay-Rasmussen)
* **Clay's Email**: [clrasm02@wsc.edu](mailto:clrasm02@wsc.edu)

<img src="https://github.com/28cyager.png" alt="Profile Picture" width="100" />

**Christian Yager**
* **Christian's GitHub Profile**: [28cyager](https://github.com/28cyager)
* **Christian's Email**: [chyage01@wsc.edu](mailto:chyage01@wsc.edu)

[Back to the top](#overview)
