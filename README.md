# docker

`docker system prune -a`

`docker rmi $(docker images -a -q)`

`docker rm $(docker ps -a -f status=exited -q)`

`docker rm $(docker ps -a -f status=exited -f status=created -q)`

`docker stop $(docker ps -a -q)`

`docker rm $(docker ps -a -q)`

`docker kill $(docker ps -q)`
