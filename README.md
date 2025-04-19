# 🧠 Python Chess Engine with AI

This is a Python-based chess game featuring a graphical interface built using `pygame`, and an AI opponent using the Minimax algorithm with Alpha-Beta pruning for move selection.

## 📁 Project Structure

- `ChessMain.py`: Main driver file. Handles user input, drawing the board, and integrating AI moves.
- `ChessEngine.py`: Manages the state of the chess game, including move validation, check/checkmate logic, castling, en passant, and more.
- `SmartMoveFinder.py`: Implements the AI for the computer player. Uses Minimax and Alpha-Beta pruning to evaluate the best move based on material.
- `images/`: Folder containing `.png` images of chess pieces used in the GUI.

## 🚀 How to Run

1. Install dependencies:
   ```bash
   pip install pygame
   ```

2. Ensure you have a folder named `images/` in the root directory containing images of chess pieces named like `wK.png`, `bp.png`, etc.

3. Run the game:
   ```bash
   python ChessMain.py
   ```

## 🧠 AI Features

- **Random move** (fallback)
- **Material-based evaluation**
- **Minimax with Alpha-Beta Pruning**
- Search Depth: Configurable (default is 4)

## 🎮 Controls

- Click on a piece and then a square to move.
- Press `Z` to undo a move.
- Press `R` to reset the game.
- Set `playerOne` and `playerTwo` in `ChessMain.py` to toggle human vs. AI.

## 🏁 Features

- Castling (both sides)
- En Passant
- Pawn Promotion
- Check, Checkmate, and Stalemate detection
- Move logging and animated moves
- Highlighting valid squares

## 📸 Screenshot

*(Add your screenshot here)*

## 🧩 Future Improvements

- Add piece-square tables for positional evaluation
- Improve UI with move suggestions or themes
- Add a proper pawn promotion GUI
- Support for time control and PGN export

## 📜 License

This project is open-source and available under the MIT License.

---

Enjoy your game of chess! ♟️
