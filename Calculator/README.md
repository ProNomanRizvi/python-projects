# 🧮 Simple Calculator

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)

A modular calculator script implemented in Python that supports basic arithmetic as well as advanced operations like power and square.

## ✨ Features

*   **Modular Design**: Functions for each operation (`add`, `sub`, `mul`, `div`, `power`, `square`) for better code organization.
*   **Arithmetic Operations**: Support for Addition (`+`), Subtraction (`-`), Multiplication (`*`), and Division (`/`).
*   **Advanced Math**: Calculate Power (`**`) and Square (`sq`) of numbers.
*   **Robust Error Handling**: Handles valid inputs and prevents crashes from division by zero.
*   **Interactive Interface**: A continuous loop that allows multiple calculations in one session.

## 🛠️ Installation

Ensure you have Python 3 installed. This script uses standard libraries and requires no external dependencies.

1.  **Clone the repository** (if applicable) or download the script.
2.  **Run the calculator**.

## 🚀 Usage

Run the Jupyter Notebook to start the calculator.

```bash
# Open main.ipynb in Jupyter Notebook or VS Code
```

**Example Interaction:**
```text
Welcome to the Calculator

Available operations: +, -, *, /, ** (Power), sq (Square)
Enter the operator: *
Enter the first number: 10
Enter the second number: 5
The product of 10.0 and 5.0 is:  50.0

Do you want to continue? (y/n): n
Goodbye!
```

## 📂 Code Structure

*   **Arithmetic Functions**: Individual functions for `add`, `sub`, `mul`, `div`, `power`, and `square`.
*   **`main()` Function**:
    *   **Input Handling**: prompts user for operator and numbers.
    *   **Logic Branching**: Distinguishes between single-input operations (like square) and double-input operations.
    *   **Loop**: Keeps the program running until the user decides to exit.
