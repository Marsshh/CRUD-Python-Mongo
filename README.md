# Movie CRUD

This is a CRUD (Create, Read, Update, Delete) for managing movies using Python with FastAPI and MongoDB.

## Requirements

- Python 3.x
- MongoDB
- Python Packages: `fastapi`, `pymongo`

## Project Structure

- `db/`: Folder containing the MongoDB client and database configuration.
- `model/`: Folder containing the data model definition.
- `schema/`: Folder containing the data schemas.
- `main.py`: Main file containing the application logic.

## Functionality

1. **Create a movie**: 
    - To add a new movie, use the `insert_film` function passing the movie data as a parameter. This will insert the data into the MongoDB database and return the ID of the newly created movie.

2. **Get a movie by ID**:
    - Using the `get_film` function, you can retrieve a specific movie by providing its ID as a parameter. This will retrieve the movie data from the database and return it as a JSON object.

3. **Update a movie**:
    - To update an existing movie, use the `update_film` function, passing the ID of the movie to update and the new movie data. This will update the data in the database and return the updated movie.

4. **Delete a movie**:
    - Using the `delete_film` function, you can delete a movie by providing its ID as a parameter. This will delete the movie from the database.

5. **List all movies**:
    - The `list_films` function is responsible for listing all movies stored in the database. It returns a list of all movies in JSON format.



