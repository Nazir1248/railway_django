web: gunicorn railway_django.wsgi --log-file - 
#or works good with external database
web: python manage.py migrate && gunicorn railway_django.wsgi
