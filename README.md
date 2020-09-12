# docker-gollum
A container running Gollum. A git-based wiki.

[Docker Hub](https://hub.docker.com/repository/docker/protosolutions/gollum)
```
# docker pull protosolutions/gollum:latest
# docker run -v -p 8000:80 protosolutions/gollum:latest
# docker run -v -p 8000:80 `pwd`:/wiki protosolutions/gollum:latest
# docker run -v -p 8000:80 `pwd`:/wiki -d protosolutions/gollum:latest
```
