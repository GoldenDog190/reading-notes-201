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
  * Uses two different elements: blockquote for larger quotes like a paragraph and q for shorter quotes that sit within a paragraph. Both are made into opening and closing tags with the quote inbetween.
- *Abbreviations & Acronyms* 
  * 
- *Citations & Definitions*
  * 
- *Author Details*
  * 
- *Changes to Content*
  * 

## CSS Chapter 10 "Introducing CSS":

**CSS**
 > *Cascading Style Sheet (CSS)*
 - CSS allows you to create rules that specify how content of element should appear
 - With CSS imagine that there is an invisible box around every HTML element.
 - CSS allows you to create rules that controlthe way each box is presented.
 - CSS properties affect how elements are displayed.

## JavaScript Chapter 2 "Basic JavaScript Instructions":

**Basic Javascript Instructions**
- Expressions: evaluates into a single value
1. Expressions that assign a value to a variable. Example: var color = 'beige'; --> The value of color is now beige.
2. Expressions that use 2 or more values to return a single value. Example: var area = 3 * 2; --> The value of the area is now 6.
- Operators
1. Assignment Operators
2. Comparison Operators
3. Logical Operators
4. Arithmetic Operators
5. String Operators

- Arithmetic Operators: mathematical operators, which you can use numbers
- String Operators: the + symbol. This is used to join strings on either side. Jioning 2 or more string to create one new string is called concatenation.

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

