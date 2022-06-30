# My Reading Notes: JavaScript Programming

## Control Flow

* What is control flow?

        - The order in which the computer executes statements in a script.

        - Code runs in order, from the first line to the last line, but frequently can run across the structures that change the **control flow**, such as *conditionals* and *loops*.  

  * Example:

    ~~~
    if (field==emtpy){
        promptUser();
    } else {
        submitForm();
    }
    ~~~

    * A typical script in JS or PHP includes  many control structures:
        1. Conditionals
        2. Loops
        3. Functions

## JavaScript Functions

'''text
    function myFunction (p1, p2){
        return p1 * p2;  // The function returns the product of p1 and p2
    }
'''
    * JS Function Syntax
        -Defined with the *function* keyword, followed by a **name**, followed by **()**.
        -Names can contain letters, digits, underscores, and dollar signs (same rules apply as variables).
        -The **()** may include parameter names separated by commas: **(parameter1, parameter2,..)** .
        -The code to be executed, by the function, is placed inside curly brackets: **{}** .
'''text
    function name(parameter1, parameter2, parameter3){
        // code to be executed
    }
'''

## JavaScript Operators

'''text
    let x = 5;  // assign the value 5 to x
    let y = 2;  //assign the value 2 to y
    let z = x + y;  // assign the value 7 to z (5 + 2)
'''