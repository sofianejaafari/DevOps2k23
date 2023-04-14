
# Lab

Containers with Docker


## 1. Write a Dockerfile and build a Docker image

Run the following command:
   ```
   docker pull elmarmry/hello_world_docker
   ```
     
   ```
   docker run -p 12345:8080 -d elmarmry/hello_world_docker
   ```

## 2. Build and run a multiple container app with Docker Compose

 Run the container with the following command:  
   ```
   docker pull elmarmry/hello-world-docker-compose
   ```
   ```
   docker-compose up
   ```
