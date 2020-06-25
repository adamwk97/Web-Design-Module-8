Link to website -> http://adamwk97.epizy.com
       
PHP output -> http://adamwk97.epizy.com/module8.php

1. What is the difference between $_Get vs. $_POST?

"$_Get" requests data from either a user or a repository where can then be stored in memory,while "$_Post" takes that data from memory and pushes it to update a resource. For example, $_Get could be used to ask for a user's email address and store it locally, while $_Post would be used to send and update that email address to a server.

2. 2. Create an HTML form page on your website that used Post or Get and connect to .php file post on your website and collects the data from the form. 

Code:
```
<form action="/xxx.php" method="post" name="myForm">
  <label for="email">Email address:</label>
  <input type="text" id="email" name="email"><br><br>
  <label for="lname">Last name:</label>
  <input type="text" id="lname" name="lname"><br><br>
  <label for="school">School:</label>
  <input type="text" id="school" name="school"><br><br>
  <input type="button" onclick="formSubmit()" value="Verify Student">
</form>
```
The code I created uses "get" to ask for a student's email, last name and institution name and then verifies the student's credentials and would then theoretically use "post"
to send the data and grant access to a server. 
saf
