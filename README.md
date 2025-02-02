# sp24-lab4
Materials for Week 4 Lab, which includes "Running Tests adapted from [Software Design by Example](https://third-bit.com/sdxpy/) by Greg Wilson.

_February 6, 2024_

Organization:
* SDX-ch6: The code files for the _SDX Ch.6_ activity (as downloaded directly from the book website, unmodified) 

## Team Members for Part 1
Shahrom Dehoti, Grant Didway

## Team Roles for Part 1
Who will start out as
* DRIVER: Shahrom
* NAVIGATOR: Grant

You will switch halfway through the _SDX Ch. 3_ activity.

## Part 1 Documentation

Write your answers to the questions below.

* What were the main ideas from SDX chapter 6?
The main ideas from chapter 6 were how to properly use assertions, dynamic typing, exception raises, and largely, unit tests. It talked about how to use pytests to do these things for more rigorous testing in a framework that has lots of built-in testing features.
* What questions did you have about the material in the chapters? What did you find confusing?
For automatic documentation makers, are similar tools used to identify functions and globals?

### Part A: Recreate the tests from SDX Ch. 6 in the unittest framework

Write a short description of what you did for Part A below. Some questions you might answer: 
* What was your experience putting the tests in unittest like? 
* How is this different from Greg Wilson's simple implementation? 
* How is it similar? 
* Why might you use pytest over unittest, or vice versa?

It became more concise and robust after implementing unittest. Raising exceptions and testing is much easier with assertRaise in the unittest package. 

### Part B: Exercises from the end of SDX Ch. 6

Write a short summary of what you did below, with answers to the questions embedded in the exercises.

We completed Exercise 1 for part B where we printed the globals. It just added the variable name to global variables. 