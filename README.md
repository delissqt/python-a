
Try exercise pretend to crea a api


Is import have installed **uvicorn** in order to run the program more details in [uvicorn.org](https://www.uvicorn.org/)

````commandline
$ pip install uvicorn
````

### run program

````commandline
$ uvicorn main:app --reload
````

output
````commandline
INFO:     Uvicorn running on http://127.0.0.1:8000 (Press CTRL+C to quit)
INFO:     Started reloader process [28720]
INFO:     Started server process [28722]
INFO:     Waiting for application startup.
INFO:     Application startup complete.
````

At time the program is running api documentation is automatically documented

_Interactive API docs_

You will see the automatic interactive API documentation (provided by Swagger UI):
**http://127.0.0.1:8000/docs.**


_Alternative API docs_

You will see the alternative automatic documentation (provided by ReDoc):
**http://127.0.0.1:8000/redoc.**
