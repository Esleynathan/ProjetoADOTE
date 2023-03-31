web: python.exe manage.py collectstatic --no-input && python.exe manage.py migrate && gunicorn -b 0.0.0.0:$PORT adote.wsgi --log-level debug
