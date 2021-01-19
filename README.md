# DigitalWellbeing
Where health meets lifestyle.

## Build
Install Python3 and MongoDb from their respective websites.

Install pipx if not installed.
```
pip install --user pipx
```

Pipenv for the virtual environment.
```
pipx install pipenv
```

cd to project's root folder and activate the virtual environment.
```
pipenv shell
```

Install requirements.
```
pipenv sync
```

Install developer requirements.
```
pipenv sync --dev
```

Run project.
```
python manage.py runserver
```
