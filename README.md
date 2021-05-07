# Lift

## Abstract:
LIFT: A Cab Management System, is a web-based application useful for car
travel agencies for handling their data and bookings. Implemented using
SQLITE3 and Streamlit, this project aims at managing overall car services by
handling finance, human resource, maintenance and movement in addition to
details of customers, employees, payment and types of cabs.

## Structure of the Database Used:
* **Customer Table:** This table is identified by _USER ID_ as Primary Key,
and contains the User’s Name and Contact Number.
* **Drivers Table:** This table is identified by _EMPLOYEE ID_ as Primary
Key and contains the Driver’s Name, his Vehicle’s Registration
Number and type of Vehicle (Mini, Sedan, SUV).
* **Bookings Table:** This table is identified by _BOOKING ID_ as Primary
Key and contains Users’ and their respective Drivers’ details.

## Technologies Used:
The Web Application was primarily developed in Python3 language. The modules and technologies that were used to design the application are as follows:
* Pandas
* SQLITE3 (Database)
* Numpy
* Streamlit (UI Development)
* Heroku (Hosting)
* Atom (Text Editor)
