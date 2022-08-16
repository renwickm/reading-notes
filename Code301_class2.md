# Code 301 Class 2 Reading Notes

## React Lifecycle

1. based off the diagram, what happes first, the 'render' or the 'componentDidMount'?

  -The `render` happens prior to the `componentDidMount`

2.What is the very first thing to happen in the lifecyle of React?

  -The constructer is mounted

3.Put the following thins in the order they happen: 

  1.`constructor`
  2.`render`
  3.`react updates`
  4.`componentDidMount`
  5.`componentWillUnmount`

4.What does `componentDidMount` do?

  -After a component is rendered and already placed in the DOM, `componentDidMount` allows us to execute the React code.

## React State Vs Props

1.What types of things can you pass in the props?

  -not sure but I think this is getting at different data types or attributes. In React, props are considered attributes so I would think that what gets passed through a prop are attributes. 

2.What is the big difference between props and state?

  -props are you to pass data and the state is a local storage.

3.When do we re-render our application?

  -When there is a change in the state or props, it will need to be updated. A re-render occurs when an update is needed or executed.

4.What are some examples of things that we could store in state?

  -We could store different data types such as ***strings***, ***numbers***, or ***objects***.