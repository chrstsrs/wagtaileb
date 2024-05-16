# WagtailWeb

This is a wagtail webpage with a blog. 

Requires Docker.

There are two containers. One for the wegtalweb app and one for the database that is postgresSQL.

The steps you have to follow after you download the project

There is a file named envsample. Rename it to .env.

The next steps require a bash terminal.
### Build the containers
```bash
docker-compose -f docker-compose.development.yml -f docker-compose.yml build
```
### Start the containers

```bash
docker-compose -f docker-compose.development.yml -f docker-compose.yml up
```

### Access the Admin panel.
Open in a browser the url
```bash
http://127.0.0.1:8000/admin
```
and you will see the login page.
Use the credentials: 

username: admin

password: adminpassword

and you are in the admins page. 
This is where you can create the webpages you like, uploading images and creating content.

### Stop the server
In the bash terminal type
```bash
  ^C
```

### If you want to remove the containers with the volume
In the bash terminal type
```bash
docker-compose -f docker-compose.development.yml -f docker-compose.yml down -v
```
These are the minimum changes. However, it is recommended to change the credentials.


## Author

- Charisios Tsiairis[@chrstsrs](https://www.github.com/chrstsrs)
