# Code 201 Class-06 Reading Notes 

## JavaScript Object Basics

### Objects

An object in JavaScript is most easily defined as a collection of related data and/or functionality.
//reference from mdn web docs//

It is another way we can store data with a lot of moving parts into a container which allows for better organization. 

### Advantages of Object literals

1.Objects' contents are written out as you are creating it
2.Transferring a series of related and structured data is more efficient to do because you can send data using one item instead of having to write out several items.
3.More efficient when working with arrays

### How to Object Literals differ from Arrays

An object is made up of properties that can, in itself, also be considered an object. Much like with arrays, objects are made up of many data, and there type can very. However, an array is a series of data, but one data point within the array cannot be considered an array. This is where objects and arrays differ. 

### When to use bracket notation instead of dot notation

If an object property name is defined at runtime then you can't use dot notation to access the value, but you can pass the name as a variable inside brackets.
// referenced from mdn web docs //

### What does This refer to in the code below and what is the advantage to using it.

~~~bash
const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}
~~~

*this.* is the object identifier where the code is being writtin inside of.  For instance, the *this.* from the code above refers to **dog**. From there, the code will search for objects tied to the end of the *this.* keyword ('spot', 2).


## Introduction to the DOM

### What is DOM

**Document Object Model (DOM)** is the data representation of the objects that comprise the structure and content of a document on the web. It is a programming interface for web documents that represents the page so that programs can change the document structure, style, and content. It also represents the document as nodes and objects; in that way, programming languages can interact with the page.
// reference from mdn web docs //

### What is the relationship between DOM and JS

You write your code in JS but in order to access the document and its elements, you need to use the DOM because JS utilizes it to reference web pages, HTML documents, SVG documents, and their component parts.