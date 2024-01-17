# vue_django_auth_backend
# make a virtual environment using
--virtualenv environmentName
--.\environmentName\Scripts\activate
# install all requirements from requirements.txt
# install some additional packages
--pip install djangorestframework
--pip install djangorestframework_simplejwt
--pip install django-cors-headers
# run following commands
--python manage.py makemigrations
--python manage.py migrate
--python manage.py runserver