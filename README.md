# Тестовое задание в команду Backend

## Задача
Необходимо создать сервис заказов. В рамках данного сервиса требуется реализовать 2 ручки:
1. Ручка создания заказа. На входе мы получаем информацию о пользователе и его выборе(корзине), нужно создать заказ, списать остатки, вернуть информацию о заказе.
2. Ручка листинга заказов. Здесь можно получить информацию об имеющихся заказов с пагинацией и сортировкой.

## Требования к коду
1. Язык разработки: PHP. 
2. Фреймворки и библиотеки можно использовать любые. (Мы используется в своих сервисах symfony - это будет плюсом)
3. Ограничений по системе хранения данных нет.
4. Из структур данных у нас минимально должны быть заказы/товары/пользователи
5. Взаимодействие с сервисом должено быть при помощи REST API или JSON RPC запросов
6. В рамках задачи требуется описать контракт взаимодействия с ручками в формате openapi
7. Простая инструкция для запуска
8. Валидация входящих данных
   

## Будет плюсом
Не обязательно, но в дополнении к заданию можно выполнить те или иные условия:
1. Написать юнит тесты.
2. Контейнеризация, хорошим решением будет поднять проект с помощью команды docker-compose up;
3. Архитектура сервиса описана в виде текста и/или диаграмм
4. Документация в виде структурированное описание методов сервиса.
