# MySQL online editor
Write, Run & Share MySQL queries online using OneCompiler's MySQL online editor and compiler for free. It's one of the robust, feature-rich online editor and compiler for MySQL. Getting started with the OneCompiler's MySQL editor is really simple and pretty fast. The editor shows sample boilerplate code when you choose language as 'MySQL' and start writing queries to learn and test online without worrying about tedious process of installation.

# About MySQL

MySQL is a open-source, free and very popular relational database management system which is developed, distributed and supported by Oracle corporation. 

### Key Features:

*	Open-source relational database management systems.
*	Reliable, very fast and easy to use database server.
*	Works on client-server model.
*	Highly Secure and Scalable
*	High Performance
*	High productivity as it uses stored procedures, triggers, views to write a highly productive code.
*	Supports large databases efficiently.
*	Supports many operating systems like Linux*,CentOS*, Solaris*,Ubuntu*,Windows*, MacOS*,FreeBSD* and others. 

# Syntax help

## Commands

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
### 3. TRUNCATE
```sql
TRUNCATE table table_name;
```
### 4. DROP
```sql 
DROP TABLE table_name;
```
### 5. RENAME 
```sql
RENAME TABLE table_name1 to new_table_name1; 
```
### 6. COMMENT

###  Single-Line Comments: 
 ```sql
  --Line1;
  ```
###   Multi-Line comments: 
 ```sql
    /* Line1,
    Line2 */
```

## DML Commands

### 1. INSERT  
```sql
INSERT INTO table_name (column1, column2, column3, ...) VALUES (value1, value2, value3, ...);
```
Note: Column names are optional.

### Example
```sql
INSERT INTO EMPLOYEE VALUES (0001, 'Ava', 'Sales');
```
### 2. SELECT 

```sql
SELECT column1, column2, ...
FROM table_name
[where condition]; 
```

### Example
```sql
SELECT * FROM EMPLOYEE where dept ='sales';
```
### 3. UPDATE 

```sql
UPDATE table_name
SET column1 = value1, column2 = value2, ...
WHERE condition; 
```
### Example
```sql
UPDATE EMPLOYEE SET dept = 'Sales' WHERE empId='0001'; 
```
### 4. DELETE 

```sql 
DELETE FROM table_name where condition;
```
### Example
```sql
DELETE from EMPLOYEE where empId='0001'; 
```

## Indexes

### 1. CREATE INDEX

```sql
  CREATE INDEX index_name on table_name(column_name);
```
* To Create Unique index:

```sql
  CREATE UNIQUE INDEX index_name on table_name(column_name);
```
### 2. DROP INDEX

```sql
DROP INDEX index_name ON table_name;
```
## Views

### 1. Create a View
```sql
Creating a View:
CREATE VIEW View_name AS 
Query;
```

### 2. How to call view
```sql
SELECT * FROM View_name;
```
### 3. Altering a View
```sql
ALTER View View_name AS 
Query;
```
### 4. Deleting a View
```sql
DROP VIEW View_name;
```

## Triggers

### 1. Create a Trigger

```sql
CREATE TRIGGER trigger_name trigger_time trigger_event
    ON tbl_name FOR EACH ROW [trigger_order] trigger_body
/* where
trigger_time: { BEFORE | AFTER }
trigger_event: { INSERT | UPDATE | DELETE }
trigger_order: { FOLLOWS | PRECEDES } */
```

### 2. Drop a Trigger

```sql
DROP TRIGGER [IF EXISTS] trigger_name;
```
## Stored Procedures

### 1. Create a Stored Procedure

```sql
CREATE PROCEDURE sp_name(p1 datatype)
BEGIN
/*Stored procedure code*/
END;
```
### 2. How to call Stored procedure

```sql
CALL sp_name;
```
### 3. How to delete stored procedure
```sql
DROP PROCEDURE sp_name;
```

## Joins

### 1. INNER JOIN
```sql
SELECT * FROM TABLE1 INNER JOIN TABLE2 where condition;
```
### 2. LEFT JOIN
```sql
SELECT * FROM TABLE1 LEFT JOIN TABLE2 ON condition;
```
### 3. RIGHT JOIN

```sql
SELECT * FROM TABLE1 RIGHT JOIN TABLE2 ON condition;
```
### 4. CROSS JOIN

```sql
SELECT select_list from TABLE1 CROSS JOIN TABLE2;
```

