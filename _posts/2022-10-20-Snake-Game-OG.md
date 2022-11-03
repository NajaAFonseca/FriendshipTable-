---
author: Naja Fonseca
permalink: /snake-game
---

<!DOCTYPE html>
<html>
  <head>
    <!-- title of game -->
  	<title>Snake Game</title>
    <link href="https://fonts.googleapis.com/css?family=Antic+Slab" rel="stylesheet">

  </head>

  <body>
    <!--setting the canvas up as a id and canvas size-->
    <canvas id="snakeboard" width="400" height="400"></canvas>
    <script src="assets/js/snake.js"></script>

  <!--setting up the position of the board/canvas-->
    <style>
      #snakeboard {
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
      }
      #score {
        text-align: center;
        font-size: 100px;
      }
    </style>
  </body>
  </html>