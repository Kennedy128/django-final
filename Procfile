release: python manage.py makemigrations rate
release: python manage.py migrate


web: gunicorn rateapp.wsgi --log-file -