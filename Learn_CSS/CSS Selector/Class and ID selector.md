 Class and ID Selectors in CSS
These selectors allow you to target specific HTML elements for styling — especially useful when you want to reuse or uniquely style elements.

1 Class Selector (.)
Targets one or multiple elements that share the same class name.

Use a dot . before the class name in CSS.

 Syntax:
In HTML:

<p class="note">This is a note.</p>
<p class="note">Another note.</p>
In CSS

.note {
  color: green;
  font-style: italic;
}
 Notes:
Can be reused on many elements.

You can use multiple classes on one element:


<p class="note big-text">...</p>
2 ID Selector (#)
Targets only one unique element with a specific ID.

Use a hash # before the ID name in CSS.

Syntax:
In HTML:

<h1 id="main-heading">Welcome</h1>
In CSS:

#main-heading {
  color: blue;
  text-align: center;
}