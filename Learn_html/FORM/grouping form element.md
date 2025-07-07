Grouping Form Elements in HTML
To make a form more organized and user-friendly, HTML provides tags for grouping related inputs. This is especially useful for styling and accessibility.

1. <fieldset> and <legend>
<fieldset> groups related form elements.

<legend> adds a label/title to that group.

 Example:
<form>
  <fieldset>
    <legend>Personal Info</legend>
    
    <label for="name">Name:</label>
    <input type="text" id="name" name="name"><br><br>
    
    <label for="email">Email:</label>
    <input type="email" id="email" name="email">
  </fieldset>
</form>
