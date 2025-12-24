🌍 World Happiness Report Analysis & Dashboard
📌 Project Overview

This project analyzes the World Happiness Report dataset to understand the key social and economic factors that influence happiness levels across countries.

Using Python, the project performs data cleaning, exploratory data analysis, correlation analysis, and basic validation through a train–test approach.
The final insights are presented through a Python-generated HTML dashboard for effective storytelling and visualization.

🎯 Objectives

Identify factors that contribute most to a country’s happiness score

Analyze relationships between happiness and socio-economic indicators

Validate analytical insights using a basic train–test approach

Present insights in an interactive and easy-to-understand dashboard

🛠 Tools & Technologies

Python

pandas, numpy – Data cleaning and transformation

matplotlib, seaborn – Data visualization

scikit-learn – Train–test split and basic validation

HTML – Dashboard presentation

📂 Dataset

Source: World Happiness Report

Data Includes:

Happiness Score

GDP per Capita

Social Support

Healthy Life Expectancy

Freedom to Make Life Choices

Generosity

Perceptions of Corruption

🧹 Data Cleaning & Preparation

Converted object-type numerical columns to numeric format using safe type conversion

Handled missing values using mean imputation

Standardized and validated feature columns

Prepared clean feature and target datasets for analysis and validation

📊 Exploratory Data Analysis

The following analyses were performed:

Distribution analysis of happiness scores

Correlation analysis between happiness score and socio-economic indicators

GDP per capita vs happiness score comparison

Regional comparison of happiness levels

Identification of top and bottom ranked countries by happiness score

🤖 Train–Test Validation

A basic train–test approach was applied to validate analytical insights.

Key socio-economic indicators were selected as features

The dataset was split into training and testing subsets

A simple regression-based approach was used to understand how well these factors explain variations in happiness scores

📌 Purpose:
This step was performed to support and validate analytical findings, not to build a production-level machine learning model.

Key takeaway:
Economic and social indicators together explain a significant portion of happiness variation, reinforcing the importance of health and social support beyond economic growth alone.

📈 Dashboard

The final insights are presented through a Python-generated HTML dashboard, allowing users to visually explore:

Happiness score distribution across countries

Relationships between GDP, health, and happiness

Regional trends and disparities

🔑 Key Insights

Countries with higher GDP per capita and strong social support tend to have higher happiness scores

Healthy life expectancy shows a strong positive correlation with happiness

Economic growth alone does not guarantee happiness without social and health factors

Significant regional disparities exist in happiness levels

📌 Conclusion

This project demonstrates how data-driven analysis can be used to understand complex social phenomena.
By combining Python-based analysis, validation techniques, and dashboard storytelling, the project highlights the key drivers of global happiness in a clear and interpretable manner.

🚀 Future Scope

Extend analysis with additional years of data

Explore country-level time series trends

Enhance dashboard interactivity
