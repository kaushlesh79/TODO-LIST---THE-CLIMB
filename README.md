# To-Do List (THE CLIMB) App with React and Redux Toolkit

A simple and efficient To-Do List application built with React and Redux Toolkit. This app allows you to add tasks, view tasks based on their completion status (Active, Complete, All Tasks), and manage them (mark tasks as complete, delete tasks).

## Features
- **Three pages**: Active, Complete, and All Tasks.
- **Add task interface**: Add tasks with a simple input form.
- **Task cards**: Mark tasks as complete or delete them.
- **State management**: Uses Redux Toolkit to manage the state of tasks.

## Tech Stack
- **React**: A JavaScript library for building user interfaces.
- **Redux Toolkit**: A state management library to manage tasks and their states (active/completed).
- **CSS/SCSS**: For styling the application.
- **React Router**: For navigation between pages.

## Application Pages

### 1. **Active Tasks** Page
- Displays all tasks that are currently active (i.e., tasks that are not marked as complete).
- Each task can be marked as complete or deleted.

### 2. **Complete Tasks** Page
- Displays all tasks that have been marked as complete.
- Tasks are no longer editable once completed, but can still be deleted.

### 3. **All Tasks** Page
- Displays all tasks, regardless of their completion status.
- Tasks can be filtered by their current state (Active/Complete).

## Components

### 1. **AddTaskForm**
- **Description**: A form where users can add a new task.
- **Functionality**: 
  - An input field to enter the task description.
  - A submit button to add the task to the state.
  
### 2. **TaskCard**
- **Description**: A card for each individual task.
- **Functionality**:
  - A checkbox to mark a task as complete.
  - A button to delete the task.

### 3. **TaskList**
- **Description**: A component that lists tasks in a given state (Active or Complete).
- **Functionality**: 
  - Displays tasks based on their completion status.
  - Allows for task actions like mark as complete and remove.

## How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/kaushlesh79/TODO-LIST---THE-CLIMB
cd todo-list-redux
```

### 2 . Install the npm
```bash
 cd todo-list-redux
 npm install
```
### 3  Adding Redux toolkit
 
