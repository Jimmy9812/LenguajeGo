
# Hello, Docker! - Go Web Application

This is a simple project that uses Go to create a web server that responds with a basic message: **"Hola, Mundo!"**. The project is containerized using Docker for easy deployment and portability.

## Technologies Used

- Go 1.23
- Docker
## Description

This project demonstrates how to create a basic web application with Go and how to containerize it using Docker. The web server responds with a personalized message when accessing the root route `/`.

## Requirements

To run this project, you will need to have the following installed:

- [Docker](https://www.docker.com/products/docker-desktop)
- [Visual Studio Code](https://code.visualstudio.com/)
- **Go**: The Go programming language, version 1.23

## Files in the Project

- **Dockerfile**: Contains the configuration to build the Docker image with Go.
- **main.go**: The Go file that creates a web server and serves the message "Hello, Docker! with Jimmy Maila".

## Dependences

* No external dependencies are required for this project. Ensure you have Go installed. 
* You can download it from https://golang.org/dl/.




## Steps to Run the Project

### 1. Clone the Repository

If you haven't downloaded the project yet, clone or download it from GitHub:

```bash
git clone https://github.com/Jimmy9812/LenguajeGo.git
```
### 2. Build the Docker Image
In the project directory, run the following command to build the Docker image:

```bash
docker build -t lenguajeGo .

```

### 3. Run the Container
Once the image is built, run the container with this command:
```bash
docker run -p 8080:8080 lenguajeGo
```

### 4. Verify the Application
Open your web browser and go to http://localhost:8080. You should see a page with the message:
Hola, Mundo!