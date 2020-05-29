# django-docker
django on docker

```
$pipenv install
$pipenv shell
(django) $python -V
Python 3.8.2
(django) $pip list
Package                       Version
----------------------------- -------
asgiref                       3.2.7
Django                        3.0.6
django-cors-headers           3.2.1
django-environ                0.4.5
django-templated-mail         1.1.1
djangorestframework           3.11.0
djangorestframework-gis       0.15
djangorestframework-simplejwt 4.4.0
djoser                        2.0.3
gunicorn                      20.0.4
pip                           20.0.2
psycopg2-binary               2.8.5
PyJWT                         1.7.1
pytz                          2020.1
setuptools                    46.1.3
sqlparse                      0.3.1
wheel                         0.34.2

$django-admin startproject config .


python manage.py runserver localhost:8000
```

`chmod +x entrypoint.sh`