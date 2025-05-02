# Kotlin online compiler

Write, Run & Share Kotlin code online using OneCompiler’s Kotlin online compiler for free. It’s a modern and fast online playground for Kotlin, supporting the latest version and ideal for learning, experimenting, and sharing code instantly.

# About Kotlin

Kotlin is a statically typed, modern programming language developed by JetBrains. It runs on the JVM and is fully interoperable with Java. Kotlin is concise, expressive, and safe, and it’s officially supported by Google for Android app development.

# Sample Code

The following is a simple Kotlin program that prints a greeting:

```kotlin
fun main() {
    println("Hello, OneCompiler!")
}
```

# Taking inputs (stdin)

OneCompiler’s Kotlin editor supports stdin. You can provide input using the I/O tab. Here's a sample program that reads a line of input and prints a greeting:

```kotlin
fun main() {
    print("Enter your name: ")
    val name = readLine()
    println("Hello, $name")
}
```

# Syntax Basics

## Variables

```kotlin
val name: String = "OneCompiler"  // Immutable
var age: Int = 25                 // Mutable
```

Kotlin supports type inference, so explicit types are optional:

```kotlin
val city = "Hyderabad"
var count = 10
```

## Conditionals

```kotlin
val score = 85
if (score >= 50) {
    println("Pass")
} else {
    println("Fail")
}
```

## Loops

### For loop

```kotlin
for (i in 1..5) {
    println(i)
}
```

### While loop

```kotlin
var i = 1
while (i <= 5) {
    println(i)
    i++
}
```

### Do-While loop

```kotlin
var j = 1
do {
    println(j)
    j++
} while (j <= 5)
```

## Functions

```kotlin
fun add(a: Int, b: Int): Int {
    return a + b
}

fun greet(name: String) = "Hello, $name"
```

## Collections

```kotlin
val items = listOf("apple", "banana", "cherry")
for (item in items) {
    println(item)
}
```

---

This guide provides a quick reference to Kotlin programming syntax and features. Start coding in Kotlin using OneCompiler’s Kotlin online compiler today!
