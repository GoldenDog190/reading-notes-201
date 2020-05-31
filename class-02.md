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
  * A *script* is a series of instructions that a computer can follow one by one, an each individual step is known as a statement. 
  - Statements end with a semicolon, and are case sensitive.
  - Statements are instructions, each starts on a new line, and can be organized into code blocks.

- *Comments*
  * Should be written to expain what your code does. Can use multi-line comments or single line comments.

- *Variable*
  * A script will have to store bits of information, and this can be stored in *variables*.
    - How to declare them: create the variable and giving it a name
    - How to assign them a value: once you have made a variable, you can tell it what information you want to store for you.
    - Data Types: Numeric Data Type, String Data Type, and Boolean Data Type
    - Using them to store a number: once a value has been assigned to a variable, you can use the variable name to represent that value.
    - Using them to store a string: 2 variables are declared, and they are used to hold strings.
    - Using quotes inside a string: you will sometimes want to use quotation marks within a string.
    - Using them to store a boolean: boolean variable can only be true or false, and booleans are used when your code can take more than one path.
    - Shorthand for creating variables: shorthand can be used to lessen the amount of typing, but it can also make your code harder to follow.
    - Changing the value of a variable: once you have assigned a value to a variable, you can then change what is stored in the same script.
    - Rules for naming variables: 
      * The name must begin with a letter, $, or underscore
      * The name can contain letters, numbers, $, or underscore
      * You cannot use keywords or reserved words
      * All variables are case sensitive
      * Use a name that describes the kind of information that the variable stores
      * If variable name is made up of more than one word, use a capital letter for the first letter of every word after the first word. 

- *Arrays*: a special type of variable that stores a list of values
  * Creating an array is called an array variable.
  * Values in arrays: are accessed as if they are in a numbered list, which starts with 0, not 1
  * Accessing & changing values: to access a value from an array, after the array name you specify the index number for that value inside brackets. You cna change the value of an item an array by selecting it and assigning it a new value.

- *Expressions* evaluate into a single value and rely on operators to calculate a value.
  *  Expressions can just assign a value to a variable or use 2 or more values to return a single value.

- *Operators* allow programers to create a single value from one or more values.
 * Arithmetic Operators: mathematical operators, which you can use with numbers.
 * String Operators: the + symbol. This is used to join strings on either side. Joining 2 or more string to create one new string is called concatenation.

## JavaScript Chapter 4 "Decisions and Loops" *only up to section on switch statements*: 
**Decision Making**
- Flowcharts can help you make decisions about which lines of code should be ran next.
- 2 components to a decision: an expression is evaluated, which returns a value, and a conditional statement says what to do in a given situation

**Evaluating Conditions & Conditional Statements**
- Evaluating conditions: to make a decision your code checks the current status of the script, which is commonly done by comparing two values using a comparison operator that returns a value of true or false.
- Conditional statement is based on a concept of if/then/else

**Operators**
- *Comparision Operators*
  * Evaluating conditions: can evaluate a situation by comparing one value in the script to what you expect it might be. 
  * The results will be a Boolean: true or false value
  * Comparision operator structure:
   - Example: (score >= pass)
  * Using Expressions w/ comparision operators:
   - The operand doesn't have to be a single value or variable name because an operand can be an expression.
   - Example: (score1 + score2) > (highScore1 + highScore2)

- *Logical Operators*
> allow you to compare results of more than one comparison operator.
  * Types of Logical Operators
   1. Logical And: &&
   2. Logical Or: ||
   3. Logical Not: !

**If Statements**
- The if statement evaluates a condition. If condition evaluates to true, any statements in subsequent code block are executed. If conditions are false, the code block will not run.

**If...Else Statements**
- The if...else statement checks a condition. If it is true, the first code block is executed. If resolves false the second code block is run instead.

# Additional Reading - [How to Write a Git Commit Message](https://chris.beams.io/posts/git-commit/) 

**How to Write a Git Commit Message**
- A well crafted Git commit message is a way to communicate context about changes made, tell you why they were made, and should be as concise and consistant as possible.  
- A commit log should be defined by three conventions: style, content, and metadata
- 7 Rules of a Git commit message:
  1. Separate subject from body with a blank line
  2. Limit subject line to 50 characters
  3. Capitalize subject line
  4. Don't end subject line with a period
  5. Use imperative mood in the subject line
  6. Wrap body at 72 characters
  7. Use the body to explain what and why vs how