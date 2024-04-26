# PL/SQL Online Compiler

Write, Run & Share PL/SQL code online using OneCompiler's Oracle PL/SQL online editor and compiler for free. It's one of the robust, feature-rich online editor and compiler for Oracle PL/SQL running on latest version 23c (23.3.0.0). Getting started with the OneCompiler's Oracle PL/SQL editor is really simple and pretty fast. The editor shows sample boilerplate code when you choose language as 'PL/SQL' and start writing code to learn and test online without worrying about tedious process of installation.

# About PL/SQL

PL/SQL is procedural extension for SQL created by Oracle. It is by default embedded into the Oracle Database. PL/SQL program units are compiled and stored inside the Oracle Database which results in optimal execution times as the PL/SQL and SQL run within the same server process.

# Syntax help

Following is the syntax structure for the PL/SQL code blocks

```sql
DECLARE 
   <declarations section> 
BEGIN 
   <executable command(s)>
EXCEPTION 
   <exception handling> 
END;
```

### Example
```sql
DECLARE 
   message  varchar2(100):= 'Hello, World!'; 
BEGIN 
   dbms_output.put_line(message); 
END; 
/
```

## Named procedures 

```sql
CREATE OR REPLACE FUNCTION 
hello_user
   (user_name IN VARCHAR2) 
    RETURN VARCHAR2
IS
BEGIN
   RETURN 'Hello ' || user_name;
END hello_user;
/

BEGIN
   dbms_output.put_line(hello_user('Peter'));
END;
/
```

## Exception handling

```sql
BEGIN
  DBMS_OUTPUT.put_line (1/0);
EXCEPTION
  WHEN OTHERS
  THEN
    DBMS_OUTPUT.put_line ('error is: ' || SQLERRM);
END;
```
