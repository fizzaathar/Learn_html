<label> Tag
 Basic Syntax:

<label for="id_of_input">Label Text</label>
<input type="text" id="id_of_input" name="...">
 How it Works:
The for attribute of <label> must match the id of the input.

This connects the label with the input box.

Clicking the label will focus/select the input field.

 Example:

<form>
  <label for="username">Username:</label>
  <input type="text" id="username" name="username">
  
  <br><br>
  
  <label for="email">Email:</label>
  <input type="email" id="email" name="email">
</form>
