# docker-resources

## check docker status
docker ps

## docker logs 
docker logs

## check docker images
docker images

## create docker image
docker build -f Dockerfile.dev -t reactapp .

## docker run container
docker run -it -p 3000:3000 -v /app/node_modules -v ${pwd}:/app reactapp   

