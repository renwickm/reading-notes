# Code 301 Class 1

## Readings: Introduction to React and Components

### Component-Based Architecture

1.What is a "component"?

> A component is a JavaScript class or function that optionally accepts input properties and returns a React element that describes how a section of the UI should appear. They are like functions for creating HTML elements.

2.What are the characteristics of a component?

-The two types of components are **Class** components and **Function** components.

3.What are the advantages of using component-based architecture?

-They serve similar purpose to JavaScript functions but work in isolation and return HTML.

### What is Props and How to Use it in React

1.What is "props" short for?

-Props are arguments passed into React components

2.How are props used in React?

-Because components and props are connected to creating HTML elements, props are used in React in a similar fashion to the way the attributes in HTML are used. To send props into a component, the same syntax as HTML attributes is what the component will be looking for.

3.What is the flow of props?

-React uses a unidirectional data flow. What this means is data can only travel one-way. In relation to props, or the data from the parent, data can only be passed down to the child of that prop, or parent.
