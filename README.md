# PostGreSQL

## Install Django:
 ```python -m pip install Django```
 
 ## Create Virtual Environment:
  One of your projects might require a different version of an external library than another one. Therefore it is recommended that a virtual environment be created wherein different versions of some libraries may reside than the ones present in main environment.
 ```
 python -m venv djangoenv 
 . djangoenv/Scripts/activate
```
**OR**
```
source djangoenv/Scripts/activate
```

This created and activated the new virtual environment

To make the django code importable, run following commands

```
# Clone the django repo
git clone https://github.com/django/django.git

# Install the repo
python -m pip install -e django/
```

Above code makes commands django-admin etc executable.

To create a project, run following command: 
``` django-admin startproject <name of project> ```


## Run the project
Run the project using following command:
``` python manage.py runserver ```

## To create another page or 'app'
Run following command: ```django-admin startapp <page/app name>```