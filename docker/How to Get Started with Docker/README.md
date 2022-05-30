docker build --help
docker build --tag hello-world .
docker images
docker run --help
docker run hello-world
docker ps
docker ps -a
docker start crazy_ptolemy
docker stop crazy_ptolemy
docker rm crazy_ptolemy
docker images
docker run -p 8080:80 --name hello -d hello-world
docker stop hello

