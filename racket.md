# Racket Online Compiler

Write, Run & Share Racket code online using OneCompiler's Racket online compiler for free. It's one of the robust, feature-rich online compilers for Racket language, running on the latest version 6.8. Getting started with the OneCompiler's Racket compiler is simple and pretty fast. The editor shows sample boilerplate code when you choose language as `Racket` and start coding. 

# Taking inputs (stdin)

OneCompiler's Racket online editor supports stdin and users can give inputs to programs using the STDIN textbox under the I/O tab. Following is a sample Racket program which takes name as input and print your name with hello.

```racket
#lang racket/base
(define name (read))                
(printf "Hello ~a.\n" name)   
```
# About Racket

Racket is a general-purpose programming language based on the Scheme dialect of Lisp. It is also used for scripting, computer science education, and research related applications.

## Basics

| Item | Decsription|
|----|----|
|`;` | To comment a single line|
|`;;`| to mark important comments|
|`#;`| to comment the following s-expression|

## Data types

| Data-type | Decsription|
|----|----|
|Numbers| represents integers, float and complex numbers|
|Boolean| `#t` and `#f` are the two boolean literals|
|Strings| To represent sequence of characters and double quotes("") are used to represent strings|

## Variables

let  and define are used to declare  variables

### Syntax

```racket
(let ([id value-expression] ...) body ...+)

(let proc-id ([id init-expression] ...) body ...+)
```

```racket
define id expression
```

### Example

```racket
> (let ([x 10]) x)
10
```
## Loops and conditional statements

### 1. If family

If, If-else are used when you want to perform a certain set of operations based on conditional expressions.

#### If
```racket
(if cond-expr then-expr)
```

#### If-else
```racket
(if cond-expr then-expr else-expr)
```

### 2. For

For loop is used to iterate a set of statements based on a condition.


```racket
(for (for-clause ...) body-or-break ... body)
```
```
where 

for-clause = [id seq-expr] | [(id ...) seq-expr] | #:when guard-expr | #:unless guard-expr | break-clause
 	 	 	 	 
break-clause = #:break guard-expr | #:final guard-expr
 	 	 	 	 
body-or-break = body | break-clause

seq-expr : sequence?
```


## Functions

A lambda expression is used to create a function. 

```racket
(lambda (argument-id ...)
  body ...+)
```