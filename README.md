# RestfulAPI-Python
REST API - Python, Django, MySQL

brew install python3

// create virtual environment 
python3 -m venv venv

// activate venv
source venv/bin/activate

python3 -m pip install --upgrade pip

//install Django
pip install Django

pip install djangorestframework
pip install django-cors-headers

// Create Project
django-admin startproject worldCountries .

// Create App 
python manage.py startapp countries

// settings.py, models.py, serializers.py copy

// 설치
pip install mysqlclient

// Migration
python manage.py migrate

python manage.py makemigrations

Python manage.py migrate countries


// python Super User create
python manage.py createsuperuser

// 서버 가동
python manage.py runserver

// admin page
http://127.0.0.1:8000/admin
