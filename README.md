# JSL02 Project Brief: Task Input and Status Validation System

## Descriptions
This project is a JavaScript-based task entry system that collects and validates user input for two tasks. The program prompts the user to enter a task title, task description, and task status for each task. To ensure consistency, the system automatically converts status inputs to lowercase and validates that the status is only one of the following options: “todo”, “doing”, or “done”. If the user enters an invalid status, the program displays an alert and repeatedly prompts the user until a valid status is provided.
 
## Technologies 

- HTML
- CSS
- Javascript

## Key Features

Ensure the JavaScript file is correctly linked to the HTML document.
Prompt the user to enter details (title, description, status) for two separate tasks and store them in variables.
Convert all status inputs to lowercase automatically for consistency.
Validate the status input to allow only "todo", "doing", or "done" and repeatedly prompt the user until a valid status is entered.
Display the title and status of completed tasks (status: "done") in the console.
If no tasks are marked as "done", show a motivational message in the console: "No tasks completed, let's get to work!".
 

Prompt the user to 
![Description image](./explainer-images/Description%20prompt.png)

  

  ![title prompt](./explainer-images/title%20prompt.png)

**Invalid status**

- If the user enters a status other than `todo`, `doing` or `done`, the program must alert the user of this and return to prompting them to enter a status.

  ![invalid status](./explainer-images/invalid%20status.png)

**Console log**

- When there is a completed task:

  ![invalid status](./explainer-images/completed%20task%20log.png)

- When there are no completed tasks:

  ![invalid status](./explainer-images/no%20completed%20tasks%20log.png)
