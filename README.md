<!DOCTYPE html>
 <html>

<input type="text">

<head>
  <title>Change Button Colour</title>
</head>
<body>
  <button id="colorButton">Click me to change colour</button>

  <script>
    //Get a reference to the button element
    var button = document.getElementbyId("colorButton");

    //Function to change the button colour
    function changeColor(){
      //Generate a random colour (hexadecimal)
      var randomColor = "#" + Math.floor(Math.random()*16777215).toString(16);

      //Set the button's background color to the random color
      button.style.backgroundColor = randomColor;
      ]

      //Add a click event listener to the button
      button.addEventListener("click",changeColor);
      </script>
</body>
