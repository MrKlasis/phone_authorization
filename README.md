# Сервис авторизации по номеру телефона

Данное тестовое задание выполнено с использованием следующего стека технологий:
- Phyton 3
- Django 4 
- Django REST Framework 3 - 
- PostgreSQL 

# Запуск проекта

Для запуска проекта необходимо:

    1. Создать базу данных для использования в приложении.
    2. В корневой директории проекта создать файл .env в котором указать данные для доступа к серверу базы данных:
        
        SECRET_KEY=

        POSTGRES_DB=
        POSTGRES_USER=
        POSTGRES_PASSWORD=

    3. Создать и активировать виртуальное окружение проекта.(опционально)
    4. Установить зависимости используемые в проекте из файла requirements.txt(pip install -r requirements.txt)
    5. Применить имеющиеся миграции к базе данных.(python3 manage.py migrate)
    6. Запустить сервер (python3 manage.py runserver)

# Примечание

    Коллекция запросов Postman coхранена в виде файла diplom.postman_collection.json находящегося в корне проекта.
    
