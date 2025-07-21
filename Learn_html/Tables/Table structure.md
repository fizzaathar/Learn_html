 Table Structure in HTML
HTML tables are used to display data in rows and columns, just like in Excel or a spreadsheet.

 Basic Table Tags:
Tag	Description
<table>	Starts the table
<tr>	Table row (horizontal line)
<th>	Table header (bold + centered by default)
<td>	Table data cell
<caption>	(Optional) Title for the table

 Basic Table Example:

<table border="1">
  <caption>Student Marks</caption>

  <tr>
    <th>Name</th>
    <th>Subject</th>
    <th>Marks</th>
  </tr>

  <tr>
    <td>Ali</td>
    <td>Math</td>
    <td>85</td>
  </tr>

  <tr>
    <td>Sara</td>
    <td>Science</td>
    <td>92</td>
  </tr>
</table>
 Output:
Name	Subject	Marks
Ali	Math	85
Sara	Science	92

