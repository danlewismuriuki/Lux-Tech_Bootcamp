Weather Data Analysis and SQL Operations
Welcome to the Weather Data Analysis project! This project focuses on exploring and analyzing weather data using both Python and SQL. The dataset we're working with includes various weather metrics such as temperature, humidity, wind speed, and visibility.

What We Did
Python Data Analysis
Loading and Exploring Data

We started by loading the weather data from a CSV file into a Pandas DataFrame.
We took a look at the first few rows and the overall shape of the data to get a feel for what we’re working with.
Column Handling

To make things clearer, we renamed the 'Weather' column to 'Weather_Condition'.
We cleaned up the data by stripping any extra spaces and converting all weather conditions to lowercase.
Data Analysis

We filtered out records where the weather was 'clear'.
We counted how many times the wind speed was exactly 4 km/hr.
We checked if there were any missing values in the dataset.
We calculated the average visibility across all records.
We found records where the wind speed was greater than 24 km/hr and visibility was exactly 25 km.
We looked for cases where the weather was clear, the relative humidity was above 50, or visibility was over 40.
We counted how many records had 'snow' as part of the weather condition.
Aggregation

We grouped the data by 'Weather_Condition' and calculated the average values for various numeric columns to see how conditions affect the metrics.
SQL Operations
Setting Up the Database

We created a new database and imported our weather data CSV file into a table.
We managed the table schema and fixed any issues related to column names and data types.
Querying Data

We wrote SQL queries to filter records based on weather conditions and numeric values.
We renamed columns in the SQL table and ran queries to count records meeting specific criteria.
Managing SQL Files

We shared our SQL scripts and committed them to GitHub to keep track of changes and collaborate effectively.
How to Get Started
To follow along with the analysis, here’s what you need to do:

Install Dependencies

Make sure you have Python and MySQL installed on your system.
Install the necessary Python packages using pip:
bash
Copy code
pip install pandas numpy mysql-connector-python
Run the Python Script

Place your CSV file in the right location and make sure it’s named correctly.
Execute the Python script to perform the data analysis:
bash
Copy code
python your_script.py
Set Up MySQL

Create and configure your MySQL database.
Import the SQL file into your MySQL instance to set up the tables and load the data.
A Few Notes
Always check your column names and data types to avoid issues while manipulating data.
This project covers a variety of data operations, including filtering, aggregation, and counting, to extract useful insights from our weather dataset.
Feel free to tweak the analysis as needed and explore the data further!
