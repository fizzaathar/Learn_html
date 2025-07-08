Writing Links in HTML
In HTML, links are created using the <a> tag, which stands for "anchor". Links allow users to navigate from one page to another, or to an external website.

 Basic Syntax:

<a href="URL">Link Text</a>
href stands for Hypertext REFerence

URL is the web address or file path

The link text is what users click on

 Examples:
 1. Link to Another Website

Edit
<a href="https://www.google.com">Go to Google</a>
 Opens Google when clicked.

 2. Link to Another Page (Same Site)

<a href="about.html">About Us</a>
 Opens the about.html page in your website folder.

 3. Link Opens in New Tab

<a href="https://www.facebook.com" target="_blank">Facebook</a>
target="_blank" opens the link in a new tab.

 4. Link to a Section in Same Page
Use an ID to jump to a part of the page.


<a href="#contact">Go to Contact</a>


<h2 id="contact">Contact Us</h2>
 5. Email Link

<a href="mailto:info@example.com">Email Us</a>
 Opens the user's email app to send a message.