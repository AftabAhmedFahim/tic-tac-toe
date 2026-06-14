# Tic Tac Toe

A simple single-player Tic Tac Toe game built with Python, Pygame, and NumPy following `minimax algorithm`.
You play as circles and the computer plays as crosses using a minimax-based move
selector.

## Features

- 3x3 Tic Tac Toe board
- Mouse-based square selection
- Computer opponent using minimax
- Win and draw highlighting
- Press `R` to restart the game

## Requirements

- Python 3
- Pygame
- NumPy

Install the dependencies with:

```bash
python -m pip install pygame numpy
```

## Run

Start the game with:

```bash
python main.py
```

## How To Play

Click an empty square to place your circle. The computer will automatically place
an `X` after your move. The game ends when either player gets three in a row or
the board is full.

Controls:

- Click: place your move
- `R`: restart the game
- Window close button: quit

## Project Structure

```text
.
+-- main.py
`-- README.md
```

`main.py` contains the full game loop, drawing logic, board state, win checks,
restart behavior, and minimax computer player.
