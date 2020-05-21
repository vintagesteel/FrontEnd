# FrontEnd
Docker training using a React app

Learning General Docker Commands

docker build -t waynegaskill/frontend:latest -f Dockerfile.dev . 
docker run -it -p 3000:3000 -v $(PWD):/app CONTAINER_ID 
docker exec -it CONTAINER_ID sh
