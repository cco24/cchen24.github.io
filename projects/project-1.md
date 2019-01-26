---
layout: project
type: project
image: images/tictactoe1.png
title: Tic-Tac-Toe
permalink: projects/tictactoe
# All dates must be YYYY-MM-DD format!
date: 2019-01-20
labels:
  - Python
summary: A tic-tac-toe game based on online exercises.
---

<div class="ui medium rounded images">
  <img class="ui image" src="../images/tictactoe1.png">
  <img class="ui image" src="../images/tictactoe2.png">
</div>


This program is a non-graphical implementation of tic-tac-toe based on four exercises found on Michele Pratusevich's [practicepython.org](https://www.practicepython.org/about/). I broke my program down into four modules corresponding to those four exercises: one to print the arbitrarily sized game board as a single ```string``` (["Exercise 24 Draw a Game Board"](https://www.practicepython.org/exercise/2014/12/27/24-draw-a-game-board.html)), one to check throughout the game if and which player won (["Exercise 26 Check Tic Tac Toe"](https://www.practicepython.org/exercise/2015/11/16/26-check-tic-tac-toe.html)), one to modify the game board ```string``` with the players' moves during the actual game (["Exercise 26 Check Tic Tac Toe"](https://www.practicepython.org/exercise/2015/11/16/26-check-tic-tac-toe.html)), and one to put all those modules together to create the game (["Exercise 29 Tic Tac Toe Game"](https://www.practicepython.org/exercise/2016/08/03/29-tic-tac-toe-game.html)). 

In order to make my program resemble a "real-life" and practical tic-tac-toe game, I also implemented certain functionalities. In order to minimize the opportunities for cheating, players would not be able to insert their moves in squares already filled by their opponent (and/or by their ownselves in previous turns). If the board is all filled up and there's no winner, the game will indicate so before terminating. In addition, the smallest size of the board users are restricted to enter is 3 x 3, and the program will continue running until they do. 

I found practicepython.org during the summer after my first year of programming courses in college. That summer was when I decided to brush up on my programming skills by revisiting general programming fundamentals by learning Python after reflecting on that first year. In that first year, I was exposed to the intricacies of how logic is applied in programming and the multitude of methods for storing and accessing data, but those courses were difficult for me, and I wasn't able to grasp all that I was taught. Instead of being whole and organized, I felt like my understanding of what I learned in those courses was muddled and contained holes of missing information I failed to retain. This project was one of the things that helped me to         , and it was the largest piece of code I've ever written that wasn't for school. 









