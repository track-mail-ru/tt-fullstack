# Домашнее задание

- Ознакомиться с документацией по ссылке
   - [Docker](https://docs.docker.com/get-started/)
   - [Sentry для react приложений](https://docs.sentry.io/platforms/javascript/react/)
- Добавить докер
   - Делать сборку в контейнере (Dockerfile + docker-compose.yml)
   - Раздавать статику из контейнера
   - Докерфайл разбить на этапы: сборка, раздача
- Добавить в приложение `Sentry`

## Срок: 10 мая

При сдаче необходимо убедиться:

`docker-compose up -d` производит сборку фронтового контейнера и на выходе отдает легковесный контейнер с любым веб сервером (nginx), который раздает статику.

При возникновении ошибок на фронте, данные данные логгируются в `Sentry`

## Успехов!