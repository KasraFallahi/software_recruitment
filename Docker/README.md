# Docker

Write a Dockerfile that sets up a web server using Python and serves the `index.html` file located in the same directory as this README.

The Dockerfile should perform the following steps:

1. Install Python
2. Copy the `index.html` file into the container, placing it in a dedicated folder
3. Configure the Dockerfile to start a Python web server that serves files from the folder where the `index.html` file is located

Feel free to use whichever port you find suitable.

## How To Run the Container

First use this command to build the image using docker file

```
docker build -t python-web-server .
```

Then, start the container using this command

```
docker run -d -p 8000:8000 python-web-server
```
