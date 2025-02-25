# Dart online compiler

Write, Run & Share Dart code online using OneCompiler's Dart online compiler for free. It's one of the robust, feature-rich online compilers for the Dart language, running the latest Dart version 3.6.1. Getting started with OneCompiler's Dart editor is easy and fast. The editor shows sample boilerplate code when you choose Dart as the language and start coding.

# Taking inputs (stdin)
OneCompiler's Dart online editor supports stdin, and users can provide inputs to programs using the STDIN textbox under the I/O tab. The following is a sample Dart program that takes a name as input and prints a greeting message.

```java
import 'dart:io';

void main() {
  String? name = stdin.readLineSync();
  print("Hello $name");
}
```

# About Dart

Dart is an open-source, general-purpose programming language developed by Google. It is optimized for building mobile, desktop, server, and web applications. Dart is known for its simplicity, fast execution, and easy-to-learn syntax. It is the primary language used in Flutter for building cross-platform mobile apps.

# Syntax help

## Variables

* Dart is a statically typed language but also supports dynamic typing.
* Variables can be explicitly typed or inferred using `var`.
* The `final` and `const` keywords define immutable variables.

### Examples

```java
// Explicitly typed variables
int a = 10;
String name = "OneCompiler";

// Type inference using var
var x = 30;

// Final and Const
final String appName = "OneCompiler";
const double pi = 3.14;
```


| Value Type | Description |
|------------|------------|
| int | Represents integer numbers |
| double | Represents floating-point numbers |
| String | Represents text |
| bool | Value can be either `true` or `false` |
| List | Represents an ordered collection of elements |
| Map | Represents key-value pairs |
| Set | Represents an unordered collection of unique elements |
| Runes | Represents Unicode characters |
| Null | Represents the absence of a value |
| dynamic | Can hold any type of value |

## Loops

### 1. While:
The `while` loop is used to execute a set of statements while a condition holds true.

```java
while (condition) {
  // code
}
```

### 2. Do-While:
The `do-while` loop executes the code at least once before checking the condition.

```java
do {
  // code
} while (condition);
```

### 3. For:
The `for` loop is used when the number of iterations is known in advance.

```java
for (int i = 0; i < 5; i++) {
  // code
}
```

### 4. For-in:
Used for iterating over collections like lists or sets.

```java
List<String> names = ['Alice', 'Bob', 'Charlie'];
for (String name in names) {
  print(name);
}
```

### 5. ForEach:
An alternative way to iterate over collections.

```java
names.forEach((name) {
  print(name);
});
```

## Functions
A function is a reusable block of code that performs a specific task.

```java
// Function with return type
int add(int a, int b) {
  return a + b;
}

// Function without return type
void greet(String name) {
  print("Hello, $name");
}

// Arrow function (short-hand syntax)
int multiply(int a, int b) => a * b;
```

---
This guide provides a quick reference to Dart programming syntax and features. Start coding in Dart using OneCompiler's Dart online compiler today!
