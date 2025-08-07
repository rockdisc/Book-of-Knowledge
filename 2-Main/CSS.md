#Tech/Coding 

Used in conjunction with [[HTML]] and other languages like [[React]] and [[PHP]]. Cascading Style Sheets is used to make the UI and animations of the website. It can be used normally, but there are also different versions one can download like Tailwind to make it easier to use. 

```css 
.class {
	color:red;
}

#id {
	padding:100px;
}

button::hover {
	border:1px dotted black;
}

```



| Property                     | Description                                        | Common Values                                       | Example                            |
| ---------------------------- | -------------------------------------------------- | --------------------------------------------------- | ---------------------------------- |
| **color**                    | Sets the text color of an element.                 | `red`, `#ff0000`, `rgb(255, 0, 0)`                  | `color: blue;`                     |
| **font-size**                | Sets the size of the font.                         | `12px`, `1.2em`, `120%`                             | `font-size: 16px;`                 |
| **font-family**              | Specifies the font for an element.                 | `Arial, sans-serif`, `"Times New Roman", serif`     | `font-family: Arial;`              |
| **background-color**         | Sets the background color of an element.           | `blue`, `#0000ff`, `rgb(0, 0, 255)`                 | `background-color: lightgray;`     |
| **width**                    | Sets the width of an element.                      | `100px`, `50%`, `auto`                              | `width: 300px;`                    |
| **height**                   | Sets the height of an element.                     | `100px`, `50%`, `auto`                              | `height: 200px;`                   |
| **margin**                   | Sets the space outside an element's border.        | `10px`, `auto`, `1em`                               | `margin: 10px;`                    |
| **padding**                  | Sets the space inside an element's border.         | `10px`, `1em`, `5%`                                 | `padding: 20px;`                   |
| **border**                   | Sets the border of an element.                     | `1px solid black`                                   | `border: 2px solid red;`           |
| **display**                  | Sets how an element is displayed.                  | `block`, `inline`, `flex`, `grid`, `none`           | `display: flex;`                   |
| **text-align**               | Aligns the text within an element.                 | `left`, `right`, `center`, `justify`                | `text-align: center;`              |
| **flex-direction**           | Defines the direction of flexible items.           | `row`, `column`, `row-reverse`, `column-reverse`    | `flex-direction: column;`          |
| **justify-content**          | Aligns flexible items along the main axis.         | `flex-start`, `flex-end`, `center`, `space-between` | `justify-content: center;`         |
| **align-items**              | Aligns flexible items along the cross axis.        | `flex-start`, `flex-end`, `center`, `stretch`       | `align-items: center;`             |
| **position**                 | Specifies the positioning method of an element.    | `static`, `relative`, `absolute`, `fixed`, `sticky` | `position: relative;`              |
| **top, right, bottom, left** | Used with `position` to set an element's position. | `10px`, `0`, `50%`                                  | `top: 10px;`                       |
| **z-index**                  | Specifies the stack order of an element.           | An integer (e.g., `1`, `100`)                       | `z-index: 99;`                     |
| **opacity**                  | Sets the transparency of an element.               | A number from `0.0` to `1.0`                        | `opacity: 0.5;`                    |
| **box-shadow**               | Attaches one or more shadows to an element.        | `h-offset v-offset blur spread color`               | `box-shadow: 2px 2px 5px #888888;` |
| **transition**               | Defines the transition effect between two states.  | `property duration timing-function delay`           | `transition: width 2s;`            |
