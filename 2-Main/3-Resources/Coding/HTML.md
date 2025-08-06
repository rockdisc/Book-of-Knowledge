#Tech/Coding 

Hyper text markup language is a way of creating elements in websites. Here is how to set it up:

```html 
<!DOCTYPE html>  
<html>  
<head>  
	<title>Page Title</title>  
	<link rel="stylesheet" href="style.css"> <!-- this allows for all the styling to be in the CSS file instead of in here -->
</head>  
<body>  
	<!-- this is a comment -->
	<h1>This is a Heading</h1>  
	<p>This is a paragraph.</p>
	<!-- All elements are enclosed <>, the thing inside tells what element it is in, it is closed by </> -->

	<script src="script.js"></script> <!-- you can write JS in this file but people find it easier to write it in another file -->
</body>  
</html>
```
Most IDEs will generate this for you just by typing !. 

Here is a list of commonly used elements:

| Element       | Purpose                                   | Example                                    |
|:------------- |:----------------------------------------- |:------------------------------------------ |
| `<html>`      | Root element of an HTML document          | `<html> ... </html>`                       |
| `<head>`      | Contains metadata and links               | `<head> ... </head>`                       |
| `<title>`     | Sets the page title                       | `<title>My Page</title>`                   |
| `<meta>`      | Defines metadata like charset or viewport | `<meta charset="UTF-8">`                   |
| `<link>`      | Links external resources like CSS         | `<link rel="stylesheet" href="style.css">` |
| `<script>`    | Embeds or links JavaScript                | `<script src="app.js"></script>`           |
| `<style>`     | Embeds CSS styles                         | `<style>body { color: red; }</style>`      |
| `<body>`      | Main content of the page                  | `<body> ... </body>`                       |
| `<h1>`–`<h6>` | Headings, h1 is the largest               | `<h1>Title</h1>`                           |
| `<p>`         | Paragraph                                 | `<p>Hello world</p>`                       |
| `<a>`         | Hyperlink                                 | `<a href="https://example.com">Link</a>`   |
| `<img>`       | Image                                     | `<img src="image.jpg" alt="desc">`         |
| `<ul>`        | Unordered list                            | `<ul><li>Item</li></ul>`                   |
| `<ol>`        | Ordered list                              | `<ol><li>First</li></ol>`                  |
| `<li>`        | List item                                 | `<li>List item</li>`                       |
| `<div>`       | Generic container                         | `<div class="box">Content</div>`           |
| `<span>`      | Inline container                          | `<span style="color:red">Red</span>`       |
| `<br>`        | Line break                                | `Hello<br>World`                           |
| `<hr>`        | Horizontal rule                           | `<hr>`                                     |
| `<strong>`    | Strong importance (bold)                  | `<strong>Important</strong>`               |
| `<em>`        | Emphasis (italic)                         | `<em>Note</em>`                            |
| `<input>`     | User input field                          | `<input type="text">`                      |
| `<button>`    | Clickable button                          | `<button>Click me</button>`                |
| `<form>`      | Form container                            | `<form action="/submit">...</form>`        |
| `<label>`     | Label for input                           | `<label for="name">Name:</label>`          |
| `<textarea>`  | Multi-line text input                     | `<textarea></textarea>`                    |
| `<table>`     | Table container                           | `<table>...</table>`                       |
| `<tr>`        | Table row                                 | `<tr>...</tr>`                             |
| `<td>`        | Table cell                                | `<td>Cell</td>`                            |
| `<th>`        | Table header cell                         | `<th>Header</th>`                          |
| `<nav>`       | Navigation links                          | `<nav>...</nav>`                           |
| `<header>`    | Page or section header                    | `<header>...</header>`                     |
| `<footer>`    | Page or section footer                    | `<footer>...</footer>`                     |
| `<section>`   | Thematic section of content               | `<section>...</section>`                   |
| `<article>`   | Independent content block                 | `<article>...</article>`                   |
| `<aside>`     | Side content like a sidebar               | `<aside>...</aside>`                       |
| `<main>`      | Main content area                         | `<main>...</main>`                         |
