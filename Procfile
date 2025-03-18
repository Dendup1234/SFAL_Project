web: gunicorn SFAL.wsgi --log-file - 
#or works good with external database
web: python manage.py migrate && gunicorn SFAL.wsgi