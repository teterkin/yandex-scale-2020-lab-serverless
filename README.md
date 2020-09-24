# yandex-scale-2020-lab-serverless
Сокращатель ссылок aka URL shortener example for Yandex Scale 2020 workshop (Serverless).


Практическая лабораторная работа предполагает использование следующих сервисов Yandex.Cloud:
* Object Storage
* API gateway
* Cloud Functions
* Yandex Database.


# Требуемое окружение

Все работы мы будем проводить в Яндекс.Облаке (https://cloud.yandex.ru/);
У вас уже есть облако и каталог, войдите, пожалуйста с выданными логином и паролем.



Для работы нам понадобится:

* консоль https://console.cloud.yandex.ru/

* текстовый редактор (textedit, vim, etc)

* браузер.


# Шаги 
1. Создаем страницу index.html 
2. Создаем бакет в S3, помещаем туда страницу
3. Создаем сервисный аккаунт, навешиваем роль editor.
4. Создаем API gateway
5. Создаем логику сокращения ссылки: создаем публичную функцию, редактируем gw (добавляем в него функцию), проверяем сокращение
6. Создаем базу данных Yandex Database Serverless, создаем таблицу links в БД
7. Правим фукнцию сокращатель (правим код, добавляем переменные окружения), проверяем.

