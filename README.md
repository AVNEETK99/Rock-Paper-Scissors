# Rock-Paper-Scissors

Rock Paper Scissors is a popular hand game that is played by two or more people. The game is played by making hand gestures representing "rock" (a closed fist), "paper" (an open hand), and "scissors" (a fist with the index and middle fingers extended and separated like a pair of scissors).

The game is often used as a way of making a decision or resolving a dispute between two people. The basic rule of the game is that rock beats scissors, scissors beat paper, and paper beats rock. The game is typically played in a best-of-three or best-of-five format. It is a simple, yet entertaining game that can be played virtually anywhere with no equipment necessary.

## Instructions to run the game

* Open the Github repository where the game code is hosted.

* Click on the green "Code" button and then select "Download ZIP" to download the code as a ZIP file.

* Extract the ZIP file to a folder on your computer.

* Open a command prompt or terminal window and navigate to the folder where you extracted the code.

* Type ```python rock.py''' and press Enter to start the game.

* Follow the prompts to play the game.

## Functionality of the code

* The first line of the code imports the 'random' module in Python. This module allows the generation of random numbers in the program.

* The next few lines use the 'print' function to display some instructions to the user regarding the rules of the Rock, Paper, Scissors game. The '\n' character is used to move the cursor to the next line, and the '+' operator is used to concatenate the different lines into a single string.

* The code then enters an infinite loop using the 'while True' statement. This is done to allow the user to keep playing the game until they choose to quit.

* Inside the loop, the user is prompted to enter their choice by typing either 1, 2, or 3, which represent Rock, Paper, or Scissors, respectively. The 'input' function is used to take user input, and the 'int' function is used to convert it to an integer.

* A while loop is used to check if the user has entered a valid choice. If the user enters a value less than 1 or greater than 3, they are prompted to enter a valid input.

* The program then assigns a corresponding name to the user's choice using an if-else statement.

* The program generates a random choice for the computer using the 'random.randint' function, which generates a random integer between the given range (1-3). Another while loop is used to ensure that the computer does not choose the same option as the user.

* The program assigns a corresponding name to the computer's choice using another if-else statement.

* The user's and computer's choices are printed using the 'print' function.

* The program checks the winning conditions for the game using a series of if-else statements. If the user wins, the 'result' variable is set to the user's choice. If the computer wins, the 'result' variable is set to the computer's choice.

* The winner of the game is then printed to the console using another 'print' statement.

* The user is prompted to play again using an 'input' statement. If the user enters 'n' or 'N', the program exits the loop, and the game ends.

* Finally, a 'print' statement is used to thank the user for playing the game.

