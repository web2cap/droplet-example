# Droplet example
#### Example of deploying multiple projects on a server.
An example of deploying several independent applications on a server.

Each application is packaged in docker containers, has an isolated local network.

Traefik as a proxy pass will be responsible for proxying traffic to the nginx application and for updating certificates for the application domain. Traefik and NGINX application containers are placed in an isolated network.

## Stack:
 - Traefik 
 - Docker 
 - Docker Compose 
 - Let's encrypt
 - NGINX
 - Ubuntu
