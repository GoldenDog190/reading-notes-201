# Ducket - HTML & CSS / JavaScript & JQuery Notes

## HTML Chapter 4 "Links":
**Links**
> *Links*: allow you to move from one web page to another
- Writing links: links are created using (a) element with opening tag, which also will have the href attribute with the url of the page you are linking to, and closing tags, and the specific page information on the URL you want to link inbetween.
- Linking to other sites: opening and closing bracket, a href = "url" in between them, and a closing a element tag
- Links to other pages on same site: don't have to specify the domain name in the URL, instead can use a shorthand known as relative URL.
- *Directory Structure*: for larger websites organize your code by placing the pages for each section of the site into a new folder/ directory.
- *Relative URLS*: used when linking pages within your own website
- Email links - have the opening element be: a href = "mailto:email url" 
- To open links in a new window use the target attribute: a href-"url" target="_blank"
- Links to specific parts of page - example: h1 id="#prologue"
- Links to specific part of another page - example: a href="url/#prologue"

## HTML & CSS Chapter 15 "Layout":
**Key concepts in Positioning Elements:**
- *Building Blocks*: css treats each HTML element as if its in its own box, and this box will either be block-level box or inline box.
  * Block-level elements: h1, p, ul, li
  * Inline elements: img, b, i
- *Containing Elements*: if one block-level element sits inside another block-level element, then the outer box is the contianing/ parent element.

**Controlling the Position of Elements**
- *Positioning Schemes*: allow you to control the layout of a page
  * Normal Flow: position:static
  * Relative Positioning: position:relative
  * Absolute Positioning: position:absolute
  * Fixed Positioning: position:fixed
  * Floating Elements: float
- Box offset property tells the browser how far from the top or bottom and left or right the box should be placed.
- z-index property allows control over which box appears on top

**Screen Sizes & Screen Resolutions**
- Screen size - your design needs to be able to work on a large range of different screen sizes
- Screen resolutions - resolution refers to the number of dots a screen shows per inch

**Page Sizes**
- Due to screen sizes and screen resolutions varying so much, designers often try to create pages around 960-1000 pixels wide.

**Fixed Width Layouts**
- These designs don't change size as the user increases or decreases sizeof their browser window. Measurements are in pixels.

**Liquid Layouts**
- These designs stretch and contract as user increases or decreases the size of their browser window, and use percentages.

**Layout Grids**
- Designers use a grid structureto help position and organize items on a page.
- Possible layouts: 960 pixels wide and a 12 column grid

**CSS Frameworks**
- CSS frameworks aim is to make life easier by providing code for common tasks, such as creating layout grids, styling forms, creating printer friendly version of pages, etc.
- Advantages - save you from repeatedly writing code for the same tasks, and are well tested
- Disadvantages - require you to use class names in the HTML code that only controls presentation of the page, and to satify a variety of needs CSS frameworks often contains more code than you need for a web page.

## JS Chapter 3 "Functions, Methods, & Objects" (first part pp 86-99 only): 
**Function**
> *Functions*: let you group a series of statements together to perform a specific task. You can reuse the function in different parts of the script to repeat the same task.
- Declaring functions: give it a name and then write the statement needed to achieve its task inside the curly braces.
  * sometimes functions need specific information to perform its task, which is when you will declare the function it gives you a *parameter*. Parameters act like variables.  
- Calling functions: executing all of the statements between the curly braces with one line of code
  * when you call a function that has parameters, specify the values it should use in the parentheses that follow its name. The values/ variables are called *arguments*.
- A single value or multiple values can be gotten out of a function.

**Anonymous Functions & Function Expressions**
- *Anonymous functions*: a function with no name
- *Function expressions*: if a function is placed where it is expected to see an expression, then it gets treated as an expression.
- Immediately involked function expression (IIFE): these functions are not given a name, instead are executed once as the interpreter comes across them. 

**Variable Scope**
- *Variable scope*: the location where you declare a variable will affect where it can be used within your code. If declared within a function, it can only be used within that function.
  * *Local variables*: created inside of a function, and can only be used in that function
  * *Global variables*: created outside of the function, and can be used anywhere within the script.

**How Memory & Variables Work**
- Global variables use more memeory. 
- Local variables are only remembered while the function is being executed.
- Name collisions

## Extra Reading Article ["6 Reasons for Pair Programming"](https://www.codefellows.org/blog/6-reasons-for-pair-programming/): 

**Pair Programming**
- *Pair programming* involves two roles: the driver and navigator
  * Driver - is the programmer who is typing, and manages the text editor,switching files, version control, and writing code.
  * Navigator - thinks about the big picture, what comes next, how an algorithm might be converted into code, and scans for typos or bugs. Also, uses their computer as a second screen to look up solutions and documentations.
- **Four skills programmers use:** 
  * listening
  * Speaking 
  * Reading
  * Writing
- **Why pair program?**
  1. Greater efficiency
  2. Engaged collaboration
  3. Learning from fellow students
  4. Social skills
  5. Job interview readiness
  6. Work enviroment readiness
