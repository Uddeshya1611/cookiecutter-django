web: gunicorn config.wsgi:application
worker: celery worker --app=django-cookie-cutter.taskapp --loglevel=info
