# Ducket - HTML & CSS / JavaScript & JQuery Notes

## HTML Chapter 3 "Lists":
**Lists**
- **3 types of HTML lists**
  * **Ordered Lists, Unordered Lists and Definition Lists**
- *Ordered Lists*
  * Are lists that are numbered. Is created with ol element with the actual numbered part of the list inbetween the opening and closing ol tags. Each item of the numbered list is placed between an opening li tag and closing li tag.
- *Unordered Lists*
  * Lists that use bullet points. Created using opening and closing ul elements with each item listed with opening and closing li tags inbetween the ul tags.
- *Definition Lists*
  * Made up of a set of terms along the definitions for each of those terms. The list is made with opening and closing dl elements.Inside the dl elements you use dt element to contain the term being defined, and dd element for containing the definition.
- *Nested Lists*
  * A second list within the li element to create a sublist or nested list.

## CSS Chaper 13 "Boxes":
**Box Dimensions**
- Control the dimensions of your boxes, create borders around boxes, set margins and padding for boxes, & show & hide boxes.
- A box is sized just big enough to hold its contents. you can set your own dimensions for a box using width and height.
- *Limiting width* using: 
  * min-width
  * max-width
- *Limiting height* using:
  * min-height
  * max-height
- *Overflowing content*
  * overflow - tells browser what to do if content within box is larger than the box itself
  * hidden - to hide extra content
  * scroll - to add a scroll bar

**Border, Margin, & Padding**
- *Border*: every box has a border, and it seperates the edge of one box from another
  * border-width
  * border-style
  * border-color
  * shorthand: border
- *Margin*: sits outside the edge of the border
  * margin
- *Padding*: the space between the border of a box & any content contianed within it
  * padding

**White Space & Verticle Margin**
- The padding and margin properties are helpful in adding space between various items on the page.

**Centering Content**
- To center a box set the left-margin and right-margin to auto, which will make the browser put an equal gap on each side of the box, and this will center the box.

**Change Inline/Block**
- *display* property: allows you to turn an inline element into a block-level elment or vise versa, and can be sued to hide an element from the page. The values this property can take are:
  * inline
  * block
  * inline-block
  * none

**Hiding Boxes**
- *visibility* property: allows you to hide boxes from users, but leaves space where the lelment would have been. Can take on these two values:
  * hidden
  * visible

**CSS3**
- *Border Image*: applies an image to a border of any box, and slices the background image into 9 pieces 
  * border-image 
- *Box Shadow*: box-shadow property allows you to add a drop shadow aound a box.
- *Rounded Corners & Elliptical Shapes*: use border-radius to round corners and elliptical shapes
  * border-radius

## JS Chapter 4 "Decisions and Loops" *from switch statements*:
**Switch Statements**
- *Switch statements*: starts with a variable called switch value
- Each case indicates a possible value for this variable and the code that should run if the variable switches the value.

**Type Coercion & Weak Typing**
- *Type coercion*: JS can convert data types behind the scenes to complete an operation
- *Weak typing*: JS is said to use weak typing because the data type for a value can change
- *Strong typing*: other languages are said to use strong typing because they require that you specify what data type each variable will be

**Truthy & Falsy Values**
- *Truthy values*: are treated as if they are true, and as number 1
- *Falsy value*: are treated as if they are false, and as number 0

**Checking Equality & Existence**
- The presence of an object or array can be considered truthy, it is often used to check for the existance of an element with in a page.

**Short Circuit Values**
- Logical operators are processed left to right, and they short circuit as soon as they have a result, but they retern the stopped the processing.

**Loops**
- *Loops*: check a condition to see if its true or false, and will run true until the condition becomes false.
- *Loop Counters*
  * Initialization: var i = 0;
  * Condition: i< 10;>
  * Update: i++
- *Looping*
  * First time loop is run, variable i is assigned value 0
  * Every time loop is run, condition is checked
  * Then code inside loop is run
  * Variable i can be used inside the loop
  * When statement have finished, variable i is incremented by 1
  * When condition is no longer true, loop ends
- *Key Loop Concepts*
  * 2 key words used with loops: break and continue
  * Loops are helpful when dealing with arrays if you want to run the same codefor each item in the array.
  * Performance issues: infinite loop is a when condition never returns false. 
- *For Loops*
  * Used to loop through the items in an array
  * Total number of items is stored in a variable called arrayLength
  * 3 more variables involved: roundNumber, msg, and i
  * The loop starts with the for keyword, then contains the condition inside of the parentheses. It will continue to run as long as the counter is less than the total number of items in the array
  * Each time the loop is run the round number increases by 1.
- *While Loops*
  * Each time the loop is run, another calculation is written into the variable called msg.
  * While loop will continue to run for as long as the condition in the parenthesis is true.
  * That condition is a counter indicating that, as long as the variable i remains less than 10, the statements in the subsequent code block will run.
  * Inside the code block there are 2 statements:
    1. first statement: uses the += operator, which is used to add new content to message variable.
      * Each time the loop runs a new calculation and line break is added to end of message being stored in it.
      * So, += works as shorthand for writting: msg = msg + 'new' msg
    2. second statement: increments the counter variable by one.
  * When loop is finished, the interpreter goes to the next line of code, which writes the msg vsrisble to the page.
- *Do While Loop*
  * Main difference betwenn a while loop and a do while loop is that the statements in the code block come beforethe condition, which means that the statements will run once whether or not the condition is met.

