# Guitar Pedal Shop

This project is a web-based application built using the **Laravel** framework for managing a guitar pedal shop. It allows users to browse, search, and purchase guitar pedals. Additionally, administrators can add, update, and delete pedals, manage categories, and view customer orders.

## Table of Contents

- [Features](#features)
- [Technologies](#technologies)
- [Installation](#installation)
---

## Features

- **Browse Guitar Pedals**: View all available pedals.
- **Search Functionality**: Search for pedals by name, brand, or category.
- **Add to Cart**: Users can add pedals to their cart and checkout.
- **User Authentication**: Login and registration functionality for customers, supports OAuth 2.0 via Google/Facebook (might be broken due outdated developer API).
- **Admin Dashboard**: Manage pedals, categories, orders, and users. (Looks not great, but it works)
- **Order Management**: View customer orders and update their statuses.

## Technologies

- **Laravel**: PHP web application framework
- **MySQL**: Database management
- **Bootstrap**: Frontend framework
- **Blade**: Laravel templating engine
- **Composer**: PHP dependency management

## Installation

To install and run this project locally, follow these steps:

### Prerequisites

- PHP >= 8.0
- Composer
- MySQL or other supported databases

### Steps

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yourusername/guitar-pedal-shop.git
   cd guitar-pedal-shop

2. **Install dependencies**:
   ```bash
   composer install
3. **Environment setup**:
   Make sure to set up app name and db connection.
   ```bash
   cp .env.example .env
   php artisan key:generate
5. **Database migration**:
   ```bash
   php artisan migrate
   php artisan db:seed
6.  **Run the application**:
    ```bash
    php artisan serve
7. Visit http://localhost:8000 in your browser.
