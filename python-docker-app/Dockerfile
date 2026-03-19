# we need to get the base image for our docker container
FROM ubuntu:latest

# Set the working directory in the image
WORKDIR /app

# Copy all the source code files from host machine to image file system
COPY . /app

# Install the necessary packages
RUN apt-get update && apt-get install -y python3 

# Run a command to start the application
CMD ["python3", "app.py"]
