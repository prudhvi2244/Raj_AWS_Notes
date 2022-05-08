version: '3'

networks:
  custom-network:
    external:
      name: my_network

services:
  mysql_db:
    image: mysql
    container_name: mysql_container
    restart: always
    environment:
      - MYSQL_ROOT_PASSWORD=password
      - MYSQL_DATABASE=bookdb
    networks:
      - custom-network
  
  ubuntu:
    image: ubuntu
    container_name: ubuntu_container
    restart: on-failure
    command: ["sleep","infinity"]
    networks:
      - custom-network
