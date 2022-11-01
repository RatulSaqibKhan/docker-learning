# Docker Learning
## Use the following commands in terminal
1. `cd mysql`
2. `sudo docker build -t mysql-test .`
3. `sudo docker run -p 3305:3306 mysql-test:latest`
4. open new terminal `cd {path_to}\node`
5. `sudo docker build -t msvc .`
6. `sudo docker run msvc:latest`
## To list all Docker Containers
1. `sudo docker ps`
## To get inside docker container
1. `sudo docker exec -it {container_id} bash`
