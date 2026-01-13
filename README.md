# Introduction to Docker
This repository contains tasks built to show us how Docker works. A powerful tool to develop, ship, and run applications, Docker makes use of containers to ensure code is shared with its specific environment, making it much easier not only to deploy applications but also to work with a team.

## General Information
__Number of tasks:__ 7<br/>
__Completed:__ TBA<br/>
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

#### 
See file [](./)

#### 
See file [](./)

#### 
See file [](./)

#### 
See file [](./)