# Hello World with NodeJs and Docker

This is a simple NodeJs project that displays a message through a Docker container. It is configured to listen on port 3000.

## Prerequisites

- [Docker](https://www.docker.com/) installed on your machine.

## Steps to test the program

### 1. Clone the repository
First, clone this repository to your local machine.

```bash
https://github.com/Felipe0806/NodeJsProgra.git
cd NodeJsProgra
```

### 2. Build the Docker image
In the directory where the Dockerfile is located, run the following command to build the Docker image:

```bash
docker build -t hola-mundo-nodejs .
```

### 3. Run the Docker container
Once the image is built, you can run the container on port 3000:

```bash
docker run -p 3000:3000 hola-mundo-nodejs
```

### 4. Verify that the program is working
Open your web browser and navigate to http://localhost:3000. You should see the message as a response.
