### Linux permissions
```
docker-compose run --rm wordpress chown -R $(id -u):$(id -g) .
```