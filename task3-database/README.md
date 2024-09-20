<h1 align="center">Task 03: Movie Collection</h1>

**Objective**: Design a MongoDB schema and implement database operations for managing a movie collection.

## Instructions

1. **Design the Schema**:

   - Create a schema for a `Movie` collection with the following fields:
     - `title`: The name of the movie.
     - `description`: The description of the movie.
     - `director`: The director of the movie.
     - `year`: The release year of the movie.
     - `genre`: The genre of the movie.

2. **Connect to MongoDB**:

   - Develop a script to establish a connection to a MongoDB database.

3. **Database Functionality**:
   - Read Operations:
     - Retrieve a movie.
     - Retrieve all movies.
   - Create Operations:
     - Insert a new movie.
   - Update Operations:
     - Update a movie by its title.
   - Create Operations:
     - Remove a movie by its title.

### Setup Instructions

1. Utilize the cloud-based MongoDB Atlas.
2. Navigate to the `task3-database` directory.
3. Execute the script: `node src/database.js`.

### Evaluation Criteria

- Accurate schema design following best practices.
- Proper implementation of MongoDB operations (create, read, update, delete).
- Clean, organized code with appropriate error handling.
