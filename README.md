# udacity-data-eng-project2
## Project 2: Data Modeling with Apache Cassandra from the Udacity Data Engineer Nanodegree Program

Project: Data Modeling with Cassandra
A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analysis team is particularly interested in understanding what songs users are listening to. Currently, there is no easy way to query the data to generate the results, since the data reside in a directory of CSV files on user activity on the app.

They'd like a data engineer to create an Apache Cassandra database which can create queries on song play data to answer the questions, and wish to bring you on the project. Your role is to create a database for this analysis. You'll be able to test your database by running queries given to you by the analytics team from Sparkify to create the results.

### Project Steps
Below are steps you can follow to complete each component of this project.

#### Modeling your NoSQL database or Apache Cassandra database
1. Design tables to answer the queries outlined in the project template<br>
2. Write Apache Cassandra **CREATE KEYSPACE** and **SET KEYSPACE** statements<br>
3. Develop your **CREATE** statement for each of the tables to address each question<br>
4. Load the data with **INSERT** statement for each of the tables<br>
5. Include **IF NOT EXISTS** clauses in your **CREATE** statements to create tables only if the tables do not already exist. We recommend you also include **DROP TABLE** statement for each table, this way you can run drop and create tables whenever you want to reset your database and test your ETL pipeline<br>
6. Test by running the proper select statements with the correct **WHERE** clause

#### Build ETL Pipeline
1. Implement the logic in section Part I of the notebook template to iterate through each event file in **event_data** to process and create a new CSV file in Python<br>
2. Make necessary edits to Part II of the notebook template to include Apache Cassandra **CREATE** and **INSERT** statements to load processed records into relevant tables in your data model<br>
3. Test by running **SELECT** statements after running the queries on your database<br>
