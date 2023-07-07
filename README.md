# assiPlatform
A Management Platform

A task management system using React, MongoDB, and Postman. The project aimed to provide functionality for creating tasks, marking them as completed, and storing completed tasks in a separate collection.

Started by setting up the backend using Node.js and Express. We utilized the MongoDB database to store the task data. The tasks were defined using a TaskSchema and managed using the Task model. Created API endpoints for creating tasks, retrieving all tasks, and deleting tasks by their IDs. Additionally, I introduced a new model called CompletedTaskSchema to store completed tasks.

On the frontend, I developed a user interface using React. I created a form to add new tasks and a task list to display the existing tasks. Each task had properties such as client name, contact, address, equipment type, serial number, and model. Implemented the functionality to mark tasks as completed by using checkboxes and a handleTaskComplete function. When a task was marked as completed, it was removed from the task list and added to the completedTasks array.

Used Axios to make HTTP requests from the frontend to the backend API endpoints. Utilized the GET method to fetch tasks from the server and display them in the task list. The POST method was used to add new tasks to the database. The DELETE method was used to delete tasks by their IDs, and also stored the deleted tasks in the CompletedTask collection by creating a new CompletedTask instance and saving it.

To test the API endpoints, I used Postman. I made requests to the server's endpoints to create tasks, retrieve all tasks, and delete tasks by their IDs. I also tested the functionality of marking tasks as completed using Postman.

Overall, the project provided a practical example of integrating React with MongoDB and utilizing Postman for API testing. It showcased how to build a task management system with features such as task creation, completion, and storage of completed tasks.
