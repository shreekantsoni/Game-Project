# Game-Project
This is Quiz-game project and Tic-Tac-Toe project


Using simple HTML, create a starter Tic Tac Toe grid with some data and basic styling.
HTML Concepts : html head, html body, table, row, column, header h1, div, span (label)
CSS Concepts : height, width, table / cell's border & color, font-size, text alignment (center, left justified etc)
BootStrap : bootstrap4 using with side bar.
End Result: Open the file Step 1/game1.html in Chrome browser


TECHNOLOGY
.HTML
.CSS
.BootStrap
.JavaScript


Basic CSS
Add the CSS code to the right to the head of the document, designing the page. 
I have added an image to fit in the head of the document, that you can find here. the heading section in a different way.

Creating the Form
create the form that contain our quiz. For this, using several different radio buttons using type="radio". For each question,  I've wrapped the inputs with labels. We'll style them below.
The correct answer will receive a value, and an incorrect answer will receive a value of 0. depending on how you'd like to weight answers. 
In your document, replace the series of questions with the form script to the right. You will open the form tag, giving it an id of form1, so that can be used with the onsubmit event. retain the DOM element you created to hold the score.


Adding Interactivity
So far, i have created a nice HTML page with some CSS styling. i have a form in it with several questions and answers. to add the functionality to the form with JavaScript, so that something happens when the form is submitted.
Updated. Slightly different than video: To get the value of a radio button, we have to evaluate which selection is checked. See the code to the right.
The result is calculated as the total of the four scores, and then that amount is passed via getElementById into the id "grade" in the HTML.

