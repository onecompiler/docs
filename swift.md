# Swift online compiler

Write, Run & Share Swift code online using OneCompiler’s Swift online compiler for free. It’s a fast and user-friendly platform to explore Swift programming right from your browser. Ideal for students, beginners, and professionals looking to prototype or test Swift code.

# About Swift

Swift is a powerful and intuitive programming language developed by Apple for iOS, macOS, watchOS, and tvOS app development. It's designed to be safe, fast, and expressive, with modern features like optionals, closures, and type inference.

# Sample Code

The following is a simple Swift program that prints a greeting:

```swift
import Foundation

print("Hello, OneCompiler!")
```

# Taking inputs (stdin)

OneCompiler’s Swift editor supports standard input via the I/O tab. Here’s a sample Swift program that takes a user’s name and prints a greeting:

```swift
import Foundation

if let name = readLine() {
    print("Hello, \(name)!")
}
```

# Syntax Basics

## Variables

```swift
var age = 25          // Mutable variable
let name = "Swift"     // Constant
```

## Data Types

| Type       | Description            |
| ---------- | ---------------------- |
| Int        | Whole numbers          |
| Double     | Decimal numbers        |
| String     | Sequence of characters |
| Bool       | true or false          |
| Array      | Ordered collection     |
| Dictionary | Key-value pairs        |

## Conditionals

```swift
let score = 75
if score >= 50 {
    print("Pass")
} else {
    print("Fail")
}
```

## Loops

### For-in loop

```swift
for i in 1...5 {
    print(i)
}
```

### While loop

```swift
var i = 1
while i <= 5 {
    print(i)
    i += 1
}
```

### Repeat-While loop

```swift
var j = 1
repeat {
    print(j)
    j += 1
} while j <= 5
```

## Functions

```swift
func greet(name: String) {
    print("Hello, \(name)!")
}

greet(name: "OneCompiler")

func add(a: Int, b: Int) -> Int {
    return a + b
}
```

---

This guide provides a quick reference to Swift programming syntax and features. Start writing Swift code using OneCompiler’s Swift online compiler today!
