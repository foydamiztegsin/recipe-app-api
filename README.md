# recipe-app-api project
Recipe API project

docker build .
docker-compose build
docker-compose run --rm app sh -c "flake8"

docker-compose run --rm app sh -c "django-admin startproject app ."
docker-compose up

docker-compose down

docker-compose build

