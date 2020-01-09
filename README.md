# Docker for golang

## Prerequisites

- [docker latest](https://www.docker.com/)
- [docker-compose latest](https://docs.docker.com/compose/)
- your hands

### How to run

```shell
docker-compose up -d
```

### Some useful commands

#### Go to workspace directly

```shell
docker-compose exec -u laradock -w /var/www/learning-go workspace bash
```
