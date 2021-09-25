# Creating-Image-Docker

A Docker image contains application code, libraries, tools, dependencies and other files needed to make an application run.

Steps to create a simple image-

```

1. Create the Dockerfile similiar to the DockerFile in this repo.
$ mkdir demo
$ cd demo
$ vi Dockerfile

2. Create another file in the same directory similiar to the file in this repo.
$ vi index.nginx-debian.html

3. Execute the file
$ sudo docker build .

4. List the images to check the newly created Docker image
$ sudo docker images

```
