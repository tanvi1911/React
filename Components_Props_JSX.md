## Introduction to React

React is a declarative and efficient JavaScript library for creating interactive UIs. It allows you to build reusable UI components and efficiently update and render them as the data changes. React's component-based architecture promotes reusability, separation of concerns, and a modular approach to building user interfaces.

## Components

In React, components are the building blocks of the UI. They encapsulate reusable parts of the user interface and can be composed together to create complex UIs. React components can be divided into two types:

- **Functional Components**: These are JavaScript functions that receive props (input data) and return JSX (descriptive markup). Functional components are simpler and used for presentational purposes.

- **Class Components**: These are ES6 classes that extend the `React.Component` class. Class components have additional features, such as lifecycle methods, state management, and more. They are used for complex UI logic and maintaining state.

## Props

Props (short for properties) are inputs to React components. They allow you to pass data from a parent component to a child component. Props are immutable, meaning they cannot be modified by the child component. To access props in a functional component, you can use the function's arguments. In a class component, props are accessed via the `this.props` object.

## JSX (JavaScript XML)

JSX is a syntax extension for JavaScript that allows you to write HTML-like code within JavaScript. It provides a concise and familiar way to describe the structure and content of React components. JSX is not mandatory, but it greatly enhances the readability and maintainability of React code.

JSX elements are represented using angle brackets, similar to HTML tags. Here's an example of JSX:

```jsx
function Welcome(props) {
  return <h1>Hello, {props.name}!</h1>;
}
