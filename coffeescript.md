# CoffeeScript online compiler

Write, Run & Share CoffeeScript code online using OneCompiler’s CoffeeScript online compiler for free. It’s a sleek and efficient environment to explore CoffeeScript's syntax and compile it directly into JavaScript.

# About CoffeeScript

CoffeeScript is a lightweight language that compiles into JavaScript. It introduces a more readable and expressive syntax by eliminating much of the boilerplate found in traditional JavaScript. CoffeeScript supports all JavaScript features but with a more concise syntax.

# Sample Code

The following CoffeeScript program prints a greeting:

```coffeescript
console.log 'Hello, OneCompiler!'
```

# Taking inputs (stdin)

CoffeeScript itself doesn't support native input, but in environments like OneCompiler, you can simulate input using `readline-sync` or predefined variables.

```coffeescript
readline = require 'readline-sync'
name = readline.question 'Enter your name: '
console.log "Hello, #{name}!"
```

# Syntax Basics

## Variables

```coffeescript
name = 'OneCompiler'
age = 25
```

## Conditionals

```coffeescript
if age >= 18
  console.log 'Adult'
else
  console.log 'Minor'
```

## Loops

### For loop

```coffeescript
for i in [1..5]
  console.log i
```

### While loop

```coffeescript
i = 1
while i <= 5
  console.log i
  i++
```

## Functions

```coffeescript
square = (x) -> x * x
console.log square 4
```

## Arrays and Objects

```coffeescript
fruits = ['apple', 'banana', 'cherry']
person = name: 'Alice', age: 30
```

---

This guide provides a quick reference to CoffeeScript syntax and features. Start writing CoffeeScript code using OneCompiler’s CoffeeScript online compiler today!
