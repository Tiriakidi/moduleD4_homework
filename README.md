# moduleD4_homework
Доступ в админ-панель: polina / qwerty

#ЗАПУСК ПРОЕКТА MACOS

python3 -m venv .env
source .env/bin/activate
pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
