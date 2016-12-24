web: gunicorn config.wsgi:application
worker: celery worker --app=brokenib.taskapp --loglevel=info
