Setup for Django
# Install Django
pip install django

# Create a new Django project
django-admin startproject budgetor

# Navigate to the project directory
cd budgetor

# Create a new Django app
python manage.py startapp budget

# Add the app to the project's settings.py file
INSTALLED_APPS = [
    ...
    'budget',
]

# Run the development server
python manage.py runserver