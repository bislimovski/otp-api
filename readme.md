## Laravel PHP Framework

0. Clone the project and in terminal type >composer install

1. In config\database.php, you can select your database driver:
    default=sqlsrv

2. In .env, select your database connection settings and create new database
    DB_HOST=.\SQLEXPRESS
    DB_DATABASE=otp
    DB_USERNAME=
    DB_PASSWORD=

3. In database\2016_01_21_144014_create_sectors_table.php, you can add or remove fields, default:

    string('name');
    string('year');
    string('revenue')->nullable();

4. In terminal type:

    >php artisan migrate
    >php artisan serve

5. In app\HTTP\Controllers, you can see the CRUD controller:

    SectorsController.php

6. Basic route:

    http://localhost:8000/sectors

