# Introduction to Data APIs

One of the things that has made it possible to develop interesting and useful apps is that organizations (governments, businesses, not-for-profits, etc.) now make lots of data available via an Application Programming Interface (API).

Using JavaScript or jQuery, we can write scripts to connect to those APIs, retrieve data, and then use that data in our apps.

http://readwrite.com/2013/09/19/api-defined/ provides a good overview of APIs;  give it a read.  (For those who want to know more, take a look at http://www.programmableweb.com/api-university/what-are-apis-and-how-do-they-work .)

For now, we'll be focusing on Data APIs, but later on we'll look at APIs for data visualization, user authentication, and more.

No matter which data APIs we use, we'll need to programmatically work with the data, and so we need to practice manipulating it.  Most APIs deliver data in JavaScript Object Notation (JSON) format, where the data is presented as a combination of **arrays** (sets of values accessed by index position) and  **objects** (sets of key:value pairs where values are accessed by their *key*).

(A quick explanation of JSON syntax is at http://www.w3schools.com/js/js_json_syntax.asp .)

For a little practice in working with JSON objects, take a look at [simpleJSONexample.html](./simpleJSONexample.html) .  Open the page, open the JavaScript console, and try the examples. 
