# Two Player Chess in Python with Pygame:
This repository contains a two-player chess game implemented in Python using the Pygame library. The project demonstrates how to set up a basic chess game with a graphical user interface (GUI) where two players can take turns to play against each other.

# Features
Classic Chess Gameplay: A standard chessboard with 64 squares, supporting two players, each controlling white and black pieces.
Graphical Interface: The chess pieces and board are displayed using Pygame, allowing intuitive visual gameplay.
Turn-Based System: The game alternates turns between white and black, with clear visual cues to indicate which player's move it is.
Check and Checkmate Detection: Highlights the king if it is in check. The game ends when one player wins by checkmate or forfeits.
Move Validation: Each piece follows its correct movement rules (e.g., knights moving in an "L" shape, rooks moving in straight lines, etc.).
Captured Pieces Display: Captured pieces are displayed on the side of the board to keep track of each player's taken pieces.

# How to Run the Game
Ensure Python is installed on your system. You can download Python here.
Install Pygame by running:
pip install pygame

Clone this repository:
git clone https://github.com/yourusername/two-player-chess-pygame.git
cd two-player-chess-pygame

Run the game: python chess_game.py

How to Play
Game Start: The game starts with white's turn. Players alternate turns moving their respective pieces.

# Move Selection:
Click on a piece to select it.
Available valid moves will be highlighted.
Click on a valid square to move the piece.
End Conditions: The game ends when one player wins by checkmate, or if a player chooses to forfeit.
Forfeit: A player can forfeit the game by clicking the "FORFEIT" button at any time during their turn.
Files and Directories
chess_game.py: Main Python file containing the game logic.
assets/: Folder containing images of the chess pieces.
black_queen.png, black_king.png, white_rook.png, etc.
# Key Functions
draw_board(): Draws the chessboard and the status area for player turns.
draw_pieces(): Places the pieces on their respective starting positions.
check_options(): Calculates the valid moves for all pieces on the board.
check_king(), check_rook(), check_pawn(): Individual functions to check valid moves for specific pieces.
draw_valid(): Highlights valid moves for the currently selected piece.
draw_check(): Highlights the king when it's in check.
draw_captured(): Displays the captured pieces on the side of the screen.
draw_game_over(): Displays the game-over screen when one player wins.
# Future Enhancements
Add AI to allow players to play against the computer.
Add more advanced move validation like castling and en passant.
Enhance visuals and user interface with animations for moves and captures.
Feel free to contribute to the project or suggest improvements!

License
This project is licensed under the MIT License. See the LICENSE file for detail

