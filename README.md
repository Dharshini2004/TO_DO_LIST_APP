#To-Do List Application

## Introduction
A simple **To-Do List** application developed using Python. It provides functionalities to **add, remove, and delete tasks**. The application uses **Tkinter for GUI** and **SQLite for database storage**.

## Features
- **Add new tasks** dynamically.  
- **Remove a specific task** from the list.  
- **Delete all tasks** at once.  
- **Persistent storage** using SQLite database.  
- **User-friendly interface** built with Tkinter.  

## Technologies Used
- **Python** – Core programming language.  
- **Tkinter** – GUI Library for Python.  
- **SQLite** – Lightweight database for task storage.  

## Application Architecture
The application follows a **layered approach**:  
1. **GUI Layer (Tkinter)** – Handles user interactions.  
2. **Database Layer (SQLite)** – Stores tasks.  
3. **Business Logic (Python)** – Manages task operations.  

## Database Design
The application uses an **SQLite database** with the following table structure:

| Column      | Type     | Description                |
|------------|---------|----------------------------|
| `id`       | INTEGER | Unique task ID (Primary Key) |
| `title`    | TEXT    | Stores task name            |
| `completed` | INTEGER | Task status (0 = pending, 1 = completed) |

## Application Layout
The user interface includes:  
![layout](C:\Users\Lenovo\Desktop\727822TUCS032_python project_TO DO LIST APPLICATION\layout)
- **Add Task** – Input field to add new tasks.  
![add](C:\Users\Lenovo\Desktop\727822TUCS032_python project_TO DO LIST APPLICATION\add)
- **Remove Task** – Option to remove a specific task.  
![remove one](C:\Users\Lenovo\Desktop\727822TUCS032_python project_TO DO LIST APPLICATION\remove one)
- **Delete All** – Clears all tasks from the list.
![remove all](C:\Users\Lenovo\Desktop\727822TUCS032_python project_TO DO LIST APPLICATION\remove all)




## Conclusion
This **To-Do List** application provides an **efficient way to manage tasks**. It utilizes **Python, Tkinter for GUI, and SQLite for database storage**. The project can be extended with **additional features** like **task deadlines, notifications, etc.** A great **beginner-friendly project** to understand **GUI and database integration in Python**.
