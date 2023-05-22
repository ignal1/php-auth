**[Demo](http://84.38.180.229:88)**

**Учетные данные для входа в систему**

логин: `1`  
пароль: `1`

## Используемые технологии

- PHP

- JavaScript

## Реализовано

- сообщение о неправильном логине/пароле

- авторизация без перезагрузки системы

- после успешного входа в систему сообщение. Исчезает через 10 секунд + анимация

- адаптивная верстка

- одновременная поддержка нескольких сессий

- после третьей подряд попытки ввести неверный пароль, акаунт блокируется на час, о чем выводится сообщение

- пароли хешируются

- созданы дополнительные индексы в БД

## Запуск проекта

`index.php`

Перед запуском приложения необходимо создать базу данных MySQL с именем **php-auth**, пользователем **root** без пароля и загрузить в нее данные из файла dump.sql
