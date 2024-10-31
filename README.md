# Tic-Tac-Toe-Game
This C++ program implements a console-based Tic-Tac-Toe game for two players. Players take turns placing their markers on a 3x3 board until one of them wins or the game ends in a draw. The program handles player input, board display, win condition checks, and switching turns.
# Tic-Tac-Toe Game in C++

This is a simple implementation of the classic Tic-Tac-Toe game using C++. The game runs in a console environment and allows two players to play against each other.

## Features
- Two players can play the game on a 3x3 grid.
- Players choose their marker ('X' or 'O') at the beginning.
- Checks for winning conditions after each move.
- Detects draw conditions when no moves are left.
- User-friendly display of the game board.

## How to Run
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/tic-tac-toe.git
    ```
2. Navigate to the project directory:
    ```bash
    cd tic-tac-toe
    ```
3. Compile the code using a C++ compiler:
    ```bash
    g++ tic_tac_toe.cpp -o tic_tac_toe
    ```
4. Run the game:
    ```bash
    ./tic_tac_toe
    ```

## Game Instructions
1. Player 1 selects a marker ('X' or 'O') at the start of the game.
2. Players take turns entering a slot number (1-9) to place their marker.
3. The first player to align three markers in a row, column, or diagonal wins.
4. If all slots are filled and no player has won, the game declares a draw.

