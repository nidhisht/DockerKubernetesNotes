# Containerize .NET Core 3.1 Web API using Docker


## Prerequisites
1. Install docker desktop on windows machine

2. Install Azure CLI on windows machine


## Docker Commands

### Get docker version details
docker version

### Get docker version number
docker --version

### Get list of docker images
docker images

### Remove a docker image
docker rmi -f 46e18b10d5fe

### Build docker image
docker build -t weatherapi:v1 .

*NOTE: . denotes the current directory*

### Retag docker image to ACR (Azure Container Registry)
docker tag weatherapi:v1 acrweather.azurecr.io/weatherapi:v1

