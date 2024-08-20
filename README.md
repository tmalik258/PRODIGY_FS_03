# PRODIGY_FS_03 - Django E-commerce Project

An e-commerce platform built using Django with a focus on simplicity, security, and flexibility. This project includes basic functionality like product listing, cart management, user authentication, and checkout.

## Features

- User registration and login
- Product catalog with categories
- Shopping cart functionality
- Checkout process
- Order management
- Admin panel for product and order management

## Prerequisites

- Python 3.x
- Django 3.x or higher
- SQLite3 (or any other supported database)
- Virtualenv (optional, but recommended)

## Installation

### 1. Clone the repository:

```bash
git clone https://github.com/tmalik258/PRODIGY_FS_03.git
cd PRODIGY_FS_03
```

### 2. Create and activate a virtual environment:

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install dependencies:

```bash
pip install -r requirements.txt
```

### 4. Configure the database:

Update `settings.py` with your database credentials if you're not using SQLite. Then, run the migrations:

```bash
python manage.py migrate
```

### 5. Create a superuser for the admin panel:

```bash
python manage.py createsuperuser
```

### 6. Run the development server:

```bash
python manage.py runserver
```

Visit `http://127.0.0.1:8000/` in your browser to see the application in action.

## Project Structure

- **prodigy_fs_03/** - Main project directory
- **store/** - App responsible for product catalog
- **basket/** - App managing the shopping cart
- **order/** - App handling orders
- **checkout/** - App handling checkout
- **account/** - Custom user management with JWT-based authentication
- **address/** - App handling Billing Addresses
- **static/** - Static files (CSS, JS)
- **templates/** - HTML templates

## License

This project is licensed under the MIT License.
