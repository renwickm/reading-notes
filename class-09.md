# Code 201 Class 09 Reading Notes

## HTML Form

### Your First Web Form

1.Why are forms so important in web development?

Forms are one way in which a webpage interacts with users, and it's a pretty common one. Most of us have had to fill out information for something and it is very useful being able to do those things on the web instead of having to use a handout. This makes the process a little more effiecent and less time-consuming, and it creates additional options for people when considering location - with the use of forms on webpages, your current location is not a factor in determining your capability or plan to giving that information. All of it can be done online, so they are very useful to utilize on your webpage.

2.When designing a form, what are some key things to keep in mind when it comes to user experience?

One thing to keep in mind when deciding on the concept of your form and how to best translate a quality user experience(UX) into it, it to keep it simple. Write a mock-up beforehand and try to identify key areas that are essential to the form. If there are any areas, including key areas of necessary information, are there ways to condense that information. Trying to elaborate on a particular subject manner can be difficult to describe without the use of words, so finding a way to condense your wording - or the way you elaborate - is a very good concept to follow because it helps get others to the root of the subject matter - if you can condense an elaborate idea well - with less effort. 

### Hot To Structure A Web Form

3.List 5 form elements and explain their importance

- The `form` element formally defines a form and attributes that determine the form's behavior.
- The `fieldset` elementis a conveniant way to create groups of widgets that share the same purpose, for styling and semantic purposes. Also like an article section used in other HTML elements.
- The `legend` is an element that can be utitlized with a `fieldset` element that works as label for that `fieldset`.
- The `label` element is the formal way to define a label for an HTML form widget.
- The `input` is an element that provides key information to parent elements about the acceptable content that is allowed to be passed through it.

## Learn JS

## Introduction to Events

1.How would you describe events to a non-technical friend?

Events are any particular action that the computer takes when filing through your code. For example, if your code places an action for the user to provide information to a section of a form that was inproperly filled out, the event would trigger. That's just one example and there are many events happening on the webpage. 

2.When using the `addEventListener()` method, what 2 arguments will you need to provide?
  1.The name of the event we want to register this handler for
  2.The code that comprises the handler function we want to run in response to it.

3.Describe the event object. Why is the target within the event object useful?

One way to think of event object is a value. These values are automatically passed to event handlers to provide extra features and information based on the content of the value theyr're providing. 

4.What is the difference between event bubbling and event capturing?

These are described as phases in how the browser handles events targeted at nested elements. In **Bubbling**, the browser checks to see if the direct parent of the clicked element has a `click` event handler registered on it for the bublling pahse, and runs it if so. In **Capturing**, the browser checks to see if the element's outer-most ancestor, `html` has a `click` event handler registered on it for the capturing phase, and runs it if so. The differenece between the two is more on where they reference the `click` event handler.