
# Data Mining Project: Adult Mortality Rate Analysis (2019-2021)

## Overview

This project explores the application of data mining techniques to analyze global Adult Mortality Rates from 2019 to 2021. The primary objective is to enhance market segmentation and risk assessment strategies for a global health insurance provider by identifying patterns in health outcomes, economic status, and demographic factors across different countries.

## Table of Contents
- [Project Overview](#overview)
- [Data](#data)
- [Methods](#methods)
- [Results](#results)
- [Conclusion](#conclusion)
- [Installation](#installation)
- [Usage](#usage)
- [Contributors](#contributors)
- [License](#license)

## Data

The dataset used for this project includes the Adult Mortality Rate for various countries from 2019 to 2021. Key attributes include:
- **Countries**
- **Continent**
- **Average Population (thousands)**
- **Average GDP (Million $)**
- **Average GDP per Capita**
- **Average Health Expenditure ($)**
- **Development Level**
- **Adult Mortality Rate (AMR) per 1000 Adults (Male & Female)**
- **Average Crude Death Rate (CDR)**

## Methods

The project involves several data mining techniques:

1. **Data Preprocessing:**
   - Data Cleaning: Removing erroneous data and handling missing values.
   - Outlier Removal: Excluding outliers like Luxembourg and Qatar to avoid skewing the analysis.
   - Discretization: Grouping continuous variables like GDP per capita into 'low', 'medium', and 'high' categories.

2. **Clustering:**
   - Employed the k-means clustering algorithm to segment countries into groups based on health and economic indicators.
   - Utilized the Elbow Method to determine the optimal number of clusters.

3. **Classification:**
   - Applied multiple classification algorithms, including Decision Trees, Naive Bayes, IBk (k-nearest neighbors), and OneR, to predict mortality risk categories.
   - Performed cross-validation to assess the accuracy of each model.

## Results

- **Clustering:**
  - The analysis revealed four distinct clusters based on health and risk profiles, providing insights into regional health trends and economic conditions.
  
- **Classification:**
  - The Decision Tree model achieved the highest accuracy at 98.08%, followed by Naive Bayes (87.82%) and IBk (86.54%).

## Conclusion

The project successfully demonstrates the use of data mining techniques to derive actionable insights for market segmentation and risk assessment in the health insurance sector. The findings can guide the development of tailored insurance products and strategic marketing efforts based on regional health profiles and economic conditions.


## Contributors

- **Kyaw Zaww Linn** - Data Analyst
- **Group Members:**  
  - Nang Kaung Shan Kham  
  - Hpu Hpu Thant Sin  
  - Nyan Lin Htut  
