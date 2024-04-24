# DBMS-Expt03

## Aim
To learn and practice the uses of Update , Delete and Select in SQL.

### 1.Write a SQL query to identify customers who do not belong to the city of 'New York' or have a grade value that exceeds 100. Return customer_id, cust_name, city, grade, and salesman_id.
![Screenshot 2024-04-24 143107](https://github.com/Harsayazheni/DBMS-Expt03/assets/118708467/f122f32d-1c14-414b-b8de-77e2c5f45d66)

#### Program
```
SELECT customer_id, cust_name, city, grade, salesman_id
FROM customer
WHERE grade = 100;
```
#### Output
![Screenshot 2024-04-24 143139](https://github.com/Harsayazheni/DBMS-Expt03/assets/118708467/11a20438-1f36-432b-b341-a56f519512e4)

### 2.write a SQL query to find details of all orders with a purchase amount less than 200 or exclude orders with an order date greater than or equal to '2012-02-10' and a customer ID less than 3009. Return ord_no, purch_amt, ord_date, customer_id and salesman_id.
![Screenshot 2024-04-24 143227](https://github.com/Harsayazheni/DBMS-Expt03/assets/118708467/7308b320-e9d7-4a7e-b247-e9ffb0ffac9e)

#### Program
```
SELECT ord_no, purch_amt, ord_date, customer_id, salesman_id
FROM orders
WHERE (purch_amt < 200) OR (ord_date <= '2012-10-10' AND customer_id >= 3009);
```
#### Output
![Screenshot 2024-04-24 143254](https://github.com/Harsayazheni/DBMS-Expt03/assets/118708467/66015547-941a-46d5-a5ce-9cd4b94662e3)

### 3.Write a SQL query to find the details of those salespeople who live in cities other than Paris and Rome. Return salesman_id, name, city, commission.
![Screenshot 2024-04-24 143332](https://github.com/Harsayazheni/DBMS-Expt03/assets/118708467/25db1b42-a408-4732-b827-14f541edb10c)

#### Program
```
SELECT salesman_id, name, city, commission
FROM salesman
WHERE city NOT IN ('Paris', 'Rome');
```
#### Output
![Screenshot 2024-04-24 143404](https://github.com/Harsayazheni/DBMS-Expt03/assets/118708467/ae6b933a-edc9-41f3-903b-ac770fff0b73)

### 4.Write a SQL query to find customers who are either from the city 'New York' or who do not have a grade greater than 100. Return customer_id, cust_name, city, grade, and salesman_id.
![Screenshot 2024-04-24 143440](https://github.com/Harsayazheni/DBMS-Expt03/assets/118708467/08cde6ef-d0d9-4aa1-afaf-375345d4044b)

#### Program
```
SELECT customer_id, cust_name, city, grade, salesman_id
FROM customer
WHERE city = 'New York' OR grade <= 100;
```
#### Output
![Screenshot 2024-04-24 143507](https://github.com/Harsayazheni/DBMS-Expt03/assets/118708467/e28b80c6-4a89-47be-8d72-94df0321ab9b)

### 5.Write a SQL query to reduce the reorder level by 30% where cost price is more than 50 and quantity in stock is less than 100 in the products table.


#### Program
```

```
#### Output

## Result
Thus , Create , Alter and Insert in SQL is practiced successfully.
