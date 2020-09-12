# docker-gollum
A container running Gollum. A git-based wiki.

[Docker Hub](https://hub.docker.com/r/protosolutions/gollum)
```
# docker pull protosolutions/gollum:latest
# docker run -p 8000:80 protosolutions/gollum:latest
# docker run -p 8000:80 -v `pwd`:/wiki protosolutions/gollum:latest
# docker run -p 8000:80 -v `pwd`:/wiki -d protosolutions/gollum:latest
```

Don't forget to make sure the directory you present with `-v` is a git repository. You can just run `git init /path/to/directory` to initialize a fresh repo.
