
# **Error Handling & Debugging**


![img](https://distancelearning-images.s3.eu-west-2.amazonaws.com/product-images/600-600/Webmaster-Javascript-1200x600.jpg)

## JavaScript can be hard to learn and everyone makes mistakes when writing it. This chapter will help you learn how to find the errors in your code. It will also teach you how to write scripts that deal with potential errors gracefully.


## When you are writing JavaScript, do not expect to write it perfectly the first time. Programming is like problem solving: you are given a puzzle and not only do you have to solve it, but you also need to create the instructions that allow the computer to solve it, too.


## When writing a long script, nobody gets everything right in their first attempt. The error messages that a browser gives look cryptic at first, but they can help you determine what went wrong in your JavaScript and how to fix it. 


* ## **THE CONSOLE & DEV TOOLS**
## Tools built into the browser that help you hunt for errors.

* ## **COMMON PROBLEMS**
## Common sources of errors, and how to solve them.

* ## **HANDLING ERRORS**
## How code can deal with potential errors gracefully.


# **ORDER OF EXECUTION**
## To find the source of an error, it helps to know how scripts are processed. The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run:


![img](https://www.oreilly.com/library/view/javascript-and-jquery/9781118531648/images/p452-001.jpg)


# **How code can deal with potential errors gracefully.**

## Firstly, **The order of execution** The order that your codes or your statements run, it is very important to know how it goes, but some of these codes will be complex and hard to track the execution order.

## **Excution Context** We need to know that there is one global execution context and every function creates a new execution context.

## **The Stack** That is mean when a function need a variable or some statements from another functions, it stacked this task on top and make the other tasks on hold.

* ## EXECUTION CONTEXT & HOISTING There are two execution phases every time a script runs:
## 1. prepare
## 2. execute

* ## UNDERSTANDING SCOPE
* ## UNDERSTANDING ERRORS

## **HOW TO DEAL WITH ERRORS**
* ## You need to track every statement to debug your script.
* ## gracfully, handle the errors: Try to narrow the problem where might be to ease tracking it.


# **summary**

* ## If you understand execution contexts (which have two stages) and stacks, you are more likely to find the error in your code. 
* ## Debugging is the process of finding errors. It involves a process of deduction. 
* ## The console helps narrow down the area in which the error is located, so you can try to find the exact error. 
* ## JavaScript has 7 different types of errors. Each creates its own error object, which can tell you its line number and gives a description of the error. 
* ## If you know that you may get an error, you can handle it gracefully using the try, catch, finally statements. 
* ## Use them to give your users helpful feedback. 

![js](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRoFhhOhsxwbhZG1fdsn_segYTIFxBzubf4VQ&usqp=CAU)

### Sources:
* [the Duckett JS book](https://slack-files.com/files-pri-safe/TNGRRLUMA-F01VBUFKN3C/javascript_and_jquery_interactive_jon_du.pdf?c=1619379436-96c719feacff7a14)