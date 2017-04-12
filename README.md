# Falcon REST-API Pattern
Scalable RESTFul API design with Falcon and PyPy

Running:

`$ virtualenv .venv`

`$ source .venv/bin/activate`

`(.venv)$ pip install -r requirements.txt`

Then serve app using gunicorn

`(.venv)$ gunicorn app:api`

Now visit http://localhost:8000/notes/

to fetch notes using GET request.