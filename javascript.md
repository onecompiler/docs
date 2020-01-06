# Javascript Online Compiler

Write, Run & Share Javascript code online using OneCompiler's Javascript online compiler. It's one of the robust, feature-rich online compilers for Javascript language. Getting started with the OneCompiler's Javascript editor is easy and fast. The editor shows sample boilerplate code where you choose language as Javascript. OneCompiler also has reference programs, where you can look for the sample code to get started with.

# About Javascript

Javascript(JS) is a object-oriented programming language which adhere to ECMA Script Standards. Javascript is required to design the behaviour of the web pages.

# Key Features

* Open-source
* Just-in-time compiled language
* Embedded along with HTML and makes web pages alive
* Originally names as LiveScript.
* Executable in both browser and server which has Javascript engines like V8(chrome), SpiderMonkey(Firefox) etc.

# Syntax help

## variable declaration

|Keyword|Description|Scope|
|----|----|----|
|var| Var is used to declare variables(old way of declaring variables)| Function or global scope| 
|let| let is also used to declare variables(new way)|Global or block Scope|
|const|const is used to declare const values. Once the value is assigned it can not be modified|Global or block Scope|

## Arrays
An array is a collection of items or values. 

## Syntax

```javascript
let arrayName = [value1, value2,..etc];
// or
let arrayName = new Array("value1","value2",..etc);
```

## Example

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

## 1. With no argument

### Syntax

```javascript
() => expression
```

### Example

```javascript
const numbers = [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]
const squaresOfEvenNumbers = numbers.filter(ele => ele % 2 == 0)
                                    .map(ele => ele ** 2);
console.log(squaresOfEvenNumbers);
```
## Loops
### 1. If

IF is used to execute a block of code based on a condition. 

### Syntax

```javascript
if(condition){
    // code
}
```
### 2. If-Else

Else part is used to execute the block of code when the condition fails.

### Syntax
```javascript
if(condition){
    // code
} else {
    // code
}
```


### 3. Switch

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

While is also used to iterate a set of statements based on a condition. Usually while is preferred when number of ierations is not known in advance.

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

## Syntax
```javascript
class className {
  constructor() { ... } //Mandatory Class method
  method1() { ... }
  method2() { ... }
  ...
}
```

## Example
```javascript
class Mobile {
  constructor(model) {
    this.name = model;
  }
}

mbl = new Mobile("iPhone");
```
