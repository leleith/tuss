# Introduction
This repository contains the code and infra to get data from TUSS (health public data) and put into a PostgreSQL database.
You can also consult the data using an API.

To use this repository you must have Git and Docker installed in your machine. Do a clone and then
run "docker compose up --build" in the main folder and in the mage folder.

# Usage
To use this repository, open a terminal in the root folder and get the services up, by typing `docker compose --build -d`.\
This will run MageAI, PostgreSQL and FastAPI. MageAI is a data orquestrator.
