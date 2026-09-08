# Task 1 - BDA: Sample Superstore Data Analysis

## Project Description

This project performs basic data analysis and visualization on the Sample Superstore dataset using Python.

The project uses Pandas, NumPy, Matplotlib, and Seaborn for data analysis and visualization.

## Objectives

- Load the Sample Superstore dataset
- Explore the dataset
- Display basic information and statistics
- Convert Order Date and Ship Date into datetime format
- Calculate delivery days
- Find unique product categories
- Check for missing values
- Calculate sales by category
- Visualize sales by category
- Visualize the sales distribution

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab / Jupyter Notebook

## Data Analysis

### 1. Data Loading

The Sample Superstore dataset is loaded using Pandas.

### 2. Data Exploration

The following functions are used to understand the dataset:

- `df.head()`
- `df.info()`
- `df.describe()`

### 3. Date Conversion

The `Order Date` and `Ship Date` columns are converted into datetime format.

### 4. Delivery Days

Delivery days are calculated using the difference between Ship Date and Order Date.

### 5. Category Analysis

The unique values in the `Category` column are displayed.

### 6. Missing Value Check

The project checks for missing values using:

```python
df.isnull().sum()
