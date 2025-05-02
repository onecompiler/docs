# Pascal online compiler

Write, Run & Share Pascal code online using OneCompiler’s Pascal online compiler for free. It’s a straightforward, accessible way to learn and experiment with Pascal programming right from your browser. OneCompiler supports modern Pascal syntax and provides a ready-to-use editor for immediate execution.

# About Pascal

Pascal is a procedural programming language developed in the 1970s by Niklaus Wirth. It was designed to encourage good programming practices and structured programming. Pascal is widely used in teaching computer science fundamentals and has influenced many modern languages.

# Sample Code

The following is a simple Pascal program that prints a greeting:

```pascal
program HelloWorld;
begin
  writeln('Hello, OneCompiler!');
end.
```

# Taking inputs (stdin)

OneCompiler’s Pascal editor supports stdin through the I/O tab. Here’s an example that reads a user's name and prints a greeting:

```pascal
program GreetUser;
var
  name: string;
begin
  readln(name);
  writeln('Hello, ', name, '!');
end.
```

# Syntax Basics

## Variables

```pascal
var
  age: integer;
  name: string;
  score: real;
  flag: boolean;
```

## Data Types

| Type    | Description            |
| ------- | ---------------------- |
| integer | Whole numbers          |
| real    | Floating-point numbers |
| char    | Single character       |
| string  | Sequence of characters |
| boolean | True or False          |

## Conditionals

```pascal
if score >= 50 then
  writeln('Pass')
else
  writeln('Fail');
```

## Loops

### For loop

```pascal
for i := 1 to 5 do
  writeln(i);
```

### While loop

```pascal
i := 1;
while i <= 5 do
begin
  writeln(i);
  i := i + 1;
end;
```

### Repeat-Until loop

```pascal
i := 1;
repeat
  writeln(i);
  i := i + 1;
until i > 5;
```

## Procedures and Functions

```pascal
procedure SayHello;
begin
  writeln('Hello!');
end;

function Add(a, b: integer): integer;
begin
  Add := a + b;
end;
```

---

This guide provides a quick reference to Pascal programming syntax and features. Start coding in Pascal using OneCompiler’s Pascal online compiler today!
