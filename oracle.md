# Oracle Online Compiler

Write, Run & Share Oracle queries online using OneCompiler's Oracle online editor and compiler for free. It's one of the robust, feature-rich online editor and compiler for Oracle running on latest version 23c (23.3.0.0). Getting started with the OneCompiler's Oracle editor is really simple and pretty fast. The editor shows sample boilerplate code when you choose language as 'Oracle' and start writing queries to learn and test online without worrying about tedious process of installation.

# About Oracle

Oracle Database is world's most popular database built by Oracle Corporation. It is a multi-model database management system. It's known for its robustness, scalability, and comprehensive feature set, making it popular for enterprise-level applications and large-scale data management.

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
  empId NUMBER PRIMARY KEY,
  name VARCHAR2(15) NOT NULL,
  dept VARCHAR2(10) NOT NULL
);
```
### 2. Add Data

### Example

```sql
INSERT INTO EMPLOYEE VALUES (1, 'Dave', 'Sales');
```

### 3. TRUNCATE

```sql
TRUNCATE table table_name;
```

### 4. DROP
```sql 
DROP TABLE table_name;
```

### 6. COMMENTS

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
INSERT INTO EMPLOYEE VALUES (1, 'Ava', 'Sales');
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
