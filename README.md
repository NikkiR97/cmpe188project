# Kaggle Competition Application 
Note: make sure your system is running Python 3+ 

## Setting Up Virtual Environment 
It is strongly advised to use a virtual environment! In case your machine is handling multiple versions of python & django, create a virtual environment with settings specific for each application to prevent program crashes. Follow the these instructions when first setting it up: 

 1. Download virtual environment
 ```
pip install virtualenv
```
2.  Make a directory for your virtual environment 
```
mkvirtualenv env-name
```
3.  Install dependencies 
```
pip install -r requirements.txt 
```
4. Activate the virtual environment

Linux/Mac
```
source env-name/bin/activate
```
Windows
```
env-name/script
activate
```

## Run Server: 
```
python3 manage.py runserver  
```

## Optional: Switch alias of python3 to python 
```
alias python="python3"
python manage.py runserver
```

## Push to Github
"Freeze" the current state of environment packages into requirements.txt so every person will have the same settings & versions. Don't push your virtual environment folders as is, b/c it won't be usable on every machine. 
```
pip freeze > requirements.txt
git add --all
git commit -m "some message"
```

## Deactivate Virtual Environment 
Upon completion :D 
```
deactivate 
```

