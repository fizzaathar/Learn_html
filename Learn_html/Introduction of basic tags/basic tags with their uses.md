1. Text and Headings (<h1> to <h6>)
HTML headings define titles.


<h1>Main Heading</h1>    <!-- Largest -->
<h2>Sub Heading</h2>
...
<h6>Smallest Heading</h6>
 2. Paragraph (<p>)
Used for normal text blocks.


<p>This is a paragraph of text.</p>
 3. Bold Text
Tag	Description	Example
<b>	Just bold (visual only)	<b>Hello</b> → Hello
<strong>	Bold + semantic meaning (important)	<strong>Warning!</strong> → Warning!

 4. Italic Text
Tag	Description	Example
<i>	Italic (visual only)	<i>Word</i> → Word
<em>	Emphasis (semantic)	<em>Important</em> → Important

 5. Superscript and Subscript
Tag	Use	Example	Output
<sup>	Above line	x<sup>2</sup>	x²
<sub>	Below line	H<sub>2</sub>O	H₂O

 6. White Spaces
HTML ignores extra spaces.
To add a space, use &nbsp; (non-breaking space):


Hello&nbsp;&nbsp;&nbsp;World
 7. Line Break (<br>)
Breaks to the next line inside a paragraph.


Line 1<br>Line 2
 8. Horizontal Rule (<hr>)
Creates a horizontal line — a visual divider.

<p>Section 1</p>
<hr>
<p>Section 2</p>
 9. Semantic Markup
Semantic tags tell meaning, not just style.

Tag	Meaning
<strong>	Important text
<em>	Emphasized text
<mark>	Highlighted
<blockquote>	Large quote
<cite>	Reference source

 10. Quotation Tags
Tag	Use
<q>	Short quote inside sentence
<blockquote>	Long quotation block


<q>Honesty is the best policy.</q>
<blockquote>Full paragraph quote here...</blockquote>
 11. Abbreviations and Acronyms

<abbr title="HyperText Markup Language">HTML</abbr>
 Hovering shows full form.

 <acronym> is obsolete. Use <abbr> instead.

 12. Author Detail (<address>)
Displays contact or author info.


<address>
  Written by Fizza.<br>
  Email: fizza@example.com
</address>


 13. Citation (<cite>)
Used to cite titles of books, articles, etc.


<cite>Romeo and Juliet</cite>
Usually shown in italic.

 14. Definition (<dfn>)
Used to mark a definition term.


<dfn>HTML</dfn> is a markup language.
 Screen readers may treat it as a defined term.

 15. Changes to Content
Tag	Use	Example
<ins>	Inserted text	<ins>new</ins>
<del>	Deleted text	<del>old</del>

 16. Strikethrough (<s> / <del>)
<s> = Struck out for visual only

<del> = Struck out with meaning (content removed)


<p>Price: <s>$100</s> $80</p>
 Output: $100 $80

