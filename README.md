# Project 3: Pong 
## Introduction

This is for playing the game of Pong on the msp430. This game is created using modified code from Professor Eric Fraudenthal, especially shapemotion.c. The layout for the red and green paddles comes from using the rectangle layout in the demo code, with altered dimensions. The ball layout was modified from the demo code as well and has the properties to only bounce off the left and right wall. If the ball touches the top or bottom walls the game registers that as point for either the red or green paddle. Lastly, the paddes are designed to make the ball bounce if the ball touches the paddle.

## How To Run and Play

To run the program you need to make all from the original file in the repisotory

$ make all

and goto shapemotion file and call
$ make clean

$ make load

To play the game: 

Player 1: RED Paddle

Player 2: GREEN Paddle

Switches s1 and s2 move the RED paddle left and right 

Switches s3 and s4 move the GREEN paddle left and right

Any of the two players that score 4 points will win the game and a gameover followed by which player won will print in the screen,
