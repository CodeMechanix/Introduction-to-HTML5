## HTML Basic

### Lecture 1: What is HTML?

HTML stands for Hypertext Markup Language.

- "Hypertext" refers to the hyperlinks that an HTML page may contain. 
- "Markup language" refers to the way tags are used to define the page layout and elements within the page.

Technoliges that Drive The Web:

HTML - Structure
CSS - Style
JavaScript - Behavior

### Lecture 2: Relevant History of HTML

In 1995, the IETF organizes a working group of HTML and manages to publish, on September 22 of that same year, the HTML 2.0 standard. Despite its name, HTML 2.0 is the first official HTML standard.

As of 1996, the HTML standards are published by another standard organization called W3C (World Wide Web Consortium).

The HTML 3.2 version was published on January 14, 1997 and is the first HTML recommendation published by the W3C.

This revision incorporates the latest advances of the websites developed up to 1996, such as Java applets and text that flows around the images.

HTML 4.0 was published on April 24, 1998 (being a corrected version of the original publication of December 18, 1997)

The last official HTML specification was published on December 24, 1999 and is called HTML 4.01.

For this reason, in 2004, the companies Apple, Mozilla and Opera showed their concern about the lack of interest of the W3C in HTML and decided to organize in a new association called WHATWG (Web Hypertext Application Technology Working Group).

The current activity of the WHATWG is focused on the future HTML5 standard, whose first official draft was published on January 22, 2008.

Due to the strength of the companies that make up the WHATWG group and the publication of the HTML 5.0 drafts, in March In 2007 the W3C decided to resume the standardizing activity of HTML.

Parallel to its activity with HTML, W3C has continued with the standardization of XHTML, an advanced version of HTML and based on XML.

The first version of XHTML is called XHTML 1.0 and was published on January 26, 2000 (and subsequently revised on August 1, 2002).

XHTML 1.0 is an adaptation of HTML 4.01 to the XML language, so it maintains almost all its tags and features, but adds some restrictions and elements of XML.

The XHTML 1.1 version has already been published in draft form and aims to modularize XHTML.

It has also been published the draft of XHTML 2.0, which will be a very important change from previous versions of XHTML.

Reference from: disenowebakus.net

Resource: 
1. https://caniuse.com/
2. https://validator.w3.org/

### Lecture 3: Anatomy of an HTML Tag

[ 'Opening Tag' - Content - 'Closing Tag' ]
 ```html
1. Paragraph: <p></p>
2. Break: <br>
3. Horizontal Rule: <hr>
```
### Lecture 4: Basic HTML Document Structure

The basic structure of any HTML document consists of the following sections or elements:

- The DTD (!DOCTYPE declaration).
- The main container (html element).
- The head section (head element).
- The body section (body element).

 ```html
The <!DOCTYPE html> declaration defines this document to be HTML5
The <html> element is the root element of an HTML page
The <head> element contains meta information about the document
The <title> element specifies a title for the document
The <body> element contains the visible page content
```
### Lecture 5: HTML Content Models

A block-level element always starts on a new line and takes up the full width of a page, from left to right. A block-level element can take up one line or multiple lines and has a line break before and after the element.

Block level elements in HTML:
```html
<address>	<article>	<aside>	<blockquote>	<canvas>	<dd>	<div>	<dl>	<dt>	<fieldset>	
<figcaption>	
<figure>	<footer>	<form>	<h1>-<h6>	<header>	
<hr>	<li>	<main>	<nav>	<noscript>	<ol>	<p>	<pre>	<section>	<table>	<tfoot>	<ul>	<video>
```

Inline element does not cause a line break (start on a new line) and does not take up the full width of a page, only the space bounded by its opening and closing tag. It is usually used within other HTML elements.

Inline elements in HTML:
```html
<a>	<abbr>	<acronym>	<b>	<bdo>	<big>	<br>	<button>	<cite>	<code>	<dfn>	<em>	
<i>	
<img>	<input>	
<kbd>	<label>	<map>	<object>	<output>	<q>	
<samp>	<script>	<select>	<small>	<span>	<strong>	<sub>	<sup>	<textarea>	<time>	<tt>	<var>
```

### Lecture 6: Heading Elements (and some new HTML5 semantic comments)

Semantic elements = elements with a meaning.A semantic element clearly describes its meaning to both the browser and the developer.
```html
Examples of non-semantic elements:  <div> and <span>   - Tells nothing about its content.

Examples of semantic elements:   <form>, <table>, and <article>   - Clearly defines its content.
```

### Lecture 7: Lists
Unordered HTML List
```html
An unordered list starts with the   <ul>  tag. Each list item starts with the   <li>  tag.

<ul style="list-style-type:circle;">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>
```
Ordered HTML List
```html
An ordered list starts with the   <ol>  tag. Each list item starts with the   <li>  tag.

<ol type="A">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>	
```
- HTML Description Lists
HTML also supports description lists. A description list is a list of terms, with a description of each term.
```html
<dl>
  <dt>Coffee</dt>
  <dd>- black hot drink</dd>
  <dt>Milk</dt>
  <dd>- white cold drink</dd>
</dl>
```

### Lecture 8: HTML Character Entity References
Reserved characters in HTML must be replaced with character entities. Characters that are not present on your keyboard can also be replaced by entities.

[See Link](https://www.w3schools.com/html/html_entities.asp)

### Lecture 9: Creating Links
```html
Hyperlinks are defined with the HTML   <a>  tag:

<a href="url">link text</a>
```

### Lecture 10: Displaying Images
Images can improve the design and the appearance of a web page.
```html
<img src="pic_trulli.jpg" alt="Italian Trulli">
```
