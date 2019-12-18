# PHP dev env \w docker

features:
- php 7.2
- composer
- nginx
- mysql
- mysqladmin
- memcached

todo:
- rm nazarpc/phpmyadmin
- migrate to config version 3

## Useful commands
Start docker
```
docker-compose up -d
```

Install symfony
```
docker-compose run --rm php composer create-project symfony/skeleton .
```

## Help
[Telegram chat](https://t.me/maksze_support)
