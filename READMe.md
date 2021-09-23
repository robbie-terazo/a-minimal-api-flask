# A Minimal API (Flask)

https://flask-restful.readthedocs.io/en/latest/quickstart.html

## Setup your virtual environment
```
python -m venv venv
source venv/bin/activate
pip install -r requirements
```

## Minimal

```
python api.py
```

- Resources are built on top of [Flask pluggable views](http://flask.pocoo.org/docs/views/), giving you easy access to multiple HTTP methods just by defining methods on your resource.
- notice that you can pass multiple URLs when adding a resource.

## Todo API

```
python todo.py
```
- Flask-RESTful understands multiple kinds of return values from view methods. Similar to Flask, you can return any iterable and it will be converted into a response, including raw Flask response objects.
- Notice how you can set the response code and response headers using multiple return values.
- reqparse gives Flask-RESTful built-in support for request data validation using a library similar to [argparse](http://docs.python.org/dev/library/argparse.html).