docker build -t my-php-app .

docker ps -l
docker stop <id>
docker rm   <id>

docker-compose up -d
docker-compose down

docker-compose.yml
Dockerfile

docker rm -vf $(docker ps -aq)
docker rmi -f $(docker images -aq)
docker-compose up -d --build



Install Nano:
docker exec -t -i <container> /bin/bash
apt-get update
apt-get install nano



git diff

git add .
git commit -m ""
git push

https://dzone.com/articles/top-20-git-commands-with-examples
