## IMS
### Overview
This is a Inventory Management System for Super Market where I have created two options one is for customer who purchases the products and another for seller where the products are added to the inventory so that customers can buy the products.And I have stored the products in Json File.And have also created a separate JSON File for sales which will show the products along with their details that are sold.

### Brief Description
This is a super market inventory system. I have coded in such a way that first the available products along with its price and available quantity is listed.Then the user has to enter whether he/she is a customer or seller by typing 1 or 2.If user types other than 1 0r 2 then the output is displayed as Invalid Output and the program is stoped.If the user types 1 then the user is a customer and he/she has to type the number of products they want to purchase along with the quantity of that particular product.If the no of products are greater than number of products in inventory or wrong values then the ouput will be displayed as invalid no of products and will list the no of products available in the inventory.And also it checks whether the entered quantity by the customer is less than or equal to the available quantity in the inventory.If suppose that quantity is greater than the total quantity in the inventory then the ouput is displayed as the product is out of stock.And asks the user whether to proceed with the remaining products or not. Now the bill is generated with the details like Product_Id,Items,MRP,Amount,Quantity,Expiry Date and Time&Date of Purchase.HereI got the Time&Date of Purchase by importing time module in python.In this bill,bill Number is generated using random module.Discount(if the total amount is greater than 500),Total Amount,Bill Amount,Total Items,Total Quantity,Total Savings(this is showed only if the total amount is greater than 500) are all calculated in the program.Or if suppose the user is a seller he/she has to give the correct username and password inorder to add the products in the inventory and all the details about the product has to be entered by the seller which is directly stored in the inventory.

### Username and Password For Seller Login
Username:MariaAdeline
Password:maria20

### In this Repository..
JSON, NOSQL Databases, File Handling.

### Files
I have included 3 files:
1)sales.json - Stores the products along with their details that the customer purchases.
2)record.json - This is where the products of the supermarket is stored and the quantity of products available is also updated here.
3)INVENTORY.ipynb - This is the main execution part of the program.

### Main Features
1)Displaying Available Products along with the available quantity and price.
2)Generates Bill.
3)Update the inventory with available quantity.
4)Add New Items which is done by the seller.
5)Customers Can purchase the products.
6)Sales record is maintained.(sales.json)
7)The seller can also delete a particular product if not required.
8)Discount and Total Savings are also calculated in the bill.(if the total amount is greater than 500)

### Product Features
1)Product Id
2)Items
3)Quantity
4)MRP
5)Amount
6)Expiry Date
7)Date&Time of Purchase
There are currently 39 products available in the inventory(record.json).

### About Me
My name is Maria Adeline P and I'm a 3rd year B.E CSE student studing in SRM Easwari Engineering College,Chennai,TamilNadu 600125. I'm passionate about Data related fields like Data Analytics and also interested in python language.I am willing to learn, work and gain some experience in this field.
