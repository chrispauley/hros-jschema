# Dockerized hros-jschema

## Build the docker image
docker build -t nginx-hrosjschema .

## Create and run a container
docker run -d --rm -p 8001:80  --name nginx-hrosjschema-app nginx-hrosjschema

## Inspect running processes
docker ps

## Kill running images
docker kill <container_id>

## To inspect the contents of the running container
docker exec -it nginx-hrosjschema-app sh

# View the logs
docker logs nginx-hrosjschema-app

## To kill the running container
docker kill nginx-hrosjschema-app

## To remove the image created by the Dockerfile
docker rmi nginx-hrosjschema-app

To tag and commit
```
docker tag nginx-hrosjschema chrispauley/nginx-hrosjschema
 - create the repo at docker hub
docker push chrispauley/nginx-hrosjschema

- login to aws
docker pull chrispauley/nginx-hrosjschema

docker run -d --rm -p 8007:80  --name nginx-hrosjschema-app chrispauley/nginx-hrosjschema

http://ec2-54-210-221-125.compute-1.amazonaws.com:8007/index.html
```
