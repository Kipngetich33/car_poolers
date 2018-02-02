# CAR POOLERS
An application that allows passangers to find drivers heading to the same route and share a ride with them

## Description
Car Poolers is an application more or less like the famous Uber App that allows users to find cars with space in them and heading to the same direction as they are.

## User Stories 
As a user you can do the following:

* Sign in to the application to start using.
* Set up a profile about me and a general location.
* Find a list of drivers near me.
* View a map with the location of all pickup points.
* Review a driver and also be reviewed by the driver.
* View the current space left in a driver’s car and get to book It.

## Driver Stories
As a driver you can use the following:

* Sign up as a driver to use the application
* Set up my drivers profile.
* View a map with the location of all pickup points.
* View all the requests for a ride.
* Review passengers coming on to your application.

## Setup/Installation Requirements
* Prerequisites
* Python 3.6.2
* Virtual environment
* Postgres Database

## Internet
* Installation Process
* Copy repolink
* $ git clone REPO-URL in your terminal
* $ cd car-poolers
* $ python3.6 -m venv virtual
* Create .env file touch .env and add the following:
    SECRET_KEY=<your secret key>
    DEBUG=True
* $ source virtual/bin/activate
* $ python3.6 -m pip install -r requirements.txt
* Create a database with Postgres 
* $ psql
* $ CREATE DATABASE carpoolers
Change the database informatioin in car/settings.py
    DATABASES = {
        'default': {
            'ENGINE': 'django.db.backends.postgresql',
            'NAME': 'poolers',
            'USER': *POSTGRES_USERNAME*,
            'PASSWORD': *POSTGRES_USERNAME*,
        }
    }
* $ python3.6 manage.py runserver 
## Known Bugs
No known bugs yet since the app is still in development process 

## Technologies Used
* Python 3.6.2
* Django 1.11.7
* Bootstrap 3
* Postgres Database
* CSS
* HTML
* Heroku
## License
MIT **[License(/)]** (c) 2017 **[Kipngetich Ngeno(/)]**

