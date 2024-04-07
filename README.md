# 911 Calls Analysis Capstone Project
This project is part of the "Python for Data Science and Machine Learning Bootcamp" on Udemy.  
This capstone project involves analyzing 911 call data obtained from Kaggle. The dataset contains various fields such as latitude, longitude, description of the emergency call, zip code, title, timestamp, township, address, and a dummy variable.

## Data and Setup
* Importing Libraries: The project utilizes libraries such as NumPy, Pandas, Matplotlib, and Seaborn for data analysis and visualization.
* Reading Data: The dataset is read into a Pandas DataFrame named df.
* Basic Data Exploration: Various methods like info() and head() are used to explore the basic structure and content of the DataFrame.

## Analysis Highlights
* Creating New Features: The project creates a new column called "Reason" by extracting reasons/departments from the title column.
* Time Analysis: Analysis of time-related information involves converting timestamp strings to DateTime objects and creating new columns for hour, month, and day of the week.
* Visualization: Seaborn is used to visualize the distribution of 911 calls based on reasons, day of the week, month, and hour.
* Missing Data Handling: Techniques like grouping and aggregation are used to handle missing months in the data.
* Heatmaps and Clustermaps: Heatmaps and clustermaps are generated to visualize the frequency of 911 calls based on hours and days of the week or months.

## Conclusion
This project demonstrates a comprehensive analysis of 911 call data, providing insights into the distribution of emergency calls over time, reasons, and locations. It showcases various techniques in data manipulation, visualization, and interpretation using Python and data science tools.
