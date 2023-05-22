# SQLDataVerification
It is a Python script that checks the availability , accessibility, and row count (under user specified condition) of the table inside MySQl Server. 


# Desciption

It is a python scipt that has a web application to take input such as your User id , Password, Host name, Database name and an excel sheet containing the name of the tables and the conditions based on which the user wants to check the row count. 
It will connect to the MySQL server with user provided credentials and checks the availability , accessibility, and row count (under user specified condition) of the table inside MySQl Server by taking the inputs from the excel sheet. 
It will then create a consolidated excel sheet report with all the data available. If the users wants to send the report through mail, they can give the mail adddress of the recipient in the web interface and the mail will be automatically sent. How ever this option is optional.

# Technology Used 

Python

# Modules Used

from flask import Flask, render_template, request
openpyxl
datetime
mysql.connector
os
win32com.client
webbrowser 
