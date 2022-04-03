# Tool Command Language(TCL) online compiler

Write, Run & Share TCL code online using OneCompiler's TCL online compiler for free. It's one of the robust, feature-rich online compilers for TCL language, running the latest TCL version 8.6. Getting started with the OneCompiler's TCL editor is easy and fast. The editor shows sample boilerplate code when you choose language as TCL and start coding. 

# Taking inputs (stdin)
OneCompiler's TCL online editor supports stdin and users can give inputs to programs using the STDIN textbox under the I/O tab. Following is a sample TCL program which takes name as input and prints hello message with your name.

```tcl
set name [gets stdin]
puts "Hello $name"
```
# About TCL

Tool Command Language(TCL) is a general purpose scripting language which is commonly used for GUIs and for testing. Everything is by default string in TCL. It was created by John Osterhout in 1989.


# Syntax help

## Variables

Variable is a identifier which is used to hold the value. `set` is used to create variables.

### Examples

```tcl
set name onecompiler
```

## Loops

### 1. If-Else:

When ever you want to perform a set of operations based on a condition IF-ELSE is used.

```tcl
if(conditional-expression) {
   #code
} else {
   #code
}
```

You can also use if-else for nested Ifs and If-Else-If ladder when multiple conditions are to be performed on a single variable.

### 2. Switch:

Switch is an alternative to If-Else-If ladder.

```tcl
switch(conditional-expression) {    
value1 {     
 # code
}    
value1 {     
 # code
}    
...
default {
# code
} 
```
### 3. For:

For loop is used to iterate a set of statements based on a condition.

```tcl
for{start}{test}{next}{  
  # code  
} 
```
### 4. While:

While is also used to iterate a set of statements based on a condition. Usually while is preferred when number of iterations are not known in advance.

```tcl
while(condition) {  
 # code 
}  
```


## Arrays

Array is a collection of similar data which is stored in continuous memory addresses. Array values can be fetched using index. Index starts from 0 to size-1.

### Syntax

```tcl
set ArrayName(Index) value
```
## Procedures

Procedure is a sub-routine which contains set of statements. Uusually procedures are required when multiple calls are made to same set of statements. Procedures increases re-usuability and modularity.

### Syntax
```tcl
proc procedureName {arguments} {
   # code
}
```
