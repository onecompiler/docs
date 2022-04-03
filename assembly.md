# Assembly Online Compiler

Write, Run & Share Assembly code online using OneCompiler's Assembly online compiler for free. It's one of the robust, feature-rich online compilers for Assembly language. Getting started with the OneCompiler's Assembly compiler is simple and pretty fast. The editor shows sample boilerplate code when you choose language as `Assembly` and start coding. 

# About Assembly

Assembly language(asm) is a low-level programming language, where the language instructions will be more similar to machine code instructions. 

Every assembler may have it's own assembly language designed for a specific computers or an operating system.

Assembly language requires less execution time and memory. It is more helful for direct hardware manipulation, real-time critical applications. It is used in device drivers, low-level embedded systems etc.

# Syntax help

Assembly language usually consists of three sections, 

1. Data section

    To initialize variables and constants, buffer size these values doesn't change at runtime. 
2. bss section

    To declare variables

3. text section

    `_start` specifies the starting of this section where the actually code is written. 

## Variables


There are various define directives to allocate space for variables for both initialized and uninitialized data.

### 1.  To allocate storage space to Initialized data

### Syntax
```c
variable-name    define-directive    initial-value 
```

|Define Directive| Description| Allocated Space|
|-----|----|----|
|DB| Define Byte| 1 byte|
|DW| Define Word| 2 bytes|
|DD| Define Doubleword | 4 bytes|
|DQ| Define Quadword | 8 bytes|
|DT| Define Ten Bytes | 10 bytes|


### 2.  To allocate storage space to un-initialized data


|Define Directive|Description|
|-----|----|
|RESB|Reserve a Byte|
|RESW|Reserve a Word|
|RESD|Reserve a Doubleword|
|RESQ|Reserve a Quadword|
|REST|Reserve a Ten Bytes|


## Constants

Constants can be defined using 

### 1. equ

 * To define numeric constants

```
CONSTANT_NAME EQU regular-exp or value
```
### 2. %assign

 * To define numeric constants.

 ```
 %assign constant_name value
 ```

### 3. %define
* To define numeric or string constants.

```
%define constant_name value
```

## Loops

Loops are used to iterate a set of statements for a specific number of times.

```
mov ECX,n
L1:
;<loop body>
loop L1
```
where n specifies the no of times loops should iterate.

## Procedures

Procedure is a sub-routine which contains set of statements. Usually procedures are written when multiple calls are required to same set of statements which increases re-usuability and modularity.


```
procedure_name:
   ;procedure body
   ret
```
