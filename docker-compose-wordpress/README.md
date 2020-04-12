docker network create -d bridge privnet
docker network create -d bridge pubnet
docker-compose up -d
docker ps
