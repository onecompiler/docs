# MariaDB online editor
Write, Run & Share MariaDB queries online using OneCompiler's MariaDB online editor and compiler for free. It's one of the robust, feature-rich online editor and compiler for MariaDB. Getting started with the OneCompiler's MariaDB editor is really simple and pretty fast. The editor shows sample boilerplate code when you choose database as 'MariaDB' and start writing queries to learn and test online without worrying about tedious process of installation.

# About MariaDB

MariaDB is a community developed, open source relational database management system. 

### Key Features

* Development was led by few of the original developers of MySQL
* It's an improved version of MySQL with numerous inbuilt powerful features,security, performance improvements compared to MySQL.
* High compatibility with MySQL and thus it has exact matching with MySQL APIs and commands with new features. 
* New storage engine, Aria
* MariaDB has been supported in Amazon RDS service and Microsoft Azure.
* Intended to remain free and open source software under GPL, BSD or LGPL licenses.
* Supports different programming languages and runs on different operating systems.

# Syntax help

## 1. CREATE
CREATE command is used to create a table, schema or an index.
#### Syntax:
```sql
         CREATE TABLE table_name (
                column1 datatype,
                column2 datatype,
                ....);
``` 
## 2. ALTER
 ALTER command is used to add, modify or delete columns or constraints from the database table.
        
#### Syntax
```sql 
ALTER TABLE Table_name ADD column_name datatype;
```
## 3. TRUNCATE: 
 TRUNCATE command is used to delete the data present in the table but this will not delete the table.
#### Syntax
```sql
TRUNCATE table table_name;
```
## 4. DROP
DROP command is used to delete the table along with its data.

#### Syntax
```sql 
DROP TABLE table_name;
```
## 5. RENAME
RENAME command is used to rename the table name.

#### Syntax
```sql
ALTER TABLE table_name1 RENAME to new_table_name1; 
```

## 6. INSERT
INSERT Statement  is used to insert new records into the database table.
#### Syntax
```sql
INSERT INTO table_name (column1, column2, column3, ...) VALUES (value1, value2, value3, ...);
```

## 7. SELECT
Select statement is used to select data from database tables.

####   Syntax:
```sql
SELECT column1, column2, ...
FROM table_name; 
```   
## 8. UPDATE
UPDATE statement is used to modify the existing values of records present in the database table.

#### Syntax
```sql
UPDATE table_name
SET column1 = value1, column2 = value2, ...
WHERE condition; 
```
## 9. DELETE
DELETE statement is used to delete the existing records present in the database table.

#### Syntax
```sql 
DELETE FROM table_name where condition;
```
