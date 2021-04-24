# Simple Task Manager

This task manager is made in Flask and SQLite as you can see REQUIREMENTS.txt file
All the requirements and the things to install are there in the REQUIREMENTS.txt file itself..

## How to run?

First you can create a virtual enviroment but that's totally optional..
And a side note, you must have virtualenv installed or it won't work :/
```
virtualenv env
```

Then you have to initialize the virtual enviroment
You can run the following command:
```
source env/bin/activate
```

Then you have to download all the packages used in this package
```
pip install -r REQUIREMENTS.txt
```

Then you have to open Python shell by using
```
python3
```

Then you have to run
```
from app import db
```

It will get the database configuration from the main file
Then you have to initialize the database using a command which is:
```
db.create_all()
```

Then your database will get created :D
Then just run the code using
```
python3 app.py
```

And then you have your easy, simple Task Manager ready!
