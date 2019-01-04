# Flaskr - Flask Tutorial
The basic blog app built in the Flask [tutorial](http://flask.pocoo.org/docs/tutorial/).

## Install
Create a virtualenv and activate it:
```
python -m venv venv
.\venv\Scripts\activate
pip install -r requirements.txt
```

## Run
```
$env:FLASK_APP='flaskr'
$env:FLASK_ENV='development'
flask run
```

## Test
To run the tests, use the `pytest` command.
```
pytest
```

To measure the code coverage, use the `coverage` command.
```
coverage run -m pytest
```

To view the coverage report in the terminal use the `coverage report` command.