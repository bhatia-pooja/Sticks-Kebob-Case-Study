# Sticks Kebob Customer Segmentation Analysis

## Overview

This repository contains a comprehensive analysis of customer and non-customer segmentation for Sticks Kebob, a restaurant chain specializing in kebobs and related dishes. The analysis leverages survey data to identify distinct customer groups, understand their behaviors and preferences, and provide actionable insights for improving marketing strategies and customer engagement.

## Contents

- **Data Sources**: The repository includes datasets used in the analysis, including cleaned customer survey data, as well as additional segmentation data.
- **Analysis Code**: Python scripts for data preprocessing, clustering (both K-Means and Hierarchical), and the creation of visualizations.
- **Findings and Reports**: A detailed report of the findings, including segment profiles, recommendations, and suggested marketing strategies.

## Data Description

The analysis primarily uses survey data collected from both customers and non-customers of Sticks Kebob. Key variables include:

- **Demographics**: Age, Gender, Profession, Income
- **Behavioral Attributes**: Frequency of visits, Importance of restaurant attributes (e.g., convenience, value, healthiness)
- **Attitudinal Questions**: Planning habits, spending control, importance of local products, health consciousness

### Key Questions Analyzed:
1. **Customer Profiling**: What is the typical profile of a Sticks Kebob customer and non-customer?
2. **Segmentation Analysis**: How can we segment the customer base to target marketing more effectively?
3. **Behavioral Insights**: What are the key differences between customers and non-customers in terms of their behavior and preferences?

## Initial Analysis: Characterizing a Sticks Kebob Customer

### Customer Profile

Based on the survey data, the typical Sticks Kebob customer can be characterized as follows:

- **Profession**: Predominantly Business Professionals (Profession 7) and Educators (Profession 5).
- **Household Composition**: Typically from households with one or two children, and generally falls into household types 1 or 2.
- **Visit Frequency**: Customers visit Sticks Kebob frequently, especially during weekends and after-school hours.
- **Important Attributes**: The most valued attributes include community involvement, ambiance, and variety. Customers also place significant importance on convenience and staff friendliness.
- **Perception of Sticks Kebob**: Customers generally perceive Sticks Kebob positively, particularly in terms of value for money, convenience, and ambiance.

## K-Means Cluster Analysis

### Methodology

To further understand the customer base, K-Means clustering was performed on the cleaned survey data. The analysis involved the following steps:

- **Data Standardization**: Variables were standardized to ensure equal weighting during clustering.
- **Cluster Evaluation**: The optimal number of clusters was determined using the Sum of Squared Errors (SSE) and Silhouette Coefficient.
- **Cluster Profiling**: Each cluster was profiled to identify key characteristics and differences among the customer segments.

### Findings

The K-Means analysis revealed distinct customer segments, each with unique behaviors and preferences:

- **Cluster 1**: Composed mainly of frequent visitors who highly value convenience and ambiance. This group is generally more loyal and consistent in their patronage.
- **Cluster 2**: Includes customers with moderate visit frequency but high spending behavior. This segment places significant importance on health-conscious options and community involvement.

These segments provide a basis for targeted marketing efforts, allowing Sticks Kebob to tailor its offerings and promotions to different customer needs.

## Segmentation Analysis

### Data Preprocessing

- **Cleaning**: Handled missing data, standardized variables for clustering.
- **Segmentation**: Used both K-Means and Hierarchical clustering techniques to segment the data.
- **Visualization**: Created various charts to visually represent the findings.

### Hierarchical Clustering

Hierarchical clustering was performed separately for customers and non-customers, resulting in four distinct segments. These segments were then analyzed and profiled to provide insights into their characteristics and potential marketing strategies.

### Segment Profiles

#### Non-Customers:

- **Segment 0**: Struggles with spending control; moderately values local products and health.
- **Segment 1**: More balanced in planning and spending; moderate concern for local products and health.

#### Customers:

- **Segment 0**: Low planning, high spending issues; moderate interest in local products and health.
- **Segment 1**: More stable, moderate values across planning, spending, and health consciousness.

## Recommendations

### Targeted Marketing Strategies

1. **For Non-Customers**:
   - **Segment 0**: Focus on value-driven promotions that help manage spending.
   - **Segment 1**: Highlight local products and health benefits in marketing to convert them into customers.

2. **For Customers**:
   - **Segment 0**: Introduce promotions that encourage healthier eating and better spending habits.
   - **Segment 1**: Reinforce loyalty through programs that align with their moderate preferences.

### Future Research

Further analysis could explore additional segmentation variables, such as frequency of visits and satisfaction levels, to refine the understanding of customer behavior. Additionally, tracking changes in customer behavior over time could help in adapting marketing strategies more dynamically.

## Conclusion

This analysis provides a comprehensive understanding of the Sticks Kebob customer base, offering valuable insights that can be used to enhance marketing efforts, improve customer retention, and increase conversion rates. The findings serve as a foundation for data-driven decision-making in customer relationship management and marketing strategy development.
