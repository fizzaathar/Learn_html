 Form Validation in HTML
Form validation ensures that the data entered by the user is correct, complete, and safe before the form is submitted.

Common Validation Attributes:
Attribute	Purpose
required	Field must be filled before submission

Example:

<form>
  <label>Email:</label>
  <input type="email" name="userEmail" required><br>

  <label>Password (min 6 characters):</label>
  <input type="password" name="pass" minlength="6" required><br>

  <label>Age (between 18 and 60):</label>
  <input type="number" name="age" min="18" max="60" required><br>

  <input type="submit" value="Submit">
</form>
 The browser will automatically block submission if rules are not follo