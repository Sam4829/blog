# blog Readme

Steps to create a Virtual Env (Windows)
- Create Virtual env : mkvirtualenv blog-name
- activate virtual env : & cmd /k workon env_name
- Change to blog directory, then set directory to virtualenv : setprojectdir .

Install packages
- pip install requirements.txt

Migrations
- python manage.py makemigrations
- python manage.py migrate

Runserver
- python manage.py runserver
