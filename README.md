# docker-express
Running an express app on a Docker Container

## To run a docker container

...properties
sudo docker build -t express-app .
...

...properties
 sudo docker run -v $(pwd):/app -p 3000:3000  -d --name docker-express express-app
 ...