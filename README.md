# C++man - Hangman Game

A simple console-based Hangman game written in C++ where players guess letters to reveal a hidden word.

## How to Play

1. **Objective**: Guess the hidden word before running out of lives
2. **Gameplay**:
   - The program selects a random word and displays it as underscores
   - Guess one letter at a time
   - Correct guesses reveal the letter in the word
   - Incorrect guesses cost one life
   - Win by guessing all letters in the word
   - Lose if you run out of lives (6 total)

## Features

- Random word selection from a predefined list
- Input validation for letters only
- Prevents guessing the same letter multiple times
- Visual display of current progress with underscores
- Life counter
- Case-insensitive (lowercase only)

## Requirements

- C++ compiler with C++17 support or later
- `Random.h` header file (must be in the same directory)

## Building and Running

```bash
g++ -std=c++17 main.cpp -o cppman
./cppman
```

## Word List

The game includes these words:
- mystery
- broccoli  
- account
- almost
- spaghetti
- opinion
- beautiful
- distance
- luggage
- skibidi

## Game Rules

- You start with 6 lives
- Guess one lowercase letter at a time (a-z)
- Cannot guess the same letter twice
- Correct letters are revealed in the word
- Wrong guesses reduce your life count
- Game ends when you either:
  - Guess all letters (win)
  - Run out of lives (lose)

## Sample Gameplay

```
words: _______
Enter your letter: a
You guessed wrong;
words: _______
your lives: 5
```

Good luck and have fun playing C++man!
