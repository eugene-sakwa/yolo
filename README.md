# YOLO

The YOLO application is an e-commerce website that doubles as a dashboard where you can load retail products onto the site.

![Frontend Image](https://github.com/eugene-sakwa/yolo/assets/129692730/0db2751f-ed4d-4855-bc71-edd46a268d94)
![Backend Image](https://github.com/eugene-sakwa/yolo/assets/129692730/664624f9-30bd-4093-8964-80c7b752c09b)

## Prerequisites

Before you run this app, make sure you have the following installed on your system:
- Docker: [Docker Installation Instructions](https://docs.docker.com/get-docker/)

## Installation

To run the application using Docker containers, follow these steps:

1. **Clone the repository to your local machine**:

    ```bash
    git clone https://github.com/eugene-sakwa/yolo.git
    ```

2. **Navigate to the project directory**:

    ```bash
    cd yolo
    ```

3. **Pull the Docker images for the frontend and backend from Docker Hub**:

    ```bash
    docker pull eugenedon/backend-image:v2
    docker pull eugenedon/client-image:v5
    ```

## Usage

Once you have pulled the Docker images, you can run the app using the following command:

```bash
docker-compose up
```
This command will start the frontend and backend containers and link them together.

You can access the app in your web browser at http://localhost:3000.

License
This project is licensed under the MIT License - see the LICENSE file for details.
