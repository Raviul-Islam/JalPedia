BACKEND:

python -m venv venv(Install virtual environment)
pip install django==4.2(Install Django)
pip freeze > requirements.txt(Create requirement list)
pip install -r requirements.txt(Install packages in requirement list)
django-admin startproject backend . (Start Project)
py manage.py runserver (Run Server)
py manage.py startapp api(Include API in Project)
