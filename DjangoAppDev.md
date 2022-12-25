# Create your first Django app

We’ll assume you have Django installed already else you need to follow the link given below.

https://github.com/Nitya663/Django_Markdown_project/blob/main/Django_test.md 

check the which Django version installed by running the following command in a shell prompt (indicated by the $ prefix):

     $ python3 -m django --version

If Django is installed, you should see the version of your installation. If it isn’t, you’ll get an error telling <mark>“No module named django”.</mark>
To reoleve this error will give refered steps.

## Creating a project

If this is your first time using Django, you’ll have to take care of some initial setup. Namely, you’ll need to auto-generate some code that establishes a Django project (steps are given in above given link) – a collection of settings for an instance of Django, including database configuration, Django-specific options and application-specific settings.

To create a new Django project named myapp use the django-admin command-line utility:

    (venv)$ django-admin startproject myapp
    

The command above will create a mydjangoapp directory in your current directory.

Inside that directory, you will find the main script for managing projects named manage.py and another directory including database configuration, and Django and application-specific settings.

Let’s migrate the database and create an administrative user.
Start by navigating to the myapp directory:

    (venv)$ cd myapp

By default, Django uses a SQLite database. For production applications, you can use PostgreSQL , MariaDB , Oracle or MySQL Database.

Run the following command to migrate the database:


       (venv)$ python manage.py migrate

The output will look something like the following:


     output :

        Operations to perform:
        Apply all migrations: admin, auth, contenttypes, sessions
        Running migrations:
        Applying contenttypes.0001_initial... OK
        Applying auth.0001_initial... OK
        Applying admin.0001_initial... OK
        Applying admin.0002_logentry_remove_auto_add... OK
        Applying admin.0003_logentry_add_action_flag_choices... OK
        Applying contenttypes.0002_remove_content_type_name... OK
        Applying auth.0002_alter_permission_name_max_length... OK
        Applying auth.0003_alter_user_email_max_length... OK
        Applying auth.0004_alter_user_username_opts... OK
        Applying auth.0005_alter_user_last_login_null... OK
        Applying auth.0006_require_contenttypes_0002... OK
        Applying auth.0007_alter_validators_add_error_messages... OK
        Applying auth.0008_alter_user_username_max_length... OK
        Applying auth.0009_alter_user_last_name_max_length... OK
        Applying sessions.0001_initial... OK

## Write your first view

Let’s write the first view. Open the file members/views.py and put the following Python code in it:

myapp/members/views.py:

```python
    from django.shortcuts import render
    from django.http import HttpResponse

    def members(request):
        return HttpResponse("Hello world!")
```
Create a file named urls.py in the same folder as the views.py file, and type this code in it:

myapp/members/urls.py:

```python
    from django.urls import path
    from . import views

    urlpatterns = [
    path('members/', views.members, name='members'),
    ]
```

The urls.py file you just created is specific for the members application. We have to do some routing in the root directory my_tennis_club as well. This may seem complicated, but for now, just follow the instructions below.

There is a file called urls.py on the myapp folder, open that file and add the include module in the import statement, and also add a path() function in the urlpatterns[ ] list, with arguments that will route users that comes in via 127.0.0.1:8000/.

Testing the Development Server

Start the development web server using the manage.py script followed by the runserver option:

       (venv)$ python manage.py runserver

You’ll see the following output:


output: 
        
    Performing system checks...
        
    System check identified no issues (0 silenced).
    December 23, 2022 - 11:16:28
    Django version 2.1.2, using settings 'myapp.settings'
    Starting development server at http://127.0.0.1:8000/
    Quit the server with CONTROL-C.


 
 If you installed Django on a virtual machine and you want to access Django development server then you’ll need to edit the settings.py file and add the server IP address inside the **ALLOWED_HOSTS** list.</mark>

Open http://127.0.0.1:8000 in your web browser and you will be presented with the "Hello world!" landing page:


![hello World](helloworld.png)


To stop the development server type CTRL-C in your terminal.

## Deactivating the Virtual Environment :

To deactivate the environment, by typing deactivate and you will return to your normal shell.
   
    (venv)$ dectivate
