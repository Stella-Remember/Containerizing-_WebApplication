# Containerizing-_WebApplication
The main objective is to develop a minimal viable product (MVP)of the project management web application using HTML, CSS, and JavaScript. Additionally, you will containerize this application using Docker to ensure it can be easily deployed and scaled across different environment 

# Usage
Running the Application Locally

To run the application locally, make sure you have Docker installed on your system. Then, follow these steps:

Clone this repository to your local machine:

```bash
git clone https://github.com/NiyonshutiDavid/Task-managing.git
```
Navigate to the project directory:

```bash
cd Task-managing
Build the Docker image:
```
docker build -t task-managing:latest .
Run the Docker container:

```bash
docker run -d -p 3000:3000 task-managing:latest
Access the application in your web browser at http://localhost:3000.
```
Docker Image

You can view Image from DockerHub, ```bash DockerHub Image:https://hub.docker.com/repository/docker/rstella/my_app/general
```

Presentation slides
You can view the slides using canva. Here is the Link:
