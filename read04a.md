## Dynamic web pages with JavaScript ##


**THE DOCUMENT OBJECT REPRESENTS AN HTML PAGE**
Using the document object, you can access and change what content users see on the page and respond to how they interact with it.

 # HOW A BROWSER SEES A WEB PAGE :
 In order to understand how you can change the content of an HTML page using JavaScript, you need to know how a browser interprets the HTML code and applies styling to it.

 ### 1.  RECEIVE A PAGE AS HTML CODE
 ### 2. CREATE A MODEL OF THE PAGE AND STORE IT IN MEMORY
 ### 3. USE A RENDERING ENGINE TO SHOW THE PAGE ON SCREEN

 **All major browsers use a JavaScript interpreter to translate your instructions (in JavaScript) into instructions the computer can follow.**
 
 
 **HOW HTML, CSS,& JAVASCRIPT FIT TOGETHER ?** 

 Before diving into the JavaScript language, you need to know how it will fit together with the HTML and CSS in your web pages.

 # HOW do I write Ascript for a web bage  : 
 * It is best to keep JavaScript code in its own JavaScript
file. JavaScript files are text files (like HTML pages and
CSS style sheets), but they have the . j s extension. 

* The HTML <script> element is used in HTML pages
to tell the browser to load the JavaScript file (rather like
the <link> element can be used to load a CSS file). 

* If you view the source code of the page in the browser,
the JavaScript will not have changed the HTML,
because the script works with the model of the web
page that the browser has created.  


# Basic javascript instructions  : 

* A script is made up of a series of statements. Each
statement is like a step in a recipe. 

* Scripts contain very precise instructions. For example,
you might specify that a value must be remembered
before creating a calculation using that value. 

* Variables are used to temporarily store pieces of
information used in the script. 

# javascript variables 

How do you write variables in JavaScript?
Creating a variable in JavaScript is called "declaring" a variable:
**var carName;**

After the declaration, the variable is empty (it has no value).

To assign a value to the variable, use the equal sign:
**carName = "Volvo";**

You can also assign a value to the variable when you declare it:
**var carName = "Volvo";**

## Syntax
**var varname = value;**

## varname :
Required. Specifies the name of the variable.
Variable names can contain letters, digits, underscores, and dollar signs.

- Variable names must begin with a letter
- Variable names can also begin with $ and _
- Variable names are case sensitive (y and Y are different variables)
- Reserved words (like JavaScript keywords) cannot be used as variable names


## varvalue
Optional. Specifies the value to assign to the variable.

![java](https://d2h0cx97tjks2p.cloudfront.net/blogs/wp-content/uploads/sites/2/2019/08/JavaScript-Variables.png)


