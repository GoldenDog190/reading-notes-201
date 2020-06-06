# Ducket - HTML & CSS / JavaScript & JQuery Notes

## HTML Chapter 6 "Tables"
**Tables**
- *Table*: represents information in a grid format
- Basic Table Structure:
  * table element is used to create a table, and the contents are written row by row
  * tr element indicates the start of each row using an opening tr tag
  * it is followed by the td element used to make a cell for each row
  * end it with a closing tr tag
- Table Headings: to make table headings use th element
- Spanning columns: th or td colspan=""
- Spanning rows: th or td rowspan=""
- Long Tables: 
  * use the thead element to make heading of table
  * tbody element - the body of your table should be put in here
  * tfoot for the footer list 

## JS Chapter 3 "Functions, Methods, and Objects"(pp 106-144)
**Creating an object: Construction Notation**
- new keyword and the object constructor create a blank object, and then can add properties and methods to the object.

**Updating an Object**
- to update the value of properties, use dot notation or square brackets.
- they work on objects created using literal or constructor notation.
- to delete a property, use the delete keyword

**Creating many objects: Constructor Notation**
- *Object constructor* can use a function as a template for creating objects
- create the template with the object's properties and methods
- the function has parameters, each one sets the value of a property in the object, and the methods will be the same for each object created using this function
- you create instances of the object using the *constructor function*
- New keywords followed by the function creates a new object. The properties of each object are given as arguments to the fuction

**This(keyword)**
- The keyword this is commonly used inside functions and objects. Where the function is declared alters what this means. it always refers to one object, usuallt objects in which the fuction operates
- *Global scope/ context* is when a function is created at the top level of the script
- when a function is defined inside an object, it becomes a *method*, and in a method this refers to the contianing object

**Storing Data**
- In JS, data is represented using name/value pairs.
- To organize data, you can use an array or object to group a set of related values. 
- In arrays and objects the name is also known as a *key*. Arrays can store multiple pieces of information. 
- Variables have just one key and one value.
- Objects store sets of name/value pairs

**Arrays**
- Arrays are Objects:
  * Arrays are special types of object, and hold a related set of key/value pairs, but each key for each value is its own index number
- Arrays of objects & objects in arrays: 
  * Can combine arrays and objects to create complex data structures - arrays can store a series of objects and objects can hold arrays.

**Built-in Objects**
- Browsers come with a set of *built-in objects* that represent things like the browser window and the current web page shown in that window. Built-in objects act like a toolkit for creating interactive web pages. The toolkit has 3 compartments:
  * browser object model
  * document object model
  * global javascript objects
- *Object model* is a group of objects, each of which represent related things from the real world using data
- 3 Groups of Builtin Objects:
  * 

**Browser Object Model**
- 

**Windows Object**
- 

**Global Objects: String Objects**
- 

**Working with Strings**
- 

**Number Objects**
- 

**Math Object**
- 

**Creating an instance of Date Object**
- Date Object(and time)
- 

## Other Reading:[Domain Modeling](https://github.com/codefellows/domain_modeling#domain-modeling)  

**Domain Modeling**
- *Domain Modeling*: is the process of creating a conceptual model in code for a specific problem. If articulated well, it can verify and validate the understanding of a specific problem amoung various stake holders.
- A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. 
- An entity that stores data in properties and encapsulates behaviors in methodsis commonly refered to as an *onject-oriented* model.

**Define a constructor and initialize properties**
- To define the same properties between many objects, use a constructor function.

**Object-Oriented Programming in JS**
- The new keywork instantiaties an object
- the constructor function initializes properties inside that object using this variable
- the object is stored in a variable for later use.

**Generate random numbers**
- To model the random nature of user behavior, use the random number generator: Math.random() function
- *Prototype*: acts an objects stunt double

**Tips to Build Domain Model**
- When modeling a single entity that'll have many instances, build self-contained objects with same attributes and behaviors
- model its attributes with a constructor function that defines and initializes properties
- model its behaviors with small methods that focus on doing one job well
- create instances using new keyword follow by call to a constructor function
- store newly created objects in a variables so you can access its properties and methods from inside