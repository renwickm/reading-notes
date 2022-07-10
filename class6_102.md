# Class 6 Reading Notes!

## JavaScript

1. What is JavaScript

    - A lightweight, interpreted, or just-in-time compiled programming language with first-class functions.

    - Prototype based, multi-paradigm, single-threaded, dynamic language, supporting object-oriented, imperative, and declarative styles.  

    - Standards for JS

        1. [ECMAScript Language Specification](https://tc39.es/ecma262/)

        2. [ECMAScript Internationaliztion API specification](https://tc39.es/ecma402/)  

2. Tutorials

    1. Beginners

        - [Learning Area JavaScript topic](https://developer.mozilla.org/en-US/docs/Learn/JavaScript)
    
    2. Intermediate

        - [JavaScript guide](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide)

    3. Advanced

        - [Strict mode](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Strict_mode)

3. JavaScript Variables

    - 4 ways to Declare a JavaScript Variable:  
        1. Using var  
        2. Using let  
        3. Using const  
        4. Using nothing

    - What are Variables?  
        - Cotainers for storing data (storing data values).
        - Example:  

        ~~~
        var x = 5;
        var y = 6;
        var z = x + y;
        ~~~

        ~~~
        let x = 5;
        let y = 6
        let z = x + y;
        ~~~
    
    - When to use JavaScript var?

        - var keyword used in all JS code from 1995 to 2015.  

        - let and const keywords added to JS in 2015.  

    - When to use JS const?

        - As a general rule, always declare variables with **const**.  

        - When you think the value of a variable can change, use **let**.  

            >example:
                const price1 = 5;
                const price2 = 6;
                let total = price1 + price2;
        
4. JavaScript Identifiers

    - All **variables** must be **identified** with **unique names**.  

    - These unique names are called **identifiers**.  

        - Can be short, like *x* and *y* or more descriptive like *age*, *sum*, or *totalVolume*.  

    - General rules:  

        1. Names can contain letters, digits, underscores, and dollar signs.
        2. Names must begin with a letter.  
        3. Names can also begin with $ and _.
        4. Names are case sensitive (y and Y are different variables).
        5. Reserved words (like JavaScript keywords) cannot be used as names.

5. The Assignment Operator

    - The "assignment" operator is the equal sign (=), but not an "equal to" operator. 

    - Different from algebra:

        x = x + 5

        - This does not make sense in algebra but makes perfect sense in JS.  

        -In JS, it assigns the value of x + 5 to x.  

        >Note: the "equal to" operator is written like == in JS.

    