# Class 5 Reading Notes!

1. What is CSS?
    - **Cascading Style Sheets**  
    - A Language for specifying how documents are presented to users, or how they are styled, laid out, etc.  

2. What is CSS used for?  
    - Very basic document text styling  
        - changing **color**  
        - changing **size**  
    - Create a layout  
        - convert a single column of text into a layout  
    - Animation  

3. CSS Syntax
    - Rule based language  
        - define rules by specifying groups of styles that should be applied to particular elements or groups of elements on your web page.  
        - Example
            ~~~
            h1 {  
                color: red;  
                font-size: 5em;  
            }
            ~~~
            1. CSS opens with selector  (h1)
            2. Then have a set of curly braces {}  
            3. Inside braces will be one or more declarations, in this case it refers to color and font size, whcih take the form of **property** and **value**.  
        - CSS Properties
            - have different allowable values, depending on which property is being specified.  
            - In the above example, we have properties of color and font size.  
        - CSS Values
            - Specify what properties should do.  
            - The values above use red and 5em, with respect to their intended properties.  
4. CSS Modules  
    - MDN  
        - [Backgrounds and Borders](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Backgrounds_and_Borders)  

5. How to Add CSS  
    - Three ways to add CSS  
        1. External Style Sheet  
        2. Internal Style Sheet  
        3. Inline Style Sheet  
    