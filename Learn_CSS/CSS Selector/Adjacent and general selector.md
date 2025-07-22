 Adjacent vs General Sibling Selectors in CSS
These two selectors are used to target sibling elements — elements that share the same parent — but they behave differently.

1 Adjacent Sibling Selector (+)
Selects the first sibling that comes immediately after a specified element.

Both elements must have the same parent.

 Syntax:

A + B {
  /* styles */
}
 Example:

<h2>Title</h2>
<p>This paragraph is styled.</p>
<p>This one is not.</p>

h2 + p {
  color: blue;
}
 Only the first <p> immediately after <h2> will be styled.

2 General Sibling Selector (~)
Selects all siblings that come after a specified element.

Again, they must share the same parent.

 Syntax:

A ~ B {
  /* styles */
}
Example:

<h2>Title</h2>
<p>This paragraph is styled.</p>
<p>This one is also styled.</p>

h2 ~ p {
  color: green;
}
 Both <p> elements after <h2> will be styled.

