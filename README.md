# Salon Scheduler Application
A project for the Relational Database Certification at Freecodecamp.org. 
The `salon.sh` file provides the code to run a small application for a salon scheduler. The application takes an individuals selection of the service they would like to schedule, the time they would like, their name, and phone number.
The information is entered into a SQL database with three `tables`, `customers`, `appointments`, and `services`. The `appointments` table has foreign keys that references unqiue service IDs in the `services` table and customer IDs in the customers table.
