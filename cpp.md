# C++ Online Compiler

Write, Run & Share C++ code online using OneCompiler's C++ online compiler for free. It's one of the robust, feature-rich online compilers for C++ language, running on the latest version 17. Getting started with the OneCompiler's C++ compiler is simple and pretty fast. The editor shows sample boilerplate code  when you choose language as `C++` and start coding!

# Read inputs from stdin
OneCompiler's C++ online compiler supports stdin and users can give inputs to programs using the STDIN textbox under the I/O tab. Following is a sample program which takes name as input and print your name with hello.

```c
#include <iostream>
#include <string>
using namespace std;

int main() 
{
    string name;
    cout << "Enter name:";
    getline (cin, name);
    cout << "Hello " << name;
    return 0;
}
```

# About C++
C++ is a widely used middle-level programming language. 

* Supports different platforms like Windows, various Linux flavours, MacOS etc
* C++ supports OOPS concepts like Inheritance, Polymorphism, Encapsulation and Abstraction.
* Case-sensitive
* C++ is a compiler based language
* C++ supports structured programming language 
* C++ provides alot of inbuilt functions and also supports dynamic memory allocation.
* Like C, C++ also allows you to play with memory using Pointers.

# Syntax help

## Loops
### 1. If-Else:

When ever you want to perform a set of operations based on a condition If-Else is used.

```c
if(conditional-expression) {
   //code
}
else {
   //code
}
```
You can also use if-else for nested Ifs and If-Else-If ladder when multiple conditions are to be performed on a single variable.

### 2. Switch:

Switch is an alternative to If-Else-If ladder.

```c
switch(conditional-expression){    
case value1:    
 // code    
 break;  // optional  
case value2:    
 // code    
 break;  // optional  
......    
    
default:     
 code to be executed when all the above cases are not matched;    
} 
```

### 3. For:

For loop is used to iterate a set of statements based on a condition.

```c
for(Initialization; Condition; Increment/decrement){  
  //code  
} 
```

### 4. While:

While is also used to iterate a set of statements based on a condition. Usually while is preferred when number of iterations are not known in advance.

```c
while (condition) {  
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

## Functions

Function is a sub-routine which contains set of statements. Usually functions are written when multiple calls are required to same set of statements which increases re-usuability and modularity. Function gets run only when it is called.

### How to declare a Function:

```c
return_type function_name(parameters);
```

### How to call a Function:

```c
function_name (parameters)
```
### How to define a Function:
```c
return_type function_name(parameters) {  
 // code
}
```

