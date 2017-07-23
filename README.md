# polls

This website I created while learninig Django from the official docs of Django.  
Reference: https://docs.djangoproject.com/en/1.11/intro/  

It contains basic functionality like creating polls and their corresponding choices, and people will vote for the choices given
with the poll.

### To clone this project type: 
```
$git clone https://github.com/rajeshtezu90/polls.git
```

### Before start exploring the project one need to install following:  
Django 1.11

### To start playing with the website:
Navigate to polls folder containg manage.py file and type:  
```
$python manage.py makemigrations  
$python manage.py migrate
```

### Now run the follwing command in the terminal:
```
$python manage.py runserver
```

and then open the follwoing url in your favorite web browser:  
http://localhost:8000  

### Create a super user to use the admin page:
```
$python manage.py createsuperuser
```

Now navigate to http://localhost:8000/admin page and create some polls and their choices. Go to home page and explore 
your website 




