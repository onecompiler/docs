# EJS online compiler

Write, Run & Share EJS templates online using OneCompiler’s EJS online compiler for free. It’s a minimal yet powerful online playground for rendering dynamic HTML using Embedded JavaScript (EJS). Getting started with OneCompiler’s EJS editor is quick and easy. You get a sample boilerplate EJS code with every new session.

# About EJS

EJS (Embedded JavaScript templating) is a simple templating language that lets you generate HTML markup with plain JavaScript. It is commonly used in Node.js applications, especially with Express, to render views on the server side.

EJS syntax allows embedding JavaScript logic directly within HTML using `<% %>` delimiters.

# Sample Code

The following is a sample EJS template that displays a personalized greeting:

```ejs
<%
 let message = 'Hello, World!'
%>
<%= message %>
```

# Syntax Basics

## Output Data

* `<%= %>` — Outputs the value into the template (escaped)
* `<%- %>` — Outputs unescaped HTML

```ejs
<p>Hello, <%= user.name %>!</p>
<%- include('footer') %>
```

## Control Flow

* `<% %>` — Executes JavaScript logic without output

```ejs
<% if (user.isLoggedIn) { %>
  <p>Welcome, <%= user.name %>!</p>
<% } else { %>
  <p>Please log in.</p>
<% } %>
```

## Loops

```ejs
<ul>
<% items.forEach(function(item) { %>
  <li><%= item %></li>
<% }); %>
</ul>
```

## Partials (Includes)

```ejs
<%- include('header') %>
<main>
  Content goes here
</main>
<%- include('footer') %>
```

---

This guide provides a quick reference to EJS templating syntax and usage. Start writing and rendering EJS code with OneCompiler’s EJS online compiler today!
