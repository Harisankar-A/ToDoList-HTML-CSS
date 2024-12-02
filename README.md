# To-Do List Application

This repository contains a simple To-Do List application that allows users to add, mark as complete, and clear items. It is designed to be minimalistic, with clear buttons for managing the list, including options to save the list and clear completed tasks.

## Features

### To-Do List Section
- **Input Field**: Allows users to enter a new task to be added to the list.
- **Add Button**: Adds the new task to the list when clicked. (Currently without functionality)
- **Task Items**: Tasks are displayed in an ordered list, and items marked as completed have a line-through style.
- **Double-click to Mark Complete**: Users can double-click on a task to mark it as complete, which strikes through the text.

### Clear and Empty Options
- **Clear Completed**: Removes tasks that are marked as completed (currently without functionality).
- **Empty List**: Clears all tasks from the list (currently without functionality).
- **Save List**: Saves the current list (currently without functionality).

### Styling
- The application uses simple CSS for layout and design, with rounded corners, a centered container, and contrasting colors for tasks and buttons.
  
## How It Works

### HTML Structure:
- **To-Do List**: The list is wrapped in an ordered list (`<ol>`) where each task is an `<li>` element.
- **Buttons**: There are buttons for adding tasks, clearing completed tasks, emptying the list, and saving the list.
- **Input Field**: A text input is provided for adding new tasks to the list.

### CSS Styling:
- **Container**: The `.one` class centers the content and adds a light green background with rounded corners.
- **Button Styling**: Buttons are styled with colors to visually differentiate them for specific actions like adding tasks, clearing completed tasks, etc.
- **Task Item Styling**: Completed tasks are styled with a line-through (`text-decoration: line-through`) and a different background color.
  
## Technologies Used

- **HTML**: Used for structuring the to-do list, buttons, and input fields.
- **CSS**: Custom styles for layout, button colors, task completion, and responsive adjustments.
  
## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Harisankar-A-18/ToDoList-HTML-CSS
    ```

2. Navigate to the project directory

3. Open the `index.html` file in your preferred web browser to view the application.

## Usage

- **Add Task**: Enter a task in the input field and click the "Add" button.
- **Mark Task as Complete**: Double-click on any task to mark it as completed (it will appear with a line through it).
- **Clear Completed**: The "Clear Completed" button is intended to remove tasks marked as completed.
- **Empty List**: The "Empty List" button will remove all tasks from the list.
- **Save List**: The "Save List" button can be used to save the current state of the list (requires implementation).

## Screenshot

### To-Do List Application
![image](https://github.com/user-attachments/assets/084adec0-6a22-4384-b532-4d2f798a4c0f)


## Limitations

- **Functionality**: Currently, the buttons (Add, Clear Completed, Empty List, Save List) do not have any implemented functionality. JavaScript can be added to make them work.
- **Interactivity**: Double-click to mark tasks as complete is visual but does not have full interactivity without JavaScript.
- **Save/Load**: The "Save List" feature is not yet implemented.

