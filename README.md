# Company Sales Data Analysis

## Overview
This Python script analyzes company sales data from `company_sales_data.csv` and automobile data from `automobile_data.csv`. It performs data visualization, statistical analysis, and NumPy array manipulation to gain insights into sales trends, product distribution, and automobile data.

## Requirements
Ensure you have the following Python libraries installed:

```sh
pip install pandas numpy matplotlib
```

## Features

### 1. Load and Display Company Sales Data
- Reads `company_sales_data.csv`
- Displays the first few rows of data
- Plots total profit by month

### 2. Analyze Total Profit and Toothpaste Sales
- Plots total profit over months
- Highlights the month with maximum profit
- Compares total profit with toothpaste sales using a scatter plot

### 3. Product Sales Distribution
- Computes total sales for each product category
- Visualizes sales distribution using a pie chart
- Plots sales trends for all products over months

### 4. Automobile Data Analysis
- Reads `automobile_data.csv`
- Counts the total number of cars for each company
- Visualizes the car count data using a bar chart

### 5. NumPy Array Manipulation
- Demonstrates array manipulation:
  - Deletes a column from a NumPy array
  - Inserts a new column
- Visualizes the transformations using matplotlib

## Usage
Run the script using Python:

```sh
python sales_analysis.py
```

Ensure that `company_sales_data.csv` and `automobile_data.csv` are in the same directory as the script.

## Output
The script generates multiple visualizations, including:
- Line plots for sales trends
- Scatter plots for product sales comparison
- Pie charts for product sales distribution
- Bar charts for automobile data
- Matrix plots for NumPy array operations

<img width="468" alt="image" src="https://github.com/user-attachments/assets/1d51d2e2-9d94-4154-8a65-a063338b98bf" />
<img width="470" alt="image" src="https://github.com/user-attachments/assets/3fce5329-760a-43e3-9fdb-de912ef855a3" />
<img width="412" alt="image" src="https://github.com/user-attachments/assets/6f2a1d7e-f45e-4398-92d2-74b83b208c9b" />
<img width="471" alt="image" src="https://github.com/user-attachments/assets/aca376d8-3d42-4f66-9014-33f3bd24ba49" />
<img width="468" alt="image" src="https://github.com/user-attachments/assets/6434cb92-4f31-4402-b26f-600430a32c24" />
<img width="412" alt="image" src="https://github.com/user-attachments/assets/cc820cc0-70eb-4d44-8da3-34ea09d757e6" />

## Author
Developed by Jeremy Martinez-Quinones.

## License
This project is licensed under the MIT License.
