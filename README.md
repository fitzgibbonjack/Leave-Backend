# Leave - API

## Requirements

-   Docker

## Running the application locally

-   Duplicate .env.example file and call it .env
-   Update .env file
    -   Database credentials
-   Run `docker-compose up -d`
-   Laravel
    -   `docker-compose exec app composer install`
-   Database
    -   create local database named `leave`
    -   `docker-compose exec app php artisan migrate:fresh --seed`
-   Visit the local url specified in [access](#access) section

## Access

| Environment |                    URL                    |
| ----------: | :---------------------------------------: |
|       Local | https://leave-api.local.designbysweet.com |
| Development |                    tbc                    |
|  Production |                    tbc                    |
