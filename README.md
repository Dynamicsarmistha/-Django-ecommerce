# Django E-commerce Website

A full-stack e-commerce web application developed using Python and Django. The project provides product browsing, shopping cart, checkout, order management, stock validation, and payment integration functionality.

## Project Overview

This project demonstrates the development of an e-commerce application using Django for backend development and HTML, CSS, and JavaScript for the frontend.

The application includes:

- Product listing and product details
- Product categories and brands
- Shopping cart management
- Checkout and order processing
- Customer information management
- Product stock validation
- Discount, shipping, tax, and total calculations
- Razorpay payment integration
- Payment and order record management
- Backend API endpoints
- Automated Django tests

## Technologies Used

- Python
- Django
- Django ORM
- SQLite
- HTML5
- CSS3
- JavaScript
- Razorpay API
- Git
- GitHub

## Key Features

### Product Management

- Display products
- Product details
- Categories
- Brands
- Stock quantity management

### Shopping Cart

- Add products to cart
- Update product quantity
- Remove products from cart
- Calculate cart totals
- Validate available stock

### Checkout and Orders

- Customer information
- Order creation
- Order item management
- Subtotal calculation
- Discount calculation
- Shipping calculation
- Tax calculation
- Final order total
- Stock quantity update after order creation

### Payment Integration

Worked on backend integration with the Razorpay payment gateway.

The project includes payment-related backend logic and payment/order record management.

> Razorpay payment functionality requires valid test credentials and proper local configuration.

## My Role

### Backend Developer

My main contribution to the project was backend development using Django.

I worked on:

- Django backend development
- Django models and ORM
- Cart and checkout logic
- Order processing
- Order and cart APIs
- Product stock validation
- Order total calculations
- Razorpay payment integration
- Payment/order record handling
- Backend testing
- Git and GitHub version control

## Testing

The project includes automated Django tests for important order and cart functionality.

Tests cover:

- Cart-to-order conversion
- Order total calculations
- Stock validation
- Invalid product handling
- Invalid order items
- Stock quantity updates

### Test Command

```bash
python manage.py test github_tests

### Test Result
Found 3 test(s).

Ran 3 tests in 0.075s

OK

### Project Structure
django-ecommerce/
│
├── auth/
├── checkout/
├── core/
├── fashion_store/
├── frontend/
├── github_tests.py
├── manage.py
├── .gitignore
└── README.md

### Django Architecture
Model
   ↓
Database and Data Management

View
   ↓
Business Logic and Request Handling

Template
   ↓
User Interface

### API Functionality
The backend provides API endpoints for different application operations, including:

Product data
Cart management
Order creation
Checkout processing
Payment order creation

Example endpoints:  /api/products/
/api/cart/items/
/api/orders/
/api/payments/razorpay/order/
