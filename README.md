# djangoCreateProject
# use can any vitual env from pipenv or virtualenv
# create virtual environment
# > virtualenv myenv
# > myenv/Scripts/activate
# > deactivate to deactivate myenv
# > pip install django // for current version of django 
> pip install django==2.x
> python -m django --version // getting installed django version
> django-admin // for all commands
Type 'django-admin help <subcommand>' for help on a specific subcommand.

Available subcommands:

[django]
    check
    compilemessages
    createcachetable
    dbshell
    diffsettings
    dumpdata
    flush
    inspectdb
    loaddata
    makemessages
    makemigrations
    migrate
    runserver
    sendtestemail
    shell
    showmigrations
    sqlflush
    sqlmigrate
    sqlsequencereset
    squashmigrations
    startapp
    startproject
    test
    testserver
Note that only Django core commands are listed as settings are not properly configured (error: Requested setting INSTALLED_APPS, but settings are not configured. You must either define the environment variable DJANGO_SETTINGS_MODULE or call settings.configure() before accessing settings.).

> django-admin startproject django_project // for creating new django project
> cd django_project
> python manage.py runserver // for running the django project
>
