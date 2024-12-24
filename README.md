Data Analyst Intern Assignment

Objective

The objective of this project is to analyze datasets related to user behavior, cooking preferences, and order trends to derive insights and create visualizations. This assignment is designed for a Data Analyst Intern position.

Datasets Used

This project uses the following datasets:

  UserDetails.csv: Contains user demographic and preference information.
  
  CookingSessions.csv: Tracks cooking sessions conducted by users.
  
  OrderDetails.csv: Records user orders and related details.

Steps Performed

1. Loading Data

  The datasets were loaded using pandas from an Excel file.
  
  Initial inspection of the datasets was conducted using .head() to view the first few rows.

2. Checking and Cleaning Data

  Missing Values: Identified using .isnull().sum().
  
  Duplicates: Removed using .drop_duplicates().
  
  Date Columns: Converted to datetime format using pd.to_datetime().
  
  Ratings: Missing ratings were filled with the mean rating.
  
  String Trimming: Leading and trailing whitespace in categorical columns was stripped.

3. Merging Datasets

  The datasets were merged into a comprehensive dataset:
  
  UserDetails was merged with CookingSessions on User ID.
  
  The resulting dataset was merged with OrderDetails on User ID and Session ID.
  
  Overlapping column names were resolved by renaming or dropping unnecessary columns.

4. Analysis and Insights

  Correlation Analysis:
  
  Correlation between total orders and session ratings was computed.
  
  Popular Dishes:
  
  The top 10 popular dishes were identified based on frequency.
  
  A bar plot visualized the popularity of these dishes.
  
  Demographic Insights:
  
  Users were segmented by age groups (e.g., 18-25, 26-35).
  
  Average orders per age group were analyzed and visualized using a bar chart.
  
  Cooking Session vs. Order Analysis:
  
  A scatter plot visualized the relationship between session ratings and order amounts.

5. Data Export and Documentation

  The cleaned and merged dataset was saved as final_data.csv.
  
  A summary of insights and data analysis report was written to summary and report.txt.

Visualizations

    Top 10 Popular Dishes: A bar plot showing the frequency of the top dishes.
    
    Age Group Analysis: A bar chart displaying average orders by age group.
    
    Cooking Session Ratings vs. Order Amount: A scatter plot illustrating the relationship between cooking session ratings and order amounts.

Files

    final_data.csv: Contains the cleaned and merged dataset.
    
    summary and report.txt: Summarizes key insights and findings and with a data analysis report having insights and recommendations.
    
    Python Script: Code used for data cleaning, merging, analysis, and visualization.

How to Run

    Place the datasets (Data Analyst Intern Assignment - Excel.xlsx) in the working directory.
    
    Run the Python script to execute all steps.
    
    View the generated visualizations and the output files (final_data.csv and summary.txt).

Dependencies

Python 3.6+

    Libraries:
    
    pandas
    
    matplotlib
    
    seaborn

Insights

    Correlation between user engagement (session ratings) and order behavior was analyzed.
    
    Popular dishes and demographic factors influencing orders were identified.
    
    Visualizations provided actionable insights for business recommendations.

For any questions, please contact the author of this analysis.

aditya0112kumar@gmail.com
