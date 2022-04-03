# Ada online compiler

Write, Run & Share Ada code online using OneCompiler's Ada online compiler for free. It's one of the robust, feature-rich online compilers for Ada language, running the latest Ada version 2012. Getting started with the OneCompiler's Ada editor is easy and fast. The editor shows sample boilerplate code when you choose language as Ada and start coding. 

# Read inputs from stdin

OneCompiler's Ada online editor supports stdin and users can give inputs to programs using the STDIN textbox under the I/O tab. Following is a sample Ada program which takes name as input and prints hello message with your name.

```ada
with Ada.Text_IO; use Ada.Text_IO;
procedure Hello is
begin
  declare
  name : String := Ada.Text_IO.Get_Line;
  begin
  Ada.Text_IO.Put ("Hello ");
  Ada.Text_IO.Put_Line (name);
	end;
end Hello;
```
# About Ada

Ada is suitable for all development needs and it is extremely good for developing very large applications with built-in features which supports structured, object-oriented, generic, distributed and concurrent programming directly. Ada was designed by Jean Ichbiah.

It's a Good choice for Rapid Application Development, Extreme Programming. It is a very strong and statically typed language.


# Syntax help
## Loops
### 1. Infinite loop:

This is the simplest loop

```ada
begin
   Index := 1; --initialization
    loop                            
     --code
	exit when Index = n;
	end loop;
```
### 2. while loop

While is also used to iterate a set of statements based on a condition. Usually while is preferred when number of iterations are not known in advance.

```ada
   Count := 1;    --initialization
   while Count < n loop  
   --code
   end loop;
```

### 3. for loop
For loop is used to iterate a set of statements based on a condition. Usually for loop is preferred when number of iterations are known in advance.

```ada
for Index in 1..n loop          
--code
end loop;
```
## Sub programs

Ada distinguishes functions and procedures. In simpler terms, functions return some value and must be called as part of larger expressions. Procedures never return a value.

Functions and procedures are collectively called as sub-programs.

### Syntax for procedure

```ada
procedure proc-name
(X : in Integer ; Y : out Integer ; Z : in out Integer ) is
begin
X := 10; −− it's an Error as you can’t modify an in parameter.
Y := X; −− can modify Y as it's an out parameter.
Z := Z + 1; −− can read and write as it's an in out parameter.
end proc-name;
```
### Syntax for functions

```ada
function function_name(declaration) return value is
begin
--code
end function-name;
```