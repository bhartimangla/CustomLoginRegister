# CustomLoginRegister
Laravel Custom Login Register functionality. It's developed on the Laravel 5.8, On this Custom Login Register we can register, login any user logout also.

Database name - customLoginRegister

After clone repository from github-
Instrall composer & PHP >= 7.1.3 version

Run Composer update

Create copy of .env.example with name .env

This is your environment file which is required by laravel project

Open .env file and update this file with your MySQL Connection credentials

After that run the following command-

php artisan key:generate

php artisan config:cache

After that run your migration commands

php artisan migrate

Now Run your project with the following command-

php artisan serve --host 0.0.0.0 --port 8000

