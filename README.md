composer create-project laravel/laravel first-project

php artisan serve

php artisan make:controller ViewController

php artisan make:mail EnrollConfirmationMail

php artisan make:model Product
php artisan make:model Product -m
php artisan migrate

php artisan migrate:rollback

php artisan make:middleware AdminMiddleware

php artisan migrate:fresh // remove cache file

php artisan make:migration create_flights_table // add table
php artisan make:migration add_password_column_to_teachers_table //add column

composer require laravel/jetstream
php artisan jetstream:install livewire











https://stackoverflow.com/questions/31935417/how-to-use-artisan-to-make-views-in-laravel-5-1
composer require theanik/laravel-more-command --dev
php artisan make:view index
