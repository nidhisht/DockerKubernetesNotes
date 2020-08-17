# Containerize .NET Core 3.1 Web API using Docker


## Prerequisites
1. Install docker desktop on windows machine

2. Install Azure CLI on windows machine


## Docker Commands

### Docker version
docker version

### Docker version (only the version number)
docker --version

### Docker build
docker build -t weatherapi:v1 .

*NOTE: . denotes the current directory*

### Retag docker image to ACR (Azure Container Registry)
docker tag weatherapi:v1 acrweather.azurecr.io/weatherapi:v1
