# Dice Game

A fun, two-player dice game where players take turns rolling a die, accumulating points in a race to reach a target score of 30. Players can roll the dice to add points to their current round, but rolling a 1 ends their turn. Players can also "hold" their score to accumulate it into their total score. The first player to reach or exceed the target score wins!

## Table of Contents
- [How to Play](#how-to-play)
- [Features](#features)
- [Installation](#installation)
- [Game Rules](#game-rules)
- [Technologies Used](#technologies-used)
- [Credits](#credits)

## How to Play

1. Player 1 starts the game by rolling the dice.
2. The dice shows a number between 1 and 6:
   - If the dice rolls a 2-6, the number is added to the player's current round score.
   - If the dice rolls a 1, the player loses their turn and their current round score is reset to 0. The next player takes over.
3. The player can choose to "Hold" their score. When holding, the current round score is added to the total score, and the next player gets their turn.
4. The first player to reach or exceed 30 points wins the game.

## Features

- **Two-player mode**: Players can switch turns, roll the dice, and hold their score.
- **Dynamic UI**: Updates the scores and player states based on gameplay.
- **Dice roll animation**: Displays a dice face that corresponds to the roll.
- **Winner declaration**: Highlights the winning player and stops further action.
- **New Game button**: Resets the game for a fresh start.

## Installation

1. Clone the repository to your local machine using:

   ```bash
   git clone https://github.com/your-username/dice-game.git

2. Open the folder and run the game by opening the index.html file in your browser.


