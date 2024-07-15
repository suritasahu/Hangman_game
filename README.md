# Hangman_game
A classic Hangman game implemented in Python. This project showcases proficiency in Python programming, object-oriented principles, and basic game development. The Hangman game is a word-guessing game where the player tries to guess the word by suggesting letters within a limited number of attempts.


# Features
- **Object-Oriented Design**: The game is designed using object-oriented principles, making the code modular and easy to maintain.
- **Word List**: Includes a comprehensive list of words for the player to guess.
- **User Input Handling**: Validates user inputs to ensure they are single alphabetic characters.
- **Game State Tracking**: Keeps track of the number of attempts left, correct guesses, and the current state of the word being guessed.
- **ASCII Art**: Displays a simple hangman figure that progresses as the player makes incorrect guesses.


# Usage
- Start the game by running hangman.py.
- The game will randomly select a word from the word list.
- Guess letters one at a time. If the letter is in the word, it will be revealed in its correct position(s).
- If the guessed letter is not in the word, you lose one attempt. The game ends when the word is guessed or the player runs out of attempts.
