 #Шаблон проекта Symfony

#Getting started
##dev
1. `HTTP_PORT=<HTTP_PORT> docker compose up --build`

#production
2. `HTTP_PORT=<HTTP_PORT> docker compose -f docker-compose.yml up --build`

###линкз
* Приложение https://github.com/symfony/demo
* Docker образ https://github.com/dunglas/symfony-docker

## Фичерс

* nginx 😂
* php 8.2 🤠
* alpine 🥵
* mysql 🥱
* сумфони 6 🤩

#cs fix:

if нот сделано 

`composer require --working-dir=tools/php-cs-fixer friendsofphp/php-cs-fixer`

then выполнить

`tools/php-cs-fixer/vendor/bin/php-cs-fixer fix src`