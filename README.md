# AndersenLab-PetProject-
## №1. microservice task
### Сервис 1
Задача сервиса собрать 50 страниц постов из открытого API - https://gorest.co.in/public/v1/posts
Собранные данные в несколько потоков и необходимо сохранять в бд (postgesql).
### Сервис 2
Сервис должен реализовать логику crud для собранных ранее постов:
- Возможность получить несколько постов.
- Возможность получить конкретный пост
- Возможность удалить пост
- Возможность изменить пост
### Сервис 3
  Сервис должен являться API Gateway и предоставить методы для выполнения операций сервиса 1 и сервиса 2.
- Запуск процесса сбора данных и возможности проверки окончания процесса
- Методы crud сервиса 2