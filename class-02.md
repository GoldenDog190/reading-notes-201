# Ducket - HTML & CSS / JavaScript & JQuery Notes

## HTML Chapter 2 "Text":
**Markups**
> *Markups* are the tags that you add to the content of the page
- Structural Markup: the elments you can use to describe both headings and paragraphs
- Semantic markup: provides extra information, such as wehere emphasis is placed in a sentence, quotations, meaning of acrroyms, etc.

**Structural Markups**
- *Headings*
  * Used to make the headings for the page. HTML has six levels of headings. H1 for main heading, and h2 - h6 are subheadings.
  * Has an opening and closing tag with the heading inbetween them. Make the opening tag using an left-angle bracket, right-angle bracket, and put this inside of the brackets: h1, h2, h3, h4, h5, or h6.
- *Paragraphs*
  * Used to make paragraphs on the page.
  * Has an opening and closing tag with the paragraph inbetween them. Make the opening tag using an left-angle bracket, right-angle bracket, and put this inside of the brackets: p
- *Bold & Italic*
  * Has an opening and closing tag with what words you want to appear bold or italic inbetween them. Make the opening tag using an left-angle bracket, right-angle bracket, and put this inside of the brackets: b for bold or i for italic.
- *Superscript & Subscript*
  * Superscript has an opening and closing tag with the characters that should be superscript, such as dates, inbetween them. Make the opening tag using an left-angle bracket, right-angle bracket, and put this inside of the brackets: sup
  * Subscript has an opening and closing tag with the characters that should be subscripted, such as in footnotes or chemical formulas, inbetween them. Make the opening tag using an left-angle bracket, right-angle bracket, and put this inside of the brackets: sub
- *White Space*
  * White space is used to make code more easy to read, and put some extra space inbetween code.
- *Line Breaks & Horizantal Rules*
  * Line break have an left-angle bracket, br, a space inbetween the br and /, /, and an right-angle bracket. This adds a breakline inside the middle of the paragraph.
  * Horizantal rules have an left-angle bracket, hr, a space inbetween the br and /, /, and an right-angle bracket. This is used to create a break between themes.

**Visual Editors & Their Code Views**
- *Visual Editors*: resemble word processors, and allows you to control the presentation of text.
- *Code Views*: show you yht code created by the visual editor, so you can manually edit it or enter new code.

**Semantic Markups**
- *Strong & Emphasis*
  * Strong has an opening and closing tag with the content that you want to put strong importance on inbetween. It is created using an left-angle bracket, right-angle bracket, and put this inside of the brackets: strong.
  * Emphasis has an opening and closing tag with the content that you want to put emphasis on. Created using an left-angle bracket, right-angle bracket, and put this inside of the brackets: em
- *Quotations*
  * Uses two different elements: blockquote for larger quotes like a paragraph and q for shorter quotes that sit within a paragraph. Both are made into opening and closing tags with the quote inbetween the tags.
- *Abbreviations & Acronyms* 
  * If you want to use abbreviation or acronyms use the abbr element, which is made into opening and closing tags with the abbreviation or acronym inbetween the tags.
- *Citations & Definitions*
  * For citations use the cite element, which is made into opening and closing tags with the citation for the book or film inbetween the tags.
  * For definitions use the dfn element, which is made into opening and closing tags with the definition inbetween the tags.
- *Author Details*
  * Use the address element to contain the contact details for the author of the page. Make the address element into opening and closing tags with the conatct details inbetween the tags.
- *Changes to Content*
  * Use the ins element to show content that has been inserted into a document between the opening and closing tags.
  * Use the del element to show text that has been deleted between the opening and closing tags.
  * Use the s element to visibly put a line through the content between the opening and closing tags.

## CSS Chapter 10 "Introducing CSS":

**CSS**
 > *Cascading Style Sheet (CSS):* CSS allows you to create rules that specify how content of element should appear. Also, with CSS imagine that there is an invisible box around every HTML element, and that CSS allows you to create rules that control the way each box is presented.

 **CSS associates style rules with HTML elements:**
 - CSS works by associating rules with HTML elements, and these rule govern how the content of specified elements should be displayed. A CSS rule contains a selector and declaration.
   * Selector: indicates which element the rule applies to
   * Declaration: indicates how the elements refered to in the selector should be styled

 **CSS properties affect how elements are displayed:**
 - CSS declarations sit inside curly brackets and made up of two parts: a property and a value.
   * Properties: indicate the aspects of the element you want to change
   * Value: specifies the setting you want to use for the chosen properties

 **Using External CSS**
 - The link element is used in HTML document to tell the browser where to find CSS file used to style the page.

 **Using Internal CSS**
 - You can also use the style element, which sits within the head of the page, to tell the browser that the CSS is placed within the HTML structure.

 **CSS Selectors**
 - Universal Selector
 - Type Selector
 - Class Selector
 - ID Selector
 - Child Selector
 - Descendent Selector
 - Adjacent Sibling Selector
 - General Sibling Selector

**How CSS Rules Cascades**
- If 2 selectors are identical, the latter of the 2 will take precedence
- If one selector is more specific that the others, the more specific rule will take precedence.
- You can add !important after any property value to indicate that it is more important than the others.

**Inheritance**
- Properties can inherit values from their parent element, and they are called child properties.

**Why Use External Style Sheets?**
- Makes the HTML code easier to read.
- Easier to make changes to the CSS.
- Good practice to have the contents of the site seperate from the rules that determine how it will appear.

**Different Versions of CSS & Browser Quirks**
- Different versions of CSS include: CSS1 from 1996, CSS2 from 1998, and CSS3, which is ongoing.
- Browser quirks, also known as CSS bug shows up when a CSS property doesn't display as expected. 

## JavaScript Chapter 2 "Basic JavaScript Instructions":

**Basic Javascript Instructions**
- *Statements*
  * 
- *Comments*
  * 
- *Variable*
  * 
    - How to declare them:
    - How to assign them a value:
    - Data Types: 
    - Using them to store a number:
    - Using them to store a string:
    - Using quotes inside a string:
    - Using them to store a boolean: 
    - Shorthand for creating variables:
    - Changing the value of a variable:
    - Rules for naming variables: 

- *Arrays*
  * Creating an array
  * Values in arrays:
  * Accessing & changing values:

- *Expressions* evaluate into a single value and rely on operators to calculate a value.
  *  Expressions can just assign a value to a variable or use 2 or more values to return a single value.

- *Operators* allow programers to create a single value from one or more values.
 * Arithmetic Operators: mathematical operators, which you can use numbers
 * String Operators: the + symbol. This is used to join strings on either side. Joining 2 or more string to create one new string is called concatenation.

## JavaScript Chapter 4 "Decisions and Loops" *only up to section on switch statements*: 

**Operators**
- *Comparision Operators*
  * Evaluating conditions: can evaluate a situation by comparing one value in the script to what you expect it might be. 
  * The results will be a Boolean: true or false

- *Logical Operators*
> allow you to compare results of more than one comparison operator.
  * Types of Logical Operators
   1. Logical And: &&
   2. Logical Or: ||
   3. Logical Not: !

**Loops**
> *Loops* - check a condition.
- If it returns true, a code block will run. Condition will be checked again and still returns true, code block will run again. Will repeat until condition returns false.
- 3 Types of Loops
 1. For
 2. While
 3. Do While
- Loop Counters: 
 1. Initialization: var i = 0;
 2. Condition: i , 10;
 3. Update: i++
- First time loop is run, variable i is assigned value 0
- Every time loop is run, condition is checked
- Then code inside loop is run
- Variable i can be used inside the loop
- When statement have finished, variable i is incremented by 1
- When condition is no longer true, loop ends
- Using While Loops: each time the loop is run, another calculation is written into the variable called msg.
- While loop will continue to run for as long as the condition in the parenthesis is true.
- That condition is a counter indicating that, as long as the variable i remains less than 10, the statements in the subsequent code block will run.
- Inside the code block there are 2 statements:
1. first statement: uses the += operator, which is used to add new content to message variable.
- Each time the loop runs a new calculation and line break is added to end of message being stored in it.
- So, += works as shorthand for writting: msg = msg + 'new' msg
2. second statement: increments the counter variable by one.
- When loop is finished, the interpreter goes to the next line of code, which writes the msg vsrisble to the page.

# Additional Reading - [How to Write a Git Commit Message](https://chris.beams.io/posts/git-commit/) 

