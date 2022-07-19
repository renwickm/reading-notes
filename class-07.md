# Code 201 Class-07 Reading Notes

## Domain Modeling

### Why do we need domains?

The sole purpose of domain modeling is to conceptualize or reduce problems in your code. With domain modeling, and in a domain model that is written and articulated well, you can verify and validate the understanding of a specific problem among various stakeholders.
// from https://github.com/codefellows/domain_modeling#domain-modeling //

## HTML Table Basics

### Why shouldn't you use tables for page layouts?

1.Layout tables reduce accessibility for visually impaired users.
2.Tables produce tag soup
3.Tables are not automatically responsive.
// referenced from mdn web docs //

### Semantic HTML elements used in an HTML table

1.(<td>)table cell(</td>)
2.(<tr>)table row(</tr>)
3.(<th>)table header(</th>)

## Introducing Constructors

### What is a constructor and what are some advantages to using it?

A constructor is a function called using the *new* keyword:
1.create a new object
2.bind *this* to the new object, so you can refer to *this* in your constructor code
3.run the code in the constructor
4.return the new object.

Start with a Capital letter:

~~~bash
function Person(name) {
  this.name = name;
  this.introduceSelf = function() {
    console.log(`Hi! I'm ${this.name}.`);
  }
}
~~~

To call **Person()** as a constructor, use **new**:

~~~bash
const salva = new Person('Salva');
salva.name;
salva.introduceSelf();

const frankie = new Person('Frankie');
frankie.name;
frankie.introduceSelf();
~~~

### How does *this* differ when used in an object literal versus when used in a constructor?

When you create more than one object from a single object definition, *this* is a lot more usefel. From the code example above:

*this* is first used to identify *name* and *introduceSelf*. The new object bind to *this* and is used for reference in your constructor code.

## Object Prototypes Using a Constructor

### Prototype and Inheritance

What prototype means to me is something that is being tested out for efficiancy. It is currently in a stage of development but needs some data points - or obersvable input - that can be used to help verify confidence in its' effective use. Sometimes prototypes don't make it through to Inheritance, which is like the adoption of something, some value that we are trying to test. When you get to the stage of Inheritance, the values have been declared as useful and working efficiently, where we are confident in the parameters of what we intend it to do. 

Thinking back on previous work experience, I remember working with experienced technicians in the field of mechanics. Many of them had different ways of doing this same thing, both ways worked efficiently and got the job done. Some were faster than others. I was benefited through knowledge they had already worked out, some of which took many years to do so. In that light, you could say that what started out for them as a working prototype that developed condfidence and trust to be used again, and that trust is easily inherited onto others, as myself. The same kind of applications can be observed in code and software developement. While you may start out with a version of code, that version is inherited and often upgraded, and the cycle continues. 

// references mdn web docs //