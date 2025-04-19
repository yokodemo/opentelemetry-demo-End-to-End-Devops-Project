# Docker Lifecycle

Docker follows a standardized lifecycle that allows for efficient application deployment. The Docker lifecycle includes three key steps:

## 1. Dockerfile Creation  
A **Dockerfile** is a text-based script containing a set of instructions that define how a Docker image should be built. It specifies the base image, dependencies, environment configurations, and the command to run the application. The Dockerfile ensures consistency by automating the image creation process.

## 2. Docker Image Build  
The 'docker build' command creates a **Docker image** based on the **Dockerfile**. A Docker image is a lightweight, standalone executable package that contains all of the components required to run an application, including the runtime environment, system tools, libraries, and dependencies.

## 3. Run the Docker Container  
Once the image is built, a **Docker container** is created and executed using the `docker run` command. A container is an isolated environment where the application runs consistently across different systems. Containers leverage the lightweight nature of Docker images, ensuring minimal overhead and fast deployment.
