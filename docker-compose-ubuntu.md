version: '3'
services:
  ubuntu:
    image: ubuntu
    container_name: ubuntu_container
    restart: on-failure
    command: ["sleep","infinity"]





