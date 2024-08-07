What is docker?

A platform for building, running and shipping applications in consistent manner.

Reasons that application run in one computer doesn't run in another computer:
1. Different OS
2. One or more files are missing
3. Different versions of software


Codes:

docker-compose up - to start the application
docker-compose down --rmi all - to stop the application


Container - An isolated environment for running an application
    - Allow running multiple apps in isolation.
    - Are lightweight
    - Use OS of the host machine
    - Start quickly
    - Need less hardware resources.

Docker Architecture
 uses Client-Server Architecture


Image
    - A cut-down OS
    - A runtime environment (eg Node)
    - Application files
    - Third-party libraries
    - Environment variables


codes:
    docker pull docker/hello-docker - to pull an image
    docker run docker/hello-docker - to run the image


Linux Distributions
    - Open Source OS

