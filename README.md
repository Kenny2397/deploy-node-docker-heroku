docker build -t node-docker .

docker images

docker run -it -p 4000:3000 node-docker

docker run -d -p 4000:3000 node-docker

docker ps

docker stop ID