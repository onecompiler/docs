# C online compiler
OneCompiler's C online compiler is one of the robust, feature-rich online compilers for C language, running the latest C version which is C18. Users can write, run and share the code online and can track all the code history. Getting started with the OneCompiler's C editor is really simple and pretty fast. The editor shows sample boilerplate code when you choose language as 'C' and you can also choose hundreds of reference programs to get started. OneCompiler also has reference programs, where you can look for the sample code and start learning.

## Taking inputs (stdin)
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

## About C

C language is one of the most popular general-purpose programming language developed by Dennis Ritchie at Bell laboratories for UNIX operating system.

It's one of the simple and flexible programming language and infact almost all of us would have started our programming language's language with C.

### Key Features

* Structured Programming
* popular system programming language
* UNIX, MySQL are completely written in C.
* supports variety of platforms
* efficient and also handle low-level activities.
* As fast as assembly language and hence used as system development language.

## Loops

### IF-ELSE

When ever you want to perform a set of operations based on a condition IF-ELSE is used.

```c
if(conditional-expression)
{
    //code
}
else
{
    //code
}
```

You can also use if-else for nested IFs and IF-ELSE-IF ladder when multiple conditions are to be performed on a single variable.

### SWITCH

Switch is an alternative to IF-ELSE-IF ladder.

```c
switch(conditional-expression){    
case value1:    
 //code    
 break;  //optional  
case value2:    
 //code    
 break;  //optional  
...    
    
default:     
 code to be executed when all the above cases are not matched;    
} 
```
### FOR

For loop is used to iterate a set of statements based on a condition.

```c
for(Initialization; Condition; Increment/decrement){  
//code  
} 
```
### WHILE

While is also used to iterate a set of statements based on a condition. Usually while is preferred when number of ierations is not known in advance.

```c
while(condition){  
//code 
}  
```
### DO-WHILE
Do-while is also used to iterate a set of statements based on a condition. It is mostly used when you need to execute the statements atleast once.

```c
do{  
//code 
}while(condition); 
```

## Arrays

Array is a collection of similar data which is stored in continuous memory addresses. Array values can be fetched using index. 

Index starts from 0 to size-1.

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

Functions is a sub-routine which contains set of statements. Usually functions are written when multiple calls are required to same set of statements which increases re-usuability and modularity.

Two types of functions are present in C

1. Library Functions

Library functions are the in-built functions which are declared in header files like printf(),scanf(),puts(),gets() etc.,

2. User defined functions

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

return_type function_name(parameters){  
//code
}

For more detailed C concepts checkout our beginner's tutorial. 
