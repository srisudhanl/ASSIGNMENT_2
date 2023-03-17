# Assignment-2 By, L.Srisudhan (20ITR106) IT-B
COLUMN FAMILY DATABASE

HBase is an open-source, column-oriented database management system (DBMS) that is designed to handle large volumes of structured data. It is built on top of Apache Hadoop, which provides HBase with the ability to store and manage massive amounts of data across distributed clusters of commodity hardware.

HBase is a NoSQL database that provides real-time read/write access to large datasets. It is commonly used in applications that require fast and random read/write access to very large datasets, such as social networks, online advertising, financial services, and web analytics.

Fireworks Shop Application is used to organize and manage the details of customer,items1,items2,items3,salesman details.It will manage the types of items sold in shop and customer details and details of salesman.This configuration includes ,
   
    1)Customer name,id,brand,discount
    2)Items_1 itemname,id,price
    3)Items_2 itemname,id,price
    4)Items_3 itemname,id,price
    5)Salesman name,id,salary

The database supports five entities:
     1)Customer Information abbreviated as 'cust'
     2)Items_1 abbreviated as 'item_1'
     3)Items_2 abbreviated as 'item_2'
     4)Items_3 abbreviated as 'item_3'
     5)Salesman Information as 'salesman'

The data is stored as a column family database and id as row-key and other attribute as column.Each set has two-three column with row-id associated with it.

For cust entity the attributes are: name,id,brand,disc
For item_1 entity the attributes are itemname,id,price
For item_2 entity the attributes are itemname,id,price
For item_3 entity the attributes are itemname,id,price
For salesman entity the attributes are name,id,salary

To make the above operation I used the following keywords:

     put- put keyword is used to insert and update the values of the family in the table.

     scan- scan keyword is used to display the entities of the table we have created.

     create- create keyword is used to create the table.

     delete- delete keyword is used to delete the value as well as the table.
     
Column-family databases are a powerful tool in the world of data management, and their popularity is only expected to grow as organizations continue to generate and collect more and more data.
