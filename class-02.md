# Code 201 Class 02 Reading Notes

## Why this Reading is Important

The prior reading assignment was built off of a basic understanding of 'how it all works' kind of approach. This reading jumps into more of the same, identifying HTML, CSS, and JavaScript common principles that are at the core of each respective language. They are important because they will be necessary to understand as software developers as the building blocks for any code we procure. 

## Introduction to HTML

Semantics are important because they are what give our code meaning. Every piece of code is tied to an element that holds a specific value or meaning. That value communicates what the browser should expect, given the respective element, and then display that accordingly. Without these respective semantics, the computer would not know how to display the coding because it would not be communicated. Everything that we code has meaning.

There are 6 different Heading levels to use. The first level heading is the biggest, scaling down a size to the last, 6, level heading. 

~~~text
# h1
## h2
### h3
#### h4
##### h5
###### h6
~~~

You may need to use a function that allows you to organize your HTML output in a specialized way. Special formating such as dates, math or chemical equations require portions to be placed either up or down a position, respectively. We use the element **sup** and **sub** to handle these special circumstances. Ex:

~~~text
<p>The date is June 26<sup>the</sup></p>
<p>C<sub>8</sub>H<sub>10</sub>N<sub>4</sub>O<sub>2</sub></p>
~~~

~~~bash
<p>The date is June 26<sup>the</sup></p>
<p>C<sub>8</sub>H<sub>10</sub>N<sub>4</sub>O<sub>2</sub></p>
~~~

When using the <abbr> element, you must use a <title> attribute to provide the full expansion of the term.

## Learn CSS

You can apply CSS to HTML in three different ways:

1. External: place a link element within the head of your HTML that will corresponde to another workspace page where you can impliment your CSS.
2. Internal: place a script element within the head of your HTML and apply your CSS within that area/spcace of the HTML page
3. Inline: directly place CSS content within elements' opening tag.

The CSS declaration is found within the brackets of whatever selector it is assigned to . Within the declaration you will find properties with an assigned value that are separated by a semicolon.

## Learn JS

A **string** is a data type that encloses test within single quotes.

An **operator** is a symbol used in JavaScript that produces results stemming from two values or variables. These symbols are commonly mathematical such as:

1. *Addition* use the + symbol;
2. *Subtraction*, *Multiplication*, *Division*, use the -, *, / symbolse respectively;
3. *Assignment*, use the = symbol;
4. *Strict equality*, use the = symbol times 3, or ===;

**Functions** are a way of packaging functionality that you wish to reuse.

- Webpages are only necessary because people use them to find answers. In a way, these webpages are the pathway to finding the answers to whatever 'real-world-problem' people are facing. In order to provide a better experience for the user, *functions* will display output based on the input from the user. If the userInput is this way, the functionOutput is this way. If the userInput is the other way, the functionOutput is the other way. 

- A simple 'real-world-probelm' based of some of the operators listed above would be any form of calculation. If the user needed to know the output from a mathematical equation, a function could solve this for them.

## Making Decisions in your Code - Conditionals

An if statement chacks a ***Condition*** and if it evaluates to ***true***, then the code block will execute.

If you have more than one ***truth*** that could be examined by the ***condition***, the **else if** statement would be utilized and each additional condtion would need to be recognized and recorder respectively.

### Comparison Operators

1. === and !==; test if one value is identical to, or not identical to, another;
2. < and >; test if one value is less than or greater than another;
3. <= and >=; test if one value is less than or equal to, or greater than or equal to, another;

### Logical Operators

1. && - AND; this allows the user to chain together two or more expressions so that *all* have to individually equate to *true* for the entirety of the expression to return *true*.
2. || - OR; this allows the user to chain together two or more expressions so that *one or more* have to individually equate to *true* for the entirety of the expression to return *true*. 