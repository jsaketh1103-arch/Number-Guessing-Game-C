# Number Guessing Game in C

A simple command-line number guessing game built using the C programming language.

## Features

- Generates a random number between 1 and 100
- Allows the user to repeatedly guess the number
- Provides hints to guess a higher or lower number
- Counts the total number of guesses
- Continues until the correct number is guessed

## Concepts Used

- Variables
- Loops
- Conditional statements
- `rand()`
- `srand()`
- `time()`
- Random number generation

## How It Works

The program generates a random number between 1 and 100. The player keeps entering guesses until the correct number is found. After each incorrect guess, the program tells the player whether to guess a higher or lower number.

## How to Run

Compile the program:

```bash
gcc number_guessing_game.c -o game
