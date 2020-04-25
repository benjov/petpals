# petpals


1. conda create -n pet_pals_env python=3.6
2. conda acrtivate...
3. pip install gunicorn
4 pip install flask pip 
install flask-sqlalchemy
pip install pandas
pip install psycopg2
pip install psycopg2-binary ***** For mac users

python initdb.py

./run.sh

pip freeze > requirements.txt

touch Procfile

agregar: web: gunicorn pet_pals.app: app

GIT ADD .
.....

