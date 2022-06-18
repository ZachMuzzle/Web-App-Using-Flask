# Flask Web App Project

## Objective of This Project

This project is to work more with flask, but now have it working with a HTML and CSS. We use templates
and jinja syntax to call our flask project to fill areas in our HTML.

## How to  Setup the Project

You will want to have **Python3** installed to check this do: `python3 --version` to check and if you do not have this
use `brew install python`. You will homebrew on MacOS to do this. 
On Linux use `sudo apt-get install python3.6`

After this you will need to install **virtualenv**; this is for having a virtual environment which can have all your dependencies installed in one place!

* Make sure **pip3** is installed!
* Then use `pip3 install virtualenv`
* Create the environment; use `virtualenv env`
* To active the environment use `source env/bin/activate`
* Once activate we can now download our Flask files.
* Use `pip3 install flask flask-sqlalchemy`

### Create a new Database

* From the base of the directory go into a python terminal; just use `python3`
* In the python terminal you can call app one of two ways
  * The first `from app import db` 
  * then `db.create_all()` then `exit()`
  * The second being `import app`
  * then `app.db.create_all()` then `exit()`

This will create a database 

## To run Project

When ever you want to run the program; use `python3 app.py`

**REMEMBER** you must be in your virtual environment for the project to work; otherwise you will get errors with finding Flask.