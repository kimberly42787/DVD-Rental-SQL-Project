# Investigating Sakila DVD Rental Database

### Introduction
In this project, I used SQL(PostgreSQL) to gain insights and create visualization on the Sakila DVD Rental Database. 

I will be analyzing the database to answer certain questions the company would find beneficial in  order to increase profits. This consists of finding patterns on revenue, which kind of movies are being rented out more, and how do the two stores compare to each other in terms of profits and number of rentals. 

Because this is a PostgreSQL Database, I will be using the pgAdmin tool to write all of my queries. Then, I will be connecting the database to Python to create visualizations to show my findings.

### Database

There are 14 tables in the database. Each table holds specific information about the company. 
- category - Stores the name of each category
- film_category - Stores the relationship between the film and the film's category
- film - Stores information regarding the films
- film_actor - Stores the relationship between the films and the actors
- actor - Stores information regarding the actors
- staff - Stores staff's information
- payment - Stores costumer's payment data
- rental - Stores rental data
- inventory - Stores inverntory data
- customer - Stores information about the customers
- address - Stores address data
- city - Stores city names
- country - Stores country names
- store - Stores information about the stores

The database and the ERD (Entity Relationship Diagram) can be found here in the project's folder

### Analysis: 

