# grocery_store-IMS
An Inventory Management System project using Python and json. I have used Anaconda navigator as my IDE.


## Table of Contents
1. [General Info](#general-info)
2. [Inventory](#inventory)
3. [User Interface](#user-interface)
    1. [Owner User Interface](#owner-user-interface)
    2. [Customer User Interface](#customer-user-interface)
4. [Sale Record](#sale-record)

***
## General Info
In this project, I have built an inventory management system for a grocery store. 
It contains 3 file:
  * inventory.json - contains all product items and their details
  * sales.json - record of each transaction 
  * Grocery Store IMS.ipynb - backend program using Python

***
## Inventory
  * Attributes:
    * name
    * brand
    * category
    * weight
    * price
    * quantity
  
The inventory is created using python data structure ***dictionaries*** and is then converted into a json file using json.dump() function available in ***python in-built library json***

***
## User Interface
The user interface is divided for two types of users. Their are different functionalities for different types of users.
  * Owner 
  * Customer
  
    ### Owner User Interface
    Functionalities: 
      * Displaying the inventory
      * Adding Items to the Inventory
      * Increasing stocks or prices of products present in inventory
      * Deleting item from the inventory
      * Checking the sales record using sales.json file
      
    ### Customer User Interface
    Functionalities:
      * Displaying the products category wise
      * Asking customer how many products they want to purchase
      * Placing an order
      * Checking availability of product
      * updating sales.json file at each transaction
      * creating a receipt.txt file and displaying it as a receipt to user. 
      * Deleting the contents of receipt.txt file using truncate() function so that a new receipt can be created for each customer.
      
***
## Sale Record
Each transaction details are added in sales.json file.
  * Attributes:
    * Product Name
    * Brand
    * Weight/Size
    * Cost per unit
    * Quantity
    * Cost


***
***I would like to thank Ashish Jangra Sir and ETG platform for providing me with this amazing opportunity and guiding me throughout the way .*** 
