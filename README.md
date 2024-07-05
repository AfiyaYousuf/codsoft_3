# codsoft_3
Tic-tac-toe

# Tic-Tac-Toe Game with Minimax Algorithm

This project implements a Tic-Tac-Toe game where the user can play against an AI that uses the Minimax algorithm with alpha-beta pruning to determine its moves.

## Features

1. **Game Initialization**: The game starts with an empty 3x3 board.
2. **User Input**: The user can enter their move by specifying the row and column indices.
3. **AI Move Calculation**: The AI calculates the best move using the Minimax algorithm with alpha-beta pruning.
4. **Win/Draw Detection**: The game checks for a win or draw after each move.
5. **Game Loop**: The game continues until there is a win or a draw.

## How It Works

1. **Board Printing**: The board is printed after each move.
2. **Move Validation**: The game ensures that the user’s move is valid.
3. **Minimax Algorithm**: The AI uses the Minimax algorithm to evaluate the best possible move, considering both maximizing its own chances of winning and minimizing the user's chances.
4. **Alpha-Beta Pruning**: This optimization technique reduces the number of nodes evaluated in the Minimax algorithm, making it more efficient.
5. **Win Conditions**: The game checks if any player has won after each move.
6. **Draw Condition**: The game checks if the board is full, indicating a draw.

## Example Interaction

1. **User Input**: The user is prompted to enter the row and column for their move.
2. **Board Update**: The board is updated with the user’s move and printed.
3. **AI Move**: The AI calculates and makes its move, and the updated board is printed.
4. **Win/Draw Check**: The game checks for a win or draw after each move.
5. **Game Continuation**: The game continues until a win or draw is detected.

## Running the Game

- To start the game, simply run the script.
- The user is prompted to enter their move, and the AI will respond with its move.
- The game continues until there is a winner or the board is full.


