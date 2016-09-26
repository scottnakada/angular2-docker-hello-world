# angular2-docker-hello-world
This git repository contains an Angular 2 Sample Hello World application.
It can be started as within a docker container.

Docker creates a virtual machine running a debian linux environment with a
web server.  You can download docker for Mac, Windows or Linux from:
https://www.docker.com/products/docker

To start the docker container, use:

	docker run -it -p 3000:3000 -p 3001:3001 --name angular2-hello scottnakada/angular2-hello-world

To view the web-page, connect to localhost:3000

To connect to the docker container to edit files, use:

	docker exec -it angular2-hello bash

The files for editing are located in /quickstart
