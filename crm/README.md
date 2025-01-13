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

bash
Copy code
pip install django
Create a new Django project:

bash
Copy code
django-admin startproject customer_management
cd customer_management
Create a new app for managing customers:

```bash
Copy code
python manage.py startapp accounts
Register the app in INSTALLED_APPS in the settings.py file:
```
python
Copy code
INSTALLED_APPS = [
    ...
    'accounts',
]
2. Clone the Repository (Optional)
If the project is prebuilt and stored in a repository:

bash
Copy code
git clone <repository-url>
cd customer-management-app
3. Create and Activate a Virtual Environment
Create a virtual environment:

bash
Copy code
python -m venv venv
Activate the virtual environment:

On Linux/MacOS:
bash
Copy code
source venv/bin/activate
On Windows:
bash
Copy code
venv\Scripts\activate
4. Install Dependencies
Install required Python packages:

bash
Copy code
pip install -r requirements.txt
5. Apply Migrations
Create the database migrations:

bash
Copy code
python manage.py makemigrations
Apply the migrations:

bash
Copy code
python manage.py migrate
6. Create a Superuser
Create a superuser to access the admin panel:

bash
Copy code
python manage.py createsuperuser
7. Run the Development Server
Start the development server:

bash
Copy code
python manage.py runserver
Access the app at http://127.0.0.1:8000/ and the admin panel at /admin/.
