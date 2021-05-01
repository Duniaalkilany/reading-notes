

# **Problem Domain, Objects, and the DOM**


# **JavaScript Objects**

![object](https://cdn.educba.com/academy/wp-content/uploads/2019/10/JavaScript-Objects-2.png)
 that JavaScript variables are containers for data values , Objects are variables too. But objects can contain many values.

 ## This code assigns many values (Fiat, 500, white) to a variable named car:

 **var car = {type:"Fiat", model:"500", color:"white"};**

 The values are written as name:value pairs (name and value separated by a colon).

 ## JavaScript objects are containers for named values called properties or methods.

 Object Definition
You define (and create) a JavaScript object with an object literal:

Example
var person = {firstName:"John", lastName:"Doe", age:50, eyeColor:"blue"};


## Object Definition
You define (and create) a JavaScript object with an object literal:

**Example**
**var person = {firstName:"John", lastName:"Doe", age:50, eyeColor:"blue"};**

Spaces and line breaks are not important. An object definition can span multiple lines:

**Example**
**var person = {**
  **firstName: "John",**
  **lastName: "Doe",**
  **age: 50,**
 **eyeColor: "blue"**
**};**


![objecttt](https://fireship.io/courses/javascript/img/js-object-props.png)

## Object Properties
The name:values pairs in JavaScript objects are called properties:

|Property|Property Value|
|----------|--------|
|firstName|John|
|lastName|Doe|
|age|50|
|eyeColor|blue|

## Accessing Object Properties
You can access object properties in two ways:

**objectName.propertyName**

or

**objectName[" propertyName"]**

# **Document Object Method**
![dom method](https://www.geeksread.com/wp-content/uploads/2018/04/DOM-Methods-in-JavaScript-For-Selecting-HTML-Elements.png)

The Document Object Model (DOM) specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window. 

THE DOM TREE IS A MODEL OF A WEB PAGE As a browser loads a web page, it creates a model of that page. 
The model is called a DOM tree, and it is stored in the browsers' memory. 
It consists of four main types of nodes :

**1. THE DOCUMENT NODE**

**2. ELEMENT NODES**

**3. ATTRIBUTE NODES** 

**4. TEXT NODES**

![dom](https://www.tutorialrepublic.com/lib/images/html-dom-illustration.png)

## What is the HTML DOM?
The HTML DOM is a standard object model and programming interface for HTML. It defines:

* The HTML elements as objects
* The properties of all HTML elements
* The methods to access all HTML elements
* The events for all HTML elements
**In other words: The HTML DOM is a standard for how to get, change, add, or delete HTML elements.**

## With the object model, JavaScript gets all the power it needs to create dynamic HTML:

* JavaScript can change all the HTML elements in the page
* JavaScript can change all the HTML attributes in the page
* JavaScript can change all the CSS styles in the page
* JavaScript can remove existing HTML elements and attributes
* JavaScript can add new HTML elements and attributes
* JavaScript can react to all existing HTML events in the page
* JavaScript can create new HTML events in the page

## **JavaScript - HTML DOM Methods** 
**HTML DOM methods are actions you can perform (on HTML Elements).**

**HTML DOM properties are values (of HTML Elements) that you can set or change.**

## The getElementById Method
The most common way to access an HTML element is to use the id of the element.

## The innerHTML Property
The easiest way to get the content of an element is by using the innerHTML property.

The innerHTML property is useful for getting or replacing the content of HTML elements.

The innerHTML property can be used to get or change any HTML element, including < html> and < body>.

## **JavaScript HTML DOM Elements**
![elements](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/08/JavaScript-Document-Object-Model-DOM-1200x900.jpg)

## Finding HTML Elements
Often, with JavaScript, you want to manipulate HTML elements.

To do so, you have to find the elements first. There are several ways to do this:

* Finding HTML elements by id
* Finding HTML elements by tag name
* Finding HTML elements by class name
* Finding HTML elements by CSS selectors
* Finding HTML elements by HTML object collections


## **JavaScript HTML DOM - Changing HTML**

## Changing the HTML Output Stream
JavaScript can create dynamic HTML content ,In JavaScript, document.write() can be used to write directly to the HTML output stream.

## Changing HTML Content
The easiest way to modify the content of an HTML element is by using the innerHTML property.

To change the content of an HTML element, use this syntax:

**document.getElementById(id).innerHTML = new HTML**

## Changing the Value of an Attribute
To change the value of an HTML attribute, use this syntax:

**document.getElementById(id).attribute = new value**

## **JavaScript HTML DOM - Changing CSS**
## Changing HTML Style
To change the style of an HTML element, use this syntax:

document.getElementById(id).style.property = new style

![domm](https://dsmith77.files.wordpress.com/2008/07/the-document-object-model-dom.gif?w=640)


### Sources:
* [the Duckett JS book](https://slack-files.com/files-pri-safe/TNGRRLUMA-F01VBUFKN3C/javascript_and_jquery_interactive_jon_du.pdf?c=1619379436-96c719feacff7a14)



