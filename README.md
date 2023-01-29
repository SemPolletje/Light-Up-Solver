# Light-Up-Solver

# Introduction
As the title says, this project is a way of making an automatic solver for any uniquely solvable Light-Up puzzle (not to be confused with Lights Out).
This solver uses a way of creating inequalities per area that a white square can see. By creating these inequalities we can add different inequalities together to provoke more information about the square.

We then further optimized the setup by creating different ways of adding these inequalities, or making sure to remove unnecessary inequalities.
Because we used these technologies, we created a very quick algorithm that still lacks define touches when it comes to bigger puzzles. This is an opportunity for anyone reading this to try making our algorithm quicker. We have selected a method to do so, but because of, amongst others, a lack of time (yes this was a project for school) we weren't able to. Our method would be:

Try creating a definition that checks the priority of adding different inequalities. For example: Two inequalities from squares in eachother's neighbourhood are more important to add up than two inequalities of two squares on the opposite sides of the board.

We ourselves created this project because one of us was bored of playing this game mindlessly without getting an answer if the puzzle is too difficult, so we wanted to create a way to make something that will solve it for us. We learned a lot about python in itself, but also about making an efficient program, handy datastructures and keeping our code as simple and clear as possible.

# How to run:
It is fairly simple to run this program, considering it uses only simple imports, such as Turtle. Here is a step-by-step description:
1) Copy our Python code called LightUpOplosser, found in this GitHub repository. Try not looking at the notes there to much, these are in Dutch if you would like to translate.
2) Open your python editor including console, like Spyder. We advise you to run it on a form of python3, as this is the language we used.
3) Paste the code.
4) Now create a uniquely solvable puzzle, or copy one from the site https://www.puzzle-light-up.com/.
5) Start running the code.
6) It will first ask you the 'Breedte' (aka width) of your puzzle, you can type this in. Press Enter.
7) Now it asks the 'Hoogte' (aka length) of your puzzle, type this in. Press Enter.
8) It will now ask you for 'Hint', these are the dark squares with numbers in them. You enter as followed: 'z x y', with z being the number and x & y being your x & y coordinate on the board (starting at 1,1). Press Enter and repeat for as many hints you have.
9) When you typed in all the hints, you can type in 'stop', to stop adding hints. Press Enter.
10) Now it will ask you for 'Zwart vakje', these are the dark squares without the numbers in them. You enter as followed: 'x y' with x & y being the coordinates again. Press Enter and repeat for as many (empty) dark squares you have.
11) When you typed in all the dark squares, type 'stop' to stop adding hints. Press Enter.
12) This part is where it gets fun, you will either already have gotten a message saying there has been a mistake in the input, at which part you will have to go again from step 5. Otherwise it will run (please let it run untill it is finished or gives an error, we know it might take a while) and give you the answer in the form of:
[[a,b],[c,d],[e,f],[g,h]]. These are the coordinates [x,y] where a lightbulb needs to be. Also now is the time there will appear a new icon on your taskbar, called 'Python Turtle Graphics'. Here you will find a drawing of the complete board with the lightbulbs in place.
13) If at any point you would like to try again, close the 'Python Turtle Graphics' window and you can simply go back to step 5 again.

# Credits
We hereby want to allow ourselves to be known as the first creators of this program, Jelle Bloemendaal, Rik Roseboom and Sem van de Pol. We would also like to credit a source we used, Shi-Jim Yen , Shih-Yuan Chiu A simple and rapid Lights-up solver (2010).

# License
As we said before, we would like to encourage you to try and improve our code. This is with the idea that the credit is given about the code we created, whilst also showing off what you made as a new part.
