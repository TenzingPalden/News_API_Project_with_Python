# News_API_Python_practice

This project is to practice and understand the utilization of API in how data is sent and transformed with Python. 

## Objective

The primary goal of this project is to demonstrate how to retrieve data from an API, transform it into a structured format, and analyze it using Python.

## Python Script Overview

The provided Python script performs the following tasks:

1. Imports necessary libraries: `requests`, `pandas`, and `csv`.
2. Creates a list with 47 numbers to use as a counter for the dataframe.
3. Creates a data frame with a single column titled "Title".
4. Requests specific information from the News API using an API key variable and converts the response into a dictionary.
5. Iterates through the dictionary to add the titles to the dataframe under the column "Titles".
6. Adds additional columns to the dataframe, including "Position on chart Count", "Word Count", and "Character Count".
7. Saves the dataframe to a CSV file without the index.
8. Calculates and saves the averages of the respective columns into their own variables.
9. Prints the results of the averages of the columns.


## Future Improvements

Potential future enhancements for this project include:
- Incorporating more advanced data analysis techniques.
- Exploring additional APIs for diverse data sources.
- Implementing visualization of the analyzed data for better insights.
