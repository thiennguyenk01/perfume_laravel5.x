📦 Perfume Laravel 5.x

A simple e-commerce web application for selling perfumes, built with Laravel 5.x.

🚀 Introduction

This project is a basic perfume shop system developed using Laravel framework. It provides features for managing products, categories, and basic shopping functionality.

Laravel is a powerful PHP framework that simplifies common web development tasks like routing, database handling, and authentication .

🛠️ Tech Stack

Backend: PHP (Laravel 5.x)

Database: MySQL

Frontend: Blade Template, HTML, CSS, JavaScript

Server: Apache / Nginx

📂 Project Structure
app/            # Business logic
bootstrap/      # Framework bootstrap
config/         # Configuration files
database/       # Migrations & seeders
public/         # Public assets
resources/      # Views (Blade templates)
routes/         # Web routes
storage/        # Logs & cache
⚙️ Installation
1. Clone project
git clone https://github.com/thiennguyenk01/perfume_laravel5.x.git
cd perfume_laravel5.x
2. Install dependencies
composer install
3. Create environment file
cp .env.example .env
4. Generate app key
php artisan key:generate
5. Configure database

Edit .env:

DB_DATABASE=your_db
DB_USERNAME=root
DB_PASSWORD=
6. Run migration
php artisan migrate
7. Start server
php artisan serve

Access: http://localhost:8000

🎯 Features

Product listing (Perfumes)

Category management

Basic CRUD operations

Simple UI with Blade

MVC architecture (Route → Controller → Model → View)

📸 Screenshots

(Add your project screenshots here)

📌 Future Improvements

User authentication (Login/Register)

Shopping cart & checkout

Payment integration

Admin dashboard

REST API

🤝 Contributing

Contributions are welcome!

Fork this repository

Create new branch (feature/your-feature)

Commit your changes

Push and create Pull Request
