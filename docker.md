# Docker

## Images
List images:
```docker images```

Remove images:
```docker image rm [IMAGE ID]```

## Build images
```docker build --tag myApp:0.0.1 .```


## Containers
Run a container:
```docker run [CONTAINER NAME] [IMAGE ID]:[IMAGE TAG]```

View all containers:
```docker container ls --all```

Stop container:
```docker container stop [CONTAINER ID]```


Remove containers:
```docker container rm [CONTAINER ID]```


## Environment variables
``` docker build --build-arg SECRET=loljk
