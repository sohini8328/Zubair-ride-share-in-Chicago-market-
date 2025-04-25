# Business Prospect Analysis for Zubair Ride Share in Chicago Market

The objective of this project is to analyze how weather conditions impact the ride share business. The insights gained will help Zubair Ride Share Company make informed decisions regarding their business plan, budget allocation, and staffing requirements. This analysis focuses on understanding customer behavior, service demand, and operational adjustments during different weather conditions in Chicago.

## Process
1. **Data Collection**: 
   - Weather data for Chicago was parsed using Beautiful Soup from a web source.
   - Datasets included cab companies, neighborhoods, and trips.

2. **Data Cleaning & Preprocessing**:
   - Duplicated data in the trips dataset was identified and dropped (minimal duplicates).
   - Dataframes were standardized and structured for analysis.

3. **Exploratory Data Analysis (EDA)**:
   - Key observations:
     - *Flash Cab* had the highest number of rides, particularly ending in the Loop neighborhood at 4 PM on Nov 25.
     - *Taxi Affiliation Services* ranked second with drop-offs in River North at 2 PM on the same day.
   - Visualization tools like histograms and correlation analysis helped uncover patterns in trips and neighborhoods.

4. **Hypothesis Testing**:
   - **Hypothesis 1**:
     - H0: The duration of rides on rainy and non-rainy days is the same.
     - H1: The duration of rides on rainy and non-rainy days differs.
     - Result: H0 was rejected, indicating a significant difference in ride duration due to weather conditions.
   - **Hypothesis 2**:
     - H0: The duration of rides on rainy Saturdays and other Saturdays is the same.
     - H1: The duration of rides on rainy Saturdays and other Saturdays differs.
     - Result: H0 was rejected, confirming differences in ride durations based on weather conditions.

## Key Findings
1. **Cab Company Insights**:
   - *Flash Cab* is the most popular, with the highest trips. Its success may be attributed to competitive pricing or superior service.
   - *Blue Ribbon Taxi Association* had the lowest trips among the top 10 companies.
2. **Neighborhood Insights**:
   - The *Loop* neighborhood had the highest number of drop-offs, indicating high usage in this area.
   - *Sheffield & DePaul* was the least popular drop-off location.
3. **Weather Impact**:
   - Rainy weather increased ride durations significantly. For example:
     - On rainy days, a driver completing 2 rides in normal weather might manage only 1 ride.
   - Rainy Saturdays also showed longer travel times compared to other Saturdays, likely due to increased congestion and reduced visibility.

This analysis highlights the impact of weather on ride durations and demand. The findings suggest:
- Adapting staffing strategies during bad weather to meet increased demand.
- Optimizing routes and service areas to minimize delays.
- Leveraging popular neighborhoods like the Loop for targeted promotions.
These insights can guide Zubair Ride Share in refining their business strategy to better serve the Chicago market under varying weather conditions.
Use BLANK_README.md to get started Build With: This is the list of the libraries used by me to run this project were pandas,numpy, matplotlib.pyplot, requests, ttest_ind and stats.

Getting Started: This is an example of how you may give instructions on setting up your project locally. To get a local copy up and running follow these simple steps. Prequisites: This is an example of software and how to install them. VS Code How to Run Clone this repository: https://github.com/sohini8328/Zubair-ride-share-in-Chicago-market-.git 

