Radio Button in HTML
Radio buttons are used when the **user must choose one option from a group (like gender, payment method, etc.). Only one radio button in a group can be selected at a time.

 Basic Syntax:

<input type="radio" name="groupname" value="option">
 Example: Gender Selection

<form>
  <label>
    <input type="radio" name="gender" value="male">
    Male
  </label><br>

  <label>
    <input type="radio" name="gender" value="female">
    Female
  </label><br>

  <label>
    <input type="radio" name="gender" value="other">
    Other
  </label>
</form>
