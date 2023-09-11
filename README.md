# Tutorial

https://nodejs.org/en/docs/guides/nodejs-docker-webapp

## Script

```
docker build . -t awsk1994/node-web-app
docker run -p 49160:8080 -d awsk1994/node-web-app
```

```
# Get container ID
$ docker ps
# Print app output
$ docker logs <container id>
# Example
Running on http://localhost:8080
```

```
GET localhost:49160/
> Hello World
```
