# video-backend
Repository for NodeJS REST application example.

This application creates a CRUD REST API for storing Videos on Mongodb.

Technology: NodeJS + Express + Mongodb.

## Mongodb deployment
```
docker pull mongo
docker run -d -p 27017:27017 --name video-backend-mongo mongo
```

## Application deployment
```
docker build -t video-backend-app .
docker run -it -p 2000:2000 video-backend-app
```
