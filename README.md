# Simple Flask App

## Dependencies

* Python 3
* Pip

```python3
pip3 install --user flask sqlalchemy flask-sqlalchemy
```

## Running the application

The follow command imports the database setup to your envoirement(run once):

```python3
from bookmanager import db
db.create_all()
exit()
```

Then run the application itself

```python3
python3 bookmanager.py
```

Author: Isamu Hirahata

Github: [@isamuhiro](github.com/isamuhiro)

To report issues please contact me in [@isamuhiro](github.com/isamuhiro)