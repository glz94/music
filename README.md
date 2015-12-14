# music
$ git clone https://github.com/phanan/koel && cd koel
$ composer install
$ vi .env # Fill in database and initial admin account
$ php artisan key:generate
$ php artisan migrate --force
$ php artisan db:seed --force
$ npm install
$ php artisan serve
$ Server started on http://localhost:8000/
