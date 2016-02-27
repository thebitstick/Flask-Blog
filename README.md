# Flask-Blog

A Flask blog *obviously written in Python* that has an admin panel

## Requirements
 - Python3
 - Everything inside requirements.txt

## Installing requirements.txt
`pip3 install -r requirements.txt`

### Configuration

There's nothing to configure except PORT and HOST, which can be done by either adding

    $ --port="YOUR_PORT" ---host="YOUR_HOST"
    
or by adding the PORT and HOST to manage.py in app.run()

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

### How to use

Just go to the admin page, click New Post at the top, and type your post **in Markdown**.
I know it says Markup, this is a bug.

### Known bugs

A unicode error will appear when initiating the blog database, however, in testing, *everything works fine*.
