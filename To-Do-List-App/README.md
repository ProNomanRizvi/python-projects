# 📝 To-Do List App

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)

A persistent task manager with JSON-based data storage and an interactive menu-driven interface.

## ✨ Features

*   **Data Persistence**: Tasks are saved to `tasks.json` and survive between sessions.
*   **CRUD Operations**: Add, Complete, and Delete tasks.
*   **Interactive Menu**: Simple text-based interface with numbered options.
*   **Dynamic Display**: Refreshes the task list after each action using `clear_output`.

## 🛠️ Installation

Ensure you have Python 3 and Jupyter Notebook installed. This script uses the `json` and `os` standard libraries.

1.  **Clone the repository** (if applicable) or download the files.
2.  **Run the notebook**.

## 🚀 Usage

Run the `todo.ipynb` notebook to start the application.

```bash
# Open todo.ipynb in Jupyter Notebook or VS Code
```

**Menu Options:**
| Key | Action |
| :--- | :--- |
| `1` | Add a new task |
| `2` | Refresh the list |
| `3` | Mark a task as complete |
| `4` | Delete a task |
| `5` | Exit the application |

**Example Interaction:**
```text
--- YOUR TO-DO LIST ---
1. [x] Break Fast
2. [ ] Lunch
-----------------------

Options: [1] Add  [2] Refresh  [3] Complete  [4] Delete  [5] Exit
cmd> 1
Description: Go for a walk
✓ Added: 'Go For A Walk'
```

## 📂 Code Structure

*   **Persistence Layer**: `load_tasks()`, `save_tasks()` handle JSON file I/O.
*   **Core Actions**: `add_task()`, `complete_task()`, `delete_task()` modify the list.
*   **Display Logic**: `view_tasks()` formats and prints the task list.
*   **Main Loop**: `main()` runs the interactive menu.
