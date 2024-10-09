# using official python runtime base image
FROM python:3.9-slim

# setting the working directory in the container
WORKDIR /app

# copying the index.html file into the container at /app/static
COPY index.html /app/static/

# exposing the port the app will run on
EXPOSE 8000

# setting the command to start the web server
CMD ["python", "-m", "http.server", "8000", "--directory", "/app/static"]
