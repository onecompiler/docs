# R Language Online Compiler

Write, Run & Share R Language code online using OneCompiler's R Language online compiler for free. It's one of the robust, feature-rich online compilers for R language, running on the latest version 3.4. Getting started with the OneCompiler's R Language compiler is simple and pretty fast. The editor shows sample boilerplate code when you choose language as `R` and start coding. 

# About R

R is very popular for data analytics which was created by Ross Ihaka and Robert Gentleman in 1993. Many big companies like Google, Facebook, Airbnb etc uses this language for data analytics. R is good for software developers, statisticians and data miners. 

## Key Features

* Interpreted programming language(no compilation required)
* provides highly extensible graphical techniques.
* Good community support
* Free and open-source
* Handles data very effectively.

# Syntax help

## Data Types

| Data type | Description | Usage |
|----|----|----|
|Numeric|To represent decimal values| x=1.84|
|Integer| To represent integer values, L tells to store the value as integer| x=10L|
|Complex| To represent complex values | x = 10+2i|
|Logical| To represent boolean values, true or false | x = TRUE|
|Character| To represent string values | x <- "One compiler"|
| raw | Holds raw bytes||

## Variables

Variables can be assigned using any of the leftward, rightward or equal to operator. You can print the variables using either print or cat functions.

```c
var-name = value
var-name <- value
value -> var-name
```

## Loops


### 1. IF Family:

If, If-else, Nested-Ifs are used when you want to perform a certain set of operations based on conditional expressions.

#### If

```py
if(conditional-expression){    
    #code    
} 
```

#### If-else
```py
if(conditional-expression){  
    #code if condition is true  
} else {  
    #code if condition is false  
} 
```

#### Nested-If-else
```py
if(condition-expression1) {  
    #code if above condition is true  
} elseif(condition-expression2){  
    #code if above condition is true  
}  
elseif(condition-expression3) {  
    #code if above condition is true  
}  
...  
else {  
    #code if all the conditions are false  
}  
```

### 2. Switch:

Switch is used to execute one set of statement from multiple conditions.

```r
switch(expression, case-1, case-2, case-3....)   
```

### 3. For:

For loop is used to iterate a set of statements based on a condition.

```r
for (value in vector) {  
  # code  
} 
```
### 4. While:

While is also used to iterate a set of statements based on a condition. Usually while is preferred when number of iterations are not known in advance.

```r
while(condition) {  
 # code 
}  
```
### 5. Repeat:

Repeat is used tyo iterate a set of statements with out any condition. You can write a user-defined condition to exit from the loop using `IF`.

```r
repeat {   
   #code   
   if(condition-expression) {  
      break  
   }  
} 
```

## Functions

Function is a sub-routine which contains set of statements. Usually functions are written when multiple calls are required to same set of statements which increases re-usuability and modularity.

### How to define a Function

```r
func-name <- function(parameter_1, parameter_2, ...) {  
   #code for function body   
}  
```

### How to call a Function

```r
function_name (parameters)
```

## Vectors

Vector is a basic data strucre where sequence of data values share same data type. 

For example, the below statement assigns 1 to 10 values to x.
You can also use se() function to create vectors.
```r
x <- 1:10
```

```r
#using seq() function
 x <- seq(1, 10, by=2)
```
the above statement prints the output as `[1] 1 3 5 7 9`.

