# Description

# Todo

# Commands

## Build docker image
```
docker build -t ionic-dev .
```

## Run docker container
Windows
```
docker run -it --name travel -p 8100:8100 -p 35729:35729 -p 5554-5559:5554-5559 -v %cd%:/app --privileged ionic-dev
```
Unix
```
docker run -it --name travel -p 8100:8100 -p 35729:35729 -p 5554-5559:5554-5559 -v ${pwd}:/app --privileged ionic-dev
```

## Update ionic inside of container
```
docker exec -it travel npm install -g @ionic/cli
docker exec -it travel npm install -g @ionic
```

## Create new ionic project inside container
```
docker exec -it travel ionic start . --type vue
```

## Launch mobile preview of app
```
docker exec -it travel ionic serve --lab
```

## Build www production files
```
docker exec -it travel ionic build --prod
```