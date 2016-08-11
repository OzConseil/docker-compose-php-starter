# Docker compose starter

## Database
Put a sql dump in `data/sql`.

`/var/lib/mysql` from container is persisted in `data/db`.

## Web server Apache and php 5.6
Document root is in `web/` via `html/` link.
`php.ini` is in `conf/php/php.loc.ini`.

`docker-compose up` then http://localhost:8080

## Composer
`./bin/composer`
