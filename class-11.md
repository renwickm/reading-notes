# Code 201 Class 11 Reading Notes

## Readings: Audio, Video, Images

### Video and Audio Content

1.Explain how the ability to use video and audio on the web has evolved since the early 2000's.

Video and Audio web capabilities have greatly evolved since the 2000's. It was difficult to apply these to any webpage due to the nature of their size in bandwidth and the speed at which applications were able to run at that time. Now, our technical abilities have improved.With many video enabled applications such as Flash and Silverlight leading the way. HTML was not capable of producing video and audio capabilities and had to rely on applications such as them. However, with the induction of HTML5 you now can run such applications on it. 

2.Describe the use of the `src` and `controls` attributes in the `<video>` element.

The `src` attribute is similar to the `src` attribut with images. They provide a source url/path to the referenced material you want to display.

The `controls` attribute allows you to apply either the browser own controls interface or custom build controls in your own way. Some points of emphasis in these controls apply to people with disabilities such as epilepsy that give them control over the video display settings. 

3.Why is it important to have **fallback content** inside the `<video>` element?

In case the user browser does not support video playback, users should be provided with older browser playback. This is called fallback content. It is a back-up to the initial plan.

4.Write a very short story where `<audio>` and `<video>` are characters.



### A Complete Guide to Grid

1.How does Grid layout differ form Flex?

Grid layout is two-dimensional. Flex is one-directional.

2.Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.

The gird container is the box, or specefied area, you are designating to be the space of the grid from where you will structure the layout. The grid item is any particular propert/element/value to be structured inside the grid layout. The grid line indexes dimensions across the page.

### Responsive Images

1.Besides making a site visually appealing across different screen sizes, why should developers make images responsive?

Developers have done a pretty good job at improving the quality of images across different viewport diplays. However, some viewports, such as narrow display devices (cell phones), don't offer the same quality in image resolution. Some suggestions are to replace larger photot with medium - small photos to adjust to the narrowing viewport. This also will work on lower bandwidth that most viewports in these categories will benefit from.  In light of the growing response to user device technologies, browsers offer more options to users from whichever viewport they are utilizing. 

2.Define the following `<img>` attributes `srcset` and `sizes`. Write an example of how they are used. 

The `srcset` is an `img` attribute that provides a set of images the browser is able to choose from. Depending on the users' browser window, or viewport, this attribute will allow the browser to pick from the set that best fits the users viewport window.

The `sizes` attribute sets conditions for the image to follow, such as specified height and width max across viewport, and how images will fit these conditions.

3.How is `srcset` more helpful for responsive images than CSS or JavaScript?

Images are downloaded prior to CSS and Javascript. By the time it takes CSS and JavaScript to run through its' download, any images have already finished their download. With the `srcset` you are provided options to address any viewport window adjustments needed, while correcting the process in webpage download steps.