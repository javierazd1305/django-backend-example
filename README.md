# Django backend simple example
This is is a basic django backend to make post request.

# Usage
```python
git clone https://github.com/javierazd1305/react-colatics.git
pipenv shell
pipenv install -r requirements.txt
python manage.py runserver
```

Also you should change in setting.py
```python
ALLOWED_HOST = ["your host"]
CORS_ALLOWED_ORIGINS = ["your host"]
```


# Deploy
This example has the files needed for Heroku deployment. 
When you create your app in Heroku you need to set Collecstatic = 1 with the following code 
```bash
heroku config:set DISABLE_COLLECTSTATIC=1
```

# Recommendations
Use github deployment method so you only need to push your updates to github and automatically heroku is going to build the changes.