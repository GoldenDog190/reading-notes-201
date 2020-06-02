# Ducket - HTML & CSS / JavaScript & JQuery Notes

## HTML Chapter 5 "Images":
**Choosing Images**
- Images for your site should set the tone for the visitor to your site, be relevant, convey information, be instantly reconisable, and fit the color palette.

**Storing Images on Your Site**
- Create a folder for all of the images on your site, and on bigger websites they will have subfolders for images.

**Adding Images**
- Use the image element with the src attribute telling you where the site came from, alt alttribute to provide a description of the image, and a title attribute to provide additional information on the image.

**Height & Width**
- height - specifies the height of the image in pixels
- width - specifies the width in pixels

**Where to Place Images in Code**
- Before a paragraph
- Inside the start of a paragraph
- In the middle of a paragraph

**3 Rules for Creating Images**
  1. Save images in the right format
  2. Save images at the right size
  3. Measure images in pixels  

**Image Formats**
- JPEG: used when you have many different colors in the image
- GIF: a picture that uses flat color, such as a logo, illustrations, and diagrams

**Image Demensions**
- Images should be saved at the same width and hieght in pixels that you want on the website.

**Cropping Images**
- When cropping images be careful to not lose the valuble part of the picture that will convey the information.

**Measuring Images & Resolution**
- Images are made up of tiny squares known as pixels
- The resolution of the screen is the number of pixels represented on it
- Only think of the size of the image in terms of dimensions in pixels

**Vector Images**
- Vector images are vreated by placing points on a grid, and drawing the lines between those points, which then can be filled with color.

**Animated GIFS**
- Show several frames of an image in a sequence, and can be used to create simple anmations.

**Transparency**
- Creating an image that is partially transparent is done by selecting 2 formats: transparent gif & png

**HTML5**
- figure element used to contain the image and put in a caption with the image
- figcaption element is used for the caption that descripes the image

## CSS Chapter 11 "Color":
**Foreground Color**
- Foreground color: color property that allows you to specifynthe color of the text inside an element.
- Specify in 3 ways: RGB values, Hex codes, and color names

**Background Color**
- background-color property sets the background color to the HTML box you choose, and you don't have to specify a background color because the default is white.

**Understanding Color:** every color on screen in a mixture between red, blue, & green
- RGB values: values for re, blue, and green expressed as numbers between 0 and 255
- Hex codes: hex values represent value for red, green, and blue in hexadecimal code
- Color names: colors are represented by predifred names
- Hue: is near to the colloquiual idea of color
- Saturation: refers to the amount of gray in a color
- Brightness: refers to how much black is in a color

**Contrast**
- When choosing foreground and background color be careful of the contrast between them, so that the visitor of the site can read the text without any issues.

**CSS3**
- Opacity property allows you to specify the opacity of an element
- HSL colors: hue, saturation, and lightness
- hsl color property is an alternative way to specify colors. Contains the individual values for hue, saturation, and lightness
- hsla color property allows you to specify colors, just like in hsl, but also includes alpha for transparency.

## CSS Chapter 12 "Text": 
**Typeface Terminology**
- Serif font: have extra detail on the ends of the main strokes of the letters
- Sans-serif font: have striaght ends to letters
- Monospace font: every letter is the same width
- Font weight: adds emphasis, affects the amoutn of white space and contrast on the page
- Font syle: italic, oblique, and normal 
- Font stretch: can condense or expand letters space between each other

**Choosing a Typeface**
- Serif
- Sans-serif
- Monospace
- Cursive fonts: either have joining strokes or other cersive characteristics
- Fantasy font: usually decorative fonts and used for titles 

**Techniques that offer a wider choice of typeface:**
- Font-family
- Font-face
- Service-based font-face
- Images
- SIFR
- Cufon

**Specifying Typefaces**
- font-family property allows you to specify the typeface that should be used for any textinside the elements to which CSS rules apply.

**Size of Type**
- font-size property enables you to specify a size for the font. Several ways to speify font: pixes, percentages, and ems

**Type Scales**
- Type scales are set to a scale or ratio thats already has been used for hundreds of years. Default size of text is generally 16 pixels, but you can go from 12 to 24 pixels.

**Units of Type Size**
- Pixels
- Percentages
- EMS

**Some More Font Choice**
- @font-face allows you to use a font thats not installed on the computer
- Bold - font-weight: bold
- Italic - font-style: italic
- text-transform:
  * uppercase 
  * lowercase
  * capitalize
- underline & strike
  * text-decoration: underline or strike
- Leadding - line-height: used for the vertical space between lines of text
- etc...

**Attribute Selectors:** allow you to create rules that apply to elementsthat have an attribute with a specific value. 
- Types of selectors include:
  * Existence
  * Equality
  * Space
  * Prefix
  * Substring
  * Suffix


