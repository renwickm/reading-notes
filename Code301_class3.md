# Code 301 Class 3 Reading Notes

## React Docs - lists and keys

1.What does .map() return?

 -.map() returns a function that returns the arguments inside its' parameters.

2.If I want to loop through an array and display each value in JSX, how do I do that in React?

 -You would want to use .forEach() because this returns a function that does not return anything but the contents of whatever array you are calling on.

3.Each list item needs a unique ___.

  -`key`

4.What is the purpose of a key?

  -The purpose of a `key` in React is to identify which items have changed, are added, or are removed.

## The Spread Operator

1.What is the spread operator?

  -Syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function's arguments.

2.List 4 things that the spread operator can do.

  -Copying an array
  -Concatenating or combining arrays
  -Using Math Functions
  -Using an array as arguments
  -Adding an item to a list
  -Adding to state in React
  -Combining objects
  Converting NodeList to an array

3.Give an example of using the spread operator to combine two arrays.

>
const fruits = ['🍏','🍊','🍌','🍉','🍍']
const moreFruits = [...fruits];
console.log(moreFruits) // Array(5) [ "🍏", "🍊", "🍌", "🍉", "🍍" ]
fruits[0] = '🍑'
console.log(...[...fruits,'...',...moreFruits]) //  🍑 🍊 🍌 🍉 🍍 ... 🍏 🍊 🍌 🍉 🍍

4.Giva an example of using the spread operator to add a new item to an array.

>
const fewFruit = ['🍏','🍊','🍌']
const fewMoreFruit = ['🍉', '🍍', ...fewFruit]
console.log(fewMoreFruit) //  Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌" ]

5.Give an example of using the spread operator to combine two objects into one.

>
const objectOne = {hello: "🤪"}
const objectTwo = {world: "🐻"}
const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }
const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}
objectFour.laugh() // 😂😂😂😂😂

## How to Pass Functions Between Components

1. In the vidoe, what is the first step that the developer does to pass functions between components?

  -created an arrow function called increment

2.In your own words, that does `increment` function do?

  -`increment` function calls a variable named `ppl` that `map()`'s through the people.array and grabs the `state` of the value for name. If the `name` value is grabbed, the `count` is incremented.

3.How can you pass a method from a parent component into a child component?

  -You need to add a reference to the method you are trying to invoke from the parent component in the child component with `this.` For the example in the video, it would be `this.increment`

4.How does the child component invoke a method that was passed to it from a parent component?
  
  -When you want to invoke a method on the child component, the parent component need to reference the child component within the method being invoked. In the video, this worked with `this.props.name`
  