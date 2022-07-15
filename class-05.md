# Code 201 Class 05 Reading Notes

## Why this reading is important

HTML is your primary source for storing and/or writing your code. You can work CSS into your HTML file, but this can be less organized than building an external CSS file. Now we are getting more into CSS and I am looking forward to it because I like organization and developing ways to make something visually stand-out - which is was CSS is, in a way. 

## HTML Media

The **alt** attribute is beneficial and applies to images and videos. For those situations when an image can't be seen - maybe slow internet connection - the alt attribute identified in the image HTML will provide that text in its' place.

Some ways to improve an images accessibility are to add a description in HTML and use alt-text, which was brought up earlier. Items like this are helpful for people with reading or seeing dissabilities. 

The figure element remains independent from the main flow. If you were to move this element, the main flow would not be affected by it. One example of a good use for this is when providing captions. 

A *gif*, also known as Graphics Inerchange Format, supports simple animation, images and interlacing. 
An *svg*, also known as Scalable Vector Graphics, specifies contents of an image and are text files containing source code.

The best image type to display a screenshot would be the *png*, Portable Network Graphics, because there is not a lot of color data to interpret. 

## Learn CSS

**Background** can be described as an area that other things sit on top of, but can still be visible either by unused space around the content of simply removinig the content. 
**Foreground** would be the content in this scenario. But mainly foreground is just anything that stacks on top of something and is easily visible because it is in front. 

There are many options to invoke color into the webpage. You first want to identify the area that you are wanting to add color to. The first place I would start would be the body section in your HTML because it's easy and you cover the entire page. With the background-color property given to the body selector, you can add color values to your bodys background. Either specific colors like **red**, **green**, or **blue**, are used or you can make adjustments through the combination of these colors with the **rgb** property value.

When considering fonts, take into consideration things like font-color and how different colors can be harder to see/read, font-size for the same reason, font-family for a specific look but some browsers may not support the font-family you're looking for.

**font-size** defines how big or small you want the text, or font, to be.
**font-weight** sets how bold the text is.
**font-style** will turn on or off italic.

**letter-spacing** and **word-spacing** are two ways you can add space between characters such as letters or words. Utilize the appropriate element to apply the spacing you're looking to achieve. S