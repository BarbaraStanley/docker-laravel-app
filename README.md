# docker-laravel-app
Write a dockerfile for the laravel app
write a docker compose file for the services involved in the laravel
Mount a volume to write
- a) a real time log entry
- b) mysql data
name these directories whatever you like

## Running locally
- clone this repo
- change environment variables to your preferences
- run `docker compose up -d`
- run `docker exec app php artisan migrate --seed`
