# Containerizing-_WebApplication
The main objective is to develop a minimal viable product (MVP)of the project management web application using HTML, CSS, and JavaScript. Additionally, you will containerize this application using Docker to ensure it can be easily deployed and scaled across different environment 

# Usage
Running the Application Locally

To run the application locally, make sure you have Docker installed on your system. Then, follow these steps:

1. Clone this repository to your local machine:

```bash
https://github.com/Stella-Remember/Containerizing-_WebApplication.git
```
2.Navigate to the project directory:

```bash
cd Containerizing-_WebApplication
```
3. Build the Docker image:
```bash
docker build -t task-managing:latest .
```

4. Run the Docker container:
```bash
docker run -d -p 3000:3000 task-managing:latest
```

5. Access the application in your web browser at http://localhost:8080.

# Docker Image

You can view Image from DockerHub, DockerHub Image:https://hub.docker.com/repository/docker/rstella/my_app/general

Presentation slides

You can view the slides using canva. Here is the Link:https://www.canva.com/design/DAGBNkyFank/n4ejMxBHV5gBwGQTIGxztw/edit?utm_content=DAGBNkyFank&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton
