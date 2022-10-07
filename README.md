### Описание:
Проект «API для Yatube» позволяет использовать взаимодействие через API с полюбившейся всем социальной сетью для публикации личных дневников.

### Установка:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone git@github.com:ts-danil/api_final_yatube.git
```

```
cd api_final_yatube
```

Cоздать и активировать виртуальное окружение:

```
python -m venv venv
```

```
source venv/Scripts/activate
```

Установить зависимости из файла requirements.txt:

```
python -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python manage.py migrate
```

Запустить проект:

```
python manage.py runserver
```

### Примеры запросов к API:

После запуска проекта по адресу http://127.0.0.1:8000/redoc/ будет доступна документация для API Yatube с примерами запросов и ответов.