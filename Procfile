release: python3 manage.py migrate
web: gunicorn app.manage.wsgi --preload --log-file - 
