# React online compiler

Write, Run & Share React code online using OneCompiler's React online compiler for free. It’s one of the simplest yet powerful React playgrounds running on the latest React version 18. Getting started with OneCompiler’s React editor is easy and fast. The editor shows sample boilerplate code when you choose React as the language and start coding.

# About React

React is a popular open-source JavaScript library developed by Facebook for building user interfaces, especially for single-page applications. It allows developers to build reusable UI components and manage application state effectively using a component-based architecture. React uses a virtual DOM to efficiently update and render components.

# Sample Code

The following is a sample React program that renders a greeting message:

```jsx
import React from "react";
import ReactDOM from "react-dom/client";

function App() {
  const [name, setName] = React.useState("");

  return (
    <div>
      <h1>Hello, {name || "World"}!</h1>
      <input
        type="text"
        placeholder="Enter your name"
        onChange={(e) => setName(e.target.value)}
      />
    </div>
  );
}

const root = ReactDOM.createRoot(document.getElementById("root"));
root.render(<App />);
```

# React Basics

## JSX

JSX is a syntax extension for JavaScript that looks similar to HTML. It is used to describe what the UI should look like.

```jsx
const element = <h1>Hello, OneCompiler!</h1>;
```

## Components

Components are the building blocks of a React application.

### Function Component

```jsx
function Welcome(props) {
  return <h1>Hello, {props.name}</h1>;
}
```

### Class Component

```jsx
class Welcome extends React.Component {
  render() {
    return <h1>Hello, {this.props.name}</h1>;
  }
}
```

## Props

Props are read-only attributes used to pass data from parent to child components.

```jsx
function Greeting(props) {
  return <p>Hello, {props.user}!</p>;
}
```

## State

State allows components to create and manage internal data that affects rendering.

```jsx
function Counter() {
  const [count, setCount] = React.useState(0);

  return (
    <div>
      <p>Count: {count}</p>
      <button onClick={() => setCount(count + 1)}>Increment</button>
    </div>
  );
}
```

## Handling Events

```jsx
function ClickButton() {
  const handleClick = () => alert("Button clicked!");

  return <button onClick={handleClick}>Click Me</button>;
}
```

## Conditional Rendering

```jsx
function Greeting({ isLoggedIn }) {
  return isLoggedIn ? <p>Welcome back!</p> : <p>Please sign in.</p>;
}
```

## Lists and Keys

```jsx
const items = ["Apple", "Banana", "Cherry"];

function ItemList() {
  return (
    <ul>
      {items.map((item, index) => (
        <li key={index}>{item}</li>
      ))}
    </ul>
  );
}
```

---

This guide provides a quick reference to React programming concepts. Start coding in React using OneCompiler’s React online compiler today!
