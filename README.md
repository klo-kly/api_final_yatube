# API для Yatube

## Описание
##### Это полноценный API для проекта социальной сети, в котором реализованы следующие функции:
- Получение информации о посте; создание, редактирование и удаление поста
- Получение информации о комментарии; создание, редактирование и удаление комментария
- Получение информации о сообществах
- Подписка и просмотор подписанных авторов

Полный список методов представлен по адресу http://localhost:8000/redoc/


## Установка
Клонируем репозиторий.
```sh
$ git clone https://github.com/github_username/api_final_yatube.git
```
Создаем и активируем виртуальное окружение.
```sh
$ python -m venv venv
$ source venv/scripts/activate
```
Устанавливаем зависимости.
```sh
$ pip install -r requirements.txt
```
Создаем и применяем миграции.
```sh
$ python manage.py makemigrations 
$ python manage.py migrate
```
Запускаем локальный сервер.
```sh
$ python manage.py runserver
```
Адрес локального сервера:
```sh
127.0.0.1:8000
```
## Примеры

Для формирования запросов будет использована программа `Postman`.

![Создание нового пользователя](https://github.com/klo-kly/pictures/blob/master/API_YATUBE/create_post.jpg)

![Получение токена для аутентификации](https://github.com/klo-kly/pictures/blob/master/API_YATUBE/create_post.jpg)

![Создание нового поста](https://github.com/klo-kly/pictures/blob/master/API_YATUBE/create_post.jpg)



**Приятного использования**
