# 🗄️ SQL Practice Questions & Solutions

A collection of common SQL interview questions and solutions for Data Analyst roles. This repository covers essential SQL concepts with practical examples.

---

## 📚 Database Schema

### Customer Table

| Column   | Type     | Description           |
|----------|----------|-----------------------|
| EMPID    | INT      | Primary Key           |
| NAME     | VARCHAR  | Customer name         |
| CITY     | VARCHAR  | Customer city         |
| PRODUCT  | VARCHAR  | Product purchased     |
| PRICE    | INT      | Product price         |
| REGION   | VARCHAR  | Region (Country)      |
| CATEGORY | VARCHAR  | Product category      |

### Orders Table

| Column   | Type     | Description           |
|----------|----------|-----------------------|
| ORDERID  | INT      | Order ID              |
| EMPID    | INT      | Foreign Key → Customer|
| AMOUNT   | INT      | Order amount          |

---

## 📋 Topics Covered

| Category | Concepts |
|----------|----------|
| **Basic Queries** | SELECT, WHERE, DISTINCT, LIKE, COUNT |
| **Aggregation** | SUM, AVG, MAX, MIN, ROUND |
| **Grouping** | GROUP BY, HAVING, ORDER BY |
| **Joins** | LEFT JOIN, INNER JOIN, Foreign Keys |
| **Subqueries** | Nested SELECT, Comparison Operators |

---

## 🔍 Sample Queries

### Basic Query
```sql
-- Find customers from Delhi
SELECT * FROM CUSTOMER WHERE CITY = 'DELHI';
