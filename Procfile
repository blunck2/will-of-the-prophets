release: python manage.py check --deploy --fail-level WARNING && python manage.py migrate --no-input && python manage.py clearsessions
web: python manage.py check --deploy --fail-level WARNING && gunicorn will_of_the_prophets.wsgi --log-file -
