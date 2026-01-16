# Introduction to Docker
This repository contains tasks built to show us how Docker works. A powerful tool to develop, ship, and run applications, Docker makes use of containers to ensure code is shared with its specific environment, making it much easier not only to deploy applications but also to work with a team.

## General Information
__Number of tasks:__ 7<br/>
__Completed:__ 7<br/>
__Passed:__ TBA<br/>

## Tasks
#### 0. Create Your First Docker Image
Create a Dockerfile that is based on the latest ubuntu; update `APT` using `apt-get update` and currently installed software using `apt-get upgrade -y`. Running the Docker image in a container will echo “Hello, World!” on the terminal.<br/>
See directory [task0](./task0)

#### 1. Back-end
Change the Dockerfile to install `Python3`, `pip3`, and `Flask`. Then, create a Python file named `api.py`. The server started with it must be reachable outside the Docker machine.<br/>
See directory [task1](./task1)

#### 2. Front-end
Now separating back- and front-end in different subdirectories, distribute a front-end using `Nginx` which will be used in the front-end Dockerfile instead of Ubuntu.<br/>
See directory [task2](./task2)

#### 3. Connecting the Front-end and Back-end
In this task we learn to connect to front- and back-end, to display dynamic data on our front-end. Making ends meet, so to speak.<br/>
See directory [task3](./task3)

#### 4. Making it Simpler with Docker Compose
Instead of building images one by one, we learn to use Docker Compose to do it quickly and more effectively.<br/>
See directory [task4](./task4)

#### 5. Proxy Server
In this task, we learn how to use a proxy server to 
See directory [task5](./task5)

#### 6. Scale Horizontally
Load balancing with Nginx and Docker is as easy as adding a flag to the `docker-compose up` command.
See directory [task6](./task6)