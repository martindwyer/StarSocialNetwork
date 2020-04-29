# StarSocialNetwork
This application, the StarSocialNetwork, is a project completed in conjunction with Python and Django Full Stack, a course taught by Jose Portilla and available at https://www.udemy.com/course/python-and-django-full-stack-web-developer-bootcamp/

The project is a Python Django full stack application written to clone the functionality of social networking sites. 

The project was originally developed using Python 3.5 and Django 1.11.  At the present time, the most recent version of Python (3.8) has compatability issues with Django.  Consequently, the project was updated to a combination of Python 3.7 and Django 2.0.  

The virtual environment including all necessary plugins to run the application is included in this project .venv folder and should be activated with the scripts/activate command before attempting to run the application.  The development server is initiated with the command $python manage.py runserver from the root directory. 

For database purposes, the application uses the SQLite technologies included by default in Django application.  The database is contained as db.sqlite3 in the root folder.  

Developed with Bootstrap 3, the site is responsive to screen size changes and mobile ready.  The site background contains an image of the milky way with a JavaScript application for stars floating across the screen.  Screen clicks produce a burst of stars.

The object orientation of the application revolves around creation and interaction of three objects; users, groups, and posts.  User, Group, and Post are all defined in the models of the application.  Moreover, the application was developed with these three classes given distinct applications.  

Beyond the original class design, changes have been limited to static images and styles as well as template files.  Models, views, and urls remain unchanged from those developed in the course.  

Screen shots of the system running can be found in the 'screenshots' folder in the root directory.  
