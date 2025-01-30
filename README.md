# London Boroughs House Price Analysis

This project involves the analysis of average house prices across different London boroughs over the past two decades. The primary goal is to identify which boroughs have seen the greatest house price increases, based on data from the year 1995 through 2018. The analysis also includes visualizing trends and calculating ratios to compare the growth rates of different boroughs.

## Table of Contents

1. [Introduction](#introduction)
2. [Data Description](#data-description)
3. [Steps Involved](#steps-involved)
4. [Key Findings](#key-findings)
5. [Visualizations](#visualizations)
6. [Installation](#installation)
7. [License](#license)

## Introduction

This project explores housing price trends across London boroughs, focusing on identifying areas that have seen the most significant increases in house prices over a 20-year period. The analysis uses historical data on average house prices in each borough from 1995 to 2018.

## Data Description

The dataset contains the following columns:

- `London_Borough`: The name of the London borough.
- `ID`: A unique identifier for each borough.
- `Month`: The date of the recorded price.
- `Average_price`: The average house price for that month.
- `Year`: The extracted year from the `Month` column for easier analysis.

### Example of data:

| London_Borough     | Year | Average_price |
|--------------------|------|---------------|
| Barking & Dagenham | 1995 | 51817.97      |
| Barking & Dagenham | 1996 | 51718.19      |
| Barking & Dagenham | 1997 | 55974.26      |
| Barking & Dagenham | 1998 | 60285.82      |
| Barking & Dagenham | 1999 | 65320.93      |

## Steps Involved

1. **Data Loading & Cleaning**: The data was loaded, and any missing values were removed to ensure accuracy in the analysis.
2. **Data Transformation**: The `Month` column was used to extract the year, which was added as a new column (`Year`).
3. **Price Growth Calculation**: The ratio of house prices in 2018 compared to 1995 was calculated to determine the growth rate for each borough.
4. **Data Visualization**: Bar plots were generated to visualize the top 15 boroughs with the highest house price increase ratios.

## Key Findings

- **Hackney** has the highest house price increase ratio, with a value of 6.32 in 2018.
- Other notable boroughs with significant growth include **Waltham Forest**, **Southwark**, **Lewisham**, and **City of London**.
- **Barking & Dagenham** saw an increase ratio of 4.95, while **Brent** had a ratio of 4.71.

## Visualizations

- A bar chart was created to visualize the top 15 London boroughs with the highest house price growth in 2018


  ![Screenshot 2025-01-29 at 8 31 57 PM](https://github.com/user-attachments/assets/2f973b5e-593e-4f81-bad2-b07209ce3649)
  

## Installation

To run this analysis on your own system, you will need the following Python packages:

- pandas
- matplotlib
- warnings (for FutureWarnings)

You can install the required libraries using pip:

```bash
pip install pandas matplotlib
