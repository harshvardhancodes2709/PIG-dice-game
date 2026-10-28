# PIG-dice-game
A multiplayer PIG Dice Game built with Python where 2–4 players roll a six-sided die to reach 50 points. Rolling a 1 ends the turn and loses all points earned during that turn.

# PIG Dice Game

A simple multiplayer PIG Dice Game built with Python, where players take turns rolling a six-sided die to reach a target score of 50 points.

## Features
- Supports 2–4 players.
- Random dice rolls.
- Tracks individual player scores.
- Players can choose whether to roll again or end their turn.
- Rolling a 1 loses all points accumulated during the current turn.
- The first player to reach 50 points wins.

## Requirements
- Python 3

## How to Run

1. Clone or download this repository.
2. Open the project folder in your terminal.
3. Run the following command:

```bash
python3 main.py
```

## How to Play

1. Enter the number of players (2–4).
2. Each player takes turns rolling the die.
3. Enter `y` to roll the die again.
4. Each roll adds to your current turn score, unless you roll a 1.
5. Rolling a 1 ends your turn and resets your current turn score to zero.
6. You can choose not to roll again to add your turn score to your total score.
7. The first player to reach 50 points wins the game.

## Technologies Used
- Python
- Random module
- Functions
- Loops and conditional statements
- Lists and score tracking
