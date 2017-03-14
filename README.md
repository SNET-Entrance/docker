# User guide:
This folder conatins all you need to setup Entrance using Docker 
Tested on Unbuntu 16.04. with:
- docker version 17.03.0-ceer (community edition)
- docker-compose version 1.11.2,

# build the docker containers with:
sudo docker-compose build

# Start the docker conatiners with:
sudo docker-compose up -d

# Get the log
sudo docker-compose logs -f

# Optional jump into the "frontend" or "kex" container:  

sudo docker-compose exec frontend /bin/bash 
# or 
sudo docker-compose exec kex /bin/bash 

