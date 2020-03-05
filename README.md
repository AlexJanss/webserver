# Webserver with Python

Folowing along the tutorial on https://ruslanspivak.com

For the webserver2 :

$ python3 -m venv lsbaws
$ ls lsbaws
bin   include   lib   pyvenv.cfg
$ source lsbaws/bin/activate
(lsbaws) $ pip install -U pip
(lsbaws) $ pip install pyramid
(lsbaws) $ pip install flask
(lsbaws) $ pip install django

For the djangoapp it is essential to run django-admin.py startproject helloworld
 beforehand.