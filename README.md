<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>


# StoreOnMS7

Welcome to the StoreOnMS7 project! This is a comprehensive online store built using the Laravel framework, PHP, CSS, JavaScript, and HTML. It took 7 months to complete and is my first full project.

## Table of Contents

- Introduction
- Features
- Installation
- Usage
- Contributing
- License
- Contact

## Introduction

StoreOnMS7 is an online store platform designed to provide a seamless shopping experience for users and an efficient management system for administrators. The project includes features such as product browsing, shopping cart, order processing, and inventory management.

## Features

- User-friendly interface for browsing products
- Shopping cart functionality
- Order processing and payment integration
- Inventory management for administrators (Add, Delete, Update products)
- Sales analytics and reporting

## Installation

To get a local copy up and running, follow these simple steps:

1. **Clone the repository**
    ```bash
    git clone https://github.com/mosbahmessaoud/storeonms7.git
    cd storeonms7
    ```

2. **Install dependencies**
    ```bash
    composer install
    npm install
    ```

3. **Set up environment variables**
    ```bash
    cp .env.example .env
    php artisan key:generate
    ```

4. **Run migrations**
    ```bash
    php artisan migrate
    ```

5. **Serve the application**
    ```bash
    php artisan serve
    ```

## Usage

Once the application is running, you can access it at `http://localhost:8000`. Here are some basic usage instructions:

- **Browse Products**: Navigate through the product catalog and add items to your cart.
- **Manage Inventory**: Log in as an administrator to add, update, or delete products.
- **Process Orders**: Complete the checkout process to place an order.

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Your Name - ms7mosbah@gmail.com

Project Link: https://storeonms7.site
