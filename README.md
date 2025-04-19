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

## 👥 Switching Between AI and Human Players

In `ChessMain.py`, you can change the `playerOne` and `playerTwo` variables to control who plays as white and black:

```python
playerOne = True  # If True, human plays white. If False, AI plays white.
playerTwo = False # If True, human plays black. If False, AI plays black.
```

Examples:
- Human vs AI (White): `playerOne = True`, `playerTwo = False`
- AI vs Human (Black): `playerOne = False`, `playerTwo = True`
- Human vs Human: `playerOne = True`, `playerTwo = True`
- AI vs AI: `playerOne = False`, `playerTwo = False`

## ♙ Pawn Promotion

When a pawn reaches the last rank (the 8th for white, 1st for black), you'll be prompted to enter the piece you'd like to promote to:

```
Promote to Q, R, B, or N:
```

Just type:
- `Q` for Queen
- `R` for Rook
- `B` for Bishop
- `N` for Knight

⚠️ Note: The promotion currently happens via console input. Make sure your terminal is active when the prompt appears.

## 🏁 Features

- Castling (both sides)
- En Passant
- Pawn Promotion
- Check, Checkmate, and Stalemate detection
- Move logging and animated moves
- Highlighting valid squares

## 📸 Screenshot

<img width="765" alt="Image" src="https://github.com/user-attachments/assets/69bccb38-3d4d-4fa9-92d5-49187f636c07" />

## 🧩 Future Improvements

- Add piece-square tables for positional evaluation
- Improve UI with move suggestions or themes
- Add a proper pawn promotion GUI
- Support for time control and PGN export

## 📜 License

This project is open-source and available under the MIT License.

---

Enjoy your game of chess! ♟️
