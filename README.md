# 📊 SQL Practice for Data Analyst Role

Hi! I'm currently learning and building my skills to become a **Data Analyst**. This repository includes a collection of practical SQL queries I've written as part of my learning journey. The queries work on a sample `EMPLOYEES` database and cover important concepts like filtering, sorting, grouping, and aggregation — all essential skills for data analysis.

---

## 🧠 What This Project Covers

These queries demonstrate how to:
- Use `SELECT`, `WHERE`, `LIKE`, `BETWEEN`, and logical conditions
- Apply `GROUP BY` and `HAVING` for aggregation
- Sort and filter records efficiently
- Explore string pattern matching with `LIKE`
- Calculate counts and averages across groups

---

## 🗃️ Sample Table: EMPLOYEES

| Column Name | Description              |
|-------------|--------------------------|
| EMP_ID      | Employee ID              |
| F_NAME      | First Name               |
| L_NAME      | Last Name                |
| ADDRESS     | Full Address             |
| B_DATE      | Date of Birth (YYYY-MM-DD) |
| SALARY      | Annual Salary            |
| DEP_ID      | Department ID            |

---

## 📝 SQL Queries

### 1. Employees living in Elgin, IL
```sql
SELECT F_NAME, L_NAME
FROM EMPLOYEES
WHERE ADDRESS LIKE '%Elgin,IL%';
