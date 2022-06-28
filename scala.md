# Scala Online Compiler

Write, Run & Share Scala code online using OneCompiler's Scala online compiler for free. It's one of the robust, feature-rich online compilers for Scala language, running on the latest version 2.13.8. Getting started with the OneCompiler's Scala compiler is simple and pretty fast. The editor shows sample boilerplate code when you choose language as `Scala` and start coding. 


# Read input from STDIN in Scala

OneCompiler's Scala online editor supports stdin and users can give inputs to programs using the STDIN textbox under the I/O tab. Following is a sample Scala program which takes name as input and prints hello message with your name.

```java
object Hello {
	def main(args: Array[String]): Unit = {
	  val name = scala.io.StdIn.readLine()        // Read input from STDIN
    println("Hello " + name ) 
	}
}
```
# About Scala

Scala is both object-oriented and functional programming language by Martin Odersky in the year 2003. 

# Syntax help

## Variables

Variable is a name given to the storage area in order to identify them in our programs.

```java
var or val Variable-name [: Data-Type] = [Initial Value];
```

## Loops and conditional statements

### 1. If family:

If, If-else, Nested-Ifs are used when you want to perform a certain set of operations based on conditional expressions.

#### If

```java
if(conditional-expression){    
//code    
} 
```

#### If-else
```java
if(conditional-expression) {  
//code if condition is true  
} else {  
//code if condition is false  
} 
```

#### Nested-If-else
```java
if(condition-expression1) {  
//code if above condition is true  
} else if (condition-expression2) {  
//code if above condition is true  
}  
else if(condition-expression3) {  
//code if above condition is true  
}  
...  
else {  
//code if all the above conditions are false  
}  
```

### 2. For:

For loop is used to iterate a set of statements based on a criteria.

```java
for(index <- range){  
  // code  
} 
```


### 3. While:

While is also used to iterate a set of statements based on a condition. Usually while is preferred when number of iterations are not known in advance.

```java
while(condition) {  
 // code 
}  
```
### 4. Do-While:

Do-while is also used to iterate a set of statements based on a condition. It is mostly used when you need to execute the statements atleast once.

```java
do {
  // code 
} while (condition) 
```

## Functions

Function is a sub-routine which contains set of statements. Usually functions are written when multiple calls are required to same set of statements which increases re-usuability and modularity.

```java
def functionname(parameters : parameters-type) : returntype = {   //code
}
```
#### Note: 
You can either use `=` or not in the function definition. If `=` is not present, function will not return any value. 

