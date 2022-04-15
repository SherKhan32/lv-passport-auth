After Clone 

cp .env.example .env
composer update

php  artisan key:gen
php artisan migrate:fresh --seed

php artisan passport:install