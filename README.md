# Housing Market Analysis

This project performs housing market analysis using the Redfin housing market dataset. It allows the user to understand the housing market trends and make informed
decisions on buying a house. As we are using big data that requires replication and sharding for faster processing, our application appreciates NoSQL deployment rather than RDBMS.

Dataset - This dataset is the Redfin monthly housing market dataset by Redfin–one of the biggest real estate brokerages on the market. This dataset is obtained from
multiple local listing services as well as from Redfin real estate agents across the country. The original size of this dataset is 2.2 GB and the size of the dataset
after wrangling is 1GB.


Housing_market_analysis.ipynb - Contains Python code to connect to the NoSQL database and provides an interface to perform various actions like serach, view, and compare

commands_to_update_database.ipynb - This Python file gives commands to perform various operations such as insert, delete, and update on the database.
