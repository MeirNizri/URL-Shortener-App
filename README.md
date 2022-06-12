# Mobileye URL Shortener

## Install the Project

1. Create a Python virtual environment

```sh
$ python -m venv venv
$ source venv/bin/activate
(venv) $
```

2. Install the requirements

```
(venv) $ python -m pip install -r requirements.txt
```

## Run the Project

You can run the project with this command in your terminal:

```sh
(venv) $ uvicorn shortener_app.main:app --reload
```

Your server will reload automacially when you change a file.

## Verify Your Environment Variables

The project provides default environment settings in [`shortener_app/config.py`](../../Mobileye-URL-Shortener/shortener_app/config.py).
While you can use the default settings, [it's recommended](https://12factor.net/config) to create a `.env` file to store your settings outside of your production code.


## Visit the Documentation

When the project is running you can visit the documentation in your browser:

- http://127.0.0.1:8000/docs