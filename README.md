Exercise 6 - Advanced SQL (NULL FUNCTIONS)

**Objective**  
Learn to handle NULL values effectively to produce clean, reliable query results and avoid common pitfalls.

**Key Concepts Demonstrated**
- `COALESCE()` – returns first non-NULL value
- `ISNULL()` (SQL Server) / `IFNULL()` (MySQL)
- `NULLIF()` – converts a value to NULL
- `CASE` statements for custom NULL handling
- Behavior of NULL in aggregates (`COUNT`, `SUM`, etc.)
- NULL-safe comparisons and concatenations

**Main Tasks**
- Display 'Unknown' or 'N/A' instead of NULL for missing values (phone, email, address)
- Safely calculate totals when some 
