To-Do List App
This is a simple CRUD (Create, Read, Update, and Delete) to-do list app built using HTML, CSS, and JavaScript. The app allows users to create, read, update, and delete tasks.
Features
•	Add tasks: Users can add tasks to the list by entering the task in the input field and clicking the “Add” button or pressing the enter key on their keyboard.
•	Read tasks: Users can view the list of tasks below the input field.
•	Update tasks: Users can update individual tasks by editing the value of the input field for that task.
•	Delete tasks: Users can delete individual tasks by clicking the “Delete” button next to the task. Users can also clear all tasks from the list by clicking the “Clear” button at the bottom of the page.
Usage
To use the app, simply open the index.html file in a web browser. Enter a task in the input field and click the “Add” button or press the enter key on your keyboard to add it to the list. To update a task, edit the value of the input field for that task. To delete a task, click the “Delete” button next to it. To clear all tasks from the list, click the “Clear” button at the bottom of the page.

The JavaScript code in the to-do list app performs several functions to enable the app’s CRUD functionality:
1.	Add tasks: The addTask function is called when the user clicks the “Add” button or presses the enter key on their keyboard. This function creates a new li element with the class “task” and appends it to the ul element with the id “taskList”. The new li element contains an input element of type “text” with its value set to the value of the input element with the id “taskInput”. This allows the user to edit the task later. The new li element also contains a button element labeled “Delete” that, when clicked, calls an anonymous function that removes the li element from its parent ul element. This allows the user to delete individual tasks.
2.	Clear tasks: The clearList function is called when the user clicks the “Clear” button. This function removes all child elements from the ul element with the id “taskList”, effectively clearing all tasks from the list.
3.	Add task on enter key press: An event listener is added to the input element with the id “taskInput” that listens for the keyup event. When this event is triggered, an anonymous function is called that checks if the key that was released was the enter key. If it was, the addTask function is called to add a new task to the list.
