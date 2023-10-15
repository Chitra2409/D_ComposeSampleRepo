# Dockerized Python Flask Application

## Overview

This repository contains a simple Python Flask application that demonstrates how to use Docker Compose to run a Flask web application along with a Redis database. The application provides a basic web page that displays a "Hello from Docker!!" message along with a hit count using Redis as a backend for storage.

## Prerequisites

Before you begin, ensure you have the following installed:

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

## Application Structure

The project structure is as follows:

- `app.py`: The main Python Flask application.
- `requirements.txt`: Lists the Python packages required by the application.
- `Dockerfile`: Contains instructions to build the Docker image for the application.
- `docker-compose.yaml`: Defines the services (web and Redis) and their configuration.

## Getting Started

To run this application locally using Docker Compose, follow these steps:

1. Clone this repository to your local machine:

   ```bash
   git clone [https://github.com/Chitra2409/D_ComposeSampleRepo.git]
2. Change your working directory to the cloned repository:
   cd your-repo-name
3. Build and start the application using Docker Compose:
   docker-compose up --build
4. Once the containers are running, you can access the web application in your browser at http://localhost:8000.
5. To stop the application, press Ctrl+C, and then run:
   docker-compose down


**Note**: This is just a sample code which I have copied from somewhere just to try my hands on Docker Compose.
