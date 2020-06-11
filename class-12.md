# Assorted Online Readings
## Article on Chart.js API [Charts.js API](https://www.webdesignerdepot.com/2013/11/easily-create-stunning-animated-charts-with-chart-js/)

**Charts.js API**
- Charts are better for displaying data than tables
- Chart.js is a JavaScript plugin that uses HTML5 to draw graphs onto a page.
- It can make all kinds of charts: bar charts, line charts, pie charts, etc.

## Chart.js docs [Chart.js docs](https://www.chartjs.org/docs/latest/)

**Charts.js docs**
- Can download Chart.js from GitHub or Chart.js CND. 
- Just a single canvas node to render the chart 
- Can be intergrated with plain JavaScript or different module loaders
- Chart.js is rendered on user provided canvas elements
- has higher pixel ratio
- options: scriptable, indexable, option context
- can use different colors, fonts
- rendering is very quick
- configuration is used to change how the chart behaves
- animates charts out of the box
- layout configuration is passed into the option.layout name space
- built in chart types
- axes are used to determine how data maps to a pixel value on the chart
- developer features allow extending and enhancing Chart.js in many different ways.

## Article on Canvas API: [Basic Usage](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Basic_usage)

**Basic Usage**
- The canvas element looks like an image element but it only has two attributes width and height
- Can be styled like any normal image though
- provides fallback content
- canvas requires a closing tag unlike img
- creates a fixed-size drawing surface that exposes one or more rendering context, which are used to create and manipulate the content shown

## Article on Canvas API: [Drawing shapes with canvas](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes) 

**Drawing shapes with canvas**
- The canvas grid/ coordinated space helps to set up the area that you will be drawing in
- canvas only supports rectangles and paths
- you can draw rectangles by combining one or more paths
- there are three functions that draw rectangles
  * fillRect, strokeRect, and clearRect
- each function take the same parameters: x, y, width, and height
- functions for drawing paths: beginPath, closePath, stroke, fill
- to move the pen use: moveTo(x,y)
- to draw lines: lineTo(x,y)
- to make arcs use function arc or arcTo
- you can also make brazier and quadratic curves, rectangles, combinations, and path2D objects

## Article on Canvas API: [Applying styles and colors](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Applying_styles_and_colors)

**Appyling styles and colors**
- two imprtant properties to use for color: fillStyle and strokeStyle
- color is a string representing a CSS color, gradient object or pattern object
- you can also draw semi-transparent shapes with glabalAlpha
- there are seven properties that allow us to line style: lineWidth,lineCap, LineJoin, miterLimit, etc.
- we can fill and stroke shapes using linear and radial gradients
- we can create patters using a series of loops
- you can also create shadows
- when you use fil you can optionally provide a fill rule algorithm

## Article on Canvas API: [Drawing text](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_text)

**Drawing text**
- provides two methods to render text: fillText and strokeText
- you cna also style text with the font poperty, and several other properties
- you cna measure text using measureText