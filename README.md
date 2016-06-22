#Django Tutorial 
Follow step by step to acheieve final output
Django runs on python environment, everything in django is done in pyhton programming language.
#Step 1: Setting Python Environment
To Download python editor, Click the link given below
    Python 2.7.11 : https://www.python.org/ftp/python/2.7.11/python-2.7.11.msi
    Python 3.5.1  : https://www.python.org/ftp/python/3.5.1/python-3.5.1.exe
Open System Properties-->Go to Advance System Settings-->Environment variables-->click on new
    Variable name : path
    Variable Value : C:\Python27\Python27\Scripts 
#Step 2 : Setting Django Environment.
    Open Command Prompt
    Type : pip install django
This will install django framework, if you want to change the verision of django type pip install django=1.6
#Step 3 : Creating Django Project
    
    django-admin startproject website
website is a project name which contain python package.
Look at website project:

mysite/
    manage.py
    mysite/
        __init__.py
        settings.py
        urls.py
        wsgi.py
These files are:

The outer mysite/ root directory is just a container for your project. Its name doesn’t matter to Django; you can rename it to anything you like.
manage.py: A command-line utility that lets you interact with this Django project in various ways. You can read all the details about manage.py in django-admin and manage.py.
The inner mysite/ directory is the actual Python package for your project. Its name is the Python package name you’ll need to use to import anything inside it (e.g. mysite.urls).
mysite/__init__.py: An empty file that tells Python that this directory should be considered a Python package. If you’re a Python beginner, read more about packages in the official Python docs.
mysite/settings.py: Settings/configuration for this Django project. Django settings will tell you all about how settings work.
mysite/urls.py: The URL declarations for this Django project; a “table of contents” of your Django-powered site. You can read more about URLs in URL dispatcher.
mysite/wsgi.py: An entry-point for WSGI-compatible web servers to serve your project. See How to deploy with WSGI for more details.
