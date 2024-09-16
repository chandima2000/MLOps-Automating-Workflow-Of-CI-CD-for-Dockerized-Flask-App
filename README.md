## MLOPS with Docker

# Flask MLOps Project

This project is a simple website built using Flask. The project is containerized with Docker and can be easily deployed using DockerHub.

## Features
- Flask web server
- Docker containerization for easy deployment

## Prerequisites
Make sure you have the following installed on your system:
- [Docker]

## Getting Started

### 1. Clone the Repository
First, clone the repository to your local machine:

```bash
git clone https://github.com/chandima2000/MLOps-Automating-Workflow-Of-CI-CD-for-Dockerized-Flask-App
cd MLOps-Automating-Workflow-Of-CI-CD-for-Dockerized-Flask-App
```

### 2. Pull the Docker Image from DockerHub

```bash
    docker pull chandima2000/flask-app:latest
```

### 3. Run the Docker Container

```bash
    docker run -p 5000:5000 chandima2000/flask-app:latest
```

### 4. Access the Application

```bash
    http://localhost:5000
```

### Build and Push the Docker Image

#### 1. Build the Docker Image
```bash
docker build -t chandima2000/flask-app .
```

#### 2. Push the Docker Image to DockerHub
```bash
docker push yourusername/your-repo-name:latest
```

