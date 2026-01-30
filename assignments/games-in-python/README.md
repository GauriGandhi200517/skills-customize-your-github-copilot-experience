
# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Build the classic word-guessing game using Python strings, loops, and user input. Students will practice string manipulation, control flow, and simple I/O.

## 📝 Tasks

### 🛠️	Build the Hangman Game

#### Description
Create a playable Hangman game that randomly selects a hidden word and lets a player guess letters until they either guess the word or run out of attempts.

#### Requirements
Completed program should:

- Randomly select words from a predefined list
- Accept single-letter guesses and reveal correctly guessed letters in the word (e.g. `_ _ a _ _`)
- Track and display remaining incorrect guesses
- Prevent repeated guesses from counting against the player
- End when the word is guessed or attempts are exhausted, showing a win or lose message
- Include inline comments and a short README describing how to run the program

#### Example (playthrough)
```
Hidden word: _ _ _ _ _
Guess a letter: a
Progress: _ a _ _ _
Incorrect guesses remaining: 5
```

### 🛠️	Optional Enhancements

#### Description
Add one or more optional features to improve user experience or code quality.

#### Requirements

- Load words from an external `data/words.txt` file
- Add difficulty levels that change number of attempts
- Save high scores to a file
- Provide simple unit tests for core logic (optional)

Do not add extra sections unless explicitly specified by the template.
