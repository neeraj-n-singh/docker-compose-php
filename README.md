Docker Compose PHP Project
This repository sets up a multi-container environment using Docker Compose, featuring:

Frontend: NGINX server serving PHP files.
Backend: A basic Python/Flask application with a persistent MySQL database.

## Prerequisites

Docker
Docker Compose

## Clone the repo
```bash
git clone https://github.com/neeraj-n-singh/docker-compose-php.git
cd docker-compose-php
```

## Build
```bash
docker-compose up --build
```

## Access the applications
```bash
Frontend: http://localhost:85
```
## Project Structure
* frontend/: NGINX and PHP setup.
*  backend/: Python/Flask and MySQL setup.
*  docker-compose.yml: Docker Compose configuration.


Feel free to modify this as per your project updates!
