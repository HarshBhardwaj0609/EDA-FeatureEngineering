This project performs Exploratory Data Analysis (EDA) and Feature Engineering on the Google Play Store Apps Dataset to uncover trends in app popularity, user engagement, and market dynamics. 
The dataset contains 10,841 apps with 13 features, including Category, Rating, Installs, Size, and Price.

Technologies Used:
 Python (Pandas, NumPy, Matplotlib, Seaborn)
 Jupyter Notebook
 Data Cleaning & Feature Engineering Techniques
 
Visualizations:
 Bar charts (Category distribution).
 Histograms (Rating distribution).
 Scatter plots (Installs vs. Ratings).
 Time-series trends (App updates over years).

Objective:
 Clean and preprocess raw data for analysis.
 Extract meaningful insights about app performance.
 Engineer new features to enhance dataset usability.
 Visualize trends in ratings, installs, pricing, and categories.

Key Steps:
 1. Data Cleaning:
    Handled missing values in Rating, Size, and Content Rating.
    Removed duplicate entries (1,181 duplicates dropped).
    Cleaned and converted:
         Size (e.g., "19M" → 19000.0).
         Installs (e.g., "10,000+" → 10000).
         Price (e.g., "$4.99" → 4.99).
2. Feature Engineering:
   Extracted Day, Month, Year from Last Updated.
   Processed categorical data (Category, Type, Content Rating).
   Analyzed app genres and their popularity.
   
4. Exploratory Data Analysis (EDA):
   Top Categories: Family, Games, Tools.
   Rating Distribution: Mean ~4.19, with anomalies (max: 19).
   Installs vs. Ratings: High-install apps tend to have better ratings.
   Free vs. Paid Apps: 92.6% apps are free.
   Last Update Trends: Most updates occurred in 2018.
