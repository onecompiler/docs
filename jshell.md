# Jshell online compiler
Write, Run & Share Jshell code online using OneCompiler's Jshell online compiler. It's one of the robust, feature-rich online compilers for Jshell language, running the latest Jshell version 9. Getting started with the OneCompiler's Jshell editor is easy and fast. The editor shows sample boilerplate code when you choose language as Jshell. OneCompiler also has reference programs, where you can look for the sample code and start learning. Happy learning!!

# About Jshell

Jshell is Java’s first official REPL (READ-EVAL-PRINT-LOOP) tool which was introduced in JDK 9 as part of Java Enhancement Proposal. It is suitable to learn the language and also to understand unfamiliar code. With Jshell, you can test the functionality in isolation of a class.

In short, Jshell creates a simple and easy programming environment in the command line which can take input from user, read it and then prints the result.


# Syntax help

## Variables
When you evaluate any valid java expression, the result will be stored in the system defined variables.

You can also create your own variables

### Syntax
```java
datatype variable name = value;
```

## Control statements

### 1. If-Else:

When ever you want to perform a set of operations based on a condition If-Else is used.

```java
if(conditional-expression) {
  // code
} else {
  // code
}
```
### Example:
```java
int x = 3
if(x%2 == 0) {
   System.out.println("Even number");
} else {
   System.out.println("Odd number");
}
```
### 2. For:

For loop is used to iterate a set of statements based on a condition. Usually for loop is preferred when number of ierations is known in advance.

```java
for(Initialization; Condition; Increment/decrement){  
//code  
} 
```
### 3. While:

While is also used to iterate a set of statements based on a condition. Usually while is preferred when number of iterations is not known in advance.

```java
while(condition){  
 // code 
}  
```
### 4. Do-While:
Do-while is also used to iterate a set of statements based on a condition. It is mostly used when you need to execute the statements atleast once.

```java
do {
  // code 
} while (condition); 
```
