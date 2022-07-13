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

