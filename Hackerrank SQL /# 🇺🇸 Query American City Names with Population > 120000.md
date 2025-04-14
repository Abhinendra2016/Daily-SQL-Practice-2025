# 🇺🇸 Query American City Names with Population > 120000

Query the `NAME` field for **all American cities** in the `CITY` table with populations **larger than 120000**.

---

## 📋 Problem Description

Given a table named `CITY`, write a query to return the **names** of all cities in **America (CountryCode = 'USA')** where the **population is greater than 120000**.

---

## 🗂️ Table Schema: `CITY`

| Field       | Type         |
|-------------|--------------|
| ID          | NUMBER       |
| NAME        | VARCHAR2(17) |
| COUNTRYCODE | VARCHAR2(3)  |
| DISTRICT    | VARCHAR2(20) |
| POPULATION  | NUMBER       |

---

## 📥 Input Format

All data is stored in a SQL table named `CITY`.

---

## ✅ Output

A list of city `NAME`s in the USA where the population is greater than 120000.

---

## 💡 SQL Query

```sql
SELECT NAME 
FROM CITY 
WHERE COUNTRYCODE = 'USA'
  AND POPULATION > 120000;
```