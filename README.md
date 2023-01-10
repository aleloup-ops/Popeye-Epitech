# Popeye-Epitech

### Introduction ###
The goal of Epitech's project Popeye is to containerize and define the deployment of a simple web poll application.

There are five elements constituting the application:
- Poll, a Flask Python web application that gathers votes and push them into a Redis queue.
- A Redis queue, which holds the votes sent by the Poll application, awaiting for them to be consumed by the Worker.
- The Worker, a Java application which consumes the votes being in the Redis queue, and stores them into a PostgreSQL database.
- A PostgreSQL database, which (persistently) stores the votes stored by the Worker.
- Result, a Node.js web application that fetches the votes from the database and displays the. . . well, result. ;)

Author: Alexis Leloup

### Installation ###

In order to run this project you will need:
    
    - Docker
    
    - docker-compose
    
### Run the project ###

Run the following command in your terminal :

`docker-compose up --build`

You can now access the application on port 80
