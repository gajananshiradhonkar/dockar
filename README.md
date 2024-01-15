# Introduction to Docker:

Docker is a very popular and powerful open-source containerization platform 
that is used for building, deploying, and running applications. 

Docker allows you to decouple the application/software from the underlying infrastructure.

# What is a Container?

Containers allow the packaging of your application (and everything that you need to run it) in a
"container image"

 Inside a container you can include a base operational-system, libraries, files
and folders, environment variables, volumes mount-points, and the application binaries.

A "Docker image" is a template for the execution of a container --- It means that you can have
multiple containers running from the same image, all sharing the same behavior, which
promotes the scaling and distribution of the application. 

These images can be stored in a remote registry to ease the distribution.

Once a container is created, the execution is managed by the "Docker Engine" aka "Docker
Daemon". 
You can interact with the the Docker Engine through the "docker" command. 

These three primary components of Docker (client, engine and registry)

# 1)Docker Client: 
This component performs “build” and “run” operations for the purpose of opening communication with the docker host.

# 2)Docker Host: 
This component has the main docker daemon and hosts containers and their associated images. 

The daemon establishes a connection with the docker registry.

# 3)Docker Registry: 
This component stores the docker images. 

There can be a public registry or a private one. 

The most famous public registries are Docker Hub and Docker Cloud.

Docker can be visualized as a big ship (docker) carrying huge boxes of product (containers).

Docker container doesn’t require the installation of a separate operating system.

