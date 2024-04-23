<!DOCTYPE html>
<html lang="en">
  <head>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/1.9.1/p5.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/1.9.1/addons/p5.sound.min.js"></script>
    <link rel="stylesheet" type="text/css" href="style.css">
    <meta charset="utf-8" />

  </head>
  <body>
    <main>
    </main>
    <script src="sketch.js"></script>
  </body>
</html>


Javascript
let x; 

function setup() {
  createCanvas(800, 800);
  x = 0;
  noLoop();
  board = []
  
}
 function grid(row, col) {
   row = 0;
   col = 0;
    for (var r=0;r<rows;r++){
    board.push(row)
    
    }
      for (var c=0;c<cols;c++){}
     
   
 }
function draw(){
rect(200,200,200,200), fill(0);
}



CSS
html, body {
  margin: 0;
  padding: 0;
}
canvas {
  display: block;
}


This week, try and finish the board/ click 
Next week continue to work on board add game logic
Continue addeding game logic, might take a while
add diffret sized boards?
