# docker-library_rabbitmq-599

https://github.com/docker-library/rabbitmq/discussions/599

## Start container

```
make up
```

## Run command

```
docker compose exec rabbitmq1 rabbitmqctl status
```

## Versions

```
$ docker version
Client:
 Version:           20.10.22
 API version:       1.41
 Go version:        go1.19.4
 Git commit:        3a2c30b63a
 Built:             Tue Dec 20 20:43:40 2022
 OS/Arch:           linux/amd64
 Context:           default
 Experimental:      true

Server:
 Engine:
  Version:          20.10.22
  API version:      1.41 (minimum version 1.12)
  Go version:       go1.19.4
  Git commit:       42c8b31499
  Built:            Tue Dec 20 20:42:46 2022
  OS/Arch:          linux/amd64
  Experimental:     false
 containerd:
  Version:          v1.6.14
  GitCommit:        9ba4b250366a5ddde94bb7c9d1def331423aa323.m
 runc:
  Version:          1.1.4
  GitCommit:
 docker-init:
  Version:          0.19.0
  GitCommit:        de40ad0

$ docker compose version
Docker Compose version 2.14.2
```
