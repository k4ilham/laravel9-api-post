composer create-project laravel/laravel:^9.0 laravel9-api
php artisan serve
db_laravel9_api_post
php artisan make:model Post -m
php artisan storage:link
php artisan make:resource PostResource 
php artisan make:controller Api/PostController
php artisan route:list