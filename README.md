# ScrataScratch-SQL

##  Easy

[Customer Details](https://platform.stratascratch.com/coding/9891-customer-details?python=)


`select c.first_name,
c.last_name,c.city, 
o.order_details
FROM customers as c LEFT JOIN orders as o on c.id = o.cust_id
ORDER by c.first_name`

_Screenshot showing first 5 records only._
![image](https://user-images.githubusercontent.com/48564899/159240234-390a1ebe-09c6-49e7-8b4a-0db9d00fc556.png)
