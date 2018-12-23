# django-basic-setup
Implemented basic setup django framwork like creating routes, integrated static files (css &amp; js) and models

# Superuser Credentials
Username: admin
Password: admin@123456

 # Django uses sqlite db as default
    
    ## To install sqlite browser
        sudo apt-get install sqlitebrowser
    ## To open sqlite browser (type in terminal)
        sqlitebrowser

# To Start New Project in Django

    django-admin startproject <prj_name>

# To Run Server
    
    python manage.py runserver

    # to kill if 8080 port is already in use
        sudo of -t -i tcp:8000 | xargs kill -9

# To Migrate Models in sqlite
    
    ## Common migration command
        python manage.py migrate

    ## To integrate newly created models into sqlite (it will create new files inside migration folder of an app)
        python manage.py makemigrations
 

# To Create A New App In Server
    
    python manage.py startapp <app_name>


# To Create A New Admin User

  python manage.py createsuperuser


