# F sharp Online Compiler

Write, Run & Share `F#` code online using OneCompiler's F# online compiler for free. It's one of the robust, feature-rich online compilers for `F#` language, running on the latest version 4.0. Getting started with the OneCompiler's `F#` compiler is simple and pretty fast. The editor shows sample boilerplate code when you choose language as `F#` and start coding. 

# Read inputs from stdin

OneCompiler's `F#` online editor supports stdin and users can give inputs to programs using the STDIN textbox under the I/O tab. Following is a sample `F#` program which takes name as input and prints hello message with your name.

```fsharp
open System
let name = Console.ReadLine()
Console.Write("Hello 0.\n", name)         
```
# About **`F#`**

`F#`(F sharp) is a functional programming language which was developed by Microsoft in the year 2005. `F#` is .net implementation of OCaml. It can be used in variety of applications like graphic designing, Telecommunications, AI, CPU design, compiler programming, web applications, games etc.,

# Syntax help

## Data Types

### Integer Data types
|Data type|Description|Size|Range|
|-----|----|----|----|
|sbyte|8-bit signed integer|1 byte|-128 to 127|
|byte|8-bit unsigned integer|1 byte|0 to 255|
|int16|16-bit signed integer|2 bytes|-32768 to 32767|
|unit16|16-bit unsigned integer|2 bytes|0 to 65,535|
|int/int32|32-bit signed integer|4 bytes|-2,147,483,648 to 2,147,483,647|
|uint32|32-bit unsigned integer|4 bytes|0 to 4,294,967,295|
|int64|64-bit signed integer|8 bytes|-9,223,372,036,854,775,808 to 9,223,372,036,854,775,807|
|uint64|64-bit unsigned integer|8 bytes|0 to 18,446,744,073,709,551,615|
|bigint|arbitrary precision integer|At least 4 bytes|Integers|

### Float Data types
|Data type|Description|Size|Range|
|-----|-----|-----|----|
|float32|32-bit signed floating point number|4 bytes|±1.5e-45 to ±3.4e38|
|float|64-bit signed floating point number|8 bytes|±5.0e-324 to ±1.7e308|
|decimal|128-bit signed floating point number|16 bytes|±1.0e-28 to ±7.9e28|

### Text and Boolean Data types
|Data type |Description|Size|Range|
|-----|-----|-----|----|
|char|single character|2 bytes|U+0000 to U+ffff|
|string|Text|20 + (2 * length of the string) bytes|0 to up to 2 billion characters|
|bool|Stores either true or false|1 byte|True or false|

## Variables

Variable is a name given to the storage area in order to manipulate them in our programs.

```fsharp
let variable_name:data-type = value
```
### Mutable variable declaration

```fsharp
let mutable variable_name:data-type = value
```

## Loops
### 1. If-Else:

When ever you want to perform a set of operations based on a condition or set of conditions then If or IF-ELSE or Nested If-Elif-Else are used.

#### If
```fsharp
if conditional-expression then
   // code
```
#### If-Else
```fsharp
if conditional-expression then
   // code
else 
   // code
```
#### Nested If-Elif-Else

```fsharp
if conditional-expression then
  // code
elif conditional-expression then
   // code
elif conditional-expression then
   // code
...
else
   // code
```
### 2. For:

For loop is used to iterate a set of statements based on a condition.

#### For..to
Iteration occurs in ascending order

```fsharp
for var = start-expression to end-expression do
  // code  
```

#### For...down-to
Iteration occurs in descending order.

```fsharp
for var = start-expression downto end-expression do
  // code  
```
#### For..in
This loops is used when iteration occurs over enumerable collection like arrays, lists, sequences, range expression etc.

```fsharp
for pattern in enumerable-collection-expr do
   // code
```

#### Example
```fsharp
let listItems = [1,2,3,4,5]
for x in listItems do
   printfn "%d" x
``` 

### 3. While:

While is also used to iterate a set of statements based on a condition. Usually while is preferred when number of iterations are not known in advance.

```fsharp
while condition-expr do   
 // code 
```

## Function

In `F#`, You can declare and use functions similar to Variables. In simpler words, you can understand them as user-defined variables.

### How to define a function

```fsharp
let [inline] function-name parameter-list [ : return-type ]
   = function-body
```

### How to call a function

```fsharp
let VarName = function-name parameter-list
```
