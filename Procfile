web: gunicorn config.wsgi:application
worker: celery worker --app=lseu.taskapp --loglevel=info
