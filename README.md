# To-Do List App

This is a simple React To-Do List application that allows users to add, remove, and mark tasks as completed. It also supports filtering and sorting tasks, with data persistence via `localStorage`.

## Features

- Add new tasks
- Remove tasks
- Mark tasks as completed
- Filter tasks (all, completed, incomplete)
- Sort tasks (default, ascending, descending)
- Persist tasks using `localStorage`

## Installation

To get started, clone the repository and install the dependencies:

```bash
git clone https://github.com/your-username/todo-list-app.git
cd todo-list-app
npm install
```

## Testing Guidance

- Add Task: Enter a task in the input field and click "Add Task". The task should appear in the list below.
- Remove Task: Click the "Remove" button next to a task. The task should be removed from the list.
- Complete Task: Click the "Complete" button next to a task. The task should be marked as completed (strikethrough text).
- Filter Tasks: Use the filter dropdown to display all tasks, only completed tasks, or only incomplete tasks.
- Sort Tasks: Use the sort dropdown to sort tasks in default order, ascending order, or descending order.
