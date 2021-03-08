# Simple_Docker_Container_Project

This is building a container for backpropagation algorithm with respect to Deep Neural Network.

## Build the Container Yourself and Push to Docker Hub

### Build image

docker build --tag backpropagation_algo .

### List docker images
docker image ls

### Run my newly built container

docker run -it backpropagation_algo python app.py --name "backprop"

### Push to Docker Hub

docker push reinhardtxie/backpropagation_algorithm

## Run it yourself

```bash
docker pull reinhardtxie/backpropagation_algorithm:latest
docker run -it reinhardtxie/backpropagation_algorithm:latest bash 

#then run python app.py --help
```

## Pass in a command

```bash
docker run -it reinhardtxie/backpropagation_algorithm:latest python app.py 
```


