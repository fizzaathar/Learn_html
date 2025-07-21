Long Tables in HTML
When you create a long table (many rows of data), HTML provides special elements to help organize and structure the table for better readability and styling.

 Long Table Structure
You can divide a long table into 3 main sections:

Tag	Purpose
<thead>	Header section (column titles)
<tbody>	Body section (main data rows)
<tfoot>	Footer section (totals, summaries, notes)

 Example of a Long Table

<table border="1">
  <thead>
    <tr>
      <th>Roll No</th>
      <th>Name</th>
      <th>Marks</th>
    </tr>
  </thead>

  <tbody>
    <tr>
      <td>101</td>
      <td>Ali</td>
      <td>85</td>
    </tr>
    <tr>
      <td>102</td>
      <td>Sara</td>
      <td>92</td>
    </tr>
    <tr>
      <td>103</td>
      <td>Usman</td>
      <td>78</td>
    </tr>
    <!-- More rows can go here -->
  </tbody>

  <tfoot>
    <tr>
      <td colspan="2">Total Students</td>
      <td>3</td>
    </tr>
  </tfoot>
</table>