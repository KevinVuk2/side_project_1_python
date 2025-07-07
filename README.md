# This is a  Project I did while studying Data Analysis

# NYC Public School SAT Performance Analysis
This project performs an exploratory data analysis on a dataset of SAT scores for public high schools in New York City. The analysis aims to answer key questions about school performance, identify top-performing schools, and understand score variations across different boroughs.
Analysis Overview
The notebook uses the pandas library to manipulate and analyze the schools.csv dataset to answer three main questions:
1. Which schools have the best math scores?
The notebook filters for schools where the average math score is 640 or higher (at least 80% of the maximum possible score of 800).
The resulting list of schools is sorted by their math scores and saved to a new file, best_math_schools.csv.
2. What are the top 10 schools based on combined SAT scores?
A total_SAT score is calculated for each school by summing the average scores for the math, reading, and writing sections.
The schools are then ranked by this combined score to identify the overall top 10 performing schools in NYC.
3. Which borough has the largest variation in SAT scores?
The data is grouped by borough to calculate summary statistics, including the count of schools, the average SAT score, and the standard deviation.
The borough with the highest standard deviation is identified, highlighting the area with the most significant disparity in school performance.

# Technologies Used
- Python
- pandas
