# Docker-Basics-
A beginner-level Docker project built for an Operating Systems Lab. It demonstrates the installation of Docker and Python, customization of Docker images, running Python applications inside containers, and sharing data between the host and container using bind mounts.
## 🎯 Objective
To learn Docker by practically working with containers and images. This includes:
- Installing Docker and Python
- Customizing an image with utilities like `curl`, `git`, and `python3`
- Running a Python script inside a container
- Exposing the container to the host

## ⚙️ Installation

Install the following tools:
- Docker
- Python 3 and pip

## 🛠️ Customization of Docker Image

Added the following to the base image:
- `curl`
- `git`
- `python3` and `pip`

## 🏗️ Building Docker Image

Created a custom Docker image after making modifications inside the running container using:

```bash
docker commit <container_id> student/ubuntu_custom
