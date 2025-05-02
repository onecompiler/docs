# BASIC online compiler

Write, Run & Share BASIC code online using OneCompiler's BASIC online compiler for free. It’s a simple, easy-to-use playground to learn and explore the fundamentals of BASIC programming. The compiler supports classic BASIC syntax, ideal for learning or refreshing the basics of structured programming.

# About BASIC

BASIC (Beginner's All-purpose Symbolic Instruction Code) is one of the earliest programming languages designed to be easy for beginners. Originally developed in the 1960s, it emphasizes simplicity and readability, making it an ideal first language. Many dialects exist, such as QBASIC, FreeBASIC, and Microsoft BASIC.

# Sample Code

The following is a sample BASIC program that asks for a user's name and displays a greeting:

```basic
PRINT "Hello, World!"
```

# Taking inputs

In BASIC, you can take input from the user using the `INPUT` keyword. String variables usually end with `$`, and numeric variables can be declared without a suffix.

```basic
INPUT "Enter your age: "; age
PRINT "You are "; age; " years old."
```

# Syntax Basics

## Variables

* String variables end with `$` (e.g., `name$`)
* Numeric variables are used directly (e.g., `x`, `score`)

## Arithmetic Operators

| Operator | Description    |
| -------- | -------------- |
| +        | Addition       |
| -        | Subtraction    |
| \*       | Multiplication |
| /        | Division       |
| ^        | Exponentiation |

## Conditional Statements

```basic
IF score >= 50 THEN
  PRINT "You passed!"
ELSE
  PRINT "You failed."
END IF
```

## Loops

### FOR Loop

```basic
FOR i = 1 TO 5
  PRINT i
NEXT i
```

### WHILE Loop (often using GOTO in classic BASIC)

```basic
i = 1
WHILE i <= 5
  PRINT i
  i = i + 1
WEND
```

## GOTO and Labels

```basic
10 PRINT "Hello, World!"
20 GOTO 10
```

---

This guide provides a quick reference to BASIC programming syntax and features. Start coding in BASIC using OneCompiler’s BASIC online compiler today!
