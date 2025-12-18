# Dockerize-an-application
## how to dockerize an application
i've some knowledge in docker (image and container) that was the 1st challenge of DevOps bootcamp. 
Now's the second challenge we were asked to dockerize an application

What does “dockerizing an application” mean?
Dockerizing an application means preparing an application so it can run inside a Docker container in a consistent, portable, and reproducible way.
It involves:
- Defining the application environment
- Packaging the application and its dependencies
- Making it runnable using Docker
- This is done primarily by creating a Dockerfile.


### 1. Dockerizing an application (the process)
- This is the preparation phase:
- Writing a Dockerfile
- Choosing a base image
- Installing dependencies
- Copying application files
- Defining how the app starts
### 2. Creating a Docker image (the result)
A Docker image is the packaged result of dockerizing your application.
You create it using: docker build -t my-app .
The image is:
- Immutable
- Reusable
- Shareable (e.g., via Docker Hub)


i haven't done anything yet
