# Methodology

## Project Overview
- The project, Tidy Track, is a simple website that helps users organize their tasks. It allows users to add, edit, delete, and search tasks. The goal is to make task management easy and accessible.

## Core Features
### Task Input
- Users can type a task name, description, and due date in the input fields. The system checks if the task name and description are filled in before adding the task. This prevents empty tasks.

### Task Management
#### Add Task
-Users can add a new task. Each task is saved with a name, description, and due date.
#### Edit Task
-Users can change a task. When editing, the task details appear in the input fields so they can be updated.
#### Delete Task
-Users can remove a task from the list.

These features allow users to fully manage their tasks.
#### Search Feature
-Users can search for tasks using the search bar. The system shows only the tasks that match the typed word. If no task is found, a message will appear.
#### Task Display
-All tasks are shown on the screen. Each task includes: Task name, Description, Due date, and Edit and delete buttons. The display updates automatically whenever changes are made.
#### Local Storage
-The system uses the browser’s local storage to save tasks. This means: Tasks stay even after refreshing the page, and no internet or database is needed


## Technologies Used
#### HTML 
– Used to create the structure (inputs, buttons, layout)
#### CSS 
– Used to design the look of the app
#### JavaScript 
– Used to make the app work (adding, editing, deleting, searching tasks)

## System Flow
#### Adding or Updating a Task
- User enters task details
- System checks the input
- Task is added or updated
- Task is saved
- Task list is refreshed
#### Searching Tasks
- User types in search bar
- System checks all tasks
- Matching tasks are shown
- If none match, a message is displayed
#### Design Decisions
- Local Storage was used because it is simple and does not need internet
- Single Page Design makes the app faster and easier to use
- Simple Layout helps users understand the app quickly

## Limitations
- Tasks are only saved on one device
- Data may be lost if browser storage is cleared
- Search only works for task names
- Future Improvements
- Add checkbox for completed tasks
- Sort tasks by date
- Add priority levels
- Improve design and layout
- Ethical Consideration

## Conclusion
- Tidy Track is a simple and useful task manager. It shows how basic web tools can be used to create a working and helpful application.
