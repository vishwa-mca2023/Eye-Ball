# Eye-Ball

The provided HTML and CSS code creates a simple webpage with two animated eyes that follow the user's mouse cursor. Let's break down the code step by step:

The HTML structure:
<!DOCTYPE html>: This declaration specifies the document type and version of HTML being used (HTML5 in this case).
<html lang="en">: The root element of the HTML document, specifying the language as English.
<head>: This section contains metadata about the document and links to external resources such as stylesheets and scripts.
<meta charset="UTF-8">: Specifies the character encoding for the document as UTF-8.
<meta name="viewport" content="width=device-width, initial-scale=1.0">: This meta tag sets the viewport settings for responsive design.
<title>Document</title>: Sets the title of the webpage, which appears in the browser's title bar or tab.
<style>: This section contains inline CSS styles for styling the elements within the document.
<body>: The main content of the webpage is placed inside the <body> element.
CSS Styles:
The CSS styles define the appearance of the eyes and the animated balls within them. Some key CSS classes and properties include:
body: Sets the background color to light grey and removes margin and padding from the body element.
.eyes: Positions the eyes in the center of the viewport vertically using position: absolute and transform: translateY(-50%).
.eye: Styles the eye containers with a white background, margin, and border-radius to create circular eyes. They are displayed side by side with some spacing.
.ball: Styles the black pupils of the eyes with a circular shape using border-radius.
JavaScript:
The JavaScript code is placed within a <script> element at the end of the document.
It selects both .ball elements using document.getElementsByClassName("ball").
The document.onmousemove event handler tracks the mouse cursor's position and updates the position of the black balls (pupils) within the eyes.
It calculates the position of the pupils based on the mouse cursor's coordinates and applies the transform property to move them accordingly.
Overall, this code creates a fun and interactive effect where the eyes follow the movement of the mouse cursor on the screen
