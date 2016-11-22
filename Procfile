web:python manage.py runserver
web: gunicorn textsageone.wsgi --log-file -
heroku ps:scale web=1
