# OIBSIP-TASK2 : NUMBER GUESSING GAME

Game Class:
Attributes:

systemInput: Randomly generated number between 1 and 100.
userInput: User's input for guessing the number.
noOfGuesses: Number of attempts made by the user.
Constructor (Game()):

Generates a random number between 1 and 100 when an object of the Game class is created.
Methods:

takeUserInput(): Takes user input for guessing the number, limiting the number of guesses to 10.
isCorrectGuess(): Checks whether the user's guess is correct, too high, or too low, and provides feedback. Also calculates and displays the user's score based on the number of guesses.
GuessTheNumber Class:
Static Method (`takeIntegerInput(int limit)'):

Ensures that the user enters a valid integer within a specified limit.
Main Method (main()):

Presents a menu with options to start the game or exit.
If the user chooses to start the game, it enters a loop to allow for multiple rounds.
In each round, a new instance of the Game class is created, and the user is prompted to guess the number.
After each round, the user is given the option to play the next round or exit.
Flow of Execution:
The user starts the game or exits.
If the user starts the game, a loop begins for multiple rounds.
In each round, a random number is generated, and the user attempts to guess it within 10 tries.
Feedback is provided after each guess (correct, too high, too low).
After each round, the user decides whether to play the next round or exit.
