# Bootstrap-Project-2-Ajax

**1 The aim of the laboratory**

The laboratory exercises aim to familiarize the student with using the Ajax in order to
load/refresh part of the web page without full request to the server.
Please copy and modify the subpage prepared in Exercise 3 from the last laboratory.

**1.1 Exercise 1**

Prepare students.json file containing exemplary data for the table from the last laboratory.
The file should contains the data for the 5 students.

**1.2 Exercise 2**

Add a new button “Load JSON”. After clicking the button you should display the Bootstrap
modal window containing the content of the JSON file loaded using Ajax (JavaScript or
JQuery approaches). The order of the work can look that:
a. Implementation click event for the button
b. Loading content of the JSON file into the div element (inside the Bootstrap modal
window, you do not need any parsing, load content)
c. Displaying the modal window on the web page.

**1.3 Exercise 3**

Add a new button “Load table data”. After clicking on the button you should display the
Bootstrap modal window with the data from the JSON file. The loaded data should be
formatted as the table prepared in the last laboratory.
Tip: you should create html elements of the bootstrap table using jQuery – for each student
data from the JSON file, you should prepare a one row of the bootstrap table
JQuery – creation html element: https://www.w3schools.com/jquery/jquery_dom_add.asp
For example: element.after(”<tr> <td> data from the JSON file </td> <td> .. <td> </tr>”);
