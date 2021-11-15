

python -m venv venv
venv\Scripts\activate.bat
source venv/bin/activate

pip install django==3.2
django-admin startproject geekshop

.\geekshop\manage.py runserver
 python manage.py runserver
python manage.py --help
cd geekshop
python manage.py startapp mainapp