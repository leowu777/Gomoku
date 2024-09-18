# Gomoku Game

## Overview

Gomoku, also known as Five in a Row, is a classic strategy game where players take turns placing stones on a board. The objective is to be the first to form an unbroken line of five of one's own stones either horizontally, vertically, or diagonally. This game is developed using **Processing** and features both Player vs Player and Player vs AI modes.

## Files

- **Gomoku.pde**: The main game loop where the core mechanics of the Gomoku game are handled.
- **GomokuBoard.pde**: This file defines the game board and manages drawing and updating it.
- **Player.pde**: Defines the player class, handling input and tracking the current player’s state.
- **AiMove.pde**: Implements the AI logic for the game, allowing a player to compete against a computer opponent.
- **WinChecker.pde**: This file contains the logic to check for win conditions, ensuring a valid five-stone line is correctly identified.
- **Point.pde**: Defines a point class for managing coordinates on the board.
- **background.jpg**: Background image used in the game.

## How to Play

1. **Game Modes**:
   - **Player vs Player**: Two human players take turns placing their stones on the board.
   - **Player vs AI**: The player competes against the AI, with the AI making calculated moves to challenge the player.

2. **Gameplay**:
   - The game is played on a 15x15 board.
   - Players place their stones by clicking on an empty intersection on the board.
   - The first player to align five stones in a row either horizontally, vertically, or diagonally wins the game.

## Features

- **Player vs Player** and **Player vs AI** modes.
- A fully functional AI opponent that challenges players with intelligent move selection.
- A visual game board with a background image to enhance the gaming experience.
- Win condition detection with automatic game reset after a match concludes.

## Controls

- **Mouse Click**: Place a stone at the clicked location.

## Installation and Running

1. Install **Processing** from [Processing's website](https://processing.org/download/).
2. Download all the files from this repository and place them in the same folder.
3. Open `Gomoku.pde` in Processing.
4. Click the play button in Processing to run the game.

## Future Improvements

- Add more difficulty levels for the AI.
- Implement an online multiplayer mode.
- Add custom board sizes and rule variations.
