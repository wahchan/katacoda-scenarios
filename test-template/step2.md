Execute the following command to  access the databse using mysql client as a root user

`docker-compose exec db  mysql -u root -p`{{execute}}


You need to enter the password:
`mypassword`{{copy}}

# After enter the database
You can view the databases by:
 `show databases;`{{execute}}


# You may also visit the woocommerce website

View the Home page at port 8080 
<br>

http://[[HOST_SUBDOMAIN]]-8080-[[KATACODA_HOST]].environments.katacoda.com/wp-login.php

username: testuser
<br>
password: testpassword
<br>
email: testuser@test.com

# After log in
Create the woocommerce site by install plugin
![plugin](./assets/plugin.png)
<br>
You need to type the following to start the store

![start](./assets/start.png)

<br>

After that , need to create a new user to browse the store
![create_user](./assets/creatw_user.png)

<br>

# After the above step
open the following by the new account:
<br>
https://[[HOST_SUBDOMAIN]]-8080-[[KATACODA_HOST]].environments.katacoda.com/










