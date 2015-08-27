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

### Starting a web server on port 8080

```bash
$ docker run -d --name web-test -p 8080:8000 mattmahoneyrh/hello-world
```

Curl Exmaple
```
$ curl localhost:8080
Hello World
...

```
