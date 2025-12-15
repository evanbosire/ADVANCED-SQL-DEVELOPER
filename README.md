# ADVANCED-SQL
In this course i have dived into basic to advanced sql using MS SQL

# Advanced SQL Developer Repository

## 📌 Overview

This repository is a **comprehensive Advanced SQL reference and practice guide** designed for developers, data analysts, and database professionals who want to **master SQL beyond the basics**.

It covers **end-to-end SQL concepts**, ranging from simple data retrieval to **advanced analytics, performance optimization, stored procedures, triggers, indexing, and execution plans**. The scripts are written using **T-SQL (Microsoft SQL Server)** syntax.

---

## 🎯 Objectives

By working through this repository, you will be able to:

* Write **efficient and optimized SQL queries**
* Understand and apply **advanced joins and set operations**
* Perform **data aggregation and analytical reporting**
* Handle **NULL values and data transformations** correctly
* Use **CTEs (Common Table Expressions)** and **Recursive CTEs**
* Create and manage **Views, Temporary Tables, and CTAS tables**
* Implement **Stored Procedures with parameters and error handling**
* Create **Triggers for audit logging**
* Optimize query performance using **Indexes and Execution Plans**

---

## 🗄️ Databases Used

The scripts assume the existence of the following databases:

* **MyDatabase** – used for introductory and core SQL examples
* **SalesDB** – used extensively for advanced joins, analytics, reporting, and optimization
* **AdventureWorksDW2022** – used for performance and execution plan demonstrations

---

## 📂 Topics Covered

### 1️⃣ Data Retrieval (SELECT)

* Selecting all and specific columns
* Sorting results using `ORDER BY`
* Filtering data using `WHERE`
* Using `TOP` and `DISTINCT`

### 2️⃣ Filtering Data

* Comparison operators (`=`, `!=`, `>`, `<`, `>=`, `<=`)
* Logical operators (`AND`, `OR`, `NOT`)
* Range filtering using `BETWEEN`
* Membership filtering using `IN` and `NOT IN`
* Pattern matching using `LIKE`

### 3️⃣ Aggregation & Grouping

* `COUNT`, `SUM`, `AVG`, `MIN`, `MAX`
* `GROUP BY` with `HAVING`
* Conditional aggregation

### 4️⃣ Joins & Advanced Joins

* `INNER JOIN`
* `LEFT JOIN`
* `RIGHT JOIN`
* `FULL JOIN`
* Anti Joins (LEFT & FULL ANTI JOIN)
* `CROSS JOIN`

### 5️⃣ Set Operators

* `UNION`
* `UNION ALL`
* `EXCEPT`
* `INTERSECT`

### 6️⃣ SQL Functions

#### 🔹 String Functions

* `CONCAT`, `LOWER`, `UPPER`
* `TRIM`, `LEN`, `LEFT`, `RIGHT`, `SUBSTRING`
* `REPLACE`

#### 🔹 Numeric Functions

* `ROUND`, `ABS`

#### 🔹 Date & Time Functions

* `GETDATE`, `YEAR`, `MONTH`, `DAY`
* `DATEPART`, `DATENAME`, `DATETRUNC`
* `EOMONTH`, `DATEADD`, `DATEDIFF`
* `FORMAT`, `CAST`, `CONVERT`, `ISDATE`

### 7️⃣ NULL Handling

* `IS NULL` / `IS NOT NULL`
* `ISNULL`
* `COALESCE`
* `NULLIF`

### 8️⃣ CASE Statements

* Conditional data transformation
* Categorization and reporting
* Dynamic column creation

### 9️⃣ Window Functions

* `OVER()` clause
* `PARTITION BY`
* Ranking functions (`RANK()`)
* Running totals

### 🔟 Common Table Expressions (CTEs)

#### Non-Recursive CTEs

* Standalone CTEs
* Nested CTEs

#### Recursive CTEs

* Generating sequences
* Employee hierarchy modeling

### 1️⃣1️⃣ Views

* Creating and querying views
* Updating views using DROP & CREATE
* Using views to:

  * Hide query complexity
  * Protect sensitive data

### 1️⃣2️⃣ CTAS & Temporary Tables

* `CREATE TABLE AS SELECT (CTAS)`
* Refreshing CTAS tables
* Temporary tables using `#TableName`

### 1️⃣3️⃣ Stored Procedures

* Creating stored procedures
* Parameterized procedures
* Control flow (`IF`, `ELSE`)
* Error handling (`TRY...CATCH`)
* Reporting and logging logic

### 1️⃣4️⃣ Triggers

* DML Triggers (`AFTER INSERT`)
* Audit logging using triggers
* Using `INSERTED` virtual table

### 1️⃣5️⃣ Performance Optimization

#### Indexes

* Clustered Indexes
* Non-Clustered Indexes
* Composite Indexes
* Columnstore Indexes
* Unique Indexes

#### Index Monitoring

* Index usage statistics
* Missing index analysis
* Fragmentation awareness

#### Execution Plans

* Understanding query execution flow
* Heap vs Indexed tables

---

## 🛠️ Technologies & Tools

* **Microsoft SQL Server**
* **T-SQL (Transact-SQL)**
* **SQL Server Management Studio (SSMS)**

---

## 👤 Intended Audience

This repository is suitable for:

* SQL Developers
* Backend Developers
* Data Analysts
* BI Developers
* Students learning **Advanced SQL**

---

## 🚀 How to Use This Repository

1. Clone the repository
2. Open SQL Server Management Studio (SSMS)
3. Execute scripts section by section
4. Review results and execution plans
5. Modify queries to deepen understanding

---

## 📈 Skill Level

**Intermediate → Advanced**

A basic understanding of SQL is recommended before using this repository.

---

## 📜 License

This project is for **educational and learning purposes**.

---

## ✨ Author

**Brian Bosire Evans**
Advanced SQL Developer & Software Engineer

---

Happy querying 🚀
