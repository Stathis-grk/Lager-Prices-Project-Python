# Lager-Prices-Project-Python

## Overview
This project analyzes historical lager beer price trends in Germany, France, and Greece from December 2014 to March 2025. The analysis includes data cleaning, exploratory data analysis, statistical calculations, and visualization of price trends over time.

## Project Structure
The analysis is organized in a Jupyter Notebook (Lager Prices Project.ipynb) with the following sections:

## Data Import and Initial Exploration
### Import necessary libraries (pandas, numpy, matplotlib) and Load and display the dataset
<img width="1045" height="743" alt="Στιγμιότυπο οθόνης 2025-09-17 140917" src="https://github.com/user-attachments/assets/d54b17c3-ea0f-4124-9fd8-c93b575524c5" />



### Basic dataset information and statistics
<img width="1335" height="1156" alt="image" src="https://github.com/user-attachments/assets/4d925f13-6e4b-4aa1-b46e-4b67dccf4cab" />



## Data Cleaning and Preparation
### Convert TIME column to datetime format
<img width="1529" height="1091" alt="image" src="https://github.com/user-attachments/assets/b0969120-6eba-4994-b63a-92f8b930ec08" />



### Check for missing values and duplicates
<img width="1235" height="788" alt="image" src="https://github.com/user-attachments/assets/6c6f5da0-0165-423b-9d40-457dfb1f8eeb" />

## Exploratory Data Analysis
### Value counts and unique values for Greece prices
<img width="1223" height="775" alt="image" src="https://github.com/user-attachments/assets/bc7610a3-09be-40f1-85d2-e62669f61043" />



### Correlation analysis between countries and Calculation of percentage changes for Germany, France and Greece prices
<img width="1240" height="1252" alt="image" src="https://github.com/user-attachments/assets/1bca40fe-36f2-4749-a99a-6da7ac7b8e14" />



## Visualization
### Time series comparison of lager prices across all three countries
<img width="1120" height="710" alt="Στιγμιότυπο οθόνης 2025-09-17 142319" src="https://github.com/user-attachments/assets/ca2b1a16-5b9c-4ae4-a423-b7551b98f6b4" />


# Key Findings
## Statistical Summary
<img width="768" height="267" alt="image" src="https://github.com/user-attachments/assets/762c817c-ac66-48d5-94c0-adda4dbd2e95" />


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
