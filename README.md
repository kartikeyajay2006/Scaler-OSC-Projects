# 🎯 Number Guessing Game (Python CLI)

A small command-line game, and one of the first Python programs I wrote.

The computer picks a secret number and you guess it. After each guess it tells you whether to go higher or lower, and at the end it counts how many tries you took.

## Features

- **3 difficulty levels**: Easy (1–20), Medium (1–50) and Hard (1–100)
- **Hints** after every guess ("Too high!" or "Too low!")
- **Attempt counter** shown when you win
- **Input validation**: a non-number does not crash the game

## Run

```bash
python number_guess.py
```

```text
-------------- WELCOME TO NUMBER GUESSING GAME -----------
1 - Easy (Guess between 1-20)
2 - Medium (Guess between 1-50)
3 - Hard (Guess between 1-100)

Choose Your Difficulty: 2
Enter a number: 25
Too low! Try a bigger number.
Enter a number: 37
CONGRATULATIONS !! You did it in  2  trials
```

## Concepts practised

Loops, conditionals, functions, `random`, `try` / `except` and user input.
The best strategy is binary search: always guess the middle of the remaining range, and Hard mode needs at most ⌈log₂ 100⌉ = **7 guesses**.

## Author

**[Kartikeya Yadav](https://github.com/kartikeyajay2006)**
