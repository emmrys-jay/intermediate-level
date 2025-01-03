# Intermediate Level Bootcamp Assesment DevOps Challenge

## Project:
The project is a simple static website that is deployed using docker.

## How to:
- Create a repository on your github account
- Work on the challenges

## Here are the challenges:
- Install Docker on your machine
- Create a Dockerfile for the app
- Run the static app using docker run
- Make a merge to your fork repository
**Note: Do not change the source code of the app. It is a simple static website.**

## Submission:
Push your changes to your repository and share the repository link with us via email: submissions@devopsthepracticalway.com with the subject: 
[Your Name] - Intermediate Level Bootcamp Assesment DevOps Challenge

## Solution

- Create a dockerfile that uses the alpine nginx image

- After writing the docker file, build and tag the image using 
```bash
    docker build -t intermediate-level .
```

- Run the image using:
```bash
    docker run -p 8080:80 intermediate-level
```

- View the static app using [http://localhost:8080](http://localhost:8080)

## Static application image

