# docker-ngnix-webapp
Creates a NGINX reverse proxy that routes to a webapp and static website

Prerequisites

- Before you can use this code, you must install Docker and docker-compose on your local machine. 
https://docs.docker.com/get-docker/
https://docs.docker.com/compose/install/

Make a special directory for this project and place all the files inside that directory

How It Works

- This docker project contains a docker-compose file that launches 4 separate containers: 
  1. A NGINX reverse proxy
  2. A NGINX static website
  3. A flask webapp
  4. A redis database

The reverse proxy will direct the http request to the webapp or static website depending if the user requests /app or /static.

The website is a simple sample website.

The webapp is a simple sample web application that uses a redis database to hold a value.

How To Create the Docker Project

- After placing all the files in your project directory - type docker-compose up 





