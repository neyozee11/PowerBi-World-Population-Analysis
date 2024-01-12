# Analysis of World Population

### Project Overview

This data analysis project endeavors to offer valuable insights into the global population's demographics. Through this exploration, my goal is to enhance understanding of the composition of the world population, considering factors such as the populations of diverse regions(countries and continents), age distributions and gender demographics.

### Data Source

The primary dataset used for this analysis are; "population-2010-2019.csv", "population-2020-2029.csv" and "population-2030-2040.xlsx"

### Tools

- PowerBi [Dowload here](https://powerbi.microsoft.com/en-us/downloads/)

### Steps

1. Loaded source files into the query editor
2. Cleaned data using the following steps:
- Removed blank and unwanted rows
- Used the append feature to combine information from the different source files into a single file containing all information from 2010 to 2040
- Removed unwanted columns
- Replaced incorrect values
- Gave the columns the appropriate data types
3. Using the duplicate and reference as appropriate, I split the table into one fact table and three dimension tables based on the category of information needed so as to have a 
   structured project
4. Used the merge feature to creat more columns to include the foreign keys and primary key into the fact and dimension tables respectively
5. Loaded the files into the data model for modelling, analysis and reporting
6. Based on the star schema modelling technique, I connected the primary keys of the dimension tables to the foreign keys in the fact table so as to establish a relationship
7. Created visuals and reports

### Concepts Applied

- DAX Concepts: Calculated columns and Calculated measures
- Data Modelling: Star Schema

### Analysis/Findings

The analysis and findings from this data are as follows:
The world population steadily grows with each passing year and at any point in time, Asia has the highest percentage of the world population. Also, the adult category has the highest number of population of each region except for Africa, which also makes it the age category with the most population.

### Recommendation

This analysis serves as a replicable model for the actual world population, given that the dataset employed in this project, while not real, can be applied to both global and individual country censuses.



