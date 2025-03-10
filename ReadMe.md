# Docker for Robotics with the Robot Operating System (ROS/ROS 2)

Author: [Tobit Flatscher](https://github.com/2b-t) (August 2021 - February 2023)

[![ROS Docker](https://github.com/2b-t/docker-for-ros/actions/workflows/build-ros.yml/badge.svg)](https://github.com/2b-t/docker-for-ros/actions/workflows/build-ros.yml) [![ROS 2 Docker](https://github.com/2b-t/docker-for-ros/actions/workflows/build-ros2.yml/badge.svg?branch=main)](https://github.com/2b-t/docker-for-ros/actions/workflows/build-ros2.yml) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)



## Overview

This guide discusses best practices for **robotics development with the [Robot Operating System (ROS/ROS 2)](https://www.ros.org/) and Docker/Docker-Compose**. This includes displaying **graphic user interfaces**, working with hardware, **real-time capable code** and the **network set-up** for multiple machines. Additionally it walks you through the **set-up with Visual Studio Code**.

This repository used to be part of [another guide](https://github.com/2b-t/docker-realtime) I have written on Docker and real-time applications. As the general Docker and ROS part has now become quite lengthy, I have decided to extract it and create a repository of its own for it.



## Structure of this guide

This guide is structured in four chapters:

- [**Motivation**](./doc/Motivation.md): Tries to answer why you should use Docker as a company or research institution.
- [**Introduction to Docker and Docker-Compose**](./doc/Introduction.md): Introduces fundamental concepts of container-based development.
- [**Set-up with Visual Studio Code**](./doc/VisualStudioCodeSetup.md): Walks you through the set-up of containers with Visual Studio Code.
- [**Graphic user interfaces and Docker**](./doc/Gui.md): Discusses the challenges of using Docker with graphic user interfaces and presents workarounds.
- [**ROS and Docker**](./doc/Ros.md): Discusses best-practices of Docker and ROS/ROS 2.
- [**Working with hardware**](./doc/WorkingWithHardware.md): Discusses best-practices when working with hardware.

It is further extended by an external guide on **Docker for real-time applications with `PREEMPT_RT`** that can be found [here](https://github.com/2b-t/docker-realtime) as well as several examples for giving software running inside a container access to hardware.

 

## Get a copy

This workspace contains several other repositories as submodules. Therefore please clone it with the following command:

```bash
$ git clone --recurse-submodules https://github.com/2b-t/docker-for-ros.git
```
