# docker-express

Running an express app on a Docker Container

Improving my understanding of docker and DevOps by this small project, where I use docker to run an express app.

## To run a docker container

```sh
sudo docker build -t express-app .
```

```sh
 sudo docker run -v $(pwd):/app -p 3000:3000  -d --name docker-express express-app
 ```