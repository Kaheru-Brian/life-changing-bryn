Creating a To Do list using Dnango rest framwork API
creat a virtual environment using " python -m venv myenv"
activate the environment "myenv\scripts\activate.bat"
install django in your environment"pip install django"
install django rest framework in your environment "pip istall djangorestframework"
Then start project "django-admin startproject name-project
start app in the new project "python manage.py startapp app-name
in the settings.py file, register the app created
create the models for the to do list.
then register the models in the admin.py file
create a serializers.py file  (responsible for converting the objects into a data type which is understandable by javascript 
and other frontend frameworks)
create views(class-based views)
create urls.py file in the app directory for the paths of the views we created.
in the settings.py file under the instaled apps, include thirdparty apps "rest_framework"
in the urls.py file in the project directory, register the urls file created in the app directiory.
then make migrations and migrate the models 
create superuser