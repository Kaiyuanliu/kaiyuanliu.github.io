---
layout: post
title: Get Docker on Mac 01
---

This post describes how to install and set up Docker on Mac OSX. This is the first time I play with Docker.

# Before installation

In order to make Docker working on Mac quickly, [Docker for Mac] is the first choice for me to choose, but there are some requirements before install it on Mac, please go [here][Docker for Mac requirements]for more information.

# Installation and setup

Download [Docker for Mac][Docker for Mac download] and install it.
Double click the `Docker.app` to start Docker, it may ask privileged access to install components on your Mac. After the installation, you should be able to see a docker icon on the top bar.

<img src="/attachments/images/docker_icon_screenshot.png" width="50%" height="100%" alt="Docker Icon" />

By click the icon, you can change preference or other options.

# Test Docker

Open a terminal and run these commands to see the version of Docker.

> Note: You may not see the same version as mine

<img src="/attachments/images/docker_command.png" width="50%" height="100%" alt="Docker Version Check" />

In order to verify that Docker is running correctly, run `docker run hello-world` in the command line.

<img src="/attachments/images/docker_hello_world.png" width="50%" height="100%" alt="Docker Hello World"/>

Boom! You are good to go now.


[Docker for Mac]: <https://www.docker.com/products/docker#/mac>
[Docker for Mac requirements]: <https://docs.docker.com/docker-for-mac/install/#/what-to-know-before-you-install>
[Docker for Mac download]: <https://download.docker.com/mac/stable/Docker.dmg>