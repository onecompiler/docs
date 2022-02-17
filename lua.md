# Lua online compiler

Write, Run & Share Lua code online using OneCompiler's Lua online compiler for free. It's one of the robust, feature-rich online compilers for Lua language, running the latest Lua version 5.3. Getting started with the OneCompiler's Lua editor is easy and fast. The editor shows sample boilerplate code when you choose language as Lua and start coding. 

# Taking inputs (stdin)
OneCompiler's Lua online editor supports stdin and users can give inputs to programs using the STDIN textbox under the I/O tab. Following is a sample Lua program which takes name as input and prints hello message with your name.

```c
name = io.read("*a")
print ("Hello ", name)
```
# About Lua

Lua is a light weight embeddable scripting language which is built on top of C. It is used in almost all kind of applications like games, web applications, mobile applications, image processing etc. It's a very powerful, fast, easy to learn, open-source scripting language.

# Syntax help

## Variables

* By default all the variables declared are global variables
* If the variables are explicitly mentioned as local then they are local variables.
* Lua is a dynamically typed language and hence only the values will have types not the variables.

### Examples

```c
-- global variables
a = 10

-- local variables

local x = 30
```

|Value Type| Description|
|-----|-----|
|number| Represents numbers|
|string| Represents text|
|nil|Differentiates values whether it has data or not|
|boolean|Value can be either true or false|
|function|Represents a sub-routine|
|userdata|Represents arbitary C data|
|thread|Represents independent threads of execution.|
|table|Can hold any value except nil|


## Loops

### 1. While:

While is also used to iterate a set of statements based on a condition. Usually while is preferred when number of iterations are not known in advance.

```c
while(condition)
do
--code
end
```
### 2. Repeat-Until:

Repeat-Until is also used to iterate a set of statements based on a condition. It is very similar to Do-While, it is mostly used when you need to execute the statements atleast once.

```c
repeat
   --code
until( condition )
```

### 3. For:
For loop is used to iterate a set of statements based on a condition.

```c
for init,max/min value, increment
do
   --code
end
```

##  Functions
Function is a sub-routine which contains set of statements. Usually functions are written when multiple calls are required to same set of statements which increase re-usuability and modularity.


```c
optional_function_scope function function_name( argument1, argument2, argument3........, argumentn)
--code
return params with comma seperated
end
```