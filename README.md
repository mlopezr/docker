# Red5 Media Server

Docker + Red5 items, forked from https://github.com/Red5/docker

### Installation

1. Install [Docker](https://www.docker.com/).

2. Build image from Dockerfile: `docker build -t red5-docker github.com/mlopezr/docker`


### Usage

 1. Starts red5 and exposes default ports for http and rtmp/e
```sh
    docker run -it -p 5080:5080 -p 1935:1935 --rm red5-docker
```

 1. Starts red5 and exposes default ports for http, rtmp/e, and websocket
```sh
    docker run -it -p 5080:5080 -p 1935:1935 -p 8081:8081 --rm red5-docker
```
    
### Additional Information

 * [Container linking](https://docs.docker.com/userguide/dockerlinks/)
 * [Managing data](https://docs.docker.com/userguide/dockervolumes/)
 

