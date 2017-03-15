# User guide:
This folder contains all you need to setup Entrance using Docker, 
Tested on Ubuntu 16.04. with:
- docker version 17.03.0-ceer (community edition)
- docker-compose version 1.11.2,

# Build the docker containers with:
sudo docker-compose build

The sources are fetched from: 

Dashboard/Frontend and KeyExchange (KEX) services
- https://github.com/SNET-Entrance/Entrance-UM
- https://github.com/SNET-Entrance/Entrance-KEX

Backend (not yet dockerized  - comming soon!)
- https://github.com/SNET-Entrance/Entrance-Backend

# Start docker containers with:
sudo docker-compose up -d

# Get the log
sudo docker-compose logs -f

# Optional: jump into the "frontend" or "kex" container:  

sudo docker-compose exec frontend /bin/bash 
sudo docker-compose exec kex /bin/bash 

# Webinterfaces are available on:
- localhost:5000 (Dashboard/Frontend GUI)
- localhost:5001 (KeyExchange (kex) GUI)

# A test user is already preconfigured:
Testuser:Test1234
