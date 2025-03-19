# **Bun Online Compiler**  

Write, Run & Share Bun code online using OneCompiler's Bun online compiler for free. It's one of the fastest, feature-rich online compilers for the Bun runtime. Getting started with OneCompiler's Bun editor is easy and fast. The editor shows sample boilerplate code when you choose Bun as the language and start coding.  

---

# **About Bun**  

**Bun** is a modern JavaScript runtime designed for speed, efficiency, and native support for modern web development. It is built on JavaScriptCore instead of V8, making it extremely fast for running JavaScript and TypeScript applications.

---

# **Key Features**  

- **Blazing fast**: Bun is significantly faster than Node.js and Deno for many operations.  
- **Built-in package manager**: No need for `npm` or `yarn`—Bun can install packages directly.  
- **Native TypeScript & JSX support**: No additional configuration required.  
- **Embedded SQLite & Web APIs**: Makes it easy to build full-stack applications.  
- **Compatible with Node.js APIs**: Supports many existing Node.js modules.  

---

# **Syntax Help**  

## **Hello World**
```typescript
console.log("Hello, World!");
```

## **Variable Declaration**  

| Keyword  | Description                                     | Scope                 |
|----------|---------------------------------|----------------------|
| `var`    | Old way of declaring variables  | Function or global   |
| `let`    | Block-scoped variable           | Block scope         |
| `const`  | Constant, cannot be reassigned  | Block scope         |

---

## **Arrow Functions**  
Arrow functions provide a more concise syntax for defining functions.

### **Syntax:**
```typescript
const greet = (name: string): string => `Hello, ${name}!`;
console.log(greet("Bun"));
```

---

## **Template Literals (Backtick Strings)**  

### **Interpolation**
```typescript
let name = "Bun";
console.log(`Hello, ${name}!`);
```

### **Multi-line Strings**
```typescript
const message = `
Hello,
Welcome to Bun!
`;
console.log(message);
```

---

## **Arrays**  

An array is a collection of values.  

### **Syntax:**
```typescript
let numbers: number[] = [1, 2, 3, 4, 5];
console.log(numbers[0]); // Accessing first element
```

### **Spread operator with Arrays**
```typescript
let moreNumbers = [...numbers, 6, 7, 8];
console.log(moreNumbers);
```

---

## **Object Destructuring**  

### **Example:**
```typescript
const user = { name: "Alice", age: 25 };
const { name, age } = user;
console.log(name, age);
```

---

## **Loops**  

### **For Loop**
```typescript
for (let i = 0; i < 5; i++) {
  console.log(i);
}
```

### **While Loop**
```typescript
let count = 0;
while (count < 5) {
  console.log(count);
  count++;
}
```

### **Do-While Loop**
```typescript
let num = 0;
do {
  console.log(num);
  num++;
} while (num < 5);
```

---

## **Classes**  

Bun supports ES6 classes, allowing for object-oriented programming.

### **Example:**
```typescript
class Car {
  model: string;

  constructor(model: string) {
    this.model = model;
  }

  display(): void {
    console.log(`Car model: ${this.model}`);
  }
}

const myCar = new Car("Tesla");
myCar.display();
```

---

## **Bun’s Built-in HTTP Server**  

Unlike Node.js, Bun has a **simplified** HTTP server API.

### **Example:**
```typescript
import { serve } from "bun";

serve({
  port: 3000,
  fetch(req) {
    return new Response("Hello, World from Bun!");
  },
});

console.log("Server running at http://localhost:3000");
```

---

Bun is an **exciting alternative to Node.js**, optimized for speed and modern JavaScript/TypeScript development! 🚀

