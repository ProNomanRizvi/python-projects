# 🔐 Random Password Generator

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)

A secure, customizable random password generator written in Python. This utility allows you to generate strong passwords with various complexity options and automatically copies the result to your clipboard.

## ✨ Features

*   **Customizable Length**: Choose how many characters you want in your password.
*   **Security Toggles**: Option to include:
    *   Uppercase Letters (A-Z)
    *   Numbers (0-9)
    *   Symbols (!@#$...)
*   **Auto-Copy**: The generated password is automatically copied to your clipboard using `pyperclip` for immediate use.

## 🛠️ Installation

You need Python 3 installed. This tool relies on the `pyperclip` library for clipboard operations.

1.  **Clone the repository** (if applicable) or download the script.
2.  **Install requirements**:

```bash
pip install pyperclip
```

## 🚀 Usage

You can run the script (or Jupyter Notebook) directly.

```bash
python password_gen.py
# or open password_gen.ipynb in Jupyter
```

**Example Interaction:**
```text
Password Generator
Enter password length (e.g., 8): 12
Include symbols (y/n): y
Include numbers (y/n): y
Include uppercase letters (y/n): y
Generated Password: 8£n2@K#m9P1!
Password copied to clipboard!
```

## 📂 Code Structure

*   `gen_pwd(length, ...)`: Core function that builds the character pool based on user flags, randomly selects characters, shuffles them for entropy, and returns the final string.
*   `main()`: Handles user input validation and interaction.
