# flask-api-default
# Default project for API with Flask

Into the project there some files called `card_*.py` these files is examples how to implement an API. If you want, you can delete every one and start a new file or rename, but if you chose the second option, remember to rename the imports.

## Struct project

```txt
project/
    │
    ├── api/
    │   ├── entidades              
    │   ├── models              
    │   ├── schemas              
    │   ├── services
    │   ├── views                                  
    │   └── __init__.py     # File initialize project
    ├── config.py           # File settings Flask        
    ├── Dockerfile
    ├── docker-compose.yml  
    ├── .dockerignore
    ├── requirements.txt    # Requirements of project
    └── .gitignore
```

<br>

| When you start the project you'll need run the follow command to set the variable `FLASK_APP=api`:

```bash
export FLASK_APP=api
```

## Some commands if you need

- Start project:
<br>

```bash
flask --app api run
```

<br>

- Start Database with mysql:
<br>

```bash
flask db init
```

<br>

- Migrate database:
<br>

```bash
flask db migrate
```

<br>

- Update database:
<br>

```bash
flask db update
```

<br>

