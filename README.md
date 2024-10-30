# Number elimination Game
This Java project is a grid-based puzzle game where the player aims to eliminate numbers in a 5x5 grid so that each row and column sum matches a target value. The game is played via command-line input, providing a fun way to test strategic thinking and logic.

*Game Objective*
The objective of the game is to eliminate specific numbers from the grid so that the sum of each row and column matches its assigned target sum.

*Game Rules*
The game initializes a 5x5 grid with random numbers between 1 and 9.
Each row and column has a randomly set target sum based on the initial numbers in the grid.
Players can eliminate a number at specific coordinates by entering the row and column.
Players can undo their last move if they make a mistake.
The game is won when the sum of each row and column equals its respective target sum.
*How to Play*
Run the game, and the grid with target sums will be displayed.
Enter the coordinates of the number you wish to eliminate in the format row col.
Use the command:
z to undo the last move.
q to quit the game.
The game will display "Congratulations!" when you win by matching all row and column target sums.
*Commands*
row col - Eliminate the number at the specified row and column.
z - Undo the last move.
q - Quit the game.
*Code Structure*
Grid Class: Handles grid initialization, target generation, and elimination operations.
Game Class: Manages gameplay loop, user input, and win condition checking.
