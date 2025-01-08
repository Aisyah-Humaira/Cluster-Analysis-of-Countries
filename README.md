# Cluster Analysis of Countries

## Project Domain
The Project Domain focuses on the humanitarian mission of HELP International, a non-governmental organization dedicated to combating poverty and providing essential aid and services in underdeveloped countries, especially during natural disasters and emergencies. The organization has successfully raised $10 million in funds and seeks to strategically allocate these resources to the countries most in need. The project aims to categorize countries based on socio-economic and health factors, which are critical determinants of national development. By analyzing indicators such as child mortality, GDP per capita, health expenditure, and life expectancy, the project will help identify the countries with the greatest need for assistance, ensuring the efficient and impactful use of the funds.

## Problem Statements
The primary challenge faced by the CEO of HELP International is determining which countries most urgently require assistance from the allocated $10 million. To make an informed decision, it is necessary to categorize countries based on socio-economic and health factors that influence overall national development. A clear understanding of these factors will enable the CEO to strategically prioritize the allocation of aid to the countries with the highest needs.

## Scope
1. **Objective**: Categorise countries using socioeconomic and health data to determine aid allocation priorities.
2. **Analysis**: Focus on factors such as GDP per capita, income, child mortality, life expectancy, inflation, exports, health, and fertility.
3. **Main Outcome**: Split the country into two clusters based on the available data:
    - Cluster 0: Countries with high aid needs (low socioeconomic and health indicators).
    - Cluster 1: Countries with more developed economies (high socioeconomic and health indicators).
  
### *Preprocessing Data:*
- Imported the data and ensured there were no missing values.
- Checked descriptive statistics and removed outliers using boxplots.

### *Data Analysis:*
- Use scatter plots and heatmaps to understand correlations between features.
- Identify significant correlations, such as between GDP per capita and income.

### *Clustering:*
- Standardised the features using StandardScaler.
- Determining the optimal number of clusters using the Silhouette Score method, which shows that 2 clusters are the best with a score of 0.304.
- Perform clustering using the K-Means algorithm with $n = 2 $

### *Cluster Profiling:*
- Calculating the average value of each feature in the cluster to understand its characteristics.
- Visualisation of clustering results.

## Conclusions
Countries in Cluster 0 were analyzed as most in need of assistance because:
- *Health Indicators*: High child mortality and low other health indicators indicate an urgent need for improvement in the health system.
- *Economic Indicators*: Low income and GDP per capita indicate a need for economic development and improved living standards.
- *Social Conditions*: High inflation and fertility rates may indicate additional challenges that require attention.
 
