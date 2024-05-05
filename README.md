# Todos-Fast-API

This project is a Todo management system built with FastAPI, a modern, fast (high-performance), web framework for building APIs with Python 3.7+.

### Features

- **User Authentication**: Users can register and log in to manage their todos.
- **Authorization**: Admin users have the privilege to delete any todo or user.
- **Todo Operations**:
  - **Create**: Users can add new todos.
  - **Update**: Users can update existing todos.
  - **Delete**: Users can delete their own todos, and admin users can delete any todo.
  - **Retrieve**: Users can get a list of all their todos.

### Technologies Used

- **FastAPI**: A modern, fast (high-performance), web framework for building APIs with Python 3.7+.
- **Pydantic**: Data validation and settings management using Python type annotations.
- **SQLAlchemy**: SQL toolkit and Object-Relational Mapping (ORM) for Python.
- **JWT (JSON Web Tokens)**: For user authentication and authorization.
- **SQLite**: Lightweight, serverless database engine.

### Setup Instructions

First Step which you need to do to run this Todos-Fast-API is to clone the repository.

#### Clone the repository

After cloning the repository navigate to the directory and create a virtual environment for your project.

- **Using the following command**:
  `python3 -m venv myenv`

Once the Virtual Environment is created, Activate the Environment with following command.

- **For Mac Users**:
  `source myenv/bin/activate`

- **For windows Users**:
  `myenv\Scripts\activate`

Once the Virtual Environment is Activated, The first thing which you need to do is install all the dependencies of requirements.txt file.

- To install requirements.txt file. Run following command in your terminal.

  `python3 install -r requirements.txt`

Once all the dependencies are installed.

#### Check the following details:

- [ ] Configure all your Database details in `database.py` file.
- [ ] Change the secret key with your secret key in `routers/auth.py` file.

Once you have completed these steps, we are good to move forward.

#### Run the server locally and test the API's

- To Run server locally in your machine. Run the following command.

  `uvicorn main:app --reload`

This command will run the Todos-Fast-API at `localhost` and on port `8000`

Access the API documentation at `http://localhost:8000/docs` and test the endpoints using the Swagger UI.
