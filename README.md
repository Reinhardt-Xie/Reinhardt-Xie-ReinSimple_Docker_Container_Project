## Simple_Docker_Container_Project

This is building a container for the backpropagation algorithm with respect to Deep Neural Network.

### Build image

docker build --tag backpropagation_algo .

### List docker images
docker image ls

### Run my newly built container

docker run -it backpropagation_algo python app.py --name "backprop"

### Create a docker repo on Dockhub

Create a docker repo called reinhardtxie/backpropagation_algorithm on the Docker Hub

### Change local image name

docker tag backpropagation-algo reinhardtxie/backpropagation_algorithm

### Push to Docker Hub

docker push reinhardtxie/backpropagation_algorithm

### Run it on Cloud or your own terminal

docker pull reinhardtxie/backpropagation_algorithm:latest
docker run -it reinhardtxie/backpropagation_algorithm:latest bash 




