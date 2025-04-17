# 🏙️ SQL Query: Select City by ID

Query all columns for a city in the `CITY` table with the **ID = 1661**.

---

## 📥 Input Format

The `CITY` table is described as follows:

| Field        | Type         |
|--------------|--------------|
| ID           | NUMBER       |
| NAME         | VARCHAR2(17) |
| COUNTRYCODE  | VARCHAR2(3)  |
| DISTRICT     | VARCHAR2(20) |
| POPULATION   | NUMBER       |

---

## ✅ Solution

```sql
SELECT * 
FROM CITY 
WHERE ID = 1661;
