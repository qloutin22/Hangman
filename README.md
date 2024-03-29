# Hangman

<h1>Project Title: Hangman Game </h1>

# Table of Contents
- [Description](#description)
- [Installation Instructions](#installation-instructions)
- [Game Logic](#game-logic)
- [File Structure](#file-structure)
- [License Information](#license-information)


## Description:

The Hangman Game is a classic word-guessing game implemented in Python. The aim of the project is to allow users to play the game where the computer selects a word at random, and the player attempts to guess the word by suggesting letters within a limited number of attempts. The game provides an interactive interface for users to input their guesses and keeps track of the progress of the game, revealing correctly guessed letters and penalizing incorrect attempts. Throughout this project, I learned about classes , magic methods , methods in a class and While True loops.

## Installation Instructions:

To run the Hangman game on your local machine, follow these steps:

Ensure you have Python 3.11.5 installed on your system.
Download or clone the repository to your local machine: git clone https://github.com/qloutin22/hangman385
Navigate to the project directory in the terminal/command prompt.
Run the game by executing the command: python hangman.py

## Usage Instructions:

Upon running the game, follow the prompts displayed on the screen.
You will be presented with a series of dashes representing the hidden word.
Guess letters by entering them via the keyboard.
Continue guessing letters until you either reveal the entire word or exhaust the allowed number of attempts.
The game will display the progress of your guesses and inform you if you win or lose.

## Game Logic
Below I will explain the logic of each method in the Hangman class:
<h4>def __init__ function </h4>
Defines attributes for the hangman class.
<h4>def check_guess </h4>
Checks guesses from user input against the letters in the randomly generated word.
<h4>def ask_for_input </h4>
This method asks the user for a letter and will print a response dependant of if that letter is valid or has already been used.
<h4>def play_game </h4>
This method determines the outcome of the game.

## File Structure
|---milestone 5
|---README.ms
## License Information
This project is licensed under the [MIT License]# Hangman
