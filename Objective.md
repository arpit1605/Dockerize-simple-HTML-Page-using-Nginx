# Dockerizing a Simple HTML Page with Nginx

## Objective

The objective is to familiarize with Docker and containerization by Dockerizing a simple HTML page using Nginx as the web server.

## Requirements

### 1. Basic HTML Page

- **Task**: Create a plain HTML page named `index.html`.
- **Content**: Include some basic content, such as "Hello, Docker!".

### 2. Nginx Configuration

- **Configuration File**: Create an Nginx configuration file named `nginx.conf`.
- **Purpose**: Ensure this file serves the `index.html` page.
- **Port Configuration**: Configure Nginx to listen on port 80.

### 3. Dockerfile

- **Task**: Create a `Dockerfile` to define the Docker image.
- **Base Image**: Use an official Nginx base image.
- **File Copy**: Copy the `index.html` and `nginx.conf` files to the appropriate location in the container.
- **Server Start-Up**: Ensure that the Nginx server starts when the container is run.

### 4. Building the Docker Image

- **Build Process**: Build the Docker image using the created `Dockerfile`.

### 5. Push the Image on ECR

- **Repository Management**: Create a public repository and push the image to AWS ECR.


### Customization

- **Enhancements**: Add more features to your HTML page or customize the Nginx configuration to serve additional static files.

### HTTPS Support

- **Implementation**: Explore and implement support for serving the HTML page over HTTPS.

### Docker Compose

- **Compose File**: Create a `docker-compose.yml` file to define and run the Docker container in a streamlined manner.
