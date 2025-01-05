# Frequently Used Commands

## Docker
```
$ docker system df
$ docker system prune --all --force
$ docker-compose images
$ docker-compose ps
$ docker-compose build --no-cache
$ docker-compose up -d
$ docker-compose exec app bash
$ docker-compose stop
$ docker-compose down --rmi all
```

## Python
``` python
$ python manage.py runserver
$ python manage.py check
$ python manage.py shell

# DB
# Modify model.py
$ python manage.py makemigrations APP_NAME
$ python manage.py migrate
```

## sqlite3
```
$ sqlite3 db.sqlite3
$ .tables
```