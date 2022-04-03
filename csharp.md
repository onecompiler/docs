# C Sharp Online Compiler

Write, Run & Share C# code online using OneCompiler's C# online compiler for free. It's one of the robust, feature-rich online compilers for C# language, running on the latest version 8.0. Getting started with the OneCompiler's C# compiler is simple and pretty fast. The editor shows sample boilerplate code  when you choose language as `C#` and start coding. 

# Read inputs from stdin
OneCompiler's C# online compiler supports stdin and users can give inputs to programs using the STDIN textbox under the I/O tab. Following is a sample program which takes name as input and print your name with hello.

```c#
using System;
 
namespace Sample
{
  class Test
    {
      public static void Main(string[] args)
       {
         string name;
         name = Console.ReadLine();
         Console.WriteLine("Hello {0} ", name);
	}
     }
}
```

# About C Sharp

C# is a general purpose object-oriented programming language by Microsoft. Though initially it was developed as part of .net but later it was approved by ECMA and ISO standards.

You can use C# to create variety of applications, like web, windows, mobile, console applications and much more using Visual studio.


# Syntax help

## Data types
|Data Type| Description|Range| size|
|----|----|----|----|
|int| To store integers|-2,147,483,648 to 2,147,483,647| 4 bytes|
|double| to store large floating point numbers with decimals|can store 15 decimal digits| 8 bytes|
|float| to store floating point numbers with decimals| can store upto 7 decimal digits| 4 bytes
|char| to store single characters|-| 2 bytes|
|string| to stores text|-| 2 bytes per character|
|bool|  to stores either true or false|-|1 bit|

## Variables

### Syntax
```c#
datatype variable-name = value;
```
## Loops

### 1. If-Else:

When ever you want to perform a set of operations based on a condition or set of few conditions IF-ELSE is used.

```c#
if(conditional-expression) {
   // code
} 
else {
   // code
}
```

You can also use if-else for nested Ifs and If-Else-If ladder when multiple conditions are to be performed on a single variable.

### 2. Switch:

Switch is an alternative to If-Else-If ladder.

```c#
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

```c#
for(Initialization; Condition; Increment/decrement) {
  // code  
} 
```
### 4. While:

While is also used to iterate a set of statements based on a condition. Usually while is preferred when number of iterations are not known in advance.

```c#
while(condition) {
 // code 
}
```
### 5. Do-While:
Do-while is also used to iterate a set of statements based on a condition. It is mostly used when you need to execute the statements atleast once.

```c#
do {
  // code 
} while (condition);
```

## Arrays

Array is a collection of similar data which is stored in continuous memory addresses. Array values can be fetched using index.  Index starts from 0 to size-1.

### Syntax

```c#
data-type[] array-name;
```

## Methods

Method is a set of statements which gets executed only when they are called. Call the method name in the main function to execute the method.

### Syntax

```c#
static void method-name() 
{
  // code to be executed
}
```
