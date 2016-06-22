#Django Tutorial 
Follow step by step to acheieve final output
Django runs on python environment, everything in django is done in pyhton programming language.
#Step 1: Setting Python Environment.
#To Download python editor, Click the link given below:
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


