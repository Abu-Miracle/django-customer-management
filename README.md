# Customer Management App
A web-based application for managing customer records, built with the Django framework. This app provides an admin interface for managing customer data and includes features like creating, updating, and deleting customer records.

## Features
- Add new customers with relevant details.
- Edit and update existing customer information.
- Delete customer records.
- Admin panel for managing customer data.

## Technologies Used
- Backend Framework: Django
- Database: SQLite (development) / PostgreSQL (production)
- Frontend: Django Templates, Bootstrap (optional)
- Deployment: Vercel / Other hosting platforms

## Prerequisites
- Python 3.x installed
- pip (Python package manager)
- Django framework

## Installation
1. Create a Django Project
Install Django:

```bash
pip install django
```

Create a new Django project:
```bash
django-admin startproject crm
cd crm
```
Create a new app for managing customers:

```bash
python manage.py startapp accounts
```

Register the app in INSTALLED_APPS in the settings.py file:
```python
INSTALLED_APPS = [
    ...
    'accounts',
]
```

2. Create and Activate a Virtual Environment
Create a virtual environment:

```bash
python -m venv venv
```

Activate the virtual environment:
```bash
venv\Scripts\activate
```

3. Apply Migrations
Create the database migrations:

```bash
python manage.py makemigrations
```

Apply the migrations:
```bash
python manage.py migrate
```

4. Create a Superuser
Create a superuser to access the admin panel:
```bash
python manage.py createsuperuser
```

5. Run the Development Server
Start the development server:
```bash
python manage.py runserver
```
Access the app at http://127.0.0.1:8000/ and the admin panel at /http://127.0.0.1:8000/admin/.
