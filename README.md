# -Django-Meeting-Planner
Meeting Planner with Django Framework, HTML, CSS

# -To Install Django
pip install Django

# -To Create Virtualenv
pip install pipenv
<br>
pipenv shell

# -To Create django project
django-admin startproject <project_name>
<br>
EX:
django-admin startproject meeting_plan


# -To run django server
<br>
cd meeting_plan
<br>
python manage.py runserver

# -To create an application inside of the project
python manage.py startapp website

# -To show the list of migrations
python manage.py showmigrations

# -To create default tables with migrations
python manage.py migrate

# -To create migrations
python manage.py makemigrations

# -To convert migrations to the sql query from migration file
python manage.py sqlmigrate meetings 0001

# -To create super user in the admin
python manage.py createsuperuser
<br>
username: admin
<br>
email: admin@gmail.com
<br>
password: admin
