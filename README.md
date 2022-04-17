# Django-loginlogout-and-file-upload-and-display-data

SampleDjango Authentication Application and  store User Details 
1.Download Python
2.Download vscode Editor
3.creteated projects folder
4. cd to projects folder
5.open terminal and create new virtual environment using python -m venv envname
6.Activate the environment using envname\scripts\activate
7. install the django using pip: pip install django
8.create new django project using :django-admin startproject projectName
9.cd to projectName created
10. To check the project created run: python  manage.py runserver 
11.Now cd to the projectName and create the Application using the:django-admin startapp AppName
12.To migrate all tables and other files run :python mange.py migrate
13 under the project  create the  templates folder as django by defaults looks into the templates folder for the views
14.Create requirements.txt under the Project Name.
15.in settings.py add the templates in the DIR[] :
16.As  we are creating authentication at the bottom of settings.py file add 
LOGIN_REDIRECT_URL=’home’
LOGOUT_REDIRECT_URL=’home’ which is a HTML file
17.  created Login.html under templates folder which takes username and password
18.after successful login it redirects to home.html
19.Logout also Redirects to Home.html
12.under the app create urls.py and add : path of the app urls.py file
13.under the the project url.py add : path of the app path 
14.create the user by using the superuser command: django-admin createsuperuser or python manage.py createsuperuser
15.can also add other users as well
17.check the authentication after creating the user.
18. Now to dockerise the application create requirements.txt file
Django==3.24
Gunicorn==20.0.4
19. Now create docker file and docker-compose.yml files
20.install docker desktop for windows 10
21.Enable wsl2 on settings
22.setup wsl2 as the default windows insider by downloading any linux disort
23. run docker-compose build to build the image
24.run docker-compose up to run the server
25.use docker-compose stop instead of docker-compose down
26.Used sqlite3 to store and the retrieve the data.
27.Installed Db browser to view and open the data stored the database.
28. placed form in home screen to upload the file which once uploaded will be displayed in the upload.html template as table.

