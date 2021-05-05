# node-docker
### Build Docker local development environment
    docker-compose -f docker-compose.yml -f docker-compose.dev.yml up --build 
### Build Docker local production environment
    docker-compose -f docker-compose.yml -f docker-compose.prod.yml --build -t bongthorn/node-app
