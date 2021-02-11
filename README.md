## About Laravel 7 Bikerent

Laravel 7 & admin LTE 3

## Installasi
- Download repository dan ekstrak atau clone repository
	```sh
	$ git clone https://github.com/denisuryadi26/bikerent.git
	```
- Masuk ke direktori aplikasi dan jalankan composer
	```sh
	$ cd C:\xampp\htdocs\bikerent
	$ composer install
	```
 - Copy file .env.example menjadi .env
	```sh
	$ cp .env.example .env
	```
- Generate key application
	```sh
	$ php artisan key:generate
	```
- Buat Database
- Edit database name, database username dan database password di file .env
    ```sh
	DB_DATABASE=your_db.
    DB_USERNAME=your_mysql_username.
    DB_PASSWORD=your_mysql_password.
	```
- Migrate table
	```sh
	$ php artisan migrate
	```
- Seed table
	```sh
	$ php artisan db:seed
	```
- Jalankan lokal development server
    ```sh
	$ php artisan serve
	```
- Buka di browser http://localhost:8000
- Login
    ```sh
	Username :  admin@admin.com
    Password :  password
	```

