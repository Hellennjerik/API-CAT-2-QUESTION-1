# E-Commerce Customer and Order Management

This project provides a simple Django-based system to manage customers and their orders. 

## Features

- **Customer Model**: Stores basic customer information (name and email).
- **Order Model**: Tracks orders placed by customers with the order date and total amount.
- **Database Relationships**: A one-to-many relationship where a customer can place multiple orders, but each order is linked to only one customer.

## Technologies Used

- **Django** - A high-level Python web framework for building web applications.
- **SQLite** (default) - Database backend for storing customer and order information. You can configure a different database if needed.
- **Django ORM** - Object-relational mapping for interacting with the database.

## Setup Instructions

### Prerequisites

- Python 3.x
- `pip` for installing dependencies
- Basic knowledge of Django and its architecture


