## Docker

### Delete all docker containers
 
 ```bash
 docker rm `docker ps --no-trunc -aq`
```

### Delete all docker images

 ```bash
 docker rmi -f $(docker images -q)
```

