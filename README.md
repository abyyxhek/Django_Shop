# Django_Shop
# 🛒 Django E-Commerce Website

This is a full-featured e-commerce website built using Django (Python-based web framework). It allows users to browse products, register/login, add items to the cart, place orders, and manage product listings (for admins).

## 🔧 Features

- User registration and login
- Product listing and detail pages
- Add to cart and cart management
- Checkout and order summary
- Admin panel for product and order management
- Responsive design with Bootstrap

## 📦 Tech Stack

- **Backend**: Django
- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **Database**: SQLite (default, can be switched to PostgreSQL/MySQL)
- **Authentication**: Django built-in auth system
- **Payments**: [Optional: Stripe/PayPal integration]

## 🚀 Getting Started

### 1. Clone the Repository


git clone https://github.com/yourusername/django-ecommerce.git
cd django-ecommerce
2. Create a Virtual Environment

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

3.install dependencies
pip install -r requirements.txt

4.run migrations
python manage.py makemigrations
python manage.py migrate

5.Create superuser
python manage.py createsuperuser

6.start development server
python manage.py runserver
📜 License
This project is licensed under the MIT License. Feel free to use and modify it as needed.


