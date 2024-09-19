<h1 align="center">Task 04: User and Task Management</h1>

**Objective**: Integrate the frontend with the backend to manage users and their tasks.

## Instructions

1. **Use Express Server**:
   - Use the Express server created in Task 02.
   - Add endpoints for managing users and tasks.

2. **Fetch and Display**:
   - Create a React component to fetch users and their associated tasks.
     - Use `useState` wherever necessary
     - Use `useEffect` wherever necessary
   - Display the list of users with their tasks in a user-friendly format.
     - Display their name, and for each user, list their associated tasks.
   - Implement error handling for failed API calls.
     - Display error messages.

3. **Task 02 Server Side**:
   - Implement CRUD operations for users and tasks in the frontend.
   - Implement the following routes for managing users and tasks:
     - `GET /users`: Fetch a list of all users.
     - `POST /users`: Create a new user.
     - `PUT /users/:id`: Modify an existing user's details.
     - `DELETE /users/:id`: Remove a user.
     - `GET /users/:id/tasks`: Retrieve the tasks assigned to a specific user.
     - `POST /users/:id/tasks`: Add a new task for a particular user.
     - `PUT /users/:id/tasks/:taskId`: Edit an existing task for a specific user.
     - `DELETE /users/:id/tasks/:taskId`: Delete a task assigned to a specific user.
   - Store user and task data temporarily using in-memory storage (arrays).

### Setup Instructions

1. Follow the setup instructions for both the frontend and backend.
2. Ensure both are running and properly integrated.

### Evaluation Criteria

- Correct integration of frontend and backend.
- Proper handling of asynchronous operations and API calls.
- Code organization and error handling.