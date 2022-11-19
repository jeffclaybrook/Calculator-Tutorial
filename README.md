# Calculator-Tutorial
Build a basic calculator with HTML, CSS, and JavaScript

## TLDR;
- Semantic HTML
- CSS grid
- Vanilla JavaScript with arrow functions

### Demo link:
https://jeffclaybrook.github.io/Calculator-Tutorial/


In this tutorial, you'll create a very basic calculator app using HTML, CSS, and Javascript. This tutorial is intended for beginners and anyone who appreciates clean symmetrical code.

Overview
- The calculator is styled using CSS grid
- The screen portion is a single input tag with a class and an ID. The class is for styling and the ID is used for accessing the element in JavaScript
- Each button has a class of either 'symbol' or 'number', which are used for styling purposes
- Each button also has an onclick function assigned to it
- The wipe() function is used to clear the display by resetting the value of the input tag to an empty string
- The show() function is used to type the corresponding value of the clicked button (represented as n in js file) into the input tag
- The calc() function evaluates the value of the input tag and does the actual calculations

IMPORTANT - in order for the calc() function to work, the buttons onclick function must have the appropriate operator assigned to it, i.e:

/
*
-
+
=

Happy coding!
