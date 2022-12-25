# Проект «API для Yatube»
## **Описание** <br>
  
API для Yatub представляет собой проект социальной сети в которой реализованы следующие возможности:

### С помощью API для Yatube можно:
* работать с публикациями:
  * получать список всех публикаций
  * создавать (обновлять, удалять) публикации

* работать с комментариями к публикациям:
  * добавлять (получать, обновлять, удалять) комментарии

* Получать список сообществ
* Подписываться на пользователей
* Получать и обновлять JWT-токены

### **Технологии** <br>

Python 3.7, Django 3.2, DRF, JWT + Djoser

### **Запуск проекта**
>***Клонируйте репозиторий*** и 
>***Создайте виртуальное окружение:***
>
    python -m venv venv
    Source venv/Scripts/activate
>***Установите все зависимости:***
>
    pip install -r requirements.txt
>***Сделайте миграции и создайте пользователя:***
>
    python manage.py migrate
    python manage.py createsuperuser
>***Запуск проекта:***

    python manage.py runserver
    
__Полный функционал с примерами доступен по адресу__   
__http://127.0.0.1:8000/redoc__  
__(Будет доступен поле запуска проекта)__
