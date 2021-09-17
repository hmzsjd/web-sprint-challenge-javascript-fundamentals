# Sprint Challenge - JavaScript Fundamentals

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in project. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied array methods, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a range of JavaScript problems.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the sprint challenge. 

## Introduction

The index.js file contains all of your challenges. Please review it in full before answering the questions. If you complete the stretch goals please leave them in your file but commented out so that they do not affect the MVP tasks 

In meeting the minimum viable product (MVP) specifications listed below, you should have all tests passing. You can console.log to check your work and ensure you are submitting the correct results 

### Commits

Set up codegrade early and commit your code regularly and meaningfully. 

## Interview Questions
### (please edit this file and write your answer below each question.)
Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read.

1. Explain the differences between `.map`, `.reduce` and `.filter` and describe a use case for each. 

.map() can be used when a transformation is required on the elements of an array without manipulating the original array, one example would be if we have an array of integers and wanted to double every single integer we would use .map()

.filter() can be used to return a copy of an array with elements that only match the conditional that is provided. One example is if we have an array of student objects with their names and GPAs, we could use .filter() to return an array only of students that have a GPA of higher than 3.5 

.reduce() can be used to manipulate or reshape data to return a single value. One example is if we have an array of the population of all US States, we could return the total population of all states or we could return the state with the highest population. 


2. Explain the difference between a callback and a higher order function.

A higher order function is a function that can receive other functions as arguments and these functions that are passed in as arguments are known as callback functions. 

3. Explain what a closure is.

Closure is the ability for nested functions to reach out and find variables that are one scope higher. If the variable is not found in the local scope, the function will go one scope higher and look for the specific variable. This level of inheritance only works one way and that is downwards from parent to child functions. A parent function cannot access variable within the child function, but a child function can access variables of the parent. 

4. Describe the four principles of the 'this' keyword.

    Global Binding: 'this' points to the window if being used in the browser which is the global object. 
    Implicit Binding: 'this' when used inside of an object will point to the object itself. When an object's method is invoked using dot notation, 'this' points to whatever is to the left of the dot. 
    New Binding: 'this' refers to the specific instance of the objected that is created and returned when a constructor function is used. 
    Explicit binding: 'this' refers to the object that is passed into the call() or apply() functions as an argument. 

5. Why do we need super() in an extended class?

Becasue super() passes the required information and calls the constructor of the parent class, it takes care of all the initializations that are common with the parent class as well as the binding. 

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Set up Project

Using VSCode and Command Line:


1. Fork the repo
2. Clone your forked version of the repo
3. cd into your repo and create a branch with your first and last name
4. open the terminal in your vs code and type `npm install`
5. next type `npm run test` in your terminal
6. Complete your work making regular commits, once you have all your tests passing and you are ready to submit your work please see canvas for instructions on how to submit

### Testing & Debugging

Open a second terminal inside of your project by clicking on the split terminal icon
![alt text](assets/split_terminal.png "Split Terminal")

Inside of your second terminal type `npm start` 
![alt text](assets/npm_start.png "type npm start")

You will be running your tests in one terminal and debugging in the other. As you work on your code you should make use of `console.log` to check your progress and debug.
![alt text](assets/tests_debug_terminal_final.png "your terminal should look like this")

### Task 2: Project Requirements (MVP)

You must complete all tasks inside of `index.js` and answer the questions above.

In your solutions, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Resources
 
 [Sprint Challenge Study Guide](https://www.notion.so/lambdaschool/Unit-1-Sprint-3-Study-Guide-033a9a00659a4ef98c12eb97e49a6110)

## Submission format

Please submit your project via codegrade by following [these instructions](https://www.notion.so/lambdaschool/Submitting-an-assignment-via-Code-Grade-A-Step-by-Step-Walkthrough-07bd65f5f8364e709ecb5064735ce374)

