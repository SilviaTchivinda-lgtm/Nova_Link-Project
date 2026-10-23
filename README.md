NovaLink Telecom Ltd. is a telecommunications provider offering mobile voice, data and digital services across multiple regions.

The company wants to use customer behaviour, product adoption and subscription data to improve service quality, increase retention and support analytics-driven decisions.

## Dataset 
The data contains 1,000 sales records with information including:

Customer information
Order information
Product information
Order revenue
Payment method
Sales channel
Order status
Delivery status
Customer ratings
Return information

## Tools Used 
Python
Pandas
Jupyter
Github
PgAdmin 4
PostgreSQL

## Database Tables 

The data was organised into the following tables:

Costumers
Products
Orders
Order_items
Deliveries

## Analysis 
The Project includes calculation for

Total revenue
Total number of order
Revenue by product
Revenue by sales channel
Delivery performance

## Project Objectives 
The main objectives are to:

Tack Business Sales:

Customer Purchasing Behavior
Product Performance
Revenue and order fulfilment
Organise the data:

Store the sales data in PostgreSQL
Organise the data into structured tables
Maintain the original dataset
Calculate important sales metrics
Use SQL queries to support business analysis

## Author
Silvia Tchivinda

## Setup Instructions:

Step by step how to create a project on python

•	Create a folder on your laptop

•	Open VS code- click on open folder

•	Click on the folder created – select folder

•	Open your terminal on GitHub – Add Git bash 

On Git bash write:
1.	 python -m venv urbannest – to create a copy of the project

2.	source urbannest/scripts/activate

•	Go to your GitHub:

1.	New repository – name the created repository as your project 

2.	Get the link generated on GitHub to enable you to link with your VS code

3.	Copy the link: 

git remote add origin https://github.com/SilviaTchivinda-lgtm/Nova_Link-Project.git

•	Open VS code (The same terminal)- Write git init

•	 Paste the copied link – Press enter

•	Git remote  -v (Terminal)

•	Create a new file and name it

•	Create a new file .gitignore 

•	Create a new file Readme.md

•	Add the data: git add . (Terminal)

•	git commit -m "add novalink dataset" (Terminal)

•	git push (Terminal)

•	Copy the link (on Terminal): git push --set-upstream origin main

•	Getting a branch to work on: git branch nova (Terminal)

•	Work on the branch created: git checkout nova (Terminal)

To Instal Pandas notebook:
1.	Pip install pandas notebook  

•	Create a jupyter file: novalink_telecom.ipynb

•	Choosing the Kernel: click select kernel- python

•	Code cell: import pandas as pd - run

Short sample of the project

•	Code cell: novalink_df=pd.read_csv('./data/NovaLink_Telecom_Dirty_Exploration_Dataset.csv')

•	Code cell: novalink_df.info()

•	Code cell: gender = novalink_df["gender"].astype("string").str.strip().str.casefold()

•	novalink_df["gender"] = gender.replace({

•	    "m": "Male",

•	    "male": "Male",

•	    "f": "Female",

•	    "female": "Female",

•	    })


