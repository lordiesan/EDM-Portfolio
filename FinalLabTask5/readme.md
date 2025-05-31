## Final Term Lab Task 5 - Using SQL views and Stored Procedures and Stored Functions

1. To have an idea of how SQL views work, kindly read the lecture on SQL views and stored procedures, then you may try the following examples in MySQL Workbench: 
2. Start Xampp and MySQL Workbench – create or start a connection 
4. Open the democodes.sql, and you may try executing all the examples using the hrd.sql file

5. AFTER the practice codes…. Perform the required SQL statements of the ff: use inventory.sql for this.


6. Print screen the appropriate sql and output per item

* 1 <ins>CREATE A VIEW that will display the vendors_code, vendors name, product description p_indate, of all products with p_indate from 2002 onwards
> ![Sample Output](IMAGE/1.PNG)

# *Task 2*
* <ins>Add a CHECK constraint to ensure that the price of the product must be greater 
than 0.
> ![Sample Output](IMAGE/3.PNG)

# *Task 3*
* <ins>Insert the products that will not violate the check constraint into the products 
table
```
Product 1: "Laptop", 999.99 
Product 2: "Headphones", -49.99 
Product 3: "Smartphone", 599.99 
Product 4: "Tablet", 299.99 
Product 5: "Monitor", -149.99 
Product 6: "Keyboard", 19.99 
Product 7: "Mouse", 14.99 
Product 8: "Desk Lamp", 24.99 
Product 9: "External Hard Drive", -79.99 
Product 10: "Speakers", 9.99 
```
>![Sample Output](IMAGE/2.PNG)

# *Task 4*
* <ins>Modify the product_name field to have a maximum length of 120 characters
> ![Sample Output](IMAGE/4.PNG)

## **EER**
![Sample Output](IMAGE/EER%20task%203.PNG)

