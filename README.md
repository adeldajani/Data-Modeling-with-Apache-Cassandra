# Introduction
A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analysis team is particularly interested in understanding what songs users are listening to. Currently, there is no easy way to query the data to generate the results, since the data reside in a directory of CSV files on user activity on the app.

They'd like a data engineer to create an Apache Cassandra database which can create queries on song play data to answer the questions, and wish to bring you on the project. Your role is to create a database for this analysis. You'll be able to test your database by running queries given to you by the analytics team from Sparkify to create the results.

# Project Description
In this project, we'll do data modeling with Apache Cassandra and complete an ETL pipeline using Python. To complete the project, you will need to model your data by creating tables in Apache Cassandra to run queries. You are provided with part of the ETL pipeline that transfers data from a set of CSV files within a directory to create a streamlined CSV file to model and insert data into Apache Cassandra tables.

We have provided you with a project template that takes care of all the imports and provides a structure for ETL pipeline you'd need to process this data.

# Prerequisites

* Python 3 available
* pandas and psycopg2 available

# Data 
For this project, we'll be working with one dataset: event_data.


# Files

**1-etl.ipynb: This file containes teh ETL Pipeline for Pre-Processing the files, and will create a cluster, and a keyspace and set the keyspace.**

**2- event_datafile_new.csv: containes the new data after the manipulations.**

**3- event_data.zip: containes the original data.**
