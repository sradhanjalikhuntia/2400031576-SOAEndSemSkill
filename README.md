
# Microservice Containerization

## Experiment
Containerization of a Microservice using Docker.

## Objective
To run a microservice consistently across different environments without dependency conflicts.

## Technologies Used
- Python
- Flask
- Docker

## Application Features
- Home endpoint
- Health check endpoint

## Docker Commands

Build Docker Image:
docker build -t my-microservice .

Run Container:
docker run -d -p 5000:5000 --name my-container my-microservice

Verify Container:
docker ps

Test Application:
http://localhost:5000

Health Check:
http://localhost:5000/health
