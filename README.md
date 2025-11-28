git clone https://github.com/Syed-Sameer-Ahemed/Django-to-do-list.git

cd Django-to-do-list

python -m venv venv
venv\Scripts\activate

pip install -r requirements.txt

python manage.py makemigrations
python manage.py migrate


python manage.py createsuperuser


python manage.py runserver


http://127.0.0.1:8000/

http://127.0.0.1:8000/login/

http://127.0.0.1:8000/register/

http://127.0.0.1:8000/admin/

