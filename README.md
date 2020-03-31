# Data Science Project Template

## To start new Data Science project:

1. Copy the repo

2. Start containers

```
docker-compose up
```
3. Stop containers

```
docker-compose down
```

4. Update images
```
docker-compose build --pull
```

5. Clean Docker's mess

```
docker rmi -f $(docker images -qf dangling=true)
```

Sometimes it is useful to remove all docker's data.

```
docker system prune
```
