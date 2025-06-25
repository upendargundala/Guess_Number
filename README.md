# Guess_Number
Number Guessing Game
An engaging and classic command-line number guessing game written in Python. Players have a limited number of chances to guess a secret number within a user-defined range.

Table of Contents
Description

How to Run

How to Play

Features

Future Improvements

License

Description
This is a classic "guess the number" game where the computer selects a random integer within a range specified by the player. The player then gets 7 attempts to guess the number. After each guess, the game provides feedback (too high, too low, or correct) to help the player narrow down their next guess.

How to Run
Prerequisites
Python 3.x installed on your system.

Execution Steps
Save the code: Copy the provided Python code into a file named guess_the_number.py (or any other .py extension).

Open a terminal/command prompt: Navigate to the directory where you saved the file.

Run the game: Execute the following command:

python guess_the_number.py


How to Play
Start the game: Run the Python script as described in the How to Run section.

Enter bounds: You will be prompted to enter a lower bound and an upper bound for the number range. The secret number will be chosen randomly within this range (inclusive).

Make your guess: You have 7 chances.

Receive feedback: After each guess, you will be told if your guess was "Too high!", "Too low!", or "Correct!".

The game concludes in one of two ways:

If you guess the number correctly within 7 attempts, you win and the game tells you how many attempts it took.

If you run out of chances without guessing the number, you lose, and the game reveals the secret number.

Features
User-defined range: Players can set the lower and upper bounds for the secret number.

Limited attempts: Players have 7 chances to guess the number.

Helpful feedback: Provides hints (too high/too low) after each incorrect guess.

Simple and intuitive: Easy to understand and play.

Future Improvements
Add different difficulty levels (e.g., more or fewer chances).

Implement input validation to ensure users enter valid numbers for bounds and guesses.

Allow the player to choose whether to play again after a game ends.

Keep track of the player's high score (fewest attempts).

Add a graphical user interface (GUI) using libraries like Tkinter or PyQt.

License
This project is open-source and available under the MIT License. Feel free to modify and distribute it.
