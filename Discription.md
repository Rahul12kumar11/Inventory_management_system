# Inventory_management_system

Cell 1:- In cell 1 we store the whole inventory in single unit by using nasted dictinory 
          Where we have product id as its key and informations like name of the product, price of the product, quantity of the product, expery date of the product and it's type
          that store into a another dictinory 
          
Cell 2:- We import json and create of new file called Record.json
          Then we use json.dumps to convert the dictionary into text
          then we use the json.load to convert the text into a dictinory
          and we also import time for using it in cell 3

Cell 3:- Cell 3 is our main execution file where we first ask user thier identity, User have to be a producer or a customer other wise they can't enter the program
          if user is a producer
          then we ask the producer to enter the password, producer must have enter the correct password to execute other things
          after entering the correct password we ask producer
          Enter Add or add to add a new product in previous inventory
          Enter Update or update to change the quantity of previous product in the inventory
          if user is a customer 
          then we run a while loop untill is True
          in while loop we tell user to enter the product id to purahcse a product other wise type 0 to exit loop
          Customer enter the product id, if product id is between 101 to 130 
          then we ask user to enter the quantity of the product
          if quantity is excedd then we a msg is that stock is full
          else, customer is ready to purchase 
          
          then we ask customer that he want to print the bill if yes then we the bill otherwise the exection is end. 
          
          
