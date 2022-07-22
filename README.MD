# PHP dev env \w docker

features:
- php 7.4
- composer
- git
- nginx
- mysql
- mysqladmin
- memcached
- redis 
- mongo

todo:
- rm nazarpc/phpmyadmin
- migrate to config version 3
- migrate to php 8

## Useful commands
Start docker
```
docker-compose up -d
```
Stop docker
```
docker-compose stop
```

Install symfony
```
docker-compose run --rm php composer create-project symfony/skeleton .
```

## Help
[Telegram chat](https://t.me/maksze_support)
