# Elixir Online Compiler

Write, Run & Share Elixir code online using OneCompiler's Elixir online compiler for free. It's one of the robust, feature-rich online compilers for Elixir language, running on the latest version 1.9.4. Getting started with the OneCompiler's Elixir compiler is simple and pretty fast. The editor shows sample boilerplate code when you choose language as `Elixir` and start coding. 

# About Elixir

Elixir is a general purpose programming language built on top of Erlang or Ericsson language. It is very efficient for building distributed, fault tolerant appications. It's been used by many companies like Pinterest, PagerDuty, FarmBot, E-Metro Tel etc. 

* Built especially for scalable and maintanable applications.
* Everything is an expression
* Compiles to bytecode
* Built-in tooling for compilation, testing, debugging, formatting code etc.
* Erlang functions can be called directly as it get compiled to Erlang bytecode.

# Syntax help

## Variables
Variables must be declared and assigned a value.

```elixir
variable-name = value
```
## Data types

| Data type| Usage| Description|
|----|----|----|
| Numeric| x = 21 | Elixir supports not only integer and float values but also a number can be defined in octal, hexadecimal and binary bases.|
| Atom| :true | Atoms are constant values whose name is same as their value|
| Boolean | : false, :true| Either true or false, usually declared as atoms|
| Strings| "Hello"| Strings are enclosed in double quotes(" ") and multi line strings are enclosed in triple double quotes(""" """)|
| Lists| ['a', 10, :true]| Lists are used to store different types of values and are represented in square brackets []|
| Tuples| {'apple', 100, :false} | Similar to Lists and are represented in curly brackets {}. Tuples are good for accessing the values and lists are good for insertion and deletion of values|


## Loops


### 1. If:

When ever you want to perform a set of operations based on a condition If is used.

```elixir
if condition do
   #Code 
end
```

### 2. If-Else:

When there is requirement to add code for false condition to IF block.

```elixir
if condition do
   #Code 
else
    #code
end
```

### 3. Unless:

Unless is similar to If but the code get executed only if the condition fails.

```elixir
unless condition do
   #Code 
end
```

### 4. Unless-Else:

Unless-Else is similar to If-Else but the code get executed only if the condition fails.

```elixir
unless condition do
   #Code if condition fails
else
    #Code if condition satisfies
end
```
### 5. Cond:
Cond is used when you want to execute a piece of code based on multiple conditions.

```elixir
cond do
   condition-1 -> #code if condition is true
   condition-2 -> #code if condition is true
   ...
   true -> #code if none of the above are true
end
```

### 6. Case:

Case is similar to switch in C language.

```elixir
case value do
    value-1 -> #code if value matches value-1
	value-2 -> #code if value matches value-2
	value-3 -> #code if value matches value-3
	...
	_ -> #code if value does not match any of the above and is similar to default in switch
end
```
## Functions

Function is a sub-routine which contains set of statements. Usually functions are written when multiple calls are required to same set of statements which increases re-usuability and modularity.

Two types of functions are present in Elixir

1. Anonymous Functions:

Anonymous functions are functions with no name and they use  `fn..end` constructs.

2. Named functions:

Assign names to functions so that they can be called easily. Always named functions are defined in modules.

```elixir
defmodule modulename do
    def function_name(parameter1, parameter2) do
        #code 
    end
end
```


