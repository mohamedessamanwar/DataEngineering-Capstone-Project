# Data Engineering Capstone Project

## Overview
The purpose of this project is to give a chance to combine what I've learned throughout the Udacity Data Engineering Nanodegree program.

## Project Summary
In this project data gathered from four datasets with different sources for analysing US immigration data in a simple star schema. The main aim is to provide analytics to answer business questions which can be analyze and provide insight into the pattern of immigration. The analysis questions can be answered based on the data model using simple joins. Spark was used for the ETL pipeline and The final data is stored in parquet files for analysis.

The project uses Apache Spark engine. Spark is a simple and fast and also scalable analytics engine for large scale data processing. It has an ability to process and analyse massive ammounts of data using PySpark interface. Can handle different data formats (e.g. SAS, Parquet, CSV), and can be integrated with cloud storage solutions like S3 or Redshift.

## Project Datasets:

- I94 Immigration Data: This data comes from the US National Tourism and Trade Office. 
- U.S. City Demographic Data: This data comes from OpenSoft.
- Airport Code Table: This is a simple table of airport codes and corresponding cities.

## Project Data Model
The chosen data model was the star schema, That model was the chosen one because it allows great performance, and it also allows users to write simple queries joining the fact and dimension tables in order to achieve the analytical dataset they need and perform BI solutions.
