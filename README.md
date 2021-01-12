# Docker

## Networks

```bash
docker network create www
docker network create --internal intranet
```

## Container

### Deployment
```bash
cd <folder>
touch .vim #put each var vom docker-compose into this file
docker-compose -p <container_name> up -d
