# Docker
## Containers
Containers are running systems defined by images. These images are made up of one or more layers and metadata for docker. 
![image](https://github.com/srsapireddy/Docker/assets/32967087/266b3161-24cb-49eb-87f7-dacf562373b2)

## Docker vs VM
![image](https://github.com/srsapireddy/Docker/assets/32967087/b68e44f2-178c-44a8-9ed3-423a98126a0d)
The key difference between containers and VMs is that the containers share the host systems kernal. This means docker containers are very light weight and fast. 

## Commands
```
docker build
docker run
```

## Why use Docker?
### Benefits
1. Standardization
2. CI Efficiency
3. Maintainability
4. Isolation + Security
5. Compatinility + Scalability
6. Business Cost Saving

## Why choose Docker for ML Systems?
1. Reproducibility 
2. Scalability
3. Compatibility

## Why Docker Compose?
- Define and run multi-container Docker applications
- YAML file to configure your appliaction's services
- Create and start all the services
- Create and start all the services from your configuration

### The docker-compose.yml file steps
1. Define your app's environment with a Dockerfile so it can be reproduced anywhere.
2. Define th services taht make up your app in docker-compose.yml so they can be run together in an isolated environment
3. Run docker-compose up and compose starts and runs your entire app

### Key Commands
```
docker-compose build
docker-compose up
docker-compose down
``

















