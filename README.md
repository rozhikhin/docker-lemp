
## Docker's command helpers

- Запуск контейнеров `docker-compose up -d --build`
- Остановка контейнеров `docker-compose down`
- Просмотреть логи `docker-compose logs --tail 25`

## Laravel command helpers


- Установка Laravel `composer global require laravel/installer`
- Localized Laravel `https://github.com/mcamara/laravel-localization`
- Widgets Laravel `https://github.com/arrilot/laravel-widgets`
- Translations in DB Laravel `https://github.com/Astrotomic/laravel-translatable`


composer create-project --prefer-dist laravel/laravel .

или

docker run --rm --interactive --tty
--volume $PWD:/app
composer --prefer-dist create-project laravel/laravel .


