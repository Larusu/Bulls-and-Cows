# Bulls and Cows

A collaboration project for Data Structures and Algorithms that implements the classic Bulls and Cows code-guessing game where you compete against an AI.

## Description

Bulls and Cows is a code-breaking game where both you and the AI each choose a secret code. On each turn, both sides try to guess each other's secret code. After each guess, you'll receive feedback:

- **Bulls**: Correct digit in the correct position
- **Cows**: Correct digit in the wrong position

The game features three difficulty levels:
- **Easy**: AI generates random guesses each turn
- **Medium**: AI uses guess history to make informed guesses
- **Hard**: Advanced AI (placeholder - not yet fully implemented)

## Features

- Configurable secret code length (default: 4 digits)
- Maximum 7 guesses per round
- Score tracking across multiple games
- Input validation (unique digits only, 0-9)
- Interactive game loop with replay option

## Prerequisites

- C++ compiler (g++, clang++, or MSVC)
- C++11 or later

## Setup Guide

### Clone Repository

```
https://github.com/Larusu/Bulls-and-Cows.git
cd Bulls-and-Cows/
```

### Compile and Run (Linux/macOS)

```bash
g++ BullsAndCowsGame.cpp -o main
./main
```

### Compile and Run (Windows)

```bash
g++ BullsAndCowsGame.cpp -o main.exe
./main.exe
```

## How to Play

1. **Choose Difficulty**: Select Easy (1), Medium (2), or Hard (3)
2. **Enter Secret Code**: Enter a 4-digit number with unique digits (e.g., `1234`)
3. **Make Guesses**: Enter your guess for the AI's secret code
4. **Review Results**: See how many Bulls and Cows you got
5. **Win Condition**: Guess the full code (4 Bulls) before the AI guesses yours

## Game Rules

1. Both player and AI each have a secret code with unique digits
2. Each round, both sides make a guess at the other's code
3. After each guess, you'll receive feedback:
   - **Bulls**: Correct digit in the correct position
   - **Cows**: Correct digit in wrong position
4. Maximum of 7 guesses per game
5. If neither side guesses correctly within 7 attempts, the game ends in a draw

## Project Structure

```
Bulls-and-Cows/
├── README.md
├── BullsAndCows/
│   ├── BullsAndCowsGame.cpp    # Main game (all difficulties)
│   ├── EasyAI.cpp               # Easy mode standalone
│   ├── MediumAI.cpp            # Medium mode standalone
│   └── *.exe                   # Pre-compiled executables
```

## Credits

Created by Jhervis Arevalo and Lars Timajo
