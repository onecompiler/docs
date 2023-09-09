# Javascript Online Compiler

Write, Run & Share Javascript code online using OneCompiler's JS online compiler for free. It's one of the robust, feature-rich online compilers for Javascript language. Getting started with the OneCompiler's Javascript editor is easy and fast. The editor shows sample boilerplate code when you choose language as Javascript and start coding. 

# About Javascript

Javascript(JS) is a object-oriented programming language which adhere to ECMA Script Standards. Javascript is required to design the behaviour of the web pages.

# Key Features

* Open-source
* Just-in-time compiled language
* Embedded along with HTML and makes web pages alive
* Originally named as LiveScript.
* Executable in both browser and server which has Javascript engines like V8(chrome), SpiderMonkey(Firefox) etc.

# Syntax help

## STDIN Example

```javascript
var readline = require('readline');
var rl = readline.createInterface({
  input: process.stdin,
  output: process.stdout,
  terminal: false
});

rl.on('line', function(line){
    console.log("Hello, " + line);
});
```

## variable declaration

|Keyword|Description|Scope|
|----|----|----|
|var| Var is used to declare variables(old way of declaring variables)| Function or global scope|
|let| let is also used to declare variables(new way)|Global or block Scope|
|const|const is used to declare const values. Once the value is assigned, it can not be modified|Global or block Scope|

## Backtick Strings

### Interpolation
```javascript
let greetings = `Hello ${name}`
```
### Multi line Strings
```
const msg = `
hello
world!
`
```

## Arrays
An array is a collection of items or values. 

### Syntax:

```javascript
let arrayName = [value1, value2,..etc];
// or
let arrayName = new Array("value1","value2",..etc);
```

### Example:

```javascript
let mobiles = ["iPhone", "Samsung", "Pixel"];

// accessing an array
console.log(mobiles[0]);

// changing an array element
mobiles[3] = "Nokia";
```

## Arrow functions
Arrow Functions helps developers to write code in concise way, it’s introduced in ES6.
Arrow functions can be written in multiple ways. Below are couple of ways to use arrow function but it can be written in many other ways as well. 

### Syntax:

```javascript
() => expression
```

### Example:

```javascript
const numbers = [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]
const squaresOfEvenNumbers = numbers.filter(ele => ele % 2 == 0)
                                    .map(ele => ele ** 2);
console.log(squaresOfEvenNumbers);
```

## De-structuring

### Arrays
```javascript
let [firstName, lastName] = ['Foo', 'Bar']
```
### Objects
```javascript
let {firstName, lastName} = {
  firstName: 'Foo',
  lastName: 'Bar'
}
```
### rest(...) operator
```javascript
 const {
    title,
    firstName,
    lastName,
    ...rest
  } = record;
```
### Spread(...) operator
```javascript
//Object spread
const post = {
  ...options,
  type: "new"
}
//array spread
const users = [
  ...adminUsers,
  ...normalUsers
]
```
## Functions 
```javascript
function greetings({ name = 'Foo' } = {}) { //Defaulting name to Foo
  console.log(`Hello ${name}!`);
}
 
greet() // Hello Foo
greet({ name: 'Bar' }) // Hi Bar
```
## Loops
### 1. If:

IF is used to execute a block of code based on a condition. 

### Syntax

```javascript
if(condition){
    // code
}
```
### 2. If-Else:

Else part is used to execute the block of code when the condition fails.

### Syntax
```javascript
if(condition){
    // code
} else {
    // code
}
```

### 3. Switch:

Switch is used to replace nested If-Else statements.

### Syntax
```javascript
switch(condition){
    case 'value1' :
        //code
        [break;]
    case 'value2' :
        //code
        [break;]
    .......
    default :
        //code
        [break;]
}
```

### 4. For

For loop is used to iterate a set of statements based on a condition.

```javascript
for(Initialization; Condition; Increment/decrement){  
//code  
} 
```

### 5. While

While is also used to iterate a set of statements based on a condition. Usually while is preferred when number of iterations are not known in advance.

```javascript
while (condition) {  
  // code 
}  
```

### 6. Do-While
Do-while is also used to iterate a set of statements based on a condition. It is mostly used when you need to execute the statements atleast once.

```javascript
do {  
  // code 
} while (condition); 
```

## Classes
ES6 introduced classes along with OOPS concepts in JS. Class is similar to a function which you can think like kind of template which will get called when ever you initialize class.

## Syntax:
```javascript
class className {
  constructor() { ... } //Mandatory Class method
  method1() { ... }
  method2() { ... }
  ...
}
```

## Example:
```javascript
class Mobile {
  constructor(model) {
    this.name = model;
  }
}

mbl = new Mobile("iPhone");
```
