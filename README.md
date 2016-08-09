# Docker compose starter

## Database
Put a sql dump in `data/sql`.

`/var/lib/mysql` from container is persisted in `data/db`.

## Web server Apache and php 5.6
Document root is in `web/` via `html/` link.

`docker-compose up` then http://localhost:8080

## Composer
`./bin/composer create-project drupal-composer/drupal-project:8.x-dev ./ --stability dev --no-interaction`
