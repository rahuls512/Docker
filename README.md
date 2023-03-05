# Docker v.20.10.17
Docker:
Docker is a containerization platform that allows developers to package and deploy applications in isolated, lightweight environments called containers. Docker containers provide a consistent runtime environment for applications, regardless of the host operating system and dependencies.

Here are some basic concepts and commands in Docker:

Docker image: A Docker image is a lightweight, standalone, and executable package that includes everything needed to run an application, such as the code, runtime, system tools, libraries, and settings.

Docker container: A Docker container is a running instance of a Docker image. It is isolated from the host system and other containers, but shares the same kernel and resources with the host.

Dockerfile: A Dockerfile is a text file that contains instructions to build a Docker image. It specifies the base image, the commands to install and configure the application, and the exposed ports.

Docker Hub: Docker Hub is a central repository for Docker images. It provides a public and private registry for users to share and store Docker images.

Docker commands:

docker run: Run a Docker image and create a container.
docker build: Build a Docker image from a Dockerfile.
docker push: Push a Docker image to a Docker registry, such as Docker Hub.
docker pull: Pull a Docker image from a Docker registry.
docker ps: List running containers.
docker stop: Stop a running container.
docker rm: Remove a stopped container.
docker images: List Docker images.
These are just some of the basics of Docker, and there are many more commands and concepts to explore. Docker is a powerful tool for building, testing, and deploying applications in a portable and scalable way.
