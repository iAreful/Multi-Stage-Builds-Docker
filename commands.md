## Build image  single || fat || multistage 
```
docker build -t [image build name] ./
```


## check all images
```
docker images  or  docker image ls
```

## Run an Docker image with image ID
```
docker run -p 3000:3000  [image id]
```


## repository name change
```
docker image tag [selective repository imgage ID] [desire-image-name]:[desire tag]
```

## Run an Docker image with  repositoryb name {change if neeed [avobe cheack]}
```
docker run -p 3000:3000  [desire-image-name ]
```