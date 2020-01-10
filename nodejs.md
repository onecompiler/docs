# NodeJS Online Compiler

Write, Run & Share NodeJS code online using OneCompiler's NodeJS online compiler. It's one of the robust, feature-rich online compilers for NodeJS language,running on the latest LTS version NodeJS 12.14.0. Getting started with the OneCompiler's NodeJS editor is easy and fast. The editor shows sample boilerplate code where you choose language as NodeJS. OneCompiler also has reference programs, where you can look for the sample code and start learning. You can provide the dependencies in `package.json`.

# About NodeJS

Node.js is a free and open-source server environment. Node.js is very popular in recent times and a large number of companies like Microsoft, Paypal, Uber, Yahoo, General Electric and many others are using Node.js.

## Key features

* Built on `Google chrome's javascript engine V8` and is pretty fast.
* Node.js was developed by Ryan Dahl in 2009.
* Server-side platform for building fast and scalable applications.
* Node.js is `Asynchronous`, `event-driven` and works on `single-thread model` thus eliminating the dis-advantages of multi-thread model.
* Supports various platforms like Windows, Linux, MacOS etc.
* Provides rich library of java script modules which simplifies the development efforts.
* Released under MIT license.

## Express Framework

Express is one of the most popular web application framework in the NodeJS echosystem.

* Pretty fast
* Minimalist
* Unopinionated
* Very flexible

## How to install express

```sh
npm install express
```

# Syntax help

## Hello World server example

```javascript
const express = require('express');
const app = express();

app.set('port', (process.env.PORT || config.port));

app.get('/', (req, res) => res.send('Hello World!'));

app.listen(app.get('port'), () => console.log(`Server started on ${app.get('port')} port`))
```

## Basic routing

```javascript
//GET
app.get('/', function (req, res) {
  res.send('Hello World!')
})

//POST 
app.post('/', function (req, res) {
  res.send('POST request. body:', req.body)
})

//DELETE
app.delete('/:id', function (req, res) {
  res.send('DELETE request for id:'. req.params.id)
})
```
