# Analysis-on-Farmers-suicides
Title: Exploring Farmer Suicides in India: A Data Analysis Journey
I recently conducted a comprehensive analysis on farmer suicides in India, leveraging a dataset initially stored in a CSV file. Here are the key steps and findings:
Data Ingestion:
Read the CSV file into a Pandas DataFrame for initial exploration.
Database Connection:
Connected seamlessly to a PostgreSQL database using the psycopg2 library.
Data Transfer:
Transferred the DataFrame to the PostgreSQL database using the to_sql function.
Preprocessing and Cleaning:
Conducted thorough data preprocessing and cleaning to ensure data accuracy and reliability.
SQL Queries:
Utilized SQL queries to extract meaningful insights directly from the connected database.
Key Insight:
Uncovered a striking pattern where Maharashtra consistently exhibited the highest number of farmer suicides from 2017 to 2021. whereas I found some states which has 0 suicides in any of the year those are Goa, Jharkhand, Odisha, Tripura, Uttarakhand, West Bengal, Chandigarh, Delhi, Ladakh, Lakshadweep, Puducherry.
Visualization:
Visualized the data using line plots and bar charts to provide a clear representation of the trends.
