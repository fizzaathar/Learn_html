Universal and Type Selectors in CSS
These are two basic selectors used to apply styles to HTML elements:

1 Universal Selector (*)
Selects every element on the web page.

Useful for applying a default style to all elements.

Syntax:
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
 Example:
<style>
  * {
    font-family: Arial;
    background-color: #f9f9f9;
  }
</style>
This applies the same font and background to every element on the page.

2 Type Selector (Element Selector)
Selects all HTML elements of a specific type (e.g., p, h1, div, etc.)

 Syntax:

tagname {
  property: value;
}
 Example:

p {
  color: gray;
  font-size: 16px;
}

h1 {
  color: blue;
}
This applies styles to all <p> elements and all <h1> elements.

Universal and Type Selectors in CSS
These are two basic selectors used to apply styles to HTML elements:

