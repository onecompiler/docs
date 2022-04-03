# C Language online compiler
Write, Run & Share C Language code online using OneCompiler's C online compiler for free. It's one of the robust, feature-rich online compilers for C language, running the latest C version which is C18. Getting started with the OneCompiler's C editor is really simple and pretty fast. The editor shows sample boilerplate code when you choose language as 'C' and start coding!

# Read inputs from stdin
OneCompiler's C online editor supports stdin and users can give inputs to programs using the STDIN textbox under the I/O tab. Following is a sample C program which takes name as input and print your name with hello.

```c
#include <stdio.h>
int main()
{
    char name[50];
    printf("Enter name:");
    scanf("%s", &name);
    printf("Hello %s" , name );
    return 0;
    
}
```

# About C

C language is one of the most popular general-purpose programming language developed by Dennis Ritchie at Bell laboratories for UNIX operating system. The initial release of C Language was in the year 1972. Most of the desktop operating systems are written in C Language. 

### Key features:

* Structured Programming
* Popular system programming language
* UNIX, MySQL and Oracle are completely written in C.
* Supports variety of platforms
* Efficient and also handle low-level activities.
* As fast as assembly language and hence used as system development language.

# Syntax help

## Loops

### 1. If-Else:

When ever you want to perform a set of operations based on a condition `if-else` is used.

```c
if(conditional-expression) {
   // code
} else {
   // code
}
```

You can also use if-else for nested Ifs and if-else-if ladder when multiple conditions are to be performed on a single variable.

### 2. Switch:

Switch is an alternative to if-else-if ladder.

```c
switch(conditional-expression) {    
case value1:    
 // code    
 break;  // optional  
case value2:    
 // code    
 break;  // optional  
...    
    
default:     
 // code to be executed when all the above cases are not matched;    
} 
```
### 3. For:

For loop is used to iterate a set of statements based on a condition.

```c
for(Initialization; Condition; Increment/decrement){  
  // code  
} 
```
### 4. While:

While is also used to iterate a set of statements based on a condition. Usually while is preferred when number of iterations are not known in advance.

```c
while(condition) {  
 // code 
}  
```
### 5. Do-While:
Do-while is also used to iterate a set of statements based on a condition. It is mostly used when you need to execute the statements atleast once.

```c
do {
  // code 
} while (condition); 
```

## Arrays

Array is a collection of similar data which is stored in continuous memory addresses. Array values can be fetched using index.  Index starts from 0 to size-1.

### Syntax

### One dimentional Array:

```c
data-type array-name[size];
```

### Two dimensional array:
```c
data-type array-name[size][size];
```
## Functions

Function is a sub-routine which contains set of statements. Usually functions are written when multiple calls are required to same set of statements which increases re-usuability and modularity.

Two types of functions are present in C

1. Library Functions:

Library functions are the in-built functions which are declared in header files like printf(),scanf(),puts(),gets() etc.,

2. User defined functions:

User defined functions are the ones which are written by the programmer based on the requirement.

## How to declare a Function

```c
return_type function_name(parameters);
```

## How to call a Function

```c
function_name (parameters)
```
## How to define a Function

```c
return_type function_name(parameters) {  
  //code
}
```