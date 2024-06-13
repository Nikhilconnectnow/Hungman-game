##Hangman Game
Introduction
This Hangman game is a simple Python implementation of the classic word-guessing game. The objective is to guess the hidden word by suggesting letters. Each incorrect guess results in the drawing of a part of a hangman figure, with the game ending when either the word is correctly guessed or the hangman is fully drawn.

Features
Random word generation: A random word is selected from a predefined list each time the game is played.
ASCII art: Visual representation of the hangman stages using ASCII art.
Interactive gameplay: Users can input their guesses and receive feedback on whether the guess is correct or not.
Win/lose conditions: The game ends either when the word is guessed correctly or when the hangman figure is fully drawn.
Setup
Replit: Play the game directly on Replit here.
GitHub: Clone the repository to your local machine and run the hangman.py script using Python. GitHub Repository
How to Play
Upon starting the game, a hangman logo will be displayed.
You will be prompted to guess a letter.
Input a letter and press Enter.
If the letter is correct, it will be revealed in the word. If not, a part of the hangman figure will be drawn.
Continue guessing letters until the word is correctly guessed or the hangman is fully drawn.
Dependencies
Python 3.x
Files
hangman.py: The main Python script containing the Hangman game logic.
ascii.py: ASCII art for the Hangman logo and stages.
list.py: Predefined list of words for the game.
Contributing
Contributions are welcome! If you have any suggestions or improvements, feel free to open an issue or create a pull request.
