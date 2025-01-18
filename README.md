# for setting up virtual environment

    python3 -m venv .venv

# for activate path

    source .venv/bin/activate

# for installing django framework

    pip install djangorestframework

# for starting django app

    python3 manage.py startapp home

## if change anything in database schema

    python3 manage.py makemigrations

# for migrating default table for auth

    python3 manage.py migrate

# for creating super user

    python3 manage.py createsuperuser
    username:Abdullah
    email:shakibrybmn@gmail.com
    pass;1234

# for changing django administration text

### add below text in your project urls.py

    admin.site.site_header = "Abdullah ICE Cream Admin"
    admin.site.site_title = "Abdullah ICE Cream Admin Portal"
    admin.site.index_title = "Welcome to Abdullah ICE Cream"
