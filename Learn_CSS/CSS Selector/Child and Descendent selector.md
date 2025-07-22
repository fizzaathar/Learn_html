Child vs. Descendant Selectors in CSS
Both are combinators used to style elements based on their relationship in the HTML structure — but they work differently.

1 Descendant Selector (Space)
Selects all matching elements inside another, no matter how deep (grandchild, great-grandchild, etc.)

Uses a space between selectors.

 Syntax:

parent descendant {
  /* styles */
}
 Example:

<div>
  <p>This is a direct child</p>
  <section>
    <p>This is a nested descendant</p>
  </section>
</div>
div p {
  color: blue;
}
 This will style both <p> tags — because they are descendants of <div>, even if deeply nested.

2 Child Selector (>)
Selects only the immediate children (directly inside the parent).

Uses a greater-than sign > between selectors.

 Syntax:

parent > child {
  /* styles */
}
 Example:

<div>
  <p>This is a direct child</p>
  <section>
    <p>This is a nested child</p>
  </section>
</div>

div > p {
  color: red;
}
 This will style only the first <p>, not the nested one — because it is the direct child of <div>.

Child vs. Descendant Selectors in CSS
Both are combinators used to style elements based on their relationship in the HTML structure — but they work differently.

