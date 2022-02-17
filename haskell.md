# Haskell online compiler
Write, Run & Share Haskell code online using OneCompiler's Haskell online compiler for free. It's one of the robust, feature-rich online compilers for Haskell language, running the latest Haskell version 8.6. Getting started with the OneCompiler's Haskell editor is easy and fast. The editor shows sample boilerplate code when you choose language as Haskell and start coding. 

# Taking inputs (stdin)
OneCompiler's Haskell online editor supports stdin and users can give inputs to programs using the STDIN textbox under the I/O tab. Following is a sample Haskell program which takes name as input and prints hello message with your name.


```c
main = do  
    name <- getLine  
    putStrLn ("Hello " ++ name ++ ", Happy learning!") 
```
# About Haskell

Haskell is purely a functional programming language which was introduced in 1990's. 

## Key Features

* Haskell is both compiled and interpreted
* Lazy language as the results are computed only if required
* Pure functions
* Pattern matching on data structures
* Emphasizes on what to do but not on how to do
* Glasgow Haskell Compiler (GHC), most widely used Haskell compiler also written in Haskell.
* Data is immutable


# Syntax help
## Data Types

| Data-type | Description |
|----|----|
|Numbers| Haskell is intelligent to identify numbers without specifying data type|
|Characters| Haskell is intelligent to identify characters and strings without specifying data type|
|Tuple|To declare multiple values in a single data type. Tuples are represented in single paranthesis. For example (10, 20, 'apple')|
|Boolean|To represent boolean values, true or false|
|List|To declare same type of values in a single data type. Lists are represented in square braces.For example `[1, 2, 3]` or `['a','b','c','d']|

## Control statements

###  If-Else / Nested If-Else:
When ever you want to perform a set of operations based on a condition or set of conditions, then If-Else/ Nested-If-Else are used.

### Example:

```c
main = do   
   let age = 21 
   if age > 18 
      then putStrLn "Adult" 
   else putStrLn "child"
```


## Functions

Function is a sub-routine which contains set of statements. Usually functions are written when multiple calls are required to same set of statements which increases re-usuability and modularity. Functions play an important role in Haskell, since it is a purely functional language.


### Example
```c
multiply :: Integer -> Integer -> Integer   --declaration of a function 
multiply x1 x2 =  x1 * x2                   --definition of a function

main = do 
   putStrLn "Multiplication value is:"  
   print(multiply 10 5)    --calling a function
```
