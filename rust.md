# Rust online compiler

Write, Run & Share Rust code online using OneCompiler’s Rust online compiler for free. It’s a fast, interactive, and powerful environment to learn and experiment with the Rust programming language. OneCompiler runs the latest stable version of Rust.

# About Rust

Rust is a systems programming language developed by Mozilla that focuses on performance, memory safety, and concurrency. It guarantees memory safety without a garbage collector and is widely used for system-level programming, web assembly, and command-line tools. Rust's compiler enforces strict compile-time checks, making code safer and more predictable.

# Sample Code

The following is a simple Rust program that prints a greeting:

```rust
fn main() {
    println!("Hello, OneCompiler!");
}
```

# Taking inputs (stdin)

OneCompiler’s Rust editor supports stdin. Here’s a sample program that reads a line of input and prints it:

```rust
use std::io;

fn main() {
    let mut input = String::new();
    io::stdin()
        .read_line(&mut input)
        .expect("Failed to read line");
    println!("Hello, {}", input.trim());
}
```

# Syntax Basics

## Variables

```rust
let name = "OneCompiler";        // Immutable
let mut age = 25;                // Mutable
```

## Data Types

| Type     | Description            |
| -------- | ---------------------- |
| i32, i64 | Signed integers        |
| f32, f64 | Floating-point numbers |
| bool     | true or false          |
| char     | Single character       |
| String   | Growable string        |

## Conditionals

```rust
let score = 85;
if score >= 50 {
    println!("Pass");
} else {
    println!("Fail");
}
```

## Loops

### For loop

```rust
for i in 1..=5 {
    println!("{}", i);
}
```

### While loop

```rust
let mut i = 1;
while i <= 5 {
    println!("{}", i);
    i += 1;
}
```

### Loop (infinite with break)

```rust
let mut count = 0;
loop {
    if count == 3 {
        break;
    }
    println!("{}", count);
    count += 1;
}
```

## Functions

```rust
fn add(a: i32, b: i32) -> i32 {
    a + b
}

fn greet(name: &str) {
    println!("Hello, {}!", name);
}
```

---

This guide provides a quick reference to Rust programming syntax and features. Start coding in Rust using OneCompiler’s Rust online compiler today!
