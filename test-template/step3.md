# Address as PII
The billing address and shipping address of each customer is a type of PII . This is a sensitive information that related to customer privacy.



# In the woocommerce website
After you login , select my acocunt to edit the name
Follow the below example
![account](./assets/account.png)

![account_example](./assets/account_example.png)
And edit the billing address , shipping address
![address](./assets/address.png)


# Set shipping address
Set the shipping address as following
![shipping_address1](./assets/shipping_address1.png)
![shipping_address2](./assets/shipping_address2.png)


# Set billing address
Set the billing address as following
![billing_address1](./assets/billing_address1.png)
![billing_address2](./assets/billing_address2.png)
![address_example](./assets/address_example.png)







# Check for the shipping address
You can view the information related to shipping address by:
 `select * from wordpress.wp_usermeta where meta_key like "%shipping%";`{{execute}}
 <br>
 You will find out the information of first_name ,last_name,city,state,country
 <br>
 which will combine to form an address.


![shipping_query](./assets/shipping_query.png)


# Check for the billing address
 You can view the information related to billing address by:
 `select * from wordpress.wp_usermeta where meta_key like "%billing%";`{{execute}}
 <br>
 You will find out the information of first_name ,last_name,address,city,state,country
 <br>
 which will combine to form an address.
Also , it will shown user's email and phone as well.



![billing_query](./assets/billing_query.png)













