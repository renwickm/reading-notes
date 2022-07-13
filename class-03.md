# Code 201 Class 03 Reading Notes

## Learn HTML

### Ordered vs Unordered List

- Unordered lists should be used when the items that are being listed in your HTML section are not part of a sequence of numbers, or when the flow from one list item to the next list item will not be affected if you were to rearrange their sequencing. Unordered lists are usually represented with a square, disc, bullet, and some interfaces' allow for a triangle sign to be used. 

- In order to change your bullet style-type, you will need to communicate that in CSS because the bullet style is not defined in HTML. You will use the *list-style-type* property to accomplish this.

- When deciding which kind of list you should use, first aske yourself whether or not the sequence holds means. For instance, in one scenario you have a list of grocerie items and in the other you have a manual for putting together an uninstalled desk. It would make sense to utilize an unordered list for the groceries because it doesn't matter what order they are in, they just need to be documented. As for your manual, if you removed a reordered any part in that list, the outcome would be meaningful because you've changed the order in sequence of things to be done. In this case an ordered list would be used. 

- An Ordered list utilizes numbers or letters that are used symbolically in a sequential way. One way to change a number to a letter, for instance, is by using an inline type attribute:

~~~bash
<ol type="a">
~~~

This will output a sequence of a's, starting with 'a,' followed by 'aa,' and so on. 

- You can also change the number with the start identifier:

~~~bash
<ol start="6">
~~~

This tells HTML to start the ordering at '6' and continue from there.

## Learn CSS

### Margin and Padding

A long, long time ago, in a land far away, lived a box with four sections and story to it's name. The first was called Margin who lived on the edge; maintiained the perimeter, and valued the pledge. Then there was border, who outlined the sides. When Margin went missing, border you'd find. Next there was padding, that cushioned the center. Built to be bent, providing margins' inner. The last, you will see, is the text mystery. Provided to you, developed by me. 

The four parts of the box model:

1. Content-box: this is the innermost area of the container that provides the content/text of the box.
2. Padding-box: this is the seconed layer of the box that is white space.
3. Border-box: this is third layer and wraps the content and any white space/padding.
4. Margin-box: this is the outermost layer of the container and wraps all the three previous layers and white space between the box and any content.

## Learn JS

### Arrays

You can store multiple different data types in an array:

1. Strings
2. Numbers
3. Objects
4. Others...

~~~bash
 const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];
 ~~~

 The array listed above is a valid array. Arrays are multidimentional that can store values of many data types at once and can store multiple data type groupings on one array. The people array can access different points of the array using many different statements:

 1. *for...of*: the statement accesses every item in the array.
 2. *pop()*: this statement removes the last item in the array.
 3. *indexOf()*: this statement finds specified items within the array using a numeric number that starts with ***0***, this first item in the array.
 4. Many others....

 ### Operators

 #### Shorthand Operators for assignment

 1. Addition: x += f(), means that x = x + f(); 
 2. Subtraction: x -= f(), means that x = x - f();
 3. Remainder: x %= f(), means that x = x % f();
 4. Left Shift: x <<= f(), means that x = x << f();
 5. Exponentiation: x **= f(), means that x = x** f();

 Explain the result of this code:

 ~~~bash
  let a = 10;
 let b = 'dog';
 let c = false;

 // evaluate this
 (a + c) + b;
 ~~~

### Conditional Statements

One real-world example of when a conditional stamement should be used is for granting access, such as a password. The *if...else* statement is perfect for this because it provides options for answers based on user input. If the user inputs the correct password, the statement is true and the code with run. If the user inputs some other input, a different code will run. 

### Loops

Loops are useful when you want the ability to repeat code a number of times without having to right out that code a number of times. They are more efficient and less time consuming. A good example of when a loop would be appropriate would be like the password example above. But this time, the password only allows a certain number of attempts before the action results in termination. By inputing the correct password you proceed. By inputing the incorrect password the code loops back around and trys again and either the correct password is given or you run out of attempts and the loop is terminated.

 ### Things I would like to know more about

 Expressions and operators - it is hard to understand how we are to use these in real-worl applications from the readings. 