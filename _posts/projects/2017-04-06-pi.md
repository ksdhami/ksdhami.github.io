---
layout: project
permalink: /:title/
category: projects

meta:
  keywords: "Maze, Assembly, C, Raspberry Pi, Pi"

project:
  title: "Maze"
  type: "Pi"
  url: "https://github.com/ksdhami/SNES-Maze"
  logo: "/assets/images/projects/purplepineapple/maze.png"
  tech: "C, Assembly ARMv8, Raspberry Pi"

agency:
  title: "Computer Machinery II"
  url: "http://contacts.ucalgary.ca/info/cpsc/courses/f18/CPSC359"
  year: "2018"

images:
  - image:
    url: "/assets/images/projects/purplepineapple/rasp_pi.jpg"
    alt: "Aqua Pineapple website on tablet, mobile and desktop"
  - image:
    url: "/assets/images/projects/purplepineapple/snes_controller.jpg"
    alt: "Aqua Pineapple website on a desktop device"
  # - image:
  #   url: "/assets/images/projects/purplepineapple/mobile.jpg"
  #   alt: "Aqua Pineapple website on a mobile device"
---
<p>A program for the Raspberry Pi that presents a maze on an HDMI monitor. Red is used to represent the player as they move through the maze on the pathways. When the player reaches the exit of the maze, they are redisplayed in green, indicating that the maze has been solved and the game is over.
<br><br>
The program uses a SNES controller connected to the Raspberry Pi to control the movement of the player through the maze. When your program starts up, it displays the maze, but not the position of the player. When the user presses the controller start button, the player appears in red in the starting position. The joypad arrow buttons are used to move the player one position to the left, right, up, or down. The player can only move on the pathways, and is not allowed to go through any walls or leave the playing area. When the player reaches the exit of the maze they can press the start button to restart the game.
<br>
</p>
###### *Click title for project repository*