# Simple docker symfony

## Init project

Launch container

```bash
docker compose up
```

Get bash shell in the container

```bash
docker exec -it www_symfony_test /bin/bash
```

Run composer install or composer update
```bash
cd project
composer update (or install)
```
