# 🧠 SQL Portfolio

This repository contains SQL solutions to real-world analytical problems from platforms like [StrataScratch](https://stratascratch.com) and others.

## 🗂 Folder Structure

- `easy/` – Beginner level questions
- `medium/` – Intermediate level
- `advanced/` – Complex analytical problems (future)
- `notes/` – SQL concepts and cheat sheets (future)

## 🚀 Topics Covered

- Window Functions
- JOINS and Aggregations
- CTEs
- Subqueries
- Data Cleaning with SQL
- Real Business Use Cases

## 🔗 Sample Solution

```sql
-- Finding duplicate emails
SELECT email
FROM users
GROUP BY email
HAVING COUNT(email) > 1;

