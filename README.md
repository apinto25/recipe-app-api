# Recipe app API
Recipe api source code using Django rest framework.
This API allows to create users, each user can create their own ingredients, tags and recipes. A recipe is related to one or many ingredients and to one or many tags. Also recipes can be filtered by ingredients, tags or both.

## Requirements
Docker must be installed in your computer.

## Running the project
1. Open the terminal and move to the root directory of the project.
2. From the terminal run

        docker-compose up

    Running the project for the first time will take a few minutes.
3. Open the web browser and go to http://localhost:8000