# 🇺🇸 Revising the Select Query I

Query all columns for **all American cities** in the `CITY` table with **populations larger than 100000**.

---

## 🗂️ Table: CITY

The `CITY` table is described as follows:

| Field         | Type         |
|---------------|--------------|
| ID            | Number       |
| NAME          | VARCHAR2(17) |
| COUNTRYCODE   | VARCHAR2(3)  |
| DISTRICT      | VARCHAR2(20) |
| POPULATION    | Number       |

- **COUNTRYCODE** for America is `'USA'`.

---

## 🧪 Sample Query

```sql
SELECT * FROM CITY WHERE COUNTRYCODE = 'USA'  AND POPULATION > 100000;
```