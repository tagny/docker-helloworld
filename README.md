# docker-helloworld

![Docker Pulls](https://img.shields.io/docker/pulls/karthequian/helloworld.svg) ![Automated Builds](https://img.shields.io/docker/automated/karthequian/helloworld.svg) ![Build Status](https://img.shields.io/docker/build/karthequian/helloworld.svg )

A simple helloworld app for docker

A simple nginx helloworld application that helps you learn docker image pulls. Runs on port :80

To pull this image:
```
docker pull karthequian/helloworld:latest
```

To run this image:
```
docker run -p 80:80/tcp "karthequian/helloworld:latest"

docker run -v /opt/srv -p 8080:80 --name docker-helloword --rm tagny/docker-helloworld:1.0

docker run -v /opt/srv -P --name docker-helloword --rm tagny/docker-helloworld:1.0 &
```

To execute commands
```
docker exec -it docker-helloworld sh
```

Dockerhub link: https://hub.docker.com/r/karthequian/helloworld/

Github link: https://github.com/tagny/docker-helloworld
