# Ducket - HTML & CSS / JavaScript & JQuery Notes

## HTML & CSS Ch 16 "Images" (pp 406-427)
**Controlling Sizes of Images in CSS**
- You can control the size of an image using the width and height properties in CSS.

**Aligning Images CSS**
- The float property is added to the class that was created to represent the size of the image.
- New classes are created with names such as align-left or align-right to align the images 

**Centering Images CSS**
- Use display:block to make it into a block level element, and then on the containing element you can use text-align property with a value of center. On the image itself, use the margin property and set the values of the left and right to auto.

**Background Images**
- Use the backgground-image element to place an image behind any HTML element.

**Repeating Images**
- For repeating images use background-attachment or background-repeat. 
- background-attachment can have fixed and/or scroll values
- background-repeat can have 4 values: repeat, repeat-x, repeat-y, and no-repeat

**Background Position**
- When an image is not being repeated, you can use the background-position property.

**Shorthand**
- The background property actsas a shorthand for all of the other background properties.
- The properties below must be apecified in the following order: backgound-color, background-image, background-repeat, background-attachment, and finally background-position

**Image Rollovers & Sprites**
- *Image rollover*: a link or button that changes to a second style when a user moves their mouse over it and a third style when they click on it.
- *Sprite*: when a single image is used for several different parts of an interface.

**CSS3: Gradients**
- The gradient is created using the background-image property.

**Contrast of Background Images**
- If you want to overlay text on a background image, the image must be low contrast in order for the text to be legible.

## HTML & CSS Ch 19 "Practical Information" (476-492)
**Search Engine Optimization (SEO)**
- *SEO*: is the practice of trying to help your site appear nearer the top of the search engine results.
- On-page techniques: are the methods you can use on your web pages to improve their rating in search engines.
- Off-page techniques: getting other sites to link to you.
- On-page SEO can appear in 7 places on a webpage: page title, URL/ web address, headings, text, link text, image alt text, & page desriptions

**Identifying Keywords & Phrases**
- Six steps that help identify the right keywords and phrases:
  * brainstorm
  * organize
  * research
  * compare
  * refine
  * map

**Analytics: learning about your visitors**
- when people come to your site, you can start analyzing how they found it, what they were looking at, and when they left by using Google Analytics

**How to find out how many people visit your site:**
- The overview page of Google Analytics will give you a snapshot of information you want to know about your visitors.

**What are your visitors looking at?**
- The content link on Google Analytics allows you to learn what your visitors are looking at on your site.

**Where your visitors are coming from?**
- The traffic sources link on Google Analytics allows you to learn where your visiors are coming from.

**Domain Names & Hosting**
- *Domain name* is your websites address.
- Hosting is done by uploading your site to a web server that is run by a web hosting company.

**FTP**
- You use File Transfer Protocol (FTP) to transfer your code and images from your computer to your hosting company.

## HTML & CSS Ch 9 "Flash, Video, & Audio"(pp201-206)
**Flash**
- *Flash*: technology that is used to add animations, video, and audio to websites.
- Tool for creating animations, and playing audio and video 
- Flash is not used as much as it used to be, and now browsers are using HTML5 video and audio tags more.

## Additional Reading [MDN Article on Audio and Video Elements](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Video_and_audio_APIs)

**Video & Audio APIs**
- HTML5 Video & Audio
  * video and audio elements allow us to embed video and audio into webpages
  * can use the control attribute to defualt set of playback controls
- HTMLMediaELement API
  * allows you to control video and audio players programmatically
  * create the HTML, CSS, and implement the JS yourself, so you can have full control over every setting you want to have implemented into the video and audio players, such as the play/pause button, rewind/ fast forward function, time elapsed displays, and fixing play/pause.    
