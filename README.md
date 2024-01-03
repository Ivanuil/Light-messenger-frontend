## Light-messenger

### About

Light-messenger это простой мессенджер использующий Kafka и WebSocket для доставки сообщений.

<img src="misc/images/main_page.png" alt="Main page" width="350"/>

<img src="misc/images/log_in_page.png" alt="Log in page" width="350"/>

<img src="misc/images/chat_page.png" alt="Chat page" width="350"/>

Благодаря использованию WebSocket пользователь получает сообщения без обновления страницы.
Но отправка сообщений также возможно через Http запрос.

Фронтенд сервиса в [репозитории](https://github.com/Ivanuil/Light-messenger-frontend).

### Stack

* HTML
* JavaScript

### How to run

1. Запустить бэкенд сервер (https://github.com/Ivanuil/Light-messenger-backend)

2. Запустить NodeJs сервер (```docker compose up``` в корне проекта)

3. Домашняя страница будет доступна по адресу http://127.0.0.1/

**Необходимо обращаться к фронтенд серверу как 127.0.0.1, а не localhost. Иначе Cookie файлы не будут сохранятся 
браузером** 
