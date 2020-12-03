# User-authentication using Django REST Framework. 
It is a basic applicaion in which following operations can be performed:
    - user signup via email/user name : http://127.0.0.1:8000/rest-auth/registration/
    - signin/login : http://127.0.0.1:8000/rest-auth/login/
    - signout/logout : http://127.0.0.1:8000/rest-auth/logout/
    - forget password : http://127.0.0.1:8000/rest-auth/password/reset/ 
    - update password : http://127.0.0.1:8000/rest-auth/password/change/
    - user profile edit : http://127.0.0.1:8000/rest-auth/user/

# Technology stack
1. Python3
2. Django REST Framework
3. sqlite3 Database
    
# Running Locally
First, clone the repository to your local machine:

git clone https://github.com/saiyadfaizan/user_authentication_DRF.git

cd user_auth

# Create super user 
python manage.py createsuperuser 

Note: It will prompt to enter username, email and password one by one. Please remember the username and password,
it will be used to login admin area or to hit an API.

# Steps to run the project
1. Install the requirements: pip install -r requirements/dev.txt
2. Check for the database migrations: python manage.py makemigrations
3. Apply the database migrations: python manage.py migrate
4. Run the developement server: python manage.py runserver
5. Open chrome and the site will be available at 127.0.0.1:8000.

