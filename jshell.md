# Jshell online compiler
Write, Run & Share Jshell code online using OneCompiler's Jshell online compiler for free. It's one of the robust, feature-rich online compilers for Jshell language, running the Jshell version 17. Getting started with the OneCompiler's Jshell editor is easy and fast. The editor shows sample boilerplate code when you choose language as Jshell and start coding. 

# About Jshell

Jshell is Java’s first official REPL (READ-EVAL-PRINT-LOOP) tool which was introduced in JDK 9 as part of Java Enhancement Proposal. It is suitable to learn the language and also to understand unfamiliar code. With Jshell, you can test the functionality in isolation of a class.

In short, Jshell creates a simple and easy programming environment in the command line which can take input from user, read it and then prints the result.


# Syntax help

## Variables
When you evaluate any valid java expression, the result will be stored in the system defined variables.
You can also create your own variables

```java
// datatype variable name = value;
int age = 16; // example
```

## Taking inputs (stdin)
By default Jshell creates a new VM to run the code which makes the System.in unavialble to use. OneCompiler has a workaround to this by adding `--execution local` param. User need to mention this in comments to make use of this option. Following is an example program to demonstrate this

```java
//--execution local
Scanner input = new Scanner(System.in);
System.out.println("Enter your name: ");
String inp = input.next();
System.out.println("Hello, " + inp);
```

## Control statements

### 1. If-Else:

When ever you want to perform a set of operations based on a condition If-Else is used.

Syntax:

```java
if(condition) {
  // code when condition true
} else {
  // code when condition false
}
```

Example:

```java
int i = 3
if( i%2 == 0 ) {
   System.out.println("Even number");
} else {
   System.out.println("Odd number");
}
```

### 2. For:

For loop is used to iterate a set of statements based on a condition. Usually for loop is preferred when number of iterations is known in advance.

Syntax:

```java
for( Initialization; Condition; Increment/decrement ){  
  //code  
} 
```

Example: 

```java
for(int i = 1; i <= 10; i++ ){
  Systen.out.println(i);
}
```

### 3. While:

While is also used to iterate a set of statements based on a condition. Usually while is preferred when number of iterations are not known in advance.

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