# SQLite online editor
Write, Run & Share SQLite queries online using OneCompiler's SQLite online editor and compiler for free. It's one of the robust, feature-rich online editor and compiler for SQLite. Getting started with the OneCompiler's SQLite editor is really simple and pretty fast. The editor shows sample boilerplate code when you choose language as 'SQLite' and start writing queries to learn and test online without worrying about tedious process of installation.

# About SQLite

SQLite is an in-process C library that implements small, fast, serverless, zero-configuration, transactional SQL database engine.

### Key Features:

* Very small and light weight
* Serverless
* Free to use
* Self contained as no other dependencies required.
* zero config

# Syntax help

## Useful Commands

### 1. CREATE 

```sql
CREATE TABLE table_name (
                column1 datatype,
                column2 datatype,
                ....);
``` 

### Example
```sql
CREATE TABLE EMPLOYEE (
  empId INTEGER PRIMARY KEY,
  name TEXT NOT NULL,
  dept TEXT NOT NULL
);
```
### 2. ALTER
```sql 
ALTER TABLE Table_name ADD column_name datatype;
```

### Example
```sql
INSERT INTO EMPLOYEE VALUES (0001, 'Dave', 'Sales');
```
### 3. DROP
```sql 
DROP TABLE table_name;
```
### 4. INSERT  
```sql
INSERT INTO table_name (column1, column2, column3, ...) VALUES (value1, value2, value3, ...);
```
Note: Column names are optional.

### Example
```sql
INSERT INTO EMPLOYEE VALUES (0001, 'Ava', 'Sales');
```
### 5. SELECT 

```sql
SELECT column1, column2, ...
FROM table_name
[where condition]; 
```

### Example
```sql
SELECT * FROM EMPLOYEE where dept ='sales';
```
### 6. UPDATE 

```sql
UPDATE table_name
SET column1 = value1, column2 = value2, ...
WHERE condition; 
```
### Example
```sql
UPDATE EMPLOYEE SET dept = 'Sales' WHERE empId='0001'; 
```
### 7. DELETE 

```sql 
DELETE FROM table_name where condition;
```
### Example
```sql
DELETE from EMPLOYEE where empId='0001'; 
```

### 8. CREATE INDEX

```sql
  CREATE [UNIQUE] INDEX index_name on table_name(column_name);
```
### 9. DROP INDEX

```sql
DROP INDEX index_name ON table_name;
```

### 10. Create a View
```sql
CREATE VIEW View_name AS 
Query;
```

### 11. How to call view
```sql
SELECT * FROM View_name;
```
### 12. Altering a View
```sql
ALTER View View_name AS 
Query;
```
### 13. Deleting a View
```sql
DROP VIEW View_name;
```

### 14. INNER JOIN
```sql
SELECT * FROM TABLE1 INNER JOIN TABLE2 where condition;
```
### 15. LEFT JOIN
```sql
SELECT * FROM TABLE1 LEFT JOIN TABLE2 ON condition;
```
### 16. RIGHT JOIN

```sql
SELECT * FROM TABLE1 RIGHT JOIN TABLE2 ON condition;
```
### 17. CROSS JOIN

```sql
SELECT select_list from TABLE1 CROSS JOIN TABLE2;
```

