use to run any pip command: 
1) python -m pip install virtualenv
2) python -m virtualenv myenv - create our own virtualenv
3) .\myenv\Scripts\activate - to activate the env

after activating the virtual env
4) pip install django - to install django
5) django-admin startproject TODO_PROJECT -> cd TODO_PROJECT
6) python manage.py startapp ToDoApplication

7) pip freeze > requirements.txt
8) to install: pip install -r requirements.txt

To migrate db
9) python manage.py makemigrations
10) python manage.py migrate
11) python manage.py createsuperuser - to create super user for our application