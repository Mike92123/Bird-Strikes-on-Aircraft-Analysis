# README for Bird Strikes on Aircraft Analysis
## Overview
### Title: Bird Strikes on Aircraft Analysis
### Authors:

Mingxi Li (li.mingxi1@northeastern.edu)
Si Wu (wu.si3@northeastern.edu)
Zheng Zheng (zheng.zheng2@northeastern.edu)
Jiawei Zhou (zhou.jiaw@northeastern.edu)

This project analyzes bird strike incidents on aircraft, focusing on various flight phases across different years. Our primary aim is to identify high-risk factors and periods associated with these incidents, providing insights that can help mitigate these risks.

## Data Source
The data is sourced from the FAA's comprehensive database on bird strikes, offering detailed insights on the various factors and conditions under which these incidents occur.

## Contents
ERD Model and Relational Schema: Conceptual and logical models of the database schema.
Database Creation: Scripts to connect to MySQL, create the database, and set up the tables.
Data Loading: Instructions and scripts to load bird strikes data from a CSV file into the database.
Analysis Tasks: SQL queries and R scripts for data analysis, focusing on incidents per airline, airport, and year.
Visualizations: Graphical representations of bird strikes incidents per year during different flight phases.
Stored Procedures: MySQL procedure to remove a bird strike incident from the database.

## Requirements
R and RStudio
MySQL Server
RMySQL and DBI packages in R
Access to the bird strikes CSV data file
Setup and Usage
Build ERD Model and Relational Schema: Review the ERD and schema diagrams for understanding the database structure.
Create the Database: Run the provided R script to connect to MySQL and create the necessary database and tables.
Load the Data: Execute the R script to load data from the BirdStrikesData.csv file into the database.
Perform Analysis: Use the provided SQL queries and R scripts to analyze bird strike incidents.
View Visualizations: Generate and review the visualizations for a clearer understanding of the data.
Contribute
Contributions to this project are welcome. Please contact any of the authors for collaboration.

## License
This project is open-source and available under [license type].

## Acknowledgments
Special thanks to all contributors and Northeastern University for providing guidance and resources for this project.
