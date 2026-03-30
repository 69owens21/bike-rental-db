###Bike Rental Shop CLI & Database

##Description
This project is an interactive Command-Line Interface (CLI) application built with Bash and backed by a PostgreSQL database. It simulates a bike rental shop management system, allowing users to view available inventory, rent bikes, and process returns.
The project demonstrates full-stack terminal application development, including relational database design, data manipulation, and bash scripting with user input validation.

##Features
#Interactive CLI Menu:
- A user-friendly terminal interface that guides the user through renting or returning a bike.
#Dynamic Inventory Management:
- Queries the PostgreSQL database in real-time to only display bikes that are currently available or specifically rented by the active customer.
#Automated Customer Tracking:
- Seamlessly checks for existing customers using their phone number and automatically registers new customers during the rental checkout process.
#Database Integration:
- Executes complex SQL queries (including INNER JOIN operations) directly from the Bash script using the psql utility.

##Files Included
#bike-shop.sh:
- The main executable Bash script containing the program logic and menu systems.
#bikes.sql:
-  A PostgreSQL database dump containing the complete schema (bikes, customers, and rentals tables) and the initial seeding data.

##Technologies Used
#Bash Scripting:
- Variables, conditionals, loops, functions, and regular expressions.
#PostgreSQL:
- Table creation, primary/foreign key constraints, sequences, and querying.
#Linux Command Line:
- Text processing with sed and echo.

##Setup and Installation
#1. Rebuild the Database
- To recreate the database locally, run the provided SQL dump file using PostgreSQL:

##Bash
psql -U freecodecamp -d postgres < bikes.sql
#2. Run the Application
- Ensure the script has execution permissions, then run it in your terminal:

##Bash
- chmod +x bike-shop.sh
- ./bike-shop.sh
  Author
Gracie Owens
