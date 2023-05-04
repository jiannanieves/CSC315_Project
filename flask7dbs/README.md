# flask7dbs


## One-Time Installation

You must perform this one-time installation in the CSC 315 VM:

```
# install python pip and psycopg2 packages
sudo pacman -Syu
sudo pacman -S python-pip python-psycopg2

# install flask
pip install flask
```

## Usage

To run the Flask application, simply execute:

```
export FLASK_APP=app.py
flask run
# then browse to http://127.0.0.1:5000/
```

## References

Flask documentation:  
https://flask.palletsprojects.com/  

Psycopg2 documentation:  
https://www.psycopg.org/  

This example code is derived from:  
https://www.postgresqltutorial.com/postgresql-python/  
https://scoutapm.com/blog/python-flask-tutorial-getting-started-with-flask  
https://www.geeksforgeeks.org/python-using-for-loop-in-flask/  
