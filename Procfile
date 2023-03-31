web: python manage.py collectstatic --no-input && python manage.py migrate && gunicorn -b 127.0.0.1:$PORT adote.wsgi --log-level debug
