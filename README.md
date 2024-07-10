# Django E-commerce Platform

This project is an e-commerce platform built with Django, featuring user authentication, product management, shopping cart functionality, and order processing capabilities.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [File Structure](#file-structure)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The Django E-commerce Platform provides a robust set of functionalities to manage products, handle user authentication, facilitate shopping cart operations, and process orders. It includes features like Google OAuth integration, OTP-based login, bulk product upload, search and sorting capabilities, and email notifications for successful orders.

## Features


2. **Products Module**
   - CRUD APIs for managing products
   - Search and sorting using django-filter
   - Pagination with customizable page size

3. **Shopping Cart Module**
   - APIs for adding, removing, and updating cart items
   - Calculation of total cart amount

4. **Orders Module**
   - Order placement API with CRUD operations
   - Users can create, read, and delete orders; only admins can update orders
   - Atomic transactions to ensure data consistency during order processing

## Installation

### Prerequisites

- Python 3.10
- Django

### Installation Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/piyushkashyap07/Ecommerce_project.git
   cd ecommerce_test/


pip install -r requirements.txt

python manage.py migrate

python manage.py runserver


Contributing
Contributions are welcome! Please feel free to report issues, suggest new features, or submit pull requests.

License
This project is licensed under the MIT License. See the LICENSE file for details.
