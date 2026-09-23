# Auto-spare-Zone
A responsive Auto Spare Parts Management System developed using PHP, MySQL, HTML, CSS, and JavaScript.
# Auto Spare Zone

## Overview

Auto Spare Zone is a web-based automobile spare parts management system developed using PHP and MySQL. The system allows customers to browse spare parts, manage their shopping cart, and place orders, while administrators can manage products, categories, customers, and orders.

## Features

### Customer
- User Registration and Login
- Browse Spare Parts
- Search Products
- View Product Details
- Add to Cart
- Place Orders
- View Order History
- Update Profile

### Admin
- Secure Admin Login
- Dashboard
- Manage Categories
- Manage Products
- Manage Customers
- Manage Orders
- Update Product Stock

## Technologies Used

- PHP
- MySQL
- HTML5
- CSS3
- JavaScript
- Bootstrap

## Software Requirements

- XAMPP / WAMP
- PHP 8.x
- MySQL
- Apache Server

## Database

Import the provided SQL file into phpMyAdmin.

Database Name:
```
auto_spare_zone
```

## Installation

1. Clone the repository.

```bash
git clone https://github.com/yourusername/auto-spare-zone-php.git
```

2. Copy the project folder into the `htdocs` directory.

3. Start Apache and MySQL in XAMPP.

4. Import the SQL database using phpMyAdmin.

5. Update database credentials in the configuration file.

Example:

```php
$host = "localhost";
$user = "root";
$password = "";
$database = "auto_spare_zone";
```

6. Open the project in your browser.

```
http://localhost/auto-spare-zone-php/
```

## Project Structure

```
Auto-Spare-Zone/
│
├── admin/
├── customer/
├── images/
├── css/
├── js/
├── database/
│   └── auto_spare_zone.sql
├── includes/
├── config.php
├── index.php
├── login.php
├── register.php
├── cart.php
├── checkout.php
└── README.md
```

## Future Enhancements

- Online Payment Gateway
- Email Notifications
- Product Reviews
- Wishlist
- Invoice Generation
- Sales Reports

## Author

**Dinesh V**

MCA Student

Aspiring Software Developer
