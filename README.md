# Coffee Shop Full Stack

## Full Stack Nano - IAM Final Project

This app demonstrates my skills to create a full stack drink menu application. The application:

1. Display graphics representing the ratios of ingredients in each drink.
2. Allow public users to view drink names and graphics.
3. Allow the shop baristas to see the recipe information.
4. Allow the shop managers to create new drinks and edit/delete existing drinks.


### Backend

The `./backend` directory contains a Flask server with a SQLAlchemy module and Auth0 integration for aunthentication. You may need to edit the auth.py file with your own credentials from Auth0 to run the app.

[View the README.md within ./backend for more details.](./backend/README.md)


### Frontend

The `./frontend` directory contains a complete Ionic frontend to consume the data from the Flask server. If you are using your own Auth0 variables, you will only need to update the environment variables found within (./frontend/src/environment/environment.ts) to reflect the Auth0 configuration details set up for the backend app.

[View the README.md within ./frontend for more details.](./frontend/README.md)


## Instrucctions to run this app

For dependencies and other instructions, please refer to the READMEs in:

1. [`./backend/`](./backend/README.md)
2. [`./frontend/`](./frontend/README.md)
