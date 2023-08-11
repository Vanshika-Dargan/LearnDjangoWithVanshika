# How to Setup Django Locally On Your Windows System

This commands setup a python virtual environment on windows. Virtual environments are isolated environments where you can install packages and dependencies seperately from system wide python installation. This is useful for managing different projects with varying requirements
```bash
  pip install virtualenvwrapper-win
```
Now create a virtual environement test
```bash
  mkvirtualenv test
```
Now install django within this virtual environment
```bash
  pip install django
``` 
Check if django is installed properly
  ```bash
 django-admin --version
```
    
