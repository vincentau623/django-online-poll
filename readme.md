# Django Online Poll
Web polling system written in Django.
Visitors can choose between a fixed number of answers to make a vote.

## Prerequisite

1.  Python is installed
2.  Django is installed

## Setup Guide

1. Clone the project to local folder
2. To create database models, run 
```console
$ python manage.py migrate
```
3. To start the server, run
```console
$ python manage.py runserver
```
4. Visit the admin to create a poll. Default admin web: ```https://127.0.0.1:8000/admin```

5. Visit the ```/polls/``` URL to participate in the poll. Default index web: ```https://127.0.0.1:8000/polls```


## Run tests
```console
$ python manage.py test
# or  
$ python manage.py test polls
```
