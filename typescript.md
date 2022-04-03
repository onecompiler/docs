# Typescript Online Compiler

Write, Run & Share Typescript code online using OneCompiler's Typescript online compiler for free. It's one of the robust, feature-rich online compilers for Typescript language. Getting started with the OneCompiler's Typescript editor is easy and fast. The editor shows sample boilerplate code when you choose language as Typescript and start coding. 

# About Typescript

Typescript(JS) is a strongly typed programming language that builds on JavaScript, developed and maintained by Microsoft.

# Key Features

* Superset of Javascript
* portable
* Strong static typing
* supports OOPS
* Language extension to ECMAScript 6 with other features like Type annotations and compile-time type checking, Type inference and Type erasure, Interfaces, Enumerated types, Generics, Namespaces, Tuples
* .ts extension

# Syntax help

## variable declaration

|Keyword|Description|Scope|
|----|----|----|
|var| Var is used to declare variables(old way of declaring variables)| Function or global scope|
|let| let is also used to declare variables(new way)|Global or block Scope|
|const|const is used to declare const values. Once the value is assigned it can not be modified|Global or block Scope|

## Operators

|Operator|Description|
|----|----|
|`??`|nullish coalescing|
|`?.`|optional chaining|
|`!`|null assertion|
|`&&=`| used to assign value only if current value is truthy|
|`\|\|=`| used to assign value only if current value is falsy|
|`??=`|used to assign value if current value is null or undefined|
 
## Loops
### 1. If:

IF is used to execute a block of code based on a condition. 

### Syntax

```js
if(condition){
    // code
}
```
### 2. If-Else:

Else part is used to execute the block of code when the condition fails.

### Syntax
```js
if(condition){
    // code
} else {
    // code
}
```

### 3. Switch:

Switch is used to replace nested If-Else statements.

### Syntax
```js
switch(condition){
    case 'value1' :
        //code
        break;
    case 'value2' :
        //code
        break;
    .......
    default :
        //code
        break;
}
```

### 4. For

For loop is used to iterate a set of statements based on a condition.

```js
for(Initialization; Condition; Increment/decrement){  
//code  
} 

let arr = [1, 2, 3, 4, 5];
for (let ele of arr) {
 // code
}

for (let index in arr) {
//code
}
```

### 5. While

While is also used to iterate a set of statements based on a condition. Usually while is preferred when number of iterations are not known in advance.

```js
while (condition) {  
  // code 
}  
```

### 6. Do-While
Do-while is also used to iterate a set of statements based on a condition. It is mostly used when you need to execute the statements atleast once.

```js
do {  
  // code 
} while (condition); 
```
## Arrow functions
Arrow Functions helps developers to write code in concise way, it’s introduced in ES6.
Arrow functions can be written in multiple ways. Below are couple of ways to use arrow function but it can be written in many other ways as well. 

### Syntax:

```js
() => expression
```

### Example:

```js
const numbers = [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]
const squaresOfEvenNumbers = numbers.filter(ele => ele % 2 == 0)
                                    .map(ele => ele ** 2);
console.log(squaresOfEvenNumbers);
```
## Function Overloading

Typescript provides function overloading where multiple functions with the same name but different parameter types and return type is possible. But, the number of parameters should be the same.

```js
function Addition(a:string, b:string):string;

function Addition(a:number, b:number): number;

function Addition(a: any, b:any): any {
    return a + b;
}
Addition("Hello ","foo"); // outputs Hello foo
Addition(2,3); //outpus 5
```