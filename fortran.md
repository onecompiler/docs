# Fortran Online Compiler

Write, Run & Share Fortran code online using OneCompiler's Fortran online compiler for free. It's one of the robust, feature-rich online compilers for Fortran language, running on the latest version 7. Getting started with the OneCompiler's Fortran compiler is simple and pretty fast. The editor shows sample boilerplate code when you choose language as `Fortran` and start coding. 

# Read inputs from stdin

OneCompiler's Fortran online editor supports stdin and users can give inputs to programs using the STDIN textbox under the I/O tab. Following is a sample Fortran program which takes name as input and prints hello message with your name.

```fortran
program hello
  character :: name*30
  read *, name
	print *, "Hello ", name
end program hello
```

# About Fortran

Fortran language was initially developed for scientific calculations by IBM in 1957. It has a number of in-built functions to perform mathematical calculations and is ideal for applications which has more mathematical calculations. 

# Syntax help

## Data Types

|Data type|Description|Usage|
|-----|-----|-----|
|Integer|To store integer variables|integer :: x|
|Real|To store float values|real :: x|
|Complex|To store complex numbers|complex :: x,y|
|Logical|To store boolean values True or false|logical :: x=.True. , logical :: x = .FALSE.|
|Character|To store characters and strings|character :: x|

## Variables

Variable is a name given to the storage area in order to manipulate them in our programs.

```
data type :: variable_name
```

## Arrays

Array is a collection of similar data which is stored in continuous memory addresses.

### Syntax

```fortran
data-type, dimension (x,y) :: array-name
```

### Example
```fortran
integer, dimension(3,3) :: cube
```


## Loops

### 1. Do:

Do is used to execute a set of statement(s) iteratively when a given condition is true and the loop variable must be an integer.

```fortran
do i = start, stop [,step]    
   ! code
end do
```

### 2. Do-While:

Do-While is used to execute a set of statement(s) iteratively  when a given condition is true.

```fortran
do while (condition) 
   !Code
end do
```

### 3. If:

If is used to execute a set of statements based on a condition.

```fortran
if (logical-expression) then      
   !Code  
end if
```

### 4. If-Else:

If is used to execute a set of statements based on a condition and execute another set of statements present in else block, if condition specified in If block fails.

```fortran
if (logical-expression) then     
   !code when the condition is true
else
   !code when the condition fails
end if
```

### 5. Case:

Case is similar to switch in C language. 

```fortran
[name:] select case (regular-expression) 
   case (value1)          
   ! code for value 1          
   ... case (value2)           
   ! code for value 2           
   ...       
   case default          
   ! default code          
   ...   
end select [name]
```
