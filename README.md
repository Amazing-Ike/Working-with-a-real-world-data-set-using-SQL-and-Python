# Working-with-a-real-world-data-set-using-SQL-and-Python

This project is an analyses of the Chicago Public Schools - Progress Report Cards (2011-2012) using SQL and Python libraries

Objectives
After complting this project you will be able to:

Understand the dataset for Chicago Public School level performance
Store the dataset in SQLite database.
Retrieve metadata about tables and columns and query data from mixed case columns

The city of Chicago released a dataset showing all school level performance data used to create School Report Cards for the 2011-2012 school year. The dataset is available from the Chicago Data Portal: https://data.cityofchicago.org/Education/Chicago-Public-Schools-Progress-Report-Cards-2011-/9xs2-f89t

This dataset includes a large number of metrics. Start by familiarizing yourself with the types of metrics in the database: https://data.cityofchicago.org/api/assets/AAD41A13-BE8A-4E67-B1F5-86E711E09D5F?download=true

It is important to note that as a Data Analyst/ Scientist, your major responsibility is to extract insights from data and provide solutions to problems using data driven informed decision making process. Here, we will connect to the database by loading the ipython-sql extension and establish a magic sql connection with the sqllite database and import the python libraries needed for the project.


In many cases the dataset to be analyzed is available as a .CSV (comma separated values) file, perhaps on the internet. To analyze the data
using SQL, it first needs to be stored in the database.
We will first read the csv files from the given url into pandas dataframes
Next we will be using the df.to_sql() function to convert each csv file to a table in sqlite with the csv data loaded in it.

See the attached file for some insights drawn from the datasets using SQL and Python scripts. Remember that your insights are based on the organization problems you intend to solve and your queries/scripts may differ from mine but the basics are the same for querying columns and data manipulation.


Summary
In this project you learned how to work with a real word dataset using SQL and Python. You learned how to query columns with spaces or special characters in their names and with mixed case names. You also used built in database functions and practiced how to sort, limit, and order result sets, as well as used sub-queries and worked with multiple tables.




