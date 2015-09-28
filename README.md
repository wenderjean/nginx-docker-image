# NGINX Docker Image

This is a image to docker container that deliver a nginx server running in port 8080 and creates a static page to say "Hello" as entrypoint of server.<br/>
It's also available on docker hub [wenderfreese/nginx-docker-image/](https://hub.docker.com/r/wenderfreese/nginx-docker-image/)

## Dependencies

``Docker 1.7+``<br/>

## Running

``docker run -d -p 8080:80 --name nginx wenderfreese/nginx-docker-image``<br/>
