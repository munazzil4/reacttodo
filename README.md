# Getting Started
Clone the project by running the command below:

`git clone https://github.com/munazzil4/reacttodo`

then run:

`composer install --ignore-platform-reqs`

`npm install`

copy `.env.example` to `.env`

Fill db with local.

then run:

`php artisan key:generate`


now you can run migrations:

`php artisan migrate`

then start the application:

`php artisan serve`

and visit http://localhost:8000 to see the application.

