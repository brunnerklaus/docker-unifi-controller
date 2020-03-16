# docker-unifi-controller

Docker image for running Ubiquiti's [UniFi Controller software](https://www.ubnt.com/download/unifi/) on a [Raspberry Pi](https://www.raspberrypi.org/).

# Usage

## Prerequisites

A Raspberry Pi running with [Docker and Docker Compose installed](https://docs.docker.com/engine/installation/linux/docker-ce/debian/#install-using-the-convenience-script) on it. Guides such as [this](https://blog.alexellis.io/getting-started-with-docker-on-raspberry-pi/) or [this](https://blog.hypriot.com/getting-started-with-docker-and-mac-on-the-raspberry-pi/) are available for beginners.

## On RaspberryPI:

1. `git clone https://github.com/brunnerklaus/docker-unifi-controller.git ~/docker-unifi-controller.git`
2. `cd ~/docker-unifi-controller.git`
3. Edit `docker-compose.yml` if you need a the correct Dockerfile for your architecture platform.
4. `docker-compose up -d`

## From any computer on your network:

Visit `https://<host-ip>:8443/` with your browser.
