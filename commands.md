# Packages

django
python-dotenv==1.0.1
djangorestframework==3.15.1
pytest==8.1.1
pytest-django==4.8.0

# Commands

django-admin startproject ecommerce
./manage.py runserver
from django.core.management.utils  import get_random_secret_key
pip freeze > requirements.txt

## Pytest
pytest -h       # prints options _and_ config settings