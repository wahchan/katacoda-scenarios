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
<br>

# Setup
First, need to setup the webapge
<br>
Choose English as language
![English](./assets/English.png)

<br>
Then ,create the webapge with following information
![Detail](./assets/Detail.png)
username: testuser
<br>
password: testpassword
<br>
email: testuser@test.com
<br>

# Login
You can login the webpage by 
Username:`testuser`{{copy}}
Password:`testpassword`{{copy}}
![Login](./assets/Login.png)

# After log in

Create the woocommerce site by install plugin
![plugin](./assets/plugin.png)
<br>
You need to type the following to start the store

![start](./assets/start.png)

<br>

Select fashion,apparel and accessories as industry
![Industry](./assets/Industry.png)
<br>
Select physical products as product to sell
![Typeofproduct](./assets/Typeofproduct.png)
<br>
11-100 as number of product
![Number](./assets/Number.png)
<br>
Select the default theme
![theme](./assets/theme.png)


<br>
After that , need to create a new user to browse the store
![create_user](./assets/create_user.png)

<br>
Here is the list of user
![User_all](./assets/User_all.png)

<br>

# After the above step
open the following by the new account:
<br>
https://[[HOST_SUBDOMAIN]]-8080-[[KATACODA_HOST]].environments.katacoda.com/










