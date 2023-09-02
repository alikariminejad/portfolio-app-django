# portfolio-app-django


Building a Portfolio app with Django.      Source: https://realpython.com/get-started-with-django-1/



### Setup

1-Create a new virtual environment:

`$ python3 -m venv venv`

2-Activate the virtual environemnt

`$ source venv/bin/activate`

3-Install the dependencies

`(venv) $ python -m pip install -r requirements.txt`

4-Make and apply the migrations for the project to build your local database:

`(venv) $ python manage.py makemigrations`
`(venv) $ python manage.py migrate`

5-Run the Django developemnt server:

`(venv) $ python manage.py runserver`

6-Navigate to `https://localhost:8000` to see website in action.