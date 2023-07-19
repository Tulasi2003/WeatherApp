# WeatherApp

CREATING A DJANGO-PROJECT

PS C:\Users\jayam tulasi\OneDrive\Desktop\Folder-> django-admin startproject weatherProject

CHECKING THE FILES IN THE DIRECTORY

PS C:\Users\jayam tulasi\OneDrive\Desktop\Folder-> dir

Directory: C:\Users\jayam tulasi\OneDrive\Desktop\Folder-


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        26-02-2023  11:35 PM                weatherProject

TO GET INTO THE PROJECT

PS C:\Users\jayam tulasi\OneDrive\Desktop\Folder-> cd weatherProject

TO CREATE A AN APP IN THE PROJECT

PS C:\Users\jayam tulasi\OneDrive\Desktop\Folder-\weatherProject> python manage.py startapp weatherApp

CHECKING THE FILES IN THE DIRECTORY

PS C:\Users\jayam tulasi\OneDrive\Desktop\Folder-\weatherProject> dir

Directory: C:\Users\jayam tulasi\OneDrive\Desktop\Folder-\weatherProject


----                 -------------         ------ ----
da---l        26-02-2023  11:36 PM                weatherApp
da---l        26-02-2023  11:36 PM                weatherProject
-a---l        26-02-2023  11:35 PM            692 manage.py

TO MAKE CHANGES 

PS C:\Users\jayam tulasi\OneDrive\Desktop\Folder-\weatherProject> python manage.py makemigrations
System check identified some issues:

WARNINGS:
?: (staticfiles.W004) The directory 'C:\Users\jayam tulasi\OneDrive\Desktop\folder-\weatherProject\static' in the STATICFILES_DIRS setting does not exist.
No changes detected

TO GIVE ACCESS THE CHANGES 

PS C:\Users\jayam tulasi\OneDrive\Desktop\Folder-\weatherProject> python manage.py migrate
System check identified some issues:

WARNINGS:
?: (staticfiles.W004) The directory 'C:\Users\jayam tulasi\OneDrive\Desktop\folder-\weatherProject\static' in the STATICFILES_DIRS setting does not exist.
Operations to perform:
  Apply all migrations: admin, auth, contenttypes, sessions
Running migrations:
  Applying contenttypes.0001_initial... OK
  Applying auth.0001_initial... OK
  Applying admin.0001_initial... OK
  Applying admin.0002_logentry_remove_auto_add... OK
  Applying admin.0003_logentry_add_action_flag_choices... OK
  Applying auth.0002_alter_permission_name_max_length... OK
  Applying auth.0003_alter_user_email_max_length... OK
  Applying auth.0004_alter_user_username_opts... OK
  Applying auth.0005_alter_user_last_login_null... OK
  Applying auth.0006_require_contenttypes_0002... OK
  Applying auth.0007_alter_validators_add_error_messages... OK
  Applying auth.0008_alter_user_username_max_length... OK
  Applying auth.0009_alter_user_last_name_max_length... OK
  Applying auth.0010_alter_group_name_max_length... OK
  Applying auth.0011_update_proxy_permissions... OK
  Applying auth.0012_alter_user_first_name_max_length... OK
  Applying sessions.0001_initial... OK

TO RUN THE SERVER

PS C:\Users\jayam tulasi\OneDrive\Desktop\Folder-\weatherProject> python manage.py runserver
Watching for file changes with StatReloader
Performing system checks...

System check identified some issues:

WARNINGS:
?: (staticfiles.W004) The directory 'C:\Users\jayam tulasi\OneDrive\Desktop\folder-\weatherProject\static' in the STATICFILES_DIRS setting does not exist.

System check identified 1 issue (0 silenced).
February 27, 2023 - 00:56:09
Django version 4.0.5, using settings 'weatherProject.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CTRL-BREAK.

