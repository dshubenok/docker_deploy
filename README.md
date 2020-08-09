# YaMDB

Сервис с отзывами о фильмах, книгах и музыкальных произведениях

## Установка

Установите докер: https://www.docker.com/products/docker-desktop

Соберите приложение:

```
docker-compose build
```

Выполните миграции

```
docker-compose exec -it bash
python manage.py migrate
```

Заполните базу тестовыми данными: 

```
docker-compose exec -it bash
python manage.py loaddata fixtures.json
```

## Запуск

Выполните команду для запуска приложения:

```
docker-compose up
```
