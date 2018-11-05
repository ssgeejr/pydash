# pydash-docker
Portable docker image for a standalone pydash implementation


### Build the re-usable python image
```
    $ docker build -t pythonpip -f Dockerfile.python .
```

### Build the re-usable python image
```
    $ docker build -t sprintdash -f Dockerfile.txt .
```

### run pydash docker Image
```
    $ docker run --rm --name pydash -it --privileged=true --net=host --pid=host --ipc=host -p 9180:9180 sprintdash
```
	
	
