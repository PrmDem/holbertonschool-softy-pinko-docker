# Start image with latest Ubuntu
FROM ubuntu:latest

# Install python3, python3-pip, and flask
RUN apt-get update
RUN apt-get upgrade -y
RUN apt-get install -y python3 python3-pip
RUN rm /usr/lib/python*/EXTERNALLY-MANAGED
RUN pip3 install flask

# Set up working directory
WORKDIR /app

# Copy Python file to Docker image
COPY ./api.py /app/api.py

# Launches Flask app
CMD ["python3", "api.py"]