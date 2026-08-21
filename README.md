# Automobile Exploratory Data Analysis

## About the Project

This project is an exploratory data analysis of an automobile dataset. The goal is to understand the data, clean it properly, identify useful patterns, and explore how different vehicle features are related to price and fuel efficiency.

The analysis was carried out using Python and commonly used data analysis and visualization libraries.

## What I Worked On

In this project, I worked through the following steps:

- Loaded and inspected the automobile dataset.
- Checked the structure, columns, and data types.
- Identified missing values and replaced `?` values with `NaN`.
- Checked the dataset for duplicate records.
- Analyzed missing values across different columns.
- Converted selected columns to appropriate numerical data types.
- Explored categorical features such as fuel type, body style, drive wheels, and engine type.
- Created a new `comb_mpg` feature using city and highway mileage.
- Used basic statistical analysis to understand automobile prices.
- Used the IQR method to examine the price distribution.
- Grouped the data to compare mileage across different categories.
- Created visualizations to better understand relationships between automobile features.

## Dataset

The dataset contains information about 205 automobiles and includes details related to:

- Automobile make
- Fuel type
- Body style
- Drive wheels
- Engine type
- Engine size
- Horsepower
- Curb weight
- City mileage
- Highway mileage
- Price
- Other vehicle specifications

## Feature Engineering

I created a new column called `comb_mpg` to get a combined mileage value from city and highway mileage.
