[![Build Status](https://travis-ci.com/otus-devops-2019-02/nexsius_microservices.svg?branch=docker-3)](https://travis-ci.org/otus-devops-2019-02/nexsius_microservices)

# Nexsius_microservices
Nexsius microservices repository

# Docker-3

- Приложение разнесено на несколько компонентов
- Частично собраны образы на основе alpine linux
- В образы проброшены другие имена хостов через ключи --env докера
- Создан docker volume для БД

Размеры образов:

 nexsius/post          1.0                 97342888f264        5 minutes ago       116MB
 nexsius/test          1.0                 68857307acd8        32 minutes ago      148MB
 nexsius/ui            1.0                 a58c2d0100f1        2 hours ago         258MB
 nexsius/comment       1.0                 13134939ba43        2 hours ago         255MB

