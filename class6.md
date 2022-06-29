# Read 6 Dynamic Webpages with JavaScript

**JavaScript** (JS) is a lightweight, interpreted, or *just-in-time* compiled programming language with first-class functions. While it is most well-known as the scripting language for Web pages, many non-browser environments also use it, such as Node.js, Apache CouchDB and Adobe Acrobat. JavaScript is a prototype-based, multi-paradigm, single-threaded, dynamic language, supporting object-oriented, imperative, and declarative (e.g. functional programming) styles.

Do not confuse JavaScript with the Java programming language. Both *Java* and *JavaScript* are trademarks or registered trademarks of Oracle in the U.S. and other countries. However, the two programming languages have very different syntax, semantics, and use.

## So what can it really do?

The core client-side JavaScript language consists of some common programming features that allow you to do things like:

JavaScript contains a standard library of objects, such as Array, Date, and Math, and a core set of language elements such as operators, control structures, and statements. Core JavaScript can be extended for a variety of purposes by supplementing it with additional objects; for example:

* Client-side JavaScript extends the core language by supplying objects to control a browser and its Document Object Model (DOM). For example, client-side extensions allow an application to place elements on an HTML form and respond to user events such as mouse clicks, form input, and page navigation.
* Server-side JavaScript extends the core language by supplying objects relevant to running JavaScript on a server. For example, server-side extensions allow an application to communicate with a database, provide continuity of information from one invocation to another of the application, or perform file manipulations on a server.
This means that in the browser, JavaScript can change the way the webpage (DOM) looks.

### Input and Output in JavaScript

The very first thing we need to learn is how to interact with the JavaScript code running in the browse. There are a number of way JavaScript can display text for the user (output).

![JS example](https://linuxhint.com/wp-content/uploads/2022/01/word-image-1014.png)

### Variables

Variables are containers for *storing* data (storing data values).
In this example, x, y, and z, are variables, declared with the var keyword:

`var x = 5;`
`var y = 6;`
`var z = x + y;`

Always declare JavaScript variables with var, let, or const.
The var keyword is used in all JavaScript code from 1995 to 2015.
The let and const keywords were added to JavaScript in 2015.
If you want your code to run in older browser, you must use var.
