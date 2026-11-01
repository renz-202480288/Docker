
# PSUSphere - Docker Setup

This project contains the PSUSphere Django application packaged using Docker.

## Requirements

- Docker Desktop
- Docker Compose

## Project Structure

- Dockerfile
- docker-compose.yml
- requirements.txt
- .dockerignore
- for_client/docker-compose.yml
- README.md

## Build and Run the Application

1. Open Docker Desktop and make sure it is running.
2. Open a terminal in the project folder.
3. Build and start the Docker container:

   ```bash
   docker compose up --build
   ```

4. Wait for Django to finish starting.
5. Open your browser and visit the local application:

   **http://localhost:8000/**

   You can also use:

   http://127.0.0.1:8000/

## Access the Application

The application runs locally on your computer using Docker.

- Local URL: http://localhost:8000/
- Alternative URL: http://127.0.0.1:8000/
- Docker container port: 8000
- Django server address inside Docker: 0.0.0.0:8000

Keep the Docker terminal running while using the application.

## Stop the Application

1. Go to the terminal where Docker is running.
2. Press `CTRL + C`.
3. Run the following command:

   ```bash
   docker compose down
   ```

## Technologies Used

- Python
- Django
- SQLite
- Docker
- Docker Compose
