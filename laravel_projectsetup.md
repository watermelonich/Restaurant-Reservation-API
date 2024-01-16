# Running a Laravel App in Terminal

## Navigate to Your Laravel Project

```bash
cd path/to/your/laravel/project
```

## Install Dependencies

Run the following command to install project dependencies using Composer:

```bash
composer install
```

## Create a Copy of the .env File

Laravel uses an environment file (.env) for configuration. Copy the example file:

```bash
cp .env.example .env
```

## Generate an Application Key

Generate the application key for encryption:

```bash
php artisan key:generate
```

## Configure the Database

Open the .env file and set up your database connection details (DB_HOST, DB_DATABASE, DB_USERNAME, DB_PASSWORD).

##  Run the Migration

To create database tables, run the migration command:

```bash
php artisan migrate
```

## Serve Your Application

Use Laravel's built-in development server:

```bash
php artisan serve
```

This will start the server. Visit `http://localhost:8000` (or another port specified in the output) in your web browser.

**Note:** The built-in server is not suitable for production. For production, consider using Apache or Nginx.
