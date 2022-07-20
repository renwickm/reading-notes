# Code 201 Class 08 Reading Notes

## CSS Layout

### CSS - Flexbox

1.**Flexbox is designed for one-dimensional content. Explain what this means.**

Flexbox is designed for one-demensional content because it excels at taking a bunch of items which have different sizes, and returning the best layout for those items.

What that means is that flexbox simplifies the layout by diplaying content accross a singular line, or axis.

2.**Explain the difference between the main axis and cross axis.**

The main axis is influenced by your flex-direction. Meaning that, whatever you flex-direction is set to, the main axis will run along that. Inversely, the cross axis goes against the main axis. For instance, if you have a flex-direction set to row, the main axis will be from left to right and your cross axis will be from top to bottom. If it is set to column, the inverse takes affects.

3.**How can using certain properties of flexbox negatively impact accessibility?**

Accessibility is very important to take into account. Although the primary users may not be impacted as evenly, users with disability that utilize accessibility features such as screen readers can be affects. For instance, the row-reverse and column-reverse values only reorder for the visual order, not the logical order. If you have a nav bar at the top of your page where, most likely, a home tab would be at the begining, a 'reverse' value would display it at the end. For screen readers, this reordering will not work.

### CSS Layout - Flexbox

1.**What are some advantages of using flexbox over float?**

One advantage to using flexbox over float relates to the position of child elements: most commonly, you will see flexbox being used within a container, and within that container - or section - there will be content or other elements that are really the focus of the flexbox property. You can manage these content boxes more efficiently.

2.**How does the topic connect with your long term goals?**

The page layout is probably the most basic principle behind any webpage. With a clear understanding of how to code layout more effectively and efficiently, styling your webpages will be that much better because you understand the foundation of what styling a webpage is about. 

Getting your content to line up the way you want, while there are many ways to do it, what's most effective may not be the best. For long term goals, this topic lines up with my goal of attaining the knowledge that will push my confidence in developing webpages in an efficient way that is also pleasing to the user, who you want to invite back without acutally saying it. With user satisfaction being a vital part to producing a webpage that is inviting, page layout is essential to that process.