# HTML Tags & Their Purposes

## Basic Structure & Document Tags

### What is the purpose of the `<!DOCTYPE>` declaration in HTML?
- In this `<!DOCTYPE>`, it is not case sensitive. you can use lowercase as well.
- It follows HTML5 documents.
- Ensures consistent rendering.

### What does the `<html>` tag represent?
The `<html>` tag is the root element of an HTML document. All content on the page is contained within this tag.

### What is the role of the `<head>` tag in an HTML document?
The `<head>` tag contains meta-information about the HTML document, such as title, links to stylesheets, and meta tags for SEO or character encoding.

### What kind of information goes inside the `<title>` tag?
The `<title>` tag specifies the title of the HTML document. It appears in the browser tab or window and is important for SEO.

### How is the `<body>` tag used?
The `<body>` tag contains the visible content of the HTML document, such as text, images, and interactive elements.

---

## 🧠 Metadata Tags

### What is the `<meta>` tag used for?
The `<meta>` tag provides metadata about the HTML document, such as description, keywords, author, and character encoding.

### What does the `<base>` tag do in an HTML document?
The `<base>` tag specifies a base URL for relative URLs in the document.

### When and why do we use the `<link>` tag?
The `<link>` tag is used to link external resources, such as stylesheets, to the HTML document.

### How does the `<style>` tag differ from the style attribute?
The `<style>` tag is used to define CSS rules within the document, while the `style` attribute applies inline CSS directly to individual HTML elements.

---

## 🧾 Text Content Tags

### What is the difference between `<h1>` to `<h6>` tags?
- Browser apply decreasing font sizes from `<h1>` to `<h6>` by default.
- Html Headings Are Titles Or Subtitles That You Want To Display On A Webpage.

### How is the `<p>` tag used?
- Purpose : The `<p>` tag is used to define a paragraph of text in HTML.
- Block-Level Element: It is a block-level element, meaning it starts on a new line by default.
- Whitespace Handling: The `<p>` tag does not preserve extra whitespace (like multiple spaces or intentional line breaks). Any extra white space is generally collapsed into a single space.

### What does the `<br>` tag do, and is it self-closing?
- It is just breaking line within a text, use `<br>` tag.
- It is considered self-closing tag. Which means it does not require a separate closing tag. In HTML5, both `<br>` and `<br/>` are valid syntaxes.

### How do you create horizontal lines using the `<hr>` tag?
- It is just horizontal line , use `<hr>` tag.
- The `<hr>` tag is self-closing and does not require a closing tag.
- In HTML5, the `<hr>` tag is not just a visual element, it also carries semantic meaning. It represents a thematic break in the content.

### What is the `<pre>` tag used for?
- In this tag is Preformatted text. You can use `<pre>` tag.
- Whitespace Handling: To preserve whitespace and line breaks exactly as written (such as in poems or code snippets), use the `<pre>` tag.

### What is the purpose of the `<blockquote>` tag?
The `<blockquote>` tag is used for quoting large sections of text from an external source.

### How does `<code>` differ from `<samp>` and `<kbd>`?
- `<code>` represents computer code.
- `<samp>` represents sample output from a program.
- `<kbd>` represents user input (e.g., keyboard input).

### What is the `<abbr>` tag used for?
The `<abbr>` tag is used to define an abbreviation or acronym.

### What does the `<cite>` tag represent?
The `<cite>` tag is used to reference the title of a creative work, such as a book, article, or movie.

### What does the `<mark>` tag do?
The `<mark>` tag highlights text, usually for emphasis or as search results.

### What is the difference between `<b>` and `<strong>`?
- `<b>` is used for bold text with no semantic meaning.
- `<strong>` represents important text, typically displayed as bold.

### What is the difference between `<i>` and `<em>`?
- `<i>` is used for italic text with no semantic meaning.
- `<em>` represents emphasized text, usually displayed as italic.

### What does the `<small>` tag represent?
The `<small>` tag is used to render text in a smaller font.

### How is the `<del>` tag different from `<ins>`?
- `<del>` represents deleted text.
- `<ins>` represents inserted text.

### What is the use of the `<time>` tag?
The `<time>` tag is used to represent a specific time or date.

---

## 📋 Lists

### What are the differences between `<ul>`, `<ol>`, and `<dl>`?
- `<ul>` represents an unordered (bulleted) list.
- `<ol>` represents an ordered (numbered) list.
- `<dl>` represents a description list.

### How do `<li>` and `<dt>/<dd>` tags work in lists?
- `<li>` defines a list item in both `<ul>` and `<ol>`.
- `<dt>` defines a term in a description list.
- `<dd>` defines the description of a term in a description list.

---

## 🔗 Hyperlinks & Navigation

### What is the `<a>` tag used for?
The `<a>` tag is used to define hyperlinks.

### What attributes can you use with `<a>` (e.g., href, target, rel)?
- `href`: Specifies the URL of the link.
- `target`: Specifies where to open the linked document (e.g., `_blank` for a new window).
- `rel`: Specifies the relationship between the current document and the linked document.

### What is the purpose of the `<nav>` tag?
The `<nav>` tag is used to define a section of the document dedicated to navigation links.

---

## 🖼️ Images, Media & Embeds

### What is the `<img>` tag used for?
The `<img>` tag is used to embed images in the document.

### What’s the use of the alt, width, and height attributes in `<img>`?
- `alt`: Provides alternative text for the image (for accessibility).
- `width`: Specifies the image width.
- `height`: Specifies the image height.

### What is the `<figure>` tag, and how does it relate to `<figcaption>`?
The `<figure>` tag represents content such as an image or illustration, while `<figcaption>` provides a caption for the content.

### How is the `<picture>` tag used for responsive images?
The `<picture>` tag allows you to define multiple image sources for different screen sizes or resolutions.

### What’s the difference between `<audio>` and `<video>` tags?
- `<audio>` is used to embed audio content.
- `<video>` is used to embed video content.

### What is `<source>` and how is it used with media?
The `<source>` tag specifies multiple media resources for `<audio>` and `<video>` elements.

### What does `<track>` do in videos?
The `<track>` tag is used to specify text tracks for `<video>` elements, such as subtitles or captions.

### What is an `<iframe>` and when should it be used?
The `<iframe>` tag is used to embed another HTML page within the current document.

### What is the purpose of the `<embed>` tag?
The `<embed>` tag is used to embed external content, such as a multimedia file or plugin, into the document.

### How does `<object>` differ from `<embed>`?
The `<object>` tag is used to embed external content (e.g., PDF, Flash), but it offers more flexibility than `<embed>`.

---

## 🧰 Forms

### What are the essential tags used in forms (`<form>`, `<input>`, `<textarea>`, `<button>`, `<label>`)?
- `<form>` defines the form element.
- `<input>` is used to create input fields.
- `<textarea>` is used for multi-line text input.
- `<button>` defines a clickable button.
- `<label>` provides a label for form elements.

### What’s the difference between `<input type="text">`, `<input type="email">`, `<input type="submit">`, etc.?
- `<input type="text">`: Creates a text input field.
- `<input type="email">`: Creates an email input field (with validation).
- `<input type="submit">`: Creates a submit button.

### How does the `<select>` tag work with `<option>` and `<optgroup>`?
The `<select>` tag creates a dropdown list, `<option>` defines individual options, and `<optgroup>` groups options.

### What is `<fieldset>` and how is it used with `<legend>`?
The `<fieldset>` tag is used to group related form elements, while `<legend>` provides a title for the group.

### What is `<datalist>` used for?
The `<datalist>` tag provides a list of predefined options for an `<input>` element.

### What is the `<output>` element used for?
The `<output>` element represents the result of a calculation or user action.

---

## 📐 Tables

### What tags are used to build tables (`<table>`, `<thead>`, `<tbody>`, `<tfoot>`, `<tr>`, `<th>`, `<td>`)?
- `<table>` defines the table.
- `<thead>` represents the table header.
- `<tbody>` represents the table body.
- `<tfoot>` represents the table footer.
- `<tr>` defines a row in the table.
- `<th>` defines a table header cell.
- `<td>` defines a table data cell.

### What are attributes like `colspan`, `rowspan`, `scope` used for?
- `colspan`: Defines how many columns a cell should span.
- `rowspan`: Defines how many rows a cell should span.
- `scope`: Specifies whether a header cell is for a row, column, or group.

---

## 🏗️ Layout & Sections

### What is the purpose of the `<div>` tag?
The `<div>` tag is a generic container used to group elements and apply styles or scripts.

### What is the `<span>` tag used for?
The `<span>` tag is a generic inline container used to apply styles or scripts to text.

### What is the `<section>` tag and how is it different from `<article>`?
- `<section>` represents a section of related content.
- `<article>` represents independent, self-contained content.

### When should you use `<header>`, `<footer>`, and `<main>`?
- `<header>` represents the introductory content or navigation.
- `<footer>` represents the footer content.
- `<main>` represents the main content of the document.

### What is the `<aside>` tag used for?
The `<aside>` tag is used for content tangentially related to the main content, such as sidebars or advertisements.

### What’s the role of the `<address>` tag?
The `<address>` tag represents contact information for the document or author.

---

## 🧮 Scripting & Programmatic Content

### What is the `<script>` tag used for?
The `<script>` tag is used to include JavaScript in the document.

### What is `<noscript>` and when is it useful?
The `<noscript>` tag provides alternative content for users whose browsers do not support JavaScript.

### How is the `<template>` tag used?
The `<template>` tag defines reusable content that is not rendered until activated by JavaScript.

---

## 📊 Graphics

### What is the `<canvas>` element and how does it work?
The `<canvas>` element is used to draw graphics via JavaScript, such as 2D shapes or animations.

### What is `<svg>` used for in HTML?
The `<svg>` tag is used to define vector graphics, such as shapes and paths, in XML format.

### What is `<path>` in an SVG?
The `<path>` tag defines a path to be drawn in an SVG graphic, using a series of commands.

---

## ⚙️ Interactive Elements

### What is the `<details>` and `<summary>` combination used for?
The `<details>` tag represents a disclosure widget, while `<summary>` provides the title for the widget. The content is revealed when the user interacts with it.

### What is `<dialog>` and how does it differ from custom modal implementations?
The `<dialog>` tag represents a dialog box or modal. Unlike custom modals, it is built into the HTML standard and provides native functionality.

---

## 🧪 Obsolete/Deprecated (but sometimes asked)

### What were the roles of `<font>`, `<center>`, `<marquee>` and why are they deprecated?
- `<font>` was used for styling text, but it's deprecated in favor of CSS.
- `<center>` was used to center content, replaced by CSS.
- `<marquee>` was used for scrolling text, now deprecated for better alternatives like CSS animations.
