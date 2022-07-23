# Code 201 Class 10 Reading Notes

## Debugging

### What Went Wrong? Troubleshooting JavaScript

1.Name some key differences between a **Syntax Error** and a **Logic Error**.

A *syntax error* refers to an error in spelling. This will cause the program to stop working or even not run at all. They are usually easy to fix.

A *logic error* is an error in your actuall code. The syntax is not the problem with your code, no spelling errors. This is or can be harder to fix because there usually isn't a message to direct you to the source of the problem.

2.List a few types of errors that you have encountered in past lab assignments and explain how you were able to correct them.

One of the more common error messages I've seen on my projects is *type error: this is not a function*. It is very useful to see where these error messages are originating from, as it directs you straight to the error and makes it easy to track down. Sometimes these error messages are easy to fix but if it's an error in logic, that means that your not tying your code together appropriately, and that is a challenge to fix. 

3.How will this topic conitnue to influence your long term goals?

We are all students of software development and will continue to be, even after landing our first job onto our dream job. The tools we acquire to do our jobs easier and better will be most important as the expectation will be an ambition of perfection without the achievement of it. We should expect to make errors or mistakes going forward and tools, such as the debugging tool, will be very helpful in identifying those mistakes. 

### The JavaScript Debugger

1.How would you describe the JavaScript Debugger tool and how it works to someone just starting out in software development?

On your browser, find the inspector tab and open it. For example, for Chrome you would right click on the webpage and find the inspector tab at the bottom of the list. This will open up a section to the right that will illustrate the webpages coding. Along with many useful tools, one specific to this is the JavaSctipt debugger. Search for the source tab in the inspector window. This will pull up the section of the webpage that JavaScript is working on. Here, you can play around, add in functions, variables, etc. and see how or even if it will affect the page itself. No need to worry, these changes won't directly effect the page, as you can't save changes you make from here and you don't have the rights. But it does allow you to play around and see where fixes or updates can be made without having to switch back and forth between your text editor and live server link.

2.Define what a breakpoint is.

A *breakpoint* as a debugging skill you can utilize within your debuggin tool that allows you to set points in your code to communicate that you want to stop the execution of the code so you can examine it more thoroughly. This is useful because you can break sections of your JavaScript down into smaller portions and pinpoint where problems, if any, are occuring without having to run through the full list of code.

3.What is the call stack?

The *call stack* is a section in the debugging tool that outlines what code JavaScript is running or executed to get to the current line. 