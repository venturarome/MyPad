# MyPad

### Source
This is a dummy project achieved by following the Flask 0.12 [tutorial](http://flask.pocoo.org/docs/0.12/tutorial/).

### Useful Info
#### Folder structure
```
myPad/
|___ myPad/
|    |___ static/
|    |___ templates/
|    |___ __init__.py
|    |___ myPad.py
|    |___ schema.sql
|___ MANIFEST.in
|___ setup.py
```
#### Instalation steps
The code is distributed as a package. To install it, it is reccommended to use a virtual environment.
1. ```pip install virtualenv```
2. ```virtualenv <env_name>```
3. ```source <env_name>/bin/activate```
4. ```cd <env_name>```
5. ```mkdir myPad```
6. ```cd myPad```
7. Clone git repo there
8. ```pip install --editable .``` (That will create a \*.egg-info folder)
9. export FLASK\_APP=flaskr && export FLASK\_DEBUG=true
10. flask run
