# agentile.dev

## Usage

```sh
docker-compose pull
docker-compose \
--env-file .env.local \
-f docker-compose.yml \
-f docker-compose.local.yml \
up --build --detach
```

```sh
docker-compose \
--env-file .env.local \
-f docker-compose.yml \
-f docker-compose.local.yml \
down
```
