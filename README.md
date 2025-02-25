# Tic-Tac 


# Tic-Tac-Toe Game

## Description
This is a simple Tic-Tac-Toe game implemented using Python and Tkinter. It is a two-player game where players take turns marking a 3x3 grid with 'X' or 'O'. The game checks for a winner or a tie and provides visual feedback for the winning combination.

## Features
- Two-player functionality
- Graphical user interface (GUI) using Tkinter
- Winner detection with green-highlighted winning tiles
- Displays turn information
- Detects a tie if all cells are filled without a winner
- Displays message boxes for game results

## Installation
### Prerequisites
Ensure you have Python installed on your system. This game requires Tkinter, which is included with standard Python installations.

### Steps
1. Clone or download this repository.
2. Navigate to the folder containing the script.
3. Run the script using Python:
   ```sh
   python tic_tac_toe.py
   ```

## How to Play
1. The game starts with Player X.
2. Click on an empty button to place your mark ('X' or 'O').
3. The game automatically switches turns after each move.
4. The first player to get three of their marks in a row, column, or diagonal wins.
5. If all spaces are filled and no player has won, the game declares a tie.
6. The game window will close automatically when a winner is found or when there is a tie.

## Code Overview
- `button_click(index)`: Handles button clicks and updates the board.
- `check_winner()`: Checks for a winner or a tie.
- `toggle_player()`: Switches turns between players.
- `root.mainloop()`: Runs the game loop.

## Future Enhancements
- Add an option to restart the game without closing the window.
- Implement an AI opponent for single-player mode.
- Improve UI with better aesthetics.

## License
This project is free to use for educational purposes.

