# Common Lisp online compiler

Write, Run & Share Common Lisp code online using OneCompiler's Common Lisp online compiler for free. It's one of the robust, feature-rich online compilers for Common Lisp language, running the latest Common Lisp version 5.3. Getting started with the OneCompiler's Common Lisp editor is easy and fast. The editor shows sample boilerplate code  when you choose language as Common Lisp and start coding. 

# Read inputs from stdin
OneCompiler's Common Lisp online editor supports stdin and users can give inputs to programs using the STDIN textbox under the I/O tab. Following is a sample Common Lisp program which takes name as input and prints hello message with your name.

```py
(setq name (read))
(princ "Hello ")
(write name)
```
# About Common Lisp

Common Lisp is a generic language suitable for a wide range of industry applications. It is often referred as Programmable programming language because of it's high extensibility, machine independence, extensive control structures, dynamic updation of programs etc.

Common LISP was invented by John McCarthy in 1958 and was first implemenyted by Steve Russell on an IBM 704 computer.

# Syntax help

## Variables

* Global variables are declared using `defvar` keyword and these variables will be in effect until a new value is assigned.
* Type declaration is not required in LISP

### Example

```py
(defvar x 10)
(write x)
```
* Local variables are declared with in a function or a procedure. The scope of local variables will be only in that function.
* `let` and `prog`are used to declare local variables.

### Syntax

```py
(let ((var1  value1) (var2  value2).. (varn  valuen))<expressions>)
```

* You can also create global and local variables using `setq`

### Example

```py
(setq a 10)
```


## Loops

### 1. Loop:

This is the simplest looping mechanism in LISP. This allows the execute the set of statements repeatedly until a return statement is encountered.

### Syntax
```py
(loop (s-expressions))
```

### 2. For:

For loop is used to iterate a set of statements based on a condition.

```py
(loop for loop-variable in <a list>
   do (action)
)
```
### 3. Do:

Do is also used to iterate a set of statements and then check the condition
```py
(do ((var1    val1   updated-val1)
      (var2   val2   updated-val2)
      (var3   val3   updated-val3)
   ...)
   (test return-value)
   (s-expressions)
)
```

### 4. Dotimes:

Dotimes is used to iterate for fixed number of iterations.

### Syntax:

```py
(dotimes (n val)
  statements
```
