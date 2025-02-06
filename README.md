**Project Title: US Accidents Exploratory Data Analysis (EDA)**
**Project Description**
This project focuses on analyzing a comprehensive dataset of road accidents in the United States to uncover patterns, trends, and factors contributing to accident severity. The dataset contains over 7.7 million records with 46 features, including details such as accident location, time, weather conditions, and severity. Using Python libraries like Pandas, NumPy, Matplotlib, and Seaborn, the project performs extensive data preprocessing, visualization, and exploratory data analysis (EDA) to extract meaningful insights.

**Objective**
The primary goal of this project is to:

Identify key factors influencing accident severity.

Analyze temporal and geographical trends in accidents.

Explore the impact of weather conditions on accident frequency and severity.

Provide actionable insights to improve road safety and reduce accidents.

**Tools and Technologies**
Programming Language: Python

**Libraries:**

Pandas: Data manipulation and analysis.

NumPy: Numerical computations.

Matplotlib and Seaborn: Data visualization.

Scikit-learn: Data preprocessing (e.g., encoding, scaling).

Data Source:  US Accidents Dataset (March 2023) from Kaggle.

**Key Steps Performed**
**Data Loading and Initial Exploration:**

Loaded the dataset and performed an initial check of its structure, size, and data types.

Identified missing values and outliers.

**Data Cleaning:**

Dropped irrelevant columns (e.g., ID, Country, Turning_Loop) and columns with high missing values (e.g., End_Lat, End_Lng, Precipitation(in)).

Filled missing numerical values with the median and categorical values with the mode.

**Feature Engineering:**

Extracted time-based features such as Hour, Day, Month, and Weekday from the Start_Time column.

Encoded categorical variables using Label Encoding and One-Hot Encoding.

Scaled numerical features like Temperature(F) and Humidity(%) using StandardScaler.

**Exploratory Data Analysis (EDA):**

Accident Severity Distribution: Analyzed the distribution of accident severity levels (Minor, Moderate, High, Extreme).

Temporal Analysis: Investigated hourly, daily, and monthly trends in accidents.

Geographical Analysis: Identified states and cities with the highest accident rates.

Weather Impact: Explored the relationship between weather conditions and accident severity.

Correlation Analysis: Examined correlations between numerical features like temperature, humidity, visibility, and wind speed.

Visualizations:

Created visualizations such as bar plots, histograms, scatter plots, and heatmaps to illustrate key findings.

**Key Insights**
Accident Severity:

79.67% of accidents are Moderate, while Extreme accidents account for only 2.65%.

**Temporal Trends:**

Accidents peak during rush hours (7-9 AM and 4-6 PM).

Higher accident rates are observed in winter months due to adverse weather conditions.

**Geographical Trends:**

California (CA), Florida (FL), and Texas (TX) have the highest number of accidents.

Urban areas and highways are accident hotspots.

**Weather Impact:**

Most accidents occur during clear weather, but severe accidents are more likely during rainy or foggy conditions.

Low visibility and high wind speeds are correlated with higher accident severity.

**Correlation Analysis:**

Temperature and Humidity show a moderate negative correlation.

Visibility decreases with higher humidity, indicating foggy conditions.

**Challenges Faced**
Handling Missing Data: A significant portion of the dataset had missing values, especially in columns like End_Lat, End_Lng, and Precipitation(in).

Data Size: The dataset is large (7.7 million rows), requiring efficient memory management and preprocessing techniques.

Feature Engineering: Extracting meaningful features from raw data, such as time-based features, was crucial for analysis.

**Future Work**
**Predictive Modeling:**

Build machine learning models to predict accident severity based on features like weather, time, and location.

**Advanced Visualizations:**

Create interactive dashboards using tools like Power BI or Tableau for better data storytelling.

**Geospatial Analysis:**

Use geospatial libraries like Folium or Plotly to create heatmaps of accident hotspots.

**Real-Time Analysis:**

Develop a real-time accident monitoring system using streaming data.

**Conclusion**
This project provides a comprehensive analysis of road accidents in the United States, highlighting key trends and factors contributing to accident severity. The insights gained can help policymakers, urban planners, and transportation authorities take proactive measures to improve road safety and reduce accidents.



