# Segmentation at Sticks Kebob Shop

## Overview
This project focuses on analyzing customer data from Sticks Kebob Shop to gain insights into customer behavior, preferences, and demographics. The analysis involves data cleaning, exploratory data analysis (EDA), segmentation using both K-Means and hierarchical clustering, and making recommendations for expansion and targeted marketing strategies.

## Project Structure
The project is structured as follows:

1. **Data Cleaning**: Handling missing values, consolidating categories, and preparing the dataset for analysis.
2. **Exploratory Data Analysis (EDA)**: Visualizing demographic and behavioral data to understand customer segments.
3. **Customer Segmentation**: 
   - **K-Means Clustering**: Segmenting customers based on demographic and behavioral characteristics.
   - **Hierarchical Clustering**: Further analysis of non-customers to identify behavioral clusters and develop targeted marketing strategies.
4. **Final Recommendations**: Providing business recommendations for expansion and marketing strategies tailored to the identified customer and non-customer segments.

## Files
- **Sticks_Kebob_Customer_Data_Analysis.ipynb**: The main Jupyter notebook containing the entire analysis, from data cleaning to final recommendations.
- **Hierarchical Clustering.ipynb**: The Jupyter notebook focusing on hierarchical clustering analysis, particularly on non-customers, to develop targeted marketing strategies.

## Key Features of the Analysis
1. **Data Cleaning**:
   - Consolidation of professions and handling of missing data.
   - Renaming columns for better readability.

2. **Exploratory Data Analysis (EDA)**:
   - Visualization of demographic information such as age, income, and household type.
   - Behavioral analysis including customer preferences and competitor perceptions.

3. **Customer Segmentation**:
   - **K-Means Clustering**: Two primary customer segments were identified:
     - **"Practical Families"**: Younger, family-oriented customers with a focus on value and convenience.
     - **"Quality Seekers"**: Slightly older, quality-focused customers who value health, consistency, and community engagement.
   - **Hierarchical Clustering**: 
     - Focused on non-customers, identifying two key clusters:
       - **"Careful Planners"**: Individuals who plan carefully but struggle with spending control. They value local products and health benefits but are not highly focused on either.
       - **"Cautious Spenders"**: Less meticulous planners who exercise caution in spending. They are moderately concerned with local products and health benefits.

4. **Final Recommendations**:
   - **Expansion Plans**: Recommended Location D as the best option for expansion based on demographic fit and consumer spending potential.
   - **Targeted Marketing Strategies**:
     - **For "Practical Families"**: Focus on value-driven promotions and family-friendly options.
     - **For "Quality Seekers"**: Emphasize quality, health-conscious choices, and community involvement.
     - **For Non-Customers**:
       - **"Careful Planners"**: Use value-driven promotions and planning tools to attract this group.
       - **"Cautious Spenders"**: Offer convenience and quick rewards to appeal to their need for simplicity and control over spending.
