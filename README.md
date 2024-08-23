# UK Food Establishments Database - Analysis Setup

## Overview

This project involves setting up and updating a MongoDB database containing data on food establishments in the UK. The work is divided into two main parts:

### Part 1: Database and Jupyter Notebook Setup
### Part 2: Updating the Database
Prerequisites

Ensure you have the following installed before starting:

Python (preferably version 3.7 or higher)
MongoDB
Jupyter Notebook
PyMongo library (install using pip install pymongo)

## Part 1: Database and Jupyter Notebook Setup

### Step 1: Import the Data
Begin by importing the establishments.json data into MongoDB. This is done via the Terminal using the mongoimport command.

### Step 2: Set Up Your Jupyter Notebook
Import the necessary Python libraries such as PyMongo and Pretty Print (pprint).
Create an instance of MongoClient to connect to MongoDB.
Confirm that the uk_food database was successfully created by listing the available databases.
Assign the uk_food database to a variable for easy access in your notebook.
Verify that the establishments collection is present by listing the collections in the uk_food database.
Retrieve and display one document from the establishments collection to confirm the data was loaded correctly.
Step 3: Assign the establishments Collection
Ensure that the establishments collection is assigned to a variable to facilitate further queries and operations.

## Part 2: Updating the Database

### Step 1: Add a New Restaurant
A new halal restaurant, "Penang Flavours," has opened in Greenwich and needs to be added to the database. Include all relevant details, ensuring the new restaurant is recorded accurately.

### Step 2: Update the Business Type ID
Identify the BusinessTypeID for "Restaurant/Cafe/Canteen" and update the newly added restaurant with this ID to ensure consistency in the database.

### Step 3: Remove Establishments in Dover
The magazine is not interested in establishments located in Dover. Remove all documents related to establishments in Dover from the database.

### Step 4: Convert Data Types
Some values in the database, such as latitude, longitude, and RatingValue, are stored as strings but should be numeric. Update these fields to the correct data types to maintain data integrity.

## Conclusion

After completing these steps, the MongoDB database will be properly set up and updated, making it ready for analysis. Ensure all operations are verified by checking the database after each update.

