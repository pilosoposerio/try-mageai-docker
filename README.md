# try-mageai-docker
An overpowered MageAI dockerized local development environment

## Containers

- one instance for the web server
- one instance for the scheduler
- one Redis instance
- one Postgres instance

## How to Create Environment

```bash
docker compose -f docker/docker-compose.yml up
```

## How to Destroy Environment

```bash
docker compose -f docker/docker-compose.yml down
```

