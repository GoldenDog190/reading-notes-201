# Ducket - HTML & CSS / JavaScript & JQuery Notes

## HTML Introduction & Chapter 1 "Structure":

**How People Access the Web**
- Web Browsers: people access websites using software called web browsers.
   * Examples: Firefox, Internet Explorer, Chrome, etc.
- Web Servers: a special computer that hosts the websites that you look up on your browser.
- Devices: you get access to the web using your desktop computer, laptop computer, mobile phones, etc.
- Screen Readers - programs that read out all contents of a computer screen to a user.

**How Websites are Created**
- The HTML & CSS languages are used to create websites.

**How the Web Works**
1. First you connect to the web via an Internet Service Provider (ISP). Then you put a web address into the browser to visit the site.
2. Next your computer contacts the Domain Name System (DNS) servers.
3. The DNS server will send a unique number back to your computer that allows your browser to contact the web server that hosts the website you requested.
4. Finally, the web server then sends the page you requested back to your web browser.

**HTML**
> *Hypertext Markup Language (HTML)*
> is a text document that describes the structure of the web page, & is made up of character that are inside angled brackets, which are called elements. 
- HTML Elements: made up of two tags - opening tag and closing tag with the information you want to convay inbetween the opening tag and closing tag. 
- HTML uses elements to describe the structure of pages.
- Tags: Opening tag contain a left-angle bracket, a character in the middle, and a right-angle bracket on the end. Closing tags contain a left-angle bracket, /, a character in the middle, and a right-angle bracket.
- Attributes: provide additional information about the contents of the element, and appear in the opening tag of the element. Made up of 2 parts: a name and a value, seperated by an equals sign. 
- HTML Structure: contains at the very least the body, head, and title.
  * Body Element: everything between this element is shown inside the main browser window.
  * Head Element: it is placed before the body element, contains the information about the page, and cannot be see by the viewer of the site.
  * Title Element: this element is placed between the opening and closing head tags, and anything written between the <title> tags will appear in the title or tab bar at the top of the broswer window.

## HTML Chapter 8 "Extra Markup":

**Evolution of HTML**
* There are several different versions of HTML:
  1. HTML 4 released in 1997
  2. XHTML 1.0 released in 2000
  3. HTML5 work in progress

**DOCTYPES**
> *DOCTYPES* tell browsers which version of HTML you are using, and are put at the very top of your HTML structure. 
  * Put an left-angle bracket, right-angle bracket, and put the version of HTML you are using inside of the brackets: !DOCTYPE html

**Comments in HTML**
 - You should always put comments in your code, so that you and other people will know what code you are working on and can come back to it, as well as what that code does and what you are trying to do with it, so it can be debugged later. 
  * For comments put an left-angle bracket, right-angle bracket, and put this inside of the brackets: !-- comment in here --

**ID Attribute**
- Every HTML element can carry the id attribute, and is used to uniquely that element from other elements on the page. Its value should start with a letter or an underscore. Cannot use the same value twice on the same page. 

**Class Attribute**
- Every HTML element can also carry a class attribute. its value should describe the class it belongs to, and the class attribute on any element can be share the same value.

**Grouping Text & Elements in a Block**
- The div element allows you to group a set of elements together in one block level box. 
  * For the div element: put an left-angle bracket, right-angle bracket, and put this inside of the brackets: div

**Grouping Text & Elements Inline**
- The span element acts like an inline equivalent of the div element. 
- It is used to either: contain a section of text where there is no other suitable element to differentiaite it from surrounding text or contains a number of inline elelmenets.
- The span element is also used so that you can control the appearance of the content of these elements using CSS.
  * For the span element put an left-angle bracket, right-angle bracket, and put this inside of the brackets: span

**iFrames**
- It is like a window that has been cut into your page, and is used to imbed things, such as maps into the page. 
   * Created using an left-angle bracket, right-angle bracket, and put this inside of the brackets: iframe
   * Can also put a few attributes inside of the iframe element, such as src, height, width, scrolling, frameborder, and seamless.

**Information about your Pages**
- The meta element lives iside of the head element and contains information about that web page.
   * Created using an left-angle bracket, right-angle bracket, and put this inside of the brackets: meta
   *  Can also put a few attributes inside of the meta element, such as description, keywords, robots, author, pragma, and expires.

**Escape Characters**
- They are characters that are used in and reserved by HTML code. 
   * Example: left-angle and right-angle brackets

**Block Elements** 
- Block elements that will always appear to start on a new line in the browser of the window.
  * For block elements put an left-angle bracket, right-angle bracket, and put this inside of the brackets: h1 
  * Other Examples: h2, p, ul, & li

**Inline Elements** 
- Inline elements that will always appear to continue on the same line as their nieghboring elements.
 * For inline elements put an left-angle bracket, right-angle bracket, and put this inside of the brackets: a
 * Other Examples: b, em, & img

## HTML Chapter 17 "HTML5 Layout" Notes:

**HTML5 Layout Elements**

> New HTML5 elements indicate the purpose of different parts of a web page and help to describe its structure. Also, provides clearer code, and helps the older browsers to understand the new code elements. To make HTML5 elements work in Internet Explorer 8, extra JavaScript is needed.

- The new layout elements include:
  * Header & Footer
  * Navigation
  * Articles
  * Asides
  * Sections
  * Heading Groups
  * Figures
  * Sectioning Elements
  * Linking around block-level elements
  * Helping older browsers understand

## HTML Chapter 18 "Process & Design":
**Process:**
- Questions to ask yourself as you build your website:
  * *Who is the site for?*
  * *Why people visit your website?*
  * *What your visitors are trying to achieve?*
  * *What information your visitors need?*
  * *How often people will visit your site?*

- Site Map: a diagram of the pages that will be used to structure the site.

- Wireframe: a simple sketch of the key information that needs to go on each page of the site.

**Design:**
- Getting message across using design:
  * Content - web pages use the content to communicate
  * Prioritizing - make parts of the page look distinct from surrounding content to draw attention to those parts of the page
  * Organizing - group together related content into blocks/ chunks to make the page look simpler and eaiser to understand

- Visual Hierarchy: the order in which your eyes perceive what they see
  * Create a visual hierarchy by contrasting size, color, style, and using images to get key message across and make things easier to find.

- Grouping & Similarity:
  * Organize visual elements and information into groups by proximity, closer, continuance, white space, color, and borders. Also, use a consistant style and headings to seperate topics.

- Designing Navigation: 
  * Site navigation helps people find where they want to go on the site, what your site is about, and how it is organized.
  * Principles of navigation: be concise, clear, selective, provides content, interactive, and is consistant. 
  * Large sites might have primary, secondary, and teriary navigation

## JavaScript Introduction & Chapter 1 "The ABC of Programmimg":

**JavaScript (JS)**
> *Javascript* : A series of instructions that a computer can follow one by one. Each instruction is known as a statement, which ends with a semicolon. Allows you to make web pages more interactive, and encompasses many of the tradition rules of programming.

**How JS makes web pages more interactive**
- Access content
- Modify content
- Program rules
- React to events

**Script**
> A *Script* is a series of instructions that a computer follows step-by-step to achieve a goal.
- To write a script: state your goal, and then list the tasks needed to complete that goal in order to achieve it. Each task can be broken down intp a sequence of steps. Finally, code each step. 
- Keep in mind that a computer solves tasks in a different way than you do, and it will only do things as you tell it to, so make sure that the code is in the correct order to achieve your goal.

**Computers create models of the world using data**
- Object: each physical thing is represented as an object. Each object can have its own properties, events, and methods, which create a working model of that object.
- Properties: each property has a name and value, which tells you something about each object.
- Events: interactions with objects, and can change the values of properties in these objects. 
- Methods: how things interact with an object, and they can retrieve or update the values of an object's properties.
- Putting it all together: the events, methods, and properties of an object all relate to each other. Events trigger methods, and methods retrieve or update an objects properties
- Web browsers are programs built using objects.
- The document object represents an HTML page.
- How a browser sees a web page: 
 * the browser receives an HTML page
 * it creates a model of the page and stores it in memory
 * it shows the page on screen using a rendering engine

**Writing a script for a webpage:**
- HTML, CSS, and Javascript: these 3 fit together, and each language forms a seperate layer with a different layer. These 3 layers form what is called progressive enhancement.
  * HTML - content layer
  * CSS - presentation layer
  * Javascript - behavior layer
- JS is written in plain text, just like HTML and CSS.
- Use the HTML script element to link a JS file to the HTML.
- JS uses objects and methods to call a mothod of an object.
- JS runs where it is found in the HTML, but doesn't change the HTML structure.
