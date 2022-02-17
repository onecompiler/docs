# Go Online Compiler

Write, Run & Share Go code online using OneCompiler's Go online compiler for free. It's one of the robust, feature-rich online compilers for Go language, running on the latest version 1.10.2. Getting started with the OneCompiler's Go compiler is simple and pretty fast. The editor shows sample boilerplate code when you choose language as `GO` and start coding. 

# Read inputs from stdin
OneCompiler's Go online editor supports stdin and users can give inputs to programs using the STDIN textbox under the I/O tab. Following is a sample Go program which takes name as input and prints hello message with your name.

```go
package main
import "fmt"

func main() {
  var name string 
  fmt.Scanf("%s", &name) 
	fmt.Printf("Hello %s", name)
}
```

# About Go

Go language is an open-source, statically typed programming language by Google. Go is highly recommended for creation of highly scalable and available web applications.

Some of the products developed using Go are Kubernetes, Docker, Dropbox, Infoblox etc.

## Key Features
* Fast compilation
* Easy to write concurrent programs
* Simple and concise syntax
* Supports static linking
* Opensource and huge community support.

# Syntax help

## Data Types

| Data type | Description | Size|Range|
|-----|-----|-----|----|
|uint8|8-bit unsigned integer|1 byte|0 to 255|
|int8|8-bit signed integer|1 byte|-128 to 127|
|int16|16-bit signed integer|2 bytes|-32768 to 32767|
|unit16|16-bit unsigned integer|2 bytes|0 to 65,535|
|int32|32-bit signed integer|4 bytes|-2,147,483,648 to 2,147,483,647|
|uint32|32-bit unsigned integer|4 bytes|0 to 4,294,967,295|
|int64|64-bit signed integer|8 bytes|-9,223,372,036,854,775,808 to 9,223,372,036,854,775,807|
|uint64|64-bit unsigned integer|8 bytes|0 to 18,446,744,073,709,551,615|
|float32|32-bit signed floating point number|4 bytes|±1.5e-45 to ±3.4e38|
|float|64-bit signed floating point number|8 bytes|±5.0e-324 to ±1.7e308|
|string|sequence of immutable text|||
|bool|Stores either true or false|1 byte|True or false|

## Variables

Variable is a name given to the storage area in order to manipulate them in our programs.

```go 
var varible-names datatype;
```

## Loops

### 1. If-Else:

When ever you want to perform a set of operations based on a condition or set of conditions then If or IF-ELSE or Nested If-Elif-Else are used.

#### If
```go
if(conditional-expression) {
   // code
} 
```
#### If-Else
```go
if(conditional-expression) {
   // code
} else {
   // code
}
```
#### Nested If-Else

```go
if(conditional-expression) {
   // code
} else if(conditional-expression) {
   // code
} else {
   // code
}
```

### 2. For:

For loop is used to iterate a set of statements based on a condition.

```go
for Initialization; Condition; Increment/decrement {  
  // code  
} 
```
### 3. Switch:

Switch is an alternative to If-Else-If ladder.

```go
switch conditional-expression {    
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
#### Note:
Go doesn't have while or do-while loops like in C.

## Functions

Function is a sub-routine which contains set of statements. Usually functions are written when multiple calls are required to same set of statements which increases re-usuability and modularity.

```go
func functionname(parameter-name type) returntype {  
 //code
}
```
