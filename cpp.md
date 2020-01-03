# C++ Online Compiler

OneCompiler's C++ online compiler is one of the robust, feature-rich online compilers for C++ language, running on the latest version C++ 17. Users can write, run and share the code online and can track all the code history. Getting started with the OneCompiler's C++ compiler is simple and pretty fast. The editor shows sample boilerplate code where you can choose language as `C++`. OneCompiler also has reference programs, where you can look for the sample code and start learning.

## Taking inputs (stdin)
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
......    
    
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

## Functions

Functions is a sub-routine which contains set of statements. Usually functions are written when multiple calls are required to same set of statements which increases re-usuability and modularity. Function gets run only when it is called.

### How to declare a Function

```c
return_type function_name(parameters);
```

### How to call a Function

```c
function_name (parameters)
```
### How to define a Function

return_type function_name(parameters){  
//code
}

For more detailed C++ concepts checkout our beginner's tutorial 
