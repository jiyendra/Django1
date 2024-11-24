# Django1
docker test with my sql

# vertual env in windows.
pip install virtualenv

python -m venv myenv

myenv\Scripts\activate

# install mysql on windwos, and edit setting file


#to update the db for made changes.

python .\manage.py makemigrations

python .\manage.py migrate  



#to create user.

python .\manage.py createsuperuser

#to create app

python .\manage.py startapp app  

#to run server

python .\manage.py runservr  in local
