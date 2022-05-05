---
theme: ./theme
title: Web introduction
download: true
defaults:
  layout: 'intro'
colorSchema: 'auto'
themeConfig:
  primary: '#4f46e5'
  secondary: '#5b21b6'
  glow: '31, 27, 90'
layout: cover
---

# Introduction to Web Development
<i>for Absolute Beginners</i>

###### ver 0.3.8
##### [slides link](https://metaory.github.io/web-intro-talk/)

---
layout: cover
---

<img width="128" style="position: absolute; top: 20px; right: 20px;" src="/logo.png">

###### my name is
# Yan

# [github.com/metaory](https://github.com/metaory/)

### JS, Lua, Shell, Vim, Linux lover
## Developer Advocate

###### Solution Architect at HelloGold

<!--
test
-->

---

# Tooling
- A **text editor**, to write code in. This could be a text editor (e.g. [Visual Studio Code](https://code.visualstudio.com/), [Notepad++](https://notepad-plus-plus.org/), [Sublime Text](https://www.sublimetext.com/), [Atom](https://atom.io/), [GNU Emacs](https://www.gnu.org/software/emacs/), or [VIM](https://www.vim.org/)), or a hybrid editor (e.g. [WebStorm](https://www.jetbrains.com/webstorm/)). Office document editors are not suitable for this use, as they rely on hidden elements that interfere with the rendering engines used by web browsers.

- **Web browsers**, to test code in. Currently, the most-used browsers are [Firefox](https://www.mozilla.org/en-US/firefox/new/), [Chrome](https://www.google.com/chrome/browser/), [Opera](https://www.opera.com/), [Safari](https://www.apple.com/safari/), [Internet Explorer](https://support.microsoft.com/en-us/windows/internet-explorer-downloads-d49e1f0d-571c-9a7b-d97e-be248806ca70) and [Microsoft Edge](https://www.microsoft.com/edge). You should also test how your site performs on mobile devices and on any old browsers your target audience may still be using (such as IE 8–10).

<!--
Atom
-->

---
layout: image
titleHeader: Web Anatomy
image: /html-css-js-icons.png
overlayClass: bg-[rgba(0,0,0,0.0)]
---

---
layout: image
titleHeader: Web Anatomy
image: /html-css-js.png
overlayClass: bg-[rgba(0,0,0,0.0)]
---

---

# Structure (HTML)
### HTML to define the **content** of web pages

<v-click>

# Style (CSS)
### CSS to specify the **layout** and **style** web pages

</v-click>

<v-click>

# Functionality (JavaScript)
### JavaScript to program the **behavior** of web pages

</v-click>

---
layout: section
---

# HTML

---

# HTML
### HTML is the standard markup language for creating Web pages.

<v-click>

- HTML stands for Hyper Text Markup Language
- HTML is the standard markup language for creating Web pages
- HTML describes the structure of a Web page
- HTML consists of a series of elements
- HTML elements tell the browser how to display the content

</v-click>

---
layout: image
titleHeader: HTML Element Structure
image: /element-structure.webp
overlayClass: bg-[rgba(255,255,255,0.1)]
---

---

# HTML element parts

- **The opening tag**: This consists of the name of the element, wrapped in opening and closing angle brackets. This states where the element begins or starts to take effect.
- **The closing tag**: This is the same as the opening tag, except that it includes a forward slash before the element name. This states where the element ends.
- **The content**: This is the content of the element.
- **The element**: The opening tag, the closing tag, and the content together comprise the element.


---

# A Simple HTML Document

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Page Title</title>
  </head>
  <body>
    <h1>My First Heading</h1>
    <p>My first paragraph.</p>
  </body>
</html>
```

---

# Example Explained

- The `<!DOCTYPE html>` declaration defines that this document is an HTML5 document
- The `<html>` element is the root element of an HTML page
- The `<head>` element contains meta information about the HTML page
- The `<title>` element specifies a title for the HTML page
- The `<body>` element defines the document's body, and is a container for all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.
- The `<h1>` element defines a large heading
- The `<p>` element defines a paragraph

---

# HTML Semantic Elements

<v-click>

## Semantic elements = elements with a meaning.

</v-click>

<v-click>

### A **semantic** element clearly describes its meaning to both the browser and the developer.

### Examples of non-semantic elements: `<div>` and `<span>` - **Tells nothing about its content.**

### Examples of semantic elements: `<form>`, `<table>`, and `<article>` - **Clearly defines its content.**

</v-click>

---

# HTML Block-level Elements

## A block-level element always starts on a new line, and the browsers automatically add some space (a margin) before and after the element.

### Two commonly used block elements are: `<p>` and `<div>`.

---

# HTML Headings

## `<h1>` Heading 1 `</h1>`
### `<h2>` Heading 2 `</h2>`
#### `<h3>` Heading 3 `</h3>`
##### `<h4>` Heading 4 `</h4>`

---

# HTML Paragraphs

# `<p>` and `<pre>`

## `<p>`
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.</p>

## `<pre>`
<pre>
Lorem ipsum dolor sit amet
consectetur adipiscing elit
</pre>

---

# HTML Horizontal Rules

## The `<hr>` tag defines a thematic break in an HTML page, and is most often displayed as a horizontal rule.

### The `<hr>` element is used to separate content (or define a change) in an HTML page:

---

# HTML Line Breaks

## The HTML `<br>` element defines a line break.

### Use `<br>` if you want a line break (a new line) without starting a new paragraph:

---

# HTML Text Formatting

### <p><b>This text is bold</b></p>
### <p><i>This text is italic</i></p>
### <p>This is<sub> subscript</sub> and <sup>superscript</sup></p>

---
layout: center
titleHeader: HTML Text Formatting
---

- `<b>`      - Bold text
- `<strong>` - Important text
- `<i>`      - Italic text
- `<em>`     - Emphasized text
- `<mark>`   - Marked text
- `<small>`  - Smaller text
- `<del>`    - Deleted text
- `<ins>`    - Inserted text
- `<sub>`    - Subscript text
- `<sup>`    - Superscript text
- `...`

---

# Nested HTML Elements

## HTML elements can be nested.

### All HTML documents consist of nested HTML elements.

#### The following example contains four HTML elements (`<html>`, `<body>`, `<h1>` and `<p>`):

```html
<!DOCTYPE html>
<html>
  <body>
    <h1>My First Heading</h1>
    <p>My first paragraph.</p>
  </body>
</html>
```

---

# Case Sensitivity

## HTML is Not Case Sensitive

### HTML tags are not case sensitive: `<P>` means the same as `<p>`.

---

# HTML Attributes

## HTML attributes provide additional information about HTML elements.

- All HTML elements can have attributes
- Attributes provide additional information about elements
- Attributes are **always** specified in the **start tag**
- Attributes usually come in **name/value** pairs like: `name="value"`

---

# HTML Image Tag

## The `<img>` tag is used to embed an image in an HTML page.


### The src `attribute` specifies the path to the image to be displayed

```html
<img src="img_girl.jpg">
```

---
layout: image
titleHeader: HTML Image Attributes
image: /void_element_breakdown.png
overlayClass: bg-[rgba(0,0,0,0.0)]
---

---

# HTML Links

## Links allow users to click their way from page to page.

---

# HTML Link Tag

## The `<a>` tag defines a hyperlink.

###  The href attribute specifies the URL of the page the link goes to

```html
<a href="https://www.w3schools.com">Visit W3Schools</a>
```

---
layout: image
image: /html-link-tag.png
titleHeader: HTML Link Attributes
overlayClass: bg-[rgba(0,0,0,0.0)]
---

---

# HTML Class Attribute
## The HTML `class` attribute is used to specify a class for an HTML element.

<v-click>

### Multiple HTML elements can share the same class.

</v-click>

---

# HTML id Attribute

## The HTML `id` attribute is used to specify a unique id for an HTML element.

<v-click>

### You **cannot** have more than one element with the same **id** in an HTML document.

</v-click>

---
layout: section
---

# CSS

---

# CSS

## CSS stands for Cascading Style Sheets.

<v-click>

### CSS can control the layout of multiple web pages all at once.

<hr>

</v-click>


<v-click>

#### With CSS, you can control the color, font, the size of text, the spacing between elements,
#### how elements are positioned and laid out, what background images or background colors are to be used, different displays for different devices and screen sizes, and much more!

</v-click>

---
layout: image
titleHeader: CSS Syntax
image: /css-syntax.gif
overlayClass: bg-[rgba(0,0,0,0.0)]
---

---
layout: image
titleHeader: CSS Syntax
image: /css-declaration-small.png
overlayClass: bg-[rgba(0,0,0,0.0)]
---

---

# CSS Syntax Example
```css
body {
  background-color: powderblue;
}
h1 {
  color: blue;
}
p {
  color: red;
}
```

---

# CSS Syntax Explained

#### The selector points to the HTML element you want to style.

#### The declaration block contains one or more declarations separated by semicolons.

#### Each declaration includes a CSS property name and a value, separated by a colon.

#### Multiple CSS declarations are separated with semicolons, and declaration blocks are surrounded by curly braces.

---

# Using CSS
<v-click>

## CSS Inline
### by using the `style` attribute inside HTML elements

</v-click>

<v-click>

## CSS Internal
### by using a `<style>` element in the `<head>` section

</v-click>

<v-click>

## CSS External
### External - by using a `<link>` element to link to an external CSS file

</v-click>

---

# Inline CSS
## An inline CSS is used to apply a unique style to a single HTML element.

<v-click>

## An inline CSS uses the `style` attribute of an HTML element.

</v-click>

<v-click>

### The following example sets the text color of the `<h1>` element to blue
```html
<h1 style="color:blue;">A Blue Heading</h1>
```

</v-click>

---

# Internal CSS
## An internal CSS is used to define a style for a single HTML page.

<v-click>

#### An internal CSS is defined in the `<head>` section of an HTML page, within a `<style>` element.

</v-click>

<v-click>

#### The following example sets the text color of ALL the `<h1>` elements (on that page) to blue, and the text color of ALL the `<p>` elements to red.
```css
body {background-color: powderblue;}
h1   {color: blue;}
p    {color: red;}
```

</v-click>

---

# External CSS

### An external style sheet is used to define the style for many HTML pages.

#### To use an external style sheet, add a link to it in the `<head>` section of each HTML page:

```html
<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" href="styles.css">
  </head>
  <body>
    <h1>This is a heading</h1>
    <p>This is a paragraph.</p>
  </body>
</html>
```

---

# CSS Colors

#### Colors are specified using predefined `color names`, or `RGB`, `HEX`, `HSL` values.

#### These values represent the same color in different formats:
```css
h1 {color: #ff0000;}
h2 {color: rgb(255, 0, 0);}
h3 {color: hsl(0, 100%, 50%);}
```

---

# Background Color
```html
<p style="background-color:Tomato;">Lorem ipsum...</p>
```

# Text Color
```html
<h1 style="color:Tomato;">Hello World</h1>
```

# Border Color
```html
<h1 style="border:2px solid Tomato;">Hello World</h1>
```

---

# CSS Units
## CSS has several different units for expressing a length.

##### Many CSS properties take **"length"** values, such as `width`, `margin`, `padding`, `font-size`, etc.

##### Length is a number followed by a length unit, such as `10px`, `2em`, etc.

```css
h1 {
  font-size: 60px;
}

p {
  font-size: 25px;
  line-height: 50px;
}
```

---
titleHeader: CSS Units
layout: two-cols
---
# Absolute 
- `cm` centimeters
- `mm` millimeters
- `in` inches (1in = 96px = 2.54cm)
- `px` pixels (1px = 1/96th of 1in)
- `pt` points (1pt = 1/72 of 1in)
- `...`

::right::
# Relative
- `em` Relative to the font-size of the element
- `rem` Relative to font-size of the root element
- `vw` Relative to 1% of the width of the viewport
- `vh` Relative to 1% of the height of the viewport
- `%` Relative to the parent element
- `...`

---

# CSS Padding
## An element's padding is the space between its content and its border.
### Padding is used to create space around an element's content, inside of any defined borders.

#### The padding property is a **shorthand** property for:
- `padding-top`
- `padding-right`
- `padding-bottom`
- `padding-left`

---
layout: image
titleHeader: CSS Padding
image: /padding.webp
overlayClass: bg-[rgba(0,0,0,0.0)]
---

---

# CSS Margin
## Margins are used to create space around elements, outside of any defined borders.

#### The margin property is a **shorthand** property for:
- `margin-top`
- `margin-right`
- `margin-bottom`
- `margin-left`

---
layout: image
titleHeader: CSS Margin
image: /margin.webp
overlayClass: bg-[rgba(0,0,0,0.0)]
---

---

# CSS Alignment

- ## The `text-align` property is used to set the horizontal alignment of a text.
### A text can be `left` or `right` `aligned`, `centered`, or `justified`.


- ## The `vertical-align` property sets the vertical alignment of an element.

---
layout: center
titleHeader: CSS Properties
---

- `color`             - Sets the color of text
- `background-color`  - Specifies the background color of an element
- `background-image`  - Specifies one or more background images for an element
- `border`            - A shorthand property for border-width, border-style and border-color
- `box-shadow`        - Attaches one or more shadows to an element
- `display`           - Specifies how a certain HTML element should be displayed
- `font-weight`       - Specifies the weight of a font
- `margin`            - Sets all the margin properties in one declaration
- `padding`           - A shorthand property for all the padding-* properties
- `opacity`           - Sets the opacity level for an element
- `text-align`        - Specifies the horizontal alignment of text
- `...`

---

# CSS Selectors
## A CSS selector selects the HTML element(s) you want to style.

<v-click>

### CSS selectors are used to **"find"** (or select) the HTML elements you want to style.

</v-click>

<v-click>

#### CSS selectors five categories:

- Simple selectors (select elements based on name, id, class)
- Combinator selectors (select elements based on a specific relationship between them)
- Pseudo-class selectors (select elements based on a certain state)
- Pseudo-elements selectors (select and style a part of an element)
- Attribute selectors (select elements based on an attribute or attribute value)

</v-click>

---

# CSS Simple Selectors

| Selector name    | What does it select                                  | Example&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;                                    |
| ---              | ---                                                  | ---                                        |
| Element selector | All HTML elements of the specified type.             | `p` selects `<p>`                            |
| ID selector      | The element on the page with the specified ID.       | `#my-id` selects `<p id="my-id">`          |
| Class selector   | The element(s) on the page with the specified class. | `.my-class` selects `<p class="my-class">` |

---


# The CSS element Selector
## The element selector selects HTML elements based on the element name.

### Here, all `<p>` elements on the page will be **center-aligned**, with a **red text color**:

```css
p {
  text-align: center;
  color: red;
}
```

---

# The CSS id Selector
## The id selector uses the id attribute of an HTML element to select a specific element.
### The **id** of an element is **unique** within a page, so the **id selector** is used to select **one** unique element!

#### The CSS rule below will be applied to the HTML element with `id="para1"`:
```css
#para1 {
  text-align: center;
  color: red;
}
```

---

# Using The class Attribute
## The `class` attribute is often used to point to a class name in a style sheet.

```html
<!DOCTYPE html>
<html>
  <head>
  <style>
  .city {
    background-color: tomato;
    color: white;
    border: 2px solid black;
    margin: 20px;
    padding: 20px;
  }
  </style>
  </head>
  <body>
    <div class="city">
      <h2>London</h2>
      <p>London is the capital of England.</p>
    </div>
    <div class="city">
      <h2>Tokyo</h2>
      <p>Tokyo is the capital of Japan.</p>
    </div>
  </body>
</html>
```

---

# Selecting multiple elements

### You can also select multiple elements and apply a single ruleset to all of them. Separate multiple selectors by commas.

```css
p, li, h1 {
  color: red;
}
```

---

# Advance CSS Selectors

| Selector&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;          | Example&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;         | Example Description |
| ---               | ---             | ---                                                                               |
| `.class`          | `.intro`        | Selects all elements with `class="intro"`                                         |
| `.class1.class2`  | `.name1.name2`  | Selects all elements with both `name1` and `name2` set within its class attribute |
| `.class1 .class2` | `.name1 .name2` | Selects all elements with `name2` that is a descendant of an element with `name1` |
| `#id`             | `#firstname`    | Selects the element with `id="firstname"`                                         |
| `*`               | `*`             | Selects all elements                                                              |

---

# Advance CSS Selectors

| Selector          | Example   | Example Description                                                        |
| ---               | ---       | ---                                                                        |
| `element`         | `p`       | Selects all `<p>` elements                                                 |
| `element.class`   | `p.intro` | Selects all `<p>` elements with `class="intro"`                            |
| `element,element` | `div, p`  | Selects all `<div>` elements and all `<p>` elements                        |
| `element element` | `div p`   | Selects all `<p>` elements inside `<div>` elements                         |
| `element>element` | `div > p` | Selects all `<p>` elements where the parent is a `<div>` element           |
| `element+element` | `div + p` | Selects the first `<p>` element that is immediately after `<div>` elements |

---
layout: section
---
# JavaScript

---

# JavaScript

### JavaScript is the world's most popular programming language.

### JavaScript is the programming language of the Web.

### JavaScript is easy to learn.

---
titleHeader: JavaScript
layout: quote
---

# Variables
**Variables** are containers for storing data (storing data values).

---

# Variable Types

<v-click>

## - global
```javascript
myVariable = 'Steve';
```

</v-click>

<v-click>

## - let/var
```javascript
let myVariable = 'Steve';
myVariable = 'new name';
var name = 'John';
```

</v-click>

<v-click>

## - const
```javascript
const myVariable = 'Steve';
```

</v-click>

---
layout: two-cols
---

# Data Types

## String
```javascript
let myVariable = 'Bob';
```
## Number
```javascript
let myVariable = 10;
```
## Boolean
```javascript
let myVariable = true;
```

::right::
# &nbsp;
## Object
```javascript
let myVariable = { name: 'John' }
```
## Array
```javascript
let myVariable = [1,'Bob','Steve',10];
```

---

# Variable Examples

```javascript {none|1-3|4|5|all}
var firstName = 'Pou' // string
var lastName = 'Yan' // string
var fullName = firstName + lastName // string
var age = 34 // number
var single = true // boolean

console.log(firstName)
console.log('fullname:', fullName)
```
<v-click>

#### One of many JavaScript HTML methods is `getElementById()`.

</v-click>

<v-click>

```javascript {none|all}
document.getElementById("demo").innerHTML = fullName
```
</v-click>

---

# References
- [W3 HTML Tutorial](https://www.w3schools.com/html/default.asp)
- [W3 CSS Tutorial](https://www.w3schools.com/css/default.asp)
- [W3 CSS Selectors Reference](https://www.w3schools.com/cssref/css_selectors.asp)
- [W3 JavaScript Tutorial](https://www.w3schools.com/js/default.asp)
- [W3 Howto](https://www.w3schools.com/howto/default.asp)
- [MDN Getting started with the Web Tutorial](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web)
- [MDN Front-end Web Developer Tutorial](https://developer.mozilla.org/en-US/docs/Learn/Front-end_web_developer)
- [MDN HTML Elements reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
- [MDN HTML reference](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [MDN CSS reference](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [MDN JavaScript reference](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
