# Flask REST API App

Basic Flask REST API App

## Commands for database migrations

```
* flask db init
* flask db migrate -m "message"
* flask db upgrade
```

### If the main python file is not named app.py

For Windows
```
set FLASK_APP=name_of_python_file.py
```

For Mac or Linux
```
export FLASK_APP=name_of_python_file.py
```

In this case the name of python file is simpleapi.py
