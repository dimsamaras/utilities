# Stop / remove all Docker containers

```sh
docker stop $(docker ps -a -q)

docker rm $(docker ps -a -q)
```

# Docker housekeeping
### details: 
https://docs.docker.com/config/pruning/

### the juice:
```sh
docker system prune
```