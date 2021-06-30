## **Functional Programming Concepts**

![img](https://www.guru99.com/images/1/080118_0618_WhatisFunct1.png)


## **What is functional programming?**

 ### functional programming is a programming paradigm where programs are constructed by applying and composing functions. ... When a pure function is called with some given arguments, it will always return the same result, and cannot be affected by any mutable state or other side effects

## **What is a pure function and how do we know if something is a pure function?**

 ### pure function is a function that depends only on its declared inputs and its internal algorithm to produce its output. It does not read any other values from “the outside world” — the world outside of the function's scope — and it does not modify any values in the outside worls . SO , is a function where the return value is only determined by its input values, without observable side effects. This is how functions in math work: Math. cos(x) will, for the same value of x , always return the same result. Computing it does not change x .

 ![img](https://cdn-media-1.freecodecamp.org/images/0*a_yub2gTwY-1eK8j.png)


## **What are the benefits of a pure function?**

 ### are much easier to read and reason about. All relevant inputs and dependencies are provided as parameters, so no effects are observed that alter variables outside of the set of inputs. This means that we can quickly understand a function and its 

## **What is immutability?**

### The value can not be changed. Once created a string object can not be modified as its immutable. If you request a substring of a string a new String with the requested part is created


## **What is Referential transparency?**

### this is what happens when you have pure functions and immutable data. So, for example, if one replaced a function with a number that the function would always result to, that would give it referential transparency.
### An expression in a program is said to be referentially transparent if it can be replaced with its value and the resulting behavior is the same as before the change.


# **Videos**
# **Node JS Tutorial for Beginners #6 - Modules and require()**

## **What is a module?**

###  is a simple or complex functionality organized in single or multiple JavaScript files which can be reused throughout the Node. js application. Each module in Node. js has its own context, so it cannot interfere with other modules or pollute global scope.

## **What does the word ‘require’ do?**

### method is used to load and cache JavaScript modules. So, if you want to load a local, relative JavaScript module into a Node. js application, you can simply use the require() method.


## **How do we bring another module into the file the we are working in?**
### We use Require to point to a path to a js file. The .js ending is not necessary. e.g.–> require(./’count’); This is the first step in making that code able to function inside the module. Next, you have to make it available to use.

## **What do we have to do to make a module available?**

### The first thing you do to get access to module features is export them. This is done using the export statement.


## Things I want to know more about

I want to know more about Node.js .
## Sources:

* [Functional Programming Concepts](https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa)

* [Node JS Tutorial for Beginners #6 - Modules and require()](https://www.youtube.com/watch?v=xHLd36QoS4k)

