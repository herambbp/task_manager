# Task Manager

This is a simple task manager script that allows you to add tasks, delete tasks, and view tasks.

## Requirements

- Python 3.x

## Usage

1. Download the `task_manager.py` file.
2. Open a terminal or command prompt.
3. Navigate to the directory where the `task_manager.py` file is located.
4. Run the following command:

```
python task_manager.py
```

## Functionality

The task manager provides the following options:

- **Add Task (A):** Allows you to add a new task by providing a task name and description.
- **Delete Task (D):** Allows you to delete a task by specifying its ID.
- **View Tasks (V):** Displays a list of all tasks with their respective IDs, titles, and descriptions.
- **Quit (Q):** Exits the task manager.

## Example Usage

```
========== Task Manager ==========
A: Add Task
D: Delete Task
V: View Tasks
Q: Quit
Enter your choice: A

Add Task
Enter the task name: Finish project
Enter description for 'Finish project': Complete all remaining tasks and submit the project.
Task added successfully!

Press Enter to continue...
```

```
========== Task Manager ==========
A: Add Task
D: Delete Task
V: View Tasks
Q: Quit
Enter your choice: V

View Tasks
Task ID: 1
Title: Finish project
Description: Complete all remaining tasks and submit the project.

Press Enter to continue...
```

```
========== Task Manager ==========
A: Add Task
D: Delete Task
V: View Tasks
Q: Quit
Enter your choice: D

Delete Task
View Tasks
Task ID: 1
Title: Finish project
Description: Complete all remaining tasks and submit the project.

Enter the task ID you want to delete: 1
Task deleted successfully!

Press Enter to continue...
```

```
========== Task Manager ==========
A: Add Task
D: Delete Task
V: View Tasks
Q: Quit
Enter your choice: Q
```

## Note

This task manager script uses the `os` module to clear the screen after each operation. However, the clearing of the screen might not work on all operating systems. If you encounter any issues with the `clear_screen()` function, you can remove the `clear_screen()` function calls in the `home_screen()` function or replace them with an appropriate clearing mechanism for your operating system.
