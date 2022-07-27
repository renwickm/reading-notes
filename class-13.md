# Code 201 Class 13 Reading Notes

## Learn Storage and How to Use it on Websites

1.Why would a developer use local storage for a web application?

Web applications revert to server storage unless otherwise noted. In doing so, this method will leave data stateless. What this means is when a user closes a webpage, browser or application, the stored data is reset, so when the user returns, they return to a clean site. Local storage acts as a key on the user's computer. When the user returns to the site, this key is read out for identification and tracking.

2.What information should not be stored in local storage?

The formal way of storing data locally has been with cookies. These essentially are keys that have been suggested to promote problems: promote the potential for spying, add to the load of every document accessed on the domain. Some solutions through HTML5 adhere to this issue.

3.Local storage can store what type of data? How would you convert it to that type before storing?

Local storage can only store data in the form of a 'string.' You will probably come across a situation where some of the objects you're working with carry data types other than strings. This means that in order for that data to be read and stored properly, it will need to be converted. To do this you will use the `JSON.stringify()` and `JSON.parse()` methods.