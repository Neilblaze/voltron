## Running the containers 🐋

### Prerequisite : 
- you need `docker-compose` installed on your machine

### Simply start the container by using :   
`docker-compose up`

### Result :
We can test it out by opening localhost:80 on the browser or using curl. It can be observed that NGINX is properly proxying requests to the different instances of our API using the round-robin method.

