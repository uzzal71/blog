# blog
development django, postgresql blog website.posted personal and created account user posted own blog post 

# Setting project
git clone

# Database setup
create postgresql database "blog"

# Activate virtualenv
source env/bin/activate

# Install requirements.text
pip install requirements.txt

# Migrations Project

cd mysite
python manage.py migrate

# Create Super User
python manage.py createsuperuser
username:
password:

# Run Project
python manage.py runserver 127.0.0.1:8080
