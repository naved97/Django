Dependencies:

pip install pipenv
pipenv install
pipenv shell

Migrate and Static Files:

python source/manage.py migrate
python source/manage.py collectstatic
