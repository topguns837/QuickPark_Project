web: gunicorn wsgi:app
heroku ps:scale web=1
python manage.py migrate
