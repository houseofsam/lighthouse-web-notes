# Sameer's Notes

## Summary 

This repository contains all of the notes taken by [Sameer](https://github.com/houseofsam) for the [Lighthouse Labs](https://www.lighthouselabs.ca/) Web Development Bootcamp. ~~Right now~~ I'm experimenting with the live preview (Shortcut on **_VSCode = Cmd K + V_**)

***

## Table of Contents 

* [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

* [Week 1](/Week_1) 
  * [Day 1](Week_1/Day_1)
    1. What should I do for lunch
    2. Gist & committing via terminal
    3. ESLint
    4. Command Line Args
    5. Lotide
       * assertEqual
        * Implement Head/Tail of an array
  * [Day 2](Week_1/Day_2)
    1. [Lecture 1]()
    2. Minimum Values
    3. Joining concepts (Arrays)
    4. [Function Best Practices](Week_1/Day_2)
        * Dice Roller
    5. Scope
    6. Debugging and Error Messages
    7. Coercion & Truthy/Falsey
    8. Lotide
        * eqArrays, assertArraysEqual
        * Implement without
        * Implement flatten
    9. Stretch: Password Obfuscator
  * [Day 3](Week_1/Day_3)
    1. [Lecture 2]()
    2. Implement Middle (Lotide Array Method)
    3. Primitive Data Types (All values that are not objects)
    4. Objects
        * Basic concepts
        * Iteration
    5. Pair Programming #1 - Raisin Arizona
    6. Lotide 
        * countOnly
        * countLetters (Mentor review - see Guard Pattern)
        * letterPositions
        * findKeyByValue 
        * eqObjects (Review to understand workflow for future problems)
        * assertObjectsEqual (Review)
            * Util inspect used to print out object
  * [Day 4](Week_1/Day_4)
    1. [Lecture 3]()
    2. Functions as Objects & Callbacks
        * findWaldo using forEach() & Anon fn
    3. Anonymous & Arrow Functions
    4. First Class & Higher Order Functions
    5. Filtering with Callbacks (Array.prototype.filter)
    6. Array.prototype.map
    7. Lotide
        * Implement takeUntil
        * Implement findKey
    8. [Vim]()
    9. Pair Programming #2 - Object Property Value Swap
    10. Stretch - Pythagorean using Map()
  * [Day 5](Week_1/Day_5)
    1. Music Library Object Cardio w/ Methods & 'this'
    2. Arrow functions and 'this'
    3. Intro to Recursion
  *[Weekend](Week_1/We)
    1. Intro to Modules / Module.exports / require
    2. Packages & npm & package.json
    3. Automated testing
        * Unit vs. Integration vs. Functional 
        * Behaviour Driven Development
        * Happy Path vs. Sad Path Testing & Edge Cases
    4. Intro to Unit Testing
        * Mocha & Chai
        * Palindromes
        * Should I Buy This Car
        * Name Formatter
    5. Plagiarism & Tech Interview Info
    6. Stretch Readings from the Week
        * More on objects and primitives
        * Closures & Lexical Scoping (Review)
          * Immediately-invoked Function Expression (IIFE) - Limitations?
* [Week 2](Week_2)
  * [Day 1](Week_2/Day_1) - [Lotide Due]
    1. Lotide Refactor
    2. Object Shorthand in ES6
    3. Publishing Lotide to npm
    4. Kata - TitleCase
    5. Intro to Async Control Flow
        * setTimeout Intro
  * [Day 2](Week_2/Day_2)
    1. process.stdout.write (same-line) vs. console.log
    2. Console printing animations
    3. Spinner
    4. Timer
    5. Event Handling and User Input
        * stdin / .on()
        * Fun Profile Generator (readline)
    6. Asynchronous Return Values
        * Using a callback function (2nd param) instead of a return for results
    7. Pair Programming #3 - There is No Spoon (Array Transpose)
    8. Computer Networking
        * TCP & Intro to net
  * [Day 3](Week_2/Day_3)
    1. Snake Game
        * Client Setup
        * Setting Initials by writing to server
        * Move commands + stdin setup
        * Sending messages to other users in server
        * Modularizing code in play.js()
    2. Intro to HTTP
        * How HTTP uses TCP
    3. Using node 'request' library
    4. Page downloader w/ 'request library and fs.writeFile
    5. Pair Programming #4 - Word Search
  * [Day 4](Week_2/Day_4)
    1. JSON
    2. API Intro
    3. Cats as a Service (API & Test)
    4. ISS Spotter (Multiple APIs)
        * Method 1 - Nested Callbacks
        * Method 2 - Promises (request-promise-native)
    5. Creating Promises
    6. Kata: findFriend
  * [Day 5](Week_2/Day_5)
    1. Intro to OOP/OO Software Dev Paradigm vs. F.P.
        * Organization, Reusability, Modularity
    2. To-Do List (classless)
    3. OO Classless Method --> Define/return object in function with relevant property values & methods
    4. Acknowledging that Prototypes will be a Knowledge Gap in Favour of Classes
    5. Classes, Instances, Constructors (Classes = blueprints to create Objects) [Pizza]
        * 'new' keyword
    6. Inheritance
    7. Method Overriding ('super') [Person, Student, Mentor LHL Classes]
    8. Getters and Setters to Compute values on the fly and validate data before assigning to property
        * Accessed properties as if they are value properties instead of method properties (e.g. pizza.price vs pizza.getPrice())
    9. OOP Best Practices
        * Abstraction (Hiding inner workings of obj in favour or exposing simple interface to obj)
        * Private vs. Private properties / Not accessing properties directly / '_' prop naming convention
        * Single Responsibility Principle 
        * Using Inheritance to reduce duplicate code and share behaviour between classes 
    10. LightCoin Crypto App
  * [Weekend](Week_2/We)
    1. [Video on how JS Actually Works (Callbacks, Call Stack, Event Queue, Event Loop, Etc.)](https://www.youtube.com/watch?v=6MXRNXXgP_0)
    2. Promises (Refresher) - Udacity Intro Vids 
    3. Clean Code
        * [AirBnB JS Style Guide](https://github.com/airbnb/javascript)
        * [15 Best Practices for Writing Readable Code](https://code.tutsplus.com/tutorials/top-15-best-practices-for-writing-super-readable-code--net-8118)
    4. [Command Line cURL](http://www.thegeekstuff.com/2012/04/curl-examples/) = command line tool and library for transferring data with URLs
    5. [Character Encoding](https://www.youtube.com/watch?v=MijmeoH9LT4) (ASCII --> UTF-8 and its importance)
    6. [Domain Name System](https://www.youtube.com/watch?v=72snZctFFtA)
        * Root Servers --> Top Level Domain Name Servers --> Authoratative Name Servers --> Resolving Server
        * Relevance of registry/registrar 
    7. [HTTP Server Tutorial](https://www.guru99.com/node-js-create-server-get-data.html)
    8. [Express Tutorial](https://dzone.com/articles/watch-a-writer-learn-nodejs-part-1)
  * [Week 3](Week_3)
    1. [Day 1](Week_3/Day_1)
        * Building a web server with HTTP
        * Building a web server with Express
        * TinyApp project setup 
        * CRUD & HTTP
        * TinyApp (Template Engine & URL Shortening)
    2. [Day 2](Week_3/Day_2)
        * Nodemon
        * TinyApp (Deleting and Updating URLS)
        * Git Branches
        * Cookies and Cookies in Express
        * TinyApp Cookies Implementation using git branch