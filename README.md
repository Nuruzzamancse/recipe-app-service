### recipe-app-service
Recipe app api source code

Commands:
- docker-compose run --rm app sh -c "python manage.py makemigrations"
- docker-compose run --rm app sh -c "python manage.py test && flake8"