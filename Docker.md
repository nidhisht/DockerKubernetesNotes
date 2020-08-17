# Containerize .NET Core 3.1 Web API using Docker


## Prerequisites
1. Install docker desktop on windows machine

2. Install Azure CLI on windows machine


## Docker Commands

1. Docker version

docker version

docker --version

2. Docker build

docker build -t weatherapi:v1 .

3. Retag docker image to ACR (Azure Container Registry)

docker tag weatherapi:v1 acrweather.azurecr.io/weatherapi:v1
