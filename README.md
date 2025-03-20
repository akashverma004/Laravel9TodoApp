
## kinldy create a .env file by running the below command and add your credntials for mysql or pgsql.

cp .env.example .env

## install composer dependencies using command

composer update

## Migrate the database using command

php artisan migrate

## Run the project using command

php artisan serve
