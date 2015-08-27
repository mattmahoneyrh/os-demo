Hello World
===========

Based on: crccheck/docker-hello-world

This is a simple image that just gives a response on port 8000.

```bash
$ docker images | grep hell
REPOSITORY               TAG       IMAGE ID        CREATED          VIRTUAL SIZE
mattmahoneyrh/hello-world <>         <>             <>                 <>
```

Sample Usage
------------

### Build image

```bash
$ build.sh
```

### Start container

```bash
$ docker run -d --name os-demo -p 8080:8000 mattmahoneyrh/hello-world
```
### Starting web server on port 8080

Curl Exmaple
```
$ curl localhost:8080
Hello World
...

```
