# Getting Started
This api need [python](https://www.python.org/) v3+ to run.

Install the requirements from requirements.txt file
```
$ pip install -r requirements.txt
```

Change SECRET_KEY variable in shortener/setting.py to your secret key.
![before](https://i.postimg.cc/SKj3K0Dr/Screenshot-from-2022-06-24-16-27-54.png)
![after](https://i.postimg.cc/yxrSsZdn/After-Secret-Key.png)

Copy and paste this into the terminal
```
python manage.py makemigrations
python manage.py migrate
python manage.py collectstatic 
```

To post data on the api you need an admin user.
Create a superuser
```
python manage.py createsuperuser
```

And last but not least, Run the server
```
python manage.py runserver
```
