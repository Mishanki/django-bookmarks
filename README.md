# Django 4: Personal education (bookmarks)


## Виртуальное окружение

#### Создать venv
```bash
python3 -m venv env
```

#### Активировать venv
```bash
source env/bookmarks/bin/activate
```

## Django 4

#### Установка
```bash
pip install Django~=4.1.0
```

#### Зависимости
```bash
pip install -r requirements.txt
```

#### Версия
```bash
python -m django --version
```

#### Запуск сервера разработки
```bash
python manage.py runserver
или
python manage.py runserver 127.0.0.1:8001 --settings=mysite.settings
```

#### Создание проекта
```bash
django-admin startproject bookmarks
```

#### Создание приложения
```bash
python manage.py startapp account
```

## Миграции

#### Создать миграцию
```bash
python manage.py makemigrations account
```

#### Проинспектировать исходный код SQL
```bash
python manage.py sqlmigrate account 0001
```

#### Запуск миграций
```bash
python manage.py migrate
```

## Пользователи

#### Создать суперпользователя
```bash
python manage.py createsuperuser
```


## Работа через shell

#### Открыть оболочку Python
```bash
python manage.py shell
```