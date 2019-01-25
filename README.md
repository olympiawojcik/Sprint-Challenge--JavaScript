# Sprint Challenge: JavaScript Fundamentals

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a survey of problems. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied variables, functions, object literals, arrays, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a survey of JavaScript problems.

## Instructions

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. However, you are encouraged to follow the twenty-minute rule and seek support from your PM and Instructor in your cohort help channel on Slack. Your work reflects your proficiency in JavaScript fundamentals.

You have three hours to complete this challenge. Plan your time accordingly.

## Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons) and your project manager.

## Description

You will notice there are several JavaScript files being brought into the index.html file.  Each of those files contain JavaScript problems you need to solve.  If you get stuck on something, skip over it and come back to it later.

In meeting the minimum viable product (MVP) specifications listed below, you should have a console full of correct responses to the problems given.

## Self-Study Questions

Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read by your project manager

1. Describe the biggest difference between `.forEach` & `.map`.

.forEach() and .map() are two array methods that execute a provided function once for each element in an array. The biggest difference between them is that .forEach() returns undefined while .map() creates and returns a new array with the results. Since .map() is returning an array, it requires a return statement or else it will fail. 

2. What is the difference between a function and a method?

A function in Javascript is a set of instructuions that perform a task. A method is a function bound to an object and stored as an object property. In order to be used, it must be called on an object like such: myObj.myMethod().

3. What is closure?

A closure is a combination of a function and the environment within which that function was declared. When a function is declared, variables and functions inside of that functional scope have the ability to reach OUTWARDS to the outer/enclosing function's variables.

4. Describe the four rules of the 'this' keyword.

The 'this' keyword is simply a pointer to an object, allowing us to reference an object without having to refer to it's name. In order to figure out what object 'this' is pointing to, we need to understand its execution context, or the environment where our function is being called/invoked. There are 4 rules to understanding the binding of 'this':

1) Window/Global Object Binding - When a function is declared in the global scope, the value of 'this' is the global object (window in the browser, global/console in node)

2) Implicit/Automatic Binding- When a method is invoked by a preceding dot, 'this' points to the object on the left of the dot.

3) New Binding- When we build new objects using constructor functions, 'this' refers to the specific *instance* of the object that's created and returned by the constructor function.

4) Explicit Binding- When we write methods that can be used on different object's, we can explicity define what 'this' points to using Javascript's call or apply method. 


5. Why do we need super() in an extended class?

super() is used to access and call functions on an object's parents - it's what gives us access to our parent's methods. 

## Project Set up

Follow these steps to set up and work on your project:

- [X] Create a forked copy of this project.
- [X] Add PM as collaborator on Github.
- [X] Clone your OWN version of Repo (Not Lambda's by mistake!).
- [X] Create a new Branch on the clone: git checkout -b `<firstName-lastName>`.
- [X] Create a pull request before you start working on the project requirements.  You will continuously push your updates throughout the project.
- [X] You are now ready to build this project with your preferred IDE
- [X] Implement the project on your Branch, committing changes regularly.
- [X] Push commits: git push origin `<firstName-lastName>`.

Follow these steps for completing your project:

- [ ] Submit a Pull-Request to merge <firstName-lastName> Branch into master (student's  Repo).
- [ ] Add your Project Manager as a Reviewer on the Pull-request
- [ ] PM then will count the HW as done by  merging the branch back into master.


## Minimum Viable Product

Your finished project must include all of the following requirements:

**Pro tip for this challenge: If something seems like it isn't working locally, copy and paste your code up to codepen and take another look at the console.**

## Task 1: Objects and Arrays
Test your knowledge of objects and arrays. 
* [X] Use the [objects-arrays.js](challenges/objects-arrays.js) link to get started.  Read the instructions carefully!

## Task 2: Functions
This challenge takes a look at callbacks and closures as well as scope. 
* [X] Use the [functions.js](challenges/functions.js) link to get started. Read the instructions carefully!

## Task 3: Prototypes
Create constructors, bind methods, and create cuboids in this prototypes challenge.
* [X] Use the [prototypes.js](challenges/prototypes.js) link to get started. Read the instructions carefully!

## Task 4: Classes
Once you have completed the prototypes challenge, it's time to convert all your hard work into classes.
* [ ] Use the [classes.js](challenges/classes.js) link to get started. Read the instructions carefully!

In your solutions, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Stretch Problems

There are a few stretch problems found throughout the files, don't work on them until you are finished with MVP requirements!
