version: '3'
services:
  mysql_db:
    image: mysql
    container_name: mysql_container
    restart: always
    environment:
      - MYSQL_ROOT_PASSWORD=password
      - MYSQL_DATABASE=bookdb
