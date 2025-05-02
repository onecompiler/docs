# COBOL online compiler

Write, Run & Share COBOL code online using OneCompiler's COBOL online compiler for free. It’s a reliable and accessible playground to practice and run COBOL code with ease. The compiler supports classic COBOL syntax and is great for learning, teaching, and experimenting with business logic programs.

# About COBOL

COBOL (Common Business-Oriented Language) is a high-level programming language developed in the 1950s. It is primarily used in business, finance, and administrative systems for companies and governments. COBOL is known for its English-like syntax and is still widely used in legacy enterprise systems.

# Sample Code

The following is a simple COBOL program that prints a greeting:

```cobol
IDENTIFICATION DIVISION.
PROGRAM-ID. HELLO.
PROCEDURE DIVISION.
    DISPLAY "Hello, OneCompiler!".
    STOP RUN.
```

# Taking inputs

In COBOL, input is typically handled using the `ACCEPT` keyword. Here’s an example that takes user input and prints it back.

```cobol
IDENTIFICATION DIVISION.
PROGRAM-ID. GREET.
DATA DIVISION.
WORKING-STORAGE SECTION.
01 USER-NAME PIC A(30).

PROCEDURE DIVISION.
    DISPLAY "Enter your name: ".
    ACCEPT USER-NAME.
    DISPLAY "Hello, " USER-NAME "!".
    STOP RUN.
```

# Syntax Basics

## Program Structure

COBOL programs are divided into four divisions:

* **IDENTIFICATION DIVISION**: Program metadata
* **ENVIRONMENT DIVISION**: Machine/environment details (optional)
* **DATA DIVISION**: Variable declarations
* **PROCEDURE DIVISION**: Actual program logic

## Variables

Variables are declared in the `DATA DIVISION` using `PIC` clauses.

```cobol
01 AGE        PIC 99.
01 NAME       PIC A(20).
01 SALARY     PIC 9(5)V99.
```

## Displaying and Accepting Data

```cobol
DISPLAY "Welcome to COBOL!".
ACCEPT USER-INPUT.
```

## Conditional Statements

```cobol
IF AGE >= 18
    DISPLAY "Eligible to vote."
ELSE
    DISPLAY "Not eligible."
END-IF.
```

## Loops (PERFORM)

```cobol
PERFORM VARYING I FROM 1 BY 1 UNTIL I > 5
    DISPLAY "Count: " I
END-PERFORM.
```

---

This guide provides a quick reference to COBOL programming syntax and features. Start coding in COBOL using OneCompiler’s COBOL online compiler today!
