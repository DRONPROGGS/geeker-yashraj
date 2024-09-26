Code Breakdown
HTML
The table element is used to display the tasks with a thead for the column header ("Task Name") and a tbody where tasks will be appended.
The form contains an input field (#task-input) and a submit button to add new tasks.
JavaScript
JavaScript listens for the submit event on the form. It prevents the default behavior (which would refresh the page) and captures the task entered by the user.
A new row (<tr>) is created and appended to the table's <tbody> (#tasks) with the task name in a <td> cell.
Event Flow
Input a Task: The user types a task in the input field and clicks "Add Task."
Append the Task: The task is added to the table as a new row when the form is submitted.
No Page Refresh: JavaScript ensures the page does not refresh, providing a seamless user experience.
How to Run the App
Clone or Download the repository containing the index.html file.
Open the HTML file: Simply open the index.html file in any modern web browser (Chrome, Firefox, etc.).
Start Adding Tasks: Use the input box to type in a task and click "Add Task." The task will immediately appear in the table below.
Example Usage
Open the webpage in a browser.
Type a task into the input field (e.g., "Buy groceries").
Click the "Add Task" button or press Enter.
The task "Buy groceries" will appear in the task list.
Future Enhancements
Task Deletion: Add a "Delete" button for each task to allow users to remove tasks.
Task Editing: Add functionality to edit tasks once they are added.
Persistent Storage: Store tasks in the browser's local storage so that they remain even after the page is refreshed.
Dependencies
This app does not use any external libraries or frameworks. It runs purely on HTML, JavaScript, and optional CSS.

License
This project is open-source and can be freely modified or distributed.
