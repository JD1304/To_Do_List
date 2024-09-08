# To_Do_List
Web Development Project Using HTML, CSS and JAVASCRIPT
HTML Structure:

The document includes a container (.todo-container) for the to-do list, with an input field to add tasks, a button to submit them, and a list of tasks.
When a user types a task and presses Enter or clicks "Add," the task is added to the list.
Each task in the list can be removed using a "Remove" button.
CSS Styling:

The styling ensures the to-do list is centered, with padding and borders around the container.
Buttons are styled with a blue background that changes to a darker shade on hover.
The input box and buttons are nicely padded and rounded.
AngularJS Functionality:

The app is controlled by AngularJS, specifically within the todoApp module and TodoController.
addTask(): Adds a new task to the task list when the user enters text and presses Enter or clicks the "Add" button. It clears the input field after adding.
removeTask(): Removes a task from the list when the "Remove" button is clicked.
The list of tasks (vm.tasks) is displayed dynamically using ng-repeat, which loops over the tasks and displays them.
JavaScript Functionality:

The AngularJS app is linked to the input field using ng-model to capture the new task, and key press detection (ng-keydown) allows users to add tasks by pressing the Enter key (key code 13).
The app’s logic is encapsulated in a controller (TodoController) where the task list is managed.
Summary:
This is a simple to-do list app where users can add and remove tasks dynamically. The AngularJS framework is used to manage the application's state and handle user interactions. The design is clean, and functionality is straightforward, with key features like adding tasks on Enter key press and removing tasks with a button.
