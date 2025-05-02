# Octave online compiler

Write, Run & Share Octave code online using OneCompiler’s Octave online compiler for free. It’s a simple and powerful platform to practice numerical computations and matrix operations using GNU Octave right from your browser.

# About Octave

GNU Octave is an open-source high-level programming language primarily intended for numerical computations. It is mostly compatible with MATLAB, and it's commonly used for linear algebra, numerical analysis, signal processing, and other scientific computing tasks.

# Sample Code

The following is a simple Octave program that prints a greeting:

```octave
printf("Hello, OneCompiler!\n");
```

# Taking inputs (stdin)

OneCompiler’s Octave editor supports stdin through the I/O tab. Here's an example of reading input from the user:

```octave
name = input("Enter your name: ", "s");
printf("Hello, %s!\n", name);
```

# Syntax Basics

## Variables

```octave
a = 10;
b = 3.14;
name = "Octave";
```

## Vectors and Matrices

```octave
v = [1, 2, 3];
M = [1, 2; 3, 4];
```

## Arithmetic

| Operation    | Syntax     |
| ------------ | ---------- |
| Add          | `+`        |
| Subtract     | `-`        |
| Multiply     | `*`        |
| Divide       | `/`        |
| Element-wise | `.*`, `./` |

## Conditionals

```octave
x = 10;
if x > 5
    disp("x is greater than 5");
else
    disp("x is 5 or less");
end
```

## Loops

### For loop

```octave
for i = 1:5
    disp(i);
end
```

### While loop

```octave
i = 1;
while i <= 5
    disp(i);
    i = i + 1;
end
```

## Functions

```octave
function y = square(x)
    y = x ^ 2;
end

result = square(4);
printf("Square: %d\n", result);
```

---

This guide provides a quick reference to Octave programming syntax and features. Start writing Octave code using OneCompiler’s Octave online compiler today!
