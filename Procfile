web: gunicorn main.wsgi --limit-request-line 8188 --log-file -
worker: celery worker --app=main --loglevel=info
