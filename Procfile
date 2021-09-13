web: gunicorn Student_management_system.wsgi:application --log-file - --log-level debug
python manage.py collectstatic --noinput
manage.py migrate