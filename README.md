# SQL Projects - Kaggle Certification

This repository contains my SQL projects from Kaggle, including both introductory and advanced SQL.

## 📊 Skills Covered:
- SQL Joins (INNER, LEFT, RIGHT)
- Window Functions (ROW_NUMBER, RANK)
- CTE (Common Table Expressions)
- Aggregations & Subqueries

## 📘 Example Query:
```sql
-- Find top 5 customers by total spend
SELECT customer_id, SUM(amount) AS total_spent
FROM transactions
GROUP BY customer_id
ORDER BY total_spent DESC
LIMIT 5;
