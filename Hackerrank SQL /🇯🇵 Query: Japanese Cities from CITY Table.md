# 🇯🇵 Query: Japanese Cities from CITY Table

## 📝 Problem Statement

You are given a `CITY` table. Write a SQL query to **retrieve all the details** for cities **in Japan**.

The `COUNTRYCODE` for Japan is `'JPN'`.

---

## 🧾 Input Format

The `CITY` table is described as follows:

| Field        | Type         |
|--------------|--------------|
| ID           | NUMBER       |
| NAME         | VARCHAR2(17) |
| COUNTRYCODE  | VARCHAR2(3)  |
| DISTRICT     | VARCHAR2(20) |
| POPULATION   | NUMBER       |

---

## ✅ Sample Query

```sql
SELECT * FROM CITY WHERE COUNTRYCODE = 'JPN';
```