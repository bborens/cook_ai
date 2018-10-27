
# Cook_ai 

## About this Project

This project is my first attempt at creating an application with Python/Django. I plan to connect this application to a Laravel Blog, and then a robust Laravel eCommerce site, all connected to PostgreSQL via PGAdmin4. This README serves as a guide to follow along with the steps required to create it from start to finish. 

### Step 1 : Create Virtual Environment to begin project

Create Virtual Environment for Python 3 

        kde-bot@kde-bot-MS-7751:~/dev/cook_ai$ python3 -m venv ./venv

Access Virtual Python Environment 

        kde-bot@kde-bot-MS-7751:~/dev/cook_ai$ source ./venv/bin/activate
        (venv) kde-bot@kde-bot-MS-7751:~/dev/cook_ai$

        (venv) kde-bot@kde-bot-MS-7751:~/dev/cook_ai$ python --version
                Python 3.6.6 :: Anaconda custom (64-bit)

Upgrade pip if necessary

        (venv) kde-bot@kde-bot-MS-7751:~/dev/cook_ai$ pip install --upgrade pip
                Successfully installed pip-18.1

Install Django

        (venv) kde-bot@kde-bot-MS-7751:~/dev/cook_ai$ pip install django
                Installing collected packages: pytz, django
                Successfully installed django-2.1.2 pytz-2018.6

Check install dependencies within Virtual Environment 

        (venv) kde-bot@kde-bot-MS-7751:~/dev/cook_ai$ pip freeze
                Django==2.1.2
                pytz==2018.6

Django Admin to create project named 'cook_ai' inside current directory. Now manage.py will be used to create. 

        (venv) kde-bot@kde-bot-MS-7751:~/dev/cook_ai$ django-admin startproject cook_ai .

### Step 2 : Choose correct venv python interpreter

Within VScode press F1, select interpreter

Install pylint 

        (venv) kde-bot@kde-bot-MS-7751:~/dev/cook_ai$ /home/kde-bot/dev/cook_ai/venv/bin/python -m pip install -U pylint

### Step 3 : Create .gitignore

Go [here](gitignore.io) for easy gitignore file generation. 

    
