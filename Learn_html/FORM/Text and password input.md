Text Input
Used to enter plain visible text.

 Syntax:

<input type="text" name="username">
 Example:

<label for="username">Username:</label>
<input type="text" id="username" name="username">
2. Password Input
Used to enter secret text (like a password). Characters are hidden with dots or asterisks.

 Syntax:

<input type="password" name="userpass">
Example:

<label for="password">Password:</label>
<input type="password" id="password" name="userpass">
 Combined Example: Login Form

<form action="login.php" method="post">
  <label for="username">Username:</label>
  <input type="text" id="username" name="username" required><br><br>

  <label for="password">Password:</label>
  <input type="password" id="password" name="userpass" required><br><br>

  <input type="submit" value="Login">
</form>