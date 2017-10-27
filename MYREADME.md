### How to install local

1) clone
2) copy .env.example -> .env
    php artisan key:generate
    databasename => fireflyiii_contr
3) run php artisan:discover
4) create database: fireflyiii_contr
5) php artisan migrate:refresh --seed
6) Run this ```wget -q https://github.com/firefly-iii/test-data/raw/master/storage/database.sqlite -O storage/database/database.sqlite```
7) php artisan serve
8) register an account and done