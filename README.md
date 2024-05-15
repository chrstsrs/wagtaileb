# WagtailWeb

This is a wagtail webpage with a blog.

The steps you have to follow are:

### Clone the project
create a virtual environment 
```bash
python -m venv venv
```
### Go to the project directory

```bash
  cd wagtailweb
```

### Activate the virtual environment
```bash
source venv/Scripts/Activate
```

### Install the requirements
```bash
pip install -r requirements.txt
```

### Create the migrations
```bash
python manage.py makemigrations
```

### Apply the migrations
```bash
python manage.py migrate
```

### Create the superuser
```bash
python manage.py createsuperuser
```

### Start the server
```bash
python manage.py runserver
```
Go to the admin page
http://127.0.0.1:8000/admin
login as the superuser and you are in the admins page. 
This is where you can create the webpages you like, uploading images and creating content.

### Stop the server
```bash
  ^C
```

## Author

- Charisios Tsiairis[@chrstsrs](https://www.github.com/chrstsrs)
