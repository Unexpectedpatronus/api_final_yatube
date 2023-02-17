# api_final

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone git@github.com:Unexpectedpatronus/api_final_yatube.git
```

```
cd api_final_yatube
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
```

```
source env/bin/activate
```

Установить зависимости из файла requirements.txt:

```
python3 -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python3 manage.py migrate
```

Запустить проект:

```
python3 manage.py runserver
```

### Примеры запросов к API:

Получить JWT-токен:

```
/api/v1/jwt/create/
```

Получение публикаций:

```
/api/v1/posts/
```

Частичное обновление комментария:

```
/api/v1/posts/{post_id}/comments/{id}/
```
