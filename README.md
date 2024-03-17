creat vin ==> python -m venv virt
-erfan@Erfans-MacBook-Pro-2 DRF % python -m venv venv

then we can active virtual enviroment by this comment =>
source [name your virtual enviroment]/bin/activate

-erfan@Erfans-MacBook-Pro-2 DRF % source venv/bin/activate

Exit from virtual enviroment => deactivate

Creat Project:
1-(venv) erfan@Erfans-MacBook-Pro-2 DRF % pip install django
2-(venv) erfan@Erfans-MacBook-Pro-2 DRF % django-admin startproject core .

Creat Application:
(venv) erfan@Erfans-MacBook-Pro-2 DRF % python manage.py startapp blog 


Make makemigrations
-(venv) erfan@Erfans-MacBook-Pro-2 DRF % python manage.py makemigrations

Migrate
python manage.py migrate
# polls-djngo-App
