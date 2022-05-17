release: python manage.py migrate
web: gunicorn django_dream.wsgi:application --log-file -
worker: python worker.py