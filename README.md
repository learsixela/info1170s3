# info1170s2 

## comandos
pip install django
pip list
python -m venv mi_entorno
source mi_entorno/Scripts/activate (bash)
pip install django
pip list
django-admin startproject seccion3
cd seccion3
python manage.py runserver


## respaldar las depencias
pip install psycopg2
pip freeze > requerimientos.txt
pip install -r requerimientos.txt

## crear un app en django
### crear app
python manage.py startapp producto

agregar app al setting


