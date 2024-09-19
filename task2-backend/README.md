<h1 align="center">Task 02: User and Task Management</h1>

**Objective**: Build an Express server that supports CRUD functionality for managing users and their associated tasks.

## Instructions

1. **Set Up an Express Server**:

   - Initialize an Express application
   - Install necessary packages/libraries

2. **Create CRUD Endpoints**:

   - Implement the following routes for managing users and tasks:
     - `GET /users`: Fetch a list of all users.
     - `POST /users`: Create a new user.
     - `PUT /users/:id`: Modify an existing user's details.
     - `DELETE /users/:id`: Remove a user.
     - `GET /users/:id/tasks`: Retrieve the tasks assigned to a specific user.
     - `POST /users/:id/tasks`: Add a new task for a particular user.
     - `PUT /users/:id/tasks/:taskId`: Edit an existing task for a specific user.
     - `DELETE /users/:id/tasks/:taskId`: Delete a task assigned to a specific user.
   - Store user and task data temporarily using in-memory storage (e.g., arrays).

3. **Error Handling**:
   - Ensure comprehensive error handling for each endpoint to account for invalid inputs or operations.

### Setup Instructions

1. Navigate to the `task2-backend` directory.
2. Install dependencies by running: `npm install`.
3. Start the Express server: `node src/server.js`.

### Evaluation Criteria

- Accurate implementation of CRUD functionality.
- Effective error handling throughout the application.
- Clear and well-organized code structure.
