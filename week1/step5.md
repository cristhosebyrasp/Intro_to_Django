# Starting PyCharm

<!-- IMAGE
Caption: PyCharm1
ID: pycharm1
Alt text: 
Author: 
Attribution: 
Placeholder: TRUE  
--> 

![IMAGE](figures/PyCharm1.png)

<!-- END IMAGE -->

# Creating a new project

```
Creating the project
```
Open a command shell (or a terminal window), and make sure you are in your virtual environment.
Navigate to where you want to store your Django apps (make it somewhere easy to find like inside your Documents folder), and create a folder for your new website (in this case: django_projects).Then change into your newly-created directory:

```
mkdir django_projects
cd django_projects
```


<!-- IMAGE
Caption: PyCharm2
ID: pycharm2
Alt text: 
Author: 
Attribution: 
Placeholder: TRUE  
--> 

![IMAGE](figures/PyCharm2.png)


Create the new project using the django-admin startproject command as shown, and then change into the project folder:
django-admin startproject locallibrary

```
cd locallibrary
```



# Checking Python version


<!-- IMAGE
Caption: Checking Python Version
ID: pythonversioncheck
Alt text: 
Author: 
Attribution: 
Placeholder: TRUE  
--> 

![IMAGE](figures/pythonversioncheck.png)

# Installing Django

## from pip

<!-- IMAGE
Caption: Installing Django
ID: InstallingDjango1
Alt text: 
Author: 
Attribution: 
Placeholder: TRUE  
--> 

![IMAGE](figures/InstallingDjango1.png)

## from git clone

<!-- IMAGE
Caption: Installing Django
ID: InstallingDjango2
Alt text: 
Author: 
Attribution: 
Placeholder: TRUE  
--> 

![IMAGE](figures/InstallingDjango2.png)



# Creating your first Project

Now that we have created a Django project environment, let's create our app. As previewsly mentioned, one project can have many apps. But for the purpose of this course we will create just one app.

```
django-admin startproject locallibrary
cd locallibrary
```
<!-- IMAGE
Caption: Creating my first project
ID: firstproject
Alt text: 
Author: 
Attribution: 
Placeholder: TRUE  
--> 

![IMAGE](figures/firstproject.png)

# cd to folder


<!-- IMAGE
Caption: How to cd to folder
ID: cdtofolder
Alt text: 
Author: 
Attribution: 
Placeholder: TRUE  
--> 

![IMAGE](figures/cdtofolder.png)

# my first app


<!-- IMAGE
Caption: Creating my first app
ID: myfirstapp
Alt text: 
Author: 
Attribution: 
Placeholder: TRUE  
--> 

![IMAGE](figures/myfirstapp.png)


# migrate

```
python manage.py migrate
```

<!-- IMAGE
Caption: Migrate
ID: migrate
Alt text: 
Author: 
Attribution: 
Placeholder: TRUE  
--> 

![IMAGE](figures/migrate.png)


# makemigration

```
python manage.py makemigration
```

<!-- IMAGE
Caption: Making migration
ID: makemigrations
Alt text: 
Author: 
Attribution: 
Placeholder: TRUE  
--> 

![IMAGE](figures/makemigrations.png)

# Starting the web application

```
python manage.py runserver
```

<!-- IMAGE
Caption: Starting the web application
ID: runserver
Alt text: 
Author: 
Attribution: 
Placeholder: TRUE  
--> 

![IMAGE](figures/runserver.png)

# Your web app it alive

<!-- IMAGE
Caption: Screen 1
ID: screen_1
Alt text: 
Author: 
Attribution: 
Placeholder: TRUE  
--> 

![IMAGE](figures/screen1.png)

<!-- END IMAGE -->

Now that your server is up and running, next lesson we will start to customise it. Keep in mind that every time your web app goes down, to put it up again you need to repeat the command beloww:

```
python manage.py runserver
```