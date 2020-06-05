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
- 

**Updating an Object**
- 

**Creating many objects: Constructor Notation**
-

**This(keyword)**
-

**Storing Data**
- 

**Arrays**
- Are Objects:
- Arrays of objects & objects in arrays

**Built-in Objects**
- 
- 3 Groups of Builtin Objects

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