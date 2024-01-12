# Changing Styles of a Div Using DOM in JavaScript

This repository provides a simple example of how to dynamically change the styles of a div element using the Document Object Model (DOM) in JavaScript.

## Getting Started
Open the index.html file in a web browser.
## Understanding the Code
The index.html file contains a basic HTML structure with a div element:

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>DOM Style Manipulation</title>
  <style>
    /* Some initial styles for the div */
    #myDiv {
      width: 200px;
      height: 100px;
      background-color: rgb(35, 218, 50);
      color: black;
      margin: 20px;
      padding: 10px;
      font-size: 16px;
      font-weight: normal;
    }
  </style>
</head>
<body>

  <div id="myDiv">Hello, I'm a div!</div>

  <script>
    // Get the div element by its ID
    var myDiv = document.getElementById("myDiv");

    // Change the styles using JavaScript
    myDiv.style.backgroundColor = "yellow";
    myDiv.style.color = "blue";
    myDiv.style.margin = "20px";
    myDiv.style.padding = "10px";
    myDiv.style.fontSize = "18px";
    myDiv.style.fontWeight = "bold";
    myDiv.style.height = "200px";
    myDiv.style.width = "300px";
  </script>

</body>
</html>

## Repository

1. Clone the repository to your local machine.

```bash

https://github.com/TheShahilRaj/DOM-Style-Manipulation.git

