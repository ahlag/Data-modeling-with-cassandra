# Project 1: Data modeling with Cassandra

## Introduction

A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analysis team is particularly interested in understanding what songs users are listening to. Currently, there is no easy way to query the data to generate the results, since the data reside in a directory of CSV files on user activity on the app.

They'd like a data engineer to create an Apache Cassandra database which can create queries on song play data to answer the questions, and wish to bring you on the project. Your role is to create a database for this analysis. You'll be able to test your database by running queries given to you by the analytics team from Sparkify to create the results.

## Project Overview

In this project, you'll apply what you've learned on data modeling with Apache Cassandra and complete an ETL pipeline using Python. To complete the project, you will need to model your data by creating tables in Apache Cassandra to run queries. You are provided with part of the ETL pipeline that transfers data from a set of CSV files within a directory to create a streamlined CSV file to model and insert data into Apache Cassandra tables.

We have provided you with a project template that takes care of all the imports and provides a structure for ETL pipeline you'd need to process this data.

## Aim

The aim of this project is to define a data model that will help our data scientists answer questions about user activity. In this case, we are working with a NoSQL database, Apache Cassandra, which means we have to be especially intentional in our data modeling. We first need to understand what queries our data scientists would like to run, and then we can design tables to fit those queries. We will be aiming for "1 query, 1 table".

## Project structure
1. **event_data** folder nested at the home of the project, where all needed data reside.
2. **Project_1B_ Project_Template.ipynb** the code itself.
3. **event_datafile_new.csv** a smaller event data csv file that will be used to insert data into the Apache Cassandra tables.
4. **images** a screenshot of what the denormalized data should appear like in the event_datafile_new.csv. 
5. **README.md** current file, provides discussion on my project.

## How to Use

Launch **Project_1B_ Project_Template.ipynb** to run validation and example queries.
