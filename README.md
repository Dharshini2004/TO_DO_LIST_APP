# To-Do List Application

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
![layout](https://github.com/user-attachments/assets/d02907f4-43d0-4629-b29b-1d2b1c7ac23b)

- **Add Task** – Input field to add new tasks.
- ![add](https://github.com/user-attachments/assets/069d5f9a-1b45-4d52-be30-8f707889aa65)
- **Remove Task** – Option to remove a specific task.  
![remove one](https://github.com/user-attachments/assets/0523078d-df65-4f13-9857-171648bf4488)
- **Delete All** – Clears all tasks from the list.
![remove all](https://github.com/user-attachments/assets/eab4e974-b539-42a6-90cb-4bf6bf722dc7)





## Conclusion
This **To-Do List** application provides an **efficient way to manage tasks**. It utilizes **Python, Tkinter for GUI, and SQLite for database storage**. The project can be extended with **additional features** like **task deadlines, notifications, etc.** A great **beginner-friendly project** to understand **GUI and database integration in Python**.
