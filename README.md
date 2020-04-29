# Marvel Api for the marvel 

Fill the `nodejs/src/config-dev.json` with the marvel credentials

Start the docker

`docker-compose up`

Access the view :

`http://http://marvel.wako057.net/` 

## Start the wakostack

`mydocker marvel-api up -d`

ou

`mydocker marvel up -d`

## Start the docker
   
   `docker-compose up`


## Docker

### Wakodock

- wakodock marvel-api build marvel-api-node  
- wakodock marvel-api push marvel-api-node  


### Docker classic

- docker tag projects_marvel-api-node nexus.wako057.net:18442/marvel-api-node:latest
- docker push nexus.wako057.net:18442/marvel-api-node:latest

