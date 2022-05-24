# Create Django application on Docker

## Run this project on a local machine

* Clone this repository
    * `git clone <repository-url>`
* Run
    * `docker-compose up`

## Some commands for to work django project setup
* `sudo docker-compose run web django-admin startproject app .`
* `sudo chown -R $USER: $USER`
* `docker exec docker_django-web-1 python manage.py startapp hello`

## Useful links to quickstart with django
* https://docs.docker.com/samples/django/
