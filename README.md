# Django Project:
## A Django project is a comprehensive setup of configurations and settings that establish the framework and functionality of a web application. 

#### It encompasses the application code, along with templates, static assets, and additional resources necessary to build and support the application. 

* Create and Activate virtual environment :

```
	python -m venv ./venv

	./venv/Scripts/activate
```
* Install django framework:

```
	pip install django
```

* And also install this file its like package.json:

```

* Now you can check your django app using this commond:
```
python manage.py runserver
```
* if you got following error stop your app using Ctrl+c :
```
You have 18 unpplied migration(s). Your project may not work properly until you
 apply the migrations for app(s): admin, auth, contenttypes, sessions.
 Run 'python manage.py migrate' to apply them."
use this commond
```
 	pip freeze > requirements.txt 
```
Create a django project. 
```
django-admin startproject <project_Name>
```

* Apply the migrations & create superuser for admin:
```
python manage.py makemigrations
python manage.py createsuperuser
python manage.py runserver
```

