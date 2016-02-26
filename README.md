# Flask-Blog

A Flask blog *obviously written in Python* that has an admin panel

## License
Licensed under GNU GPL v3.0.

## Requirements
 - Python3
 - Everything inside requirements.txt

## Installing requirements.txt
`pip3 install -r requirements.txt`

### Initialize

The following command will create all tables and fill the database with dummy
blog posts.

    $ python manage.py init

Additional commands are

    dropdb (Drop all tables in database)
    initdb (Create all tables)
    filldb (Fill database with dummy blog posts)

## Run

    $ python manage.py runserver

Login with **admin** as default username and password. Just add /admin to the
url or press the login icon at the top of the page.
