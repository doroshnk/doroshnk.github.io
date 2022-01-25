# README

#### Добавить себя в группу docker
```bash
$ sudo gpasswd -a USERNAME docker
```

#### Собрать и запустить
```bash
$ docker-compose up -d
```
#### Запустить и пересобрать
```bash
$ docker-compose up -d --build
```
#### Остановить
```bash
$ docker-compose down
```

#### Композер
```bash
$ docker exec -it local.partners_catalog.php-fpm composer install
```
