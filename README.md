# natural-service-base

This is the project for the base image for creating Software AG Natural micro-services.

To build the image locally, run:

`docker build --tag employees-service .`

You must have 'bought' (it is free) the [softwareag/natural-ce](https://hub.docker.com/_/softwareag-natural-ce) image from the Docker Hub Store and accepted the licence agreement. You must then `docker login` as the account under which you purchased the `softwareag/natural-ce` image.  

The image is automatically built to [Docker Hub](https://hub.docker.com/r/miketrout/natural-service-base) on a commit to master as `miketrout/natural-service-base:latest`.
