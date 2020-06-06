# Ducket - HTML & CSS / JavaScript & JQuery Notes

## HTML & CSS Ch 15 "Layout"

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
