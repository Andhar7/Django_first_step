

pip install pillow 
 
pip freeze > requirements.txt  

python3 manage.py migrate

python3 manage.py startapp main

# main we should save in settings.py file INSTALLED_APPS...

# After creating in models.py file Category and Product models, we need to create migrations
 python3 manage.py makemigrations
# Then we need to apply the migrations
 python3 manage.py migrate
# After creating the models, we need to create an admin interface for them
 python3 manage.py createsuperuser

# After creating the superuser, we can run the server
 python3 manage.py runserver







 
