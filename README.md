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

1. Open a terminal in the project folder.
2. Build and start the Docker container:

   docker compose up --build

3. Open your browser and visit:

   http://localhost:8000

## Stop the Application

Press CTRL + C in the terminal, then run:

   docker compose down

## Technologies Used

- Python
- Django
- SQLite
- Docker
- Docker Compose