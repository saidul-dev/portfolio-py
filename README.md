mkdir portfolio_project
cd portfolio_project
python -m venv venv
venv\Scripts\activate
pip install django
django-admin startproject portfolio .
python manage.py startapp main
