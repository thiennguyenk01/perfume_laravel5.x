# 📦 Perfume Laravel 5.x

> A simple perfume e-commerce web application built with Laravel 5.x.

---

## 🚀 Introduction

**Perfume Laravel 5.x** is a basic e-commerce system developed using the Laravel framework.
The project focuses on core functionalities such as product management, category organization, and simple shopping features.

This project is suitable for learning **MVC architecture**, backend development, and Laravel fundamentals.

---

## 🛠️ Tech Stack

* **Backend:** PHP (Laravel 5.x)
* **Database:** MySQL
* **Frontend:** Blade Template, HTML, CSS, JavaScript
* **Server:** Apache / Nginx

---

## 📂 Project Structure

```bash
📦 perfume_laravel5.x
 ┣ 📂 app            # Business logic
 ┣ 📂 bootstrap      # Framework bootstrap
 ┣ 📂 config         # Configuration files
 ┣ 📂 database       # Migrations & seeders
 ┣ 📂 public         # Public assets
 ┣ 📂 resources      # Views (Blade templates)
 ┣ 📂 routes         # Web routes
 ┗ 📂 storage        # Logs & cache
```

---

## ⚙️ Installation

### 1. Clone project

```bash
git clone https://github.com/thiennguyenk01/perfume_laravel5.x.git
cd perfume_laravel5.x
```

### 2. Install dependencies

```bash
composer install
```

### 3. Create environment file

```bash
cp .env.example .env
```

### 4. Generate application key

```bash
php artisan key:generate
```

### 5. Configure database

Edit `.env` file:

```env
DB_DATABASE=your_database
DB_USERNAME=root
DB_PASSWORD=
```

### 6. Run migrations

```bash
php artisan migrate
```

### 7. Start development server

```bash
php artisan serve
```

👉 Access the application at: **http://localhost:8000**

---

## 🎯 Features

* 🛍️ Product listing (Perfumes)
* 📁 Category management
* ✏️ CRUD operations (Create, Read, Update, Delete)
* 🎨 Simple UI using Blade templates
* 🧩 MVC architecture (Route → Controller → Model → View)

---

## 📌 Future Improvements

* 🔐 User Authentication (Login / Register)
* 🛒 Shopping Cart & Checkout
* 💳 Payment Integration
* 🧑‍💼 Admin Dashboard
* 🔌 RESTful API (for frontend/mobile integration)

---
