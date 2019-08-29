# node app using docker
Dockerizing Node App 

# Start
```
git clone https://github.com/loaikanou/node_app_docker.git
cd node_app_docker
docker build -t node-app-docker .
docker run -p 8000:8080 -d node-app-docker
```

# Check
- docker ps
