# Описание
Проект представляет собой API для проекта yatube.

Функционал: Авторизация по JWT токену

Сериализация данных для всех моделей проекта (Post, Comment, Group, Follow)

Обработка GET, POST, PATCH, PUT и DELETE запросов к базе данных проекта Yatube

Стек технологий
----------
* Python 3.8
* Django 2.2
* Django REST framework
* Pytest
* SQLite3
* CSS
* HTML

Установка проекта из репозитория
----------

1. Клонировать репозиторий и перейти в него в командной строке:
```bash
git clone git@github.com:ArtKeyplex/api_final_yatube.git

cd api_final_yatube

```
2. Cоздать и активировать виртуальное окружение:
```bash
python3 -m venv venv

source venv/bin/activate
```
3. Установить зависимости из файла ```requirements.txt```:
```bash
python3 -m pip install --upgrade pip

pip install -r requirements.txt
```
4. Выполнить миграции:
```bash
cd yatube_api

python3 manage.py migrate
```
5. Запустить проект (в режиме сервера Django):
```bash
python3 manage.py runserver
```
