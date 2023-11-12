# CSS Nesting Practice

<p align="center">
  <img alt="png" src="Nesting.png"/>
</p>


## Description
This project demonstrates the use of CSS nesting to create a structured and maintainable stylesheet. Nesting allows us to write CSS in a way that's similar to the HTML structure of the page.

## Installation
To use this CSS in your project, add the following lines to the head of your HTML:

```html
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel='stylesheet' href='https://codepen.io/argyleink/pen/YzOzvbp/fb87d59847c9de21911b9db0d799feb7.css'>
<link rel="stylesheet" href="./style.css">
```

## Usage
The CSS provided in style.css uses the @layer directive to create a layer called nesting.practice. Inside this layer, the .demo class has two nested classes, .triangle and .square, which have certain styles applied to them.

## Code Example
```css
@layer nesting.practice {
  .demo {
    .triangle, 
    .square {
      opacity: .26;
      filter: blur(26px);
    }
  }
}
```

 This example shows how to apply opacity and blur filter to elements with the classes .triangle or .square that are nested within an element with the .demo class.
