# Code 201 Class 01 Reading Notes

These readings are important because it covers some of the more basic material of creating and codeing for a webpage. In order to better understand how websites work and interact between the server and client, and among HTML, CSS, JavaScript and the browser, it's best to understand the basics first.

## How the Web Works

Computers connected to the web are called clients and servers.
Clients are the typical web user's internet-connected devices (for example, your computer connected to your Wi-Fi, or your phone connected to your mobile network) and web-accessing software available on those devices (usually a web browser like Firefox or Chrome).
Servers are computers that store webpages, sites, or apps. When a client device wants to access a webpage, a copy of the webpage is downloaded from the server onto the client machine to be displayed in the user's web browser.

- Your internet connection: Allows you to send and receive data on the web. It's basically like the street between your house and the shop
- TCP/IP: Transmission Control Protocol and Internet Protocol are communication protocols that define how data should travel across the internet.
- DNS: Domain Name System is like an address book for websites.
- HTTP: Hypertext Transfer Protocol is an application protocol that defines a language for clients and servers to speak to each other.
- Component files: A website is made up of many different files, which are like the different parts of the goods you buy from the shop.

1. Code files: Websites are built primarily from HTML, CSS, and JavaScript, though you'll meet other technologies a bit later.
2. Assets: This is a collective name for all the other stuff that makes up a website, such as images, music, video, Word documents, and PDFs.

### So what happens?

When you type an address into the browser...

1. Browser go to DNS server and finds the **real** address the site lives on...
2. Browser sends HTTP message to server, requesting a copy be sent to the client. All of this data is sent using TCP/IP
3. Following server *approval*, server sends files to client.
4. Browser assembles data into small chunks that form the webpage.

### DNS Explained

Real web addresses aren't the nice, memorable strings you type into your address bar to find your favorite websites. They are special numbers that look like this: 63.245.215.20.

- Called in ***IP address***, this represents a unique location on the web.

To improve accessibility and memorability, **DNS** match the *typed* web address to the real server:  **IP adresses**.

## What will your Website look like?

1. What is it about?
2. What information are you presenting on it?
3. What does it look like?

**Start** with a *rough* skecth to outline key parts. Can use utilize web applications or just pen and paper.

### Choose Assetts

- ext
- Theme color
- Images
- Font

There are many resources available to use along with many styles. Outline your draft to incoroprate these design options in a way that produces your webpages' potential.

## JavaScript Basics

What is JavaScript?

- a powerful programming language that can add interactivity to a website.

**String**
This is a sequence of text known as a string. To signify that the value is a string, enclose it in single quote marks:

~~~bash
let myVariable = 'Bob';
~~~

**Number**
This is a number. Numbers don't have quotes around them:

~~~bash
let myVariable = 10;
~~~

**Variable**
Are containers that store value:

Use the *let* container to declare/store a value that can be used again:

~~~bash
let myVariable;
~~~

Use the *const* container to declare/store a value that is fixed:

~~~bash
const myVariable;
~~~

## Getting Started with HTML

An **attribute** is any extra information about an element, and is usually defined within the opening tags of that element.

~~~bash
<meta content="UTF-8>
~~~

Within the meta element, content diplays an *attribute* of UTF-8.

HTML displays content along a pattern of lines. Line-by-line, code is input started with the opening tag on the first line, which usually displays the doctype/HTML element. On each line, an element is placed to describe something that is suppose to be done. There are many types of element descriptors and most of them have opening and closing tags that can have content placed in between. For example:

~~~bash
<p>This is a paragrach</p>
~~~

The ***article*** HTML element represents a self-contained composition in a document, page, application, or site, which is intended to be independently distributable or reusable.

The ***section***  HTML element represents a generic standalone section of a document, which doesn't have a more specific semantic element to represent it. Sections should always have a heading, with very few exceptions.

Typical websites will include [element: !DOCTYPE HTML], [element: html] [element: meta], [element: link], [element: head], [element: header], [element: main], [element: body], and [element: footer]. Within each of these elements, other elements can be placed to further describe what's happening in that particular area of the webpage. With this happens, the elements are considered **nested** in their *parent* element, and are usually indented to visually communicate it.

**Metadata** is data that describes data. One of the most common is describes in an example above. In that example, the meta element has an attribute that communicates what type of languages it accepts, or undersatands. Their are many forms of metadata attributes. Some describe the way the content is suppose to adjust its' display to accomodate for user display size. Other metadata attributes can be specific and unique, such as Facebook and Twitters' icons.

## Designing a Website

The first step in designing a website is to determine what kind of content you want to display in it. Some common questions you should ask before desiging your website are:

1. What exactly do I want to accomplish?
2. How will a website help me reach my goals?
3. What needs to be done, and in what order, to reach my goals?
This *project ideation* is the necessary first step to creating your website goals.

One of the most important questions to ask in the examples above is *what exactly to I want to accomplish*?
If you own a business and want to connect your business to more people, creating a webpage would be a good idea. Start with an outline of all the important points your webpage is to accomplish setting your business up for greater success. Once you have a rough list, order that list into a heirarchy of importance, from *most important* to *least importance*.

## Semantics

Semantics refers to the meaning behind a piece of code. Elements, like the [element: h1], have a predisposition to how they are displayed. For instance, the [element: h1] default is a top level heading. You can use other elements to achieve the same sort of outcome an [element; h1] would produce with [element: span], but for ease and accessibility to the coder, it makes sense to use the [element: h1] for a top level header because that is what it is specifically designed to do. When using the [element: span], you would have to create attributes that level up to what an [element: h1] already does for you. In addition, most browsers are set to accept an [element: h1] with an appropriate stylesheet.

Other benefits of using semantic tags in HTML are:
-Search engines will consider its contents as important keywords to influence the page's search rankings.
-Screen readers can use it as a signpost to help visually impaired users navigate a page.
-Finding blocks of meaningful code is significantly easier than searching through endless [element: divs] with or without semantic or namespaced classes.
-Suggests to the developer the type of data that will be populated.
-Semantic naming mirrors proper custom element/component naming.

## What is JavaScript?

**JavaScript** is a scripting language that enables you to create dynamically updating content, control multimedia, animate images, and pretty much everything else. (Okay, not everything, but it is amazing what you can achieve with a few lines of JavaScript code.)

JavaScript is designed to read in order from top to bottom, making it very important to order your code correctly. A very common use of JavaScript is to dynamically modify HTML and CSS to update a user interface, via the Document Object Model API.

JavaScript is linked to your HTML page through an [element: script].

~~~bash
<script src="script.js" defer></script>
~~~

It is nested in the [element:head] along with your [element:meta] and CSS.

## Things I want to know more about
