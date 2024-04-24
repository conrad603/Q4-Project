v<!DOCTYPE html>
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
let row;let col
let size =40

function setup() {
  noLoop();
  createCanvas(600, 600);
  row = height/size;
  col = width/size;
  board = []
  
}

    
   

function draw(){
  background(0);
    for (let r=0;r<row;r++){
      for (var c=0;c<col;c++){
       rect(c*size, r*size, size,size)
      }
    }
  
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
