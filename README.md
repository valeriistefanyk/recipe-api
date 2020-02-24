# Recipe app api

commands:

Start folder - /app

* docker build .
* docker-compose build
* docker-compose run app sh -c "python manage.py test && flake8"
* docker-compose run app sh -c "python manage.py runserver 0.0.0.0:8000"