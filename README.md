# Woox Travel

**Travel agency management system** - a full-stack web application built with Laravel. Visitors browse destinations and deals, book trips and pay online; admins manage the catalog and reservations from a dashboard.

![PHP](https://img.shields.io/badge/PHP-8.1-777BB4?logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-10-FF2D20?logo=laravel&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-database-4479A1?logo=mysql&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-UI-7952B3?logo=bootstrap&logoColor=white)

## Features

### Storefront
- Browse travel destinations with detail pages
- Deals page with search
- Reservation flow with **PayPal** payment
- User registration and login, with a "my bookings" page

### Admin Panel
- Dashboard with bookings overview
- Manage countries and cities
- Manage reservations
- Manage admin accounts

## Tech Stack

| Layer | Technology |
| --- | --- |
| Back-end | PHP 8.1, Laravel 10 |
| Database | MySQL |
| Front-end | Blade, Bootstrap, JavaScript |
| Payments | PayPal checkout |

## Getting Started

Requirements: PHP 8.1+, Composer, MySQL.

```bash
git clone https://github.com/Mohammedkatoun/WooxTravel.git
cd WooxTravel
composer install
cp .env.example .env
# set your database credentials in .env
php artisan key:generate
php artisan migrate
php artisan serve
```

- Storefront: `http://localhost:8000`
- Admin panel: `http://localhost:8000/admin/login`
