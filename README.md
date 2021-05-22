# CS151_FinalProject

This project creates the game of Kyudoku using logic programming. 

The puzzle is a 6x6 grid of numbers that range from 1 to 9. There is one number selected to start (in yellow).

How to Play:
- Choose the numbers so the sum in every row or column is 9 or less:
    - Click once on a number to remove from the grid. This will turn the whole square red.
    - Click twice to select the number as part of your solution. This will turn the background of the square yellow.
    - Click a third time to deselect the number completly. This changes the background to white and is as if you never clicked on it.
- Each number, 1 to 9, must appear exactly once.
- The game is over when there are exactly 9 unique numbers selected on the grid and the sum rule above is followed.
- You can track your process with the notes under the board. The rules will turn green when they are satisfied and red when they are not satisfied.

Hints:
- Start by removing all the numbers that are the same as the single number given from the grid (by clicking once)
- Then look at the column of the number given and the row, crossing off all numbers that would make the sum of that row or column greater than 9.
- Look to see if there is only one instance of a number. If so, you know that needs to be in you solution because each number has to appear once. Repeat these steps until you solve the puzzle!

