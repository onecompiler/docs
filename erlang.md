# Erlang Online Compiler

Write, Run & Share Erlang code online using OneCompiler's Erlang online compiler for free. It's one of the robust, feature-rich online compilers for Erlang language, running on the latest version 21. Getting started with the OneCompiler's Erlang compiler is simple and pretty fast. The editor shows sample boilerplate code when you choose language as `Erlang` and start coding. 

# About Erlang

Erlang is a special niche functional programming language by Ericcson and first appeared in the year 1986. Many Big companies are using Erlang like Whatsapp, Facebook, Amazon, RabbitMQ and many others and ofcourse Ericsson. 

## Key Features
* Open source
* Mini operating system with a number of interesting features
* Initially designed as phone language but later it's used in variety of applications.
* Largely parallel and distributed
* updates can be made with no downtime at all
* Super clean error handling model
* Automatic application migration.

# Syntax help


## Variables
Variables syntax is as follows

```erlang
variable-name = value
```
## Data types

| Data type| Usage| Description|
|----|----|----|
| Numeric| start() -> `io:fwrite("~w",[10+10])` | Erlang supports both integer and float values.|
| Atom| start() -> io:fwrite(true) | Atoms should start with lower case leters and can contain  lowercase and uppercase characters, numbers, `_` and `@`. You can also put atom in single quotes|
| Boolean | start() ->  io:fwrite(10 =< 8)| Output will be either true or false based on the values given|
| Bit String|  str = <<10,20>>| Strings are enclosed in << >> and are used to store untyped memory|
| Lists|`[1,2,3]`| Lists is a compound data type with Variable number of elements.|
| Tuples| t = {apple, 100, {orange,50}} | Tuple is a compound data type with fixed number of elements.|
|Map| map = #{name => onecompiler, message => Learning}| Map is a compound data type with a variable number of key-value pairs|

## Loops

### 1. If-Else:

If the condition is true then true-statement will get executed else false-statement.

```erlang
if
condition ->
   true-statement;
true ->
   false-statement
end.
```

### 2. Case:

If the value is equal to any of the values(value1,value2,..Valuen) then corresponding statements will get executed.

```erlang
case value of
   value1 -> statement1;
   value2 -> statement2;
   valuen -> statementn
end.
```
### Note:
As Erlang is a functional programming language, there are no direct constructs for while, for and other loops. Recursion is the technique followed to implement loops in Erlang. 

