# TestCur

Тестовое задание
Необходимо реализовать сервис со следующим функционалом на языке C# с использованием .NET 8.
Требования
В базе данных Postgres должны быть таблицы
1) currency:
● id — первичный ключ
● name — название валюты
● rate — курс валюты к рублю
2) user
● id — первичный ключ
● name — имя пользователя
● Password - пароль
Пользователь интересуется только определенным набором валют (favorites)
Задачи:
0) Используем Clean Architecture. С или без DDD, непринципиально.
1) Реализовать микросервис миграции БД
2) Реализовать фоновый сервис, который обращается по адресу http://www.cbr.ru/scripts/XML_daily.asp и полученными данными заполняет таблицу currency
3) Реализовать микросервис юзера. Нужный функционал – регистрация юзера, логин, логаут
4) Реализовать микросервис финансов. Нужный функционал – получить курс валют по юзеру.
5) Реализовать авторизацию с помощью JWT.
6) Реализовать API Gateway для обоих микросервисов.
7) Проект с unit-тестами для сервисов юзера и финансов. Для фонового не надо.
8) Бонусная. Показать умение работать с Grpc, идеально если в паре с JWT
Требования к присылаемым решениям
1. Готовые задания должны быть переданы в zip архиве или ссылкой на гитхаб
2. Исходный код должен компилироваться средствами MSVS 2022.
3. В архиве не должно быть неиспользуемых исходных кодов, ресурсов или
промежуточных файлов сборки.
