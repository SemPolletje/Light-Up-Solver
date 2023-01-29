# Light-Up-Solver

# Introduction
As the title says, this project is a way of making an automatic solver for any uniquely sulable Light-Up puzzle (not to be confused with Lights Out).
This solver uses a way of creating inequalities per area that a white square can see. By creating these inequalities we can add different inequalities together to provoke more information about the square.
We then further optimized the setup by creating different ways of adding these inequalities, or making sure to remove unnecessary inequalities.
Because we used these technologies, we created a very quick algorithm that still lacks define touches when it comes to bigger puzzles. This is an opportunity for anyone reading this to try making our algorithm quicker. We have selected a method to do so, but because of a lack of time (yes this was a project for school) we weren't able to:
Try creating a definition that checks the priority of adding different inequalities. For example: Two inequalities from squares connected are more important to add up than two inequalities of two squares opposite side of the board.

# How to run:
It is fairly simple to run this program, considering it uses only simple imports, such as Turtle. Here is a step-by-step description:
1) Download our python program
