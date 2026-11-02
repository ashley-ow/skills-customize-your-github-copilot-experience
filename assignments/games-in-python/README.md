
# 📘 Assignment: Hangman Game

## 🎯 Objective

Build a playable Hangman game in Python that uses strings, loops, conditionals, random selection, and user input. Players will guess letters to reveal a hidden word before they run out of attempts.

## 📝 Tasks

### 🛠️ Build the Hangman Game

#### Description
Write a program that randomly selects a word from a predefined list and lets the player guess it one letter at a time.

#### Requirements
Completed program should:

- Select one word at random from a list containing at least five words.
- Display the word as underscores and reveal each correctly guessed letter in its correct position.
- Accept one-letter guesses and track the number of incorrect guesses remaining, starting with six.
- Ignore repeated guesses without counting them as incorrect attempts.

### 🛠️ Complete and Test a Game

#### Description
Finish the game by handling both possible outcomes and checking that the game responds correctly to player guesses.

#### Requirements
Completed program should:

- End the game when the player reveals every letter or uses all six incorrect guesses.
- Display a clear win or loss message; on a loss, reveal the hidden word.
- Reject input that is not a single letter and prompt the player to guess again.
- Be tested with correct guesses, incorrect guesses, repeated guesses, invalid input, and both end-game outcomes.
