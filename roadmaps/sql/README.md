# 🗄️ SQL Learning Roadmap

> **Goal:** Take you from zero SQL knowledge to writing complex queries, designing efficient databases, and optimising performance for production systems.

---

## 📌 Overview

| Stage | Topics | Estimated Time |
|---|---|---|
| 🟢 Beginner | SQL basics, CRUD, filtering, sorting | 3–4 weeks |
| 🟡 Intermediate | JOINs, subqueries, indexes, views, transactions | 5–7 weeks |
| 🔴 Advanced | Window functions, CTEs, query optimisation, database design | 6–10 weeks |

---

## 🟢 Stage 1 — Beginner

**Goal:** Understand relational databases and write basic queries to retrieve and modify data.

### Topics to Learn:
- ✅ What is a relational database? Tables, rows, columns, keys
- ✅ Setting up a database (MySQL, PostgreSQL, or SQLite)
- ✅ `SELECT` — retrieving data, choosing columns
- ✅ `WHERE` — filtering rows with conditions (`=`, `!=`, `>`, `<`, `BETWEEN`, `IN`, `LIKE`)
- ✅ `ORDER BY` and `LIMIT` — sorting and paginating results
- ✅ `INSERT INTO`, `UPDATE`, `DELETE` — adding and modifying data
- ✅ SQL data types (`INT`, `VARCHAR`, `TEXT`, `DATE`, `BOOLEAN`, `DECIMAL`)
- ✅ `NULL` values and `IS NULL` / `IS NOT NULL`
- ✅ Aggregate functions: `COUNT`, `SUM`, `AVG`, `MIN`, `MAX`
- ✅ `GROUP BY` and `HAVING`

### 🛠️ Beginner Projects:
- 🔹 Build a library database — store books, authors, and borrowers, then query the collection
- 🔹 Student grade tracker — insert student records and calculate class averages
- 🔹 Simple inventory system — track products, quantities, and prices

---

## 🟡 Stage 2 — Intermediate

**Goal:** Write multi-table queries, ensure data integrity, and improve performance with indexes and views.

### Topics to Learn:
- ✅ Primary keys, foreign keys, and referential integrity
- ✅ `JOIN` types: `INNER JOIN`, `LEFT JOIN`, `RIGHT JOIN`, `FULL OUTER JOIN`, `CROSS JOIN`
- ✅ Self-joins and multiple joins in a single query
- ✅ Subqueries (correlated and non-correlated)
- ✅ `EXISTS` and `NOT EXISTS`
- ✅ `UNION`, `UNION ALL`, `INTERSECT`, `EXCEPT`
- ✅ Views — creating and using virtual tables
- ✅ Indexes — creating, types (B-tree, hash), and understanding when to use them
- ✅ Transactions (`BEGIN`, `COMMIT`, `ROLLBACK`, ACID properties)
- ✅ Stored procedures and functions (basic)

### 🛠️ Intermediate Projects:
- 🔸 E-commerce database — customers, orders, products, and order items with full JOIN queries
- 🔸 HR management system — employees, departments, managers, and payroll with multi-table reports
- 🔸 Blog platform schema — users, posts, comments, tags, and category filters

---

## 🔴 Stage 3 — Advanced

**Goal:** Design optimal schemas, write sophisticated analytical queries, and tune databases for high performance.

### Topics to Learn:
- ✅ Window functions: `ROW_NUMBER`, `RANK`, `DENSE_RANK`, `LAG`, `LEAD`, `NTILE`, `PARTITION BY`
- ✅ Common Table Expressions (CTEs) — `WITH` clause and recursive CTEs
- ✅ Query execution plans (`EXPLAIN` / `EXPLAIN ANALYZE`)
- ✅ Query optimisation techniques — avoiding full table scans, index tuning
- ✅ Database normalisation (1NF, 2NF, 3NF, BCNF) and denormalisation trade-offs
- ✅ Triggers and event scheduling
- ✅ Partitioning and sharding concepts
- ✅ Full-text search
- ✅ JSON / semi-structured data in SQL (PostgreSQL `jsonb`, MySQL JSON)
- ✅ Replication and backup strategies

### 🛠️ Advanced Projects:
- 🔺 Analytics dashboard backend — use window functions to calculate running totals, rankings, and period-over-period comparisons
- 🔺 Social network schema — users, follows, posts, likes, and recursive CTEs for friend-of-friend queries
- 🔺 Performance tuning challenge — take a slow query, analyse the execution plan, add indexes, and measure the improvement

---

## ⏱️ Estimated Time

| Stage | Duration |
|---|---|
| Beginner | 3–4 weeks (1–2 hrs/day) |
| Intermediate | 5–7 weeks (1–2 hrs/day) |
| Advanced | 6–10 weeks (2–3 hrs/day) |
| **Total** | **~4 months** |

---

## 📚 Resources

### Free Resources:
- 🔗 [SQLZoo](https://sqlzoo.net/) — Interactive SQL exercises with instant feedback, great for beginners.
- 🔗 [SQLBolt](https://sqlbolt.com/) — Step-by-step interactive lessons covering all core SQL concepts.
- 🔗 [Mode SQL Tutorial](https://mode.com/sql-tutorial/) — Practical SQL for data analysis, free and browser-based.
- 🔗 [PostgreSQL Official Docs](https://www.postgresql.org/docs/) — The definitive reference for PostgreSQL.
- 🔗 [W3Schools SQL](https://www.w3schools.com/sql/) — Quick reference and try-it-yourself editor for SQL syntax.
- 🔗 [CS50's Introduction to Databases with SQL](https://cs50.harvard.edu/sql/) — Harvard's free SQL course.

### Books:
- 📖 *Learning SQL* — Alan Beaulieu — Best beginner book; clear and practical.
- 📖 *SQL Cookbook* — Anthony Molinaro & Robert de Graaf — Solutions to common SQL problems for all levels.
- 📖 *SQL Performance Explained* — Markus Winand — Essential guide to indexing and query optimisation.
- 📖 *Database Design for Mere Mortals* — Michael J. Hernandez — Accessible guide to relational database design.

### Practice:
- 🏋️ [LeetCode Database](https://leetcode.com/problemset/database/) — SQL interview problems at all difficulty levels.
- 🏋️ [HackerRank SQL](https://www.hackerrank.com/domains/sql) — Structured SQL challenges from basic to advanced.
- 🏋️ [StrataScratch](https://www.stratascratch.com/) — Real interview SQL questions from top tech companies.
- 🏋️ [DataLemur](https://datalemur.com/) — SQL and data science interview prep with explanations.

---

## 🔮 What's Next?

- 🏗️ Deepen your backend skills with the [System Design Roadmap](../system-design/README.md)
- 🐍 Use SQL with Python via the [Python Roadmap](../python/README.md)
- 🤖 Apply SQL to data pipelines with the [AI/ML Roadmap](../ai-ml/README.md)

---

[⬅️ Back to Main README](../../README.md)
