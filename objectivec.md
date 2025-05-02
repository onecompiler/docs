# Objective-C online compiler

Write, Run & Share Objective-C code online using OneCompiler’s Objective-C online compiler for free. It’s a fast and minimal platform to experiment with Objective-C programs without needing a local development setup. Great for learning the basics or testing code snippets quickly.

# About Objective-C

Objective-C is a general-purpose, object-oriented programming language used by Apple for macOS and iOS development before Swift. It adds Smalltalk-style messaging to the C programming language. Objective-C is still widely used in legacy Apple applications and frameworks like Cocoa and Cocoa Touch.

# Sample Code

The following is a simple Objective-C program that prints a greeting:

```objectivec
#import <Foundation/Foundation.h>

int main(int argc, const char * argv[]) {
    @autoreleasepool {
        NSLog(@"Hello, OneCompiler!");
    }
    return 0;
}
```

# Taking inputs (stdin)

OneCompiler’s Objective-C editor supports stdin through standard input. Here’s a sample program that reads a user's name and prints it:

```objectivec
#import <Foundation/Foundation.h>

int main(int argc, const char * argv[]) {
    @autoreleasepool {
        char name[100];
        printf("Enter your name: ");
        scanf("%s", name);
        printf("Hello, %s!\n", name);
    }
    return 0;
}
```

# Syntax Basics

## Variables

```objectivec
int age = 30;
double score = 95.5;
char name[] = "OneCompiler";
NSString *greeting = @"Hello";
```

## Conditionals

```objectivec
int marks = 70;
if (marks >= 50) {
    NSLog(@"Pass");
} else {
    NSLog(@"Fail");
}
```

## Loops

### For loop

```objectivec
for (int i = 1; i <= 5; i++) {
    NSLog(@"%d", i);
}
```

### While loop

```objectivec
int i = 1;
while (i <= 5) {
    NSLog(@"%d", i);
    i++;
}
```

### Do-While loop

```objectivec
int j = 1;
do {
    NSLog(@"%d", j);
    j++;
} while (j <= 5);
```

## Functions

```objectivec
int add(int a, int b) {
    return a + b;
}

void greet(const char *name) {
    printf("Hello, %s!\n", name);
}
```

---

This guide provides a quick reference to Objective-C programming syntax and features. Start writing Objective-C code using OneCompiler’s Objective-C online compiler today!
