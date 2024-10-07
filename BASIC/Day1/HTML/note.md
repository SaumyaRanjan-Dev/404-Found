## HTML

HTML (HyperText Markup Language) is a standard markup language used to create web pages. It forms the backbone of any website, defining the structure and layout of a web page.

### HTML Structure

HTML documents are divided into two main sections:

1. **`<head>`**: Contains metadata about the webpage, such as the title, character set, and links to stylesheets or scripts.
2. **`<body>`**: Contains the content that will be displayed on the webpage, such as headings, paragraphs, images, and more.

### Sample HTML Code

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My First Web Page</title>
  </head>
  <body>
    <h1>Welcome to my first web page</h1>
    <p>This is my first web page.</p>
  </body>
</html>
```

# HTML Elements and Their Default Display Values

Every HTML element has a default display value, depending on what type of element it is. The two most common display values are `block` and `inline`.

## Block-level Elements

A block-level element always starts on a new line, and the browser automatically adds some space (a margin) before and after the element. It also takes up the full width available (stretches out to the left and right as far as it can).

Two commonly used block elements are `<p>` and `<div>`.

- The `<p>` element defines a paragraph in an HTML document.
- The `<div>` element defines a division or section in an HTML document.

Both `<p>` and `<div>` are block-level elements.

### Example:

```html
<p>Hello World</p>
<div>Hello World</div>
```

-List of Block-level Elements in HTML:

```html
<address>, <article>, <aside>, <blockquote>, <canvas>, <dd>, <div>, <dl>, <dt>, <fieldset>, <figcaption>, <figure>, <footer>, <form>, <h1> to <h6>, <header>, <hr>, <li>, <main>, <nav>, <noscript>, <ol>, <p>, <pre>, <section>, <table>, <tfoot>, <ul>, <video>
```

## Inline Elements

An inline element does not start on a new line and only takes up as much width as necessary.

Example of an inline element inside a paragraph:

```html
<span>Hello World</span>
```

List of Inline Elements in HTML:

```html
<a>, <abbr>, <acronym>, <b>, <bdo>, <big>, <br>, <button>, <cite>, <code>, <dfn>, <em>, <i>, <img>, <input>, <kbd>, <label>, <map>, <object>, <output>, <q>, <samp>, <script>, <select>, <small>, <span>, <strong>, <sub>, <sup>, <textarea>, <time>, <tt>, <var>
```
