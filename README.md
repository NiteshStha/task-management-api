# Description

  A Task management API that lets you sign up, sign in, and create tasks in a postgres database and perform CRUD operations.
  The API is deploy in Heroku.

## Endpoints

  - sign up (POST) -> [https://task-management-nest.herokuapp.com/auth/signup] -> Provide a username and password in the request body.
  - sign in (POST) -> [https://task-management-nest.herokuapp.com/auth/signin] -> Provide a username and password in the request body. Returns a Token.
  - get tasks (GET) -> [https://task-management-nest.herokuapp.com/tasks] -> Returns an array of user's tasks.
  - get task (GET) -> [https://task-management-nest.herokuapp.com/tasks/:id] -> Returns a task. Should add task id in the params.
  - create task (POST) -> [https://task-management-nest.herokuapp.com/tasks] -> Creates a new task for the user.
  - update task (PATCH) -> [https://task-management-nest.herokuapp.com/tasks/:id/status] -> Updates the task. Must provide status in the request body.
  - delete task (DELETE) -> [https://task-management-nest.herokuapp.com/tasks/:id] -> Deletes the task.
