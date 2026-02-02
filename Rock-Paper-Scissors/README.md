# ✊✋✌️ Rock Paper Scissors

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)

A simple Python implementation of the classic hand game "Rock, Paper, Scissors". Play against the computer and see if you can win!

## ✨ Features

*   **Interactive Input**: Choose your move (Rock, Paper, or Scissors).
*   **Computer Opponent**: The computer makes a random choice.
*   **Game Logic**: Automatically determines the winner based on standard rules:
    *   Rock crushes Scissors.
    *   Scissors cuts Paper.
    *   Paper covers Rock.

## 🛠️ Installation

Make sure you have Python 3 installed. This script uses the standard `random` library.

1.  **Clone the repository** or download the notebook.
2.  **Play the game**.

## 🚀 Usage

Run the `code.ipynb` notebook to start playing.

```bash
# Open code.ipynb in Jupyter Notebook or VS Code
```

**Input Guide:**
*   Type `0` for **Rock** ✊
*   Type `1` for **Paper** ✋
*   Type `2` for **Scissors** ✌️

**Example Interaction:**
```text
What do you choose? Type 0 for Rock, 1 for Paper or 2 for Scissors.
0
You win!
```
*(Assuming Computer chose Scissors)*

## 📂 Code Structure

*   `game()`: The main function containing the game logic.
    *   Captures user input and handles validation.
    *   Generates computer choice (`random.randint(0, 2)`).
    *   Compares choices to print the result (Win, Lose, or Draw).
