# CodeAlpha_HumanGame

A simple command-line Hangman game built in Python.

## Game Description
This project uses a random word from a predefined list and lets the player guess letters one at a time.

The game:
- chooses a random word from a list
- shows the hidden word with underscores for unguessed letters
- keeps track of guessed letters
- allows only single alphabetic inputs
- gives the player 6 wrong guesses before ending the game
- announces the correct word when the game ends

## How to Play
1. Open a terminal in the project folder.
2. Run:
   python Game.py
3. Enter one letter at a time when prompted.
4. Try to guess the full word before you run out of wrong guesses.

## Example Behavior
- Word is displayed as: _ _ _ _ _
- If you guess a correct letter, it is revealed in the word.
- If you guess incorrectly, the number of wrong guesses increases.
- The game ends when the word is fully guessed or 6 wrong guesses are used.

## Files
- Game.py - main game logic
