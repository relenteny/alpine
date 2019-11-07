# alpine

This Alpine Linux image extends the official [Alpine Linux](https://hub.docker.com/_/alpine) image and is used as a consistent basis for other images in this repository.

Additions to the official image include:

* A default user, ```alpine```, which is specified in the Dockerfile as the ```USER``` to use when running the image

* Adds ```curl``` and ```bind-tools``` to the image

* Sets the ```WORKDIR``` to ```/home/alpine```

* Sets the ```ENTRYPOINT``` to use a login shell, ```/bin/sh -l```
