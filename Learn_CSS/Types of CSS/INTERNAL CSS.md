What is Internal CSS?
Internal CSS is written inside the <style> tag in the <head> section of an HTML document. It is used to style a single HTML page.

 Syntax of Internal CSS

<!DOCTYPE html>
<html>
<head>
  <style>
    selector {
      property: value;
    }
  </style>
</head>
<body>
  <!-- Your HTML content here -->
</body>
</html>
 Example:

<!DOCTYPE html>
<html>
<head>
  <style>
    h1 {
      color: green;
      text-align: center;
    }
    p {
      font-size: 18px;
      color: gray;
    }
  </style>
</head>
<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph with internal CSS.</p>
</body>
</html>