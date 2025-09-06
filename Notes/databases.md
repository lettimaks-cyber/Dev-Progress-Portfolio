# Databases Notes & Cheatsheet

This document contains quick references, tutorials, and examples for SQL and MongoDB.

---

## SQL (Relational Databases)

### 1. Basic Commands

```sql
-- Create a table
CREATE TABLE Users (
    ID INT PRIMARY KEY,
    Name VARCHAR(50),
    Email VARCHAR(100)
);

-- Insert data
INSERT INTO Users (ID, Name, Email)
VALUES (1, 'Lethabo', 'lethabo@example.com');

-- Select data
SELECT * FROM Users;
SELECT Name, Email FROM Users WHERE ID = 1;

-- Update data
UPDATE Users SET Name = 'L. Makola' WHERE ID = 1;

-- Delete data
DELETE FROM Users WHERE ID = 1;
```
