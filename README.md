# Lager-Prices-Project-Python

## Overview
This project analyzes historical lager beer price trends in Germany, France, and Greece from December 2014 to March 2025. The analysis includes data cleaning, exploratory data analysis, statistical calculations, and visualization of price trends over time.

## Project Structure
The analysis is organized in a Jupyter Notebook (Lager Prices Project.ipynb) with the following sections:

## Data Import and Initial Exploration
#### Import necessary libraries (pandas, numpy, matplotlib) and Load and display the dataset
<img width="2513" height="742" alt="image" src="https://github.com/user-attachments/assets/1015cb54-24a4-4149-b625-887d45b70a62" />

#### Basic dataset information and statistics
<img width="2502" height="1156" alt="image" src="https://github.com/user-attachments/assets/9d6c15eb-139a-4967-9e44-93717855f554" />

## Data Cleaning and Preparation
#### Convert TIME column to datetime format
<img width="2525" height="1091" alt="image" src="https://github.com/user-attachments/assets/7b07fc87-bd92-47a3-b576-5d832ee37c0d" />

#### Check for missing values and duplicates
<img width="2521" height="787" alt="image" src="https://github.com/user-attachments/assets/f4b20978-4069-4ef4-98ce-5887f46435b6" />

## Exploratory Data Analysis
#### Value counts and unique values for Greece prices
<img width="2481" height="775" alt="image" src="https://github.com/user-attachments/assets/cf45bea0-8fa9-4818-a402-95460257cfa2" />

#### Correlation analysis between countries and Calculation of percentage returns for Germany prices
<img width="2475" height="1250" alt="image" src="https://github.com/user-attachments/assets/5fdc6e8b-051a-4dcf-9e53-b6310bfedacb" />

## Visualization
#### Time series comparison of lager prices across all three countries
<img width="1120" height="710" alt="image" src="https://github.com/user-attachments/assets/780fb10d-59e2-4092-9999-d01def26a76e" />

# Key Findings
## Correlation Analysis
Strong positive correlations exist between all countries:

Germany-France: 0.990

Germany-Greece: 0.934

France-Greece: 0.930

## Price Trends Visualization
### The visualization shows:

Germany (red line): Highest volatility with significant price increases over time

France (yellow line): Moderate price increases with less volatility

Greece (blue line): Highest overall prices with substantial fluctuations
