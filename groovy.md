# Groovy online compiler
Write, Run & Share Groovy code online using OneCompiler's Groovy online compiler for free. It's one of the robust, feature-rich online compilers for Groovy language, running the latest Groovy version 2.6. Getting started with the OneCompiler's Groovy editor is easy and fast. The editor shows sample boilerplate code when you choose language as Groovy and start coding.

# Read inputs from stdin
OneCompiler's Groovy online editor supports stdin and users can give inputs to programs using the STDIN textbox under the I/O tab. Following is a sample Groovy program which takes name as input and prints hello message with your name.

```groovy
def name = System.in.newReader().readLine()
println "Hello " + name
```
# About Groovy

Groovy is an object-oriented programming language based on java. Apache Groovy is a dynamic and agile language which is similar to Python, Ruby, Smalltalk etc. 

## Key Features

* It's not a replacement for java but it's an enhancer to Java with extra features like DSL support, dynamic typing, closures etc.
* Accepts Java code as it extends JDK
* Greater flexibility
* Concise and much simpler compared to Java
* Can be used as both programming language and scripting language.


# Syntax help
## Data Types

| Data type | Description | Range|
|----|-----|------|
|String | To represent text literals| NA|
|char| To represent single character literal|NA
|int| To represent whole numbers|-2,147,483,648 to 2,147,483,647|
|short| To represent short numbers|-32,768 to 32,767|
|long| To represent long numbers|-9,223,372,036,854,775,808 to +9,223,372,036,854,775,807|
|double| To represent 64 bit floating point numbers|4.94065645841246544e-324d to 1.79769313486231570e+308d|
|float| To represent 32 bit floating point numbers|1.40129846432481707e-45 to 3.40282346638528860e+38|
|byte| To represent byte value|-128 to 127|
|boolean| To represent boolean values either true or false|True or False|


## Variables

You can define variables in two ways

### Syntax:
```java
data-type variable-name;

[or]

def variable-name;
```

## Loops

```java
0.upto(n) {println "$it"}
```
or
```java
n.times{println "$it"}
```
where n is the number of loops and 0 specifies the starting index

## Decision-Making

### 1. If / Nested-If / If-Else:

When ever you want to perform a set of operations based on a condition or set of conditions, then If / Nested-If / If-Else is used.

```java
if(conditional-expression) {
  // code
} else {
  // code
}
```
### 2. Switch:

Switch is an alternative to If-Else-If ladder and to select one among many blocks of code.

```java
switch(conditional-expression) {    
case value1:    
 // code    
 break;  // optional  
case value2:    
 // code    
 break;  // optional  
...    
    
default:     
 //code to be executed when all the above cases are not matched;    
} 
```

## List
List allows you to store ordered collection of data values.

### Example:

```java
def mylist = [1,2,3,4,5];
```

| List Methods | Description |
|-----|------|
|size()| To find size of elements|
|sort()| To sort the elements|
|add()| To append new value at the end|
|contains()| Returns true if this List contains requested value.|
|get()| Returns the element of the list at the definite position|
|pop()| To remove the last item from the List|
|isEmpty()| Returns true if List contains no elements|
|minus()| This allows you to exclude few specified elements from the elements of the original|
|plus()| This allows you to add few specified elements to the elements of the original|
|remove()| To remove the element present at the specific position|
|reverse()|To reverse the elements of the original List and creates new list|


