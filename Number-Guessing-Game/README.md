# 🔢 Number Guessing Game

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)

A classic number guessing game where the player attempts to guess a randomly generated number between 1 and 100 within a limited number of attempts.

## ✨ Features

*   **Random Number Generation**: The game generates a new random number for every session.
*   **Feedback Loop**: Provides hints if your guess is "Too High" or "Too Low".
*   **Attempt Limiter**: You have a maximum of 5 attempts to guess the correct number.

## 🛠️ Installation

Ensure you have Python 3 installed. No external libraries are required as this uses the built-in `random` module.

1.  **Clone the repository** (if applicable) or download the script.
2.  **Run the game**.

## 🚀 Usage

You can run the Jupyter Notebook to play the game interactively.

```bash
# Open game.ipynb in Jupyter Notebook or VS Code
```

**Example Interaction:**
```text
Guess the number between 1 and 100: 50
Too low. Try again.
Guess the number between 1 and 100: 75
Too high. Try again.
Guess the number between 1 and 100: 60
Congratulations! You guessed the number in 3 attempts.
```

## 📂 Code Structure

*   **Initialization**: Sets the target number (`random.randint(1, 101)`) and resets attempts.
*   **Game Loop**:
    *   Accepts user input.
    *   Compares input with the target number.
    *   Increments attempt counter.
    *   Checks for win/loss conditions (correct guess or max attempts reached).
