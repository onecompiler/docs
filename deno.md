# **Deno Online Compiler**  

Write, Run & Share Deno code online using OneCompiler's Deno online compiler for free. It's a modern, secure, and feature-rich runtime for JavaScript and TypeScript. Getting started with OneCompiler's Deno editor is easy and fast. The editor shows sample boilerplate code when you choose Deno as the language and start coding.  

---

# **About Deno**  

**Deno** is a secure runtime for JavaScript and TypeScript, built on V8 and Rust. It is designed by the creator of Node.js to improve upon its shortcomings, offering modern features with better security and developer experience.

---

# **Key Features**  

- **Secure by default**: No file, network, or environment access unless explicitly granted.  
- **Built-in TypeScript support**: No need for a separate compiler.  
- **Uses modern ES modules**: No need for `package.json` or `node_modules`.  
- **Ships with a built-in formatter, linter, and test runner**.  
- **Supports Web APIs**: Similar to browsers, Deno includes APIs like `fetch()`.  

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
console.log(greet("Deno"));
```

---

## **Template Literals (Backtick Strings)**  

### **Interpolation**
```typescript
let name = "Deno";
console.log(`Hello, ${name}!`);
```

### **Multi-line Strings**
```typescript
const message = `
Hello,
Welcome to Deno!
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

Deno supports ES6 classes, allowing for object-oriented programming.

### **Example:**
```typescript
class Car {
  model: string;
  constructor(model: string) {
    this.model = model;
  }
  showModel() {
    console.log(`Car model: ${this.model}`);
  }
}

const myCar = new Car("Tesla Model S");
myCar.showModel();
```

---

Deno is a modern and secure alternative to Node.js, offering built-in TypeScript support and a more streamlined developer experience. With its security-first approach and native ES module support, it is a great choice for modern JavaScript and TypeScript applications.

