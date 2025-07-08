Unordered List (<ul>)
Used to display items without numbers — instead, items appear with bullets (●).

 Syntax:

<ul>
  <li>Tea</li>
  <li>Coffee</li>
  <li>Juice</li>
</ul>
 Output:
Tea

Coffee

Juice

 Bullet Styles:
You can change the bullet style using the type attribute:


<ul type="circle">     <!-- or disc, square -->
  <li>Item A</li>
</ul>
 2. Ordered List (<ol>)
Used to display items in a numbered sequence (1, 2, 3…).

 Syntax:
<ol>
  <li>HTML</li>
  <li>CSS</li>
  <li>JavaScript</li>
</ol>
 Output:
HTML

CSS

JavaScript

 Numbering Styles:
You can use the type attribute:

Type	Result
1	1, 2, 3
A	A, B, C
a	a, b, c
I	I, II
i	i, ii


<ol type="A">
  <li>First</li>
  <li>Second</li>
</ol>
 3. Definition List (<dl>)
Used to show terms and their meanings (like a glossary or FAQ).

 Syntax:

<dl>
  <dt>HTML</dt>
  <dd>HyperText Markup Language</dd>

  <dt>CSS</dt>
  <dd>Cascading Style Sheets</dd>
</dl>
 Output:
HTML
▪️ HyperText Markup Language

CSS
▪️ Cascading Style Sheets

 . Nested List (List inside another list)
You can put a list inside a list item — called a nested list.

 Example:

<ul>
  <li>Fruits
    <ul>
      <li>Apple</li>
      <li>Banana</li>
    </ul>
  </li>
  <li>Vegetables
    <ul>
      <li>Carrot</li>
      <li>Potato</li>
    </ul>
  </li>
</ul>
 Output:
Fruits

Apple

Banana

Vegetables

Carrot

Potato

 You can nest <ol> inside <ul> and vice versa too.
