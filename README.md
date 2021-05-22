# MongoDB Login Session

User registration and login session.  User data is hosted remotely on MongoDB ATLAS.

## The Specifications

*   Build a UI for registration & login
*   Add a .env file for keeping mongoDB key values secret.
*   Create login and registration routs
*   Display Flask confirming login status based on user session
*   User encryption to hash user password
*   Verify user credentials using MongoDB Compass Community
## Acceptations

This code was based on a tutorial by Pretty Printed first published in April 2016
## Deployment

1.  This project can be forked from the GitHub repository.
2.  Setup a .venv environment for the project.  Once the environment is loaded, install the requirements.
3.  Before executing, setup a .env file in the same project directory with your own MongoDB username, dbName and mongo URI.  Be sure to add this file to your .gitignore file.
4.  Execute the application by running python login_example.py
5.  Then open the URL (http://127.0.0.1:5000/) for the application in your local browser.
