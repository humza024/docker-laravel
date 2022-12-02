Run the following commands:-

cp .env.example .env

change your db name , pass , IP and database host to db.

docker run --rm -v $(pwd):/app composer install

sudo chown -R $USER:$USER ~/docker-laravel

sudo chown -R www-data.www-data storage

sudo chown -R www-data.www-data /bootstrap/cache

sudo docker-compose up -d

docker-compose exec app bash

php artisan key:generate

php artisan config:cache

Access:- http://IP or localhost

For already created project database migration , create user , database , privilges.

> php artisan storage:link

> php artisan migrate:fresh --seed

