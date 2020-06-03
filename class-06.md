# Ducket - HTML & CSS / JavaScript & JQuery Notes

## JS Chapter 3 "Object Literals" (pp.100-105):
**Objects**
- *Objects*: group together a set of variables and functions to create a model of something you would recognize from the real world
  * *Property*: a variable that is part of an object. Properties tell us about the object.
  * *Method* a function that is part of an object, and they represent tasks that are associated with the object
  * *Key*: properties and methods have a name and value, and ina an object, that name is called a key

**Creating an Object: Literal Notion**
- *Literal Notion*: is a way to create objects
  * The object is the curly braces and their contents. It is stored in a variable. 
  * Seperate each key from its value using a colon, and seperate each property and method with a comma. 

**Accessing an object & dot notation**
- You access the properties or methods of an object using *dot notation*. 
- Can also access properties using square brackets. 
- The period is known as the *member operator*.

## JS Chapter 5 "Document Object Model" (pp. 183-242):
**Document Object Model (DOM)**
- *DOM*: specifies how browsers should create a model of HTML page, and howJS can access and update the contents of the web page while its in the browser window.
- *DOM tree*: the DOM specifies the way in which the browser should structure this model. Basically a model of a webpage.
- *DOM node*: Every element, attribute, and piece of text in the HTML is represented by its own DOM node.
  * each node is an object with methods and properties
- Working with the DOM tree: accessing and updating the DOM tree involves 2 steps:
  * locate the node that represents the element you want to work with 
  * use its text content, child elements, and attributes.
- Catching DOM Queries: 
  * DOM *queries*: methods that find elements in the DOM tree
- Methods that select individual elements: getElementById() and querySelector() can both search an entire document an return individual elements. Use similar syntax.
- *Nodelists*: DOM quieries that return more than one element
- Selecting an elelment from a nodelist: item() method and array syntax
- Repeating actions for an entire nodelist: when you have a nodelist, you can loop through each node in the collection an aaply the same statement to each.
- Looping through nodelist:
  * At first, value set to zero, so the first item from the nodelist is targeted and the value of its class attribute is set to cool.
  * When value counter is 1, the second item from the nodelist is targetted and the value of its class attribute is set to cool, etc...
  * When the value counter is 3, the conditionno longer is trueso the loop ends

  **Adding or Removing HTML Content**
  - 2 different approachesto adiing and removing content from a DOM tree: innerHTML property and DOM manipulation
  - *innerHTML property* can be used on any element node. its used both to retrieve and replace content. To update an element, new content is provided as a string, and it can contain markup for descendant elements.
  - *DOM manipulation methods*: refers to a set of DOM methods that allow you to create element and text nodes, and then attach them to the DOM tree or remove them from DOM tree.
  - *Cross-Site Scripting Attacks (XSS)*: an attacker that could gain access to your user' accounts, which is on innerHTML. Defense against this with a *validation*.

 **Attribute Nodes**
 - once you have an element node, you cna use other properties and methods on that elelment node to access and change its attributes.

## Extra Reading [Understanding the problem domain is the hardest part of programming](https://simpleprogrammer.com/understanding-the-problem-domain-is-the-hardest-part-of-programming) Notes:

**Hardest Things About Writing Code:**
- learning a new technology
- naming things
- testing your code
- debugging and fixing bugs
- making software maintainabel
- learning the problem domain, etc...

**Problem Domain**
- The problem domain is like a puzzle without any picture on it. 
- Often times programmers are not given complete information, so it makes the problem domain difficult to solve.
- Or programmers are given all the information, so they don't know how to deal with the domain.
- Understanding the problem is the most critical piece to the equation.
- Do 2 things: make the problem domain easier and get better understanding the problem domain
- Can make it easier by: cutting out cases and narrowing your focus to a particular part of the problem.
- Look as it like a game, start out with the easier problems first, and then work your way to the harder ones.
- Be sure to understand the problem inside and out before you try to solve it with code.

