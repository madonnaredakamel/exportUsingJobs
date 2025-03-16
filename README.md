# ExportUsingJobs

## Description
this is a repo which show how to export huge data into csv file using jobs in laravel

## Features
- Fully responsive design with Bootstrap.
- Export huge data from table using jobs to limit the time 
- Send the downloaded file into  email notifications.

## Installation

1. Clone the repository:
   ```bash
   https://github.com/madonnaredakamel/exportUsingJobs.git
2. Navigate to the project directory:

cd exportUsingJobs


3.Install dependencies:
composer install

4.  Set up the environment file
cp .env.example .env

   
5. Generate the application key:
php artisan key:generate

6. Configure database settings in the .env file:
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=queues
DB_USERNAME=root
DB_PASSWORD=yourpassword

7. Run database migrations and seed data:
php artisan migrate --seed


8. Start the development server:

php artisan serve





