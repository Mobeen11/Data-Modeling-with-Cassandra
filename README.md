# ETL Data Modeling with Cassandra

## Project Description

The project is a music streaming application called Sparkify. They want to analyze the data and wants to know what songs user listening to. The application have dataset of songs and users activity. 

## Files Description

    - Project_1B_ Project_Template.ipynb: Contains the Data Modeling with Apache Cassandra database. It includes
        - Design tables to answer the queries outlined in the project template
        - Write Apache Cassandra CREATE KEYSPACE and SET KEYSPACE statements
        - Develop CREATE statement for each of the tables to address each question.
        - Load the data with INSERT statement for each of the tables.
        - Include IF NOT EXISTS clauses in your CREATE statements to create tables only if the tables do not already exist. 
        - Test by running the proper select statements with the correct WHERE clause
    
## ETL PipeLine
    - Implement the logic in section Part I of the notebook template to iterate through each event file in event_data to process and create a new CSV file in Python
    - Make necessary edits to Part II of the notebook template to include Apache Cassandra CREATE and INSERT statements to load processed records into relevant tables in your data model
    - Test by running SELECT statements after running the queries on your database
