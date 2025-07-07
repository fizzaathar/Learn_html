File Input Box in HTML
The file input box allows users to upload files (like images, PDFs, documents) from their computer.

 HTML Syntax:

<form action="upload.php" method="post" enctype="multipart/form-data">
  <label for="myfile">Upload a file:</label>
  <input type="file" id="myfile" name="myfile">
  <input type="submit" value="Upload">
</form>



