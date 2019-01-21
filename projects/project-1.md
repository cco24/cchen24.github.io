---
layout: project
type: project
image: images/tictactoe1.png
title: Tic-Tac-Toe
permalink: projects/Tic-Tac-Toe
# All dates must be YYYY-MM-DD format!
date: 2019-01-20
labels:
  - Python
---

<div class="ui small rounded images">
  <img class="ui image" src="../images/tictactoe1.png">
  <img class="ui image" src="../images/tictactoe2.png">
</div>


Appropriate description: Your project description should provide at least 3 paragraphs that describe: (1) what the project was about; (2) what your role was and how much of the work you were responsible for; and (3) what did you learn from the experience?


This project is a simple, non-graphically implemented tic-tac-toe game based on four exercises found on practicepython.org. The author of the website and exercises is Michele Pratusevich. The creation process is split up into those four exercises: 1) a module to print the arbitrarily sized game board as a single ```string``` 2) a module to check throughout the game if and which player won 3) a module to modify the ```string``` board with the players' moves during the actual game 4) putting all those modules together to create the game. In addition to the 


This project was part of an individual attempt of mine to practice programming. 





Here are the links to those four exercises along with a link to the "About" section of the website:

["Exercise 24 Draw a Game Board"](https://www.practicepython.org/exercise/2014/12/27/24-draw-a-game-board.html)

["Exercise 26 Check Tic Tac Toe"](https://www.practicepython.org/exercise/2015/11/16/26-check-tic-tac-toe.html)

["Exercise 27 Tic Tac Toe Draw"](https://www.practicepython.org/exercise/2015/11/26/27-tic-tac-toe-draw.html)

["Exercise 29 Tic Tac Toe Game"](https://www.practicepython.org/exercise/2016/08/03/29-tic-tac-toe-game.html)

[about practicepython.org and Michele Pratusevich](https://www.practicepython.org/about/)





Micromouse is an event where small robot “mice” solve a 16 x 16 maze.  Events are held worldwide.  The maze is made up of a 16 by 16 gird of cells, each 180 mm square with walls 50 mm high.  The mice are completely autonomous robots that must find their way from a predetermined starting position to the central area of the maze unaided.  The mouse will need to keep track of where it is, discover walls as it explores, map out the maze and detect when it has reached the center.  having reached the center, the mouse will typically perform additional searches of the maze until it has found the most optimal route from the start to the center.  Once the most optimal route has been determined, the mouse will run that route in the shortest possible time.

For this project, I was the lead programmer who was responsible for programming the various capabilities of the mouse.  I started by programming the basics, such as sensor polling and motor actuation using interrupts.  From there, I then programmed the basic PD controls for the motors of the mouse.  The PD control the drive so that the mouse would stay centered while traversing the maze and keep the mouse driving straight.  I also programmed basic algorithms used to solve the maze such as a right wall hugger and a left wall hugger algorithm.  From there I worked on a flood-fill algorithm to help the mouse track where it is in the maze, and to map the route it takes.  We finished with the fastest mouse who finished the maze within our college.





