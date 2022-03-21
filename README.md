# ScrataScratch-SQL

##  Easy

[Customer Details] (https://platform.stratascratch.com/coding/9891-customer-details?python=)


`select c.first_name, c.last_name,c.city, o.order_details
FROM customers as c LEFT JOIN orders as o on c.id = o.cust_id
ORDER by c.first_name`
