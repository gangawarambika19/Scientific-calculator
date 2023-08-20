# Scientific-calculator

HTML Structure :
The HTML structure is divided into several parts:-

<!DOCTYPE html>: This declaration defines the document type and version as HTML.
<html lang="en">: The opening HTML tag with the "en" language attribute.
<head>: This section contains meta-information and links to external resources for the webpage.
<meta charset="UTF-8">: Sets the character encoding to UTF-8.
<meta name="viewport" content="width=device-width, initial-scale=1.0">: Sets the viewport for responsive design.
<title>Calculator</title>: The title of the webpage displayed in the browser tab.
<link rel="stylesheet" href="style.css">: Links an external CSS file named "style.css" for styling.
<body>: The main content of the webpage is contained within this section.
  .container: A container div that holds the entire calculator.
.display: A div for displaying the calculator's input and output.
#screen: An input field for displaying and entering calculations.
.btns: A container for the calculator buttons, organized into rows.
.row: Each row contains a set of calculator buttons.
Buttons for various mathematical operations and digits.
JavaScript Functions
Within the <script> tags, JavaScript code is included to provide functionality to the calculator:
screen and btn variables are declared to select the calculator screen and buttons.
A for...of loop iterates over each button element, attaching click event listeners. When a button is clicked, its text content is added to the calculator screen.
Several mathematical functions are defined, such as sin(), cos(), tan(), pow(), sqrt(), log(), pi(), e(), and fact(). These functions perform mathematical operations based on the button clicked and update the calculator screen with the result.
The eval() function is used to evaluate the expression in the calculator screen when the "=" button is clicked, and the result is displayed on the screen.
There's also a backspac() function, which doesn't seem to be implemented correctly. It should handle backspace functionality, but it's incomplete in the provided code.

CSS Styling :
The CSS styles in the <style> section define the visual appearance of the calculator and its buttons.
Here are some key styling points:The calculator is centered on the webpage with a background image.
The calculator screen (#screen) is styled to have a rounded border, a shadow, and a specific font size.
Calculator buttons have specific styling for their appearance, hover effects, and shadow.
Special buttons like "=" (#eval), "AC" (#ac), and others have distinct background colors and hover effects.

Conclusion :
This code represents a basic calculator web application with HTML for structure, CSS for styling, and JavaScript for functionality. Users can perform various mathematical operations by clicking on the buttons, and the results are displayed on the calculator screen. Note that there are some issues in the code, like the incomplete backspac() function, which may need further refinement for a fully functional calculator.
