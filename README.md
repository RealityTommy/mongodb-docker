# mongodb-docker
## Prerequisites
- [ ] [Docker](https://www.docker.com/)
- [ ] [MongoDB for VS Code](https://code.visualstudio.com/docs/azure/mongodb)
## How to Set Up
1. Pull the MongoDB Docker Image
```
docker pull mongodb/mongodb-community-server:latest
```
2. Run the Image as a Container
```
docker run --name mongodb -p 27017:27017 -d mongodb/mongodb-community-server:latest
```
3. Connect to the MongoDB Deployment with mongosh
```
mongosh --port 27017
```
4. Connect to the database with MongoDB for VS Code.