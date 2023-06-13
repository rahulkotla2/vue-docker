# vue-docker

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Containerize Project
###### Build the Image
```
docker build -t docker-app .
```
######  Create the Using image
```
docker run -d --name docker-app -p 8080:80 docker-app
```

### Requirements
```
NodeJS
Vue CLI
Docker for Desktop
NGINX (need to install inside docker)
```

