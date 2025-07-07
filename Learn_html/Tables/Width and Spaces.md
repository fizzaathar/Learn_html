 Width and Spaces in HTML
In HTML, you can control the width of elements and manage spaces (white space, line breaks, etc.) using HTML tags and CSS.

 1. Width of Elements
You can control width using:

HTML attributes (limited use)


 HTML Width Attribute :

<table width="100%">
  <tr><td>This table is full width</td></tr>
</table>

2. Spaces in HTML
 A. White Space (Extra Spaces)
HTML ignores extra spaces, tabs, and line breaks by default.

<p>This     text     has    extra spaces.</p>
 Appears as: This text has extra spaces.

 Use &nbsp; to insert non-breaking space (space that stays visible)

<p>Item&nbsp;&nbsp;&nbsp;Price</p>
Each &nbsp; adds one fixed space.

 B. Line Breaks (<br>)
Use <br> to break a line (go to next line).

<p>Hello<br>World</p>
 Output:


Hello
World
