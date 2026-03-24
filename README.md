# Authentication Project

A Laravel-based authentication system built as part of the BSc Computing Systems degree at Ulster University.

## About

This project implements a full user authentication system using the Laravel PHP framework, including user registration, login, logout, and protected routes.

## Technologies Used

- **PHP** / **Laravel** (Backend framework)
- **Blade** (Laravel templating engine)
- **MySQL** (Database)
- **Vite** (Frontend asset bundler)
- **HTML / CSS / JavaScript** (Frontend)

## Features

- User Registration
- User Login & Logout
- Password Hashing & Security
- Protected/Authenticated Routes
- Session Management

## Project Structure

```
app/          - Controllers, Models, Middleware
config/       - Application configuration
database/     - Migrations and seeders
public/       - Publicly accessible assets
resources/    - Blade views, CSS, JS
routes/       - Web and API route definitions
storage/      - Logs and cached files
```

## Setup Instructions

```bash
# Clone the repository
git clone https://github.com/Mainul009/authentication.git

# Install PHP dependencies
composer install

# Install Node dependencies
npm install

# Copy environment file
cp .env.example .env

# Generate application key
php artisan key:generate

# Run migrations
php artisan migrate

# Start development server
php artisan serve
```

## Author

**Mainul Islam Tasin**
BSc Computing Systems, Ulster University (2nd Year)

- LinkedIn: [mainul-islam-tasin-849072361](https://www.linkedin.com/in/mainul-islam-tasin-849072361)
- GitHub: [Mainul009](https://github.com/Mainul009)
