# software-irrigation
Hosting for the software irrigation team

# How to run
Install Laravel using Composer and run XAMPP with apache and mysql server

Create a new laravel project and merge with github repo

At http://localhost/phpmyadmin/ create a database called irrigation or other specified name

In the .env file set DB_DATABASE value to irrigation or other name, DB_USERNAME to root or other username, and DB_PASSWORD to specified password for username root or leave blank if not set

Run "php artisan migrate" in project directory to create user login tables in irrigation database

Run "php artisan serve" to start development server 
