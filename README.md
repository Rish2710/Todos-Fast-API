# Todos-Fast-API

First Step which you need to do to run this Todos-Fast-API is to clone the repository.

#### Clone the repository

After cloning the repository navigate to the directory and create a virtual environment for your project.

Using the following command

` python3 -m venv myenv`

Once the Virtual Environment is created, Activate the Environment with following command.

- For Mac Users

  `source myenv/bin/activate`

- For windows Users

  `myenv\Scripts\activate`

Once the Virtual Environment is Activated, The first thing which you need to do is install all the dependencies of requirements.txt file.

- To install requirements.txt file. Run following command in your terminal.

  ` python3 install -r requirements.txt`

Once all the dependencies are installed.

#### Check the following details:

- [ ] Configure all your Database details in `database.py` file.
- [ ] Change the secret key with your secret key in `routers/auth.py` file.

Once you have completed these steps, we are good to move forward.

#### Run the server locally and test the API's

- To Run server locally in your machine. Run the following command.

  `http://localhost:8000/docs`

This command will run the Todos-Fast-API at `localhost` and on port `8000`

- We can move to browser and run this URL for opening inbuilt swagger UI of FastAPI so that we can test our API's

  `http://localhost:8000/docs`

Once we start testing then we can make the changes according to our requirements in the code.
