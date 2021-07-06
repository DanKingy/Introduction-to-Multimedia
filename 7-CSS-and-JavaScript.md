# Web Sites

* Web pages represent visual information in the WWW
* Need more than a mark-up language to make web pages truly interactive



# HTML and Friends

* HTML5 requires other supporting technologies and content for modern web pages to work
  * Cascading Style Sheets
  * JavaScript
  * Scalable Vector Graphics
  * Dynamic Technologies (MySQL, PHP)
* HTML5 files contain the key content for web pages
* Most of the formatting is implemented using CSS
* Interactivity is implemented using JavaScript



# HTML Elements

* A HTML element is everything from the start tag to the end tag

  * \<p>This is a paragraph\</p>
  * \<a href="default.html">This is a link\<\a>
  * \<br>

* New semantic/structural elements:

  * \<article>
  * \<footer>
  * \<nav>
  * \<section>

  

# Cascading Style Sheets

* Style sheets can be used to define how different elements, such as fonts, colours, etc appear in a web document
* These style sheets can then be applied to any Web page
* Style Sheets can be:
  * External (most powerful, cleanest and popular)
    * Must be referenced from your HTML page \<link rel="stylesheet" href="style.css" type="text/css" />
  * Embedded
  * Inline



# CSS Rules/Selectors

* Each rule consists of a selector followed by a list of properties
* Selectors can just be names or existing tags, e.g. the paragraph tag \<p>



# \<div> Tag

* A container that styles can be applied to
* Has no default formatting information



# CSS Classes/IDs

* Classes can be used multiple times in HTML document
  * .important {color: blue; font-weight: bold;}
  * \<div class="important">Text here\</div>
* IDs used to refer to items which only occur once
  * #footer {font-size: small;}
  * \<div id="footer">Text here\</div>



# Units of Measurement

CSS specifies 8 units of length measurement, which are either relative or absolute

* em - Relative - height of the elements font
* ex - Relative -  height of x character of the font
* px - Relative - pixels
* in - Absolute - inches
* cm - Absolute - centimetres
* mm - Absolute - millimetres
* pt - Absolute - points (1 pt is 1/72 inches)
* pc - Absolute - picas (1 PC IS 12 points)



# JavaScript

* Must be embedded in the HTML document
* Most effective when used from a separate file



